<h1>Wireshark Packet Analysis Lab</h1>

<h2>Description</h2>
This project is a report of the findings in a fictional scenario in which a suspected security incident happened on a home network. This project demonstrates utilizing wireshark to analyze packets and network traffic on a network, and tying them to potential indicators of compromise (IoCs) to construct a scenario of the series of events that transpired.
<br />


<h2>Utilities Used</h2>

- <b>Wireshark</b> 
- <b>Network Miner</b>
- <b>Snort</b>

<h2>Environments Used </h2>

- <b>Windows 10 via Virtualization</b>

## Introduction to the Lab
To begin with, this lab starts out with a fictional scenario of a home network suspected of being under attack. This home network is very basic in utilization, only really being utilized to connect some home devices and access emails. After the suspected attack is terminated, we are provided with a .pcap file that allows us to see the network traffic that happened during this suspected security incident. It is our responsibility then, to see if there are any IoCs that pop up, and try to string together a narrative that fits what happened on the security incident. We'll be using Wireshark and Network Miner to examine the .pcap file, and then use Snort at the end to validate our findings.

## Basic Examination of the Traffic
Though there are various tools we will be using, let’s first use Wireshark to get a general view of this capture file. This is the very first view of the p


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
