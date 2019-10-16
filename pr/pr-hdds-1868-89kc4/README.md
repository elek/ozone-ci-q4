# Tests with failure status

## checkstyle check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1868-89kc4/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1868-89kc4/checkstyle)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1868-89kc4/checkstyle/summary.txt)

hadoop-hdds/container-service/src/main/java/org/apache/hadoop/ozone/container/common/transport/server/ratis/XceiverServerRatis.java
 29: Unused import - org.apache.hadoop.hdds.protocol.proto.StorageContainerDatanodeProtocolProtos.PipelineReportsProto.
hadoop-hdds/server-scm/src/main/java/org/apache/hadoop/hdds/scm/pipeline/PipelineStateManager.java
 35: Unused import - com.google.common.annotations.VisibleForTesting.

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1868-89kc4/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1868-89kc4/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-1868-89kc4/acceptance/summary.html)


## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1868-89kc4/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1868-89kc4/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1868-89kc4/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1868-89kc4/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.fs.ozone.contract.ITestOzoneContractMkdir](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractMkdir.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractMkdir-output.txt))
 * [org.apache.hadoop.ozone.freon.TestDataValidateWithDummyContainers](hadoop-ozone/tools/org.apache.hadoop.ozone.freon.TestDataValidateWithDummyContainers.txt) ([output](hadoop-ozone/tools/org.apache.hadoop.ozone.freon.TestDataValidateWithDummyContainers-output.txt))
 * [org.apache.hadoop.ozone.freon.TestFreonWithPipelineDestroy](hadoop-ozone/tools/org.apache.hadoop.ozone.freon.TestFreonWithPipelineDestroy.txt) ([output](hadoop-ozone/tools/org.apache.hadoop.ozone.freon.TestFreonWithPipelineDestroy-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestMultiBlockWritesWithDnFailures](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestMultiBlockWritesWithDnFailures.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestMultiBlockWritesWithDnFailures-output.txt))
 * [org.apache.hadoop.ozone.om.TestOMRatisSnapshots](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOMRatisSnapshots.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOMRatisSnapshots-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestContainerStateMachine](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestContainerStateMachine.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestContainerStateMachine-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestFailureHandlingByClient](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestFailureHandlingByClient.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestFailureHandlingByClient-output.txt))
 * [org.apache.hadoop.hdds.scm.pipeline.TestSCMPipelineManager](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestSCMPipelineManager.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestSCMPipelineManager-output.txt))
 * [org.apache.hadoop.ozone.ozShell.TestOzoneShellHA](hadoop-ozone/integration-test/org.apache.hadoop.ozone.ozShell.TestOzoneShellHA.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.ozShell.TestOzoneShellHA-output.txt))
 * [org.apache.hadoop.ozone.container.server.TestSecureContainerServer](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.server.TestSecureContainerServer.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.server.TestSecureContainerServer-output.txt))
 * [org.apache.hadoop.hdds.scm.pipeline.TestRatisPipelineCreateAndDestroy](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestRatisPipelineCreateAndDestroy.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestRatisPipelineCreateAndDestroy-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestCloseContainerHandlingByClient](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestCloseContainerHandlingByClient.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestCloseContainerHandlingByClient-output.txt))
 * [org.apache.hadoop.ozone.om.TestOzoneManagerHA](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA-output.txt))
 * [org.apache.hadoop.ozone.TestMiniChaosOzoneCluster](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestMiniChaosOzoneCluster.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestMiniChaosOzoneCluster-output.txt))
 * [org.apache.hadoop.ozone.container.common.transport.server.ratis.TestCSMMetrics](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.common.transport.server.ratis.TestCSMMetrics.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.common.transport.server.ratis.TestCSMMetrics-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower-output.txt))

## unit check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1868-89kc4/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1868-89kc4/unit)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1868-89kc4/unit/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1868-89kc4/unit/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.hdds.scm.container.placement.algorithms.TestSCMContainerPlacementRackAware](hadoop-hdds/server-scm/org.apache.hadoop.hdds.scm.container.placement.algorithms.TestSCMContainerPlacementRackAware.txt) ([output](hadoop-hdds/server-scm/org.apache.hadoop.hdds.scm.container.placement.algorithms.TestSCMContainerPlacementRackAware-output.txt))


# Tests with success status

## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1868-89kc4/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1868-89kc4/rat)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1868-89kc4/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1868-89kc4/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-1868-89kc4/findbugs/summary.html)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1868-89kc4/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1868-89kc4/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1868-89kc4/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1868-89kc4/build)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1868-89kc4/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1868-89kc4/author)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1868-89kc4/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
