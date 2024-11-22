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
