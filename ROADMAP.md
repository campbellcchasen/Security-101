# 🗺️ Cybersecurity Certification Roadmap

This roadmap maps the 8 Security-101 modules to recognized cybersecurity certifications. This will help you understand how this course aligns with industry-recognized credentials and guide your certification strategy.

---

## Your Target: SOC Analyst Role

**Recommended Certification Path:**
1. **CompTIA Security+** (Entry to intermediate) ✅ **START HERE**
2. **CompTIA CySA+** (Intermediate) - Focuses on detection and analysis
3. **EC-Council CEH** (Optional) - Ethical hacking perspective
4. **CISSP** (Advanced) - Long-term goal after 5+ years experience

---

## Module-to-Certification Alignment

### Module 1: Fundamentals of Cybersecurity

#### 🎯 Covers These Certifications
- **CompTIA Security+**: Core knowledge (~30% of exam)
  - Threats and Vulnerabilities (Domain 1)
  - Architecture and Design (Domain 3)
  - Security Operations (Domain 4)

- **CompTIA CySA+**: Foundations
  - Threats and Vulnerabilities Analysis
  - Risk Management concepts

#### Key Topics for Exams
| Topic | Security+ | CySA+ | CEH | CISSP |
|-------|-----------|-------|-----|-------|
| CIA Triad | ✅ Essential | ✅ Essential | ✅ Essential | ✅ Essential |
| Threat Types | ✅ 10+ types | ✅ Detection focus | ✅ Attack methods | ✅ Risk context |
| Risk Assessment | ✅ Basics | ✅ Detailed | ✅ Vulnerability focus | ✅ Strategic |
| MITRE ATT&CK | ⭕ Emerging | ✅ Heavy focus | ✅ Tactics/Techniques | ✅ Framework knowledge |
| Security Controls | ✅ Types | ✅ Monitoring | ✅ Evasion | ✅ Enterprise scale |
| Zero Trust | ✅ Concepts | ✅ Implementation | ⭕ Evasion | ✅ Architecture |
| Shared Responsibility | ✅ Cloud basics | ✅ Cloud risks | ⭕ N/A | ✅ Cloud governance |

#### 📚 Study Resources
- **For Security+**: 
  - Practice quizzes on threat identification
  - Create threat actor profiles
  - Study risk matrices and calculations
  - Review NIST frameworks

- **For CySA+**: 
  - MITRE ATT&CK framework deep dive
  - Build TTP (Tactics, Techniques, Procedures) profiles
  - Learn threat intelligence analysis

#### 🧪 Practice Activities
- [ ] Create 5 scenario-based threat assessments
- [ ] Map real-world attacks to MITRE ATT&CK techniques
- [ ] Build a risk assessment matrix for your organization
- [ ] Document 10 different threat actors and their motivations

---

### Module 2: Identity and Access Management (IAM)

#### 🎯 Covers These Certifications
- **CompTIA Security+**: Identity and Access Management (~15% of exam)
  - Domain 2: Architecture and Design (Identity and Access Management)

- **CompTIA CySA+**: 
  - User and entity behavior analytics
  - Unauthorized access detection

- **CISSP**: 
  - Identity and Access Management Domain (extensive coverage)
  - Access controls, authentication, authorization

#### Key Topics for Exams
| Topic | Security+ | CySA+ | CEH | CISSP |
|-------|-----------|-------|-----|-------|
| Authentication methods | ✅ Essential | ⭕ Detection | ✅ Compromise | ✅ Enterprise |
| MFA/2FA | ✅ Implementation | ✅ Bypass detection | ✅ Attacks | ✅ Strategic |
| Authorization models | ✅ RBAC, ABAC | ✅ Policy enforcement | ⭕ Evasion | ✅ Comprehensive |
| Least Privilege | ✅ Core principle | ✅ Violation detection | ⭕ Escalation | ✅ Audit |
| Directory Services | ✅ AD basics | ✅ AD security risks | ✅ Enumeration | ✅ Architecture |
| Privileged Access | ✅ PAM concepts | ✅ Anomaly detection | ✅ Credential theft | ✅ Full governance |
| SSO/Federation | ✅ Concepts | ⭕ Compromise detection | ✅ Attacks | ✅ Architecture |

#### 📚 Study Resources
- **For Security+**:
  - Understand all authentication factors
  - Know common authentication protocols (NTLM, Kerberos)
  - Study access control models (DAC, MAC, RBAC, ABAC)
  - Learn about Active Directory basics

- **For CySA+**:
  - Behavioral analytics for detecting compromised accounts
  - Privilege escalation detection
  - Unusual access patterns
  - Failed authentication trends

- **For CISSP**:
  - IAM as part of security governance
  - Enterprise authentication architecture
  - Identity governance and lifecycle management

#### 🧪 Practice Activities
- [ ] Compare AAA (Authentication, Authorization, Accounting) models
- [ ] Design IAM architecture for a fictional company
- [ ] Document identity attack techniques (pass-the-hash, etc.)
- [ ] Build user access policies using least privilege principle
- [ ] Analyze AD security audit logs for anomalies
- [ ] Create MFA deployment plan for an organization

---

### Module 3: Network Security

#### 🎯 Covers These Certifications
- **CompTIA Security+**: Network Security (~20% of exam)
  - Domain 1: Threats, Attacks and Vulnerabilities
  - Domain 3: Architecture and Design (Network Architecture and Design)
  - Domain 4: Security Operations (incident handling)

- **CompTIA CySA+**: 
  - Network traffic analysis
  - Intrusion detection
  - DDoS detection and response

- **CEH**: Network reconnaissance and attacks (significant coverage)

#### Key Topics for Exams
| Topic | Security+ | CySA+ | CEH | CISSP |
|-------|-----------|-------|-----|-------|
| TCP/UDP protocols | ✅ Understand | ✅ Traffic analysis | ✅ Attack vectors | ✅ Architecture |
| IP addressing | ✅ IPv4/IPv6 | ✅ Spoofing detection | ✅ Enumeration | ✅ Planning |
| Firewalls | ✅ Types & rules | ✅ Rule review | ✅ Evasion | ✅ Architecture |
| Network segmentation | ✅ VLAN basics | ✅ Lateral movement detection | ✅ Bypass | ✅ Design |
| Encryption protocols | ✅ TLS/SSL | ✅ Certificate analysis | ✅ Attacks | ✅ Standards |
| DDoS attacks | ✅ Types | ✅ Detection & response | ✅ Execution | ✅ Mitigation |
| VPN technology | ✅ Concepts | ✅ Configuration review | ✅ Bypass techniques | ✅ Remote access |
| Port security | ✅ Common ports | ✅ Anomalous usage | ✅ Exploitation | ✅ Controls |

#### 📚 Study Resources
- **For Security+**:
  - Memorize common port numbers (SSH:22, HTTP:80, HTTPS:443, DNS:53, etc.)
  - Understand OSI model and where controls operate
  - Study firewall types and capabilities
  - Know encryption algorithms and protocols

- **For CySA+**:
  - Learn to analyze network traffic (Wireshark)
  - Understand network baselines
  - Detect anomalous traffic patterns
  - IDS/IPS rule tuning and false positive reduction
  - DDoS attack signatures and responses

- **For CEH**:
  - Network scanning tools (Nmap)
  - Sniffing and spoofing techniques
  - Man-in-the-middle attacks
  - Network reconnaissance

#### 🧪 Practice Activities
- [ ] Memorize OSI model and map security controls to each layer
- [ ] Practice with Wireshark—analyze real traffic captures
- [ ] Build network diagrams with security zones
- [ ] Simulate network segmentation with virtual networks
- [ ] Study DDoS attack types and mitigation strategies
- [ ] Learn common network vulnerabilities (ARP spoofing, DNS poisoning)
- [ ] Design network for zero trust architecture

---

### Module 4: Security Operations (SecOps)

#### 🎯 Covers These Certifications
- **CompTIA Security+**: Security Operations (~20% of exam)
  - Domain 4: Security Operations (Threat Detection, Analysis, Response)

- **CompTIA CySA+**: **CORE FOCUS** (~50% of exam)
  - Threat Analysis and Response
  - Detection and Analysis
  - Security Tools and Technologies

- **CompTIA CASP+**: Advanced security operations and architecture

#### Key Topics for Exams
| Topic | Security+ | CySA+ | CEH | CISSP |
|-------|-----------|-------|-----|-------|
| NIST CSF | ✅ Framework | ✅ Detect/Respond | ⭕ N/A | ✅ Governance |
| Incident Response | ✅ Process | ✅ Deep detail | ✅ Evasion | ✅ Program |
| Log analysis | ✅ Basics | ✅ Heavy focus | ⭕ Evasion | ✅ Audit logs |
| SIEM tools | ✅ Concepts | ✅ Practical use | ⭕ Evasion | ✅ Architecture |
| XDR/EDR | ✅ Emerging | ✅ Practical use | ⭕ Evasion | ✅ Endpoint security |
| Threat hunting | ⭕ Mention | ✅ Core skill | ⭕ N/A | ✅ Strategy |
| Threat intelligence | ✅ Concepts | ✅ Application | ✅ Open source | ✅ Strategic |
| Automation/SOAR | ⭕ Emerging | ✅ Important | ⭕ Evasion | ✅ Operations |

#### 📚 Study Resources
- **For Security+**:
  - NIST Cybersecurity Framework (Identify, Protect, Detect, Respond, Recover)
  - Incident response phases (Preparation, Detection, Containment, Eradication, Recovery, Lessons Learned)
  - Log types and sources
  - Understand SIEM and XDR at conceptual level

- **For CySA+** (THIS IS YOUR PRIMARY FOCUS FOR SOC):
  - Deep dive into threat detection techniques
  - Log correlation and event analysis
  - SIEM tools hands-on (try Splunk, ELK, Azure Sentinel free versions)
  - Alert tuning and false positive reduction
  - Incident response playbooks
  - Threat intelligence analysis and application
  - Vulnerability severity assessment
  - Evidence collection and chain of custody

#### 🧪 Practice Activities
- [ ] Download and practice with SIEM tools (Splunk, Elastic, Wazuh)
- [ ] Create incident response playbooks for common scenarios
- [ ] Analyze sample log files and identify suspicious activity
- [ ] Study real breach case studies and how they were detected
- [ ] Practice threat intelligence consumption (CISA alerts, sector-specific feeds)
- [ ] Learn to write detection rules (use Sigma format)
- [ ] Build home lab SIEM with log sources

---

### Module 5: Application Security

#### 🎯 Covers These Certifications
- **CompTIA Security+**: Application Development and Deployment (~5% of exam)
  - Secure development practices
  - Web application vulnerabilities

- **CompTIA CySA+**: Application and web security
  - Detecting application attacks
  - Vulnerability assessment

- **CEH**: Web application testing (significant coverage)

- **CISSP**: Software Development Security domain

#### Key Topics for Exams
| Topic | Security+ | CySA+ | CEH | CISSP |
|-------|-----------|-------|-----|-------|
| OWASP Top 10 | ✅ Know all 10 | ✅ Detection focus | ✅ Exploitation | ✅ Mitigation |
| Injection attacks | ✅ SQL injection | ✅ Detection | ✅ Exploitation | ✅ Prevention |
| XSS vulnerabilities | ✅ Types | ✅ Detection | ✅ Exploitation | ✅ Controls |
| SAST/DAST | ✅ Concepts | ✅ Tool usage | ⭕ Evasion | ✅ Program |
| WAF rules | ✅ Concepts | ✅ Rule review | ✅ Bypass | ✅ Architecture |
| Dependency scanning | ⭕ Emerging | ✅ Important | ⭕ Supply chain | ✅ Governance |
| Container security | ✅ Basics | ✅ Image scanning | ✅ Escape | ✅ Architecture |
| API security | ⭕ Emerging | ✅ Increasing | ✅ Exploitation | ✅ Design |

#### 📚 Study Resources
- **For Security+**:
  - OWASP Top 10 (all 10 vulnerabilities)
  - Secure development lifecycle phases
  - Basic vulnerability testing concepts

- **For CySA+**:
  - Web application attack signatures
  - How to detect OWASP vulnerabilities in logs
  - Container image vulnerability scanning
  - API security monitoring

#### 🧪 Practice Activities
- [ ] Memorize all 10 OWASP Top 10 vulnerabilities
- [ ] Practice with OWASP WebGoat (intentionally vulnerable app)
- [ ] Learn to use Burp Suite Community edition for web testing
- [ ] Study real CVEs and how they're exploited
- [ ] Build detection rules for application attacks
- [ ] Research container security best practices

---

### Module 6: Infrastructure Security

#### 🎯 Covers These Certifications
- **CompTIA Security+**: Infrastructure and Systems (~15% of exam)
  - Cloud security
  - Endpoint security
  - Patch management

- **CompTIA CySA+**: 
  - Cloud security monitoring
  - Vulnerability management
  - System hardening detection

- **CompTIA CASP+**: 
  - Enterprise infrastructure security
  - Cloud and virtualization

#### Key Topics for Exams
| Topic | Security+ | CySA+ | CEH | CISSP |
|-------|-----------|-------|-----|-------|
| Patching | ✅ Importance | ✅ Vulnerability detection | ✅ Exploitation | ✅ Program |
| Vulnerability scanning | ✅ Concepts | ✅ Heavy focus | ✅ Using scanners | ✅ Program |
| CSPM/CNAPP | ✅ Cloud concepts | ✅ Tool usage | ⭕ N/A | ✅ Governance |
| Cloud security | ✅ Shared responsibility | ✅ Misconfiguration detection | ✅ API attacks | ✅ Architecture |
| Container security | ✅ Concepts | ✅ Scanning & monitoring | ✅ Escape techniques | ✅ Design |
| Kubernetes | ⭕ Emerging | ✅ Security basics | ⭕ Cluster attacks | ✅ Architecture |
| Hardware security | ✅ TPM, HSM | ✅ Tamper detection | ✅ Physical | ✅ Controls |
| Endpoint protection | ✅ EDR concepts | ✅ Log analysis | ✅ Evasion | ✅ Platform |

#### 📚 Study Resources
- **For Security+**:
  - Patch management lifecycle
  - Cloud service models (IaaS, PaaS, SaaS)
  - Vulnerability management basics
  - Endpoint security concepts

- **For CySA+**:
  - Vulnerability severity assessment (CVSS scoring)
  - Cloud misconfiguration detection
  - Endpoint detection and response (EDR)
  - Vulnerability trending and metrics

#### 🧪 Practice Activities
- [ ] Learn CVSS scoring system and practice scoring vulnerabilities
- [ ] Set up free cloud account and find misconfigurations
- [ ] Study container image vulnerability scanning tools
- [ ] Research real infrastructure breaches (Capital One, etc.)
- [ ] Build detection for common misconfigurations

---

### Module 7: Data Security

#### 🎯 Covers These Certifications
- **CompTIA Security+**: Data Security (~10% of exam)
  - Data classification
  - Data protection mechanisms
  - Privacy considerations

- **CompTIA CySA+**: 
  - Data exfiltration detection
  - Insider threat detection
  - DLP tools and monitoring

- **CISSP**: Information Security and Privacy domain

#### Key Topics for Exams
| Topic | Security+ | CySA+ | CEH | CISSP |
|-------|-----------|-------|-----|-------|
| Encryption | ✅ Symmetric/asymmetric | ✅ Key management | ✅ Attacks | ✅ Comprehensive |
| Data classification | ✅ Levels | ✅ Implementation | ⭕ N/A | ✅ Governance |
| Data lifecycle | ✅ Concepts | ✅ Monitoring | ⭕ Exfiltration | ✅ Management |
| DLP tools | ✅ Concepts | ✅ Practical use | ⭕ Evasion | ✅ Controls |
| Privacy laws | ✅ GDPR, HIPAA basics | ✅ Compliance detection | ⭕ N/A | ✅ Governance |
| Insider threats | ✅ Overview | ✅ Detection | ⭕ Execution | ✅ Program |
| Data retention | ✅ Basics | ✅ Policy enforcement | ⭕ Destruction | ✅ Governance |
| PII/PHI protection | ✅ Awareness | ✅ Detection | ⭕ Theft | ✅ Controls |

#### 📚 Study Resources
- **For Security+**:
  - Encryption types and use cases
  - Data classification frameworks
  - Privacy regulation basics (GDPR, HIPAA, CCPA)
  - Data handling best practices

- **For CySA+**:
  - Detecting data exfiltration attempts
  - DLP tool configuration and tuning
  - Privacy incident detection
  - Insider risk detection techniques

#### 🧪 Practice Activities
- [ ] Create data classification policy for sample organization
- [ ] Build DLP detection rules for sensitive data patterns
- [ ] Research privacy regulations affecting your industry
- [ ] Study exfiltration detection techniques
- [ ] Analyze logs for suspicious data access patterns

---

### Module 8: AI Security

#### 🎯 Covers These Certifications
- **CompTIA Security+**: Emerging (beginning to appear on exams)
- **CompTIA CySA+**: AI-powered detection and response tools
- **Advanced Certifications**: Increasingly important

#### Key Topics for Exams
| Topic | Security+ | CySA+ | CEH | CISSP |
|-------|-----------|-------|-----|-------|
| AI/ML security | ✅ Emerging | ✅ Tool usage | ⭕ Adversarial | ✅ Governance |
| Data poisoning | ⭕ Awareness | ✅ Detection | ✅ Attack method | ✅ Risks |
| Adversarial attacks | ⭕ Awareness | ✅ Impact understanding | ✅ Execution | ✅ Risks |
| AI red teaming | ⭕ Awareness | ⭕ Emerging | ⭕ N/A | ⭕ Emerging |
| Responsible AI | ✅ Concepts | ✅ Detection | ⭕ N/A | ✅ Governance |
| Bias in AI | ⭕ Awareness | ✅ Detection impact | ⭕ N/A | ✅ Risk |
| Model security | ⭕ Awareness | ✅ Tool usage | ⭕ Evasion | ✅ Governance |

#### 📚 Study Resources
- **For Security+**:
  - Understand AI/ML security challenges
  - Bias and fairness concepts
  - Data poisoning and adversarial attacks overview

- **For CySA+**:
  - AI-powered SIEM and XDR tools
  - Behavioral analytics capabilities
  - Responsible AI and ethics
  - Detection of adversarial attacks

#### 🧪 Practice Activities
- [ ] Research real AI security failures (Microsoft Tay, etc.)
- [ ] Understand how AI is used in security tools you'll use
- [ ] Study bias detection techniques
- [ ] Learn about adversarial attack examples
- [ ] Explore responsible AI frameworks

---

## Recommended Study Timeline

### Timeline for CompTIA Security+ (Your Starting Point)
**Duration: 4-6 months of consistent study**

- **Months 1-2**: Modules 1, 2, 3 (Fundamentals, IAM, Networks)
- **Months 2-3**: Module 4 (SecOps) + Practice exams
- **Month 4**: Modules 5, 6, 7 (AppSec, Infrastructure, Data)
- **Month 5**: Module 8 + Full review + Practice exams
- **Month 6**: Final preparation + Exam day

### Timeline for CompTIA CySA+ (Your Target Role)
**Duration: 3-4 months after Security+**

- **Focus Weeks 1-4**: Deep dive into Module 4 (SecOps)
- **Focus Weeks 5-8**: Modules 1-3 from detection perspective
- **Focus Weeks 9-12**: Modules 5-7, then Module 8
- **Final Month**: Labs, simulations, practice exams

### Timeline for Long-Term (CISSP)
**Duration: 5+ years experience required before taking exam**

- Develop through 5+ years in security roles
- Study all modules with enterprise perspective
- Complete official CISSP training
- Gain experience in all CISSP domains

---

## Exam-Specific Study Strategies

### CompTIA Security+ (Beginner-Friendly)
- **Format**: 90 questions, multiple choice, drag-and-drop
- **Duration**: 90 minutes
- **Passing Score**: 750/900
- **Cost**: ~$370
- **Topics Distribution**:
  - Threats, Attacks & Vulnerabilities: 24%
  - Architecture & Design: 21%
  - Implementation: 25%
  - Operations & Incident Response: 16%
  - Governance, Risk & Compliance: 14%

**Study Tips**:
- Focus on memorizing common attacks, ports, and protocols
- Use acronyms (CIA, AAA, MAC, RBAC, etc.)
- Practice scenario-based questions
- Take multiple practice exams

### CompTIA CySA+ (Your Next Step for SOC)
- **Format**: 90 questions, multiple choice, hotspot, drag-and-drop
- **Duration**: 165 minutes
- **Passing Score**: 750/900
- **Cost**: ~$420
- **Topics Distribution**:
  - Threat Analysis: 22%
  - Security Tools & Technologies: 28%
  - Vulnerability Management: 16%
  - Incident Response: 20%
  - Governance, Risk & Compliance: 14%

**Study Tips**:
- Heavy emphasis on detection and analysis (real SOC work!)
- Practice with actual tools (SIEM, vulnerability scanners)
- Study NIST frameworks and methodologies
- Focus on metrics and trending
- Hands-on labs are crucial

---

## Free Resources by Certification

### CompTIA Security+
- [CompTIA Official Study Materials](https://www.comptia.org/certifications/security)
- Professor Messer (YouTube - excellent free videos)
- TryHackMe Security+ learning path
- Practice exams (Jason Dion, Professor Messer)

### CompTIA CySA+
- [CompTIA Official Materials](https://www.comptia.org/certifications/cybersecurity-analyst)
- CBTNuggets CySA+ course (some free content)
- TryHackMe CySA+ track
- NIST Cybersecurity Framework official documentation
- CISA website (free alerts, resources)
- Splunk free tier (learning environment)

### Lab & Practice Environments
- **TryHackMe.com**: Security paths aligned with certifications
- **HackTheBox.eu**: Hands-on penetration testing labs
- **OWASP WebGoat**: Free vulnerable web app
- **Splunk Free**: SIEM learning
- **Azure Free Tier**: Cloud security labs
- **DetectionLab**: Build your own SIEM lab
- **Cybrary**: Free security courses

### Staying Current
- **CISA Alerts**: https://www.cisa.gov/alerts
- **SecurityFocus**: Latest vulnerabilities
- **Reddit**: r/Security, r/cybersecurity
- **Medium**: Security research articles
- **YouTube Channels**: 
  - John Hammond (CTF walkthrough
)
  - NetworkChuck
  - Cory Daubenmire

---

## Your Personalized Roadmap

Based on your goal (IT Help Desk → SOC Analyst):

### Phase 1: Foundation (NOW - 6 months)
**Goal**: CompTIA Security+ Certification
- Complete Security-101 Modules 1-4
- Complete CompTIA Security+ course
- Pass Security+ exam
- Build home lab

### Phase 2: Specialization (Months 7-12)
**Goal**: CompTIA CySA+ Certification + First SOC role
- Complete Security-101 Modules 5-8
- Complete CySA+ deep-dive training
- Set up SIEM lab
- Get hands-on with threat detection tools
- Pass CySA+ exam
- Target: Junior SOC Analyst role

### Phase 3: Expertise (Year 2+)
**Goal**: Intermediate SOC role + Optional certs
- Consider: GIAC certifications (GCIH, GCIA)
- Consider: Cloud certifications (AWS Security, Azure)
- Build threat hunting skills
- Contribute to threat intelligence community

### Phase 4: Leadership (Year 3-5+)
**Goal**: Senior SOC Analyst or SOC Lead
- Consider: CISSP (requires 5 years experience)
- Consider: SANS certifications (GIAC track)
- Develop specialized expertise (cloud, OT, etc.)
- Lead incident response efforts

---

## Resources Included in This Roadmap

- **8 Security-101 Learning Modules**: Complete coverage
- **Certification Alignment Table**: Clear mapping
- **Study Timeline**: Realistic progression
- **Free Study Materials**: No required purchases
- **Lab Environment Guide**: Hands-on practice
- **Practice Exam Recommendations**: Self-assessment

---

**Remember**: This roadmap is your guide, but every journey is unique. Adjust timelines based on your available study time, learning pace, and career goals. The most important thing is consistent, focused learning and hands-on practice.

Your SOC analyst journey starts here! 🚀

---

Last Updated: 2026-04-23
