# Active Domain-Domain Controller (AD-DC)
Project Title: Active Directory Deployment and Security Enhancement

Objective:
To create a comprehensive Active Directory environment showcasing domain creation, network configurations, user account generation, and client connectivity, with a focus on security measures.

Project Overview:
I deployed a virtualized environment using Oracle VirtualBox with Windows Server 2019 as the domain controller. The domain "mydomain.com" was established with two network adapters, one for the internal network and another for internet connectivity. The setup included the implementation of RAS/NAT and a DHCP scope. A PowerShell script was executed to generate 1000 user accounts, and a client VM was created and connected to the internal network.

Accomplishments:
Domain Creation: Successfully established the "mydomain.com" domain.
![Client1_vm_internal_network](https://github.com/day-zen/AD-DC/assets/153837646/bb898eb2-1bfd-4ece-94d9-6472bc140081)

Network Configuration: Configured two network adapters for internal and internet connectivity.
![Capture](https://github.com/day-zen/AD-DC/assets/153837646/cf7b2a77-fb95-4033-b713-3105b4264a09)

User Account Generation: Employed a PowerShell script to generate 1000 user accounts for testing purposes.
![AD_PowerShell_Create_Users](https://github.com/day-zen/AD-DC/assets/153837646/fa3fb1c0-d4f8-4e7b-bfe7-e6768b6e92c5)
![AD_PowerShell_Create_Users_Complete](https://github.com/day-zen/AD-DC/assets/153837646/dc0a48f8-7ded-45e0-89a2-e23e42d2c101)

Client Connectivity: Connected a client VM to the internal network, enabling successful logins for created users.
![DHCP_Server](https://github.com/day-zen/AD-DC/assets/153837646/7df99c0e-f51b-4d8e-9e11-132607d60a4b)
![whoami](https://github.com/day-zen/AD-DC/assets/153837646/14c64070-f21f-4acd-8016-5846414cb32c)

Enhancements Implemented:

Group Policies: Implemented Group Policies for enforcing security settings on client machines.

Security Auditing: Enabled security auditing to monitor and track security-related events.

Security Groups: Utilized security groups for effective access control, implementing role-based access control (RBAC).

Firewall Rules: Configured firewall rules on both domain controller and client machine to control traffic and simulate network segmentation.

Monitoring and Logging: Set up monitoring tools and centralized logging for detecting and responding to security incidents.

Backup and Recovery: Implemented a backup strategy for Active Directory, ensuring a tested restoration process.

Penetration Testing: Conducted penetration testing to identify and address potential vulnerabilities.

Documentation: Provided comprehensive documentation covering configurations, scripts, and security measures.

Recommendations:
Continued monitoring, regular security audits, and periodic penetration testing should be conducted to ensure ongoing security resilience. Documentation should be maintained and updated as the environment evolves.

Conclusion:
The successful deployment of the Active Directory environment, coupled with enhanced security measures, demonstrates a robust foundation for further cybersecurity initiatives. This project highlights a proactive approach to securing network infrastructure.
