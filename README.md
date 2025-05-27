# AZ-104 Project: Secure VM Deployment and Remote Access (RDP)

In this project, I deployed a secure Windows virtual machine on Azure and enabled controlled remote access using Network Security Groups (NSGs). The VM was configured with RDP (port 3389) allowed via NSG to enable remote administration. I also added Microsoft Antimalware for additional security.

## Key Objectives
- Create a Windows VM with a secure name and region
- Configure size, admin credentials, and network options
- Set up a Network Security Group (NSG) with RDP rule
- Deploy Microsoft Antimalware extension
- Connect to the VM using Remote Desktop Protocol (RDP)

## Key Takeaways
- NSGs act like a virtual firewall to control traffic to/from Azure resources.
- Allowing only required ports (like 3389 for RDP) follows the principle of least privilege.
- Platform-managed encryption ensures baseline data security.
- Successful RDP login confirms the entire VM setup works end-to-end.

## Screenshots Included

### 1. VM Creation Started
![VM Creation](01-vm-deployment-started.png)

### 2. VM Successfully Created
![VM Created](02-vm-created-ade.png)

### 3. Disk Encryption Enabled
![Disk Encryption](03-disk-encryption-enabled.png)

### 4. Antimalware Extension Deployed
![Antimalware Extension](04-antimalware-extention-deployed.png)

### 5. NSG Rule for RDP Configured
![NSG Rule](05-rdp-nsg-rule-configured.png)

### 6. RDP Client Prompted for Connection
![RDP Attempt](06-rdp-client-connection-atempt.png)

### 7. RDP Session Successful
![RDP Success](07-rdp-session-success.jpg)
## Author
Olarinde Akinwale – Cloud Security Engineer in training
