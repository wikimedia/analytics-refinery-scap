The 'thin' environment exists so we can deploy refinery code without refinery artifacts.
These target hosts have smaller hard drives and need all the extra space they can get.
If this changes in the future, the thin environment targets can be moved back into the
main targets file and deployed along with the rest of the production nodes.

To deploy to just to thin host targets, do

  scap deploy -e thin

The 'hadoop-test' environment exists so we can deploy refinery to the Hadoop test cluster,
without impacting the production one.

To deploy to just to thin host targets, do
  scap deploy -e hadoop-test
