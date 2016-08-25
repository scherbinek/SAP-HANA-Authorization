# SAP HANA Authorization
Official SAP Template for SAP HANA Authorizations

Template by "How to Define Standard Roles for SAP HANA Systems" from Richard Bremer (http://scn.sap.com/docs/DOC-53974). 
Refactored from a Delivery Unit (DU) to a Export Project. 

<b>Things to mind!</b><br>
1. Import the ZIP folder as Project to your Content as Package. It is not a Delivery Unit!<br>
2. After Importing the ZIP folder some .HDBROLE Files are inactive. Either due to dependencies or at least due to a missing package system-local.public<br>
3. Please assign afterwards the roles to the different user (with your SYSTEM user)<br>
3. Read the authorization concept on http://scn.sap.com/docs/DOC-53974 for the architecture<br>
4. Feel free to modify or add roles on purpose for you individual authorization concept<br>
