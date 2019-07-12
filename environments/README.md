The notebook environment exists so we can deploy refinery code without refinery artifacts.
The notebook hosts have smaller hard drives and need all the extra space they can get.
If this changes in the future, the notebook environment targets can be moved back into the
main targets file and deployed along with the rest of the production nodes.

To deploy to notebooks, do

  scap deploy -e notebook

