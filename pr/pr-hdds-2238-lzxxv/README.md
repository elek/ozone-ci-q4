# Tests with failure status

## unit check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2238-lzxxv/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2238-lzxxv/unit)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2238-lzxxv/unit/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2238-lzxxv/unit/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.hdds.scm.container.placement.algorithms.TestSCMContainerPlacementRackAware](hadoop-hdds/server-scm/org.apache.hadoop.hdds.scm.container.placement.algorithms.TestSCMContainerPlacementRackAware.txt) ([output](hadoop-hdds/server-scm/org.apache.hadoop.hdds.scm.container.placement.algorithms.TestSCMContainerPlacementRackAware-output.txt))

## findbugs check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2238-lzxxv/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2238-lzxxv/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-2238-lzxxv/findbugs/summary.html)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2238-lzxxv/findbugs/summary.txt)

M D DLS: Dead store to metadataScanInterval in org.apache.hadoop.ozone.container.ozoneimpl.OzoneContainer.startContainerScrub()  At OzoneContainer.java:[line 175]

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2238-lzxxv/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2238-lzxxv/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-2238-lzxxv/acceptance/summary.html)


## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2238-lzxxv/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2238-lzxxv/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2238-lzxxv/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2238-lzxxv/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.client.rpc.TestCommitWatcher](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestCommitWatcher.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestCommitWatcher-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.Test2WayCommitInRatis](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.Test2WayCommitInRatis.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.Test2WayCommitInRatis-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestWatchForCommit](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit-output.txt))
 * [org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs-output.txt))

## checkstyle check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2238-lzxxv/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2238-lzxxv/checkstyle)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2238-lzxxv/checkstyle/summary.txt)

hadoop-ozone/integration-test/src/test/java/org/apache/hadoop/ozone/container/common/TestBlockDeletingService.java
 454: Line is longer than 80 characters (found 83).
hadoop-hdds/container-service/src/main/java/org/apache/hadoop/ozone/container/ozoneimpl/ContainerDataScanner.java
 63: Line is longer than 80 characters (found 81).
hadoop-hdds/container-service/src/main/java/org/apache/hadoop/ozone/container/ozoneimpl/ContainerScrubberConfiguration.java
 25: Unused import - java.util.concurrent.TimeUnit.
hadoop-hdds/container-service/src/main/java/org/apache/hadoop/ozone/container/ozoneimpl/ContainerMetadataScrubberMetrics.java
 21: Unused import - org.apache.hadoop.conf.Configuration.
hadoop-hdds/container-service/src/main/java/org/apache/hadoop/ozone/container/ozoneimpl/ContainerMetadataScanner.java
 21: Unused import - org.apache.hadoop.conf.Configuration.
hadoop-hdds/container-service/src/main/java/org/apache/hadoop/ozone/container/ozoneimpl/ContainerDataScrubberMetrics.java
 21: Unused import - org.apache.hadoop.conf.Configuration.
hadoop-hdds/container-service/src/test/java/org/apache/hadoop/ozone/container/common/impl/TestContainerSet.java
 100: Line is longer than 80 characters (found 83).


# Tests with success status

## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2238-lzxxv/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2238-lzxxv/author)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2238-lzxxv/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2238-lzxxv/rat)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2238-lzxxv/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2238-lzxxv/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2238-lzxxv/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2238-lzxxv/build)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2238-lzxxv/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
