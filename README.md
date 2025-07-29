# EDC Minimum Viable Dataspace (MVD)

This is a fork of the [EDC MinimumViableDataspace](https://github.com/eclipse-edc/MinimumViableDataspace)
repo and contains gate-specific changes for testing and deployment purposes:

* pinned `hashicorp/helm` version in `deployment/main.tf`

> [!NOTE]
> The `gate/0.12.0` branch is the main branch used for GATE deployments.
> It contains changes to EDC's `v0.12.0` tag (ref.
> [140f18c](https://github.com/eclipse-edc/MinimumViableDataspace/tree/140f18c8f79d035bd42fb38e621f7a345f177875))

## Quick start

Please refer to Eclipse's
[README](https://github.com/eclipse-edc/MinimumViableDataspace/tree/0.12.0)
for MinimumViableDataspace.

If you wish to run a lightweight MVD based on docker-compose without having to set up
a Java SDK on your machine, check out GATE's
[mvd-sandbox](https://github.com/gate-institute/gate-dsv2/deployment/mvd-sandbox).

