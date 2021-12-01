# Common Azure ARM Templates

## Azure Reference Architecture Templates

The templates in this section allow you to deploy VM Series firewalls set out in the Azure Reference Architecture Guide. 

<https://www.paloaltonetworks.com/resources/whitepapers/intelligent-architectures-azure-reference-architecture>

The design models in this section offer example architectures that secure inbound access to an application in Azure, the communication between private virtual machines and workloads, and the connection to your on-site networks.
The design models primarily differ in how traffic flows are divided amongst VM-Series firewalls while offering you flexibility in the number of firewalls, scale, and operational resiliency. Consider which model best fits your needs and use it as a starting point for your design. The design models in the reference design are the:


* Dedicated model

Inbound, outbound and east-west, and backhaul traffic are each on dedicated sets of firewalls. This model offers increased operational resiliency and reduces the chances of high bandwidth use from one traffic profile affecting another.
