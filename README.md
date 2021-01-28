# singularity builds for Actions

![Generate singularity version](https://github.com/eWaterCycle/singularity-versions/workflows/Generate%20singularity%20version/badge.svg)
![Update manifest](https://github.com/eWaterCycle/singularity-versions/workflows/Update%20manifest/badge.svg)

This repository contains the code and scripts that we use to build singularity which is accessible through the [setup-singularity](https://github.com/eWaterCycle/setup-singularity) Action.

> Caution: this is prepared for and only permitted for use by setup-singularity action.

## Add new version

1. Start a [build workflow](https://github.com/eWaterCycle/singularity-versions/actions?query=workflow%3A%22Generate+singularity+version%22), set version to for example `3.7.1`. Will create a release with compiled singularity
1. Start a [manifest update workflow](https://github.com/eWaterCycle/singularity-versions/actions?query=workflow%3A%22Create+Pull+Request%22) to get updated `versions-manifest.json` file
1. Merge the generated PR
