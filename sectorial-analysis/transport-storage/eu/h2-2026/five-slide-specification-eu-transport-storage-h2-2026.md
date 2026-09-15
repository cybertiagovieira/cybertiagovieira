# Five-Slide Analytical Presentation Specification

**Topic:** EU Transport & Storage cyber-risk analysis  
**Evidence cut-off:** 15 September 2026  
**Design system:** white background, dark text, emerald green `#00915E` accent  
**Audience:** 1LoD operational management and Risk Committee

## Design and traceability rules

The deck uses a white field, charcoal text and emerald-green accents. Every chart value, scenario element and case statement is traceable to the evidence pack claim ledger. A small source line appears on each slide. Sources are shown as register IDs and corresponding short publisher labels, with full links in the evidence pack. No slide treats an EU-wide maturity assessment, a threat-intelligence target list or an exercise scenario as entity-specific evidence.

## Slide 1 - Key Threats & Top 5 Cyber Attacks

**Key message:** Transport exposure concentrates in common digital services, customer-facing availability, freight identity fraud, state-linked intermodal targeting and supplier access across OT and IT.

**Visual layout:** A left-side numbered list of five threats with a structured right-side matrix. Each row maps technical observation to operational vulnerability and systemic or concentration implication.

| Attack pattern | Evidence classification | Operational vulnerability | Systemic or concentration implication | Evidence IDs |
|---|---|---|---|---|
| Shared passenger-processing disruption | Observed | Common airport check-in and boarding dependency | Disruption can transmit across provider users and airport-community processes | C08 |
| DDoS against rail channels | Observed | Public information and booking dependency | Customer communication and channel congestion risk | C09 |
| Freight phishing and cargo diversion | Source-reported observed activity | Identity and transaction-validation weakness | Cross-border fraud can propagate through freight platforms | C10 |
| State-linked multi-vector targeting | Government-assessed targeting | Exposure across identities, public services and relationships | Cross-modal pathway through logistics and technology dependencies | C11 |
| Supplier access and OT and IT interfaces | Assessed exposure | Incomplete mapping, third-party access and recovery testing | Correlated restoration difficulty across connected operations | C06 |

**Chart:** A Transport incident-composition bar chart from ENISA's curated corpus: air 58.4%, logistics 20.8%, other Transport categories 20.8%. Adjacent callout: DDoS accounts for 87.6% of recorded Transport incidents. The slide states the 01 July 2024 to 30 June 2025 period and curated-corpus limitation. [C07]

## Slide 2 - Financial Impact: Transport & Storage

**Key message:** Public evidence supports a pathway analysis, not an EU sector loss estimate.

**Visual layout:** A horizontal value-chain flow from service interruption to financial, regulatory and insurance pathways. Four vertically aligned columns show operational disruption, financial transmission, regulatory process and liquidity or risk-transfer uncertainty.

| Pathway | Evidence-led content | Evidence IDs |
|---|---|---|
| Service interruption | Lost or delayed revenue, manual-workaround cost, restoration and extraordinary operating expenditure are relevant pathways. | C12, C13 |
| Contractual transmission | Passenger, shipper, airport-community, supplier and counterparty relationships can transmit business interruption and claim exposure. | C14, C15 |
| Data and regulatory process | Data events may trigger GDPR assessment and notification. NIS2 reporting and supervisory interaction depend on scope, thresholds and national law. | C02, C16, C17 |
| Insurance and cash timing | Coverage, retention, exclusions, claims and recovery timing depend on policy and contract evidence. EIOPA identifies contingent interruption and silent-cover uncertainty. | C15 |

**Mandatory limitation statement:** “No current public EU Transport & Storage dataset links cyber events to final loss, claims, insurance recovery and liquidity. No sector loss total is presented.”

## Slide 3 - Financial Impact: Worst-Case Scenarios

**Key message:** Stress testing must target correlated disruption and cash timing rather than a single assumed cyber-loss figure.

**Visual layout:** Three horizontal scenario lanes. Each moves from trigger to operational effect to financial and regulatory pathway. A green boundary label states “Plausible stress pathway - not an observed outcome”.

| Scenario | Operational effect | Financial and regulatory pathway | Evidence IDs |
|---|---|---|---|
| Shared airport-service outage | Manual and alternative processing, flight cancellations and recovery coordination | Revenue timing, operating expenditure, airline and passenger-management impacts, contract and insurance assessment | C08, C12, C15 |
| Supplier-access or OT and IT interface compromise | Delayed containment, patching and restoration across multi-vendor operations | Recovery cost, customer-service impact, potential claims and incident-reporting assessment | C06, C15 |
| Coordinated rail and maritime disruption with data exposure | Cargo and rail disruption, ticketing degradation, potential personal-data assessment | Concurrent business interruption, restoration, data and claims processes, insurance and funding timing | C14, C15, C16 |

**Management data required:** common-provider map, maximum tolerable outage, recovery objective, manual capacity, daily cash forecast, contract terms and current insurance wording.

## Slide 4 - Case Study: Brussels Airport, Belgium: September 2025 disruption of Collins Aerospace passenger-processing services

**Key message:** A third-party passenger-processing outage caused cancellations, while manual and alternative processing preserved many flights. The public record does not disclose entry route, actor, data effect, incident cost or recovery assurance.

**Visual layout:** A horizontal timeline with four points: 20 to 28 September 2025 cancellations; manual and alternative processing; the majority of flights operating; accelerated replacement system rollout reported on 09 October 2025. A right-side panel separates observed facts from information not established.

| Observed | Not established by available public evidence | Evidence IDs |
|---|---|---|
| The affected provider supported airport check-in and boarding systems. | Entry route, actor identity, data access or removal, ransom demand, payment and full affected-airport list. | C08 |
| Flights were cancelled from 20 to 28 September 2025. | Incident-specific financial impact, total cancellation effect and supplier control assessment. | C08 |
| Brussels Airport reported alternative systems, airport-community action and accelerated rollout of a replacement check-in and boarding system. | Whether the replacement addressed the cause of compromise or residual exposure. | C08 |

**Management lesson:** dependency ownership, tested manual fallback, supplier incident communications and recovery decision rights are control objectives. The lesson is an analytical implication, not a conclusion on either organisation's controls.

## Slide 5 - Mitigation Strategies & Security Framework

**Key message:** Resilience requires legal-perimeter clarity, common-dependency control, identity and OT governance, tested recovery and integrated financial response.

**Visual layout:** A five-pillar control framework. Each pillar has a concise action, a linked evidence driver and a management control outcome.

| Pillar | Management action | Evidence driver | Control outcome |
|---|---|---|---|
| Legal and accountability mapping | Map NIS2, CER and aviation regime by legal entity, function, country and accountable owner. | C01 to C05 | Clear scope, incident-reporting route and management-body oversight |
| Common-dependency resilience | Map shared passenger, freight, booking, identity, cloud, remote-support and OT dependencies. Test alternatives and exit options. | C06, C08 | Reduced uncertainty around common-provider outage and recovery ownership |
| Identity and transaction integrity | Strengthen phishing resilience, privileged access, multi-factor authentication, freight-transaction validation and cargo-release controls. | C10, C11 | Reduced credential-led fraud and supplier-access exposure |
| OT and IT recovery governance | Maintain asset and dependency mapping. Segment operational systems. Exercise containment, manual operations and restoration with suppliers. | C06, C14 | Faster isolation and recovery across connected operating environments |
| Financial and incident integration | Pre-agree cash, customer, legal, insurance and notification workflows. Test recovery funding and conditional insurance assumptions. | C02, C12, C15, C16 | Credible response under concurrent operational, financial and regulatory pressure |

**Source note:** The framework is a 2LoD control synthesis. It is not a finding that any entity lacks a named control.

## Evidence references

All evidence IDs map to the claim ledger in the accompanying evidence pack, **EU Transport & Storage Cyber-Risk Analysis - Evidence Pack**.
