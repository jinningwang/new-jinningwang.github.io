---
layout: post
title: Power Systems Wiki
date: 2024-12-11 10:00:00
description: Some terminology for my own reference.
tags: [frequency, terminology, NERC, power-systems]
categories: blog
thumbnail:
featured: true
giscus_comments: true
toc:
  sidebar: true
---

# Acronyms

|---------|-------------------------------------------------|
| BES | Bulk Electric System |
| BPS | Bulk Power System |
| HVDC | High Voltage Direct Current |
| FACTS | Flexible Alternating Current Transmission System|
| IBR | Inverter-Based Resources |
| DER | Distributed Energy Resources |
| GSF | Generator Shift Factor |

# Terminology

## Power Grids

---

**_Balancing Authorities_** The responsible entity that integrates resource plans ahead of time, maintains Demand and resource balance within a Balancing Authority Area, and supports Interconnection frequency in real time. [1]

---

**_Interconnection_** A geographic area in which the operation of BPS components is synchronized such that the failure of one or more of such components may adversely affect the ability of the operators of other components within the system to maintain Reliable Operation of the Facilities within their control. When capitalized, any one of the four major electric system networks in North America: Eastern, Western, ERCOT and Quebec. [1]

---

**_Bulk-Power System (BPS)_** (A) facilities and control systems necessary for operating an interconnected electric energy transmission network (or any portion thereof); and (B) electric energy from generation facilities needed to maintain transmission system reliability.
The term **does not** include facilities used in the local distribution of electric energy. (Note that the terms “Bulk-Power System” or “Bulk Power System” shall have the same meaning.) [1]

---

**_Bulk Electric System (BES)_** Unless modified by the lists shown below, all Transmission Elements operated at **100 kV or higher** and Real Power and Reactive Power resources connected at 100 kV or higher. This **does not** include facilities used in the local distribution of electric energy. [1]

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

---

**_Distribution Provider_** Provides and operates the “wires” between the transmission system and the end-use customer. For those end-use customers who are served at transmission voltages, the Transmission Owner also serves as the Distribution Provider. Thus, theDistribution Provider is not defined by a specific voltage, but rather as performing the distribution function at any voltage. [1]

---

**_Economic Dispatch_** The allocation of demand to individual generating units on line to effect the most economical production of electricity. [1]

---

## Generation

---

**_Inverter-based resources_** refer generally to BPS-connected facilities that have a power electronic interface between the ac grid and
the source of electricity [12].

Following two Q&A are from Reference [12].

**What types of IBR exist?**

Inverter-based resources include modern wind turbines, meaning type 3 and type 4 wind turbines, solar photovoltaic, and battery energy storage resources, as well as HVDC circuits and FACTs devices like static synchronous compensators and static volt-ampere reactive compensators.

**What is the difference between IBR and DER?**

- DER are generating resources located on the **distribution** system.
- DER **may or may not** use inverter technology to interface with the ac grid; however, they are distinctly different than BPS-connected inverter-based resources (connected to transmission and sub-transmission levels).

---

**_Generator Shift Factor (GSF)_** A factor to be applied to a generator’s expected change in output to determine the amount of flow contribution that change in output will impose on an identified transmission facility or Flowgate. [1]

---

## Transmission

---

**_Flowgate_** 1. A portion of the Transmission system through which the Interchange Distribution Calculator calculates the power flow from Interchange Transactions. 2. A mathematical construct, comprised of one or more monitored transmission Facilities and optionally one or more contingency Facilities, used to analyze the impact of power flows upon the Bulk Electric System.

---

**_Interchange_** Energy transfers that cross Balancing Authority boundaries. [1]

---

## Markets

---

**_Market_** A venue where participants buy and sell products or services. Usually there is agreement of product description and some standard terms to enable determination of value and price. [6]

---

**_Market power_** The ability of any market participant with a large market share to significantly control or affect price by withholding production from the market, limiting service availability, or reducing purchases. [6]

---

**_Market structure_** The rules, mechanisms and processes, under which a market operates to form prices, provide benefits and introduce risks to participants, and ultimately end consumers. Structure could enhance or inhibit competition, create just and reasonable outcomes, provide economically efficient incentives, or introduce unintended consequences including adverse market outcomes. [6]

---

**_Capacity markets_** A market for the trading of capacity credits (the ability to produce electricity in the market area during a defined period) usually between parties obligated to deliver electricity to customers and power plant owners. [6]

---

**_Day-ahead markets_** Forward markets for electricity to be supplied the following day. This market closes with acceptance by the independent system operator, power exchange, or scheduling coordinator of the final day-ahead schedule. Day-ahead is not a term commonly used for natural gas (“next day” is more common). [6]

---

**_Financial markets_** Markets where financially settled products (instruments) are traded (bought and sold). In commodity markets, it is markets where financially settled commodity derivatives are traded. Nymex is purely financial, where any residual delivery obligations on the futures contracts are matched and settled physically off-exchange by the matched parties. ICE trades both physically and financially settled products. Brokers also do both physical and financial transactions. Financial markets are also a term used for capital markets where stocks, bonds, T-Bills, foreign exchange and other financial instruments are traded. [6]

---

**_Futures market_** A market in which contracts for future delivery of a commodity or a security are bought and sold. Nymex is the primary futures market for energy commodities in the United States. [6]

---

**_Spot market_** The natural gas market for contractual commitments that are short term (usually a month or less) and that begin in the near future (often the next day, or within days). In electricity, spot markets are usually organized markets for day-ahead and real-time electricity run by an independent system operator or regional transmission organization. [6]

---

**_Wholesale electricity markets_** The purchase and sale of electricity from **generators to resellers** (who sell to retail customers) along with the ancillary services needed to maintain reliability and power quality at the transmission level. [6]

---

**_Financial transmission right_** A contract that entitles the holder to receive or pay compensation for transmission charges that arise when grid congestions cases price differences due to the redispatch of generators. [6]

---

**_Marginal electric generating unit_** In organized wholesale markets, the price of the marginal source of electricity usually sets the price of the unit providing the next increment or decrement of energy, which price usually sets the price for all generation. [6]

---

**_Bilateral transaction_** A direct contract between a seller and buyer outside of a centralized market or exchange (e.g. Nymex or an RTO/ISO). In energy markets, the buyer or seller usually finds his or her matching counter-party through a broker (e.g. voice brokers, ICE, etc.).

---

**_Zonal price_** A pricing mechanism for a **specific zone** within a **control area**.

---

## Ancillary Services

---

**_Ancillary services_** Those services necessary to support the transmission of electric power from seller to purchaser, given the obligations of control areas and transmitting utilities within those control areas, to maintain reliable operations of the interconnected transmission system. Ancillary services supplied with generation include load following, reactive power-voltage regulation, system protective services, loss compensation service, system control, load dispatch services, and energy imbalance services. [6]

More details about this can be found in Reference [7] - Appendix I: Regional Practices for Ancillary Services

---

## Frequency

---

**_Frequency Deviation_** A change in Interconnection frequency. [1]

---

**_Frequency Regulation_** The ability of a Balancing Authority to help the Interconnection maintain Scheduled Frequency. This assistance can include both turbine governor response and Automatic Generation Control. [1]

---

**_Frequency Response_** (Equipment) The ability of a system or elements of the system to react or respond to a change in system frequency. (System) The sum of the change in demand, plus the change in generation, divided by the change in frequency, expressed in megawatts per 0.1 Hertz (MW/0.1 Hz). [1]

---

**_Frequency Response Measure_** The median of all the Frequency Response observations reported annually by Balancing Authorities or Frequency Response Sharing Groups for frequency events specified by the ERO. This will be calculated as MW/0.1Hz. [1]

---

**_Area Control Error (ACE)_** Means the instantaneous difference between net actual and scheduled interchange, taking into account the effects of Frequency Bias including correction for meter error. [1]

The mismatch between demand and generation is represented via a real-time value called **_area control error (ACE)_**, estimated in MW. [2]

---

**_Automatic Generation Control (AGC)_** Means equipment that automatically adjusts a Control Area’s generation from a central location to maintain its interchange schedule plus Frequency Bias. [1]

**_Automatic Generation Control (AGC)_** The automatic regulation of the power output of electric generators within a prescribed range in response to a change in system frequency, or tie-line loading, to maintain system frequency or scheduled interchange with other areas within predetermined limits. [6]

---

**_Primary Frequency Response_** The immediate proportional increase or decrease in real power output provided by generating units/generating facilities and the natural real power dampening response provided by Load in response to system Frequency Deviations. This response is in the direction that stabilizes frequency. [1]

---

**_Ramp Rate or Ramp_** (Schedule) The rate, expressed in megawatts per minute, at which the interchange schedule is attained during the ramp period. (Generator) The rate, expressed in megawatts per minute, that a generator changes its output. [1]

---

**_Response Rate_** The Ramp Rate that a generating unit can achieve under normal operating conditions expressed in megawatts per minute (MW/Min). [1]

---

**_Primary Control_** is more commonly known as **_Frequency Response_**. Frequency Response occurs within the first few seconds following a change in system frequency (disturbance) to stabilize the Interconnection. [2]

---

**_Secondary Control_** typically includes the balancing services deployed in the “minutes” time frame. Some resources however, such as hydroelectric generation, can respond faster in many cases. This control is accomplished using the Balancing Authority’s control computer (terms most often associated with this are **“Load-Frequency Control”** or **“Automatic Generation Control”**) and the manual actions taken by the dispatcher to provide additional adjustments. Secondary Control also includes initial reserve deployment for disturbances.

In short, **_Secondary Control_** maintains the minute-to-minute balance throughout the day and is used to restore frequency to its scheduled value, usually 60 Hz, following a disturbance. Secondary Control is provided by both **Spinning** and **Non-Spinning Reserves**. [2]

<div style="text-align: ;left;">
  <img src="/assets/img/poster/frequency_trend.png"
  alt="Typical Frequency Trend for the Loss of a Generating Resource"
  style="width: 700px; height: auto;">
  <p><em>
    Typical Frequency Trend for the Loss of a Generating Resource (from [2]).
     Point A is defined as the pre-disturbance frequency;
     Point C or Nadir is the maximum deviation due to loss of resource;
     Point B is defined as the stabilizing frequency and;
     Point D is the time the contingent BA begins the recovery from the loss of resource.
  </em></p>
</div>

---

**_Tertiary Control_** encompasses actions taken to get resources in place to handle current and future contingencies. Reserve deployment and Reserve restoration following a disturbance are common types of Tertiary Control. [2]

---

**_Control Performance Standard 1 (CPS1)_** is a **yearly** standard that measures impact on frequency error, with a 100 percent minimum allowable score. CPS1 assigns each Control Area a share of the responsibility for control of Interconnection frequency. [2]

**_Control Performance Standard 2 (CPS2)_** is a **monthly** standard intended to limit unscheduled flows. The minimum allowable CPS2 score is 90 percent. [2]

## Reserve

---

**_Spinning Reserve_** Unloaded generation that is synchronized and ready to serve additional demand. [1]

---

**_Non-Spinning Reserve_** 1. That generating reserve **not connected** to the system but capable of serving demand **within a specified time**. 2. Interruptible load that can be removed from the system in a specified time. [1]

---

**_Operating Reserve_** That capability above firm system demand required to provide for regulation, load forecasting error, equipment forced and scheduled outages and local area protection. It consists of spinning and non-spinning reserve. [1]

---

**_Operating Reserve – Spinning_** The portion of Operating Reserve consisting of: • Generation synchronized to the system and fully available to serve load within the Disturbance Recovery Period following the contingency event; or • Load fully removable from the system within the Disturbance Recovery Period following the contingency event. [1]

---

**_Operating Reserve – Supplemental_** The portion of Operating Reserve consisting of: • Generation (synchronized or capable of being synchronized to the system) that is fully available to serve load within the Disturbance Recovery Period following the contingency event; or • Load fully removable from the system within the Disturbance Recovery Period following the contingency event. [1]

---

**_Regulating Reserve_** An amount of reserve responsive to Automatic Generation Control, which is sufficient to provide normal regulating margin. [1]

---

**_Contingency Reserve_** The provision of capacity deployed by the Balancing Authority to meet the Disturbance Control Standard (DCS) and other NERC and Regional Reliability Organization contingency requirements. [1]

<div style="text-align: ;left;">
  <img src="/assets/img/poster/operating_reserve.png" alt="Operating Reserves" style="width: 700px; height: auto;">
  <p><em>Operating Reserves (from [1]) </em></p>
</div>

---

## Reliability, Security, and Stability

---

**_Stability Limit_** The maximum power flow possible through some particular point in the system while maintaining stability in the entire system or the part of the system to which the stability limit refers. [1]

---

**_Interconnection Reliability Operating Limit_** A System Operating Limit that, if violated, could lead to instability, uncontrolled separation, or Cascading outages that adversely impact the reliability of the Bulk Electric System. [1]

---

**_Interconnection Reliability Operating Limit Tv_** **The maximum time** that an Interconnection Reliability Operating Limit can be violated before the risk to the interconnection or other Reliability Coordinator Area(s) becomes greater than acceptable. Each Interconnection Reliability Operating Limit’s Tv shall be less than or equal to 30 minutes. [1]

---

**_Reliability_** of a power system refers to the probability of its satisfactory operation over the long run. It denotes the ability to supply adequate electric service on a nearly continuous basis, with few interruptions over an extended time period. [3]

---

**_Security_** of a power system refers to the degree of risk in its ability to survive imminent disturbances (contingencies) without interruption of customer service. It relates to robustness of the system to imminent disturbances and, hence, depends on the system operating condition as well as the contingent probability of disturbances. [3]

---

**_Stability_** The ability of an electric system to maintain a state of equilibrium during normal and abnormal conditions or disturbances. [1]

**_Stability_** is the ability of an electric power system, for a given initial operating condition, to regain a state of operating equilibrium after being subjected to a physical disturbance, with most system variables bounded so that practically the entire system remains intact. [4]

**_Stability_** of a power system refers to the continuance of intact operation following a disturbance. It depends on the operating condition and the nature of the physical disturbance. [3]

Their relationships [3]:

1. Reliability is the overall objective in power system design and operation. To be reliable, the power system must be secure most of the time. To be secure, the system must be stable but must also be secure against other contingencies that would not be classified as stability problems e.g., damage to equipment such as an explosive failure of a cable, fall of transmission towers due to ice loading or sabotage. As well, a system may be stable following a contingency, yet insecure due to post-fault system conditions resulting in equipment overloads or voltage violations.
1. System security may be further distinguished from stability in terms of the resulting consequences. For example, two systems may both be stable with equal stability margins, but one may be relatively more secure because the consequences of instability are less severe.
1. Security and stability are time-varying attributes which can be judged by studying the performance of the power system under a particular set of conditions. Reliability, on the other hand, is a function of the time-average performance of the power system; it can only be judged by consideration of the system’s behavior over an appreciable
   period of time.

---

### Stability

---

**_Rotor angle stability_** is concerned with the ability of the interconnected synchronous machines in a power system to remain in synchronism under normal operating conditions and to regain synchronism after being subjected to a small or large disturbance. [4]

---

**_Voltage stability_** refers to the ability of a power system to maintain steady voltages close to nominal value at all buses in the system after being subjected to a disturbance. [4]

---

**_Frequency stability_** refers to the ability of a power system to maintain steady frequency following a severe system upset resulting in a significant imbalance between generation and load. [3]

---

There are also two categories of stability: **_Resonance Stability_** and **_Converter-driven Stability_**. [3]

---

## Reliability

---

**_Reliability_** NERC defines the reliability of the interconnected Bulk-Power System in terms of two basic and functional aspects, adequacy, and operating reliability [11].

---

**_Adequacy_** The ability of the electricity system to supply the aggregate electrical demand and energy requirements of the end-use customers at all times, taking into account scheduled and reasonably expected unscheduled outages of system elements [11].

---

**_Operating Reliability_** The ability of the Bulk-Power System to withstand sudden disturbances, such as electric short circuits or the unanticipated loss of system elements from credible contingencies, while avoiding uncontrolled cascading blackouts or damage to equipment [11].

---

**_Interruptible demand_** Customer demand that, in accordance with contractual arrangements, can be interrupted by direct control of the system operator or by action of the customer at the direct request of the system operator [11].

---

**_Voltage reductions_** This is also referred to as “brownouts” because lights dim as voltage is lowered [11].

---

**_Rotating blackouts_** when each set of distribution feeders is interrupted for a limited time, typically 20–30 minutes, and then those feeders are put back in service and another set is interrupted, and so on, rotating the outages among individual feeders [11].

---

## Events

---

**_Contingency_** The unexpected failure or outage of a system component, such as a generator, transmission line, circuit breaker, switch or other electrical element. [1]

---

**_Most Severe Single Contingency_** The Balancing Contingency Event, due to a single contingency identified using system models maintained within the Reserve Sharing Group (RSG) or a Balancing Authority’s area that is not part of a Reserve Sharing Group, that would result in **the greatest loss** (measured in MW) of resource output used by the RSG or a Balancing Authority that is not participating as a member of a RSG at the time of the event to meet Firm Demand and export obligation (excluding export obligation for which Contingency Reserve obligations are being met by the Sink Balancing Authority). [1]

---

**_Disturbance_** Means (i) any perturbation to the electric system, or (ii) the unexpected change in ACE that is caused by the sudden loss of generation or interruption of load. [1]

---

**_Fault_** An event occurring on an electric system such as a short circuit, a broken wire, or an intermittent connection. [1]

## Horizon

---

**_Near-Term Transmission Planning Horizon_** The transmission planning period that covers Year One through five. [1]

---

**_Long-Term Transmission Planning Horizon_** Transmission planning period that covers years six through ten or beyond when required to accommodate any known longer lead time projects that may take longer than ten years to complete. [1]

---

## Factors

---

**_Outage Transfer Distribution Factor (OTDF)_** In the post-contingency configuration of a system under study, the electric Power Transfer Distribution Factor (PTDF) with one or more system Facilities removed from service (outaged). [1]

---

**_Participation Factors_** A set of dispatch rules such that given a specific amount of load to serve, an **approximate generation** dispatch can be determined. To accomplish this, generators are assigned a percentage that they will contribute to serve load. [1]

---

## Area, Zone, and Region

---

**_Balancing Authority Area_** The collection of generation, transmission, and loads within the metered boundaries of the Balancing Authority. The Balancing Authority maintains load-resource balance within this area. [1]

---

**_Reliability Coordinator Area_** The collection of generation, transmission, and loads within the boundaries of the Reliability Coordinator. Its boundary coincides with one or more Balancing Authority Areas. [1]

---

**_Control area_** An electric power system or combination of electric power systems to which a common automatic control scheme is applied in order to [6]:

- Match, at all times, the power output of the generators within the electric power system(s) and capacity and energy purchased from entities outside the electric power system(s), with the load in the electric power system(s).
- Maintain, within the limits of Good Utility Practice, scheduled interchange with other Control Areas.
- Maintain the frequency of the electric power system(s) within reasonable limits in accordance with Good Utility Practice.
- Provide sufficient generating capacity to maintain operating reserves in accordance with Good Utility Practice.

---

**_loss_zone_** In MATPOEWR, there is a bus parameter named "ZONE", and it means loss zone. [9]

**_Zone_** There is no clear definition, but my best guess is that it refers to different areas within the Bulk-Power System.

<div style="text-align: ;left;">
  <img src="/assets/img/poster/PJM_zone_map.png" alt="PJM Zone Map" style="width: 700px; height: auto;">
  <p><em>PJM Transmission Zones Map (from [10]) </em></p>
</div>

---

**_Region_** NERC divides North America into several regions for the purpose of reliability and coordination. Each region is responsible for ensuring the reliability of the bulk power system within its boundaries [8]. The six regions are:

- MRO: Midwest Reliability Organization
- NPCC: Northeast Power Coordinating Council
- RF: ReliabilityFirst
- SERC: SERC Reliability Corporation
- Rexas RE: Texas Reliability Entity
- WECC: Western Electricity Coordinating Council

<div style="text-align: ;left;">
  <img src="/assets/img/poster/six_region.png" alt="Regional Maps" style="width: 700px; height: auto;">
  <p><em>Regional Maps (from [8]) </em></p>
</div>

---

# Change Log

## 2024-12-17

- Add Reliability section
- Add Generation section
- Add acronyms table

## 2024-12-12

- Add ancillary services and AGC by FERC
- Add AGC by FERC
- Add Market section

## 2024-12-11

- Initial post

# References

[1] North American Electric Reliability Corporation, "Glossary of Terms Used in NERC Reliability Standards," Nov. 4, 2024. [Online]. Available: https://www.nerc.com/pa/Stand/Glossary%20of%20Terms/Glossary_of_Terms.pdf

[2] North American Electric Reliability Corporation, "Balancing and Frequency Control Reference Document," Jan. 26, 2021. [Online]. Available: https://www.nerc.com/comm/RSTC_Reliability_Guidelines/Reference_Document_NERC_Balancing_and_Frequency_Control.pdf

[3] P. Kundur et al., "Definition and classification of power system stability IEEE/CIGRE joint task force on stability terms and definitions," in IEEE Transactions on Power Systems, vol. 19, no. 3, pp. 1387-1401, Aug. 2004, doi: 10.1109/TPWRS.2004.825981.

[4] N. Hatziargyriou et al., "Definition and Classification of Power System Stability – Revisited & Extended," in IEEE Transactions on Power Systems, vol. 36, no. 4, pp. 3271-3281, July 2021, doi: 10.1109/TPWRS.2020.3041774.

[5] North American Electric Reliability Corporation, "Reliability Guideline - Operating Reserve Management: Version 3," Jun. 8, 2021. [Online]. Available: https://www.nerc.com/comm/RSTC_Reliability_Guidelines/Reliability_Guideline_Template_Operating_Reserve_Management_Version_3.pdf

[6] Federal Energy Regulatory Commission, “Glossary,” Market Assessments. Accessed: Aug. 31, 2020. [Online]. Available: https://www.ferc.gov/industries-data/market-assessments/overview/glossary

[7] North American Electric Reliability Corporation, "Ancillary Service and Balancing Authority Area Solutions to Integrate Variable Generation," Mar. 2011. [Online]. Available: https://www.nerc.com/pa/RAPA/ra/Reliability%20Assessments%20DL/IVGTF2-3.pdf

[8] North American Electric Reliability Corporation, "Technical Rationale and Justification for TPL-008-1,", Oct. 2024. [Online]. Available: https://www.nerc.com/pa/Stand/Project202307ModtoTPL00151TransSystPlanPerfReqExWe2023-07_TPL-008-1%20Technical%20Rationale%20-%20Draft_3_100724.pdf

[9] MATPOWER, "MATPOWER User’s Manuals," https://matpower.org/doc-original/manuals/

[10] PJM, "Transmission Zones Map," https://www.pjm.com/-/media/DotCom/about-pjm/pjm-zones.pdf

[11] North American Electric Reliability Corporation, "Reliability Terminology," Aug., 2013. [Online]. Available: https://www.nerc.com/AboutNERC/Documents/Terms%20AUG13.pdf

[12] An Introduction to Inverter-based Resources on the Bulk Power System," Jun. 2023. [Online]. Available: https://www.nerc.com/pa/Documents/2023_NERC_Guide_Inverter-Based-Resources.pdf
