# manifest-updater-examples

## Workflows that use `Manifest.toml` files

| Workflow                                                                                             | Description                                                       |
| ---------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| [`.github/workflows/example_of_using_manifest.yml`](.github/workflows/example_of_using_manifest.yml) | Automatically select the manifest file based on the Julia version |

## Workflows that update `Manifest.toml` files

| Workflow                                                                                                     | Description                                                |
| ------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------- |
| [`.github/workflows/update_manifests_multiple_prs.yml`](.github/workflows/update_manifests_multiple_prs.yml) | Make multiple PRs (each PR updates a single manifest file) |
