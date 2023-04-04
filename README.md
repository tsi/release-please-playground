# Release Please Playground

![version](https://img.shields.io/static/v1?label=version&message=1.0.0&color=blue) <!-- x-release-please-version -->

Playing with [Release Please GitHub Action](https://github.com/marketplace/actions/release-please-action).

## Project Goals

1. Learning Release Please GitHub Action on a test repository.
2. Release PRs authored automatically by Release Please.
3. Project CHANGELOG.md generated from Conventional Commits.
4. Project GitHub Release with Semantic Versioning and version Git tags.

## Setup

Release Please workflow is configured
in [.github/workflows/release-please.yml](https://github.com/digrec/release-please-playground/blob/main/.github/workflows/release-please.yml)
file.

### Update Versions

To update versions in arbitrary files you need to use `x-release-please-version` annotation in form of a line comment
on the line where the version replacement needs to happen.

The arbitrary files that need version replacement must be listed using `extra-files` option in the workflow
configuration [file](.github/workflows/release-please.yml).

See [here](https://github.com/marketplace/actions/release-please-action#adding-additional-files) for more.
