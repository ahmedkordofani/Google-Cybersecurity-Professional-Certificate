**Project Description:**

In my role as a security analyst at a prominent travel agency, I encountered a critical incident involving a Distributed Denial of Service (DDoS) attack on our company's web server. This project documents the incident, the immediate mitigation measures taken, and outlines a comprehensive plan to prevent future attacks, showcasing my expertise in incident response and network security.

**Project Scope:**

The project encompassed the following key activities:

**Incident Detection:** The project began with the detection of an incident triggered by an automated alert from our monitoring system. Users were experiencing connection timeouts when attempting to access our sales webpage.

**Incident Verification:** To confirm the incident, I attempted to access the company's website myself, encountering a connection timeout error in my browser, corroborating the user reports.

**Packet Capture:** Leveraging a packet sniffer, I captured data packets in transit to and from the web server during the incident, allowing for a deeper analysis of the attack.

**Attack Identification:** Analysis of the captured packets revealed a substantial influx of TCP SYN requests originating from an unfamiliar IP address. This traffic overload was adversely affecting the web server's ability to respond.

**Immediate Mitigation:** Recognizing the urgency of the situation, I promptly took the web server offline temporarily to mitigate the ongoing attack and allow the server to recover.

**Firewall Configuration:** I configured the company's firewall to block the IP address responsible for the abnormal volume of SYN requests. However, I acknowledged the limitations of this solution, as attackers can employ IP spoofing to circumvent IP blocking.

**Incident Report:** I prepared a detailed incident report, which documented the attack, the impact on the web server and employees, and the immediate response actions taken.

**Recommendations:** The report also included recommendations for preventing similar attacks in the future, emphasizing the importance of a multi-faceted security strategy.

**Project Impact:**

This project had a significant impact on the organization's cybersecurity posture and incident response capabilities:

**Timely Incident Mitigation:** Swiftly taking the web server offline helped minimize the impact of the DDoS attack on our operations.

**Improved Network Security:** Configuring the firewall to block the attacker's IP address demonstrated proactive security measures.

**Detailed Incident Documentation:** The incident report provided a clear account of the attack and the response actions, facilitating communication with management and stakeholders.

**Future Attack Prevention:** Recommendations in the report outlined strategies to enhance DDoS attack resilience and bolster overall network security.

This project exemplifies my ability to handle critical incidents, respond to immediate threats, and formulate comprehensive strategies to safeguard an organization's digital assets. In my GitHub portfolio, you will find the incident report and recommendations, showcasing my dedication to maintaining network security in dynamic real-world scenarios.
