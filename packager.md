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

- Ideally, clean code, not a huge unwieldy shell script

- Runs on free CI (circleci, ...)

- Uploads to github release page

- (Optional) Upload to curseforge and wowinterface

## Open questions

- Start from/contribute to [github.com/BigWigsMods/packager](https://github.com/BigWigsMods/packager)
(tried contributing but the maintainers are quite unfriendly and reject PRs and suggestions and even delete comments for no reason so probably a fork is a better starting point, [github.com/mooreatv/packager](https://github.com/mooreatv/packager) or [github.com/Wutname1/packager](https://github.com/Wutname1/packager))

- Is it possible that this is also ran user side and merged into the downloader?

## See also
The [downloader](downloader.md).

## Discuss!

Open a Github issue and discuss ! or on our [discord](https://discord.gg/t8msyQU) server.
