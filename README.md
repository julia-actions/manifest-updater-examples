# manifest-updater-examples

This repository has examples of GitHub Actions workflows for automatically
updating `Manifest.toml` files for use with the Julia programming language.

## Update manifest files

| Status Badge                                          | Workflow File                                            | Description                                                       |
| ----------------------------------------------------- | -------------------------------------------------------- | ----------------------------------------------------------------- |
| [![Multiple PRs][multiple-prs-img]][multiple-prs-url] | [`multiple_prs.yml`](.github/workflows/multiple_prs.yml) | Make multiple PRs (each PR updates a single manifest file)        |
|                                                       |                                                          | Make a single PR that updates all of the manifest files           |

## Automatically select the manifest file based on the Julia version

| Status Badge                                          | Workflow File                                            | Description                                                       |
| ----------------------------------------------------- | -------------------------------------------------------- | ----------------------------------------------------------------- |
| [![Example][example-img]][example-url]                | [`example.yml`](.github/workflows/example.yml)           | Automatically select the manifest file based on the Julia version |

[multiple-prs-img]: https://github.com/julia-actions/manifest-updater-examples/actions/workflows/multiple_prs.yml/badge.svg "Multiple PRs"
[multiple-prs-url]: https://github.com/julia-actions/manifest-updater-examples/actions/workflows/multiple_prs.yml

[example-img]: https://github.com/julia-actions/manifest-updater-examples/actions/workflows/example.yml/badge.svg "Example"
[example-url]: https://github.com/julia-actions/manifest-updater-examples/actions/workflows/example.yml
