# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2204-lb5qm/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2204-lb5qm/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2204-lb5qm/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2204-lb5qm/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.client.rpc.TestCommitWatcher](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestCommitWatcher.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestCommitWatcher-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestWatchForCommit](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.Test2WayCommitInRatis](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.Test2WayCommitInRatis.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.Test2WayCommitInRatis-output.txt))
 * [org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFsHAURLs-output.txt))

## unit check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2204-lb5qm/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2204-lb5qm/unit)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2204-lb5qm/unit/summary.txt)

org.apache.hadoop.ozone.recon.api.TestContainerKeyService


# Tests with success status

## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2204-lb5qm/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2204-lb5qm/build)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2204-lb5qm/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2204-lb5qm/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-2204-lb5qm/findbugs/summary.html)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2204-lb5qm/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2204-lb5qm/checkstyle)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2204-lb5qm/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2204-lb5qm/rat)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2204-lb5qm/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2204-lb5qm/author)


## acceptance check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2204-lb5qm/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2204-lb5qm/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-2204-lb5qm/acceptance/summary.html)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2204-lb5qm/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2204-lb5qm/checkout)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2204-lb5qm/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
