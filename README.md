# singularity builds for Actions

![Build distro](https://github.com/eWaterCycle/singularity-versions/workflows/Build%20distro/badge.svg)

This repository contains the code and scripts that we use to build singularity which is accessible through the [setup-singularity](https://github.com/eWaterCycle/setup-singularity) Action.

> Caution: this is prepared for and only permitted for use by setup-singularity action.

## Add new version

1. Create a GH release with same version as singularity version you want to build. For example `v3.6.1`.
1. Wait for GH action job to add tarballs to release
1. Update versions-manifest.json with new version and tarballs
