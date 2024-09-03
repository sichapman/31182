# 31182

## Current behavior

Only the commons-lang update goes into the minor versions group PR (branch renovate/all-packages) - the Flyway dependencies get put in their own (branch renovate/flyway). It seems that the packageRule coming in from the extends is being applied after the packagesRules in the inherited config, instead of before.

## Expected behavior

The minor version grouping to override the extended flyway version grouping, and one branch+PR to be created for all 3 dependencies.

## Link to the Renovate issue or Discussion

[Renovate discussion 31182](https://github.com/renovatebot/renovate/discussions/31182)
