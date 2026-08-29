# Flock Safety & Automated License Plate Readers: A Deep-Dive Guide

A community-focused guide to understanding automated license plate reader (ALPR) technology, Flock Safety camera systems, data collection, searches, sharing, retention, oversight, cybersecurity, and the questions communities should ask.

---

# What Is an Automated License Plate Reader?

An automated license plate reader, commonly called an ALPR or LPR, combines cameras with software capable of identifying license plates and vehicle characteristics.

ALPR systems can be mounted in locations such as:

- Roads and intersections
- Parking areas
- Neighborhood entrances
- Commercial properties
- Government property
- Police vehicles
- Fixed poles or other structures

Unlike a traditional security camera that primarily records video for later viewing, an ALPR system can transform observations of vehicles into searchable information.

---

# What Can an ALPR Record?

The exact information depends on the system.

Flock Safety states that its ALPR technology can collect information including:

- License plate images
- License plate text
- Vehicle characteristics
- Date and time
- Camera location

Vehicle characteristics may allow searches involving attributes such as vehicle type or other visible characteristics.

Flock states that its ALPR system does not perform facial recognition or directly collect information such as a driver's name, home address, or Social Security number.

However, license plate observations can become more revealing when connected with other legally available databases or records.

---

# Why Location and Time Matter

A license plate by itself identifies a vehicle registration.

An ALPR observation adds additional context:

**A particular vehicle was observed near a particular camera at a particular time.**

One observation may reveal relatively little.

Repeated observations can potentially reveal patterns involving:

- Routes
- Frequently visited locations
- Travel patterns
- Times of movement
- Associations between locations

This is why ALPR privacy discussions frequently focus not only on the license plate itself, but also on retention, searching, sharing, and aggregation of observations.

---

# How ALPR Searching Works

ALPR systems can allow authorized users to search previously collected observations.

Depending on the system and available features, investigators may search using information such as:

- Complete license plate
- Partial license plate
- Vehicle characteristics
- Time period
- Geographic area

The usefulness and privacy implications of an ALPR system therefore depend on more than the number of cameras.

They also depend on how the resulting database can be searched.

---

# Real-Time Alerts and Hotlists

ALPR systems may compare observed license plates against lists of vehicles of interest.

These are commonly called:

- Hotlists
- Watchlists
- Alert lists

Examples might include vehicles associated with:

- Stolen vehicle reports
- Missing-person investigations
- Wanted persons
- Other authorized investigative purposes

When a camera detects a plate appearing on a configured list, the system may generate an alert.

An automated alert should not automatically be treated as proof of criminal activity.

Policies may require users to verify information before enforcement action is taken.

---

# Historical Searches

ALPR systems can also support retrospective investigation.

Instead of receiving an alert when a vehicle passes a camera, an authorized user may search previously collected observations.

For example, an investigator working on an incident may search for vehicles observed within a relevant area or time period.

Historical searching makes **data retention** especially important.

If observations are retained longer, a larger historical database may be available for searching.

---

# Data Retention

Data retention means how long ALPR observations remain stored.

Retention policies can vary by:

- Vendor
- Agency
- State law
- Local policy
- Contract
- System configuration

Flock historically used a 30-day default retention period for many ALPR deployments.

In August 2026, Flock announced that it was moving toward a recommended/default seven-day retention period while introducing mechanisms that allow specific information to be preserved when necessary for active investigations.

Because policies can change, residents should verify the current retention period for the specific system operating in their community.

---

# Why Retention Matters

Consider two systems.

### System A

Vehicle observations are deleted after a short period.

### System B

Vehicle observations remain searchable for months.

Even if both systems use identical cameras, System B creates a much larger historical database.

Questions communities should ask include:

- What is the retention period?
- Who selected that period?
- Can administrators change it?
- Can individual observations be preserved longer?
- What legal authority governs preservation?
- Are backups also deleted?
- Does contract termination result in deletion?

---

# Data Sharing

One of the most important questions involving ALPR systems is:

**Who can search the information?**

A system operated by one local agency may potentially participate in information-sharing arrangements with other authorized organizations.

Sharing rules can vary significantly.

Questions to investigate include:

- Which organizations receive access?
- Which organizations provide access in return?
- Is sharing automatic or individually approved?
- Can administrators restrict sharing?
- Can out-of-state agencies search the system?
- Can federal agencies obtain access?
- Are searches from outside agencies visible in audit logs?
- Can sharing permissions be changed without public approval?

Do not assume that the agency operating the physical camera is necessarily the only organization capable of searching available information.

---

# Local Control Matters

ALPR deployments are not necessarily configured identically.

Different agencies can have different:

- Retention periods
- Sharing arrangements
- Search requirements
- Hotlists
- User permissions
- Audit practices
- Policies
- Contracts

This means statements about one city's ALPR program should not automatically be applied to another city.

Research the actual policies and configuration governing your community.

---

# Audit Logs

Audit logs can be an important accountability tool.

A search log may document information such as:

- Who performed a search
- When the search occurred
- What was searched
- The stated reason for the search
- Associated case information

Other administrative records may document:

- Changes to users
- Changes to sharing settings
- Changes to hotlists
- Camera configuration
- System settings

The exact information available depends on the system and agency.

---

# Why Audit Logs Matter

Consider an agency policy stating:

> ALPR searches may only be conducted for legitimate law-enforcement purposes.

That rule is more meaningful if the organization can determine:

- Who searched the database
- What they searched
- Why they searched
- When they searched
- Whether the search complied with policy

Without meaningful auditing and review, improper use can be more difficult to detect.

---

# Ask About Auditing

Useful questions include:

- Are all searches logged?
- Is a case number required?
- Must users provide a reason?
- How long are audit logs retained?
- Who reviews the logs?
- How frequently are audits performed?
- Are automated misuse-detection systems used?
- What happens when suspicious activity is identified?
- Have users ever been disciplined for improper searches?
- Are audit results reported publicly?

---

# Cybersecurity of ALPR Systems

ALPR systems create databases containing potentially sensitive information.

That makes cybersecurity important.

Security controls may include:

- Multi-factor authentication
- Role-based access
- Encryption
- Logging
- Monitoring
- Security updates
- Incident response
- Account management
- Network security
- Vulnerability management

Communities should ask vendors and agencies how collected information is protected from:

- Unauthorized access
- Account compromise
- Insider misuse
- Data breaches
- Improper sharing
- Stolen credentials

---

# Ask About Authentication

Questions include:

- Is multi-factor authentication mandatory?
- Are accounts assigned to individual users?
- Are shared accounts prohibited?
- Are inactive accounts automatically disabled?
- How quickly is access removed when an employee leaves?
- Are administrators given stronger authentication requirements?

Individual accounts make auditing more meaningful because activity can be associated with a specific authorized user.

---

# Search Justification

An accountability system can require users to provide a reason before conducting a search.

Possible controls include:

- Case number
- Incident number
- Call-for-service number
- Search justification
- Supervisor approval for certain searches

Communities should ask whether searches can be performed without a documented investigative purpose.

---

# Accuracy and False Matches

ALPR systems are automated technologies and should not be assumed to be perfect.

Potential problems may involve:

- Incorrectly read characters
- Obstructed plates
- Temporary plates
- Poor visibility
- Similar plate combinations
- Outdated hotlist information
- Incorrect database information

A technology-generated match should therefore be treated as information requiring appropriate verification rather than automatic proof that a person committed an offense.

---

# Human Verification

Human review can provide an important safeguard.

Before significant action is taken based on an automated alert, an authorized person may need to verify information such as:

- Whether the plate was read correctly
- Whether the vehicle matches the relevant description
- Whether the hotlist information remains current
- Whether the alert applies to the correct jurisdiction or investigation

Ask whether your local policy requires human verification.

---

# ALPRs and Private Property

ALPR technology is not limited to government agencies.

Systems may also be used by:

- Homeowners associations
- Apartment communities
- Businesses
- Shopping centers
- Schools
- Universities
- Religious institutions
- Private security organizations

Private deployments can raise different questions involving:

- Ownership
- Consent
- Data sharing
- Contracts
- Access
- Public-records laws
- Privacy policies

A privately owned camera may not necessarily be subject to the same transparency requirements as a government-operated camera.

---

# Public-Private Networks

When researching an ALPR deployment, determine whether the system involves:

- Government-owned cameras
- Privately owned cameras
- Shared camera networks
- Vendor-hosted databases
- Third-party integrations

Understanding who owns the physical camera is only one part of understanding the system.

Also determine who controls and can access the resulting information.

---

# Questions to Ask Your Local Government

Use this checklist when researching an ALPR program.

## Deployment

- [ ] How many ALPR cameras are currently deployed?
- [ ] Where are they located?
- [ ] Who owns each camera?
- [ ] Who operates them?
- [ ] When did deployment begin?
- [ ] Are additional cameras planned?

## Cost

- [ ] What did the system cost?
- [ ] What are the annual costs?
- [ ] What vendor contracts exist?
- [ ] When does the contract expire?
- [ ] Does the contract renew automatically?

## Collection

- [ ] What information is captured?
- [ ] Are vehicle characteristics analyzed?
- [ ] Are images retained?
- [ ] Are location and timestamps stored?

## Retention

- [ ] What is the retention period?
- [ ] Can records be preserved longer?
- [ ] Who can authorize preservation?
- [ ] What happens to data when the contract ends?

## Searching

- [ ] Who can search the system?
- [ ] Is a case number required?
- [ ] Must users provide a search reason?
- [ ] Can partial plates or vehicle characteristics be searched?

## Sharing

- [ ] Which agencies receive access?
- [ ] Is data shared outside the state?
- [ ] Can federal agencies access information?
- [ ] Can sharing settings be changed?
- [ ] Who approves new sharing relationships?

## Auditing

- [ ] Are all searches logged?
- [ ] How long are logs retained?
- [ ] Who audits them?
- [ ] How often are audits conducted?
- [ ] Are audit results available to the public?

## Security

- [ ] Is multi-factor authentication mandatory?
- [ ] Is stored information encrypted?
- [ ] Are individual user accounts required?
- [ ] What happens after suspicious account activity?
- [ ] What is the incident-response process for a breach?

## Effectiveness

- [ ] What goals were established before deployment?
- [ ] How is effectiveness measured?
- [ ] Are statistics publicly reported?
- [ ] Is effectiveness reviewed before contract renewal?

---

# Find Your Community's Transparency Portal

Some agencies using Flock publish public transparency portals.

Depending on the agency, a portal may provide information such as:

- Number of cameras
- Retention period
- Search statistics
- Hotlist information
- Policies
- Permitted uses
- Prohibited uses

A transparency portal is useful, but it should not necessarily be the only source used when researching a program.

Compare information from:

- The agency
- Government contracts
- Policies
- Meeting records
- Audit records
- Vendor documentation
- Independent research

---

# Read the Contract

A surveillance technology contract can answer questions that a public information page may not.

Look for:

- Contract start date
- Expiration date
- Renewal terms
- Number of devices
- Price
- Retention provisions
- Data ownership
- Data deletion
- Sharing
- Security requirements
- Vendor responsibilities
- Termination provisions

Contract expiration dates can be particularly important for communities seeking changes because renewal provides a natural opportunity for public review.

---

# Read the Policy

The contract explains the business relationship.

The agency policy explains how personnel are supposed to use the technology.

Look for rules involving:

- Authorized purposes
- Prohibited uses
- Search justification
- Hotlists
- Sharing
- Retention
- Auditing
- User access
- Training
- Discipline
- Supervisory review

Then compare the written policy with available audit information.

---

# Request the Records

Useful public-records requests may seek:

- Current ALPR contract
- Previous contracts
- ALPR policy
- Retention policy
- Sharing agreements
- List of participating agencies
- Search audit logs
- Administrative/event logs
- Training materials
- Procurement documents
- Invoices
- Vendor communications
- Policies governing hotlists
- Cybersecurity requirements
- Internal audits
- Reports measuring effectiveness

Public-records laws vary by jurisdiction, and some information may be exempt from disclosure.

---

# Separate Vendor Claims From Independent Verification

When researching surveillance technology, identify the source of each claim.

For example:

### Vendor

A vendor may explain:

- Product capabilities
- Security features
- Retention options
- Technical architecture

### Government Agency

An agency may explain:

- Local policies
- Number of cameras
- Authorized uses
- Local retention
- Local effectiveness statistics

### Independent Research

Journalists, researchers, civil-liberties organizations, academics, and auditors may investigate:

- Misuse
- Accuracy
- Sharing
- Policy compliance
- Security incidents
- Broader social impacts

Using multiple types of sources produces a more complete picture.

---

# Build a Local ALPR Profile

When researching your own community, try to complete this worksheet.

**Community:**  
[City / County]

**Agency:**  
[Agency Name]

**Vendor:**  
[Vendor Name]

**Number of cameras:**  
[Number]

**Program start date:**  
[Date]

**Annual cost:**  
[Cost]

**Contract expiration:**  
[Date]

**Retention period:**  
[Number of days]

**Search justification required:**  
[Yes / No / Unknown]

**MFA required:**  
[Yes / No / Unknown]

**Audit logs maintained:**  
[Yes / No / Unknown]

**Data shared with other agencies:**  
[Yes / No / Unknown]

**Out-of-state sharing:**  
[Yes / No / Unknown]

**Federal access:**  
[Policy / Unknown]

**Public transparency portal:**  
[Link]

**ALPR policy:**  
[Link]

**Contract:**  
[Link]

**Last public review:**  
[Date]

**Next contract renewal:**  
[Date]

**Questions still unanswered:**  
[List]

---

# What Can Communities Do With This Information?

Once residents understand their local ALPR program, they can make more specific requests.

Instead of:

> "I don't like these cameras."

an informed request might be:

> "The current contract expires in six months. Before renewal, I am requesting a public hearing addressing retention, interagency sharing, audit requirements, and whether the program has met its stated effectiveness goals."

Specific, documented advocacy can be more effective than generalized opposition.

---

# Possible Community Policy Requests

Residents may advocate for:

- Public approval before deployment
- Public approval before expansion
- Public review before contract renewal
- Short retention periods
- Restrictions on interagency sharing
- Restrictions on out-of-state sharing
- Search justification requirements
- Mandatory case numbers
- Human verification of alerts
- Mandatory multi-factor authentication
- Regular audits
- Public transparency reports
- Independent oversight
- Documented consequences for misuse
- Clear data-deletion requirements
- Removal or non-renewal when residents determine the technology is not appropriate for their community

Different communities may reach different conclusions.

The purpose of transparency is to make those decisions informed.

---

# Key Principle

**Do not evaluate a surveillance system only by looking at the camera.**

Evaluate the entire system:

**Camera → Data → Database → Search → Sharing → Retention → Security → Auditing → Oversight**

The camera is only the beginning of the information lifecycle.

---

# Trusted & Further Resources

## Flock Safety

- [Flock Safety Trust Center — Data Privacy & Protection](https://www.flocksafety.com/trust/data-privacy)

Useful for understanding Flock's description of what its ALPR product collects, retention, access controls, encryption, audit logging, and customer-controlled sharing.

## American Civil Liberties Union

- [ACLU — How to Fight Deployment of Flock and Other Mass Surveillance License Plate Readers in Your Community](https://www.aclu.org/news/privacy-technology/tracking-alpr-cameras/how-to-fight-deployment-of-flock-and-other-mass-surveillance-license-plate-readers-in-your-community)

Provides community advocacy information concerning ALPR deployments, contracts, retention, sharing, and policy safeguards.

## Electronic Frontier Foundation

- [EFF — Automated License Plate Readers](https://sls.eff.org/technologies/automated-license-plate-readers-alprs)

Provides independent educational material about ALPR technology and surveillance policy.

## Have I Been Flocked?

- [Have I Been Flocked — Audit Log Guide](https://haveibeenflocked.com/about/audit-logs)

Provides community-oriented information about requesting and interpreting ALPR search logs, network-sharing information, event logs, and configuration records.

---

# Source Transparency

This guide intentionally uses information from different types of sources.

Vendor documentation is used to explain vendor-stated product functionality and safeguards.

Government sources can be used to understand specific local deployments and policies.

Independent civil-liberties organizations, researchers, journalists, and public records can provide additional perspectives and scrutiny.

Readers should compare multiple sources when evaluating a surveillance program.

---

## Related Community Cyber Defense Resources

- [Surveillance Technology Awareness Guide](surveillance-technology-awareness-guide.md)
- [Community Action Toolkit](community-action-toolkit.md)

---

## Project

This resource is part of the [Community Cyber Defense Project](../README.md).

The project aims to make cybersecurity, privacy, digital safety, and surveillance technology easier for communities to understand and act on.

---

## Disclaimer

This guide provides general educational information about technology, privacy, cybersecurity, public oversight, and civic participation.

Laws, public-records requirements, agency policies, and surveillance regulations vary by jurisdiction.

This material is not legal advice.
