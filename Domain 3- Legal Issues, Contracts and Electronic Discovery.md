# Domain 3: Legal Issues, Contracts and Electronic Discovery

## Introduction

This domain highlights some of the legal aspects raised by cloud computing. It provides a general background on legal issues that can be raised by moving data to the cloud, some issues for consideration in a cloud service agreement, and the special issues presented by electronic discovery in litigation.

This domain provides an overview of selected issues, however it does not go into sufficient detail to address every potential situation. To address your particular issues, you should consult with legal counsel in the jurisdiction(s) in which you intend to operate and/or in which your customers reside. In addition, be aware that laws and regulations are subject to change, and thus one should verify and update any references or information contained in this domain before relying on it in real-world situations.

Specific areas covered include:

* Legal issues.
* Cloud service agreements (contracts).
* Third-party access to electronic documents stored in the cloud.

Although this domain includes some aspects of data governance and audit/compliance, those are covered in depth in domains 4 and 5.

This domain is primarily concerned with the legal implications of public cloud computing or third-party-hosted private clouds, since on-premises private clouds can be treated like most existing IT operations.

## Overview

### Data Protection/Privacy Legal Frameworks

In many countries throughout the world, numerous laws, regulations, and other mandates require public and private organizations to protect the privacy of personal data and the security of information and computer systems. These laws are based in part on the Privacy and Security Guidelines of the Organization for Economic Cooperation and Development (OECD) and the Asia Pacific Economic Cooperation’s (APEC) Privacy Framework. 

Cloud providers and cloud consumers operating in multiple regions will face a matrix of *jurisdictions* where various laws and regulations apply. This is affected by:

	* The location of the cloud provider.
	* The location of the cloud consumer.
	* The location of the data owner (the individual or person that "owns" and provides the data).
	* The legal jurisdiction of the contract, which may be different than the locations of any stakeholders.
	* Any treaties or other legal frameworks between those various locations.

***************insert 3.1*************
> Applicable legal requirements will vary tremendously based on the various jurisdictions and legal entities and frameworks involved.

For example, in the Asia Pacific region, countries including Japan, Australia, New Zealand, and many others have adopted data protection laws that require the data controller to adopt reasonable technical, physical, and administrative measures in order to protect personal data from loss, misuse, or alteration. 

In Japan, the Personal Information Protection Act requires the private sectors to protect personal information and data securely. There are also sector-specific laws in many cases. For example in the healthcare industry, profession-specific laws such as the Medical Practitioners' Act; the Act on Public Health Nurses, Midwives and Nurses; and the Pharmacist Act require registered health professionals to maintain the confidentiality of patient information.

In Australia, two key laws provide protection to consumers when using cloud services: the Privacy Act 1988 (Privacy Act) and Australian Consumer Law (ACL). The Privacy Act addresses how personal information must be handled to ensure protection of information or opinion about an individual and that it cannot be linked from the data to the person. ACL protects consumers from false or misleading contracts and poor conduct from providers. The Privacy Act can apply for Australian customers, even if the cloud service provider is based overseas and other laws are stated in a contract. 

In the European Economic Area (EEA), the data protection requirements have historically been set out in two major EU Directives (a type of EU law that member states are required to implement in their own laws): the 1995 European Union (EU) Data Protection Directive and the 2002 E-Privacy Directive (as amended in 2009). These directives include a security component, and the obligation to provide adequate security must be passed down to subcontractors. Other countries that have close ties with the EEA, such as Morocco and Tunisia in Afric, and Israel and the United Arab Emirates in the Middle East, have also adopted similar laws that follow the same principles. 

Both the 1995 Data Protection Directive and the 2002/2009 E-Privacy Directive are being phased out and are replaced by Regulations. On May 4, 2016, the European Union adopted its new [General Data Protection Regulation (GDPR)](http://ec.europa.eu/justice/data-protection/); unlike Directives, Regulations are directly binding on member states, without any need for further legislation. The GDPR will come into effect on May 25, 2018. (There is also a new accompanying Directive that must be given effect within each member state by May 6, 2018.) The DPR will supersede the 1995 Data Protection Directive. A first draft of an E-Privacy Regulation that would replace the 2002 E-Privacy Directive has been published and the document is expected to be finalized promptly to supplement the GDPR when it becomes enforced.

From the perspective of non-EU corporations, one major difference between the Directives and the Regulation is how the new Regulation is enforced. Under the old Directives, European data privacy was enforced outside the EU under the terms of individual national laws, as well as treaties with the EU. This includes agreements like EU - U.S. Safe Harbor (now defunct, after the ruling in [Maximillian Schrems v. Data Protection Commissioner (2015)](http://curia.europa.eu/juris/documents.jsf?num=C-362/14)), or its replacement, the [EU - U.S. Privacy Shield](http://ec.europa.eu/justice/data-protection/international-transfers/eu-us-privacy-shield/index_en.htm). Therefore, under the Directives, corporations that breached EU privacy regulations would be subject to enforcement actions under their own country's laws and regulations, rather than the EU's. Under the new DPR, EU law is directly binding on any corporation that processes the data of EU citizens, regardless of whether they have any European presence. It remains to be seen what the efficacy of this enforcement regime will be.

North, Central, and South American countries are also adopting data protection laws at a rapid pace.  Each of these laws includes a security requirement and places on the data custodian the burden of ensuring the protection and security of personal data wherever the data are located, and especially when transferring to a third party. For example, in addition to the data protection laws of Canada, Argentina, and Colombia—which have been in existence for several years—Mexico, Uruguay, and Peru have all passed data protection laws that are inspired mainly by the European model and may include references to the APEC Privacy Framework as well.

Organizations that do business in the United States may be subject to one or more data protection laws. The laws hold organizations responsible for the acts of their subcontractors. For example, the security and privacy rules under the Gramm-Leach-Bliley Act (GLBA) or the Health Insurance Portability and Accountability Act of 1996 (HIPAA) require that organizations compel their subcontractors, in written contracts, to use reasonable security measures and comply with data privacy provisions. Industry rules that are enforced under contract, such as the Payment Card Industry Data Security Standards (PCI-DSS), also require subcontractors to maintain compliant security practices.

Beyond these well-known examples, the United States has a huge number of smaller laws and regulations that may affect any given storage or use of personal information. These data privacy rules are often embedded in larger sets of regulations pertaining to the activities of one industry. (For instance, see 21 C.F.R. § 21, which concerns privacy rules for information being submitted to or compiled by the Food and Drug Administration.) There are also government agencies, such as the Federal Trade Commission (FTC) or the Attorneys General of each state, that have the power to enforce privacy and security requirements in the general case, regardless of whether a specific privacy law affects a situation. For instance, in [*FTC v. Wyndham*, 799 F.3d 236 (3d. Cir. 2015)](https://www.ftc.gov/enforcement/cases-proceedings/1023142-x120032/wyndham-worldwide-corporation), the court held that the FTC could regulate failure to maintain "commercially reasonable security" as an unfair trade practice (something which falls into the FTC's jurisdiction).

Generally speaking, most countries with strong data privacy laws focus their regulations on the data subject—the person to whom the data refers. These rules protect the data regardless of who holds it. By contrast, United States privacy laws focus on who holds the data. For instance, HIPAA protections only apply to data that is held by health plans, healthcare clearinghouses, and healthcare providers, as well as their agents (referred to by HIPAA as Business Associates); other entities that may collect and use health data are likely not to be bound by HIPAA. A similar model applies to most of the other U.S. federal privacy laws and regulations.

In the United States, in addition to federal laws and regulations, most states have laws relating to data privacy and/or data security, at least with respect to financial information lost in a breach. These laws apply to corporations with any U.S. presence (not just a presence in the particular state with the law), regardless of where in the U.S. the data is stored. Some states' laws apply only to their own citizens' data; other states' laws apply both to the data of their own citizens as well as the data of citizens of other states lacking their own data privacy laws. (See, e.g., Texas's state law [Tex. Bus. & Com. Code § 521.053(b)](http://www.statutes.legis.state.tx.us/Docs/BC/htm/BC.521.htm).) Some of these laws are extremely general; others reference specific standards (such as PCI-DSS, mentioned above) and assign liability on the basis of compliance. (See, e.g., Washington's state law [RCW 19.255.020(2)(b)](http://apps.leg.wa.gov/rcw/default.aspx?cite=19.255.020).)

The following sections provide examples of legal issues that may arise in connection with the transfer of personal data to the cloud or the processing of personal data in the cloud.

|	Issue	|	Description	|
|	----------	|	--------------	|
|	U.S. Federal Laws		|	The United States is part of a small number of countries that do not have a national data protection law that applies to all types of personal data uniformly. Instead, it relies on a patchwork of federal, state, and sometimes local laws. Numerous federal laws and their related regulations—such as GLBA, HIPAA, and the Children’s Online Privacy Protection Act of 1998 (“COPPA”)—together with orders issued by the FTC require companies to adopt specific privacy and security measures when processing data. They also require similar precautions in their contracts with the third-party service provider. The numerous consent decrees issued by the FTC in enforcement cases under Section 5 of the FTC Act—or by state attorneys general in similar cases under their states' unfair and deceptive practices act—require that investigated companies adopt “commercially reasonable measures” to provide adequate privacy or security (as applicable). The ruling in FTC v. Wyndham requires that companies adopt "commercially reasonable security measures" when processing data.	|
|	U.S. State Laws		|	Numerous state laws also create an obligation on companies to provide adequate privacy protections or security for personal data and to require their service providers to do the same.  State laws that address information security issues generally require, at a minimum, that the company have a written contract with the service provider with reasonable security measures. See, e.g., the extensive requirements under the [Massachusetts "Standards for the Protection of Personal Information of Residents of the Commonwealth," 201 CMR 17.00](http://www.mass.gov/ocabr/docs/idtheft/201cmr1700reg.pdf).	|
|	Standards		|	Standards such as PCI-DSS or ISO 27001 also create a domino effect similar to that of federal and state laws. Companies that are subject to PCI-DSS or ISO 27001 must both comply with specified standards and pass onto their subcontractors the same obligation to meet the standard to which they are subject.	|
|	Non-U.S. Regulations	|	Many countries have adopted data protection laws that follow the European Union model, the OECD model, or the APEC model. Under these laws, the data controller (typically the entity that has the primary relationship with an individual) is prohibited from collecting and processing personal data unless certain requirements are met: for example, if the data subject has consented to the collection of his data as well as to the proposed uses of this data. These laws define a number of obligations for the entities that access the personal data, such as certain confidentiality and security obligations. They grant to individuals a series of rights that they can assert against any entity holding their personal data. When entrusting a third party to process data on its behalf (data processors) a data controller remains responsible for the collection and processing of personal data by those third parties. The data controller is required to ensure that any third party processing personal data on its behalf takes adequate technical and organizational security measures to safeguard the data. 	|
|	Contractual Obligations		|	Even if a specific activity is not regulated, companies may have a contractual obligation to protect the personal information of their clients, contacts, or employees to ensure that the data is not used for secondary uses, and is not disclosed to third parties. This obligation may stem, for example, from the Terms and Conditions and Privacy Statement that a company post on its website, or from contracts that the company has executed with third parties. For example, a data processor may be bound by the terms of its Services Agreement to only process the personal data for certain purposes. Alternatively, the company may have entered into contracts (such as service agreements) with its customers, in which it has made specific commitments to protect the data (personal data or company data), limit its use, ensure its security, use encryption, etc. The organization must ensure that, when data in its custody is hosted in the cloud, it will have the continued ability to meet the promises and commitments that it made in its privacy notice(s) or other contracts. For example, the company may have agreed to make only specific uses of the data. Data in the cloud must be used only for the purposes for which it was collected. 
If the privacy notice allows individual data subjects to have access to their personal data, and to have this information modified or deleted, the cloud service provider must also allow these access, modification, and deletion rights to be exercised to the same extent as it would in a non-cloud relationship.	|
|	Prohibition against cross border transfers		|	Many laws throughout the world prohibit or restrict the transfer of information out of the country. In some cases (for instance, that of the European Union), the transfer is permitted only if the country to which the data is transferred offers an adequate protection of personal information and privacy rights. The purpose of this adequacy requirement is to ensure that the individual data subjects whose data is transferred across borders will be able to enjoy, in the new country to which their data was transferred, privacy rights and privacy protections that are similar to, and not less than, those that were afforded to them before the transfer. Or, it may be necessary for the data importer and the data exporter to sign a contract in which the parties ensure that the rights of the data subjects will be protected once the data has been transmitted to the data importer. Thus, it is important for a cloud user to know where the personal data of its employees, clients, and others will be located, so that it can address the specific restrictions that foreign data protection laws may impose. Depending on the country, the requirements for ensuring this adequate protection may be complex and stringent. In some cases, it may be necessary to obtain prior permission of the local Data Protection Commissioner. In other countries (typically, those with limitations on the flow of information), transfer of citizens' data outside the country is simply prohibited.	|

### Contracts and Provider Selection

When data or operations are transferred to a cloud, the responsibility for protecting and securing the data typically remains with the collector or custodian of that data, even if in some circumstances this responsibility may be shared with others. Even when it relies on a third party to host or process its data, the custodian of the data remains liable for any loss, damage, or misuse of the data. It is therefore prudent, and may be required by law or regulation, that the data custodian and the cloud provider enter into a formal written agreement that clearly defines the roles, the expectations of the parties, and the allocation of the many responsibilities that are attached to the data at stake. Such an agreement should also clearly identify the permitted and prohibited uses of the data, and the measures to be taken if the data were stolen or compromised.

The laws, regulations, standards and the related best practices discussed above, also require data custodians to ensure that these obligations will be fulfilled by conducting due diligence (before execution of the contract) or security audits (during performance of the contract).

#### Internal Due Diligence

Companies are the custodians of the data entrusted to them. As seen above, numerous laws, regulations or contracts prohibit, restrict, or limit the disclosure or transfer of data to a third party. For example, health information protected under HIPAA cannot be transferred to a third party or “business associate” without imposing specific obligations on that business associate. If the data originates abroad, it is likely that there are significant obstacles to its transfer across borders to a country that does not provide “adequate protection” to privacy rights and personal data.

Before entering into a cloud computing arrangement, a company should evaluate its own practices, needs, and restrictions in order to identify the legal barriers and compliance requirements associated with a proposed cloud computing transaction. For example, it should determine whether its business model allows for the use of cloud computing services, and under which conditions. For instance, the nature of its business might be such that it is restricted by law from relinquishing control over company data.

The company should investigate whether it has entered into any confidentiality agreements or data use agreements that might restrict the transfer of data to third parties, even if these third parties are service providers. If the company has signed a confidentiality agreement to protect personal information or trade secrets, this agreement probably prohibits hiring a subcontractor without the prior permission of the data owner. A data use agreement to which the company is a party may require the consent of a customer if the company plans to subcontract the processing of the customer’s data to a third party. That restriction would in most cases apply to transfers to a cloud service provider. Under these circumstances, moving data to a cloud without the prior permission of the customer (data owner) would cause a breach in the data use agreement with that customer.

In other circumstances, the data processed by the company might be so sensitive or confidential that it should not be transferred to cloud, or the transfer might require significant precautions. This might be the case, for example, for files that pertain to high stakes projects such as R&D road maps, or plans for an upcoming IPO, merger, or acquisition.

In addition, common law concepts such as the concept of “duty of care” or “duty of competence” might be a significant factor in requiring that the company conduct due diligence of the proposed cloud service provider, in order to determine whether the offering will allow the company to fulfill its continued obligation to protect its assets.

#### Monitoring, Testing and Updating

The cloud environment is not static. It evolves, and the parties must adapt. Periodic monitoring, testing, and evaluation of cloud services are recommended, in order to ensure that the required privacy and security measures are being used, and that all required processes and policies are being followed. Without this periodic testing, control efficacy may be compromised in an undetected fashion.

In addition, the legal, regulatory, and technical landscape in which any company operates changes at a rapid pace. New security threats, new laws, and new compliance requirements must be addressed promptly. Both cloud clients and cloud providers must keep abreast of relevant legal, regulatory, contractual, and other requirements, and ensure both that their operations remain compliant with applicable laws and regulations, and that the security measures in place continue to evolve as new technologies emerge.  

#### External Due Diligence

Before entering into any contract, a critical part of due diligence must be to request and review all relevant aspects of the operations of the other party—in this case, that of the proposed cloud provider or vendor. A purchaser of cloud services needs to ensure that it understands the particular application or service it is contemplating acquiring. The extent of the due diligence and the time invested in it will depend upon the circumstances. The process may take a day, a week, or a month depending on the specific needs of the customer, the nature of the data to be processed, the sensitivity and intensity of the processing, and other factors that would make a particular operation “routine” or “highly sensitive.”

Thus, depending on the nature of the proposed project, the due diligence may involve evaluating the nature and completeness of the services provided, the reputation for quality or stability of the service, the availability of a certain level of support or maintenance, the responsiveness of customer service, the speed of the network, or the location of the data centers. Interviewing customers might provide valuable insight. Reviewing reports of litigation filed against the cloud providers might be eye-opening. Checking references and conducting online searches to evaluate the vendor’s reputation might be extremely valuable, as well.

In most cases, the cloud customer will want to evaluate at least the applicable service level, end-user, and legal agreements; privacy policies; security disclosures; and proof of compliance with applicable legal requirements (e.g. registration requirements) to ensure that the conditions stated by the cloud provider are suitable for its organization. Depending on the expected depth and intensity of the due diligence, issues to be investigated may include:

* Will the service will be reliable and easy to use? 
* How will the servers be used to process the data?
* How will the service operate and be provided?
* Will the data be collocated with others customers’ data?
* How will be data be protected from intrusion or disasters. 
* How will the price evolve over time? 
* Will the cloud vendor meet the company’s computing and access needs?
* Will the cloud vendor remain in business for the next few years? What is its financial profile?
* What service levels will be offered? 
* What security measures are used? 
* What will happen in the event of a breach of security? 

Reviewing all terms and conditions of the cloud services agreement (including all annexes, schedules, and appendices) is good due diligence for any new project. It's especially critical for cloud computing, as some vendor terms and conditions will be non-negotiable. In those instances, the company will need to be prepared and equipped to make an informed decision to use or not to use a provider.

#### Contract Negotiations

Cloud contracts are intended to accurately describe the understanding of the parties. Numerous precautions and measures can be taken by the parties to reduce their exposure to legal, commercial, and reputational risk in connection with the use of cloud services. 

The proposed contact should always be reviewed carefully, even if one is told that it is not negotiable. For one thing, it might actually be possible to negotiate changes. Even if it is not possible to do so, each purchaser of cloud services should understand the consequences and implications of the engagement it is making. A contract that cannot be negotiated is likely to lack some of the protections that the typical customer would need. In this case, the customer should balance the risks from foregoing these protections against the promised benefits. 

#### Reliance on Third-Party Audits and Attestations

Audits and compliance are covered in more detail in Domain 4, but two considerations may affect contractual and legal/regulatory requirements. In cloud computing third-party audits or attestations are frequently used to assure compliance with aspects of the cloud provider's infrastructure, which allows a cloud customer to build their own compliant services on top of the cloud platform. It is critical for a provider to publish, and a customer to evaluate:

* The scope of the assessment.
* Which particular features/services are included in the assessment.

For example, a cloud provider's newest storage offering may not be HIPAA-compliant (and thus the provider may not be willing to sign a HIPAA Business Associate Agreement (BAA) covering it), even though many of its other service offerings are able to be used in a HIPAA-compliant fashion.

### Electronic Discovery

This section addresses the unique requirements of litigation in the United States. The U.S. rules around "discovery"—the process by which an opposing party may obtain private documents for use in litigation—cover a wide range of potential documents. In particular, discovery need not be limited solely to documents that are known at the outset to be admissible as evidence in court; instead, discovery will apply to all documents reasonably calculated to lead to admissible evidence (evidence that is both relevant and probative). See generally Rule 26, Federal Rules of Civil Procedure (FRCP).

In recent years, there have been numerous situations in which litigants were said to have voluntarily deleted, lost, or modified important evidence that was detrimental to their case. In these cases, the Federal Rules of Civil Procedure allow, among other penalties, money to be awarded to the side not responsible for the destruction; in some cases, the jury may be given an instruction on an "adverse inference" (where the judge or jury are instructed to assume that the destroyed evidence says the worst possible thing for the party that destroyed it). See generally Rule 37, FRCP. As a result of the ongoing litigation in this area, the FRCP have been changed to clarify the obligations of the parties, especially in the case of electronically stored information (ESI).

Since the cloud will become the repository of most ESI that is needed in a litigation or investigation, cloud service providers and their clients must carefully plan how they will be able to identify all documents that pertain to a case, in order to be able to fulfill the stringent requirements imposed by FRCP 26 with regard to ESI, and the state equivalents to these laws.

In this regard, the cloud service client and provider need to consider the following issues in matters when a client is subject to a discovery request and potentially relevant data exists with the cloud provider.

#### Possession, Custody, and Control  

In most jurisdictions in the United States, a party’s obligation to produce relevant information is limited to documents and data within its possession, custody, or control. Hosting relevant data at a third party, such as a cloud provider, generally does not obviate a party’s obligation to produce information, as it may have a legal right to access or obtain the data. However, not all data hosted by a cloud provider may be in the control of a client (e.g., disaster recovery systems, or certain metadata created and maintained by the cloud provider to operate its environment). Distinguishing the data that is and is not available to the client may be in the interest of both the client and provider. The obligations of the cloud service provider as cloud data handler with regard to the production of information in response to legal process is an issue left to each jurisdiction to resolve.  

#### Relevant Cloud Applications and Environment  

On occasion, the actual cloud application or environment could itself be relevant to resolving a dispute. In these circumstances, the application and environment will likely be outside the control of the client and require that a subpoena or other discovery process be served on the provider directly.

#### Searchability and E-Discovery Tools 

Because of the cloud environment, a client may not be able to apply or use e-discovery tools that it uses in its own environment. Moreover, a client may not have the ability or administrative rights to search or access all of the data hosted in the cloud. For example, where a client could access multiple employees’ e-mail accounts on its own server at once, it may not have this ability with e-mail accounts hosted in the cloud. As such, clients need to account for the potential additional time and expense that this limited access will cause. To the extent that the customer is able to negotiate or supplement the cloud service agreement, this issue could be addressed ahead of time. Otherwise, the cloud customer may have no other option than to address the issue on a case-by-case basis; it might therefore have to pay for the additional services of the cloud provider in performing the needed search.

#### Preservation

Generally speaking, in the United States a party is obligated to undertake reasonable steps to prevent the destruction or modification of data or information in its possession, custody, or control that it knows, or reasonably should know, is relevant to either pending or reasonably anticipated litigation or a government investigation. (This is often referred to as a "litigation hold" on document destruction.) Depending on the cloud service and deployment model that a client is using, preservation in the cloud can be very similar to preservation in other IT infrastructures, or it can be significantly more complex.

In the European Union, information preservation is governed under Directive 2006/24/EC of the European Parliament and of the Council of 15 March 2006. Japan, South Korea, and Singapore have similar data protection initiatives. Within South America, Brazil and Argentina have the Azeredo Bill and the Argentina Data Retention Law 2004, Law No. 25.873, 6 February 2004, respectively. In the United States, these concerns are addressed broadly by Federal Rule of Civil Procedure 37, though there are myriad jurisdictional rulings that apply to potential litigants.

#### Data Retention Laws and Record Keeping Obligations

In addition to data preservation obligations resulting from the U.S. laws regarding e-discovery, companies may need to be aware of the effect of certain data retention laws.  Data retention laws require covered entities to retain data for a certain period of time.  

##### Costs and Storage

Preservation can require that large volumes of data be retained for extended periods. What are the ramifications of this under the service level agreement (“SLA”)? What happens if the preservation requirements outlast the terms of the SLA? If the client preserves the data in place, who pays for the extended storage and at what cost? Does the client have the storage capacity under its SLA? Can the client effectively download the data in a forensically sound manner so it can preserve it off-line or near-line? All of these questions should be considered as part of a move to the cloud.

##### Scope of Preservation

A requesting party is only entitled to data that is hosted in the cloud that contains or is reasonably calculated to lead to relevant, probative information for the issue at hand. The party is not entitled to all the data in the cloud or in the application. (The issue of what precisely the limits are is one likely to be resolved in litigation.) However, if the client does not have the ability to preserve only the relevant information or data in a granular way, it may be required to over-preserve in order to effect reasonable preservation, depending on the litigation or investigation. (The information is then worked through for a determination of what must and must not be turned over as part of the discovery process. This process, referred to as a document review or privilege review, may be undertaken by paid attorney staff or, in some cases, by emerging expert systems. How to sort the ever-more-voluminous quantities of information that may be produced by discovery is an ongoing area of both legal and technical research.)

##### Dynamic and Shared Storage

The burden of preserving data in the cloud may be relatively modest if the client has space to hold it in place, if the data is relatively static, and if the people with access are limited and know to preserve the data. However, in a cloud environment that programmatically modifies or purges data, or one where the data is shared with people unaware of the need to preserve, preservation can be more difficult. After a client determines that such data is relevant and needs to be preserved, the client may need to work with the provider to determine a reasonable way to preserve such data.

#### Collection

Because of the potential lack of administrative control a client has over its data in the cloud, collection from the cloud can be more difficult, more time-consuming, and more expensive than from behind a client’s firewall. In particular, a client may not have the same level of visibility across its cloud data, and it may have more difficulty comparing the data it has collected with the data in the cloud to determine that export was reasonably complete and accurate.

##### Access and Bandwidth 

In most cases, a client’s access to its data in the cloud will be determined by its SLA.  This may limit its ability to collect large volumes of data quickly and in a forensically sound manner (i.e., with all reasonably relevant metadata preserved). Clients and cloud providers are well served to consider this issue at the outset of their relationship, and to establish a protocol (and a cost) for extraordinary access in the case of litigation.  Absent these agreements, clients should consider the extra time and cost implicated by collection in the cloud when making representations to requesting parties and courts. Note that FRCP 26(b)(2)(B) excuses a litigant who is able to show that the information requested is not reasonably accessible because of undue burden or cost. However, even if such showing is made, the court may nonetheless order discovery from such sources if the requesting party is able to show why this information is needed and may not be obtained otherwise.

In a related issue, a client's right of access may provide them access to a full range of data, but not provide them the degree of functionality that would best assist them in a given situation. By way of example, a client may have access to three years of retail transactional data, but may only be able to download data two weeks at a time due to functionality constraints. Moreover, a client may not have full view into all the metadata that exists, but rather into only a more limited degree of metadata. It is prudent to learn what is possible with the tools available to a client before it becomes necessary to use them as a part of active litigation.

##### Forensics  

Bit-by-bit imaging of a cloud data source is generally difficult or impossible.  For obvious security reasons, providers are reluctant to allow access to their hardware, particularly in a multitenant environment where a client could gain access to other clients’ data. Even in a private cloud, forensics may be extremely difficult, and clients may need to notify opposing counsel or the courts of these limitations. (Again, FRCP 26(b)(2)(B) may provide relief from such undue burdens.) Luckily, this type of forensic analysis is rarely warranted in cloud computing, because the environment often consists of a structured data hierarchy or virtualization that does not provide significant additional relevant information in a bit-by-bit analysis.

#####  Reasonable Integrity

A client subject to a discovery request should undertake reasonable steps to validate that its collection from its cloud provider is complete and accurate, especially where ordinary business procedures are unavailable and litigation-specific measures are being used to obtain the information. This process is separate from verifying that the data stored in the cloud is accurate, authenticated, or admissible.
 
##### Limits to Accessibility

Because of differences in how data is stored, and the access rights and privileges available to the owner of the data, there are cases where a cloud customer may not be able to access all the data that it has stored in a cloud. The cloud customer and cloud provider may have to analyze the request for information and the pertinent data structures for relevance, materiality, proportionality, or accessibility when responding to a discovery request. 

#### Direct Access  

Outside of the cloud environment, a requesting party’s direct access to a responding party’s IT environment is not generally favored. (Although it does happen from time to time; in fact, some courts have been willing to allow no-notice seizures of IT equipment for the purpose of evidence preservation in civil cases, including employment disputes.) In the cloud environment, it is even less favored and may be impossible for the same reasons as a forensic analysis may be impossible. Importantly, a client may not be able to provide direct access because the hardware and facilities are outside its possession, custody, or control, and a requesting party would need to negotiate directly with the provider for such access.

#### Native Production 

Cloud service providers often store data in highly proprietary systems and applications that clients do not control. Generally, ESI is expected to be produced in standard formats (such as PDF for electronic documents), unless information lost by conversion (such as metadata) is relevant to the dispute. In these cases, production of data in the cloud-native format may be useless to the requesting party, as they will not be able to understand the information produced. In these circumstances, it may be best for all concerned—requesting party, producing party, and provider—that the relevant information be exported using standard reporting or exporting protocols that exist within the cloud environment, with due care given to preserving any relevant information.

#### Authentication  

Authentication in this context refers to forensic authentication of data that is admitted into evidence. (This should not be confused with user authentication, which is a component of Identity Management.) Storing data in the cloud does not affect the authentication of data to determine if it should be admitted into evidence. The question is whether the document is what it purports to be. For example, an e-mail is no more or less authentic because it was stored behind a company’s firewall or was stored in the cloud; the question is whether it was stored with integrity, such that the court can trust that it has not been altered since it was created. Absent other evidence, such as tampering or hacking, documents should not be considered more or less admissible or credible merely because they were created or stored in the cloud.

#### Cooperation between Provider and Client in e-Discovery  

It is in the best interests of both providers and clients to consider the complications caused by discovery at the beginning of their relationship and to account for it in their SLAs. Providers may want to consider designing their cloud offerings to include discovery services to attract clients (“Discovery by Design”). In any event, clients and providers should consider including an agreement to reasonably cooperate with each other in the event of discovery requests against either.

#### Response to a Subpoena or Search Warrant

The cloud service provider is likely to receive, from a third party, a request to provide information; this may be in the form of a subpoena, a warrant, or a court order in which access to the client data is demanded. The client may want to have the ability to fight the request for access in order to protect the confidentiality or secrecy of the data sought. To this end, the cloud services agreement should require the cloud service provider to notify the company that a subpoena was received and give the company time to fight the request for access.

The cloud service provider might be tempted to reply to the request by opening its facilities and providing the requester with whatever information is identified in the access request. Before doing so, the cloud service provider should ensure, in consultation with counsel, that the request is in good order and uses the appropriate legal method. The cloud service provider should carefully analyze the request before disclosing information in its custody, and consider whether it can meet its obligations to its clients through releasing information. In some cases, a provider may be better able to serve the needs of its clients by fighting an overbroad or otherwise problematic demand for information.

#### More Information

For more reading on discovery and electronically stored information, there are a wide variety of sources. One that may be of interest is the [Sedona Conference](https://thesedonaconference.org/publications#ediscovery), a group that has for several years made influential recommendations around the handling of ESI which have in turn shaped this emerging area of law. Note, however, that their recommendations do not themselves carry the force of law.

## Recommendations

* Cloud customers should understand the relevant legal and regulatory framework, as well as contractual requirements or restrictions that apply to the handling of their data and the conduct of their operations, before moving systems to the cloud.
* Cloud providers should clearly and conspicuously disclose guidance on their policies, requirements, and capabilities, and all terms and conditions that apply to the services they provide.
* Cloud customers should conduct a comprehensive evaluation of a proposed cloud service provider before signing a contract.
* Cloud providers should publish clear guidance on their policies, requirements, and capabilities to meet customer legal obligations, such as electronic discovery.
* Cloud customers should understand the legal implications of using particular cloud providers and match those to their legal requirements.
* Cloud customers must understand the legal implications of where the cloud provider physically operates and stores information.
	* In many cases, a cloud customer can choose where to host their data in order to comply with jurisdictional requirements.
* Cloud customers and providers should have a clear understanding of the legal and technical requirements to meet any electronic discovery requests.
* Cloud customers should understand that click-through legal agreements to use a cloud service do not obviate any requirements for performing appropriate due diligence.