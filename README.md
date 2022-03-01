# Federal-Zero-Trust 
This repository is a collection of resources to understand the Federal governments push for Zero Trust along with associated resources for learning more about Zero Trust

![image](https://user-images.githubusercontent.com/94196833/155004193-2b182a6a-e682-4c98-b987-d2bba218a8c1.png)

## "Please note that the "zero" in Zero Trust is a bit of a misnomer - it's not about literally "zero" trust, but about zero inherent or implicit trust. Zero Trust is about carefully building a foundation of trust, and growing that trust to ultimately permit an appropriate level of access at the right time" - Jason Garbis & Jerry Chapman - Zero Trust Security: An Enterprise Guide 


# Background

Zero Trust is far from being a new term or concept. The term itself dates back to 2010 when then Forrester analyst John Kindervag coined the term "Zero Trust" in research and publications. Going back even further, the Jericho Forum founded in 2004 was trying to define the problem and solutions to push for what they termed "de-perimiterization". Building on this, Google began to publish their BeyondCorp model which was founded on Google's own push to implement Zero Trust for their systems. That said, the Federal government, as often is the case, has taken some time to catch up to industry in its pursuit of Zero Trust. With the continued erosion of the legacy network perimiter and castle and moat approach to cybersecurity, agencies and Federal leaders have realized a need for a better security model that aligns with the modern threat landscape. This transition for the Government is accompanied by the increased adoption of a remote work paradigm as well as a broadscale push for digital modernization and cloud computing efforts. 

The push for Zero Trust in the Federal government has really begun to get traction with the publication of Executive Order 14028 "Executive Order on Improving the Nation's Cybersecurity". This EO mentions the term "Zero Trust" 11 times and specifically states "The Federal Government must adopt security best practices and advance towards a Zero Trust Architecture".

The EO specifically required the head of each agency to develop a plan to implement Zero Trust Architecture, aligned with guidance published by NIST. It also required the agencies to provide reporting to the Director of Office Management & Budget (OMB) on the plans. There are also requirements to weave Zero Trust Architecture through the agencies cloud migration and maturity efforts as well. Subsequently a memo has pushed the EO to the National Security Systems (NSS) such as the Department of Defense (DoD) and Intelligence Community (IC). DoD is currently undergoing a pilot titled Thunderdome and has released a Reference Architecture, which is listed below. Federal agencies have begun to develop and implement plans to meet their respective ZT goals and requirements. 


# Table of contents

- [Definitions](#Definitions)
- [Federal EO, Memos and Guidance](#Federal-EO,-Memos-and-Guidance)
- [Vendor Specific Zero Trust Content](#Vendor-Specific-Zero-Trust-Content)
- [Books](#Books)
- [Newsletters](#Newsletters)



# Definitions

To fully understand the context in which the Federal government views Zero Trust, we will completely lay out how they define it in the Cybersecurity EO

"The term “Zero Trust Architecture” means a security model, a set of system design principles, and a coordinated cybersecurity and system management strategy based on an acknowledgement that threats exist both inside and outside traditional network boundaries.  The Zero Trust security model eliminates implicit trust in any one element, node, or service and instead requires continuous verification of the operational picture via real-time information from multiple sources to determine access and other system responses.  In essence, a Zero Trust Architecture allows users full access but only to the bare minimum they need to perform their jobs.  If a device is compromised, zero trust can ensure that the damage is contained.  The Zero Trust Architecture security model assumes that a breach is inevitable or has likely already occurred, so it constantly limits access to only what is needed and looks for anomalous or malicious activity.  Zero Trust Architecture embeds comprehensive security monitoring; granular risk-based access controls; and system security automation in a coordinated manner throughout all aspects of the infrastructure in order to focus on protecting data in real-time within a dynamic threat environment.  This data-centric security model allows the concept of least-privileged access to be applied for every access decision, where the answers to the questions of who, what, when, where, and how are critical for appropriately allowing or denying access to resources based on the combination of sever."


# Federal EO, Memos and Guidance

- Executive Order 14028 "Executive Order on Improving the Nation's Cybersecurity" (https://www.whitehouse.gov/briefing-room/presidential-actions/2021/05/12/executive-order-on-improving-the-nations-cybersecurity/)
- Office of Management and Budget (OMB) Memo M-22-09 "Moving the U.S. Government Toward Zero Trust Cybersecurity Principles" This Memo sets forth a Federal zero trust architecture (ZTA) strategy, requiring agencies to meet specific cybersecurity standards and objectives by the end of Fiscal Year (FY) 2024 (https://www.whitehouse.gov/wp-content/uploads/2022/01/M-22-09.pdf)
- Cybersecurity and Infrastructure Security Agency (CISA) Zero Trust Maturity Model (https://www.cisa.gov/zero-trust-maturity-model) 
- Department of Defense (DoD) Zero Trust Reference Architecture (https://dodcio.defense.gov/Portals/0/Documents/Library/(U)ZT_RA_v1.1(U)_Mar21.pdf)
- Federal Zero Trust and Identity Management NSTAC Report to the President (https://www.cisa.gov/sites/default/files/publications/Final%20Draft%20NSTAC%20Report%20to%20the%20President%20on%20Zero%20Trust%20and%20Trusted%20Identity%20Management.pdf)

# NIST

- NIST 800-207 Zero Trust Architecture (https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-207.pdf)
- Whitepaper Planning for a Zero Trust Architecture: A Starting Guide for Administrators (https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.08042021-draft.pdf)
- Conference DevSecOps and Zero Trust Architecture (ZTA) for Multi-Cloud Environments (https://www.nist.gov/news-events/events/2021/01/devsecops-and-zero-trust-architecture-zta-multi-cloud-environments)
- Conference DevSecOps and ZTA for Cloud-Native Applications - Third Annual Multi-Cloud Conference and Workshop (https://csrc.nist.gov/Events/2022/3rd-multi-cloud-annual-conference-devsecops-and-zt)



# Vendor Specific Zero Trust Content

## Forrester

- No More Chewy Centers: Introducing The Zero Trust Model Of Information Security by John Kindervag for Security & Risk Professionals (https://media.paloaltonetworks.com/documents/Forrester-No-More-Chewy-Centers.pdf)
- Forrester Zero Trust Blogs (https://www.forrester.com/blogs/tag/zero-trust/)
- The Zero Trust Security Playbook For 2022 (https://www.forrester.com/playbook/The+Zero+Trust+Security+Playbook+For+2020/-/E-PLA300)
- Zero Trust Is Not A Security Solution; It’s A Strategy (https://www.forrester.com/blogs/zero-trust-is-not-a-security-solution-it-is-a-strategy/)

## Google 

- BeyondCorp (https://cloud.google.com/beyondcorp)
- An overview: "A New Approach to Enterprise Security" (https://research.google.com/pubs/pub43231.html)
- How Google did it: "Design to Deployment at Google" (https://research.google.com/pubs/pub44860.html)
- Google's frontend infrastructure: "The Access Proxy" (https://research.google.com/pubs/pub45728.html)
- Migrating to BeyondCorp: "Maintaining Productivity while Improving Security" (https://research.google.com/pubs/pub46134.html)
- The human element: "The User Experience" (https://research.google.com/pubs/pub46366.html)
- Secure your endpoints: "Building a Healthy Fleet" (https://ai.google/research/pubs/pub47356)

## Microsoft 

- Zero Trust Guidance Center (https://docs.microsoft.com/en-us/security/zero-trust/)
- Transitioning to modern access architecture with Zero Trust (https://www.microsoft.com/en-us/insidetrack/transitioning-to-modern-access-architecture-with-zero-trust#:~:text=Microsoft%20has%20adopted%20a%20modern,of%20identities%2C%20devices%20and%20services.)

## Amazon Web Services (AWS) 

- Zero Trust on AWS (https://aws.amazon.com/security/zero-trust/)
- Blog - Zero Trust architectures: An AWS Perspective (https://aws.amazon.com/blogs/security/zero-trust-architectures-an-aws-perspective/)
- Video - re:Invent 2020 - Zero Trust: An AWS perspective (32:36) (https://www.youtube.com/watch?v=O33LPy4M4vA)

## HashiCorp 

- https://www.hashicorp.com/solutions/zero-trust-security
- https://www.hashicorp.com/resources/enabling-zero-trust-security-in-the-public-sector
- https://www.hashicorp.com/resources/how-zero-trust-networking


# Videos

- ATARC Federal Zero Trust Summit (https://www.youtube.com/watch?v=CfIWsq0bkTU)
- GovBrief Zero Trust Architecture Adoption in Federal Government (https://www.youtube.com/watch?v=Me7CRvVSElQ)
- Government Matters How can government agencies implement OMB guidance on zero trust? (https://www.youtube.com/watch?v=gcfRnaudErA)
- CISA Cybersecurity Summit 2021: Zero Trust (https://www.youtube.com/watch?v=wW3Qtv5MgeQ)
- ATARC Hear From the Authors: Federal Zero Trust Strategy and Maturity Model (https://www.youtube.com/watch?v=bhTujGT_bSo)
- FEDERAL TECH TALK with Dr. Chase Cunningham: A deeper understanding of zero trust (https://federalnewsnetwork.com/federal-tech-talk/2021/06/a-deeper-understanding-of-zero-trust/)


# Books

- Zero Trust Security: An Enterprise Guide (https://www.amazon.com/Zero-Trust-Security-Enterprise-Guide/dp/148426701X/ref=sr_1_3?crid=3J7JOGUU6H22F&keywords=zero+trust+security&qid=1645463553&s=books&sprefix=zero+trust%2Cstripbooks%2C1410&sr=1-3)
- Zero Trust Networks: Building Secure Systems in Untrusted Networks (https://www.amazon.com/Zero-Trust-Networks-Building-Untrusted/dp/1491962194/ref=sr_1_4?crid=3J7JOGUU6H22F&keywords=zero+trust+security&qid=1645463553&s=books&sprefix=zero+trust%2Cstripbooks%2C1410&sr=1-4)
- Zero Trust Architecture: A New Model For Combating Cyber Attacks (https://www.amazon.com/Zero-Trust-Architecture-Combating-Attacks-ebook/dp/B0938Y64RP/ref=sr_1_9?crid=3J7JOGUU6H22F&keywords=zero+trust+security&qid=1645463553&s=books&sprefix=zero+trust%2Cstripbooks%2C1410&sr=1-9)
- The CISO Guide to Zero Trust Security (https://www.amazon.com/CISO-Guide-Zero-Trust-Security/dp/B09RM5HXGR/ref=sr_1_11?crid=3J7JOGUU6H22F&keywords=zero+trust+security&qid=1645463553&s=books&sprefix=zero+trust%2Cstripbooks%2C1410&sr=1-11)

# Newsletters

- Dr. Zero Trust ZT Edge (https://www.zerotrustedge.com/)


# Creators

**Chris Hughes**

- <https://github.com/chughes757>

# Thanks

Special thanks goes out to all of the Zero Trust pioneers who have contributed to this modernized approach to cybersecurity over the years. From the concept in a whitepaper, vendor specific implementations and pursuits all the way to those who have played a role it now being a published Federal strategy and implementation goal. Specically I would like to thank leaders like John Kindervag, Dr. Chase Cunningham, Jerry Chapman, Evan Gilman, Doug Barth and Jasob Garbis, who I've personally learned a lot from on the topic of Zero Trust.

