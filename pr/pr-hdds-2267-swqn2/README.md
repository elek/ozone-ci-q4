# Tests with failure status

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2267-swqn2/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2267-swqn2/acceptance)


## build check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2267-swqn2/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2267-swqn2/build)


## unit check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2267-swqn2/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2267-swqn2/unit)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2267-swqn2/unit/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2267-swqn2/unit/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.hdds.scm.container.placement.algorithms.TestSCMContainerPlacementRackAware](hadoop-hdds/server-scm/org.apache.hadoop.hdds.scm.container.placement.algorithms.TestSCMContainerPlacementRackAware.txt) ([output](hadoop-hdds/server-scm/org.apache.hadoop.hdds.scm.container.placement.algorithms.TestSCMContainerPlacementRackAware-output.txt))

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2267-swqn2/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2267-swqn2/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2267-swqn2/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2267-swqn2/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.client.rpc.TestMultiBlockWritesWithDnFailures](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestMultiBlockWritesWithDnFailures.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestMultiBlockWritesWithDnFailures-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestOzoneRpcClient](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneRpcClient.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneRpcClient-output.txt))
 * [org.apache.hadoop.fs.ozone.contract.ITestOzoneContractGetFileStatus](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractGetFileStatus.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractGetFileStatus-output.txt))


# Tests with success status

## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2267-swqn2/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2267-swqn2/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-2267-swqn2/findbugs/summary.html)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2267-swqn2/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2267-swqn2/author)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2267-swqn2/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2267-swqn2/checkstyle)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2267-swqn2/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2267-swqn2/rat)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2267-swqn2/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2267-swqn2/checkout)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2267-swqn2/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
