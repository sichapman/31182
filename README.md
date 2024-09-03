# 31182

You need to apply inherited-config.json as inherited config when executing Renovate.

## Current behavior

Two PRs get created - 1) the commons-lang update in the minor versions group PR (branch renovate/all-packages) and 2) the Flyway dependencies in their own (branch renovate/flyway).

## Expected behavior

The minor version grouping to override the extended flyway version grouping, and one branch+PR to be created for all 3 dependencies.

This expected behavior does happen if the config is placed in the repository renovate.json config instead of the inherited config.

## Link to the Renovate issue or Discussion

[Renovate discussion 31182](https://github.com/renovatebot/renovate/discussions/31182)
