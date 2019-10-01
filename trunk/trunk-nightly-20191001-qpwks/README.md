# Tests with failure status

## unit check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191001-qpwks/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191001-qpwks/unit)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191001-qpwks/unit/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191001-qpwks/unit/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.hdds.scm.container.placement.algorithms.TestSCMContainerPlacementRackAware](hadoop-hdds/server-scm/org.apache.hadoop.hdds.scm.container.placement.algorithms.TestSCMContainerPlacementRackAware.txt) ([output](hadoop-hdds/server-scm/org.apache.hadoop.hdds.scm.container.placement.algorithms.TestSCMContainerPlacementRackAware-output.txt))

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191001-qpwks/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191001-qpwks/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/trunk/trunk-nightly-20191001-qpwks/acceptance/summary.html)


## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191001-qpwks/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191001-qpwks/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191001-qpwks/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191001-qpwks/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs-output.txt))
 * [org.apache.hadoop.ozone.scm.node.TestQueryNode](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.node.TestQueryNode.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.node.TestQueryNode-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestContainerReplicationEndToEnd](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestContainerReplicationEndToEnd.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestContainerReplicationEndToEnd-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestWatchForCommit](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit-output.txt))


# Tests with success status

## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191001-qpwks/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191001-qpwks/author)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191001-qpwks/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191001-qpwks/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/trunk/trunk-nightly-20191001-qpwks/findbugs/summary.html)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191001-qpwks/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191001-qpwks/rat)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191001-qpwks/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191001-qpwks/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191001-qpwks/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191001-qpwks/build)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191001-qpwks/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191001-qpwks/checkstyle)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191001-qpwks/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
