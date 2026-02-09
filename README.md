
# Introductory Networking – TryHackMe

*Prepared by Ahmed Abdelaziz Eldkrory (EDGAR)*  
Junior Penetration Tester  
📧 Email: [ahmed.a.eldkrory@gmail.com](mailto:ahmed.a.eldkrory@gmail.com)  
🔗 LinkedIn: [www.linkedin.com/in/ahmed-eldkrory](https://www.linkedin.com/in/ahmed-eldkrory)  

Full write-up on Medium: [Introductory Networking THM Room](https://medium.com/@ahmed.a.eldkrory/introductory-networking-thm-room-62866ae1aea7)  
TryHackMe Room: [Introductory Networking](https://tryhackme.com/room/introtonetworking)

---

## Overview
This document demonstrates my understanding of networking fundamentals from a security perspective and summarizes key networking concepts and tools covered in the **Introductory Networking room**.  
The focus is on **understanding, technical reasoning, and ethical learning**, rather than reproducing lab content or solutions.

---

## Why Networking Matters in Cybersecurity
Networking is not just a theoretical topic — it’s the foundation of how systems communicate, how services are exposed, and how attackers and defenders interact.  

For penetration testers, a strong networking background enables:  
- Accurate reconnaissance and scoping  
- Better interpretation of tool output  
- Clear technical communication during assessments  

Understanding networking early saves time, reduces mistakes, and builds confidence when moving into advanced security topics.

---

## Networking Models: Thinking in Layers

### OSI Model – A Diagnostic Framework
The OSI model breaks communication into logical layers, each with a specific role.  
Security professionals use this model to:  
- Pinpoint where issues occur  
- Understand where attacks are executed  
- Communicate findings using a shared technical language  

> It’s a thinking tool — not just a diagram.  

**Mnemonic for layers:**  
*Anxious Pale Shakespeare Treated Nervous Drunks Patiently*

### TCP/IP Model – How the Internet Actually Works
The TCP/IP model reflects real-world implementation.  
It simplifies networking into practical layers used by modern systems and protocols.  
Knowing both models helps bridge the gap between theory and hands-on security work.

### Packet Encapsulation: How Data Travels
Encapsulation describes how data is wrapped with protocol-specific information as it moves through the network stack.  
From a security perspective, this explains:  
- Why packet inspection is powerful  
- How metadata is exposed at different layers  
- Where monitoring and filtering mechanisms operate  

Understanding encapsulation makes traffic analysis far more intuitive.  

---

## Essential Networking Tools (High-Level View)

### Ping
- Tests basic connectivity and reachability between systems  
- Often the first step to check if a host is accessible  

### Traceroute
- Shows the path traffic takes to reach a destination  
- Useful for understanding routing behavior and network structure  

### WHOIS
- Retrieves registration and ownership information for domains and IP ranges  
- Provides valuable context during reconnaissance and scope validation  

### Dig
- Queries DNS records directly to understand how domains resolve and are configured  
- A key tool for DNS analysis and troubleshooting  

---

## Pentester Mindset: How These Fit Together
These concepts and tools are primarily used during the **reconnaissance phase** of a penetration test.  
The goal is to:  
- Observe before interacting  
- Understand the environment before testing it  
- Build a mental map of the network  

> Good reconnaissance is about clarity, not noise.

---

## Common Challenges & Key Insights
Early learners often:  
- Focus too much on tools instead of interpretation  
- Expect immediate vulnerabilities instead of context  
- Underestimate the value of fundamentals  

**Main takeaway:**  
Strong fundamentals scale. Weak fundamentals break under pressure.

---

## Key Takeaways
- Networking models improve technical reasoning  
- Encapsulation explains packet-level visibility  
- Simple tools provide powerful insights when used correctly  
- Ethical, passive reconnaissance is a core security skill  
- Fundamentals are a long-term investment in your career  

---

## Real-World Relevance
In professional security work, these skills support:  
- Network reconnaissance and validation  
- Incident response investigations  
- Security assessments and audits  
- Clear reporting and stakeholder communication  

> Every advanced technique builds on these basics.
