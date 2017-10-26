# Update the wp-cli Tool in a Probo Build

The [wp-cli](http://wp-cli.org/) tool is installed by defeault in Probo containers, but may need to be updated if the version installed in the Probo docker image used in the build is too old.

This example [.probo.yaml](https://github.com/Probo-Demos/recipes-update-wp-cli/blob/master/.probo.yaml) file in this repository will check the current version of wp-cli in the first step, update wp-cli to the latest version in the second step, and verify the wp-cli tool version in the last step.
