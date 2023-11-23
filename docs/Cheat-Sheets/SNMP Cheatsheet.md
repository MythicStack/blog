---
layout: default
title: SNMP Cheatsheet
nav_order: 2
parent: Cheatsheets
---

The "snmpwalk" program parses through information in the SNMP-MIB. Below are a series of OIDs that I have found useful. Unfortunately I have not had the opportunity to work with a Linux server so these for sure work on Windows, but might not work with Linux. When I get the opportunity to work with a Linux system in this way I will provide an updated list.


| Use                                                     | Object ID                |
|:--------------------------------------------------------|:------------------------:|
|Shows system description like OS and Hardware info.      | 1.3.6.1.2.1.1.1.0        |
|Shows the system's ObjectID.                             | 1.3.6.1.2.1.1.2.0        |
|Shows the system's Hostname.                             | 1.3.6.1.2.1.1.5          |
|Shows the system's Uptime.                               | 1.3.6.1.2.1.1.3.0        |
|Lists user accounts.                                     | 1.3.6.1.4.1.77.1.2.25    |
|Lists installed software.                                | 1.3.6.1.2.1.25.6.3.1.2   |
|Lists running processes on the system.                   | 1.3.6.1.2.1.25.4.2.1.2   |
|Lists the full path of running software.                 | 1.3.6.1.2.1.25.4.2.1.4   |
|Lists share information.                                 | 1.3.6.1.4.1.77.1.2.27    |
|Lists active TCP Ports.                                  | 1.3.6.1.2.1.6.13.1.3     |
|Lists network interfaces.                                | 1.3.6.1.2.1.2.2.1.2      |
