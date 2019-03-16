# Oracle 12c on OpenShift

This repository is in support of my blog post about this subject that [can be found on Medium](https://medium.com). Instructions for running the official Oracle 12c image on OpenShift can be found there.

$ oc process -f https://raw.githubusercontent.com/pittar/oracle-on-openshift/master/oracle-ephemeral.yaml \
    | oc create -f -

$ oc process -f https://raw.githubusercontent.com/pittar/oracle-on-openshift/master/oracle-persistent.yaml \
    | oc create -f -