---
layout: distill
title: Power Systems Wiki
date: 2024-12-11 10:00:00
description: Some terminology for my own reference.
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
  - name: Adaquecy
  - name: Operating Reliability
  - name: Resilience
  - name: Events
  - name: Horizon
  - name: Factors
  - name: Area, Zone, and Region
  - name: Change Log
---

Acronyms:

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

Organizations:

|---------|-------------------------------------------------|
| FERC | Federal Energy Regulatory Commission |
| NERC | North American Electric Reliability Corporation |

## Power Grids

**_Balancing Authorities_** <d-cite key="nerc2024glossary"></d-cite> The responsible entity that integrates resource plans ahead of time, maintains Demand and resource balance within a Balancing Authority Area, and supports Interconnection frequency in real time.

**_Interconnection_** <d-cite key="nerc2024glossary"></d-cite> A geographic area in which the operation of BPS components is synchronized such that the failure of one or more of such components may adversely affect the ability of the operators of other components within the system to maintain Reliable Operation of the Facilities within their control. When capitalized, any one of the four major electric system networks in North America: Eastern, Western, ERCOT and Quebec.

**_Bulk-Power System (BPS)_** <d-cite key="nerc2024glossary"></d-cite> (A) facilities and control systems necessary for operating an interconnected electric energy transmission network (or any portion thereof); and (B) electric energy from generation facilities needed to maintain transmission system reliability.
The term **does not** include facilities used in the local distribution of electric energy. (Note that the terms “Bulk-Power System” or “Bulk Power System” shall have the same meaning.)

**_Bulk Electric System (BES)_** <d-cite key="nerc2024glossary"></d-cite> Unless modified by the lists shown below, all Transmission Elements operated at **100 kV or higher** and Real Power and Reactive Power resources connected at 100 kV or higher. This **does not** include facilities used in the local distribution of electric energy.

Inclusions:

**I1** - Transformers with the primary terminal and at least one secondary terminal operated at 100 kV or higher unless excluded by application of Exclusion E1 or E3.

**I2** - Generating resource(s) including the generator terminals through the high-side of the step-up transformer(s) connected at a voltage of 100 kV or above with:

(a) Gross individual nameplate rating greater than 20 MVA. Or,

(b) Gross plant/facility aggregate nameplate rating greater than 75 MVA.

**I3** - Blackstart Resources identified in the Transmission Operator’s restoration plan.

**I4** - Dispersed power producing resources that aggregate to a total capacity greater than 75 MVA (gross nameplate rating), and that are connected through a system designed primarily for delivering such capacity to a common point of connection at a voltage of 100 kV or above. Thus, the facilities designated as BES are:

(a) The individual resources, and

(b) The system designed primarily for delivering capacity from the point where those resources aggregate to greater than 75 MVA to a common point of connection at a voltage of 100 kV or above.

**I5** – Static or dynamic devices (excluding generators) dedicated to supplying or absorbing Reactive Power that are connected at 100 kV or higher, or through a
dedicated transformer with a high-side voltage of 100 kV or higher, or through a transformer that is designated in Inclusion I1 unless excluded by application of Exclusion E4

Exclusions:

**E1** - Radial systems: A group of contiguous transmission Elements that emanates from a single point of connection of 100 kV or higher and:

(a) Only serves Load. Or,

(b) Only includes generation resources, not identified in Inclusions I2, I3, or I4, with an aggregate capacity less than or equal to 75 MVA (gross nameplate rating). Or,

(c) Where the radial system serves Load and includes generation resources, not identified in Inclusions I2, I3 or I4, with an aggregate capacity of non-retail generation less than or equal to 75 MVA (gross nameplate rating).

Note 1 – A normally open switching device between radial systems, as depicted on prints or one-line diagrams for example, does not affect this exclusion.

Note 2 – The presence of a contiguous loop, operated at a voltage level of 50 kV or less, between configurations being considered as radial systems, does
not affect this exclusion.

**E2** - A generating unit or multiple generating units on the customer’s side of the retail meter that serve all or part of the retail Load with electric energy
if: (i) the net capacity provided to the BES does not exceed 75 MVA, and (ii) standby, back-up, and maintenance power services are provided to the generating unit or multiple generating units or to the retail Load by a Balancing Authority, or provided pursuant to a binding obligation with a Generator Owner or Generator Operator, or under terms approved by the applicable regulatory authority.

**E3** - Local networks (LN): A group of contiguous transmission Elements operated at less than 300 kV that distribute power to Load rather than transfer bulk power across the interconnected system. LN’s emanate from multiple points of connection at 100 kV or higher to improve the level of service to retail customers and not to accommodate bulk power transfer across the interconnected system. The LN is characterized by all of the following:

(a) Limits on connected generation: The LN and its underlying Elements do not include generation resources identified in Inclusions I2, I3, or
I4 and do not have an aggregate capacity of non-retail generation greater than 75 MVA (gross nameplate rating);

(b) Real Power flows only into the LN and the LN does not transfer energy originating outside the LN for delivery through the LN; and

(c) Not part of a Flowgate or transfer path: The LN does not contain any part of a permanent Flowgate in the Eastern Interconnection, a major transfer path within the Western Interconnection, or a comparable monitored Facility in the ERCOT or Quebec Interconnections, and is not a monitored Facility included in an Interconnection Reliability Operating Limit (IROL).

**E4** – Reactive Power devices installed for the sole benefit of a retail customer(s).

Note - Elements may be included or excluded on a case-by-case basis through the Rules of Procedure exception process.

## Dispatch

**_Economic Dispatch_** <d-cite key="nerc2024glossary"></d-cite> The allocation of demand to individual generating units on line to effect the most economical production of electricity.

## Generation

**_Inverter-based resources_** <d-cite key="nerc2023inverter"></d-cite> refer generally to BPS-connected facilities that have a power electronic interface between the ac grid and the source of electricity.

Following two Q&A are from Reference <d-cite key="nerc2023inverter"></d-cite>.

**What types of IBR exist?**

Inverter-based resources include modern wind turbines, meaning type 3 and type 4 wind turbines, solar photovoltaic, and battery energy storage resources, as well as HVDC circuits and FACTs devices like static synchronous compensators and static volt-ampere reactive compensators.

**What is the difference between IBR and DER?**

- DER are generating resources located on the **distribution** system.
- DER **may or may not** use inverter technology to interface with the ac grid; however, they are distinctly different than BPS-connected inverter-based resources (connected to transmission and sub-transmission levels).

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
  <img src="/assets/img/poster/frequency_trend.png"
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
  <img src="/assets/img/poster/operating_reserve.png" alt="Operating Reserves" style="width: 700px; height: auto;">
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

The rest two categories of stability <d-cite key="kundur2004stability"></d-cite>: **_Resonance Stability_** and **_Converter-driven Stability_**.

Reliability:

**_Reliability_** <d-cite key="nerc2013terminology"></d-cite> NERC defines the reliability of the interconnected Bulk-Power System in terms of two basic and functional aspects, adequacy, and operating reliability.

**_Adequacy_** <d-cite key="nerc2013terminology"></d-cite> The ability of the electricity system to supply the aggregate electrical demand and energy requirements of the end-use customers at all times, taking into account scheduled and reasonably expected unscheduled outages of system elements.

**_Operating Reliability_** <d-cite key="nerc2013terminology"></d-cite> The ability of the Bulk-Power System to withstand sudden disturbances, such as electric short circuits or the unanticipated loss of system elements from credible contingencies, while avoiding uncontrolled cascading blackouts or damage to equipment.

**_Interruptible demand_** <d-cite key="nerc2013terminology"></d-cite> Customer demand that, in accordance with contractual arrangements, can be interrupted by direct control of the system operator or by action of the customer at the direct request of the system operator.

**_Voltage reductions_** <d-cite key="nerc2013terminology"></d-cite> This is also referred to as “brownouts” because lights dim as voltage is lowered.

**_Rotating blackouts_** <d-cite key="nerc2013terminology"></d-cite> when each set of distribution feeders is interrupted for a limited time, typically 20–30 minutes, and then those feeders are put back in service and another set is interrupted, and so on, rotating the outages among individual feeders.

## Adaquecy

**_Expected Unserved Energy (EUE)_** <d-cite key="nerc2013probabilistic"></d-cite> is a measure of the generation and transmission system’s capability to continuously serve all loads at all delivery points while satisfying all planning criteria. EUE is energy-centric and analyzes all hours of a particular
year. Results are calculated in **_megawatthours (MWh)_**. EUE is the summation of the expected number of megawatthours of load that will not be served in a given year as a result of demand exceeding the available capacity across all hours. Additionally, this measure can be normalized based on the assessment area’s total Net Energy for Load. Normalizing the EUE provides a measure relative to the size of a given assessment area.

**_Loss-of-Load Hour (LOLH)_** <d-cite key="nerc2013probabilistic"></d-cite> is generally defined as the number of hours per year where system demand will exceed the generating capacity. LOLH is usually expressed in **_hours per year_**. Any outage caused by inadequate resources regardless of geographic extent or load interrupted (it could be 1 MW for a single customer or the loss of the whole area load) counts as a LOLH. An LOLH of 0.1 means that an hour of loss of load is expected for every 10 years. For a particular year (e.g. 2014), the resources available and load shapes for that year are used to calculate the metrics for that
year.

**_Loss-of-load expectation (LOLE)_** <d-cite key="nerc2013probabilistic"></d-cite> is generally defined as number of days per year for which the available generation capacity is insufficient to serve the demand at least once during that day. This metric is not being reported as part of this assessment. A criterion of one day in 10 years is an often used standard for LOLE.

**_Loss-of-load probability (LOLP)_** is the probability of system demand exceeding the generating capacity during a given period. If LOLP is the number of days on which there is expected to be a shortfall per year, it is the same as LOLE. However, other definitions of LOLP are also used.

**_Loss-of-load events (LOLEV)_** is the number of events in which some system load is not served in a given year. A LOLEV can last for one hour or for several contiguous hours and can involve the loss of one or several hundred megawatts of load. TRE-ERCOT is the only Assessment Area to provide this metric in its regional assessment.

## Operating Reliability

**_Severity Risk Index Enhancements_** <d-cite key="nerc2020sri"></d-cite> is a daily metric where transmission loss, generation loss, and load loss events aggregate into a single value that indicates performance of the BES. The SRI values range from zero to 1000. Zero is a theoretical condition where no transmission, generation or load loss occurred during the entire day. To the corollary, a value of 1000 would represent a situation where every transmission, generation and load5 was lost during the entire day. The SRI was designed to be usable for the entirety of NERC as well as applied more granularly, such as at an interconnection level.

The SRI provides a quantitative measure that assesses the relative severity of the combined impact of load, generation, and transmission loss on the BPS daily and offers a comprehensive picture of the performance of the BPS, allowing NERC to assess year-on-year reliability trends. <d-cite key="nerc2024sor"></d-cite>

## Resilience

**_Resilience_** <d-cite key="nerc2018resilience"></d-cite> **_FERC_** proposed to define resilience as, the ability to withstand and reduce the magnitude and/or duration of disruptive events, which includes the capability to anticipate, absorb, adapt to, and/or rapidly recover from such an event.

Some definitions of resilience <d-cite key="chiu2020resilience"></d-cite>:

FERC: The ability to withstand and reduce the magnitude and/or duration of disruptive events, which includes the capability to anticipate, absorb, adapt to, and/or rapidly recover from such event.

DOE: The ability of a power system and its components to withstand and adapt to disruptions and rapidly
recover from them.

NATF: The ability of the system and its components (i.e., both the equipment and human components) to minimize damage and improve recovery from non-routine disruptions, including high impact, low frequency (HILF) events, in a reasonable amount of time.

The IEEE Technical Report PES-TR65 and FERC Docket No. AD18-7-000 defines resilience as “The ability to withstand and reduce the magnitude and/or duration of disruptive events, which includes the capability to anticipate, absorb, adapt to, and/or rapidly recover from such an event.”

**_Storm resilience metric_** by IEEE <d-cite key="chiu2020resilience"></d-cite> This metric focuses on the speed of system recovery and is designed to capture the reduction of the number of customers without power for more than 12 hours from the time the customer loses power during a storm event. The metric will consider the instances of customer service interruptions that have been restored automatically without requiring human intervention to capture the value of technology solutions such as distribution automation, advanced distribution management system (ADMS), or microgrids, that minimize customer impacts. It will measure the number of reportable storms where recovery is favorable to threshold values divided by the total number of reportable storms.

**_Non-Storm Resilience Metric_** by IEEE <d-cite key="chiu2020resilience"></d-cite> This metric focuses on robustness and the ability to withstand events. It is designed to capture the total number of gray sky days (GSD) in a calendar year with no more than the threshold value of customer interruptions. The metric is measured in a percentage of GSDs that does not exceed the threshold value. The threshold value varies by utility size and is defined as the percentage of customer interruptions over the total customer base (e.g.,0.375% of the total number of customers). GSD excludes any calendar day with at least one reportable storm-related outage.

**_Multi-criteria decision analysis (MCDA)-based metrics_** by DOE GMLC <d-cite key="chiu2020resilience"></d-cite>: MCDA metrics generally try to answer the question,
“what is the current state of the electric system’s resilience, and what enhances its resilience over time?” These metrics can be used to assess the system’s baseline resilience relative to other systems. They typically include categories of system properties beneficial to resilience, such as robustness, resourcefulness, adaptivity, and recoverability. The application of these metrics requires following a process to review to what degree these properties are present within the system under analysis. This usually involves collecting data through surveys, developing weighting factors, and performing calculations to obtain numerical scores. MCDA metrics are used to calculate a resilience index (RI) that accounts for about 1,200 attributes grouped in 350 categories to characterize system resilience.

**_Performance-based metrics_** by DOE GMLC <d-cite key="chiu2020resilience"></d-cite>: performance-based metrics (also known as **_consequence-based metrics_**) are
generally quantitative approaches for answering the question, “How resilient is my system?” These metrics interpret quantitative data that describe infrastructure performance during disruptive events. The required data can be collected from historical events, subject matter estimates, and computational infrastructure models. These metrics are suitable for benefit-cost and planning analyses because they measure the potential benefits and costs associated with proposed resilience improvements and investments. Resilience metrics need to include a measure of consequences and the relevant statistical probability from the probability distribution of those consequences.

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
  <img src="/assets/img/poster/PJM_zone_map.png" alt="PJM Zone Map" style="width: 700px; height: auto;">
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
  <img src="/assets/img/poster/six_region.png" alt="Regional Maps" style="width: 700px; height: auto;">
  <p><em>Regional Maps (from <d-cite key="nerc2024tpl"></d-cite>) </em></p>
</div>

## Change Log

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
