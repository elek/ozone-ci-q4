# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/ozone/ozone-build-dev-xvzgc/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-xvzgc/integration)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-xvzgc/integration/summary.txt)

org.apache.hadoop.fs.ozone.TestOzoneFileInterfaces
org.apache.hadoop.fs.ozone.contract.ITestOzoneContractCreate
org.apache.hadoop.ozone.TestMiniChaosOzoneCluster
org.apache.hadoop.ozone.freon.TestDataValidateWithDummyContainers
org.apache.hadoop.ozone.om.TestOzoneManagerRocksDBLogging

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/ozone/ozone-build-dev-xvzgc/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-xvzgc/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/ozone/ozone-build-dev-xvzgc/acceptance/summary.html)



# Tests with success status

## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/ozone/ozone-build-dev-xvzgc/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-xvzgc/build)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/ozone/ozone-build-dev-xvzgc/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-xvzgc/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/ozone/ozone-build-dev-xvzgc/findbugs/summary.html)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/ozone/ozone-build-dev-xvzgc/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-xvzgc/checkstyle)


## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/ozone/ozone-build-dev-xvzgc/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-xvzgc/unit)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/ozone/ozone-build-dev-xvzgc/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-xvzgc/rat)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/ozone/ozone-build-dev-xvzgc/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-xvzgc/author)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/ozone/ozone-build-dev-xvzgc/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-xvzgc/checkout)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/ozone/ozone-build-dev-xvzgc/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
