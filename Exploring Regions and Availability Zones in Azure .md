## Regions in Azure:
Azure is a cloud computing platform provided by Microsoft, and it is globally distributed across multiple geographic locations known as regions. Each Azure region is a set of data centers deployed within a defined geographic area, and it is designed to provide low-latency access to Azure services for users and applications in that region.
- Rigions is nothing but a geographic area

## Availability Zones in Azure:
Azure Availability Zones are part of Azure's high-availability architecture, providing redundancy and resiliency for applications and data. Each Azure region is divided into multiple Availability Zones, which are essentially unique physical locations with independent power, cooling, and networking.
- simplyy, one data centre is 1 availability zone.
- Lets say in east US region we have 4 data centres, that is 4 availaibility zones.
- We will called them simply like zone 1 zone 2.

**Why is it imp to have the data centres isolated…?**
**Example**
- If we have any problem and the data centre in zone 1 is out, blacked out, then the request is sent to zone2 i.e another zone.
- If these zones are not isolated, Then all the data centres in whole region would be blacked out, and the users cant access the application.
