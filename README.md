






Provisioning Template for Create Virtual Server
User Guide





Version
Remarks
Date
1.0
Provisioning Template User Guide for Create Virtual Server
21/07/2016
2.0
Updated document with installation of the template.
14/02/2017






1 Installation of the Template and Helper Script
1. Login to AppViewX.
2. On the left navigation menu, select Provisioning; and click Template.
3. On the upper right portion of the screen click on the  Import button.
4. The following screen will appear. 
5.  Please Select Template/Helper Script.
If Template is chosen,
i. Click on Browse and select the Zip File of the template which has to be installed/imported and click open.
ii. Click on upload to import the Zip file and display the templates present in the zip file.
iii. Click on submit to deploy the templates into the AppViewX Environment.
If Helper Script is chosen,
i Click on Browse and select the Zip File of the Helper script which has to be installed/imported and click open.
ii Click on upload to import the Zip file and display the Helper Scripts present in the zip file.
iii Click on submit to deploy the Helper Scripts into the AppViewX Environment.






1. Create VIP Template

1. Login to AppViewX.
2. On the left navigation menu, select Provisioning; and click Request
3. On the upper right portion of the screen, click the    Create button.
4. Select the provisioning template name from the list – ‘Create_VIP_Template’
Note: If no template is available, this indicates that the user role does not have permission to the requesting template.
5. Enter the provisioning request description – ‘Create Virtual Server on F5/Citrix device’.
6. Add a default Request scenario name relevant to the template. E.g.: VIP creation on F5/Citrix ADC.
7. Select the ADC vendor from the available list of vendors in the Vendor field. E.g.: F5, Citrix,...
If F5 is selected, then
i. Click on ‘Get Device List’ button to fetch the available list of devices in the inventory for the selected vendor.
ii. In the Device field, list of devices are populated based on the Vendor selected. Please select the device on which the VIP is to be created.
iii. Please enter a valid Application name in the App Name field.
iv. If the IP has to be fetched from the Infoblox IPAM system, select Yes in the ‘Integrate with Infoblox IPAM’ field.
v. Click on the ‘Get Infoblox devices’ button to fetch the IPAM devices from the inventory.
vi. Please enter the subnet in the Subnet field and click on ‘Get Free IP’ button.
vii. If Infoblox IPAM integration is not required, select No in the ‘Integrate with Infoblox IPAM’ field.
viii. Enter the IP and Port in the respective fields and click on Get Details.
ix. Select the Persistence profile from the list of available profiles in the Persistence field.
x. Specify if HTTP Profile has to be created from the Create HTTP Profile field and subsequently selecting the Defaults from.



xi. Specify if HTTP Monitor has to be setup. If yes, the following fields needs to be entered.


xii. Existing monitors can be applied to the Virtual Server by selecting any existing monitor from the Use Existing Monitor dropdown list.
xiii. The load balancing algorithm can be selected from the Load Balancing Method dropdown list.
xiv. Pool Member IP and Pool Member Port can be added and by clicking on the , the specific Pool members can be added to the tabular for associating to the Virtual Server.
xv. Click   Button; ensure that the Scenario is displayed on the right hand pane.
xvi. Click on Submit to generate work order(s) for the provisioning request.

If Citrix is selected, then
i. Click on ‘Get Device List’ button to fetch the available list of devices in the inventory for the selected vendor.
ii. In the Device field, list of devices are populated based on the Vendor selected. Please select the device on which the VIP is to be created.
iii. Please enter a valid Application name in the App Name field.
iv. If the IP has to be fetched from the Infoblox IPAM system, select Yes in the ‘Integrate with Infoblox IPAM’ field.
v. Click on the ‘Get Infoblox devices’ button to fetch the IPAM devices from the inventory.
vi. Please enter the subnet in the Subnet field and click on ‘Get Free IP’ button.
vii. If Infoblox IPAM integration is not required, select No in the ‘Integrate with Infoblox IPAM’ field.
viii. Enter the IP and Port in the respective fields and click on Get Details.
ix. Specify if HTTP Monitor has to be setup. If yes, the following fields needs to be entered.


x. Existing monitors can be applied to the Virtual Server by selecting any existing monitor from the Use Existing Monitor dropdown list.
xvii. The load balancing algorithm can be selected from the Load Balancing Method dropdown list. 
xviii. Server Name, Server IP and Service Port can be added and by clicking on the , the specific Service List can be added to the tabular for associating to the Virtual Server.
xix. Click   Button; ensure that the Scenario is displayed on the right hand pane.
xx. Click on Submit to generate work order(s) for the provisioning request.
