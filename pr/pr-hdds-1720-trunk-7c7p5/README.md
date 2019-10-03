# Tests with failure status

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1720-trunk-7c7p5/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1720-trunk-7c7p5/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-1720-trunk-7c7p5/acceptance/summary.html)


## build check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1720-trunk-7c7p5/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1720-trunk-7c7p5/build)


## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1720-trunk-7c7p5/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1720-trunk-7c7p5/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1720-trunk-7c7p5/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1720-trunk-7c7p5/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.container.common.statemachine.commandhandler.TestBlockDeletion](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.common.statemachine.commandhandler.TestBlockDeletion.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.common.statemachine.commandhandler.TestBlockDeletion-output.txt))
 * [org.apache.hadoop.ozone.scm.node.TestQueryNode](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.node.TestQueryNode.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.node.TestQueryNode-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestWatchForCommit](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit-output.txt))
 * [org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs-output.txt))

## checkstyle check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1720-trunk-7c7p5/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1720-trunk-7c7p5/checkstyle)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1720-trunk-7c7p5/checkstyle/summary.txt)

hadoop-ozone/integration-test/src/test/java/org/apache/hadoop/ozone/om/TestOzoneManagerRocksDBLogging.java
 22: Unused import - org.apache.hadoop.ozone.OzoneConfigKeys.OZONE_ACL_ENABLED.
 23: Unused import - org.apache.hadoop.ozone.OzoneConfigKeys.OZONE_ADMINISTRATORS.
 24: Unused import - org.apache.hadoop.ozone.OzoneConfigKeys.OZONE_ADMINISTRATORS_WILDCARD.
 25: Unused import - org.apache.hadoop.ozone.OzoneConfigKeys.OZONE_OPEN_KEY_EXPIRE_THRESHOLD_SECONDS.
 27: Unused import - java.io.IOException.


# Tests with success status

## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1720-trunk-7c7p5/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1720-trunk-7c7p5/unit)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1720-trunk-7c7p5/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1720-trunk-7c7p5/author)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1720-trunk-7c7p5/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1720-trunk-7c7p5/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-1720-trunk-7c7p5/findbugs/summary.html)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1720-trunk-7c7p5/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1720-trunk-7c7p5/rat)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1720-trunk-7c7p5/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1720-trunk-7c7p5/checkout)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1720-trunk-7c7p5/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
