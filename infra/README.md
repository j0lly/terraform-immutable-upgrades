The directories `v1` and `v2` represents the history of the infra repository. To make them as simple as possible their content (terraform config, scripts etc...) is identical with exception of the `config` file that defines which consul AMI to use and, in `v1`, which previous infra version to use for testing rolling upgrades.