# manifest-updater-examples

This repository has examples of GitHub Actions workflows for automatically
updating `Manifest.toml` files for use with the Julia programming language.

## Update manifest files

| Workflow                                                 | Description                                                       |
| -------------------------------------------------------- | ----------------------------------------------------------------- |
| [`multiple_prs.yml`](.github/workflows/multiple_prs.yml) | Make multiple PRs (each PR updates a single manifest file)        |

## Automatically select the manifest file based on the Julia version

| Workflow                                                 | Description                                                       |
| -------------------------------------------------------- | ----------------------------------------------------------------- |
| [`example.yml`](.github/workflows/example.yml)           | Automatically select the manifest file based on the Julia version |
