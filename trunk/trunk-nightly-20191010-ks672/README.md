# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191010-ks672/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191010-ks672/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191010-ks672/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191010-ks672/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestWatchForCommit](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestWatchForCommit-output.txt))


# Tests with success status

## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191010-ks672/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191010-ks672/unit)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191010-ks672/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191010-ks672/author)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191010-ks672/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191010-ks672/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/trunk/trunk-nightly-20191010-ks672/findbugs/summary.html)


## acceptance check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191010-ks672/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191010-ks672/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/trunk/trunk-nightly-20191010-ks672/acceptance/summary.html)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191010-ks672/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191010-ks672/rat)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191010-ks672/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191010-ks672/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191010-ks672/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191010-ks672/build)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191010-ks672/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191010-ks672/checkstyle)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191010-ks672/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
