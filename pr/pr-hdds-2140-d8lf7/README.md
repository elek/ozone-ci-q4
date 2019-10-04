# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2140-d8lf7/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2140-d8lf7/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2140-d8lf7/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2140-d8lf7/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestContainerReplicationEndToEnd](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestContainerReplicationEndToEnd.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestContainerReplicationEndToEnd-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestCommitWatcher](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestCommitWatcher.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestCommitWatcher-output.txt))

## checkstyle check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2140-d8lf7/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2140-d8lf7/checkstyle)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2140-d8lf7/checkstyle/summary.txt)

hadoop-ozone/common/src/main/java/org/apache/hadoop/ozone/OmUtils.java
 49: Unused import - org.apache.hadoop.ozone.om.OMMetadataManager.

## rat check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2140-d8lf7/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2140-d8lf7/rat)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2140-d8lf7/rat/summary.txt)

hadoop-hdds/server-scm/target/rat.txt: !????? /workdir/hadoop-hdds/server-scm/src/main/java/org/apache/hadoop/hdds/scm/container/metrics/SCMContainerManagerMetrics.java
hadoop-ozone/integration-test/target/rat.txt: !????? /workdir/hadoop-ozone/integration-test/src/test/java/org/apache/hadoop/hdds/scm/container/metrics/TestSCMContainerManagerMetrics.java

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2140-d8lf7/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2140-d8lf7/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-2140-d8lf7/acceptance/summary.html)



# Tests with success status

## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2140-d8lf7/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2140-d8lf7/build)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2140-d8lf7/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2140-d8lf7/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-2140-d8lf7/findbugs/summary.html)


## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2140-d8lf7/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2140-d8lf7/unit)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2140-d8lf7/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2140-d8lf7/author)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2140-d8lf7/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2140-d8lf7/checkout)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2140-d8lf7/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
