# EU Transport & Storage Cyber-Risk Analysis

**Report date:** 15 September 2026  
**Analysis period:** H2 2026 year to date  
**Evidence cut-off:** 15 September 2026  
**Geography:** European Union  
**Audience:** 1LoD operational management and Risk Committee  
**Prepared by:** Manus AI

## Executive assessment

**EU Transport & Storage presents a differentiated resilience exposure rather than a uniform sector position.** The legal perimeter varies by transport function, legal entity, size, Member State and national designation. NIS2 names specific air, rail, water and road entity types, while its Transport listing does not provide a general warehouse or logistics classification. The Commission's July 2026 referral action against four Member States demonstrates that formal transposition remained uneven during the reporting period. A group-wide control statement therefore cannot substitute for local legal-entity mapping. [1] [15]

**Shared digital services and connected operational ecosystems are the main concentration pathway.** Brussels Airport disclosed flight cancellations after a cyberattack affected its external passenger-processing provider. ENISA separately identifies older OT and IT integration, multi-party environments, third-party access, incomplete supply-chain visibility and uneven response testing as EU Transport exposure factors. The resulting 2LoD conclusion is that common supplier failure can create correlated operational disruption across airport, rail, maritime and logistics services even where each entity maintains its own cyber controls. [3] [7]

**The 2026 activity record is not limited to ransomware.** Deutsche Bahn reported DDoS disruption to public travel-information and booking channels. CERT-EU reported credential theft, fraud and cargo diversion in a logistics phishing campaign targeting Germany, France and Lithuania. A joint government advisory assesses sustained state-linked targeting of logistics and technology organisations connected with air, sea and rail. ENISA's curated 2024 to 2025 corpus records DDoS in 87.6% of recorded Transport incidents, with air transport representing 58.4% and logistics 20.8% of the Transport subset. The corpus is curated rather than comprehensive. [5] [8] [10]

**Financial exposure arises through multiple concurrent channels.** The public evidence does not support a current EU-wide loss estimate. It supports a pathway view: foregone or delayed revenue, manual-workaround expenditure, incident response and restoration, customer and counterparty claims, data-related requirements, insurance uncertainty and cash-timing pressure. DHL identifies supply-chain disruption, business loss and data-protection effects as business-model and value-chain risk. Maersk's historical global disclosure identifies lost revenue, IT restoration and extraordinary operating cost categories but is not a current EU benchmark. [4] [18]

## Structured research data

| Analytical domain | Evidence-led observation | 2LoD risk translation | Decision boundary |
|---|---|---|---|
| Regulatory perimeter | NIS2 covers named transport entity types, while storage and logistics require functional and national assessment. Formal transposition was still uneven in July 2026. [1] [15] | **Operational vulnerability:** inconsistent scope mapping can leave legal entities, reporting routes and accountability unclear during an incident. | Do not assume sector label establishes scope or a specific supervisor. |
| Maturity and resilience | ENISA places rail and maritime in its risk zone and identifies uneven OT coverage, third-party access and response testing. [3] | **Systemic or concentration risk:** connected entities may share slow containment and recovery constraints. | The finding is EU-wide and does not assess a named operator. |
| Shared services | Brussels Airport disclosed supplier-linked passenger-processing disruption and flight cancellations. [7] | **Operational vulnerability:** common check-in, boarding, booking, cargo or dispatch services can become a single service-recovery dependency. | Public data do not disclose the entry route, full affected population or financial outcome. |
| Customer-facing availability | Deutsche Bahn reported DDoS disruption to customer information and booking tools. [5] | **Material financial and regulatory impact:** public digital-channel outages can create service, customer-care, contractual and reputational pressures without evidence of OT disruption. | No actor or train-control impact is established in the cited record. |
| Freight identity fraud | CERT-EU reported credential theft, fraud and cargo diversion in logistics campaigns. [5] | **Operational vulnerability:** weak identity protection and transaction validation can expose freight workflows to diversion and fraud. | No named affected organisation is disclosed. |
| State-linked intent | Government agencies assess Russian GRU targeting of Western logistics and technology entities connected with air, sea and rail. [10] | **Geopolitical or macro-financial threat:** transport networks supporting allied logistics face persistent multi-vector targeting that can extend through business relationships. | Targeting does not establish compromise or operational impact at a named EU operator. |
| Financial pathways | DHL describes supply-chain disruption and business loss risk. EIOPA identifies business interruption, data reconstruction, data liability, contingent interruption and wording uncertainty. [4] [14] | **Material financial and regulatory impact:** recovery funding, claims and policy response may not align in timing. | Insurance collection, claim amount and liquidity effect require policy, contract and cash data. |

## Threat assessment

### Shared passenger-processing provider disruption

**Observed activity.** Brussels Airport disclosed that the cyberattack affected Collins Aerospace, its external provider for check-in and boarding systems, and led to flight cancellations from 20 to 28 September 2025. The airport reported alternative processing, stated that the vast majority of flights continued to operate, and accelerated deployment of a replacement check-in and boarding system. [7]

**Operational vulnerability.** Passenger-processing services are embedded in airport and airline workflows. Their unavailability can move processing to manual or alternative channels, reduce throughput and expose airport-community coordination dependencies.

**Systemic or concentration risk.** A common provider can transmit disruption to multiple users or locations. The Brussels evidence establishes a supplier-linked disruption at one EU hub. It does not establish the compromise point, customer-wide impact, or a full network event.

**Material financial and regulatory impact.** The pathway includes cancelled or delayed services, recovery expenditure, customer handling and possible contractual exposure. The public record provides no incident-specific financial loss figure.

### DDoS against rail customer channels

**Observed activity.** CERT-EU reported that Deutsche Bahn was targeted with DDoS activity that disrupted travel-information and booking tools on its website and DB Navigator application. The cited record concerns public digital services and does not show disruption to train control or signalling. [5]

**Operational vulnerability.** Passenger information and booking platforms become availability dependencies when alternative communications, ticketing and customer-service workflows are not designed and tested for sustained degradation.

**Systemic or concentration risk.** A customer-channel outage can create localised demand, contact-centre and station-management congestion. It can also impair the ability to communicate service change across the rail network.

**Material financial and regulatory impact.** The initial cost pathway is service management and customer remediation. Wider financial impact depends on duration, passenger-rights exposure, contractual terms and actual service disruption, none of which is quantified in the cited record.

### Freight credential theft and cargo diversion

**Observed activity.** CERT-EU reported a phishing campaign targeting freight and logistics organisations in Germany, France and Lithuania. It reported credential theft from industry platforms, fraud and cargo diversion. [5]

**Operational vulnerability.** Identity controls, supplier onboarding, transaction confirmation and exception management are control points for freight workflows. A phishing event can create an operational loss mechanism without needing direct disruption of core operational technology.

**Systemic or concentration risk.** Common industry platforms, forwarder relationships and cross-border freight workflows can transmit fraud exposure beyond a single legal entity.

**Material financial and regulatory impact.** Exposure can arise through cargo misdirection, customer dispute, recovery cost and data-related obligations. The evidence has no named victim, financial outcome or full campaign data, so no loss estimate is presented.

### State-linked targeting of intermodal logistics

**Observed activity and government assessment.** A joint government advisory assesses that Russian GRU Unit 26165 targeted logistics and technology entities associated with air, sea and rail. Listed methods include credential guessing, spearphishing, public-facing infrastructure exploitation and specified software vulnerabilities. EU target countries cited include France, Germany, Greece, Italy, the Netherlands, Poland and others. [10] [11]

**Geopolitical or macro-financial threat.** The activity aligns with disruption and intelligence objectives against Western logistics and related technology. It creates a cross-border risk pathway where transport providers, technology suppliers and business partners have linked roles.

**Decision boundary.** The advisory does not name transport victims or establish successful compromise and operational outcome for each target. Threat intelligence must not be converted into an entity-specific loss expectation without exposure evidence.

### Supplier access and OT and IT interface exposure

**Assessed exposure.** ENISA identifies legacy OT and IT integration, multi-vendor estates, incomplete mapping, third-party access, limited supply-chain visibility and uneven response testing as Transport sector weaknesses. It reports aviation as the most mature transport mode, with rail and maritime in its risk zone. [3]

**Operational vulnerability.** Incomplete visibility across OT, IT and supplier access can delay the isolation, patching and restoration decisions required after a compromise.

**Systemic or concentration risk.** Common remote-access suppliers and connected operational systems can concentrate recovery risk. The conclusion is an EU-wide exposure assessment, not a finding on a named operator.

## Financial impact analysis

### Evidence-led financial channels

The available public record cannot support an EU Transport & Storage cyber-loss estimate. It establishes a structured set of potential impact channels. DHL identifies supply-chain disruption, business loss and data-protection effects as current business-model and value-chain risk. EIOPA's methodology identifies business interruption, data reconstruction, data liability, contingent business interruption, silent-cover uncertainty and litigation as relevant insurance channels. [4] [14]

Maersk's historical 2017 disclosure reported a global loss in the order of USD 250 million to USD 300 million, including lost revenue, IT restoration and extraordinary operational costs. This is a completed issuer case, used only to illustrate cost categories. Its global scope, age and incident-specific facts preclude use as a current EU benchmark or scenario estimate. [18]

| Impact channel | Evidence basis | Risk-committee interpretation | Entity data needed |
|---|---|---|---|
| Business interruption | DHL risk disclosure; EIOPA scenario methodology; historical Maersk cost categories [4] [14] [18] | Service interruption can suppress or defer revenue while recovery spend rises. | Service volumes, margin, maximum tolerable outage, recovery objective, backlog profile |
| Manual and alternative operations | Brussels Airport continuity disclosure [7] | Workarounds can preserve portions of service but may reduce throughput and raise operating cost. | Tested manual capacity, staffing, supplier obligations, fall-back duration |
| Customer and counterparty claims | EIOPA contingent business interruption methodology [14] | The exposure may transmit through freight, passenger, airport-community, shipper and supplier contracts. | Contract terms, indemnities, service credits, customer concentration |
| Data-related consequences | DHL disclosure; GDPR legal framework [4] [17] | Data events can require assessment, notification and remediation depending on facts and legal thresholds. | Data inventory, personal-data exposure, controller roles, jurisdictional advice |
| Insurance and liquidity timing | EIOPA methodology [14] | Recovery, claim notification and insurer response may not match the timing of cash expenditure. | Policy wording, limits, exclusions, deductibles, insurer and reinsurer data, cash forecast |
| Regulatory process | NIS2 and CER legal frameworks [15] [16] | Incident reporting and supervisory interaction can run alongside operational response where scope and thresholds are met. | Entity scope, country law, incident classification, reporting playbooks and accountable roles |

### Plausible stress scenarios

**Scenario 1 - Shared airport-service outage.** A compromise disables a common passenger-processing service used across several airports. Check-in and boarding move to manual or alternative methods. Airlines cancel or reschedule flights while service is restored. This pathway is grounded in the Brussels Airport event. Simultaneous multi-airport effect is a plausible dependency scenario, not an observed full-impact account. [7]

**Scenario 2 - Supplier-access or OT and IT interface compromise.** An attacker gains access through a supplier relationship or integrated operational and information-technology interface. Fragmented mapping and multi-vendor dependencies delay containment, patching and restoration. This is consistent with ENISA's assessed Transport exposure. It is not a prediction for a named entity. [3]

**Scenario 3 - Coordinated rail and maritime disruption with data exposure.** Port logistics and navigation disruption impedes cargo movement while rail interference disrupts cross-border services and ransomware affects ticketing or transport-authority systems. Passenger or emergency information may also be exposed. These elements derive from Cyber Europe 2026 and are a stress pathway only. They are simulated effects, not observed incident evidence. [2]

## Regulatory and resilience implications

NIS2 requires management-body approval and oversight of cyber-risk management measures, training and appropriate, proportionate measures for in-scope entities. Its prescribed areas include incident handling, continuity and recovery, supply-chain security, vulnerability handling, effectiveness assessment, access and asset management. Significant-incident reporting is staged at 24 hours, 72 hours and one month, subject to scope and incident thresholds. [15]

CER adds an all-hazards resilience process for nationally identified entities. Its 2026 national milestones do not evidence which Member States completed each action or which entities were notified. For a notified entity, Chapter III timing is conditional on notification. The framework requires a risk assessment considering cross-sector, cross-border and dependency factors, together with proportionate prevention, protection, response, recovery and continuity measures. [9] [16]

Aviation organisations within the specified scope of Commission Implementing Regulation (EU) 2023/203 are subject to a distinct EU information-security framework, with general application from 22 February 2026. This regime should be assessed alongside, not assumed equivalent to, NIS2 obligations for a particular organisation. [13]

## Risk-committee decisions and challenge points

**Legal perimeter.** Require management to map each legal entity, transport function, Member State, size threshold, NIS2 category, CER identification status, relevant aviation regime and competent authority. The output must distinguish confirmed scope from pending legal review.

**Common-dependency resilience.** Require a dependency map spanning passenger processing, ticketing, booking, freight platforms, cargo community systems, operational technology, identity providers, remote support and cloud services. The map must identify single points of failure, common providers, manual fallback, recovery ownership and tested exit options.

**Scenario discipline.** Require three stress tests: shared passenger-processing outage, supplier-access or OT and IT interface compromise, and cross-border rail and maritime disruption. Each test must quantify its own assumed duration, service impact, cash timing and management actions using internal data. External evidence in this report must not be used as an entity loss calibration.

**Identity and fraud controls.** Require validation that freight-platform authentication, privileged-access management, transaction confirmation, exception handling and cargo-release procedures address credential compromise and social-engineering fraud.

**Financial and insurance integration.** Require Finance, Treasury, Legal, Operations and Insurance to map cost ownership, customer and supplier contractual exposure, insurance notice, exclusions, deductibles, limits, recovery assumptions and funding needs. Insurance should be treated as a conditional risk-transfer mechanism, not an assured source of immediate liquidity.

## Limitations

The evidence base contains no comprehensive public EU dataset linking cyber events to final operational loss, recovery duration, customer claims, insurance proceeds, liquidity effects and legal outcome. ENISA's incident corpus is curated, and NIS360 is a sector assessment rather than a supervisory result for any particular company. Public sources do not provide a complete cut-off-date inventory of Member-State NIS2 measures, CER entity lists or competent-authority allocation.

The current case study does not disclose a forensic root cause, data effect, actor identity, complete affected-entity population, incident-specific cost or recovery assurance. Transport and Storage is not a single legal classification. Storage, warehousing and logistics require entity-level function and national-law assessment. Any quantified risk, capital, liquidity or insurance conclusion requires internal operational, contractual, financial and policy data.

## References

[1]: https://digital-strategy.ec.europa.eu/en/news/commission-refers-ireland-spain-france-and-netherlands-court-justice-failing-transpose-rules "Commission refers Ireland, Spain, France and the Netherlands to the Court of Justice for failing to transpose the rules on cybersecurity"
[2]: https://www.enisa.europa.eu/news/cyber-europe-2026-all-eyes-on-the-eus-collective-response-and-resilience "Cyber Europe 2026: All eyes on the EU's collective response and resilience"
[3]: https://www.enisa.europa.eu/sites/default/files/2026-05/ENISA%20NIS360%202026.pdf "ENISA NIS360 2026"
[4]: https://reporting-hub.group.dhl.com/2025-fy/en/combined-management-report/group-sustainability-statement/entity-specific-disclosure-cybersecurity/ "Entity-specific disclosure: Cybersecurity, 2025 Annual Report"
[5]: https://cert.europa.eu/publications/threat-intelligence/cb26-03/ "Cyber Brief 26-03 - February 2026"
[6]: https://digital-strategy.ec.europa.eu/en/library/proposal-directive-regards-simplification-measures-and-alignment-cybersecurity-act "Proposal for a Directive as regards simplification measures and alignment with the Cybersecurity Act, COM(2026) 13"
[7]: https://pressroom.brusselsairport.be/en-results-september "2.3 million passengers at Brussels Airport in September, an increase of 1%"
[8]: https://www.enisa.europa.eu/publications/enisa-threat-landscape-2025 "ENISA Threat Landscape 2025"
[9]: https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=OJ:C_202504990 "C/2025/4990: Commission Guidelines and reporting template under CER Articles 5, 6 and 7"
[10]: https://www.cisa.gov/news-events/cybersecurity-advisories/aa25-141a "Russian GRU Targeting Western Logistics Entities and Technology Companies"
[11]: https://www.ncsc.gov.uk/news/uk-partners-expose-russian-intelligence-campaign "UK and allies expose Russian intelligence campaign targeting western logistics and technology organisations"
[12]: https://eur-lex.europa.eu/eli/reg_impl/2024/2690/oj/eng "Commission Implementing Regulation (EU) 2024/2690"
[13]: https://eur-lex.europa.eu/eli/reg_impl/2023/203/oj/eng "Commission Implementing Regulation (EU) 2023/203, aviation information security"
[14]: https://www.eiopa.europa.eu/system/files/2023-07/Methodological%20principles%20of%20insurance%20stress%20testing%20-%20Cyber%20component.pdf "Methodological principles of insurance stress testing - Cyber component"
[15]: https://eur-lex.europa.eu/eli/dir/2022/2555/oj/eng "Directive (EU) 2022/2555, NIS2"
[16]: https://eur-lex.europa.eu/eli/dir/2022/2557/oj/eng "Directive (EU) 2022/2557, CER"
[17]: https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:02016R0679-20160504 "Regulation (EU) 2016/679, General Data Protection Regulation, consolidated text"
[18]: https://investor.maersk.com/static-files/d533735a-5df7-423c-8611-d4a2c3bf31b0 "2017 Risk management, A.P. Moller - Maersk Annual Report 2017"
