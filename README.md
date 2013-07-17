# openshift-deploy

Deploys your application to [OpenShift](https://www.openshift.com/) that is inside the `$WERCKER_SOURCE_DIR`.

This requires your application to have an OpenShift deploy target. See [OpenShift support for wercker](http://blog.wercker.com/2013/06/11/OpenShift-Support.html).

Note: this deployment step does not need to be added to your `wercker.yml` if you have the OpenShift deploy target added via the wercker website.

## Example

- openshift-deploy
