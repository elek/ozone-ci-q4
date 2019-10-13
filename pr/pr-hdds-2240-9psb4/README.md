# Tests with failure status

## findbugs check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2240-9psb4/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2240-9psb4/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-2240-9psb4/findbugs/summary.html)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2240-9psb4/findbugs/summary.txt)

H I Dm: Found reliance on default encoding in org.apache.hadoop.ozone.om.ratis.OzoneManagerRatisServer.getServerRoles(): new String(byte[])  At OzoneManagerRatisServer.java:[line 640]

## checkstyle check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2240-9psb4/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2240-9psb4/checkstyle)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2240-9psb4/checkstyle/summary.txt)

hadoop-ozone/tools/src/main/java/org/apache/hadoop/ozone/admin/om/GetServiceRolesSubcommand.java
 1: Missing package-info.java file.
 4: Unused import - org.apache.hadoop.hdds.protocol.proto.HddsProtos.
 6: Unused import - org.apache.hadoop.ozone.om.helpers.ServiceInfo.
hadoop-ozone/tools/src/main/java/org/apache/hadoop/ozone/admin/om/OMAdmin.java
 24: Unused import - org.apache.hadoop.hdds.scm.cli.SCMCLI.
 25: Unused import - org.apache.hadoop.hdds.tracing.TracingUtil.
 27: Unused import - org.apache.hadoop.ozone.client.OzoneClient.
 30: Unused import - org.apache.hadoop.ozone.client.rpc.RpcClient.
 31: Unused import - org.apache.hadoop.security.UserGroupInformation.
 32: Unused import - org.apache.hadoop.security.authentication.client.AuthenticationException.
 33: Unused import - org.apache.ratis.protocol.ClientId.
 39: Unused import - java.util.Map.
hadoop-ozone/tools/src/main/java/org/apache/hadoop/ozone/admin/OzoneAdmin.java
 1: Missing package-info.java file.
 45: &apos;member def modifier&apos; has incorrect indentation level 4, expected level should be 2.
 47: &apos;method def modifier&apos; has incorrect indentation level 4, expected level should be 2.
 48: &apos;if&apos; has incorrect indentation level 8, expected level should be 4.
 49: &apos;if&apos; child has incorrect indentation level 12, expected level should be 6.
 50: &apos;if rcurly&apos; has incorrect indentation level 8, expected level should be 4.
 51: &apos;method def&apos; child has incorrect indentation level 8, expected level should be 4.
 52: &apos;method def rcurly&apos; has incorrect indentation level 4, expected level should be 2.
 60: &apos;method def modifier&apos; has incorrect indentation level 4, expected level should be 2.
 62: &apos;method def&apos; child has incorrect indentation level 8, expected level should be 4.
 63: &apos;method def&apos; child has incorrect indentation level 8, expected level should be 4.
 64: &apos;method def&apos; child has incorrect indentation level 8, expected level should be 4.
 66: &apos;method def&apos; child has incorrect indentation level 8, expected level should be 4.
 68: &apos;method def&apos; child has incorrect indentation level 8, expected level should be 4.
 69: &apos;method def rcurly&apos; has incorrect indentation level 4, expected level should be 2.
hadoop-ozone/ozone-manager/src/main/java/org/apache/hadoop/ozone/protocolPB/OzoneManagerRequestHandler.java
 781: &apos;throws&apos; has incorrect indentation level 4, expected level should be 6.

## rat check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2240-9psb4/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2240-9psb4/rat)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2240-9psb4/rat/summary.txt)

hadoop-ozone/tools/target/rat.txt: !????? /workdir/hadoop-ozone/tools/src/main/java/org/apache/hadoop/ozone/admin/om/GetServiceRolesSubcommand.java

## unit check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2240-9psb4/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2240-9psb4/unit)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2240-9psb4/unit/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2240-9psb4/unit/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.om.ratis.TestOzoneManagerDoubleBufferWithOMResponse](hadoop-ozone/ozone-manager/org.apache.hadoop.ozone.om.ratis.TestOzoneManagerDoubleBufferWithOMResponse.txt) ([output](hadoop-ozone/ozone-manager/org.apache.hadoop.ozone.om.ratis.TestOzoneManagerDoubleBufferWithOMResponse-output.txt))

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2240-9psb4/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2240-9psb4/integration)
   * [summary.md](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2240-9psb4/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2240-9psb4/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.client.rpc.TestOzoneRpcClientWithRatis](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneRpcClientWithRatis.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneRpcClientWithRatis-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower-output.txt))
 * [org.apache.hadoop.ozone.om.TestOzoneManagerHA](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA-output.txt))


# Tests with success status

## acceptance check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2240-9psb4/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2240-9psb4/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-q4/pr/pr-hdds-2240-9psb4/acceptance/summary.html)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2240-9psb4/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2240-9psb4/author)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2240-9psb4/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2240-9psb4/build)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-q4/master/pr/pr-hdds-2240-9psb4/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2240-9psb4/checkout)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-q4/tree/master/pr/pr-hdds-2240-9psb4/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
