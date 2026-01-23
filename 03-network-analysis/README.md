## Network Structure & Security Analysis – Small Business

### Overview
This project analyzes the network structure of a small business environment in order to identify security weaknesses and potential risks.

The goal is to understand how network design affects security and how basic improvements can reduce attack surfaces.

---

### Network Description
The analyzed network consists of:
- 1 router connected to the internet
- 5 employee workstations
- All devices connected on the same local network
- No network segmentation

---

### Observed Network Structure
- Flat network architecture
- All devices share the same subnet
- No separation between user devices and network infrastructure
- Router exposed directly to the internet

---

### Identified Security Risks
- **Lack of network segmentation**
  - Allows lateral movement if one device is compromised
- **Single point of failure**
  - Router compromise affects the entire network
- **No traffic monitoring**
  - Suspicious network activity may go undetected
- **No access control between devices**
  - Internal systems trust all internal traffic

---

### Risk Level
- **Overall Risk:** Medium

While the network is simple, the lack of basic security controls increases the impact of potential attacks.

---

### Recommendations
- Implement basic network segmentation (e.g., separate user devices from critical systems)
- Restrict router access and disable unnecessary services
- Enable network monitoring and logging
- Apply firewall rules to limit internal and external traffic

---

### Conclusion
This analysis highlights how simple network designs can introduce security risks when proper controls are not in place.  
Improving network segmentation and monitoring would significantly enhance the security posture of the organization.
