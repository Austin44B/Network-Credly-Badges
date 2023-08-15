# Network-Credly-Badges
Explanations of each badge earned through real world lab environments to test understanding of the Network+ skills outlined by Comptia.

#

    Table Of Contents :
      1) Architecture
      2) Infrastructure
      3) Operations
      4) Security
      5) Troubleshooting

      Note : Each badge hyper link is to Credly to verify the earning of the badge, and some additional 
              information.
#

In earning the Network+ [Architecture](https://www.credly.com/badges/7ae99438-1518-40c9-adfc-ed81aeea183e/public_url) badge : 

<img width="270" alt="image" src="https://github.com/Austin44B/Network-Credly-Badges/assets/134319619/6c8a48ae-59f5-41ff-90dc-377826591191">


I Configured IPv4 static addressing by testing connectivity between two servers through changing various IP addresses and subnet masks. I then analyzed the results of these changes to recognize misconfigurations and legitimate IP address settings.

I also learned how to configure dynamic routing and static Routing using the GNS3 network simulator to configure router interfaces, static routes and internetwork running the RIP dynamic routing protocol. I then proceeded to analyze documentation and use command-line tools to implement router configurations and dynamic routing protocols quickly and accurately.

I finished up this badge by learning how to configure remote access by configuring encrypted communication between systems using an IPSec policy that requires a client to establish a secure connection with a server. IPsec policies can be enabled to encrypt connections between systems, whether on an internal LAN or a VPN connection. The principle is the same in both cases. A zero-trust model ensures that all communications between servers or between servers and clients is authenticated, authorized, and encrypted. This type of model depends heavily on the use of digital certificates to identify each host. Certificates can be deployed along with Internet Protocol Security (IPSec) to meet some of the goals of zero trust.

A digital certificate can be used to prove the identity of a subject, whether that means a hardware server, virtual machine, container, smartphone, or user account.
On the Internet, certificates are issued by public certification authorities (CAs). Most browsers and client apps are configured to trust these public CAs by default. On a private domain network, you can use the Windows Certification Authority role to issue certificates that will be trusted by accounts and services within the domain.

The CompTia Network+ Architecture badge covers exam objectives in sections, 1.4, 2.2,  4.4, 5.3

#

In earning the Network+ [Infrastructure](https://www.credly.com/badges/ddc626aa-1a93-4d99-b05f-64363c2d94cf/public_url) badge : 


<img width="264" alt="image" src="https://github.com/Austin44B/Network-Credly-Badges/assets/134319619/77f213cc-7a6b-4dee-a714-6c28e9ad8379">


I configured a SOHO Router by connecting to a small home router through using SSH, and establishing an HTTP connection. I then configured an administrative password, and displayed common configurations and IP address settings.

I then configured interface settings using the GNS3 network simulator to investigate the properties of local networks built using hubs, unmanaged switches, and managed switches.

The Graphical Network Simulator v3 (GNS3) is software that allows simulated and emulated appliances and virtual machines to be configured into network topologies within a graphical workspace, making it easy to visualize the arrangement of nodes and links. It is very widely used for network development, testing, and training.

At layers 1 and 2, the majority of networks are built by connecting end system interfaces to intermediate system interfaces. While networks of this type are now mostly built using Ethernet switches as the intermediate system, it is important to understand legacy technologies, such as hubs.

While unmanaged switches perform better than hubs, they are only suitable for use on small networks. Enterprise networks require more features to ensure reliable performance and secure operation. These features are obtained by provisioning managed switches. A managed switch has a command line interface (CLI) to allow configuration of interface settings and optional features.

With this understanding I then configured ports on a managed switch to implement a basic network. Using the NVIDIA Cumulus VX network appliance. Cumulus is a white box switch NOS. White box meaning that the switch hardware and software can be provisioned separately. The Cumulus VX version runs on ordinary PC hardware.

Finally in earning this badge I developed documentation for windows networks, using network scanners and system tools to gather hostnames, IP address configurations, DNS resources records, DHCP reservations and other information for network hosts about nodes on two network segments. I then gathered system information from virtual machines and from network services, and documented this information in the spreadsheet as well, also including the documenting of baseline configurations.

The CompTia Network+ Infrastructure badge covers exam objectives in sections, 1.1, 2.1, 2.3, 3.2, 5.3

#

In earning the Network+ [Operations](https://www.credly.com/badges/0d60fce5-749a-4b00-8c6d-d7c015514a19/public_url) badge : 

<img width="265" alt="image" src="https://github.com/Austin44B/Network-Credly-Badges/assets/134319619/1e7d9cf0-ddd3-4f97-b45b-0ed2d92e508b">

   I learned how to analyze ARP traffic by investigating with several troubleshooting tools to learn more about the relationship between ARP and IP addresses. I then displayed network adapter properties, used ipconfig, displayed the ARP cache, and captured network traffic by using tcpdump.

   I also learned that manual configuration of network settings is time-consuming and highly susceptible to errors. For most servers, it is best to use autoconfiguration. The two main tools for doing this are the Dynamic Host Configuration Protocol (DHCP) and Domain Name System (DNS) servers. Additionally Windows Server offers replication of the DHCP configuration and database between two servers. This can be done for load balancing or fault tolerance.

I analyzed a DHCP server configuration by displaying current DHCP server configurations for two subnets, including reserved addresses before creating a new scope. Next I Created a new scope of available addresses and configured DHCP replication for fault tolerance. And finally, I configured a DHCP client to receive IP address settings from the DHCP server.

   Most service-to-service communication and almost all user-facing apps depend on named resources rather than using IP addresses directly. DNS provides a system for sharing records about how host names and domain namespaces map to IP addresses.

DNS clients cache information to speed up the name resolution process. Sometimes this cached information is outdated and must be cleared to restore network functionality. Using nslookup to display name resolution information I configured DNS records on a virtual machine. I then used the ipconfig command to update DNS information after troubleshooting why a client computer couldn't successfully resolve the new name and IP address settings. 

   Lastly, I analyzed Network Performance after configuring a file share between two virtual machines, and then using various network monitoring tools such as Windows Performance Monitor, Wireshark, and the Linux tool iftop to evaluate and review network performance during the transfer of a very large file into a folder across the network.


The CompTia Network+ Operations badge covers exam objectives in sections, 1.4, 1.6, 3.1, 5.3

#

In earning the Network+ [Security](https://www.credly.com/badges/a39acf89-2227-4ae8-af5d-75a2bb9a940d/public_url) badge : 

<img width="268" alt="image" src="https://github.com/Austin44B/Network-Credly-Badges/assets/134319619/3983b2fc-efb2-4e39-ae83-38aa28fbeab4">

I learned how to scan a webserver to display open ports and then capture HTTP, SSH and ping network traffic to the web server by using tcpdump which is a packet sniffer, I then examined the captured information by using both tcpdump and Wireshark.

I used tools to test IP configurations and configure network interfaces and name resolutions on Windows and Linux ( Using Cockpit ) devices.

I learned how to configure secure access channels I first had to secure a SSH remote administration tool by confirming password authentication and configure security warnings. I then configured key-based authentication to prevent root user from authenticating over SSH. Key-based authentication is more secure and it alleviates the need to remember passwords. A private key is stored on the client computer and a related public key is copied to the remote SSH server. During the authentication process, the two keys are compared instead of a password being submitted. and finally I managed SSH log files to understand which users are remotely connecting to the server.

And I finally learned how to analyze an on-path attack, by ethically perpetrating a Man-in-the-Middle attack on a network node by using a tool called Ettercap for ARP spoofing/poisoning. I first documented the MAC address of the server, then configured the MitM attack and packet capture, I then examined the captured packets and confirmed the attack redirected packets way from the legitimate router interface to the "attacker's" own network interface. I then verified the attack was over by checking the MAC address information that was documented for the server.

The CompTia Network+ Security badge covers exam objectives in sections, 1.1, 1.5, 4.2, 5.3

#

In earning the Network+ [Troubleshooting](https://www.credly.com/badges/5ceb1f4e-7d6b-45ea-9703-717844959bd1/public_url) badge : 

<img width="273" alt="image" src="https://github.com/Austin44B/Network-Credly-Badges/assets/134319619/faf2b00b-32f8-466e-b72a-3ca5333efa1c">

I used various nmap scans to display information about nodes on a network such as open ports and services. I then used netdiscover to display MAC address information. And finally, using Wireshark I intercepted TCP and UDP traffic to learn more about these Transport layer protocols.

I then learned about configuring Syslog's, by configuring a Linux server as a central log file repository,  And then configured another server and a router to forward their log files to this repository.

I also learned how to backup and restore network device configurations on a windows server, a Linux-hosted web site, and a pfsense router. I also learned common disaster recovery term.

The CompTia Network+ Troubleshooting badge covers exam objectives in sections, 1.5, 3.1, 3.3

#
#
