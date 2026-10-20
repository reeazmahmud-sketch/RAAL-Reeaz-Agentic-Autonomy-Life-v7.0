# Unified Project (Monorepo) Plan

All RAAL-related work lives in this single repository instead of separate projects.

## Layout

```text
src/raal/            Core runtime (planner, executor, audit, config)
projects/<name>/     Each related project (e.g. weaver-engine), self-contained
docs/                Shared documentation
governance/          Shared governance
architecture/        Shared architecture
```

## Migration steps

1. Inventory existing RAAL-related projects and their owners.
2. For each, import into `projects/<name>/` (preserve history with `git subtree add` or `git filter-repo`).
3. Keep a README per project describing scope, status, and how it plugs into the RAAL core.
4. Unify issues, CI, and releases in this repository; archive the old repositories with a pointer here.
5. Do not import secrets; scan before committing.

## Rules

- Projects follow the safety model in `docs/safety.md` and remain simulation-only unless governance approves otherwise.
- Documentation comes before major implementation (see CONTRIBUTING.md).
