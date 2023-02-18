#  Kerberos Authentication Implementation
![](/Image/1.png)

## Description
This project is aimed at implementing the Kerberos authentication protocol in a networked environment. The implementation involves setting up a Key Distribution Center (KDC) and configuring clients and servers to use the KDC for authentication.

##Project Architecture 
![](/Image/Architecure.png)

## Installation
The implementation requires the following components:
- Windows Server 2019
- Application Server (Microsoft Sql Server)
- Windows Client 10 (To test Access)
- Vmware Workstation 16 (To Create a Virtual Network)

The following steps can be taken to install and configure the components:
1. Install Windows Server and create a new domain active directory who has by default the Kerberos protocol, I chopse EMSI.MA as name of the domain.
2. Add all other machines to domain .
3. Install the server application in my case i choose Microsoft Sql Server
4. Then change the parametre of KDC in the default GPO

## Usage
Once the installation and configuration steps have been completed, the Kerberos authentication service can be used by clients and servers on the network. The following are some of the scenarios that can be tested:
- A client attempting to access a server with a valid Kerberos ticket.
- A client attempting to access a server with an expired or invalid Kerberos ticket.
- A client attempting to access a server with an incorrect password.
- A client attempting to access a server with a valid Kerberos ticket, but not authorized to access the requested resource.

## Credits
This project was developed by Hamza Achahboune, as part of Security course at EMSI Tangier. 

