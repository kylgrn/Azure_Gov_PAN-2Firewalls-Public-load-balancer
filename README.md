
# Azure_Gov_PAN-2Firewalls-Public-load-balancer
<a href="https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fkylgrn%2FAzure_Gov_PAN-2Firewalls-Public-load-balancer%2Fmaster%2FAzure_Gov_PAN-2Firewalls-Public-load-balancer%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

**This templated is a revised version of the official Palo Alto Azure template but has been updated to work with Azure Government**
<br>
<br>
<b>Original text:</b>
<br>
<br>
This template was created to support the deployment of a Public Azure Load Balancer in front of 2 Palo Alto Networks Firewalls. It supports the following features:
<br>
<br>
The 2 firewalls deploys with 4-8 interfaces. 1 MGMT and 3-7 data plane.
Static IP addresses are assigned to the interfaces based on the input in the starting ip address fields.
This template deploys into existing VNETs and storage accounts within the same region. As a result, the storage account and VNET must be created before deploying this template.
<br>
<br>
  -The following Storage Account types are supported:<br>
              -Standard_LRS<br>
              -Standard_GRS<br>
              -Standard_RAGRS<br>
              -Premium_LRS<br>
  -The following VMs are supported:<br>
              -Standard_D3<br>
              -Standard_D4<br>
              -Standard_D3_v2<br>
              -Standard_D4_v2<br>
              -Standard_A4<br>
              -Standard_DS3_v2<br>
              -Standard_DS4_v2<br>
  -The following VMs Licenses:<br>
       	      -Byol<br>
              -Bundle1<br>
              -Bundle2<br>
  -The following PAN OS Options:<br>
              -Latest<br>
              -7.1.1 <br>
        <br><br>
              
  NOTE: Make sure the VMs are supported in the specific Storage Account Type and Azure Region.
