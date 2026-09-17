---
layout: page
title: CRA Reporting Obligations for Stewards - Resource Guide
---

From 11 September 2026, the [Cyber Resilience Act (CRA)](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ%3AL_202402847) introduces mandatory reporting obligations for actively exploited vulnerabilities (AEV) and severe incidents affecting products with digital elements. **These obligations apply to open source software stewards only from [11 December 2027](https://digital-strategy.ec.europa.eu/en/library/cyber-resilience-act-implementation-frequently-asked-questions)** to the extent that they are involved in the development of products with digital elements. Stewards should be prepared to identify potentially reportable events, assess whether they fall within the CRA scope, and meet the applicable reporting deadlines. This includes the 24-hour, 72-hour and final reporting requirements. This one-pager summarises the practical considerations for stewards’ reporting obligations.  

## Checks for Stewards’ Reporting Obligations \- art. 24(3):

1. **Confirm for which software you are a steward**   
    - [ ] Assess and document whether your legal entity meets the CRA definition of an open source software steward  
    - [ ] In particular, confirm for each project that you are a legal person, that the software is intended for commercial activities, and that you systematically provide support on a sustained basis and ensure its viability.  
    - [ ] Document the software within scope, what support you provide, and the designated contact channels for security and vulnerability-related matters.  
    - [ ] Clarify the resulting reporting obligations and applicable reporting arrangements under the CRA, including the relevance of [Articles 14](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#art_14) (1), (3) and (8).

1.  **Be ready to report**

    If the conditions of [Article 24(3)](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#art_24) apply, establish a process to report AEVs and severe incidents through the [EU Single Reporting Platform (SRP)](https://www.enisa.europa.eu/topics/product-security/single-reporting-platform-srp).  Make sure you have:

    - [ ] One Primary Assigned Representative, with up to 20 Secondary Representatives, able to report through the SRP [ready](https://www.enisa.europa.eu/topics/product-security/single-reporting-platform-srp/cra-srp-guidance-ar-user-registration) with their [EU Login accounts](https://trusted-digital-identity.europa.eu/creating-managing-and-using-your-eu-login-account/how-do-i-create-my-eu-login-account_en);  
    - [ ] Internal procedures to ensure timely identification, triage, and escalation of vulnerabilities and incidents that may trigger CRA reporting obligations;  
    - [ ] A process capable of meeting the 24-hour, 72-hour and final-report deadlines  
    - [ ] The relevant national coordinating CSIRT identified based on the [Article 14(7)](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#art_14) assessment.  
    - [ ] Knowledge of how to submit an AEV or severe-incident report through the SRP, including the information required at each reporting stage, based on the [ENISA SRP FAQ](https://www.enisa.europa.eu/topics/product-security/single-reporting-platform-srp/frequently-asked-questions) and [AR guidance](https://www.enisa.europa.eu/topics/product-security/single-reporting-platform-srp/cra-srp-guidance-ar-user-registration) which set out the fields and information required for each type of notification.

1.  **Recommended readiness measures**  

    - [ ] Keep relevant software information ready: Maintain up-to-date information on the software, dependencies and development infrastructure. A complete SBOM is recommended where practical to support vulnerability assessment and reporting.   
    - [ ] Plan for changes in stewardship: Reassess your steward status if your systematic support changes or ends, and document any resulting changes to reporting responsibilities.

## Stylised flowchart for CRA coverage of free and open-source software[^1]

![Figure 1 Manufacturer vs Steward](../images/figure-1-manufacturer-vs-steward.png "Figure 1: Manufacturer vs Steward")

<small>Figure 1: Manufacturer vs Steward [^1]</small>

## What is FOSS?

[CRA Guidance, 44](https://ec.europa.eu/newsroom/dae/redirection/document/131456): [Article 3](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#art_3)(48) defines FOSS as ‘software the source code of which is openly shared and which is made available under a free and open-source licence which provides for all rights to make it freely accessible, usable, modifiable and redistributable’. 

Only software that cumulatively fulfils two conditions qualifies as FOSS for the purposes of the CRA: (i) the software must be made available under a free and open-source licence granting the full set of rights referred to in Article 3(48); and (ii) its source code must be openly shared

## Stewards clarifications

[CRA Guidance, 47](https://ec.europa.eu/newsroom/dae/redirection/document/131456): “*The obligations of stewards apply to the legal person that supplies a FOSS intended for commercial activities, but does not place it on the market within the meaning of the CRA.”*

[CRA Guidance, 71](https://ec.europa.eu/newsroom/dae/redirection/document/131456): “*The concept of steward, therefore, applies to specific instances of FOSS that ‘are ultimately intended for commercial activities, such as for integration into commercial services or into monetised products with digital elements’ ([recital 19 of the CRA](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#rct_19)) but not made available on the market within the meaning of the CRA, and for which the legal person publishing that FOSS ensures systematic support.”*

[CRA Guidance, 78](https://ec.europa.eu/newsroom/dae/redirection/document/131456): “*\[…\] a foundation may not be subject to any obligations under the CRA for other specific FOSS that it hosts, in cases where it does not provide systematic support for a specific FOSS, it does not ensure its viability, and/or that specific software is not intended for commercial activities.”*

[CRA Guidance, 75](https://ec.europa.eu/newsroom/dae/redirection/document/131456): “[*Recital 19*](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#rct_19) *explains that the provision of sustained support to the development of a product with digital elements may include (but is not limited to): (i) the hosting and managing of software development collaboration platforms; (ii) hosting source code or software; (iii) governing or managing products with digital elements q*ualifying as FOSS; and (iv) steering the development of such products with digital elements.”

[CRA Guidance, 83](https://ec.europa.eu/newsroom/dae/redirection/document/131456): *“Where an entity ceases to provide systematic support on a sustained basis for a specific FOSS, it may no longer meet the definition of steward and may therefore no longer be subject to the corresponding obligations. In such cases, that entity is encouraged to communicate clearly the change in its status for that specific FOSS.”*

## Vulnerability reporting obligations

| Area | Citation | Requirement | *TL/DR* |
| ----- | ----- | ----- | ----- |
| *Vuln Reporting* | [Article 24](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#art_24) | 3\. The obligations laid down in **Article 14(1)** shall apply to open source software stewards to the extent that they are involved in the development of the products with digital elements. **The obligations** laid down in **Article 14(3) and (8)** **shall apply to open source software stewards to the extent that severe incidents having an impact on the security of products with digital elements affect network and information systems provided by the open source software stewards for the development of such products**. | *Report vulns and known exploits to the Union* |
| *Vuln Reporting* | [Article 14](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#art_14) | 1\. A manufacturer shall notify any actively exploited vulnerability contained in the product with digital elements that it becomes aware of simultaneously to the CSIRT designated as coordinator, in accordance with paragraph 7 of this Article, and to ENISA. The manufacturer shall notify that actively exploited vulnerability via the single reporting platform established pursuant to Article 16\. | *establish an EU National CSIRT contact, report known actively exploited vulns to EU National CSIRT contact and ENISA* |
| *Vuln Reporting* | [Article 14](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#art_14) | 2\. For the purposes of the notification referred to in paragraph 1, the manufacturer shall submit: an early warning notification of an actively exploited vulnerability, without undue delay and in any event within 24 hours of the manufacturer becoming aware of it, indicating, where applicable, the Member States on the territory of which the manufacturer is aware that their product with digital elements has been made available; unless the relevant information has already been provided, a vulnerability notification, without undue delay and in any event within 72 hours of the manufacturer becoming aware of the actively exploited vulnerability, which shall provide general information, as available, about the product with digital elements concerned, the general nature of the exploit and of the vulnerability concerned as well as any corrective or mitigating measures taken, and corrective or mitigating measures that users can take, and which shall also indicate, where applicable, how sensitive the manufacturer considers the notified information to be; unless the relevant information has already been provided, a final report, no later than 14 days after a corrective or mitigating measure is available, including at least the following: a description of the vulnerability, including its severity and impact; where available, information concerning any malicious actor that has exploited or that is exploiting the vulnerability; details about the security update or other corrective measures that have been made available to remedy the vulnerability. | *AEV reporting: submit the early-warning notification without undue delay and in any event within 24 hours of becoming aware of the actively exploited vulnerability; submit the vulnerability notification without undue delay and in any event within 72 hours of becoming aware; and submit the final report no later than 14 days after a corrective or mitigating measure is available.* |
| *Vuln Reporting* | [Article 14](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#art_14) | 3\. A manufacturer shall notify any severe incident having an impact on the security of the product with digital elements that it becomes aware of simultaneously to the CSIRT designated as coordinator, in accordance with paragraph 7 of this Article, and to ENISA. The manufacturer shall notify that incident via the single reporting platform established pursuant to Article 16\. | *Severe security incident \-\>  notify CSIRT \+ ENISA simultaneously via the single reporting platform.* |
| *Vuln Reporting* | [Article 14](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#art_14) | 4\.   For the purposes of the notification referred to in paragraph 3, the manufacturer shall submit: an early warning notification of a severe incident having an impact on the security of the product with digital elements, without undue delay and in any event within 24 hours of the manufacturer becoming aware of it, including at least whether the incident is suspected of being caused by unlawful or malicious acts, which shall also indicate, where applicable, the Member States on the territory of which the manufacturer is aware that their product with digital elements has been made available; unless the relevant information has already been provided, an incident notification, without undue delay and in any event within 72 hours of the manufacturer becoming aware of the incident, which shall provide general information, where available, about the nature of the incident, an initial assessment of the incident, as well as any corrective or mitigating measures taken, and corrective or mitigating measures that users can take, and which shall also indicate, where applicable, how sensitive the manufacturer considers the notified information to be; unless the relevant information has already been provided, a final report, within one month after the submission of the incident notification under point (b), including at least the following:  a detailed description of the incident, including its severity and impact; the type of threat or root cause that is likely to have triggered the incident; applied and ongoing mitigation measures. |  *Manufacturers must report severe security incidents in 3 stages: Within 24h: Early warning \+ whether malicious/unlawful activity is suspected. Within 72h: Incident details, initial assessment, and mitigation measures. Within 1 month after the submission of the incident notification: Final report with severity/impact, likely cause/threat, and mitigation measures.* |
| *Vuln Reporting* | [Article 14](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#art_14) | 8\. After becoming aware of an actively exploited vulnerability or a severe incident having an impact on the security of the product with digital elements, the manufacturer shall inform the impacted users of the product with digital elements, and where appropriate all users, of that vulnerability or incident and, where necessary, of any risk mitigation and corrective measures that the users can deploy to mitigate the impact of that vulnerability or incident, where appropriate in a structured, machine-readable format that is easily automatically processable. Where the manufacturer fails to inform the users of the product with digital elements in a timely manner, the notified CSIRTs designated as coordinators may provide such information to the users when considered to be proportionate and necessary for preventing or mitigating the impact of that vulnerability or incident. | *Notification of impacted users* |

[CRA Guidance, 79](https://ec.europa.eu/newsroom/dae/redirection/document/131456): *“While all legal entities that qualify as stewards under the CRA are required to comply with the obligations in Article 24(1) and (2), how far the obligations laid down in Article 14(1), (3) and (8) apply to those **legal entities varies depending on the type of support they provide, in accordance with Article 24(3).”***

[CRA Guidance, 80:](https://ec.europa.eu/newsroom/dae/redirection/document/131456) *“For example, a steward that only provides non-technical support is, by definition, not involved in development of the product with digital elements, and is therefore not required to report actively exploited vulnerabilities. That steward also does not provide any network and information systems for the development of such products with digital elements, and therefore is not required to report severe incidents to ENISA and the CSIRTs or to impacted users. Nonetheless, where the steward becomes aware of an actively exploited vulnerability (e.g. via a report from external sources, such as security researchers), it should share the information with the maintainers of the product with digital elements, in accordance with its cybersecurity policy. **The maintainers of the products with digital elements and/or the stewards should also consider reporting the vulnerability on a voluntary basis, in accordance with Article 15\.**”*

*\*Voluntary reporting will not be in place at 11 September 2026*

[CRA Guidance, 81](https://ec.europa.eu/newsroom/dae/redirection/document/131456): “*On the other hand, where a steward provides the underlying IT infrastructure for certain products with digital elements, it is required to notify ENISA and the CSIRTs, in accordance with Article 14(3) of **any severe incidents related to that infrastructure that have an impact on the security of products with digital elements**. It is also required, where appropriate, to inform all users (e.g. via a general announcement). As indicated in the previous point, while the steward is not required to report actively exploited vulnerabilities it becomes aware of, it should foster the correct handling of vulnerabilities and should consider voluntary reporting in accordance with Article 15.”*

[CRA Guidance, 82](https://ec.europa.eu/newsroom/dae/redirection/document/131456):*“Finally, where a steward also provides engineering resources to specific products with digital elements, it is required to: (i) notify, in accordance with Article 14(1), of **actively exploited vulnerabilities** that it becomes aware of; and (ii) where appropriate, to **inform all users**. To the extent that the steward also has a direct relationship with impacted users, it is also required to inform them directly, in accordance with Article 14(8).”*

[*CRA Guidance, 216*](https://ec.europa.eu/newsroom/dae/redirection/document/131456)*: “\[...\]open-source software stewards are also required to report actively exploited vulnerabilities in accordance with Article 24(3). **That obligation applies upon becoming aware of an actively exploited vulnerability, and not merely where a vulnerability exists in the codebase of a FOSS for which that entity is a steward.** In practice, because FOSS components are typically integrated downstream into other products with digital elements, a steward is likely to become aware of active exploitation via reports from third parties, which identify exploitation in FOSS components as integrated into other products with digital elements. This may be the case, for example, where a manufacturer of a product with digital elements detects active exploitation in a FOSS component integrated into its own product and reports it to that component’s steward; or when a user or a security researcher finds evidence of exploitation of a FOSS component integrated in a product with digital elements and reports that active exploitation to the component’s steward.”*

[*CRA, article 3(42)*](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#art_3)*: ‘**actively exploited vulnerability**’ means a vulnerability for which there is reliable evidence that a malicious actor has exploited it in a system without permission of the system owner;* 

[*CRA, article 3(44)*](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#art_3)*: ‘**incident** having an impact on the security of the product with digital elements’ means an incident that negatively affects or is capable of negatively affecting the ability of a product with digital elements to protect the availability, authenticity, integrity or confidentiality of data or functions;*

The **criteria for severity** are defined in [Article 14(5)](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#art_14): “*For the purposes of paragraph 3, an incident having an impact on the security of the product with digital elements shall be considered to be severe where:*

1) *it negatively affects or is capable of negatively affecting the ability of a product with digital elements to protect the availability, authenticity, integrity or confidentiality of sensitive or important data or functions; or*  
2) *it has led or is capable of leading to the introduction or execution of malicious code in a product with digital elements or in the network and information systems of a user of the product with digital elements.*”

| Steward activity | Applicable CRA article | Reporting obligation |
| :---: | :---: | :---: |
| Actively involved in development of a product with digital elements  | Art. 24.3 \+ Art. 14(1)  | Report actively exploited vulnerabilities affecting that product  |
| Operating infrastructure used to develop OSS (CI, repos, build systems)  | Art. 24.3 \+ Art. 14(3), (8)  | Report severe incidents affecting steward-operated infrastructure.  |
| Non-technical support (Governance, branding, community events, donations, community management)” | None | No CRA reporting obligation  |
| Downstream proprietary product affected by OSS vulnerability  | Indirect  | Disclosure encouraged via CRA Article 15, not mandated; when contiditions are met, the mandatory reporting under Art. 24(3) may apply.  |

[*EC FAQ 5.1*](https://ec.europa.eu/newsroom/dae/redirection/document/122331)*: “How can a manufacturer become aware of an actively exploited vulnerability or a severe incident?*

*The CRA does not specify how a manufacturer is to become aware of an actively exploited vulnerability or a severe incident, but rather imposes the obligation to notify in accordance with Articles 14 once it does.*

*The paragraphs below provide some examples on how a manufacturer may become aware of such vulnerabilities or incidents, via a variety of activities and channels. It should be noted that this does not imply that the manufacturer is required to carry out such activities or monitor such channels to comply with the reporting obligations.9*

*For example, a manufacturer may become aware because a customer or a partner organisation inform it of unusual activity or compromise, providing the manufacturer with reliable evidence that an actively exploited vulnerability is contained in its product (or the manufacturer gathers reliable evidence confirming its existence).*

*A manufacturer may also become aware via threat intelligence reports, e.g. security researchers or cybersecurity firms publish reports detailing a zero-day vulnerability (i.e. a vulnerability for which a patch or a security update is not yet available) in the manufacturer’s product being used in targeted attacks. Governmental cybersecurity agencies may also notify the manufacturer, having detected exploitation of a vulnerability through their monitoring systems. Ethical hackers may also report a vulnerability that is already being exploited in the wild.*

*Furthermore, the manufacturer may also become aware via internal monitoring, scanning activities or telemetry. For example, the manufacturer’s telemetry system or honeypot (i.e. a security mechanism used to lure cybercriminals away from legitimate targets) indicates exploitation of a previously unknown vulnerability in the manufacturer’s product, or the manufacturer’s security team monitors dark web forums and finds evidence that hackers have successfully exploited a vulnerability in the manufacturer’s product.”*

## Simple submission flow[^2]:

![Figure 2: Reporting actively exploited vulnerabilities and severe incidents via SRP](../images/figure-4-reporting-vulnerabilities-via-srp.png "Figure 2: Reporting vulnerabilities via SRP")

<small>Figure 2: Reporting vulnerabilities via SRP [^5]</small>

## Reporting process and timelines[^3]:

![Figure 3 Reporting timelines](../images/figure-5-reporting-timelines.png "Figure 3: Reporting timelines")

<small>Figure 3: Reporting timelines [^6]</small>

[^1]:  EC Guidance \- [https://ec.europa.eu/newsroom/dae/redirection/document/131456](https://ec.europa.eu/newsroom/dae/redirection/document/131456) \- page 29 

[^2]:  [https://www.enisa.europa.eu/sites/default/files/2026-07/ENISA\_CRA\_SRP\_Factsheet\_v1.0\_0.pdf](https://www.enisa.europa.eu/sites/default/files/2026-07/ENISA_CRA_SRP_Factsheet_v1.0_0.pdf) 

[^3]:  [https://www.enisa.europa.eu/sites/default/files/2026-07/ENISA\_CRA\_SRP\_Factsheet\_v1.0\_0.pdf](https://www.enisa.europa.eu/sites/default/files/2026-07/ENISA_CRA_SRP_Factsheet_v1.0_0.pdf) 
