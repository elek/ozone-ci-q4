# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-revert-24-hdds-2181-89r8m/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-revert-24-hdds-2181-89r8m/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-revert-24-hdds-2181-89r8m/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-revert-24-hdds-2181-89r8m/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.fs.ozone.contract.ITestOzoneContractDelete](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractDelete.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractDelete-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestKeyInputStream](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestKeyInputStream.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestKeyInputStream-output.txt))
 * [org.apache.hadoop.ozone.om.TestOzoneManagerHA](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestBlockOutputStream](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestBlockOutputStream.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestBlockOutputStream-output.txt))
 * [org.apache.hadoop.ozone.om.snapshot.TestOzoneManagerSnapshotProvider](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.snapshot.TestOzoneManagerSnapshotProvider.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.snapshot.TestOzoneManagerSnapshotProvider-output.txt))


# Tests with success status

## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-revert-24-hdds-2181-89r8m/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-revert-24-hdds-2181-89r8m/checkstyle)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-revert-24-hdds-2181-89r8m/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-revert-24-hdds-2181-89r8m/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-revert-24-hdds-2181-89r8m/findbugs/summary.html)


## acceptance check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-revert-24-hdds-2181-89r8m/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-revert-24-hdds-2181-89r8m/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-revert-24-hdds-2181-89r8m/acceptance/summary.html)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-revert-24-hdds-2181-89r8m/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-revert-24-hdds-2181-89r8m/checkout)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-revert-24-hdds-2181-89r8m/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-revert-24-hdds-2181-89r8m/author)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-revert-24-hdds-2181-89r8m/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-revert-24-hdds-2181-89r8m/build)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-revert-24-hdds-2181-89r8m/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-revert-24-hdds-2181-89r8m/rat)


## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-revert-24-hdds-2181-89r8m/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-revert-24-hdds-2181-89r8m/unit)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-revert-24-hdds-2181-89r8m/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
