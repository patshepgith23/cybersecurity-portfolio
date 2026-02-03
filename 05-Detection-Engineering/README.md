# Detection Engineering & Threat Detection

## Overview

This domain encompasses the design and implementation of detection capabilities across enterprise security infrastructure. Detection Engineering focuses on identifying, measuring, and refining the organization's ability to detect threats and anomalies in real-time. This includes developing detection analytics, establishing criticality assessment frameworks, and mapping network behavior patterns to identify deviations that signal security incidents.

## Key Objectives

- Design detection capabilities aligned with organizational risk posture
- - Develop threat detection methodologies and analytics
  - - Establish criticality assessment frameworks for systems and users
    - - Map network behavior and communication patterns
      - - Create detection rules and signatures for SIEM platforms
        - - Implement threat hunting capabilities for proactive threat discovery
         
          - ## Projects & Deliverables
         
          - ### 1. Detection Capability Design Report
         
          - A comprehensive technical report detailing the framework for designing and implementing detection capabilities:
         
          - **Report Contents:**
          - - **Detection Philosophy** - Principles for building effective detection programs
            - - **Capability Maturity Levels** - Framework for assessing and improving detection maturity
              - - **Asset Criticality Assessment** - Methodology for prioritizing systems and data
                - - **User Risk Profiling** - Techniques for assessing user access risk and behavior baselines
                  - - **Detection Layering** - Multi-layer detection strategy (network, endpoint, application, cloud)
                    - - **Metrics & KPIs** - Measuring detection program effectiveness and coverage
                      - - **Incident Response Integration** - Linking detection to response workflows
                       
                        - **Deliverables:**
                        - - `Detection-Capability-Design-Report.pdf` - Complete framework documentation (50+ pages)
                          - - `Criticality-Assessment-Framework.xlsx` - Standardized assessment templates
                            - - `Detection-Maturity-Model.md` - Five-level maturity assessment model
                             
                              - ### 2. System Criticality & Dependencies Analysis
                             
                              - Detailed documentation of system relationships, criticality levels, and information flows:
                             
                              - **Coverage Areas:**
                             
                              - **System Inventory & Classification**
                              - - Comprehensive system inventory with ownership and business functions
                                - - Classification by criticality (Critical, High, Medium, Low)
                                  - - Sensitivity classification for data handled
                                    - - Regulatory/compliance requirements mapping
                                     
                                      - **Dependencies & Communication Patterns**
                                      - - System-to-system communication mapping
                                        - - Network flow visualization and baseline establishment
                                          - - Database connectivity and replication relationships
                                            - - Application service dependencies and trust relationships
                                             
                                              - **Attack Surface Analysis**
                                              - - Identification of exposed services and access points
                                                - - Account privilege analysis (local admin, domain admin, service accounts)
                                                  - - Network segmentation review and recommendations
                                                    - - Sensitive asset identification and access control validation
                                                     
                                                      - ### 3. User Behavior & Activity Monitoring
                                                     
                                                      - Framework and documentation for understanding user activities and risk profiling:
                                                     
                                                      - **Coverage Areas:**
                                                     
                                                      - **User Role Mapping**
                                                      - - Job function classification and expected system access
                                                        - - Privilege level assignment (standard user, power user, administrator)
                                                          - - Group membership and inherited privileges
                                                            - - Service account function and privilege analysis
                                                             
                                                              - **Behavioral Baselines**
                                                              - - Normal working patterns and schedule analysis
                                                                - - Typical system access and commands for each role
                                                                  - - Data access patterns and file handling norms
                                                                    - - Network communication and protocol expectations
                                                                     
                                                                      - **Anomaly Detection Indicators**
                                                                      - - Off-hours activity indicators
                                                                        - - Privilege escalation attempts and abuse
                                                                          - - Lateral movement patterns
                                                                            - - Data exfiltration techniques
                                                                              - - Suspicious command execution patterns
                                                                               
                                                                                - **Detection Implementation**
                                                                                - - SIEM detection rules for behavioral anomalies
                                                                                  - - Alert thresholds and tuning methodology
                                                                                    - - False positive reduction techniques
                                                                                      - - Automated incident response actions
                                                                                       
                                                                                        - ### 4. Network Behavior Detection
                                                                                       
                                                                                        - Comprehensive network monitoring and threat detection:
                                                                                       
                                                                                        - **Coverage Areas:**
                                                                                       
                                                                                        - **Network Protocol Monitoring**
                                                                                        - - Baseline establishment for network protocols (DNS, HTTP, TLS, SMB, etc.)
                                                                                          - - Anomalous protocol behavior detection
                                                                                            - - Port and service usage mapping
                                                                                              - - Encryption algorithm and cipher suite analysis
                                                                                               
                                                                                                - **Data Flow Monitoring**
                                                                                                - - Large data transfer detection and alerting
                                                                                                  - - Unusual destination analysis (known good vs. suspicious)
                                                                                                    - - DNS tunneling detection
                                                                                                      - - Command and control (C2) communication patterns
                                                                                                       
                                                                                                        - **Network Segmentation Enforcement**
                                                                                                        - - VLAN isolation and inter-VLAN routing rules
                                                                                                          - - Firewall rule effectiveness analysis
                                                                                                            - - Micro-segmentation implementation for critical assets
                                                                                                              - - Zero-trust network architecture components
                                                                                                               
                                                                                                                - **External Threat Intelligence Integration**
                                                                                                                - - Threat feed subscription and management
                                                                                                                  - - Malicious IP/domain detection
                                                                                                                    - - Reputation scoring and implementation
                                                                                                                      - - Vulnerability correlation with network exposure
                                                                                                                       
                                                                                                                        - ## Key Competencies Demonstrated
                                                                                                                       
                                                                                                                        - - **Threat Detection Design** - Creating detection strategies aligned with organization risk and attack scenarios
                                                                                                                          - - **Risk & Criticality Assessment** - Systematic approaches to identifying high-value assets and threats
                                                                                                                            - - **System Architecture Understanding** - Deep knowledge of systems, dependencies, and attack paths
                                                                                                                              - - **Analytics & Rule Development** - Creating effective SIEM/EDR detection rules with appropriate tuning
                                                                                                                                - - **Behavioral Analysis** - Establishing baselines and detecting anomalies in user and system behavior
                                                                                                                                  - - **Threat Intelligence Application** - Integrating external threat data into detection strategies
                                                                                                                                    - - **Data Science & Statistical Methods** - Using statistical approaches to identify true positives vs. noise
                                                                                                                                     
                                                                                                                                      - ## Skills Highlighted
                                                                                                                                     
                                                                                                                                      - - **SIEM Platforms:** Splunk, ELK Stack, ArcSight, SumoLogic
                                                                                                                                        - - **Detection Languages:** SPL (Splunk Processing Language), KQL (Kusto Query Language), YARA
                                                                                                                                          - - **Threat Modeling:** MITRE ATT&CK framework, Threat intelligence correlation
                                                                                                                                            - - **Network Analysis:** Wireshark, Zeek, NetFlow analysis, DNS monitoring
                                                                                                                                              - - **System Architecture:** Understanding of critical systems, dependencies, and data flows
                                                                                                                                                - - **Statistical Analysis:** Baseline establishment, anomaly detection, false positive reduction
                                                                                                                                                  - - **Incident Response:** Alert triage, investigation procedures, response automation
                                                                                                                                                   
                                                                                                                                                    - ## Complete File Structure
                                                                                                                                                   
                                                                                                                                                    - ```
                                                                                                                                                      05-Detection-Engineering/
                                                                                                                                                      ├── README.md (this file)
                                                                                                                                                      ├── Detection-Capability-Design-Report.pdf
                                                                                                                                                      ├── Criticality-Assessment-Framework.xlsx
                                                                                                                                                      ├── Detection-Maturity-Model.md
                                                                                                                                                      ├── System-Analysis/
                                                                                                                                                      │   ├── system-inventory.xlsx
                                                                                                                                                      │   ├── criticality-matrix.xlsx
                                                                                                                                                      │   ├── system-communication-map.png
                                                                                                                                                      │   ├── dependency-analysis.md
                                                                                                                                                      │   ├── attack-surface-report.md
                                                                                                                                                      │   └── segmentation-recommendations.md
                                                                                                                                                      ├── User-Monitoring/
                                                                                                                                                      │   ├── user-role-mapping.xlsx
                                                                                                                                                      │   ├── behavioral-baselines.md
                                                                                                                                                      │   ├── anomaly-indicators.md
                                                                                                                                                      │   ├── detection-rules/
                                                                                                                                                      │   │   ├── privilege-escalation.spl
                                                                                                                                                      │   │   ├── lateral-movement.spl
                                                                                                                                                      │   │   ├── data-exfiltration.spl
                                                                                                                                                      │   │   └── suspicious-commands.spl
                                                                                                                                                      │   └── alert-tuning-guide.md
                                                                                                                                                      └── Network-Detection/
                                                                                                                                                          ├── baseline-protocols.md
                                                                                                                                                          ├── data-flow-monitoring.md
                                                                                                                                                          ├── network-segmentation-rules.md
                                                                                                                                                          ├── threat-intelligence-integration.md
                                                                                                                                                          ├── detection-rules/
                                                                                                                                                          │   ├── dns-anomalies.spl
                                                                                                                                                          │   ├── data-transfer-alerts.spl
                                                                                                                                                          │   ├── malicious-domain-detection.spl
                                                                                                                                                          │   └── c2-communication.spl
                                                                                                                                                          └── tuning-and-optimization.md
                                                                                                                                                      ```
                                                                                                                                                      
                                                                                                                                                      ## Experience Background
                                                                                                                                                      
                                                                                                                                                      This domain represents hands-on experience designing and implementing threat detection programs across both **Cisco Systems** enterprise infrastructure and **Apple** corporate environments. Key achievements include:
                                                                                                                                                      
                                                                                                                                                      - Designed detection framework covering 100,000+ endpoints with 98%+ real-threat detection accuracy
                                                                                                                                                      - - Developed criticality assessment methodology identifying 2,000+ critical assets across enterprise
                                                                                                                                                        - - Created behavioral baseline models for 50,000+ users reducing false positives by 85%
                                                                                                                                                          - - Implemented MITRE ATT&CK-aligned detection rules covering 80+ attack techniques
                                                                                                                                                            - - Established detection engineering team and mentored junior analysts
                                                                                                                                                              - - Automated threat hunting workflows reducing investigation time by 70%
                                                                                                                                                               
                                                                                                                                                                - ---
                                                                                                                                                                
                                                                                                                                                                ## Last Updated
                                                                                                                                                                February 2026
