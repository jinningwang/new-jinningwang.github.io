---
layout: distill
title: Power Systems Wiki
date: 2024-12-11 10:00:00
description: Some terminologies for my own reference.
tags: [frequency, terminology, NERC, power-systems]
categories: blog
thumbnail:
featured: true
giscus_comments: true
bibliography: power-systems-wiki.bib
authors:
  - name: Jinning Wang
toc:
  - name: Power Grids
  - name: Generation
  - name: Transmission
  - name: Markets
  - name: Ancillary Services
  - name: Frequency
  - name: Reserve
  - name: Reliability, Security, and Stability
  - name: Transient Stability Index
  - name: Transmission Operations
  - name: Adaquecy
  - name: Operating Reliability
  - name: Flexibility
  - name: Resilience
  - name: Transmission Expansion and Interconnection
  - name: Uncertainty
  - name: Events
  - name: Horizon
  - name: Factors
  - name: Area, Zone, and Region
  - name: Data Formats
  - name: Vendors
  - name: Change Log
---

## Preface

Language itself is inherently ambiguous, and the terminologies in power systems are no exception.
Inspired by a talk titled "Definitions of Smart Grids a Decade Ago – What Has Changed?" that began on Power-Globe in 2024, I decided to excerpt terminologies from papers, standards, reports, and other traceable sources to build a wiki for my own reference.
For any suggestions or corrections, please email me at [jinninggm@gmail.com](jinninggm@gmail.com) with the subject line **Suggestion on Power Systems Wiki**. Thank you!

What this wiki does not intend to be:
- A primary reference. Most of the items are **excerpted** from the sources, and original sources should be referred to for more details.
- Comprehensive. Given my limited attentation, I may have missed some important terminologies. Please feel free to suggest any missing items.
- Authoritative. Unlike rigorouly proven theory in mathematics, I regard these terminologies as a common language for easy communication in engineering practice.
- Up-to-date. As the terminologies in power systems are often subject to interpretation and change, I cannot guarantee that the information here is the most recent and accurate.

Wiki-wide acronyms:

|---------|-------------------------------------------------|
| BES | Bulk Electric System |
| BPS | Bulk Power System |
| HVDC | High Voltage Direct Current |
| FACTS | Flexible Alternating Current Transmission System|
| IBR | Inverter-Based Resources |
| DER | Distributed Energy Resources |
| GSF | Generator Shift Factor |
| AGC | Automatic Generation Control |
| ACE | Area Control Error |
| FERC | Federal Energy Regulatory Commission |
| NERC | North American Electric Reliability Corporation |
| EPRI | Electric Power Research Institute |
| IEC | International Electrotechnical Commission |

## Power Grids

**_Balancing Authorities_** <d-cite key="nerc2024glossary"></d-cite> The responsible entity that integrates resource plans ahead of time, maintains Demand and resource balance within a Balancing Authority Area, and supports Interconnection frequency in real time.

**_Interconnection_** <d-cite key="nerc2024glossary"></d-cite> A geographic area in which the operation of BPS components is synchronized such that the failure of one or more of such components may adversely affect the ability of the operators of other components within the system to maintain Reliable Operation of the Facilities within their control. When capitalized, any one of the four major electric system networks in North America: Eastern, Western, ERCOT and Quebec.

**_Bulk-Power System (BPS)_** <d-cite key="nerc2024glossary"></d-cite> (A) facilities and control systems necessary for operating an interconnected electric energy transmission network (or any portion thereof); and (B) electric energy from generation facilities needed to maintain transmission system reliability.
The term **does not** include facilities used in the local distribution of electric energy. (Note that the terms “Bulk-Power System” or “Bulk Power System” shall have the same meaning.)

**_Bulk Electric System (BES)_** <d-cite key="nerc2024glossary"></d-cite> Unless modified by the lists shown below (Omitted here for simplicity; can be found in the source reference), all Transmission Elements operated at **100 kV or higher** and Real Power and Reactive Power resources connected at 100 kV or higher. This **does not** include facilities used in the local distribution of electric energy.

## Dispatch

**_Economic Dispatch_** <d-cite key="nerc2024glossary"></d-cite> The allocation of demand to individual generating units on line to effect the most economical production of electricity.

## Generation

**_Inverter-based resources (IBR)_** <d-cite key="nerc2023inverter"></d-cite> refer generally to BPS-connected facilities that have a power electronic interface between the ac grid and the source of electricity.

Following two Q&A are from the source reference.

**What types of IBR exist?**

Inverter-based resources include modern wind turbines, meaning type 3 and type 4 wind turbines, solar photovoltaic, and battery energy storage resources, as well as HVDC circuits and FACTs devices like static synchronous compensators and static volt-ampere reactive compensators.

**What is the difference between IBR and DER?**

- DER are generating resources located on the **distribution** system.
- DER **may or may not** use inverter technology to interface with the ac grid; however, they are distinctly different than BPS-connected inverter-based resources (connected to transmission and sub-transmission levels).

**_Distributed Energy Resources (DER)_** <d-cite key="ieee2018std1547"></d-cite> A source of electric power that is not directly connected to a bulk power system. DER includes both generators and energy storage technologies capable of exporting active power to an EPS. An interconnection system or a supplemental DER device that is necessary for compliance with this standard is part of a DER.
DER is equivalent to “distributed resources (DR)” as defined and used in IEEE Std 1547-2003

**_Generator Shift Factor (GSF)_** <d-cite key="nerc2024glossary"></d-cite> A factor to be applied to a generator’s expected change in output to determine the amount of flow contribution that change in output will impose on an identified transmission facility or Flowgate.

## Transmission

**_Flowgate_** <d-cite key="nerc2024glossary"></d-cite> 1. A portion of the Transmission system through which the Interchange Distribution Calculator calculates the power flow from Interchange Transactions. 2. A mathematical construct, comprised of one or more monitored transmission Facilities and optionally one or more contingency Facilities, used to analyze the impact of power flows upon the Bulk Electric System.

**_Interchange_** <d-cite key="nerc2024glossary"></d-cite> Energy transfers that cross Balancing Authority boundaries.

## Distribution

**_Distribution Provider_** <d-cite key="nerc2024glossary"></d-cite> Provides and operates the “wires” between the transmission system and the end-use customer. For those end-use customers who are served at transmission voltages, the Transmission Owner also serves as the Distribution Provider. Thus, theDistribution Provider is not defined by a specific voltage, but rather as performing the distribution function at any voltage.

**_Distribution_** <d-cite key="ferc2020public"></d-cite> For natural gas - the act of distributing gas from the city gate or plant to the customer. For electric - the act of distributing electric power using low voltage transmission lines that deliver power to retail customers.

## Markets

**_Market_** <d-cite key="ferc2020glossary"></d-cite> A venue where participants buy and sell products or services. Usually there is agreement of product description and some standard terms to enable determination of value and price.

**_Market power_** <d-cite key="ferc2020glossary"></d-cite> The ability of any market participant with a large market share to significantly control or affect price by withholding production from the market, limiting service availability, or reducing purchases.

**_Market structure_** <d-cite key="ferc2020glossary"></d-cite> The rules, mechanisms and processes, under which a market operates to form prices, provide benefits and introduce risks to participants, and ultimately end consumers. Structure could enhance or inhibit competition, create just and reasonable outcomes, provide economically efficient incentives, or introduce unintended consequences including adverse market outcomes.

**_Capacity markets_** <d-cite key="ferc2020glossary"></d-cite> A market for the trading of capacity credits (the ability to produce electricity in the market area during a defined period) usually between parties obligated to deliver electricity to customers and power plant owners.

**_Day-ahead markets_** <d-cite key="ferc2020glossary"></d-cite> Forward markets for electricity to be supplied the following day. This market closes with acceptance by the independent system operator, power exchange, or scheduling coordinator of the final day-ahead schedule. Day-ahead is not a term commonly used for natural gas (“next day” is more common).

**_Financial markets_** <d-cite key="ferc2020glossary"></d-cite> Markets where financially settled products (instruments) are traded (bought and sold). In commodity markets, it is markets where financially settled commodity derivatives are traded. Nymex is purely financial, where any residual delivery obligations on the futures contracts are matched and settled physically off-exchange by the matched parties. ICE trades both physically and financially settled products. Brokers also do both physical and financial transactions. Financial markets are also a term used for capital markets where stocks, bonds, T-Bills, foreign exchange and other financial instruments are traded.

**_Futures market_** <d-cite key="ferc2020glossary"></d-cite> A market in which contracts for future delivery of a commodity or a security are bought and sold. Nymex is the primary futures market for energy commodities in the United States.

**_Spot market_** <d-cite key="ferc2020glossary"></d-cite> The natural gas market for contractual commitments that are short term (usually a month or less) and that begin in the near future (often the next day, or within days). In electricity, spot markets are usually organized markets for day-ahead and real-time electricity run by an independent system operator or regional transmission organization.

**_Wholesale electricity markets_** <d-cite key="ferc2020glossary"></d-cite> The purchase and sale of electricity from **generators to resellers** (who sell to retail customers) along with the ancillary services needed to maintain reliability and power quality at the transmission level.

**_Financial transmission right_** <d-cite key="ferc2020glossary"></d-cite> A contract that entitles the holder to receive or pay compensation for transmission charges that arise when grid congestions cases price differences due to the redispatch of generators.

**_Marginal electric generating unit_** <d-cite key="ferc2020glossary"></d-cite> In organized wholesale markets, the price of the marginal source of electricity usually sets the price of the unit providing the next increment or decrement of energy, which price usually sets the price for all generation.

**_Bilateral transaction_** <d-cite key="ferc2020glossary"></d-cite> A direct contract between a seller and buyer outside of a centralized market or exchange (e.g. Nymex or an RTO/ISO). In energy markets, the buyer or seller usually finds his or her matching counter-party through a broker (e.g. voice brokers, ICE, etc.).

**_Zonal price_** <d-cite key="ferc2020glossary"></d-cite> A pricing mechanism for a **specific zone** within a **control area**.

**_NYISO-administered markets_** <d-cite key="nyiso2024clean"></d-cite> Each of the NYISO-administered markets are are interdependent, and facilitate a different piece of the reliability puzzle:

1. The **Capacity Market** secures commitments from supply resources to be available to meet seasonal resource adequacy requirements.
2. The **Energy Market** secures electricity production to meet demand in real-time.
3. The **Ancillary Market** secures flexibility services from suppliers to maintain balance in response to changing conditions on the electrical grid.

## Ancillary Services

**_Ancillary services_** <d-cite key="ferc2020glossary"></d-cite> Those services necessary to support the transmission of electric power from seller to purchaser, given the obligations of control areas and transmitting utilities within those control areas, to maintain reliable operations of the interconnected transmission system. Ancillary services supplied with generation include load following, reactive power-voltage regulation, system protective services, loss compensation service, system control, load dispatch services, and energy imbalance services.

More details about this can be found in Reference <d-cite key="nerc2011ancillary"></d-cite> - Appendix I: Regional Practices for Ancillary Services

## Frequency

**_Frequency Deviation_** <d-cite key="nerc2024glossary"></d-cite> A change in Interconnection frequency.

**_Frequency Regulation_** <d-cite key="nerc2024glossary"></d-cite> The ability of a Balancing Authority to help the Interconnection maintain Scheduled Frequency. This assistance can include both turbine governor response and Automatic Generation Control.

**_Frequency Response_** <d-cite key="nerc2024glossary"></d-cite> (Equipment) The ability of a system or elements of the system to react or respond to a change in system frequency. (System) The sum of the change in demand, plus the change in generation, divided by the change in frequency, expressed in megawatts per 0.1 Hertz (MW/0.1 Hz).

**_Frequency Response Measure_** <d-cite key="nerc2024glossary"></d-cite> The median of all the Frequency Response observations reported annually by Balancing Authorities or Frequency Response Sharing Groups for frequency events specified by the ERO. This will be calculated as MW/0.1Hz.

**_Area Control Error (ACE)_** <d-cite key="nerc2021balancing"></d-cite> Means the instantaneous difference between net actual and scheduled interchange, taking into account the effects of Frequency Bias including correction for meter error.

**_ACE_** <d-cite key="nerc2021balancing"></d-cite> The mismatch between demand and generation is represented via a real-time value called , estimated in MW.

**_Automatic Generation Control (AGC)_** <d-cite key="nerc2024glossary"></d-cite> Means equipment that automatically adjusts a Control Area’s generation from a central location to maintain its interchange schedule plus Frequency Bias.

**_AGC_** <d-cite key="ferc2020glossary"></d-cite> The automatic regulation of the power output of electric generators within a prescribed range in response to a change in system frequency, or tie-line loading, to maintain system frequency or scheduled interchange with other areas within predetermined limits.

**_Primary Frequency Response_** <d-cite key="nerc2024glossary"></d-cite> The immediate proportional increase or decrease in real power output provided by generating units/generating facilities and the natural real power dampening response provided by Load in response to system Frequency Deviations. This response is in the direction that stabilizes frequency.

**_Ramp Rate or Ramp_** <d-cite key="nerc2024glossary"></d-cite> (Schedule) The rate, expressed in megawatts per minute, at which the interchange schedule is attained during the ramp period. (Generator) The rate, expressed in megawatts per minute, that a generator changes its output.

**_Response Rate_** <d-cite key="nerc2024glossary"></d-cite> The Ramp Rate that a generating unit can achieve under normal operating conditions expressed in megawatts per minute (MW/Min).

**_Primary Control_** <d-cite key="nerc2021balancing"></d-cite> is more commonly known as **_Frequency Response_**. Frequency Response occurs within the first few seconds following a change in system frequency (disturbance) to stabilize the Interconnection.

**_Secondary Control_** <d-cite key="nerc2021balancing"></d-cite> typically includes the balancing services deployed in the “minutes” time frame. Some resources however, such as hydroelectric generation, can respond faster in many cases. This control is accomplished using the Balancing Authority’s control computer (terms most often associated with this are **“Load-Frequency Control”** or **“Automatic Generation Control”**) and the manual actions taken by the dispatcher to provide additional adjustments. Secondary Control also includes initial reserve deployment for disturbances.

In short, Secondary Control maintains the minute-to-minute balance throughout the day and is used to restore frequency to its scheduled value, usually 60 Hz, following a disturbance. Secondary Control is provided by both **Spinning** and **Non-Spinning Reserves**.

<div style="text-align: ;left;">
  <img src="/assets/img/pswiki/frequency_trend.png"
  alt="Typical Frequency Trend for the Loss of a Generating Resource"
  style="width: 700px; height: auto;">
  <p><em>
     Typical Frequency Trend for the Loss of a Generating Resource (from <d-cite key="nerc2021balancing"></d-cite>).
     Point A is defined as the pre-disturbance frequency;
     Point C or Nadir is the maximum deviation due to loss of resource;
     Point B is defined as the stabilizing frequency and;
     Point D is the time the contingent BA begins the recovery from the loss of resource.
  </em></p>
</div>

**_Tertiary Control_** <d-cite key="nerc2021balancing"></d-cite> encompasses actions taken to get resources in place to handle current and future contingencies. Reserve deployment and Reserve restoration following a disturbance are common types of Tertiary Control.

**_Control Performance Standard 1 (CPS1)_** <d-cite key="nerc2021balancing"></d-cite> is a **yearly** standard that measures impact on frequency error, with a 100 percent minimum allowable score. CPS1 assigns each Control Area a share of the responsibility for control of Interconnection frequency.

**_Control Performance Standard 2 (CPS2)_** <d-cite key="nerc2021balancing"></d-cite> is a **monthly** standard intended to limit unscheduled flows. The minimum allowable CPS2 score is 90 percent.

## Reserve

**_Spinning Reserve_** <d-cite key="nerc2024glossary"></d-cite> Unloaded generation that is synchronized and ready to serve additional demand.

**_Non-Spinning Reserve_** <d-cite key="nerc2024glossary"></d-cite> 1. That generating reserve **not connected** to the system but capable of serving demand **within a specified time**. 2. Interruptible load that can be removed from the system in a specified time.

**_Operating Reserve_** <d-cite key="nerc2024glossary"></d-cite> That capability above firm system demand required to provide for regulation, load forecasting error, equipment forced and scheduled outages and local area protection. It consists of spinning and non-spinning reserve.

**_Operating Reserve – Spinning_** <d-cite key="nerc2024glossary"></d-cite> The portion of Operating Reserve consisting of: • Generation synchronized to the system and fully available to serve load within the Disturbance Recovery Period following the contingency event; or • Load fully removable from the system within the Disturbance Recovery Period following the contingency event.

**_Operating Reserve – Supplemental_** <d-cite key="nerc2024glossary"></d-cite> The portion of Operating Reserve consisting of: • Generation (synchronized or capable of being synchronized to the system) that is fully available to serve load within the Disturbance Recovery Period following the contingency event; or • Load fully removable from the system within the Disturbance Recovery Period following the contingency event.

**_Regulating Reserve_** <d-cite key="nerc2024glossary"></d-cite> An amount of reserve responsive to Automatic Generation Control, which is sufficient to provide normal regulating margin.

**_Contingency Reserve_** <d-cite key="nerc2024glossary"></d-cite> The provision of capacity deployed by the Balancing Authority to meet the Disturbance Control Standard (DCS) and other NERC and Regional Reliability Organization contingency requirements.

<div style="text-align: ;left;">
  <img src="/assets/img/pswiki/operating_reserve.png" alt="Operating Reserves" style="width: 700px; height: auto;">
  <p><em>Operating Reserves (from <d-cite key="nerc2021reserve"></d-cite>) </em></p>
</div>

## Reliability, Security, and Stability

**_Stability Limit_** <d-cite key="nerc2024glossary"></d-cite> The maximum power flow possible through some particular point in the system while maintaining stability in the entire system or the part of the system to which the stability limit refers.

**_Interconnection Reliability Operating Limit_** <d-cite key="nerc2024glossary"></d-cite> A System Operating Limit that, if violated, could lead to instability, uncontrolled separation, or Cascading outages that adversely impact the reliability of the Bulk Electric System.

**_Interconnection Reliability Operating Limit Tv_** <d-cite key="nerc2024glossary"></d-cite> **The maximum time** that an Interconnection Reliability Operating Limit can be violated before the risk to the interconnection or other Reliability Coordinator Area(s) becomes greater than acceptable. Each Interconnection Reliability Operating Limit’s Tv shall be less than or equal to 30 minutes.

**_Reliability_** <d-cite key="kundur2004stability"></d-cite> of a power system refers to the probability of its satisfactory operation over the long run. It denotes the ability to supply adequate electric service on a nearly continuous basis, with few interruptions over an extended time period.

**_Security_** <d-cite key="kundur2004stability"></d-cite> of a power system refers to the degree of risk in its ability to survive imminent disturbances (contingencies) without interruption of customer service. It relates to robustness of the system to imminent disturbances and, hence, depends on the system operating condition as well as the contingent probability of disturbances.

**_Stability_** <d-cite key="nerc2024glossary"></d-cite> The ability of an electric system to maintain a state of equilibrium during normal and abnormal conditions or disturbances.

**_Stability_** <d-cite key="hatziargyriou2021stability"></d-cite> is the ability of an electric power system, for a given initial operating condition, to regain a state of operating equilibrium after being subjected to a physical disturbance, with most system variables bounded so that practically the entire system remains intact.

**_Stability_** <d-cite key="kundur2004stability"></d-cite> of a power system refers to the continuance of intact operation following a disturbance. It depends on the operating condition and the nature of the physical disturbance.

Their relationships <d-cite key="kundur2004stability"></d-cite>:

1. Reliability is the overall objective in power system design and operation. To be reliable, the power system must be secure most of the time. To be secure, the system must be stable but must also be secure against other contingencies that would not be classified as stability problems e.g., damage to equipment such as an explosive failure of a cable, fall of transmission towers due to ice loading or sabotage. As well, a system may be stable following a contingency, yet insecure due to post-fault system conditions resulting in equipment overloads or voltage violations.
1. System security may be further distinguished from stability in terms of the resulting consequences. For example, two systems may both be stable with equal stability margins, but one may be relatively more secure because the consequences of instability are less severe.
1. Security and stability are time-varying attributes which can be judged by studying the performance of the power system under a particular set of conditions. Reliability, on the other hand, is a function of the time-average performance of the power system; it can only be judged by consideration of the system’s behavior over an appreciable
   period of time.

Stability Categories:

**_Rotor angle stability_** <d-cite key="hatziargyriou2021stability"></d-cite> is concerned with the ability of the interconnected synchronous machines in a power system to remain in synchronism under normal operating conditions and to regain synchronism after being subjected to a small or large disturbance.

**_Voltage stability_** <d-cite key="hatziargyriou2021stability"></d-cite> refers to the ability of a power system to maintain steady voltages close to nominal value at all buses in the system after being subjected to a disturbance.

**_Frequency stability_** <d-cite key="kundur2004stability"></d-cite> refers to the ability of a power system to maintain steady frequency following a severe system upset resulting in a significant imbalance between generation and load.

The rest two categories of stability <d-cite key="kundur2004stability"></d-cite>: **Resonance Stability** and **Converter-driven Stability**.

Reliability:

**_Reliability_** <d-cite key="nerc2013terminology"></d-cite> NERC defines the reliability of the interconnected Bulk-Power System in terms of two basic and functional aspects, adequacy, and operating reliability.

**_Adequacy_** <d-cite key="nerc2013terminology"></d-cite> The ability of the electricity system to supply the aggregate electrical demand and energy requirements of the end-use customers at all times, taking into account scheduled and reasonably expected unscheduled outages of system elements.

**_Operating Reliability_** <d-cite key="nerc2013terminology"></d-cite> The ability of the Bulk-Power System to withstand sudden disturbances, such as electric short circuits or the unanticipated loss of system elements from credible contingencies, while avoiding uncontrolled cascading blackouts or damage to equipment.

**_Interruptible demand_** <d-cite key="nerc2013terminology"></d-cite> Customer demand that, in accordance with contractual arrangements, can be interrupted by direct control of the system operator or by action of the customer at the direct request of the system operator.

**_Voltage reductions_** <d-cite key="nerc2013terminology"></d-cite> This is also referred to as “brownouts” because lights dim as voltage is lowered.

**_Rotating blackouts_** <d-cite key="nerc2013terminology"></d-cite> when each set of distribution feeders is interrupted for a limited time, typically 20–30 minutes, and then those feeders are put back in service and another set is interrupted, and so on, rotating the outages among individual feeders.

## Transient Stability Index

**_Critical Clearing Time (CCT)_** <d-cite key="kundur2004stability"></d-cite> the maximum permissible duration of the fault for which the subsequent system response remains stable. This portion of stability analysis requires the knowledge of actions of protective relaying.

**_Equal Area Criterion (EAC)_** <d-cite key="kundur2022Power"></d-cite> (p831-833, first edition) The equal-area criterion is useful in determining the maximum permissible increase in $P_{m}$ for the system illustrated in Figure 13.14. Stability is maintained only if an area $A_{2}$ at least equal to $A_{1}$ can be located above $P_{m}$. If $A_{1} > A_{2}$, then the rotor angle $\delta$ will exceed its critical value, and stability will be lost. For $\delta > \delta_{\max}$, $P_{m}$ exceeds $P_{e}$, leading to net acceleration rather than deceleration.

<div style="text-align: ;left;">
  <img src="/assets/img/pswiki/response-to-a-step-change-in-mechanical-power-input.png" alt="response-to-a-step-change-in-mechanical-power-input" style="width: 540px; height: auto;">
  <p><em>Fig. 13.14 Response to a step change in mechanical power input (from <d-cite key="kundur2022Power"></d-cite>) </em></p>
</div>

Note: another record of the **_Equal Area Criteria_** can be found in <d-cite key="dahl1935stability"></d-cite>.

<!-- This measure seems to be not that relevant -->
<!-- TODO: New Stability Measure for Multimachine Power Systems <d-cite key="teichgraeber1970stability"></d-cite> -->

<!-- This measure seems to be not that relevant -->
<!-- TODO: The Application on Transfer Admittances to the Analysis of Power System Stability Stydies <d-cite key="byerly1971transfer"></d-cite> -->

<!-- This measure seems to be not that relevant -->
<!-- TODO: Dynamic Aggregation and the Calculation of Transient Stability Incides <d-cite key="rao1972dynamic"></d-cite> -->

**_Extended Equal Area Criterion (EEAC)_** <d-cite key="xue1988eeca"></d-cite> Compared to EAC, EEAC uses an approximate one-machine-infinite-bus (OMIB) equivalent of the multi-machine system.

Note: OMIB is also known as single machine infinite bus (SIMB).

## Transmission Operations

**_PJM's Real-Time Reliability Model_** <d-cite key="pjm2024m3"></d-cite> (p17, Revision 67) is a computer representation of the power system facilities in the PJM RTO and other Balancing Authorities that may impact the reliable operation of the PJM system. The model resides and is maintained by the PJM staff on the PJM Energy Management System (EMS). The PJM EMS Network Application programs utilize the model to continuously calculate the **real-time state** and determine the **security** of the PJM system. The Security Constrained Economic Dispatch (SCED) dispatches every generator in the model. The model is also used to calculate real-time Locational Marginal Prices. The model is created and maintained from input data received by PJM from various sources including Transmission Owners, Generation Owners, Load Serving Entities, and other Balancing Authorities. The model is only as accurate as the input data used to derive it; therefore, timely and accurate data updates are critical.

**_Thermal Limit Operation Criteria_** by PJM <d-cite key="pjm2024m3"></d-cite> (p29, Revision 67) PJM uses the following techniques to control contingency or system violations:

- Adjusting PARs.
- Switching reactive devices in/out of service or adjusting generator MVAR output.
- Switching transmission facilities in/out of service.
- Adjusting generation MW output via redispatch.
- Adjusting imports/exports.
- Issuing a TLR (Transmission Loading Relief).

**_Voltage Limits_** by PJM <d-cite key="pjm2024m3"></d-cite> (p40, Revision 67) High, Low, and Load Dump actual voltage limits, High and Low emergency voltage limits for contingency simulation, and voltage drop limits for wide area transfer simulations to protect against wide area voltage collapse.

**_Transfer Limits_** by PJM <d-cite key="pjm2024m3"></d-cite> (p40, Revision 67) The MW flow limitation across an interface to protect the system from large voltage drops or collapse caused by any viable contingency.

**_Stability Limits_** by PJM <d-cite key="pjm2024m3"></d-cite> (p40, Revision 67) is limit based on **voltage phase angle difference** to protect portions of the PJM RTO from separation or unstable operation.

**_Stability Limits_** by PJM <d-cite key="pjm2024m11"></d-cite> (p82, Revision 133) The ability of a generating unit or a group of generating units to maintain synchronism following a system disturbance can be identified using real time and study applications such as the PJM Transient Stability Analysis (TSA) tool. Based on results from TSA, stability limits will be established and logged within PJM’s TO Connection. For real power (MW) stability limits only, TO Connection **stability limits will be translated into a corresponding generator output constraint** (in MW) for a single generator or a group of generators.

## Adaquecy

**_Expected Unserved Energy (EUE)_** <d-cite key="nerc2013probabilistic"></d-cite> is a measure of the generation and transmission system’s capability to continuously serve all loads at all delivery points while satisfying all planning criteria. EUE is energy-centric and analyzes all hours of a particular
year. Results are calculated in **megawatthours (MWh)**. EUE is the summation of the expected number of megawatthours of load that will not be served in a given year as a result of demand exceeding the available capacity across all hours. Additionally, this measure can be normalized based on the assessment area’s total Net Energy for Load. Normalizing the EUE provides a measure relative to the size of a given assessment area.

**_Loss-of-Load Hour (LOLH)_** <d-cite key="nerc2013probabilistic"></d-cite> is generally defined as the number of hours per year where system demand will exceed the generating capacity. LOLH is usually expressed in **hours per year**. Any outage caused by inadequate resources regardless of geographic extent or load interrupted (it could be 1 MW for a single customer or the loss of the whole area load) counts as a LOLH. An LOLH of 0.1 means that an hour of loss of load is expected for every 10 years. For a particular year (e.g. 2014), the resources available and load shapes for that year are used to calculate the metrics for that
year.

**_Loss-of-load expectation (LOLE)_** <d-cite key="nerc2013probabilistic"></d-cite> is generally defined as number of days per year for which the available generation capacity is insufficient to serve the demand at least once during that day. This metric is not being reported as part of this assessment. A criterion of one day in 10 years is an often used standard for LOLE.

**_Loss-of-load probability (LOLP)_** is the probability of system demand exceeding the generating capacity during a given period. If LOLP is the number of days on which there is expected to be a shortfall per year, it is the same as LOLE. However, other definitions of LOLP are also used.

**_Loss-of-load events (LOLEV)_** is the number of events in which some system load is not served in a given year. A LOLEV can last for one hour or for several contiguous hours and can involve the loss of one or several hundred megawatts of load. TRE-ERCOT is the only Assessment Area to provide this metric in its regional assessment.

## Operating Reliability

**_Severity Risk Index (SRI)_** <d-cite key="nerc2020sri"></d-cite> (p5) is a **daily metric** where transmission loss, generation loss, and load loss events aggregate into a single value that indicates performance of the BES. The SRI values range from zero to 1000. Zero is a theoretical condition where no transmission, generation or load loss occurred during the entire day. To the corollary, a value of 1000 would represent a situation where every transmission, generation and load5 was lost during the entire day. The SRI was designed to be usable for the entirety of NERC as well as applied more granularly, such as at an interconnection level.

**_SRI_** <d-cite key="nerc2024sor"></d-cite> (p12) The SRI provides a quantitative measure that assesses the relative severity of the combined impact of load, generation, and transmission loss on the BPS daily and offers a comprehensive picture of the performance of the BPS, allowing NERC to assess year-on-year reliability trends.

## Flexibility

**_System flexibility_** <d-cite key="nerc2010flexible"></d-cite> (in Executive Summary on page I) is defined as the ability of supply-side and demand-side resources to respond to system changes and uncertainties. Flexibility also includes the ability to store energy for delivery in the future and the operational flexibility to schedule/dispatch resources in the most efficient manner.

**_Flexibility reserves_** <d-cite key="nyiso2024power"></d-cite> (p37) are an emerging concept for addressing variability and uncertainty on longer timescales than operating reserves and regulation service.
The Ancillary Services Market secures **flexibility services** from suppliers to maintain balance in response to changing conditions on the electrical grid.

## Resilience

**_Resilience_** <d-cite key="nerc2018resilience"></d-cite> (p8) FERC proposed to define resilience as, the ability to withstand and reduce the magnitude and/or duration of disruptive events, which includes the capability to anticipate, absorb, adapt to, and/or rapidly recover from such an event.

Some other definitions of resilience <d-cite key="chiu2020resilience"></d-cite> (p8):

FERC: The ability to withstand and reduce the magnitude and/or duration of disruptive events, which includes the capability to anticipate, absorb, adapt to, and/or rapidly recover from such event.

DOE: The ability of a power system and its components to withstand and adapt to disruptions and rapidly
recover from them.

NATF: The ability of the system and its components (i.e., both the equipment and human components) to minimize damage and improve recovery from non-routine disruptions, including high impact, low frequency (HILF) events, in a reasonable amount of time.

The IEEE Technical Report PES-TR65 and FERC Docket No. AD18-7-000 defines resilience as “The ability to withstand and reduce the magnitude and/or duration of disruptive events, which includes the capability to anticipate, absorb, adapt to, and/or rapidly recover from such an event.”

**_Storm resilience metric_** by IEEE <d-cite key="chiu2020resilience"></d-cite> (p12) This metric focuses on the speed of system recovery and is designed to capture the reduction of the number of customers without power for more than 12 hours from the time the customer loses power during a storm event. The metric will consider the instances of customer service interruptions that have been restored automatically without requiring human intervention to capture the value of technology solutions such as distribution automation, advanced distribution management system (ADMS), or microgrids, that minimize customer impacts. It will measure the number of reportable storms where recovery is favorable to threshold values divided by the total number of reportable storms.

**_Non-Storm Resilience Metric_** by IEEE <d-cite key="chiu2020resilience"></d-cite> (p13) This metric focuses on robustness and the ability to withstand events. It is designed to capture the total number of gray sky days (GSD) in a calendar year with no more than the threshold value of customer interruptions. The metric is measured in a percentage of GSDs that does not exceed the threshold value. The threshold value varies by utility size and is defined as the percentage of customer interruptions over the total customer base (e.g.,0.375% of the total number of customers). GSD excludes any calendar day with at least one reportable storm-related outage.

**_Multi-criteria decision analysis (MCDA)-based metrics_** by DOE GMLC <d-cite key="chiu2020resilience"></d-cite> (p13): MCDA metrics generally try to answer the question,
“what is the current state of the electric system’s resilience, and what enhances its resilience over time?” These metrics can be used to assess the system’s baseline resilience relative to other systems. They typically include categories of system properties beneficial to resilience, such as robustness, resourcefulness, adaptivity, and recoverability. The application of these metrics requires following a process to review to what degree these properties are present within the system under analysis. This usually involves collecting data through surveys, developing weighting factors, and performing calculations to obtain numerical scores. MCDA metrics are used to calculate a resilience index (RI) that accounts for about 1,200 attributes grouped in 350 categories to characterize system resilience.

**_Performance-based metrics_** by DOE GMLC <d-cite key="chiu2020resilience"></d-cite> (p13): performance-based metrics (also known as **_consequence-based metrics_**) are
generally quantitative approaches for answering the question, “How resilient is my system?” These metrics interpret quantitative data that describe infrastructure performance during disruptive events. The required data can be collected from historical events, subject matter estimates, and computational infrastructure models. These metrics are suitable for benefit-cost and planning analyses because they measure the potential benefits and costs associated with proposed resilience improvements and investments. Resilience metrics need to include a measure of consequences and the relevant statistical probability from the probability distribution of those consequences.

## Transmission Expansion and Interconnection

**_Transmission Expansion_** by NYISO <d-cite key="nyiso2023tei"></d-cite> (p4, Version 4.2): A transmission expansion is the **addition or modification** of facilities of the NYS Transmission System that may be proposed or initiated by an Eligible Customer, including a TO, under Section 3.7 of or Attachment P to the NYISO OATT.

**_Interconnection_** by NYISO <d-cite key="nyiso2023tei"></d-cite> (p28, Version 4.2): In the context of this manual, an interconnection refers to the connection of a new **Generating Facility**, Class Year Transmission Project, or **Load** to the NYS Transmission System; or to materially increase the capacity of, or make a material modification to the operating characteristics of, an existing Generating Facility (including a BTM:NG Resource) or Class Year Transmission Project that is interconnected to the NYS Transmission System or Distribution System (see definition of “Interconnection Request” and related capitalized terms in Attachment X and Attachment Z to the NYISO OATT).

**_System Impact Study (SIS)_** by NYISO <d-cite key="nyiso2023tei"></d-cite> (p16, Version 4.2), The purpose of the SIS is to evaluate the impact of the proposed transmission project on the reliability of the NYS Transmission System and if study results indicate that the project, as proposed, would result in any adverse impact on reliability or violations of reliability standards and identify any Network Upgrades that would be required to mitigate any such adverse impact(s) or violation(s).

**_Facilities Study_** by NYISO <d-cite key="nyiso2023tei"></d-cite> (p21, Version 4.2), The main purpose and objective of the Facilities Study is to provide to the Customer good faith estimates of the cost and time to construct the new facilities identified in the SIS.

## Uncertainty

**_Aleatoric (aka statistical) uncertainty_** <d-cite key="hullermeier2021aleatoric"></d-cite> refers to the notion of randomness, that is, the variability in the outcome of an experiment which is due to **inherently random effects**.

**_Epistemic (aka systematic) uncertainty_** <d-cite key="hullermeier2021aleatoric"></d-cite> refers to uncertainty caused by a **lack of knowledge** (about the best model). In other words, it refers to the **ignorance** of the agent or decision maker, and hence to the epistemic state of the agent instead of any underlying random phenomenon.

As opposed to uncertainty caused by randomness, uncertainty caused by ignorance can in principle be reduced on the basis of additional information. In other words, epistemic uncertainty refers to the **reducible** part of the (total) uncertainty, whereas aleatoric uncertainty refers to the **irreducible** part.

## Events

**_Contingency_** <d-cite key="nerc2024glossary"></d-cite> The unexpected failure or outage of a system component, such as a generator, transmission line, circuit breaker, switch or other electrical element.

**_Most Severe Single Contingency_** <d-cite key="nerc2024glossary"></d-cite> The Balancing Contingency Event, due to a single contingency identified using system models maintained within the Reserve Sharing Group (RSG) or a Balancing Authority’s area that is not part of a Reserve Sharing Group, that would result in **the greatest loss** (measured in MW) of resource output used by the RSG or a Balancing Authority that is not participating as a member of a RSG at the time of the event to meet Firm Demand and export obligation (excluding export obligation for which Contingency Reserve obligations are being met by the Sink Balancing Authority).

**_Disturbance_** <d-cite key="nerc2024glossary"></d-cite> Means (i) any perturbation to the electric system, or (ii) the unexpected change in ACE that is caused by the sudden loss of generation or interruption of load.

**_Fault_** <d-cite key="nerc2024glossary"></d-cite> An event occurring on an electric system such as a short circuit, a broken wire, or an intermittent connection.

## Horizon

**_Near-Term Transmission Planning Horizon_** <d-cite key="nerc2024glossary"></d-cite> The transmission planning period that covers Year One through five.

**_Long-Term Transmission Planning Horizon_** <d-cite key="nerc2024glossary"></d-cite> Transmission planning period that covers years six through ten or beyond when required to accommodate any known longer lead time projects that may take longer than ten years to complete.

## Factors

**_Outage Transfer Distribution Factor (OTDF)_** <d-cite key="nerc2024glossary"></d-cite> In the post-contingency configuration of a system under study, the electric Power Transfer Distribution Factor (PTDF) with one or more system Facilities removed from service (outaged).

**_Participation Factors_** <d-cite key="nerc2024glossary"></d-cite> A set of dispatch rules such that given a specific amount of load to serve, an **approximate generation** dispatch can be determined. To accomplish this, generators are assigned a percentage that they will contribute to serve load.

## Area, Zone, and Region

**_Balancing Authority Area_** <d-cite key="nerc2024glossary"></d-cite> The collection of generation, transmission, and loads within the metered boundaries of the Balancing Authority. The Balancing Authority maintains load-resource balance within this area.

**_Reliability Coordinator Area_** <d-cite key="nerc2024glossary"></d-cite> The collection of generation, transmission, and loads within the boundaries of the Reliability Coordinator. Its boundary coincides with one or more Balancing Authority Areas.

**_Control area_** <d-cite key="ferc2020glossary"></d-cite> An electric power system or combination of electric power systems to which a common automatic control scheme is applied in order to:

- Match, at all times, the power output of the generators within the electric power system(s) and capacity and energy purchased from entities outside the electric power system(s), with the load in the electric power system(s).
- Maintain, within the limits of Good Utility Practice, scheduled interchange with other Control Areas.
- Maintain the frequency of the electric power system(s) within reasonable limits in accordance with Good Utility Practice.
- Provide sufficient generating capacity to maintain operating reserves in accordance with Good Utility Practice.

**_loss_zone_** <d-cite key="matpower"></d-cite> In MATPOEWR, there is a bus parameter named "ZONE", and it means loss zone.

**_Zone_** There is no clear definition, but my best guess is that it refers to different areas within the Bulk-Power System.

<div style="text-align: ;left;">
  <img src="/assets/img/pswiki/PJM_zone_map.png" alt="PJM Zone Map" style="width: 700px; height: auto;">
  <p><em>PJM Transmission Zones Map (from <d-cite key="pjm"></d-cite>) </em></p>
</div>

**_Region_** <d-cite key="nerc2024tpl"></d-cite> NERC divides North America into several regions for the purpose of reliability and coordination. Each region is responsible for ensuring the reliability of the bulk power system within its boundaries. The six regions are:

- MRO: Midwest Reliability Organization
- NPCC: Northeast Power Coordinating Council
- RF: ReliabilityFirst
- SERC: SERC Reliability Corporation
- Rexas RE: Texas Reliability Entity
- WECC: Western Electricity Coordinating Council

<div style="text-align: ;left;">
  <img src="/assets/img/pswiki/six_region.png" alt="Regional Maps" style="width: 700px; height: auto;">
  <p><em>Regional Maps (from <d-cite key="nerc2024tpl"></d-cite>) </em></p>
</div>

## Data Formats

**_Common Information Model (CIM)_** <d-cite key="epri2021cim"></d-cite> (in Report Summary, page v) is **a set of open standards** for representing power system components originally developed by the EPRI in North America and now a series of standards under the IEC.

**_CIM_** (p1) <d-cite key="anderson2023cim"></d-cite> is an **abstract information model** that can be used to model an electrical network and the various equipment used on the network. CIM is widely used for data exchange of bulk transmission power systems and is now beginning to find increasing use for distribution modeling and analysis. By using a common model, utilities, vendors, and researchers from both academia and industry can reduce the effort and cost of data integration, and instead focus on developing increased functionality for managing and optimizing the smart grid of the future.

A brief history of CIM can be found in <d-cite key="wollenberg2015cimhistory"></d-cite>.

A sample CIM file can be found at [CIMpy - CIM data created with NEPLAN](https://github.com/sogno-platform/cimpy/tree/master/cimpy/examples/sampledata/CIGRE_MV)

Two answers by Microsoft Copilot about CIM, RDF, UML, and XML, on 01-09-2025:

The **Common Information Model (CIM)** is a **standard** developed by the electric power industry to facilitate the exchange of information about an electrical network. It is maintained as a UML model and defines a common vocabulary and basic ontology for modeling the components and measurements of power systems. The CIM is officially adopted by the International Electrotechnical Commission (IEC) and is used to derive design artifacts like XML or RDF schemas for application integration. It supports various applications, including energy management systems, SCADA, and planning and optimization1.

The **Resource Description Framework (RDF)** is a **standard model** for data interchange on the web. Developed by the World Wide Web Consortium (W3C), RDF allows for the representation of information about resources in a graph form. RDF uses triples, which consist of a subject, predicate, and object, to make statements about resources. This model is highly flexible and can represent complex relationships between data. RDF is often used in conjunction with other web standards like SPARQL for querying RDF data, and it supports various serialization formats such as RDF/XML, Turtle, and JSON-LD23.

The **Unified Modeling Language (UML)** is a standardized general-purpose **modeling language** in the field of software engineering. UML provides a set of graphical notation techniques to create visual models of software-intensive systems. It includes various types of diagrams, such as class diagrams, sequence diagrams, and use case diagrams, to represent different aspects of a system. UML is widely used for specifying, visualizing, constructing, and documenting the artifacts of software systems. It helps in understanding, designing, and managing complex software projects45.

The **Extensible Markup Language (XML)** is a **markup language** designed to store and transport data. XML allows developers to define their own tags and structure data in a platform-independent way. It is widely used for data interchange between different systems and platforms. XML documents are made up of elements defined by starting and ending tags, and they can include attributes to provide additional information about the data. XML is used in various applications, including web services, configuration files, and data exchange formats67.

Summary:

- CIM: Standard for modeling power system components and measurements, used for data exchange in the electric power industry.
- RDF: Framework for representing information about resources in a graph form, used for data interchange on the web.
- UML: General-purpose modeling language for visualizing and documenting software systems.
- XML: Markup language for storing and transporting data, allowing for custom tag definitions and platform-independent data exchange.

Summary of what CIM is not:

- CIM is not a programming language: It is a standard for modeling power system components and measurements.
- CIM is not a software application: It provides a common data model for information exchange but is not an executable program.
- CIM is not a database: While it can be used to define data structures, it is not a database management system.
- CIM is not a communication protocol: It defines data models and schemas but does not specify how data is transmitted between systems.

**_Common Format for Event Data Exchange (COMFEDE) for Power Systems_** <d-cite key="ieee2010comfede"></d-cite> This standard defines a common format for the data files needed for the exchange of various types of power network events in order to facilitate event data integration and analysis from multiple data sources and from different vendor devices. The flexibility provided by digital devices in recording network fault event data in the electric utility industry has generated the need for a standard format for the exchange of data. These data are being used with various devices to enhance and automate the analysis, testing, evaluation, and simulation of power systems and related protection schemes during fault and disturbance conditions. Since each source of data may use a different proprietary format, a common data format is necessary to facilitate the exchange of such data between applications. This will facilitate the use of proprietary data in diverse applications and allow users of one proprietary system to use digital data from other systems. **A sample file is given in the source file.**

Versions:
Inactive

- Draft: PC37.239/D04, Mar 2010 - Dec 31, 2010
- Reserved: C37.239-2010 - Nov 11, 2010
- Draft: C37.239 - Jan 01, 2010

**_Common Format for Transient Data Exchange (COMTRADE) for Power Systems_** <d-cite key="ieee1999comtrade"></d-cite>
A common format for data files and exchange medium used for the interchange of various types of fault, test, or simulation data for electrical power systems is defined. Sources of transient data are described, and the case of disketts as an exchange medium is recommended. issues of sampling rates, filters, and sample rate conversions for transient data being exchanged are discussed. Files for data exchange are specified, as is the organization of the data. **A sample file is given in the source file.**

Versions:
Superseded

- C37.111-1999 - Oct 15, 1999
- C37.111-1991 - Oct 21, 1991

Inactive

- Reserved: C37.111-2013 - Apr 30, 2013
- Redline: C37.111-2013 - Apr 30, 2013
- Draft: PC37.111/D4, Jan 2012 - Jul 24, 2012

**_Common Format for Exchange of Solved Load Flow Data_** <d-cite key="ieee1973loadflow"></d-cite>, also referred as common data format (CDF). This format is presently (Note that this format was used around the 1970s rather than 2020s) being used throughout most of the eastern and north central United States and parts of Canada. By publishing through the national organization, it is intended that a common reference be established and maintained for those who wish to use the format. The paper presents a detailed description of the format as well as procedures for making revisions and additions.

A matpower function to convert an IEEE CDF data file into a MATPOWER case struct., https://matpower.org/doc/ref-manual/legacy/functions/cdf2mpc.html#cdf2mpc

## Vendors

**_EMTP_** Electromagnetic transients program (EMTP) is the reference for EMT simulations and analysis of power systems.

- Load-Flow: EMTP has a very powerful unbalanced multi-phase load-flow solver capable of solving very large scale transmission and distribution grids, cases with more than 300000 buses can be solved.
- Time-Domain: EMTP provides the most accurate, numerically stable, and consistent time-domain EMT simulations.
- Steady-State: The electrical network equations are solved using complex phasors. This option can be used in the stand-alone mode or for initializing the time-domain solution. A harmonic steady-state solution can be achieved.
- Frequency-Scan: A frequency scan simulation is available with EMTP to determine the system impedance and to identify any possible resonance frequencies within the system.

Note: [screen shot on 01-09-2025](https://github.com/jinningwang/jinningwang.github.io/tree/main/assets/img/vendors/EMTP.png), https://www.emtp.com/products/emtp

**_EasyPower_** The EasyPower product suite delivers a full lineup of powerful electrical software tools for intelligently designing, analyzing, and monitoring electrical power systems.

- PowerFlow: Optimize voltage drop, conductor and equipment loading, power factor, losses, transformer taps, and real and reactive load flows at each branch and bus. (This includes balanced and unbalanced AC, and DC)
- Harmonics: Analyze system harmonic conditions for standards or interconnect compliance, optimization, troubleshooting, and filter design.
- Reliability: Calculate reliability, assess contingency plans, and quantify downtime costs.
- Transient Motor Starting – Solve complex motor starting scenarios to verify system stability.
- Dynamic Stability: Simulate dynamic interaction between machines, networks, and protective device actions. Keep your system stable & avoid downtime.

Note: [screen shot on 01-09-2025](https://github.com/jinningwang/jinningwang.github.io/tree/main/assets/img/vendors/EasyPower.png), https://www.easypower.com/products/easypower

**_PSCAD_** The World's Most Advanced Tool for Power Systems EMT Simulations

Note: [screen shot on 01-09-2025](https://github.com/jinningwang/jinningwang.github.io/tree/main/assets/img/vendors/PSCAD.png), https://www.pscad.com/software/pscad/overview

**_ETAP_** provides market-leading software solutions for electrical systems, from design and engineering to operations and maintenance.

- ETAP Load Flow Analysis Software offers an extensive set of power flow analysis and simulation tools to calculate bus voltages, branch power factors, currents, and power flows throughout the electrical system.
- Transient stability analysis enables engineers to accurately simulate and analyze power system dynamics and transients via system disturbances and other events.
- Distribution Network Analysis, Distribution system analysis and optimization tools used for network planning, simulation, and prediction of system response using schematic or geospatial views.

Note: cheked on 01-09-2025, https://etap.com/home

**_PowerFactory_** by DIgSILENT, is a power system analysis software application for use in analysing generation, transmission, distribution and industrial systems. It covers the full range of functionality from standard features to highly sophisticated and advanced applications including windpower, distributed generation, real-time simulation and performance monitoring for system testing and supervision.

Note: [screen shot on 01-09-2025](https://github.com/jinningwang/jinningwang.github.io/tree/main/assets/img/vendors/PowerFactory.png), https://www.digsilent.de/en/powerfactory.html

**_NEPLAN Electricity_** is a software tool to analyse, plan, optimize and simulate electrical networks. The strength of the software is the extremely user-friendly graphical interface with the extensive libraries for the network elements, protection devices and control circuits, which allows the user to perform study cases very efficiently. The software has a modular concept, is based on international standards, such as IEC, ANSI, IEEE, etc. and is customizable for the European and US market. It is used in transmission, distribution, generation / industrial networks amongst others for network and investment planning, power quality, multi-period optimization, protection setting and assessment, dynamic simulation (RMS/EMT). The stationary and dynamic models for 1-2-3 phase (with neutral and earth wire) AC and DC networks have a high accuracy and performance. Very big network (above 500’000 bus bars) could be easily handled by new IT-techniques and algorithm.

Note: [screen shot on 01-09-2025](https://github.com/jinningwang/jinningwang.github.io/tree/main/assets/img/vendors/NEPLANElectricity.png), https://neplan.ch/neplanproduct/en-electricity/

**_PowerWorld Simulator_** is an interactive power system simulation package designed to simulate high voltage power system operation on a time frame ranging from several minutes to several days. The software contains a highly effective power flow analysis package capable of efficiently solving systems of up to 250,000 buses.

PowerWorld offers several optional add-ons in addition to the base Simulator Package:

- Available Transfer Capability (ATC): Determine the maximum MW transfer possible between two parts of the power system without violating any limits.
- Distributed Computing: Leverage multi-processor hardware and network Resources for faster analys.
- Geomagnetically Induced Current (GIC): Model and evaluate the risk posed by geomagnetic disturbances, such as solar storms
- Integrated Topology Processing: Access full unification of planning and operations at three levels: format, model and application environment.
- Optimal Power Flow Analysis Tool (OPF): Optimally dispatch generation while simultaneously enforcing transmission line and interface limits.
- SimAuto: Take advantage of the power of automation to extend the functionality of PowerWorld Simulator to any external program that you write.
- Transient Stability: Utilize powerful dynamic simulation with the simplicity only PowerWorld can deliver.
- Voltage Stability (PVQV): Analyze a power system’s static voltage stability margins.

Note: [screen shot on 01-09-2025](https://github.com/jinningwang/jinningwang.github.io/tree/main/assets/img/vendors/PowerWorld.png), https://www.powerworld.com/solutions

**_Energy Exemplar_**

- PLEXOS, Co-optimization; Nodal and Zonal analysis; Renewables and ancillary markets; Hydro-optimization; Gas Planning; Multi-objective decision optimization
- AURORA: Power Market Price Forecasting; Energy Portfolio Analysis; Optimized Resource Expansion; Power Market Risk Analysis
- Adapt2: streamlines energy operations
- Simulation-Ready Datasets: Our data teams gather available public and subscribed data, analyzing and calibrating information within each global market for use in your models. Data is updated annually and benchmarked against historical data to demonstrate data quality. Global Datasets are available for the following markets: North America, Latin America, Europe, APAC.

Note: [snapshot on 01-09-2025](https://github.com/jinningwang/jinningwang.github.io/tree/main/assets/img/vendors/EnergyExemplar.png), https://www.energyexemplar.com/products

**_PSS_** by Siemens, power system simulation and modeling software

- PSS®E – high-performance transmission planning and analysis software. PSS®E allows operators to perform analyses of power flow, dynamics, short circuits, contingency, voltage stability, transient stability, and much more.
- PSS®E Cloud X combines your industry trusted transmission planning tool with the power of the cloud. Unlock scalable computation power, secure collaboration, flexible remote working, and more!
- PSS®MOD – project modeling and data management for PSS®E. Your solution for power transmission planning model management: PSS®MOD coordinates submission of network model data and provides access to complete study cases on demand for any point in time.
- PSS®ODMS – CIM-based transmission network modeling and analysis. Bridge the gap between multiple utility domains, including operations and planning. With real and virtual worlds tightly aligned, PSS®ODMS provides utilities with a single source of truth for managing and exchanging network model data across their entire IT landscape.
- PSS®SINCAL – analysis and planning of electric and pipe networks. A simulator for planning, modeling, and analyzing all electrical power or pipe network types: PSS®SINCAL provides a full unbalanced power system model for high, medium and low-voltage grids.
- Gridscale X Network Model Manager. Comprehensive, consistent network model data management and repository – fast, scalable, and fully interoperable.
- Gridscale X Advanced Protection Assessment. Gridscale X Advanced Protection Assessment (formerly known as PSS®CAPE) supports transmission and distribution protection engineers with their entire workflow from detailed protection data collection, electronic setting management, setting calculations and validation.
- Gridscale X Dynamic Security Assessment. The automated, integrated Gridscale X Dynamic Security Assessment software increases transmission system security and improves operational planning processes.
- Gridscale X Protection Data Manager. Powerful and convenient tool for managing protection data.
- CTDim – Current and voltage transformer dimensioning. With CTDim, efficiently perform instrument transformer dimensioning while considering both protection and measuring cores. It allows you to decrease engineering and production costs by optimizing the CT and VT data.

Note: [snapshot on 01-09-2025](https://github.com/jinningwang/jinningwang.github.io/tree/main/assets/img/vendors/SiemensPSS.png), https://www.siemens.com/global/en/products/energy/grid-software/planning/pss-software.html

**_PlanOS_**, by GE Vernova, a comprehensive software platform to confidently plan for a more reliable, resilient, and stable energy system.

- Steady State Power Flow (formerly PSLF) Describe and simulate more accurately the physical behavior of the grid and connected equipment under stable operating conditions, identify potential vulnerabilities, and help ensure reliable operation.
- Resource Adequacy (formerly MARS) Assess the ability of a power system to help adequately satisfy load requirements.
- Production Cost (formerly MAPS) Model the economic operation of the power system for informed economic decisions.
- New: Capacity Expansion Forecast capacity additions considering uncertain (stochastic) variables and generate adaptable plans that reduce costs across many possible future outcomes.

Note: [snapshot on 01-09-2025](https://github.com/jinningwang/jinningwang.github.io/tree/main/assets/img/vendors/GEVeronaPlanOS.png), https://www.gevernova.com/consulting/planos

## Change Log

2025-01-18

- Add a Preface section

2025-01-16

- Add section of Uncertainty

2025-01-15

- Add section of Transmission Expansion and Interconnection

2025-01-13

- Add Transmission Operations section
- Simplify the item of Bulk Electric System
- Add page numbers for some items

2025-01-12

- Add definition of DER by IEEE Std 1547-2018
- Add Transient Stability Index section

2025-01-09

- Add Data Formats section
- Add Vendors section

2024-12-30

- Add Flexibility section
- Add NYISO's description of the markets

2024-12-19

- Add Adaquecy section
- Add Operating Reliability section
- Add Resilience section

2024-12-17

- Add Reliability section
- Add Generation section
- Add acronyms table

2024-12-12

- Add ancillary services and AGC by FERC
- Add AGC by FERC
- Add Market section

2024-12-11

- Initial post
