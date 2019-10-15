# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/dev/dev-nightly-20191015-lc69l/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191015-lc69l/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191015-lc69l/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191015-lc69l/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.client.rpc.TestOzoneClientRetriesOnException](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneClientRetriesOnException.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneClientRetriesOnException-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestContainerReplicationEndToEnd](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestContainerReplicationEndToEnd.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestContainerReplicationEndToEnd-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestWatchForCommit](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit-output.txt))


# Tests with success status

## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/dev/dev-nightly-20191015-lc69l/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191015-lc69l/checkout)


## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/dev/dev-nightly-20191015-lc69l/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191015-lc69l/unit)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/dev/dev-nightly-20191015-lc69l/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191015-lc69l/build)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/dev/dev-nightly-20191015-lc69l/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191015-lc69l/checkstyle)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/dev/dev-nightly-20191015-lc69l/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191015-lc69l/rat)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/dev/dev-nightly-20191015-lc69l/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191015-lc69l/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/dev/dev-nightly-20191015-lc69l/findbugs/summary.html)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/dev/dev-nightly-20191015-lc69l/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191015-lc69l/author)


## acceptance check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/dev/dev-nightly-20191015-lc69l/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191015-lc69l/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/dev/dev-nightly-20191015-lc69l/acceptance/summary.html)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191015-lc69l/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
