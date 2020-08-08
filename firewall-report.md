# Report on Firewall

## Introduction

- A **Firewall** is a software program or a piece of hardware that helps to defend from **hackers, viruses, and worms** that try to attack over the internet.
- A software firewall is a program installed in your system, whereas a hardware firewall is a device placed between your network and the internet.
- The basic task of the firewall is to check and see if the coming data passes the security criteria, otherwise, they are blocked by the firewall.

## Types of Protection in Firewall

#### 1. Packet Filtering

This firewall maintains the list of allowed and not-allowed computers. It blocks the request if it falls under the not-allowed section of the firewall list.

#### 2. Statefull Inspection

This firewall maintains the conversation list between the user and the website. This is because if an attacker tries to send any malicious data with the requested data, the firewall knows that you are accessing data from a particular source only and the malicious data will be blocked.

#### 3. Proxy Firewall

This firewall hides the identity of the user by blocking the internal network from being exposed to the internet.

## Types of Firewall

#### 1. Packet Filtering Firewall

This firewall checks for the sender's & receiver's IP address and port number in the data packet. It verifies the data packet by the rules in the access control list.

#### 2. Application Firewall

This firewall does not let the webserver know the origin of the request. It hides the information of the local network and the server thinks that the data has been requested from the application firewall.

#### 3. Hybrid Firewall

This firewall is the combination of both packet filtering and application firewall. They are both used in the form of series hence they provide the best security.

## Limitation of Firewall

- The firewall cannot protect against the attack which bypasses the firewall.
- The firewall is not capable of protecting from the internal threat.
- It does not have any anti-virus properties so we need to have an extra layer of protection in the form of anti-viruses.

References :

1. [Firewall Explanation Video.](https://www.youtube.com/watch?v=eO6QKDL3p1I&list=PLBbU9-SUUCwV7Dpk7GI8QDLu3w54TNAA6)
2. [Blog post on the firewall.](https://www.forcepoint.com/cyber-edu/firewall)

---
