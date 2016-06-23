Site to Site VPN Connection

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https://raw.githubusercontent.com/jayparadis/cloud-templates/master/azure-site-to-site-create/azuredeploy.json?token=AAuWNczcZmInfA_d5uoki6EyS6JpX7yYks5XdRsJwA%3D%3D" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https://raw.githubusercontent.com/jayparadis/cloud-templates/master/azure-site-to-site-create/azuredeploy.json?token=AAuWNSC0pp1fFOczHgCtqGs1GZS2u--nks5XdRiYwA%3D%3D" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template will create a Virtual Network, a subnet for the network, a Virtual Network Gateway and a Connection to your network outside of Azure (defined as your `local` network). This could be anything such as your on-premises network and can even be used with other cloud networks such as [AWS Virtual Private Cloud](https://github.com/sedouard/aws-vpc-to-azure-vnet).

Please note that you must have a Public IP for your other network's VPN gateway and cannot be behind an NAT.

Although only the parameters in [azuredeploy.parameters.json](./azuredeploy.parameters.json) are necessary, you can override the defaults of any of the template parameters.
