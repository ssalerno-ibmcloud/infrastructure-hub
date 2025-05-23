---

copyright:
  years: 2020, 2025
lastupdated: "2025-04-28"

keywords: infrastructure

subcollection: infrastructure-hub

---

{{site.data.keyword.attribute-definition-list}}

# Networking services
{: #network}

You automatically get connected to the {{site.data.keyword.vpn_full}} when your {{site.data.keyword.cloud_notm}} account is set up. By default, your server has a public IP address and a private IP address. If you want your server to be private, you can either turn off the public interface after your server is provisioned or order your server as private. For more information, see [Getting started with Virtual Private Networking](/docs/iaas-vpn?topic=iaas-vpn-getting-started) for more information.

Check out the following tables for a summary of networking options.

## VPC infrastructure
{: #network-vpc}

Within the infrastructure layer, you can build a virtual private cloud, which is a virtual network that is tied to your {{site.data.keyword.cloud_notm}} account.

| Option | Description |
|--------|---------------|
| [Getting started with {{site.data.keyword.vpc_full}}](/docs/vpc?topic=vpc-getting-started)| Provides cloud security and the ability to dynamically scale your virtual server instances.  |
| [Load balancer for VPC](/docs/vpc?topic=vpc-load-balancers) | Distributes traffic among multiple server instances within the same region of your VPC. |
| [VPN for VPC](/docs/vpc?topic=vpc-using-vpn) | Securely connect your VPC to another private network. You can use VPN to set up an IPsec site-to-site tunnel between your VPC and your on-premises private network or another VPC. |
| [DNS Services](/docs/dns-svcs/getting-started) | Provides private DNS to Virtual Private Cloud (VPC) users.  |
| [Transit Gateway](/docs/transit-gateway?topic=transit-gateway-getting-started) | Interconnect IBM Cloud Classic and Virtual Private Cloud (VPC) infrastructures worldwide, keeping traffic within the IBM Cloud network. |
|[Direct Link 2.0](/docs/dl/getting-started)|Seamlessly connect your on-premises resources to your cloud resources. |
{: caption="Networking options - VPC" caption-side="top"}

## Classic infrastructure
{: #network-classic}

| Option | Description |
|--------|---------------|
| [Domain Name Service](/docs/dns-svcs?topic=dns-svcs-getting-started) | Provides a central location to view and manage your domains through the basic DNS management interface, and also gives you the option to manage reverse and secondary DNS in the same location for free of charge. |
| [Global IP addresses](/docs/subnets?topic=subnets-about-subnets-and-ips#global-ip-addresses) | Provide flexibility to shift workloads between servers, even across geographically disparate data centers. |
| [Load balancing](/docs/loadbalancer-service?topic=loadbalancer-service-getting-started) | Distributes processing and communications evenly across multiple servers within a data center so that a single device does not carry an entire load. |
| [Virtual Router Appliance](/docs/virtual-router-appliance?topic=virtual-router-appliance-getting-started-vra) | Selectively routes private and public network traffic through a full-featured enterprise router with firewall, traffic-shaping, policy-based routing, VPN, and a host of other features. |
| [IPSec VPN](/docs/iaas-vpn?topic=iaas-vpn-setup-ipsec-vpn#setup-ipsec-vpn) | A suite of protocols designed to authenticate and encrypt all IP traffic between two locations by using a tunnel mode that provides an encrypted site-to-site network. |
| [{{site.data.keyword.cloud_notm}} Direct Link](/docs/direct-link?topic=direct-link-get-started-with-ibm-cloud-direct-link#get-started-with-ibm-cloud-direct-link) | Leverages a Cloud Exchange provider to deliver connectivity to {{site.data.keyword.cloud_notm}} infrastructure locations. |
| [Gateway Appliances](/docs/gateway-appliance?topic=gateway-appliance-getting-started-ga) | Enhances control over network traffic, accelerates your network’s performance, and improves your network security. |
| [Hardware Firewalls](/docs/hardware-firewall-shared?topic=hardware-firewall-shared-getting-started) |Prevent unwanted traffic from hitting your servers, reduce your attack surface, and allow your server resources to be dedicated for their intended use. |
| [Fortigate Security Appliance 10 Gbps](/docs/fortigate-10g?topic=fortigate-10g-getting-started) | Protect traffic on multiple VLANs for both public and private networks.|
| [VLANs](/docs/vlans?topic=vlans-getting-started) | Isolate broadcast traffic on the public and private networks. |
| [Subnets](/docs/subnets?topic=subnets-getting-started) |Each subnet provides IP addresses to resources in different ways.  |
{: caption="Networking options - Classic" caption-side="top"}

## Next steps
{: #nextsteps5}

To continue, see [Building your infrastructure](/docs/infrastructure-hub?topic=infrastructure-hub-storage) with storage services.
