# singularity builds for Actions

![Publish](https://github.com/eWaterCycle/singularity-versions/workflows/Publish/badge.svg)

This repository contains the code and scripts that we use to build singularity which is accessible through the [setup-singularity](https://github.com/eWaterCycle/setup-singularity) Action.

> Caution: this is prepared for and only permitted for use by setup-singularity action.

## Add new version

1. Start a [build workflow](), set version to for example `3.7.1`. Will create a release with compiled singularity
1. Start a [manifest update workflow]() to get updated `versions-manifest.json` file
1. Merge the generated PR
