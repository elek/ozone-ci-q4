# Tests with failure status

## unit check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191009-4zxp8/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191009-4zxp8/unit)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191009-4zxp8/unit/summary.txt)

org.apache.hadoop.hdds.scm.block.TestBlockManager
org.apache.hadoop.ozone.container.ozoneimpl.TestOzoneContainer
org.apache.hadoop.ozone.om.request.s3.bucket.TestS3BucketDeleteRequest
org.apache.hadoop.ozone.om.request.s3.multipart.TestS3MultipartUploadCommitPartRequest

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191009-4zxp8/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191009-4zxp8/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191009-4zxp8/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191009-4zxp8/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.client.rpc.TestCommitWatcher](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestCommitWatcher.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestCommitWatcher-output.txt))


# Tests with success status

## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191009-4zxp8/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191009-4zxp8/author)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191009-4zxp8/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191009-4zxp8/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/trunk/trunk-nightly-20191009-4zxp8/findbugs/summary.html)


## acceptance check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191009-4zxp8/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191009-4zxp8/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/trunk/trunk-nightly-20191009-4zxp8/acceptance/summary.html)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191009-4zxp8/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191009-4zxp8/rat)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191009-4zxp8/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191009-4zxp8/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191009-4zxp8/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191009-4zxp8/build)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/trunk/trunk-nightly-20191009-4zxp8/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191009-4zxp8/checkstyle)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/trunk/trunk-nightly-20191009-4zxp8/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
