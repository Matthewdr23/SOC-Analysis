# SIEMS
The purpose of this repository is to store all of the information that I have gathered in regards to SIEMs. 
## Table of Contents
1. [Introduction of SIEM Alerts]()
2. [Log Analysis: Using a SIEM]()


# Introduction of SIEM Alerts
The thing about SIEM alerts in the field is that the more time you spend on an alert the less time youb have in the day for the other 100s of alerts waiting to be reviewed. 

You need to be able to carefully look through each alert with detail and confidence so that no mistakes are made but also flash like efficency so that your back log does not become overloaded. 

The more alerts you tackle and close, the faster you can respond to new attacks and handle the 100s of alerts thaty come through any SOC. 

</br>

# Log Analysis: Using a SIEM

## Ingesting Log Data with a SIEM
SIEMs store, search, analyze, and visulaize data form mulitple sources, in any format and in real-time.  

Every device in the network generates some kind of log whenever an activity is performed on it, like a user visiting a website, connecting to SSH, logging into their workstation, and so many more. 

### Windows Machines
Windows records every event that can viewed through the Event Viewer Utility. One of the things that it does is it assigns a unique ID to each type of log activity. This makes it easier for the analyst to examine and keep track of. 

To view events in a Windows environment, 
```
Type: Event Viewer
```
In the ***Search Bar***