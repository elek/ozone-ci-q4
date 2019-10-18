# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2280-982rn/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2280-982rn/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2280-982rn/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2280-982rn/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.scm.node.TestQueryNode](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.node.TestQueryNode.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.node.TestQueryNode-output.txt))
 * [org.apache.hadoop.ozone.container.common.statemachine.commandhandler.TestDeleteContainerHandler](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.common.statemachine.commandhandler.TestDeleteContainerHandler.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.common.statemachine.commandhandler.TestDeleteContainerHandler-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestWatchForCommit](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit-output.txt))
 * [org.apache.hadoop.ozone.om.TestOzoneManagerHA](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA-output.txt))
 * [org.apache.hadoop.ozone.container.common.statemachine.commandhandler.TestCloseContainerByPipeline](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.common.statemachine.commandhandler.TestCloseContainerByPipeline.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.common.statemachine.commandhandler.TestCloseContainerByPipeline-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestContainerReplicationEndToEnd](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestContainerReplicationEndToEnd.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestContainerReplicationEndToEnd-output.txt))

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2280-982rn/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2280-982rn/acceptance)



# Tests with success status

## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2280-982rn/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2280-982rn/checkstyle)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2280-982rn/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2280-982rn/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-2280-982rn/findbugs/summary.html)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2280-982rn/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2280-982rn/checkout)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2280-982rn/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2280-982rn/author)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2280-982rn/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2280-982rn/build)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2280-982rn/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2280-982rn/rat)


## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2280-982rn/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2280-982rn/unit)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2280-982rn/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
