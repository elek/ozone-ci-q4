# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/dev/dev-nightly-20191014-2mv7m/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191014-2mv7m/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191014-2mv7m/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191014-2mv7m/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.container.common.statemachine.commandhandler.TestCloseContainerByPipeline](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.common.statemachine.commandhandler.TestCloseContainerByPipeline.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.common.statemachine.commandhandler.TestCloseContainerByPipeline-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestCommitWatcher](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestCommitWatcher.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestCommitWatcher-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestWatchForCommit](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit-output.txt))


# Tests with success status

## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/dev/dev-nightly-20191014-2mv7m/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191014-2mv7m/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/dev/dev-nightly-20191014-2mv7m/findbugs/summary.html)


## acceptance check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/dev/dev-nightly-20191014-2mv7m/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191014-2mv7m/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/dev/dev-nightly-20191014-2mv7m/acceptance/summary.html)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/dev/dev-nightly-20191014-2mv7m/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191014-2mv7m/author)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/dev/dev-nightly-20191014-2mv7m/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191014-2mv7m/build)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/dev/dev-nightly-20191014-2mv7m/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191014-2mv7m/checkstyle)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/dev/dev-nightly-20191014-2mv7m/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191014-2mv7m/rat)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/dev/dev-nightly-20191014-2mv7m/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191014-2mv7m/checkout)


## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/dev/dev-nightly-20191014-2mv7m/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191014-2mv7m/unit)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/dev/dev-nightly-20191014-2mv7m/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
