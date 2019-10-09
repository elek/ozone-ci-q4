# Tests with failure status

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1569-mfl88/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-mfl88/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-1569-mfl88/acceptance/summary.html)


## checkstyle check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1569-mfl88/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-mfl88/checkstyle)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-mfl88/checkstyle/summary.txt)

hadoop-hdds/server-scm/src/main/java/org/apache/hadoop/hdds/scm/pipeline/RatisPipelineProvider.java
 98: &apos;lambda arguments&apos; has incorrect indentation level 8, expected level should be one of the following: 10, 12.

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1569-mfl88/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-mfl88/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-mfl88/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-mfl88/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.hdds.scm.pipeline.TestRatisPipelineCreateAndDestroy](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestRatisPipelineCreateAndDestroy.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestRatisPipelineCreateAndDestroy-output.txt/))
 * [org.apache.hadoop.ozone.client.rpc.TestCommitWatcher](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestCommitWatcher.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestCommitWatcher-output.txt/))
 * [org.apache.hadoop.hdds.scm.safemode.TestSCMSafeModeWithPipelineRules](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.safemode.TestSCMSafeModeWithPipelineRules.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.safemode.TestSCMSafeModeWithPipelineRules-output.txt/))
 * [org.apache.hadoop.ozone.client.rpc.TestWatchForCommit](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit-output.txt/))
 * [org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures-output.txt/))
 * [org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs-output.txt/))


# Tests with success status

## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1569-mfl88/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-mfl88/findbugs)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1569-mfl88/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-mfl88/author)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1569-mfl88/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-mfl88/build)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1569-mfl88/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-mfl88/rat)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1569-mfl88/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-mfl88/checkout)


## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1569-mfl88/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-mfl88/unit)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1569-mfl88/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
