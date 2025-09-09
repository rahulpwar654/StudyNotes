
---
## **Slide 1 – Title**
**Text on Slide:**  
**Data at Rest & Data in Transit**  
*Cybersecurity and Data Protection*

*Presented by:* [Your Name]  
*Date:* [Date]

**Speaker Notes:**  
“Good [morning/afternoon], everyone. Today, I’ll be walking you through two important concepts in cybersecurity — Data at Rest and Data in Transit — and how they can be protected to ensure sensitive information is secure.”

---

## **Slide 2 – Agenda**
**Text on Slide:**
- Definitions and concepts
- Threat landscape
- Security measures
- Real-world examples
- Best practices
- Compliance considerations
- Q&A

**Speaker Notes:**  
“This is our roadmap for today — we’ll start with definitions, explore threats, look at security techniques, see examples, discuss best practices, and lastly, touch on compliance regulations before Q&A.”

---

## **Slide 3 – Introduction**
**Text on Slide:**
- Data is a critical organizational asset
- Threats exist at every stage of data’s life
- Two major states:  
  **1. Data at Rest**  
  **2. Data in Transit**
- Different threats require different protection mechanisms

**Speaker Notes:**  
“In cybersecurity, understanding *where* your data is and *how* it’s moving is essential to securing it. We’ll focus on these two key states — data stored vs data moving — since they require different defense strategies.”

---

## **Slide 4 – Data at Rest**
**Text on Slide:**
- Inactive, stored data
- Locations:
    - Databases
    - File systems
    - Cloud storage
    - Backups / Archives
- Vulnerable to unauthorized access or theft

**Speaker Notes:**  
“Data at rest is the data sitting in a database, on a server, in a file, or in backups. It is not being transferred; it’s simply stored. This makes it a target for physical theft, hacking attempts, or insider misuse.”

---

## **Slide 5 – Data in Transit**
**Text on Slide:**
- Data actively moving from one point to another
- Examples:
    - Internet traffic
    - API calls
    - Email transmission
- Vulnerable to interception (MITM attacks, sniffing)

**Speaker Notes:**  
“In contrast, data in transit is moving data — for instance, when you send an email or a file is retrieved from a server. The main risk here is interception while it’s traveling over the network.”

---

## **Slide 6 – Data Lifecycle**
**Text on Slide:**
- Creation → Storage → Use → Sharing → Archiving → Destruction  
  *(Include simplified diagram)*
- Both data at rest & in transit appear repeatedly

**Speaker Notes:**  
“A helpful concept is the data lifecycle. At some stages it’s in motion, others at rest. Both states repeat many times as data is used and stored.”

---

## **Slide 7 – Threats: Data at Rest**
**Text on Slide:**
- Device theft or server breach
- Insider threats
- Ransomware
- Misconfigured storage (e.g., public S3 bucket)

**Speaker Notes:**  
“Common threats to data at rest range from physical theft of devices to cyber breaches, where attackers exfiltrate stored sensitive records.”

---

## **Slide 8 – Threats: Data in Transit**
**Text on Slide:**
- Man-in-the-Middle attacks
- Packet sniffing
- Session hijacking
- DNS spoofing

**Speaker Notes:**  
“On the move, data can be intercepted through MITM attacks or sniffing unencrypted traffic. If not encrypted, sensitive data like passwords can be stolen.”

---

## **Slide 9 – Securing Data at Rest**
**Text on Slide:**
- Encryption: AES-256, RSA
- Access control / RBAC
- Physical security
- Encrypted databases and drives

**Speaker Notes:**  
“Encrypting stored data ensures that even if accessed illegally, it cannot be read without the decryption key. Access controls and physical protections are equally important.”

---

## **Slide 10 – Securing Data in Transit**
**Text on Slide:**
- End-to-end encryption (TLS/SSL, HTTPS)
- VPNs, SSH
- Secure API calls
- Encrypted email protocols

**Speaker Notes:**  
“Data in transit must be sent over secure, encrypted channels such as HTTPS or secure VPN tunnels. This prevents interception from translating into data theft.”

---

## **Slide 11 – Encryption Basics**
**Text on Slide:**
- Symmetric Encryption – same key (fast)
- Asymmetric Encryption – public/private key (secure key exchange)
- Hybrid Encryption – best of both

**Speaker Notes:**  
“Symmetric encryption is faster but needs a secure key exchange. Asymmetric encryption solves that problem but is slower. Many systems use a hybrid model.”

---

## **Slide 12 – Visual Overview**
**Text on Slide:**
*(Diagram showing “Data at Rest” – encrypted on disk + “Data in Transit” – encrypted over network)*

**Speaker Notes:**  
“This diagram shows at a high level where encryption applies — at rest, storage is encrypted; in transit, channels are secured with protocols like TLS.”

---

## **Slide 13 – Real-world Examples**
**Text on Slide:**
- WhatsApp: End-to-End encryption
- AWS S3: AES-256 encryption at rest + HTTPS in transit
- SFTP vs FTP: Secure vs insecure file transfer

**Speaker Notes:**  
“These are real-world applications of the principles — many popular services now intentionally encrypt at both stages.”

---

## **Slide 14 – Best Practices**
**Text on Slide:**
- Encrypt everywhere
- Strong key management
- Limit retention
- Patch and update
- Monitor and audit

**Speaker Notes:**  
“The safest approach is encrypting sensitive data always, using strong keys, limiting how long you keep data, and continuously monitoring access.”

---

## **Slide 15 – Compliance**
**Text on Slide:**
- GDPR – Data protection requirements
- HIPAA – Healthcare data encryption
- PCI DSS – Payment card data
- ISO 27001 – Security management standard

**Speaker Notes:**  
“Regulations such as GDPR and HIPAA often require encryption at both rest and transit as part of compliance.”

---

## **Slide 16 – Summary**
**Text on Slide:**
- **Data at Rest**: Stored → encrypt + control access
- **Data in Transit**: Moving → encrypt channels + authenticate
- Different risks, similar goals: keep data confidential, intact, and available

**Speaker Notes:**  
“In summary — while the risks differ between stored and moving data, our security goal remains the same: to ensure confidentiality, integrity, and availability.”

---

## **Slide 17 – Q&A**
**Text on Slide:**
- Questions?
- Discussion

**Speaker Notes:**  
“Thank you for your attention. I’m happy to take your questions.”

---
