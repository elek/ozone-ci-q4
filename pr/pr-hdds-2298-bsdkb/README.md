# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2298-bsdkb/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2298-bsdkb/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2298-bsdkb/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2298-bsdkb/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.client.rpc.TestSecureOzoneRpcClient](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestSecureOzoneRpcClient.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestSecureOzoneRpcClient-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestOzoneClientRetriesOnException](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneClientRetriesOnException.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneClientRetriesOnException-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestFailureHandlingByClient](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestFailureHandlingByClient.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestFailureHandlingByClient-output.txt))


# Tests with success status

## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2298-bsdkb/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2298-bsdkb/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-2298-bsdkb/findbugs/summary.html)


## acceptance check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2298-bsdkb/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2298-bsdkb/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-2298-bsdkb/acceptance/summary.html)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2298-bsdkb/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2298-bsdkb/author)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2298-bsdkb/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2298-bsdkb/build)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2298-bsdkb/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2298-bsdkb/checkstyle)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2298-bsdkb/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2298-bsdkb/rat)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2298-bsdkb/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2298-bsdkb/checkout)


## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2298-bsdkb/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2298-bsdkb/unit)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2298-bsdkb/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
