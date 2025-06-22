# NIST Cybersecurity Framework Applied: Incident Response to a DDoS Attack

## Background
You are a cybersecurity analyst at a multimedia company providing web design, graphic design, and social media marketing services to small businesses. Recently, the company experienced a cybersecurity incident impacting its internal network.

## Incident Description
The company’s network services suddenly became unresponsive for approximately two hours. Investigation revealed a distributed denial-of-service (DDoS) attack launched through a flood of ICMP packets. This flood overwhelmed the internal network and blocked normal traffic from accessing critical network resources.

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

## Your Task
Using the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF), analyze this incident by addressing the following:

- **Identify:** What assets, processes, and personnel were affected?
- **Protect:** What safeguards should be implemented to prevent similar attacks?
- **Detect:** Which tools or methods can be used to detect such attacks early?
- **Respond:** What response strategies should be in place to contain and mitigate the attack?
- **Recover:** How should the organization restore normal operations and improve resilience?

## Incident Report Analysis

You can view the detailed incident report analysis applying the NIST Cybersecurity Framework to the DDoS attack scenario here:

[Incident Report Analysis (PDF)](https://github.com/Arif-Abdul/NIST-Cybersecurity-Framework-to-respond-to-a-security-incident/blob/main/Incident%20Report%20Analysis.pdf)


---

*Used this scenario as the basis for my incident report and analysis, applying the NIST CSF framework.*

---

### References
- [NIST Special Publication 800-61 Revision 2: Computer Security Incident Handling Guide](https://nvlpubs.nist.gov/nistpubs/specialpublications/nist.sp.800-61r2.pdf)
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
