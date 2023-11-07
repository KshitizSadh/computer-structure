# COMPUTATION
1. **Host** - A host is any hardware device that has the capability of permitting access to a network via a user interface, specialized software, network address, protocol stack, or any other means. Some examples include, but are not limited to, computers, personal electronic devices, thin clients, and multi-functional devices.
 - BareMetal :- server with no os
2. **VIRTUAL MACHINE** - A virtual machine, commonly shortened to just VM, is no different than any other physical computer like a laptop, smart phone, or server. It has a CPU, memory, disks to store your files, and can connect to the internet if needed.
   
| Type I  | Type II |
| ------------- | ------------- |
| Native (bare metal)  | Hosted  |
| Directly on hardware and runs guest OS  | Runs on previously installed OS  |
| acts as light weight as it runs directly  | runs as software like other computer programs  |
|XEN,KVM |Virtual Box,Virtual work station|

3. **CONTAINER** - Containers are packages of software that contain all of the necessary elements to run in any environment. In this way, containers virtualize the operating system and run anywhere, from a private data center to the public cloud or even on a developer's personal laptop.  

  - *DOCKER* :-Docker is a software platform that allows you to build, test, and deploy applications quickly. Docker packages software into standardized units called containers that have everything the software needs to run including libraries, system tools, code, and runtime.  
 
 ![Docker-Logo_Horizontel_279x131 b8a5c41e56b77706656d61080f6a0217a3ba356d](https://github.com/KshitizSadh/computer-structure/assets/142923024/3d553528-eea8-49ef-86c1-de773818d3ff)  
 - *LXC* :- LXC (LinuX Containers) is a OS-level virtualization technology that allows creation and running of multiple isolated Linux virtual environments (VE) on a single control host.

![Untitled](https://github.com/KshitizSadh/computer-structure/assets/142923024/007b496b-c299-49e8-90f0-7bea3ed6e8d6)  
 | CONTAINER CLUSTER MANAGER |
 | --------------------------|
 |Apache, Mesos, Kubernetes, Rancher ,Nomad ,Amazon EC2 Conatiner Service ,Docker UCP |   

 
 | CONTAINER ENGINES |
 | ----------------- |
 |Docker hub, IBM WebSphere Hybrid Edition (Application Server & Liberty),Red Hat OpenShift Kubernetes Engine.,Oracle Cloud,Infrastructure Computer,Sandboxie.,Canonical MicroK8s.,canonical LXC.,resinOS.|
4. **ORCHESTRATORS** - Orchestration is the coordination and management of multiple computer systems, applications and/or services, stringing together multiple tasks in order to execute a larger workflow or process. These processes can consist of multiple tasks that are automated and can involve multiple systems.
 - SOME EXAMPLES OF ORCHESTRATORS    
   - KUBERNETES
   - DOCKER SWARM 
   - MESOS 
   - EKS 
   - ECS
 5. **SAAS** = Software as a service (or SaaS) is a way of delivering applications over the Internet—as a service. Instead of installing and maintaining software, you simply access it via the Internet, freeing yourself from complex software and hardware management.
 6. **IAAS** = infrastructure as a service is a cloud computing service model by means of which computing resources are supplied by a cloud services provider. The IaaS vendor provides the storage, network, servers, and virtualization. This service enables users to free themselves from maintaining an on-premises data center
 7. **PAAS** = Platform as a service (PaaS) or application platform as a service (aPaaS) or platform-based service is a category of cloud computing services that allows customers to provision, instantiate, run, and manage a modular bundle comprising a computing platform and one or more applications, without the complexity of building and maintaining the infrastructure typically associated with developing and launching the application(s), and to allow developers to create, develop, and package such software bundles.
 8. **cas**-Content as a service (CaaS) or managed content as a service (MCaaS) is a service-oriented model, where the service provider delivers the content on demand to the service consumer via web services that are licensed under subscription. The content is hosted by the service provider centrally in the cloud and offered to a number of consumers that need the content delivered into any applications or system, hence content can be demanded by the consumers as and when required.
# NETWORKING
![image](https://github.com/KshitizSadh/computer-structure/assets/142923024/dce15b84-8c81-447e-b0b8-bb9f01685bae)
1. **OSIMODEL/TCP-IP MODEL** = The Open Systems Interconnection model is a conceptual model from the International Organization for Standardization that "provides a common basis for the coordination of standards development for the purpose of systems interconnection."  

2. **NETWORK TOPOLOGIES** = A network topology is the physical and logical arrangement of nodes and connections in a network. Nodes usually include devices such as switches, routers and software with switch and router features.
![image](https://github.com/KshitizSadh/computer-structure/assets/142923024/d91a23e2-d0e1-4d61-bd36-9ff3b01f57fe)

3.  **CIDR NOTATIONS**

![image](https://github.com/KshitizSadh/computer-structure/assets/142923024/b9e2fa42-b450-4377-9bc6-df865bfeb8ab) 

4. **subnetting** = One goal of a subnet is to split a large network into a grouping of smaller, interconnected networks to help minimize traffic. This way, traffic doesn't have to flow through unnecessary routes, increasing network speeds. Subnetting, the segmentation of a network address space, improves address allocation efficiency
5. **SR-IOV** = The single root I/O virtualization (SR-IOV) interface is an extension to the PCI Express (PCIe) specification. SR-IOV allows a device, such as a network adapter, to separate access to its resources among various PCIe hardware functions. These functions consist of the following types: A PCIe Physical Function (PF).

   ![image](https://github.com/KshitizSadh/computer-structure/assets/142923024/902b51c3-7c3b-4012-b8aa-1613f2be2b0c)

6.**SR-IOV**- Single Root I/O Virtualization (SR-IOV) is a technology that allows a physical PCIe device to present itself multiple times through the PCIe bus. SR-IOV is an extension to the PCI Express (PCIe) specification. It allows a device, such as a network adapter, to separate access to its resources among various PCIe hardware functions.   

7. **NTP**- Network Time Protocol (NTP) is an internet protocol that synchronizes computer clock time sources in a network. NTP is one of the oldest parts of the TCP/IP suite. It runs on User Datagram Protocol (UDP), which in turn runs on IP.  

8. **PTP**- Precision Time Protocol (PTP) is a protocol that synchronizes clocks in a computer network. It's similar to Network Time Protocol (NTP), but PTP is more accurate, measuring in nanoseconds. PTP is used to synchronize clocks in systems that require precise time synchronization, such as:  
<img src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/38808ddb-e3ac-445b-b5eb-58cec8004bf7" height="400" width="350" align="right"> 
- Mobile networks
- Measurement and control systems
- The metaverse
  
9. **CISCO**- Cisco is a US technology company that develops, manufactures, and sells networking hardware, telecoms equipment, and other IT services and products.Cisco offers courses and certifications in: 
- Installing, monitoring, and troubleshooting network infrastructure products, Programming
- Computer Hardware Basics
  
10.**Mysterium Network**- Mysterium Network is a free, open-source network that provides anonymous access to the internet.Users and clients can pay to connect to these nodes, which provide: 
- A VPN or proxy service
- Access to the open internet
- A secure line of communication

11.**Kubernetes vs Mesos vs Dockerswarm**    
- Container orhestration tools
<img width="600" height="400" alt="Screenshot 2023-11-03 124703" src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/10f11bc8-5b75-445b-807b-3b977f141c2c">

12.*Control plane vs Data Plane**    
<img src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/9fcc5798-9b18-4a6d-884c-3dc6f5a09dce" width="700" height="400" >  

13.**COTS**-Commercial-off-the-shelf: A product that is a standard, existing hardware product that is available from commercial sources.COTS products are designed to be easily installed and interoperate with existing system components.  

14.**CIDR Notations**-CIDR notation, or Classless Inter-Domain Routing notation, is a way to represent IP addresses in computer networks. CIDR notation uses a slash ('/') character to separate a prefix from a suffix. The prefix is the IP address, and the suffix is a decimal number that indicates how many bits are in the entire address.  

15.**Subnetting**-Subnetting is a method of dividing a single physical network into logical sub-networks, also known as subnets.  
*Benifits*:
- Reduce network traffic
- Conceal network complexity
- Increase routing efficiency
- Enhance the security of the network

16.**L4 and L7 load balancers**  
- L4 load balancers deliver traffic with limited network information using a load balancing algorithm. They calculate the best server based on fewest connections and fastest server response times.
- L7 load balancers disconnect network traffic and process the message inside. They make a decision based on the content of the message. Once decided, they establish a new TCP connection to the designated upstream server and send the request to the server.

17.**SSO**-Single sign-on (SSO) is a system that allows users to access multiple applications and services with just one set of login credentials. SSO works by authenticating a user's identity once and then granting access to all of the applications and services that the user is authorized to access.   

18.**Okta**-The Okta app integrations in your org use Single Sign-On (SSO) to provide a seamless authentication experience for end users. After end users sign in to Okta, they can launch any of their assigned app integrations to access external applications and services without reentering their credentials.  

19.**OIDC**-OpenID Connect (OIDC) is an open authentication protocol that works on top of the OAuth 2.0 framework. It allows individuals to use single sign-on (SSO) to access relying party sites using OpenID Providers (OPs), such as an email provider or social network, to authenticate their identities.  

20.**LDAP(Lightweight directory access protocol)**-LDAP authentication is the process of verifying a user's identity by checking their credentials against an LDAP directory server.  

21.**CDN**-Content delivery networks (CDNs) work by establishing a point of presence (POP) or a group of CDN edge servers at multiple geographical locations. This geographically distributed network works on the principles of caching, dynamic acceleration, and edge logic computations.    

22.**API Gateway**-An application programming interface (API) gateway is software that takes an application user's request, routes it to one or more backend services, gathers the appropriate data and delivers it to the user in a single, combined package.  

23.**Isolation**-An isolated local network consists of servers that are connected in an environment which has no connection to any other network. In this model, there is zero network connectivity to a larger internal network or the Internet.  

24.**Site to site VPN**-A site-to-site virtual private network (VPN) is a way to connect local area networks (LANs) in multiple locations across the public internet. It allows employees in different sites to securely share resources and information.   

25.**Client to site VPN**-A client-to-site VPN (Virtual Private Network) is a type of VPN that connects a single device, such as a laptop or smartphone, to a remote network, such as a corporate or cloud network.      
![1_2LhRE8Y2KD8hZhcz9BNYFA](https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/b44adbf9-79ee-42b7-9e4a-a042b5066b9a) 

# STORAGE
1.**RAID**- RAID stands for "Redundant Array of Inexpensive Disks" or "Redundant Array of Independent Disks". It's a data storage virtualization technology that combines multiple physical disk drive components into one or more logical units.  
RAID is used for:    
<img src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/41a1ccf5-2e22-4c8a-99d2-33aadefc7d92" height="250" width="450" align="right">
- Data redundancy
- Performance improvement
- Storing the same idea in different places
- Applications that require high data read/write transfer rates for large sequential files
- Enabling the array to function, even if one drive were to fail

2.**Object, file and block storage**    
<img src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/935f9697-575e-4662-a855-76f82fa70197" width="750"  height="450">

3.**Sharding**-Database sharding is the process of breaking up large database tables into smaller chunks called shards. A shard is a horizontal data partition that contains a subset of the total data set.     
<img src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/9ae45b73-327b-4566-89fd-4716037fbb2c" width="600" height="300">  
*Types of sharding*  
<img src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/9a7bfe17-2caa-42c3-ac51-add91f83a8f3" width="600" height="400">  

  
4.**DATA CENTERS**- A data center is a physical facility that stores a company's critical applications and data. It contains computing and networking equipment that is used to: 
- Collect, process, and store data
- Distribute and enable access to resources
  
5.**HCL**-HCL stands for Hindustan Computers Limited. HCL is an Indian multinational IT services and consulting company.HCL offers data center solutions, including: Modernization, Platform tech refresh, Datacenter consolidation, Datacenter migration, Hybrid cloud.  

6.**Hyperscale Data Center**-A hyperscale data center is a large facility that houses critical compute and network infrastructure. These facilities are designed to support robust and scalable workloads.They are often associated with large companies that require vast data processing and storage requirements, such as: Google, Amazon, Microsoft, Facebook, Apple.Hyperscale data centers typically house 5,000 or more servers.  

7.**Public Data centers**-A public data center is a facility that provides shared access to applications and data using a complex network, compute, and storage infrastructure.Some of the most reliable colocation data center companies are:   

- QTS Realty Trust Inc (NYSE: QTS)
- Digital Realty (NYSE: DLR)
- Equinix (NASDAQ)

8.**NFS**-NFS stands for Network File System. It is a file system mechanism that allows users to store and retrieve data from multiple disks and directories across a shared network. NFS is a distributed file system protocol that allows users to access files and directories located on remote computers and treat those files and directories as if they were local. 

 9. **san**- A storage area network or storage network is a computer network which provides access to consolidated, block-level data storage. SANs are primarily used to access data storage devices, such as disk arrays and tape libraries from servers so that the devices appear to the operating system as direct-attached storage.  
![image](https://github.com/KshitizSadh/computer-structure/assets/142923024/d8c953bc-ff6c-42ec-9a37-e510a5c1e2de)

10.**NAS**-Network-attached storage (NAS) is a file-dedicated storage device that makes data continuously available for employees to collaborate effectively over a network. Any computer network has interconnected server machines and client machines that send requests to the servers

![image](https://github.com/KshitizSadh/computer-structure/assets/142923024/ac194e04-8d1a-4f0d-aaaa-0c657dbc961b)

11. **DISKIOPS**- IOPS, pronounced “eye ops,” is the measurement of the number of input/output operations a storage device can complete within a single second. It's a standard performance benchmark for solid-state drives, hard drives, flash drives, and network attached storage (NAS) devices. The IOP needs to be fast to avoid latency in servers.
12. **Key- Value stores**- A key-value store, or key-value database is a simple database that uses an associative array (think of a map or dictionary) as the fundamental data model where each key is associated with one and only one value in a collection. This relationship is referred to as a key-value pair.
    13. **NFS**-Network File System (NFS) is a distributed file system protocol originally developed by Sun Microsystems (Sun) in 1984,[1] allowing a user on a client computer to access files over a computer network much like local storage is accessed. NFS, like many other protocols, builds on the Open Network Computing Remote Procedure Call (ONC RPC) system. NFS is an open IETF standard defined in a Request for Comments (RFC), allowing anyone to implement the protocol.
# security
  1. **SSL Certificate** 
      | SINGLE | MUTUAL |
      | ------ | ------- |
 2. **PKL infrastructure**-A public key infrastructure (PKI) is a set of roles, policies, hardware, software and procedures needed to create, manage, distribute, use, store and revoke digital certificates and manage public-key encryption. The purpose of a PKI is to facilitate the secure electronic transfer of information for a range of network activities such as e-commerce, internet banking and confidential email. It is required for activities where simple passwords are an inadequate authentication method and more rigorous proof is required to confirm the identity of the parties involved in the communication and to validate the information being transferred.
 3. **ZERO TRUST SECURITY**- Zero Trust security means that no one is trusted by default from inside or outside the network, and verification is required from everyone trying to gain access to resources on the network. This added layer of security has been shown to prevent data breaches 
 4. **ZERO TOUCH SECURITY**- Zero touch IT can be used to deploy enhanced cybersecurity measures on employee devices from day one. Rather than manually installing antivirus software, for example, zero touch can make this step standard practice for new device setup, which helps prevent security threats like data breaches and malware attacks.
 5. **SITE-TO-SITE VPN**-A site-to-site virtual private network (VPN) refers to a connection set up between multiple networks. This could be a corporate network where multiple offices work in conjunction with each other or a branch office network with a central office and multiple branch locations.

 ![image](https://github.com/KshitizSadh/computer-structure/assets/142923024/44868d6b-bf06-4c5b-84d4-e523336aa82b)   
 6. **CLIENT-TO-SITE VPN**-In a Client-to-Site Virtual Private Network (VPN) connection, clients from the Internet can connect to the server to access the corporate network or Local Area Network (LAN) behind the server but still maintains the security of the network and its resources.  
 ![image](https://github.com/KshitizSadh/computer-structure/assets/142923024/a006b688-d25f-4adf-a252-ea38f366cc9e)  
 7.**Security Compliance**-Security compliance management is that set of policies, procedures, and other internal controls that an organization uses to fulfill its regulatory requirements for data privacy and protection.  
 # LOAD BALANCER
 | L4 LOAD BALANCER | L7 LOAD BALCANCER |
 |------------------|-------------------|
 |L4 Load Balancer (Transport Layer Load Balancer): L4 load balancers operate at the transport layer (Layer 4) of the OSI model. They primarily focus on distributing network traffic based on information available in the transport layer protocols such as IP addresses and port numbers. L4 load balancers are typically transparent to the application layer protocols and don’t inspect the content of network packets.|L7 Load Balancer (Application Layer Load Balancer): L7 load balancers operate at the application layer (Layer 7) of the OSI model. They have the ability to understand and interpret the content of network packets, including application layer protocols such as HTTP, HTTPS, SMTP, or FTP. L7 load balancers can make routing decisions based on application-specific data, enabling advanced traffic management and application-aware load balancing.|  

 - **Load Balancing Algorithms**:A load balancer is a software or hardware device that keeps any one server from becoming overloaded. A load balancing algorithm is the logic that a load balancer uses to distribute network traffic between servers (an algorithm is a set of predefined rules.
    - *Dynamic load balancing algorithms*
    - *Static load balancing algorithms*
 - **REVERSE PROXY**:  A reverse proxy is a server that sits in front of web servers and forwards client (e.g. web browser) requests to those web servers. Reverse proxies are typically implemented to help increase security, performance, and reliability.
   | EXAMPLES |
   |--------------|
   |HAPROXY, NGINX , APACHE , Træfɪk |
 - **FORWARD PROXY**: A forward proxy is an intermediary that sits between one or more user devices and the internet. Instead of validating a client request and sending it directly to a web server, a forward proxy server evaluates the request, takes any needed actions, and routes the request to the destination on the client's behalf.
# HIGH AVAILBLITY
1.**Distributed Systems(clusters)**- A distributed system is simply any environment where multiple computers or devices are working on a variety of tasks and components, all spread across a network.  

![image](https://github.com/KshitizSadh/computer-structure/assets/142923024/9c313886-c577-46ee-b5e4-be32527f82e7)


2.**Fall-Over Mechanisms**- the transfer of workload from a primary system to a secondary system in the event of a failure on the primary system. When workload has been transferred like this, the secondary system is said to have taken over the workload of the failed primary system.  

|  Horizontal Scaling | Vertical Scaling |
|---------------------|------------------|
|When new server racks are added to the existing system to meet the higher expectation, it is known as horizontal scaling. | When new resources are added to the existing system to meet the expectation, it is known as vertical scaling. | 





 
 





