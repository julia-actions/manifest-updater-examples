# manifest-updater-examples

This repository has examples of GitHub Actions workflows for automatically updating `Manifest.toml` files

## Update manifest files

| Workflow                                                                                                     | Description                                                |
| ------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------- |
| [`.github/workflows/update_manifests_multiple_prs.yml`](.github/workflows/update_manifests_multiple_prs.yml) | Make multiple PRs (each PR updates a single manifest file) |

## Automatically select the manifest file based on the Julia version

| Workflow                                                                                             | Description                                                       |
| ---------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| [`.github/workflows/example_of_using_manifest.yml`](.github/workflows/example_of_using_manifest.yml) | Automatically select the manifest file based on the Julia version |
