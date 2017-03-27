# IOT an overview

> Feel like I knowed IoT, but I don't...
> So I read through [ISOC](https://www.internetsociety.org/sites/default/files/ISOC-IoT-Overview-20151014_0.pdf), hopes it let me know more about IoT

## Summary

### Key concepts serve as foundation for exploring opportunities and challenges of IoT:

- IoT Definition
 - Connectivity+Computing ability extends to objects, sensors
 - Minimal human intervention

- Enabling Technologies
 - IoT idea existed for decades, but recent trends bring it closer to reality
 - Connect anywhere, adoption of IP network, computing economies (eg driven by industry), miniaturization (moore's law), data analytics, cloud

- Connectivity Models
 - Common communications model: D2D, D2C, D2G, Backend data sharing

- Transformational Potential
 - Passive devices object; Active content

### Key IoT issue

- Security
 - new security challenges
 - fundamental priority when it integrated to our daily lives
 - Interconnect of poorly secure device (massive similiar IoT devices, one endangered all unsecure)
 - Developer + Users together to ensure the Internet safety

- Privacy
 - Respect of privacy right ensuring user trust to IoT
 - Features need aggregate many forms of data, but amplify concern of tracking

- Interoperability (interconnectivity) / Standards
 - fragment of technical implementations makes IoT products inflexible

- Legal
 - Crossborder data flow
 - Internet Society principle: connect, speak, innovate, share, choose, trust

- New Economy and Development Issue

## Intro

- promise vs peril of IoT
 - Promise: Smart X for security, energy, effectiveness, affordable, opportunity
 - Peril: Surveillance, privacy, security, monopoly

- 3 Main Sections:
 - What is IoT
 - What issues in IoT?
 - Further Information


## What Is IoT

### Origin

> - Kevin Ashton & RFID count and track goods without human intervention
> - Concept related to M2M
>  - Build on industry sprcific std
>  - not using IP based network
> - First IP enabled non-computer device: toaster
>

- What makes Iot possible?
 - Connectivity Everywhere, gateway everywhere
 - Adoption of IP-based net, or domination of TCP/IP
 - Computing Economics, money matters
 - Miniaturization, smaller more powerfull
 - Data Analytics
 - Cloud Computing

### Different definition

> - IAB: "Architectural Consideration in Smart Object Networking"
>  - embedded devices spread out in environment, with communications services
>  - not directly operated by humans
> - IETF: "Smart Object Networking"
>  - limited power, memory, cpu, bandwidth
> - ITU: "Overview of IoT"
>  - ensuring security; can idenfication, data capture & processing, communication capabilities
> - IEEE: "IoT to cloud services"
>  - All things presense in Internet
> - Oxford: "IoT"
>  - noun, interconnection of computing devices embedded in everyday objects

- **Computing capability** & **Network connectivity** extends to objects other than computers, require minimal human intervention

### Communications Models

- IAB: RFC 7425

#### Device to Device

- Not going through intermediary server
- Using protocol like: BT, Z-Wave, ZigBee
- Challenges:
 - Compatibility
 > IETF "devices usually have built-in security, trust mechanisms, specific data formats, protocols"


#### Device to Cloud

- Establish through exisiting communication machanism and protocol directly to cloud
- Add value to devices
- Challenges:
 - vendor lock-in: tied of device and service from preventing the data used by alternative vendors

#### Device to Gateway

- Gateway connected to cloud, relay data from devices
- To solve interoperability among devices

#### Back-End Data-Sharing Model

- Share data to 3rd parties app
- Standards protocols Restful-API, Oauth, JSON etc
- Challenges: Data Silos
 - Common information models are needed


## Issues raised by IoT

- ISOC: Internet users should enjoy the ability and protected
- Abilities: *connect, speak, innovate, share, choose, trust*

### Security Issues (*trust*)

#### IoT Security Challenge

- Large numbers of poorly secure devices on Internet
- Unplug Internet connected devices from Internet myth? control system, power meter is unable to turn off easily


#### Spectrum of security considerations

- IoT security is not binary proposition, spectrum ranges of security (from unprotected to highly secure)
- Security is endless cat-and-mouse game, threats evovle vendors update
- Developers should ensure devices do not expose to potential harm, but adding cost for secure will cause product uncompetitve
- Law enforcement can influence vendors to develop more security products (just like pollution issues)


#### Unique Security Challenges

- Design/Develop of IoT devices is new, existing tools/methods/strategies associated with IoT security may need to reconsider
- Homogeneity of devices, vulnerable of single device impact many
- Need longer term support but difficult/impossible to upgrade
- User is no real visible to internal of IoT devices, mallicious/surveillance actions can hide underneath
- Anti-tamper design to ensure physical security


#### IoT Security Questions

1. Good Design Practices
 - Set of best practices should use?
 - Lesson learned from IoT security to improve in future?
 - training and education on dev/engineers for more secure design?
2. Cost vs Security Trade-Off
 - cost-benifit analysisi decisions?
 - accurately evaluate security risk?
 - motivate to let vendors to accept cost on security, take responsibility on security decisions?
 - incompatibilities between funtionality and security?
3. Standards
 - Effectively evaluate standard of secure?
 - Effectively identify security of device?
 - Ensure best security practices?
4. Data Confidentiality, Auth, Access Ctrl
 - Which encrytion/auth should use on different IoT devices?
 - Predictable issue on mass scale cryptography?
 - Cryto Key life cycle?
 - Secure and simple enough for typical users?
5. Field-Upgradeability
 - Should device to be upgradable?
 - Should have UI for user to manage?
6. Share Responsibility
 - IoT security be encouraged across stakeholders?
7. Regulation
 - penaty for selling products with security flaws?
 - cross border law protections?
 - Regulations keep updated according to evolving of IoT?
 - Regulations balance against permission-less innovation, internet and expression freedom
8. Device life cycle
 - Right way to take for outdated devices?
 - Should IoT devices should disable after end of life?
 - Should force to disable old/outdated devices? Whose responsiblity to replace it?

### Privacy Considerations (*trust, speak, connect, choose*)

#### IoT Privacy Background

- Correct data handling: respect a person expectations of privacy and fair use of their data
- Privacy considered when people and data collector have different privacy expectations
- Single type of a user's data may be harmless, but combining different types of data may extract much more detailed and private description of the person
- Devices may collect data (e.g. conversations) of user without knowing them
- Legal and regulatory challenges on data protection and privacy
- If users lost trust on Internet, then value of Internet may lost


#### Unique Privacy Aspects of IoT

- Traditional "notice and agree" unable to provide in IoT without UI
- Privacy interface (user can interact and control their data privacy) need to scalable to the size of IoT problem, while also practical from a user pov (good in both scalability and UX)
- Different exceptation of privacy in public vs private spaces
- Individual privacy preferences is unable distinguish if devices operate in situation while collecting data of multiple people at same time
- Big data which aggregated(collect and join) personal data may create the detailed profile of individual

#### IoT Privacy Question

- Unbalance relationships and interests between data source and data collector
- Data source unwelcome intrusion to private space without permission
- Data collector consider privacy data is a benificial source

1. Fairness in Data Collection and Use
 - Market relationship of data source and collector?
 - Fair and consistent rules for both in giving and using data?
2. Transparency, Expression and Enforement of Privacy Preferences
 - Privacy policy can be get and understand in IoT?
 - Alternative to the traditional "notice and accept"?
 - Effective model to express individual and multi-party privacy preference?
 - Can multi-party model be constructed?
 - Market for outsourcing management of privacy settings of users' preferences?
 - Proxy for express and enforce a user preference across devices?
3. Wide-Ranging Privacy Expectations
 - Different culture have different privacy expectation
 - Design a crossboarder privacy protection model?
 - IoT devices adapted the range of privacy expectations of users and crossboarder law?
4. Privacy by Design
 - Encourage manufacturers design product under core value of privacy?
 - Include consumer privacy considerations in every product design phase?
 - Choose between product features and privacy?
 - Long-term customer trust build vs competitive market desired for design simplicity and speed to market?
 - Devices default configure to most conservative(保守) data collection mode?
5. Identification
 - Protect data that not to be personal data (possible to be re-identified/combined to become personal data)?

### Interoperability[互動性]/Protocol Issues (*connect, speak, share, innovate*)

#### IoT Interoperability/Protocol Background

- Most basic core value
- Cornerstone of open internet
- Any devices able to connect to any other device without artificially applied if protocol are standardized
- Well designed protocol provide lower entry barrier, increase the overall economic value to market

#### Key Considerations and Challenges in IoT Interoperability/ Protocol

- Proprietary Ecosystems and Consumer Choice
 - Create non-interoperal ecosystem lock-in users to use their product line
 - Some manufactures see closed ecosystem approach can be adapted quickly, which is benifit to users
 - Interoperal also provide a person to choose alternative service provider for data collecting and processing
- Technical and Cost Constraints
 - Interoperability may cause reduce of performance or increase of cost (in implement and test standards)
- Schedule Risk
 - Interoperability design takes times, makes manufacturer unable to quick to market
- Technical Risk
 - Using interoperabel technical design represent a lower technical risk
 - Larger pools of technical talent/tools/cheaper tools
- Devices Behaving Badly
 - Lack of standards and document, developers design products in bad way, and no effective machanism to fix problems
- Legacy Systems
 - Interperability is a challenge for IoT devices need to interface with old system already deployed (such as industry network)
- Configuration
 - Users will face challenge in managing large numbers of devices
 - Standardization of configuration tools needed to quicky modify settings of many devices
- Proliferation of Standards Efforts
 - Everyone wants to dominate standard, cause overlap or conflict standard
 - Increase the cost of standards development, fragmentation of products, services and industry

#### Interoperability and Protocol Questions

1. Generic and widely available standards
 - Sufficiently protocol for different IoT use cases?
 - Impact users' ability to connect, speak, share, innovate?
2. 
3. Education about standards
 - Best way to engage user and developer about problems of badly behaving  IoT devices and lack of standards implementation?
 - Best practices/implementation models which suitable in broad range of IoT application
4. Cloud-enabled services
 - Standard extends that able to follow up the extends of impact on resources (bandwidth consumption)
 - challenges related to Cloud-to-cloud interoperability?


### Regulatory, Legal, and Rights Issues

#### Data Protections and Crossborder Data Flows

#### IoT Data Discrimination

#### IoT Devices as Aids to Law Enforcement and Public Safety

#### IoT Device Liability

#### Proliferation of IoT Devices Used in Legal Actions


### Emerging Economy and Development Issues

#### Ensuring IoT Opportunities are Global

#### Economic and Development Opportunities

#### IoT Emerging Economy and Development Questions

1. Infrastructure Resources
2. Investment
3. Technical and Industry Development
4. Policy and Regulatory Coordination

