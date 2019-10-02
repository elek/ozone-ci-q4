# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-trunk-878pl/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-trunk-878pl/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-trunk-878pl/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-trunk-878pl/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.client.rpc.TestCommitWatcher](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestCommitWatcher.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestCommitWatcher-output.txt))
 * [org.apache.hadoop.ozone.container.server.TestSecureContainerServer](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.server.TestSecureContainerServer.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.server.TestSecureContainerServer-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.Test2WayCommitInRatis](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.Test2WayCommitInRatis.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.Test2WayCommitInRatis-output.txt))
 * [org.apache.hadoop.ozone.om.TestOzoneManagerRestart](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerRestart.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerRestart-output.txt))
 * [org.apache.hadoop.ozone.scm.TestGetCommittedBlockLengthAndPutKey](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.TestGetCommittedBlockLengthAndPutKey.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.TestGetCommittedBlockLengthAndPutKey-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestOzoneClientRetriesOnException](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneClientRetriesOnException.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneClientRetriesOnException-output.txt))
 * [org.apache.hadoop.ozone.scm.TestSCMContainerPlacementPolicyMetrics](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.TestSCMContainerPlacementPolicyMetrics.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.TestSCMContainerPlacementPolicyMetrics-output.txt))
 * [org.apache.hadoop.ozone.scm.TestContainerSmallFile](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.TestContainerSmallFile.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.TestContainerSmallFile-output.txt))
 * [org.apache.hadoop.ozone.TestContainerStateMachineIdempotency](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestContainerStateMachineIdempotency.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestContainerStateMachineIdempotency-output.txt))
 * [org.apache.hadoop.fs.ozone.contract.ITestOzoneContractMkdir](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractMkdir.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractMkdir-output.txt))
 * [org.apache.hadoop.fs.ozone.contract.ITestOzoneContractDelete](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractDelete.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractDelete-output.txt))
 * [org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs-output.txt))
 * [org.apache.hadoop.fs.ozone.contract.ITestOzoneContractOpen](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractOpen.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractOpen-output.txt))

## unit check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-trunk-878pl/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-trunk-878pl/unit)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-trunk-878pl/unit/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-trunk-878pl/unit/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.hdds.scm.block.TestBlockManager](hadoop-hdds/server-scm/org.apache.hadoop.hdds.scm.block.TestBlockManager.txt) ([output](hadoop-hdds/server-scm/org.apache.hadoop.hdds.scm.block.TestBlockManager-output.txt))

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-trunk-878pl/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-trunk-878pl/acceptance)


## rat check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-trunk-878pl/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-trunk-878pl/rat)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-trunk-878pl/rat/summary.txt)

hadoop-hdds/server-scm/target/rat.txt: !????? /workdir/hadoop-hdds/server-scm/src/main/java/org/apache/hadoop/hdds/scm/container/metrics/SCMContainerManagerMetrics.java
hadoop-ozone/integration-test/target/rat.txt: !????? /workdir/hadoop-ozone/integration-test/src/test/java/org/apache/hadoop/hdds/scm/container/metrics/TestSCMContainerManagerMetrics.java

## checkstyle check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-trunk-878pl/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-trunk-878pl/checkstyle)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-trunk-878pl/checkstyle/summary.txt)

hadoop-ozone/common/src/main/java/org/apache/hadoop/ozone/OmUtils.java
 49: Unused import - org.apache.hadoop.ozone.om.OMMetadataManager.

## findbugs check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-trunk-878pl/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-trunk-878pl/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-trunk-878pl/findbugs/summary.html)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-trunk-878pl/findbugs/summary.txt)

M B OS: org.apache.hadoop.hdds.ratis.ContainerCommandRequestMessage.buildContent() may fail to close stream  At ContainerCommandRequestMessage.java:[line 97]


# Tests with success status

## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-trunk-878pl/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-trunk-878pl/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-trunk-878pl/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-trunk-878pl/build)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-trunk-878pl/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-trunk-878pl/author)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-trunk-878pl/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
