# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191007-kbwpl/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191007-kbwpl/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191007-kbwpl/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191007-kbwpl/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.client.rpc.Test2WayCommitInRatis](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.Test2WayCommitInRatis.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.Test2WayCommitInRatis-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestWatchForCommit](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit-output.txt))
 * [org.apache.hadoop.ozone.container.common.statemachine.commandhandler.TestBlockDeletion](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.common.statemachine.commandhandler.TestBlockDeletion.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.common.statemachine.commandhandler.TestBlockDeletion-output.txt))
 * [org.apache.hadoop.ozone.om.TestOzoneManagerRestart](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerRestart.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerRestart-output.txt))

## unit check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191007-kbwpl/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191007-kbwpl/unit)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191007-kbwpl/unit/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191007-kbwpl/unit/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.hdds.scm.container.placement.algorithms.TestSCMContainerPlacementRackAware](hadoop-hdds/server-scm/org.apache.hadoop.hdds.scm.container.placement.algorithms.TestSCMContainerPlacementRackAware.txt) ([output](hadoop-hdds/server-scm/org.apache.hadoop.hdds.scm.container.placement.algorithms.TestSCMContainerPlacementRackAware-output.txt))


# Tests with success status

## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191007-kbwpl/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191007-kbwpl/build)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191007-kbwpl/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191007-kbwpl/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/trunk/trunk-nightly-20191007-kbwpl/findbugs/summary.html)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191007-kbwpl/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191007-kbwpl/checkstyle)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191007-kbwpl/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191007-kbwpl/rat)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191007-kbwpl/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191007-kbwpl/author)


## acceptance check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191007-kbwpl/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191007-kbwpl/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/trunk/trunk-nightly-20191007-kbwpl/acceptance/summary.html)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191007-kbwpl/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191007-kbwpl/checkout)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191007-kbwpl/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
