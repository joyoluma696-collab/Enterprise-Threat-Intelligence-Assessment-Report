<img width="1021" height="538" alt="image" src="https://github.com/user-attachments/assets/d6964eef-b34c-408c-8500-5d572fb86a00" />





# Enterprise Intelligence Assessment
## Open-Source Exposure and Security Intelligence


**Target Organization:** NIIT Port Harcourt

**Target IP Address:** 185.53.179.146

**Assessment Type:** Passive Open-Source Intelligence (OSINT)

**Classification:** Academic / Internal Use

**Prepared By:** Joy Oluma Udochi

**Contact:** joyoluma696@gmail.com | 09078221520  

---

## Table of Contents
1. [Introduction](#introduction)
2. [Objectives](#objectives)
3. [Scope](#scope)
4. [Tools Used](#tools-used)
5. [Methodology](#methodology)
6. [Findings](#findings)
7. [Intelligence Correlation](#intelligence-correlation)
8. [Intelligence Assessment](#intelligence-assessment)
9. [Risk Analysis](#risk-analysis)
10. [Recommendations](#recommendations)
11. [Conclusion](#conclusion)

---

## Introduction
* This Enterprise Threat Intelligence Assessment presents the results of a passive Open-Source Intelligence (OSINT) investigation conducted using publicly available information. The assessment aimed to identify externally accessible information relating to the target organization, evaluate potential exposure, and assess associated security risks.
The investigation was performed exclusively through passive intelligence collection techniques. No intrusive testing, vulnerability exploitation, authentication attempts, or unauthorized activities were conducted.
The assessment identified publicly exposed employee email addresses, publicly available organizational information, and employee profiles that reveal aspects of the organization’s internal structure. These findings indicate an increased potential for phishing, social engineering, and organizational reconnaissance. The report also references open ports as a risk area; however, no supporting technical evidence or service details were provided.
This assessment evaluates the organization’s publicly available digital footprint using Open-Source Intelligence (OSINT) techniques. The objective was to identify publicly accessible information that could be leveraged during reconnaissance by potential threat actors and to assess the associated security implications.
The assessment was limited to passive intelligence gathering using publicly available sources.

## Objectives
* Identify publicly available information.
* Assess employee and organizational exposure.
* Discover digital assets and online footprints.
* Investigate publicly available infrastructure.
* Correlate intelligence findings into meaningful insights.
* Assess security risks based on collected intelligence.
* Produce a professional intelligence report.

## Scope
This assessment was strictly limited to passive open-source intelligence activities using publicly available information. No intrusive, active scanning, or unauthorized activities were performed against the target infrastructure.

## Tools Used

| Tools | Purpose |
| :--- | :--- |
| **Google Dorking** | Advanced search syntax queries |
| **Whois** | Domain registration information |
| **TheHarvester** | Email and subdomain harvesting |
| **Wayback Machine** | Historical website analysis |
| **Maltego** | Relationship and infrastructure mapping |
| **HTTrack** | Offline website analysis |
| **Shodan** | Internet-facing asset and port discovery |
| **OSINT Framework** | Directory for domain registration and data discovery |

## Methodology
This assessment followed the structured Intelligence Cycle methodology to ensure a repeatable and rigorous process:
1. **Planning:** Defining target objectives and parameters.
2. **Collection:** Gathering raw data from public repositories and OSINT tools.
3. **Processing:** Structuring and filtering the collected raw information.
4. **Analysis:** Reviewing processed data to draw actionable security insights.
5. **Dissemination:** Presenting findings and strategic recommendations in this report.

## Findings

## Finding 1 – Domain Information

**Observation**
Domain registration information was collected using publicly available WHOIS resources.
Threat Assessment
Domain information primarily supports reconnaissance activities and contributes to attacker profiling.
Risk Rating
Low

  <img width="882" height="344" alt="image" src="https://github.com/user-attachments/assets/04fe6082-f666-48b6-a43e-efe4b90d8488" />


## Finding 2 – Public Exposure of Employee Email Addresses

**Observation**
The assessment identified employee email addresses that are publicly accessible through open sources.
Maltego transformation techniques were used to collect publicly available email addresses associated with the target domain from multiple public data sources.
Security Impact
Publicly exposed email addresses increase organizational visibility and may facilitate:
*	Phishing campaigns
*	Email spoofing
*	Business Email Compromise (BEC)
*	Social engineering attacks
The document also notes that both organizational and personal email accounts were identified. This may increase the likelihood of communications occurring outside official organizational channels.


<img width="965" height="520" alt="image" src="https://github.com/user-attachments/assets/1d5e9807-a14e-470a-9b15-eb36342376fe" />

## Intelligence Correlation
This process helped uncover publicly exposed email accounts linked either directly to the domain or indirectly through related data sources. 

* **Automated Extraction:** Email addresses associated with the target domain were investigated and extracted using automated transformations within Maltego, which aggregates publicly available data from multiple open sources.
* **Analysis:** The mix of organizational and personal email accounts suggests that some corporate communications may be conducted outside official channels. This introduces potential security concerns, particularly regarding phishing and social engineering, as attackers frequently target exposed addresses.

## Intelligence Assessment
The investigation uncovered professional data regarding individuals linked to the organization through publicly accessible platforms, primarily LinkedIn. This provided structural insight into the enterprise's internal hierarchy and role distribution.
Based solely on the documented findings, the primary threats include:
Phishing
Publicly exposed employee email addresses may be used to deliver targeted phishing campaigns.
Social Engineering
Employee role information and organizational structure may improve the credibility of impersonation attempts.
Organizational Reconnaissance
Publicly available information enables adversaries to better understand personnel relationships and organizational structure prior to conducting further attack activities.


**Observed Positions:**
* IT Manager
* Administrative Staff
* Department Heads, etc.

A number of employees openly list their roles and affiliations with the organization, making it possible to map out internal departments. In some cases, profiles go further by outlining granular job responsibilities, past technical experience, and specific areas of expertise. While useful for professional visibility, this data creates a highly detailed blueprint of internal operations for external actors.

## Risk Analysis

| Risk Area | Description | Severity |
| :--- | :--- | :--- |
| **Open Ports** | Exposed services may present vulnerabilities if not properly maintained. | Medium |
| **Employee Exposure** | Public organizational mapping increases the likelihood of targeted social engineering. | High |
| **Email Exposure** | Exposed addresses support phishing, spoofing, and credential impersonation attempts. | High |
| **Domain Information** | Basic registration details, primarily useful for initial external reconnaissance. | Low |

> **Summary Takeaway:** The risks identified stem from a combined mix of technical asset exposure and publicly accessible human-interest data. Addressing both structural vectors is critical to effectively reducing the overall corporate attack surface.

## Recommendations
Based exclusively on the findings documented in this assessment, the following recommendations are appropriate:
* Email Exposure
•	Minimize unnecessary public exposure of employee email addresses.
•	Implement email authentication technologies such as SPF, DKIM, and DMARC where appropriate.
•	Provide ongoing phishing awareness training for employees.

* Employee Information
•	Encourage personnel to limit publication of unnecessary operational information on professional networking platforms.
•	Develop guidance regarding acceptable public disclosure of organizational information.

* Internet-Facing Services
•	Review internet-facing systems to ensure exposed services are necessary.
•	Maintain regular patch management for externally accessible services.
•	Conduct periodic external exposure reviews.

* Continuous OSINT Monitoring
•	Perform periodic OSINT assessments to identify newly exposed information.
•	Monitor changes in publicly available organizational data over.
## Conclusion
The assessment identified publicly accessible organizational information that may increase exposure to phishing, social engineering, and reconnaissance activities. The findings primarily relate to publicly available employee information and exposed email addresses obtained through passive OSINT techniques.
No evidence of system compromise, active malicious activity, or exploited vulnerabilities was documented. The assessment supports reducing unnecessary public exposure, strengthening employee security awareness, and regularly reviewing publicly accessible organizational information to reduce the external attack surface.
