# Google-Conduct-A-Security-Audit

## Scenario <br></br>

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. <br></br>

 ## Botium Toys: Scope, goals and risk assessment Overview
<br> </br> 
Scope: The scope is defined as the entire security program at Botium Toys. This means
all assets need to be assessed alongside internal processes and procedures related to
the implementation of controls and compliance best practices. <br></br>
Goals: Assess existing assets and complete the controls and compliance checklist to
determine which controls and compliance best practices need to be implemented to
improve Botium Toys’ security posture.<br></br>
Risk Assessment: 
Risk description
Currently, there is inadequate management of assets. Additionally, Botium Toys does
not have all of the proper controls in place and may not be fully compliant with U.S. and
international regulations and standards.<br></br>
Control best practices
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to
dedicate resources to identify assets so they can appropriately manage them.
Additionally, they will need to classify existing assets and determine the impact of the
loss of existing assets, including systems, on business continuity.<br></br>
Risk score
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of
controls and adherence to compliance best practices.<br></br>



## Controls List
<br></br>

### Current assets
Assets managed by the IT Department include: <br></br>
● On-premises equipment for in-office business needs<br></br>
● Employee equipment: end-user devices (desktops/laptops, smartphones),
remote workstations, headsets, cables, keyboards, mice, docking stations,
surveillance cameras, etc.<br></br>
● Storefront products available for retail sale on site and online; stored in the
company’s adjoining warehouse<br></br>
● Management of systems, software, and services: accounting,
telecommunication, database, security, ecommerce, and inventory
management<br></br>
● Internet access<br></br>
● Internal network<br></br>
● Data retention and storage<br></br>
● Legacy system maintenance: end-of-life systems that require human
monitoring<br></br>

### Administrative Controls
| Control Name | Control Type | Implementation | Priority| 
|--------------|--------------|----------------|---------|
| Least Privilege| Preventative| Yes | High |
| Disaster Recovery Plan| Corrective| Yes| High |
| Password Policies| Preventative| Yes| High|
| Access Contorl Policies| Preventative| Yes| High|
| Access Management Policies| Preventative| Yes| High|
| Seperation of duties| Preventative| Yes| High|

### Technical Controls
| Control Name | Control Type | Implementation | Priority| 
|--------------|--------------|----------------|---------|
| Firewalls | Preventative |  | |
| IDS/IPS | Detective | Yes| High |
| Encrpytion| Deterrent | Yes| High |
| Backups | Corrective | Yes | High |
| Password management | Preventative| Yes | High |
| Antivirus (AV) Software | Corrective | Yes | High |
| Manual monitoring, maintenance, and intervention | Preventative | Yes | High| 

### Physical Controls 
| Control Name | Control Type | Implementation | Priority| 
|--------------|--------------|----------------|---------|
| Time Controlled safe | Deterrent | Yes | Medium/High| 
| Adequate Lighting | Deterrent | Yes | Medium/High |
| Closed Circuit Television | Preventative/Detective | Yes | Medium/High |
| Locking Cabinests (for network gear) | Preventative | Yes | High |
| Signage indicating alarm service provider | Deterrent | Yes | Low |
| Locks | Deterrent/Preventative | Yes | Medium/High |
| Fire detection and prevention (fire alarm, sprinkler system, etc.) | Detective/Preventative | Yes | High|


Current Controls Assessment Checklist:

|Control| Yes | No|
|--|---|---|
Least Privilege| | x |
Disaster recovery plans| | x |
Password policies| x|  |
Separation of duties| x|  |
Firewall| | x |
Intrusion detection system (IDS)| | x |
Backups| | x |
Antivirus software| | x |
Manual monitoring, maintenance, and intervention for legacy systems| | x |
Encryption| | x |
Password management system|x |  |
Locks (offices, storefront, warehouse)|x |  |
Closed-circuit television (CCTV) surveillance| x | |
Fire detection/prevention (fire alarm, sprinkler system, etc.)| | x |

## Compliance Checklist 

Botium Toys will need to adhere to the following standards:

● General Data Protection Regulation (GDPR)

GDPR is a European Union (E.U.) general data regulation that protects the processing of E.U. citizens' data and their right to privacy in and out of E.U. territory

Current Complicant Adherence Checklist:
|Control| Yes | No|
|--|---|---|
E.U. customers’ data is kept private/secured. |x |  |
There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. | | x |
Ensure data is properly classified and inventoried.  |x |  |
Enforce privacy policies, procedures, and processes to properly document and maintain data. |x |  |


● Payment Card Industry Data Security Standard (PCI DSS)

PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure environment. 

Current Complicant Adherence Checklist:
|Control| Yes | No|
|--|---|---|
Only authorized users have access to customers’ credit card information. |x |  |
Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment. |x |  |
Implement data encryption procedures to better secure credit card transaction touchpoints and data.| x|  |
Adopt secure password management policies.| | x |


● System and Organization Controls (SOC type 1 and SOC type 2)

They are used to assess an organization’s financial compliance and levels of risk. They also cover confidentiality, privacy, integrity, availability, security, and overall data safety. Control failures in these areas can lead to fraud.

Current Complicant Adherence Checklist:
|Control| Yes | No|
|--|---|---|
User access policies are established. | | x |
Sensitive data (PII/SPII) is confidential/private. | x|  |
Data integrity ensures the data is consistent, complete, accurate, and has been validated.|x |  |
Data is available to individuals authorized to access it.| x |  |



## Recommendations

It is reommended that Botium Toys correct all of their practices that they are not currently adhereing to and adhere to them. With adhereing to them they will be significantly stronger and well equiped to handle their increased online worldwide demand.
