# NIST Cybersecurity Framework Applied: Incident Response to a DDoS Attack

## Project Overview

This repository demonstrates the application of the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF) to analyze and respond to a real-world cybersecurity incident. The incident involved a Distributed Denial-of-Service (DDoS) attack targeting a multimedia company's internal network. This project showcases how the NIST CSF core functions — Identify, Protect, Detect, Respond, and Recover — can be used to structure incident response and improve organizational cybersecurity posture.

---

## Background

You are a cybersecurity analyst at a multimedia company that provides web design, graphic design, and social media marketing services to small businesses. Recently, the company experienced a cybersecurity incident that impacted its internal network.

---

## Incident Description

The company’s network services suddenly became unresponsive for approximately two hours. Investigation revealed a distributed denial-of-service (DDoS) attack launched through a flood of ICMP packets. This flood overwhelmed the internal network and blocked normal traffic from accessing critical network resources.

---

## Key Details

- The attack exploited an unconfigured firewall that allowed unlimited incoming ICMP traffic.
- Network services stopped responding due to the flood of ICMP packets.
- The incident management team blocked incoming ICMP packets and took non-critical services offline to stabilize the network.
- Critical services were restored after mitigation.
- Post-incident analysis found the firewall vulnerability allowed the attack.
- The security team implemented:
  - Firewall rules to limit ICMP packet rates.
  - Source IP verification to prevent IP spoofing.
  - Network monitoring software for abnormal traffic detection.
  - IDS/IPS to filter suspicious ICMP traffic.

---

## Your Task

Using the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF), analyze this incident by addressing the following core functions:

- **Identify:** What assets, processes, and personnel were affected?
- **Protect:** What safeguards should be implemented to prevent similar attacks?
- **Detect:** Which tools or methods can be used to detect such attacks early?
- **Respond:** What response strategies should be in place to contain and mitigate the attack?
- **Recover:** How should the organization restore normal operations and improve resilience?

---

## Incident Report Analysis

You can view the detailed incident report analysis applying the NIST Cybersecurity Framework to the DDoS attack scenario here:

[Incident Report Analysis (PDF)](https://github.com/Arif-Abdul/NIST-Cybersecurity-Framework-to-respond-to-a-security-incident/blob/main/Incident%20Report%20Analysis.pdf)

---

## Applying the NIST Cybersecurity Framework (CSF)

To better understand the NIST Cybersecurity Framework and its five core functions — Identify, Protect, Detect, Respond, and Recover — you can review the detailed explanation provided in the following document:

[Applying the NIST CSF (PDF)](https://github.com/Arif-Abdul/NIST-Cybersecurity-Framework-to-respond-to-a-security-incident/blob/main/Applying%20the%20NIST%20CSF%20.pdf)

This document outlines the framework’s purpose, benefits, and key questions to consider for each core function, providing a comprehensive guide to managing cybersecurity risks effectively.

---

## How to Use This Repository

1. Review the **Incident Scenario** and understand the technical and business context.
2. Study the **Task** section to see how the NIST CSF framework guides incident analysis.
3. Download and review the **Incident Report Analysis (PDF)** for a comprehensive walkthrough of the incident response.
4. Download and review the **Applying the NIST CSF (PDF)** for foundational knowledge about the framework.
5. Use this project as a reference or template for applying NIST CSF to similar cybersecurity incidents.

---

## References

- [NIST Special Publication 800-61 Revision 2: Computer Security Incident Handling Guide](https://nvlpubs.nist.gov/nistpubs/specialpublications/nist.sp.800-61r2.pdf)
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)

---

## Contact

For questions or feedback, please contact:  
**Arif Abdul**  
[GitHub Profile](https://github.com/Arif-Abdul)

---

*This project is intended for educational and professional portfolio purposes to demonstrate practical application of cybersecurity frameworks.*
