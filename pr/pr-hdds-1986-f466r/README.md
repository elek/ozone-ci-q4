# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1986-f466r/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1986-f466r/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1986-f466r/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1986-f466r/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.freon.TestRandomKeyGenerator](hadoop-ozone/tools/org.apache.hadoop.ozone.freon.TestRandomKeyGenerator.txt) ([output](hadoop-ozone/tools/org.apache.hadoop.ozone.freon.TestRandomKeyGenerator-output.txt))
 * [org.apache.hadoop.ozone.scm.node.TestQueryNode](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.node.TestQueryNode.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.node.TestQueryNode-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestWatchForCommit](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit-output.txt))
 * [org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs-output.txt))

## checkstyle check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1986-f466r/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1986-f466r/checkstyle)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1986-f466r/checkstyle/summary.txt)

hadoop-ozone/ozone-manager/src/test/java/org/apache/hadoop/ozone/om/request/TestOMRequestUtils.java
 123: &apos;method def&apos; child has incorrect indentation level 5, expected level should be 4.

## unit check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1986-f466r/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1986-f466r/unit)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1986-f466r/unit/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1986-f466r/unit/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.hdds.scm.block.TestBlockManager](hadoop-hdds/server-scm/org.apache.hadoop.hdds.scm.block.TestBlockManager.txt) ([output](hadoop-hdds/server-scm/org.apache.hadoop.hdds.scm.block.TestBlockManager-output.txt))


# Tests with success status

## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1986-f466r/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1986-f466r/build)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1986-f466r/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1986-f466r/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-1986-f466r/findbugs/summary.html)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1986-f466r/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1986-f466r/rat)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1986-f466r/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1986-f466r/author)


## acceptance check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1986-f466r/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1986-f466r/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-1986-f466r/acceptance/summary.html)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-1986-f466r/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1986-f466r/checkout)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-1986-f466r/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
