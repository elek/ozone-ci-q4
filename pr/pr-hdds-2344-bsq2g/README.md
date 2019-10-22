# Tests with failure status

## findbugs check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2344-bsq2g/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2344-bsq2g/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-2344-bsq2g/findbugs/summary.html)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2344-bsq2g/findbugs/summary.txt)

M B CN: org.apache.hadoop.ozone.om.helpers.OmOzoneAclMap.clone() does not call super.clone()  At OmOzoneAclMap.java:[lines 309-327]

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2344-bsq2g/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2344-bsq2g/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2344-bsq2g/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2344-bsq2g/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.om.TestScmSafeMode](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower-output.txt))
 * [org.apache.hadoop.ozone.om.TestOzoneManagerHA](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA-output.txt))
 * [org.apache.hadoop.ozone.om.snapshot.TestOzoneManagerSnapshotProvider](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.snapshot.TestOzoneManagerSnapshotProvider.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.snapshot.TestOzoneManagerSnapshotProvider-output.txt))


# Tests with success status

## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2344-bsq2g/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2344-bsq2g/rat)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2344-bsq2g/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2344-bsq2g/checkstyle)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2344-bsq2g/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2344-bsq2g/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2344-bsq2g/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2344-bsq2g/build)


## acceptance check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2344-bsq2g/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2344-bsq2g/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-2344-bsq2g/acceptance/summary.html)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2344-bsq2g/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2344-bsq2g/author)


## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2344-bsq2g/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2344-bsq2g/unit)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2344-bsq2g/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
