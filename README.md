
A minimal example that uses github actions to upload files to a release.

When a release is published this triggers a github action.

The action runs within a container and creates files, these files are then
compressed and attached to the release as a downloadable zip file.

The attached_files.zip is then [downloadable from releases](https://github.com/Shimwell/example_upload_files_to_release/releases).

This is just a minimal example of the action and could be adapted to added files
that require more significant processes to generate (e.g. simulations, plots).
