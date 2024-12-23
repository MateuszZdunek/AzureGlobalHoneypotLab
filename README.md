## Project Overview

This project demonstrates the collection, enrichment, and visualization of failed Remote Desktop Protocol (RDP) login attempts on a Windows virtual machine hosted on Microsoft Azure. 

### Key Features
1. **Virtual Machine Setup**  
   A virtual machine was deployed with open firewall rules, allowing global access.  
2. **Log Monitoring**  
   Windows Event Viewer (Event ID 4625) was used to track failed login attempts.  
3. **Geo-Enrichment**  
   IP addresses were processed using a geolocation API to gather location data.  
4. **Data Visualization**  
   Logs were processed and sent to Azure Monitor Logs for analysis and visualization on an interactive map.

## Code
- [**PowerShell Script**](./powershell_script.ps1): Script to collect and send logs to Azure.
- [**KQL Query**](./kql_query.kql): Query for visualizing and analyzing RDP login attempts.

## Screenshots
### 1. Azure VM Configuration
![Azure VM NIC](./screenshots/NICConfig.png)
![Azure VM NIC](./screenshots/FirewallConfig.png)

### 2. Powershell Logs
![Powershell Logs](./screenshots/Powershell.png)

### 3. KQL Querry
![KQL Querry](./screenshots/KQL.png)

### 4. RDP Attempts Map
![RDP Attempts Map](./screenshots/map.png)
