# TASK-1

Intership Task 1 : Scan your Local Network for Open ports
Tool Used :
nmap - to scan local network
Scan Date: June 23, 2025
Target IP: 10.87.3.216
Host Status: Up
Scan Method: TCP SYN Scan with Service Version Detection
Open Ports Found: 3
Operating System Detected: Windows
Service Detection: Enabled

| **Port** | **Protocol** | **State** | **Service**    | **Description**                                         |
| -------- | ------------ | --------- | -------------- | ------------------------------------------------------- |
| 135      | TCP          | Open      | `msrpc`        | Microsoft RPC (Remote Procedure Call)                   |
| 139      | TCP          | Open      | `netbios-ssn`  | NetBIOS Session Service – used for file/printer sharing |
| 445      | TCP          | Open      | `microsoft-ds` | Microsoft Directory Services – SMB over TCP             |
