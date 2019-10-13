# Tests with failure status

## unit check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds2071-28zjt/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds2071-28zjt/unit)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds2071-28zjt/unit/summary.txt)

org.apache.hadoop.hdds.scm.block.TestBlockManager

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds2071-28zjt/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds2071-28zjt/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds2071-28zjt/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds2071-28zjt/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.hdds.scm.pipeline.TestPipelineClose](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestPipelineClose.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestPipelineClose-output.txt))


# Tests with success status

## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds2071-28zjt/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds2071-28zjt/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds2071-28zjt/findbugs/summary.html)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds2071-28zjt/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds2071-28zjt/author)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds2071-28zjt/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds2071-28zjt/build)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds2071-28zjt/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds2071-28zjt/checkstyle)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds2071-28zjt/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds2071-28zjt/rat)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds2071-28zjt/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds2071-28zjt/checkout)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds2071-28zjt/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
