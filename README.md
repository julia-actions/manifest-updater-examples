# manifest-updater-examples

This repository has examples of GitHub Actions workflows for automatically
updating `Manifest.toml` files for use with the Julia programming language.

## Update manifest files

| Workflow File                                            | Description                                                       |
| -------------------------------------------------------- | ----------------------------------------------------------------- |
| [`multiple_prs.yml`](.github/workflows/multiple_prs.yml) | Make multiple PRs (each PR updates a single manifest file)        |

## Automatically select the manifest file based on the Julia version

| Workflow File                                            | Description                                                       |
| -------------------------------------------------------- | ----------------------------------------------------------------- |
| [`example.yml`](.github/workflows/example.yml)           | Automatically select the manifest file based on the Julia version |
