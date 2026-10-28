# Packet Tracer – Use the ipconfig Command

## Overview
This project demonstrates basic network troubleshooting using the Windows-style `ipconfig /all` command in Cisco Packet Tracer. The objective is to identify and correct an incorrect static IP configuration that prevents a PC from accessing a web server.

## Objectives
- Inspect IP configuration on four PCs.
- Identify an incorrect IP address, subnet mask, or default gateway.
- Correct the network configuration.
- Verify connectivity to the router and web server.

## Tools Used
- Cisco Packet Tracer
- Command Prompt
- IP Configuration utility
- Web Browser

## Network Details
- Network: `192.168.1.0/24`
- Subnet mask: `255.255.255.0`
- Addressing method: Static IPv4 addressing
- Web server: `www.cisco.pka`

## Procedure

### 1. Inspect Network Configuration
Executed the following command on each PC:

`ipconfig /all`

Recorded the IP address, subnet mask, and default gateway for comparison.

### 2. Identify the Misconfiguration
Compared each PC's settings against the expected network configuration and the addressing used by the other devices.

### 3. Correct the Configuration
Opened Desktop > IP Configuration on the affected PC and corrected the invalid setting using the values appropriate for the topology.

### 4. Verify Connectivity
Used ping to test connectivity and accessed `www.cisco.pka` through the web browser.

## Key Concepts Learned
- IPv4 addressing
- Subnet masks and default gateways
- Static IP configuration
- Network troubleshooting
- Connectivity testing
- Basic client-server communication

## Results
Document the PC that was incorrectly configured, the setting that was wrong, and the test results after correction.

## Evidence
Add screenshots showing the original configuration, the corrected settings, and successful connectivity.

## Skills Demonstrated
Cisco Packet Tracer, IPv4 networking, IP configuration, troubleshooting, and network diagnostics.
