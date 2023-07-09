<h1 style='text-align:center;'> Network Automation</h1>

### Telnet Script for remote configuration of a router

This project utilises python programming language to develop a basic script which automates the configuration
of a Router interface for remote management.

<hr>

<!-- ![Basic LAN Topology](basic%20LAN.png) </br> -->

<div align='center'><img src="basic%20LAN.png" alt="Network-diagram" width='50%' ></div>

- This demo is meant to serve as a brief introduction to network programming using Python.
- It is based on a practical course taught by David Bombal in his Python Network course for Network Engineers.
- For this Demonstration, the topology was was inteneded to be simple with just a single router, switch and PC(automation client) to represent the network administrator.
- The network topology was designed and simulated in GNS3. </br>
- The automation client is a PC running Ubuntu through which the Network administrator can
  remotely manage Network Devices on the Network. </br>
- For this demo the Router was the target device.

The script lets you configure the following on the router;

- telnet credentials to login
- Loopback address
- OSPF Areas
