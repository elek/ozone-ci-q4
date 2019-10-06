# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/ozone/ozone-build-dev-nffdx/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-nffdx/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-nffdx/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-nffdx/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestBlockOutputStreamWithFailures-output.txt))
 * [org.apache.hadoop.ozone.scm.node.TestQueryNode](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.node.TestQueryNode.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.node.TestQueryNode-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestOzoneClientRetriesOnException](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneClientRetriesOnException.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneClientRetriesOnException-output.txt))


# Tests with success status

## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/ozone/ozone-build-dev-nffdx/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-nffdx/build)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/ozone/ozone-build-dev-nffdx/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-nffdx/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/ozone/ozone-build-dev-nffdx/findbugs/summary.html)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/ozone/ozone-build-dev-nffdx/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-nffdx/checkstyle)


## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/ozone/ozone-build-dev-nffdx/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-nffdx/unit)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/ozone/ozone-build-dev-nffdx/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-nffdx/rat)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/ozone/ozone-build-dev-nffdx/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-nffdx/author)


## acceptance check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/ozone/ozone-build-dev-nffdx/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-nffdx/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/ozone/ozone-build-dev-nffdx/acceptance/summary.html)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/ozone/ozone-build-dev-nffdx/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-nffdx/checkout)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-nffdx/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
