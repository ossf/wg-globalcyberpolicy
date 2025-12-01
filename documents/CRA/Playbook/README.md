# LF CRA Playbook #

Congratulations!  You are one of the parties that controibute to "Products with Digital Elements" (PDE) as detailed in [Article 6](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#art_6) that will be sold within the European Union.  You are an upstream open source developer, get to be an open source Steward, or perhaps you are a Manufacturer 
as outlined within the [EU’s Cyber Resilience Act (CRA)](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#art_3). You are vitally important in supporting upstream projects, developers, and maintainers as they go about the task of 
maintaining and creating innovative solutions that solve the world’s problems. 

Tnis document is intended to be a living playbook of terms, artifacts, entities, and expected processes you will see and hear about as part of the implementation of the CRA in September 2026 and December 2027.

Take free course [Understanding the EU Cyber Resilience Act (CRA) (LFEL1001)](https://training.linuxfoundation.org/express-learning/understanding-the-eu-cyber-resilience-act-cra-lfel1001/) to learn more.
 
## Executive Summary ##
The EU’s Cyber Resilience Act (CRA) is one of the most consequential pieces of recently drafted legislation when it comes to its impact on open source software development. It combines cybersecurity hygiene, best practices, vulnerability reporting, and documentation requirements that may be unfamiliar to many that work exclusively upstream. Please first consult the LF CRA Stewards ED/GM One-Pager for more concise instructions. This playbook is designed to provide more in-depth details and instructions on how an Open Source Steward can fulfill their obligations, both under the law, but as well to the projects that are housed beneath them as well as the community of members and other participants within the ecosystem. 

The CRA created a new role, the Open Source Steward to help support upstream projects and support both up and downstream:
An ‘open-source software steward’ means a legal person, other than a manufacturer, that has the purpose or objective of systematically providing support on a sustained basis for the development of specific products with digital elements (PDEs), qualifying as free and open-source software and intended for commercial activities, and that ensures the viability of those products (Article 3.14)

Stewards are formally recognized as entities that can support the compliance efforts of open-source software projects and shared digital components. The regulation assigns them a limited but essential set of legal obligations, primarily focused on ensuring that secure development and vulnerability handling processes are in place, and that relevant information can be communicated effectively to market surveillance authorities when required. These obligations aim to establish a clear line of accountability for the security posture of software elements that may be integrated into products placed on the Union market. In fulfilling these duties, stewards act as a bridge between open-source or collaborative development environments and the regulatory compliance expectations imposed on commercial manufacturers.

Not every project needs a Steward. Some stewards will support multiple projects within their community. The flowchart below is a starting point for clarifying if you are a steward or a manufacturer or both.


## Open Source Developers ##
The CRA puts no legal obligations for the overwhleming majority of people that create and contribute upstream opne source software.  Just because you do not have legal obligations does not mean that your downstream consumers 
will not appraoch you to provide them infoation that THEY need to fulfill THEIR legal obligations.
[Recital 15](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#rct_15) speaks to "intention of 'making a profit'" as one possible area that open soruce projects and developers need to understand where they 
*may* be considered to have more obligatipons under the law in line with Manufactureurs.  The OpenSSF and other upstream foundations are working with the European Commission (ec) to provide better definitiaon ad clarity around statemns like this to help guide upstream.

## Open Source Stewards ##
[Article 24](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#art_24) describes the three obligations that OSS Stewards must fulfill.  
The Steward role was recognized early on by EU policymakers as distinct from the software creators and the commercial organizations that sell products using those technologies.

While open source software stewards are not subject to the full obligations imposed on manufacturers under this Regulation (and therefore may not affix the CE marking to supported digital products), they remain responsible for implementing a security strategy, reporting vulnerabilities, and cooperating with market surveillance authorities to ensure the cybersecurity and integrity of open source projects. 

## Manufacturer ##
[Article 13](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=OJ:L_202402847#art_13) lays down the obligations of Manufacturers under the CRA.

# Table of Contents #
This Playbook is divided up into sections that focsu in on assiorted topic areas of the CRA including:
- [CRA Glossary of Terms]()
- [Coordinated Public Vulnerability Reporting & Process]()
- [Entities involved in the CRA]()
- [Important Files & Artifacts for the CRA]()
- [Information EU Officials may ask for]()
- [Software Bill of Materials (SBOM) generation]()
- [EU Single Rpoerting Platofmr (SRP) and Natiopnal CSIRT designation]()
- [Known Exploited Vulnerabilties]()
- [Severe Incidents]()
- [CRA Checklists]()
- [OpenSSF & the Linux Foundation as Open Source Stewards]()
