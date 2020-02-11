# OpenEBS Addons for D2iQ Ksphere

This repository contains the OpenEBS addons needed to bootstrap [D2iQ Kubernetes](https://d2iq.com/solutions/ksphere).

## Overview

The structure of this repository follows the [Kubeaddons Catalog Documentation](https://github.com/mesosphere/kubeaddons/blob/master/tools/catalog/README.md) in reference, and uses the [Addon Revision concept covered therein](https://github.com/mesosphere/kubeaddons/blob/master/tools/catalog/README.md#special-addonrepository-options---addon-revisions).

You will find the following directories here:

* `addons/` - containing the actual manifests for addon resources
* `deployments/` - containing the default addons depending on the Kubernetes version
* `metadata/` - containing static metadata for the addons in `addons/`
* `test/` - containing integration tests for the addons in `addons/`
