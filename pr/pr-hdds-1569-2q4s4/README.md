# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1569-2q4s4/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-2q4s4/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-2q4s4/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-2q4s4/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.hdds.scm.pipeline.TestNode2PipelineMap](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestNode2PipelineMap.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestNode2PipelineMap-output.txt))
 * [org.apache.hadoop.ozone.scm.TestContainerSmallFile](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.TestContainerSmallFile.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.TestContainerSmallFile-output.txt))
 * [org.apache.hadoop.hdds.scm.safemode.TestSCMSafeModeWithPipelineRules](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.safemode.TestSCMSafeModeWithPipelineRules.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.safemode.TestSCMSafeModeWithPipelineRules-output.txt))
 * [org.apache.hadoop.hdds.scm.pipeline.TestRatisPipelineCreateAndDestroy](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestRatisPipelineCreateAndDestroy.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestRatisPipelineCreateAndDestroy-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower-output.txt))
 * [org.apache.hadoop.ozone.scm.TestAllocateContainer](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.TestAllocateContainer.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.TestAllocateContainer-output.txt))

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1569-2q4s4/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-2q4s4/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-1569-2q4s4/acceptance/summary.html)



# Tests with success status

## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1569-2q4s4/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-2q4s4/rat)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1569-2q4s4/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-2q4s4/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1569-2q4s4/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-2q4s4/build)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1569-2q4s4/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-2q4s4/author)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1569-2q4s4/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-2q4s4/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-1569-2q4s4/findbugs/summary.html)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-2q4s4/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
