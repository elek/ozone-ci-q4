# Tests with failure status

## unit check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191006-mzxw6/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191006-mzxw6/unit)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191006-mzxw6/unit/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191006-mzxw6/unit/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.hdds.scm.container.placement.algorithms.TestSCMContainerPlacementRackAware](hadoop-hdds/server-scm/org.apache.hadoop.hdds.scm.container.placement.algorithms.TestSCMContainerPlacementRackAware.txt) ([output](hadoop-hdds/server-scm/org.apache.hadoop.hdds.scm.container.placement.algorithms.TestSCMContainerPlacementRackAware-output.txt))

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191006-mzxw6/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191006-mzxw6/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191006-mzxw6/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191006-mzxw6/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestWatchForCommit](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit-output.txt))
 * [org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs-output.txt))


# Tests with success status

## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191006-mzxw6/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191006-mzxw6/author)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191006-mzxw6/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191006-mzxw6/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/trunk/trunk-nightly-20191006-mzxw6/findbugs/summary.html)


## acceptance check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191006-mzxw6/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191006-mzxw6/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/trunk/trunk-nightly-20191006-mzxw6/acceptance/summary.html)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191006-mzxw6/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191006-mzxw6/rat)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191006-mzxw6/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191006-mzxw6/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191006-mzxw6/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191006-mzxw6/build)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191006-mzxw6/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191006-mzxw6/checkstyle)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191006-mzxw6/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
