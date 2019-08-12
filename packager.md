# Packager

## Requirements

- Support from major modern sources
  - Number one priority GitHub
  - Also GitLabs, BitBucket
  - others?

- Automatically create classic and regular TOC/zip

- Compatibility or equivalence (converter) with curseforge packager:
  - `@project-version@`, `@project-abbreviated-hash@` variables
  - use git tag to label/version and categorize (alpha/beta/release)
  - support for external (lib) inlining
  - pattern ignore exclusion (e.g `*.bat`, `*.sh`...) and inclusion lists (e.g. `*.lua`)
    - recursively into dependencies (a lib dependency should alone specify files to be ignored/used)
  - ChangeLog
  - and possibly more from [curseforge's doc](https://authors.curseforge.com/knowledge-base/projects/3451-automatic-packaging)

- Clean code, not a huge spaghetti shell script

- Runs on free CI (circleci, ...)

- Uploads to github release page

- (Optional) Upload to curseforge and wowinterface


## Discuss!

Open a Github issue and discuss ! or on our [discord](https://discord.gg/t8msyQU) server.
