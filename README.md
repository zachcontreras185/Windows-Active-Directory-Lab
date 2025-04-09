# Windows Active Directory Lab

## Objective
The Windows Active Directory (AD) Lab project aimed to simulate a corporate Windows server enviroment complete with users and groups all under one domain. The primary focus was to gain hands-on experience and understanding in deploying a secure and efficient AD infrastructure while ensuring proper integration with other Windows Server services. This includes creating and managing user accounts, organizational units, and group policies; which are all tasks completeted in this lab. 

### Skills Learned
- Learned the installation and configuration of Active Directory Domain Services (AD DS) on Windows Server.
- Proficency in the creation and management of user accounts, groups, and organizational units (OUs).
- Implementation of security settings and software deployment through Group Policy Objects (GPOs).
- Configuring DNS and DHCP settings in Active Directory.
- Connected various Windows ans Linux machines to the domain, assigning them a user and password. 

### Tools Used
- Windows Server 2025 as the server manager OS
- Windows 11 as a user machine
- Ubuntu Linux as a user machine

## Screenshots

![VirtualBox_project-px2-dc_01_04_2025_17_42_06](https://github.com/user-attachments/assets/3e9c7288-bd2c-4e95-b9e6-0281193f2180)

*Ref 1: Creation of the Active Directory Domain Controller. I created the forest under the DC and named it "CORP.project-px2-dc.com".*





![VirtualBox_project-px2-dc_01_04_2025_18_00_10](https://github.com/user-attachments/assets/18db6eb0-12ef-4f1d-8125-f791131e5bf7)

*Ref 2: Creation of a user named "John Doe". I logged them into a seperate Windows 11 machine and configured it so that the user could not change the password as as security measure.*






![VirtualBox_project-px2-dc_02_04_2025_00_34_27](https://github.com/user-attachments/assets/685d920f-fefc-4d86-ab45-d4eb2583a100)

*Ref 3: Each service up and running. I configured the ADDC, DHCP, AND DNS servers for ease of user integration and ease of network & ip-address management."*






![VirtualBox_project-px2-linux-client_02_04_2025_00_59_42](https://github.com/user-attachments/assets/29511f05-4eb9-4cdb-b744-b93afaa4ee37)
![VirtualBox_project-px2-linux-client_02_04_2025_01_01_02](https://github.com/user-attachments/assets/6d6a65e2-ba14-4b32-92e6-75898b5f987b)

*Ref 4: Connecting a Ubuntu Linux machine to the CORP.project-px2-dc.com DC through the CLI. User was created under the name "Jane Doe".*



