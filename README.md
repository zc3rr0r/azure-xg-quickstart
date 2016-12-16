These templates deploy a Quickstart environment for Sophos XG firewall, consisting of:

 - One VNet 
 - Two subnets 
 - a Windows Server Active Directory
 - a Microsoft RDS deployment with a GW, CB and RDSH
 - an Azure lb for RD with a public IP for remote RD access (outbound filtering scenario)
 - a Microsoft Windows IIS host (running a template website for contoso.com)
 - a Sophos XG Firewall
 
All machines deployed through these templates are billed hourly through Marketplace in a PAYG scenario.

Note that the templates are not linked currently, so one has to manually deploy them in the following order:

 1. AD
 2. RDS
 3. IIS
 4. XG Firewall
