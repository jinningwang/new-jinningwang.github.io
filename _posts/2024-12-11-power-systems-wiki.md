---
layout: post
title: Power Systems Wiki
date: 2024-12-11 10:00:00
description: Some terminology for my own reference.
tags: [frequency, terminology, NERC]
categories: blog
thumbnail:
featured: false
giscus_comments: true
toc:
  sidebar: true
---

# Terminology

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

**_Ancillary services_** Those services necessary to support the transmission of electric power from seller to purchaser, given the obligations of control areas and transmitting utilities within those control areas, to maintain reliable operations of the interconnected transmission system. Ancillary services supplied with generation include load following, reactive power-voltage regulation, system protective services, loss compensation service, system control, load dispatch services, and energy imbalance services. [6]

More details about this can be found in Reference [7] - Appendix I: Regional Practices for Ancillary Services

---

## Frequency

**_Frequency Deviation_** A change in Interconnection frequency. [1]

---

**_Frequency Regulation_** The ability of a Balancing Authority to help the Interconnection maintain Scheduled Frequency. This assistance can include both turbine governor response and Automatic Generation Control. [1]

---

**_Frequency Response_** (Equipment) The ability of a system or elements of the system to react or respond to a change in system frequency. (System) The sum of the change in demand, plus the change in generation, divided by the change in frequency, expressed in megawatts per 0.1 Hertz (MW/0.1 Hz). [1]

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
    Typical Frequency Trend for the Loss of a Generating Resource (copied from [2]).
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

## Entities

**_Balancing Authorities_** The responsible entity that integrates resource plans ahead of time, maintains Demand and resource balance within a Balancing Authority Area, and supports Interconnection frequency in real time. [1]

---

**_Interconnection_** A geographic area in which the operation of Bulk Power System components is synchronized such that the failure of one or more of such components may adversely affect the ability of the operators of other components within the system to maintain Reliable Operation of the Facilities within their control. When capitalized, any one of the four major electric system networks in North America: Eastern, Western, ERCOT and Quebec. [1]

---

**_Reliability Coordinator Area_** The collection of generation, transmission, and loads within the boundaries of the Reliability Coordinator. Its boundary coincides with one or more Balancing Authority Areas.

---

**_Interchange_** Energy transfers that cross Balancing Authority boundaries. [1]

---

## Reserve

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
  <p><em>Operating Reserves (from referenced document) </em></p>
</div>

---

## Reliability, Security, and Stability

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

**_Rotor angle stability_** is concerned with the ability of the interconnected synchronous machines in a power system to remain in synchronism under normal operating conditions and to regain synchronism after being subjected to a small or large disturbance. [4]

---

**_Voltage stability_** refers to the ability of a power system to maintain steady voltages close to nominal value at all buses in the system after being subjected to a disturbance. [4]

---

**_Frequency stability_** refers to the ability of a power system to maintain steady frequency following a severe system upset resulting in a significant imbalance between generation and load. [3]

---

There are also two categories of stability: **_Resonance Stability_** and **_Converter-driven Stability_**. [3]

---

## Contingency

**_Most Severe Single Contingency_** The Balancing Contingency Event, due to a single contingency identified using system models maintained within the Reserve Sharing Group (RSG) or a Balancing Authority’s area that is not part of a Reserve Sharing Group, that would result in **the greatest loss** (measured in MW) of resource output used by the RSG or a Balancing Authority that is not participating as a member of a RSG at the time of the event to meet Firm Demand and export obligation (excluding export obligation for which Contingency Reserve obligations are being met by the Sink Balancing Authority). [1]

---

**_Disturbance_** Means (i) any perturbation to the electric system, or (ii) the unexpected change in ACE that is caused by the sudden loss of generation or interruption of load. [1]

---

## Horizon

**_Near-Term Transmission Planning Horizon_** The transmission planning period that covers Year One through five. [1]

---

**_Long-Term Transmission Planning Horizon_** Transmission planning period that covers years six through ten or beyond when required to accommodate any known longer lead time projects that may take longer than ten years to complete. [1]

---

## Factors

**_Outage Transfer Distribution Factor (OTDF)_** In the post-contingency configuration of a system under study, the electric Power Transfer Distribution Factor (PTDF) with one or more system Facilities removed from service (outaged). [1]

---

**_Participation Factors_** A set of dispatch rules such that given a specific amount of load to serve, an **approximate generation** dispatch can be determined. To accomplish this, generators are assigned a percentage that they will contribute to serve load. [1]

---

## Area, Zone, and Region

**_Control area_** An electric power system or combination of electric power systems to which a common automatic control scheme is applied in order to [6]:
- Match, at all times, the power output of the generators within the electric power system(s) and capacity and energy purchased from entities outside the electric power system(s), with the load in the electric power system(s).
- Maintain, within the limits of Good Utility Practice, scheduled interchange with other Control Areas.
- Maintain the frequency of the electric power system(s) within reasonable limits in accordance with Good Utility Practice.
- Provide sufficient generating capacity to maintain operating reserves in accordance with Good Utility Practice.

---

**_Balancing Authority Area_** The collection of generation, transmission, and loads within the metered boundaries of the Balancing Authority. The Balancing Authority maintains load-resource balance within this area. [1]

---

# Change Log

- 12/12/2024: Add ancillary services by FERC, add AGC by FERC, add markets related terms
- 12/11/2024: Initial post

# References

[1] North American Electric Reliability Corporation, "Glossary of Terms Used in NERC Reliability Standards," Nov. 4, 2024. [Online]. Available: https://www.nerc.com/pa/Stand/Glossary%20of%20Terms/Glossary_of_Terms.pdf

[2] North American Electric Reliability Corporation, "Balancing and Frequency Control Reference Document," Jan. 26, 2021. [Online]. Available: https://www.nerc.com/comm/RSTC_Reliability_Guidelines/Reference_Document_NERC_Balancing_and_Frequency_Control.pdf

[3] P. Kundur et al., "Definition and classification of power system stability IEEE/CIGRE joint task force on stability terms and definitions," in IEEE Transactions on Power Systems, vol. 19, no. 3, pp. 1387-1401, Aug. 2004, doi: 10.1109/TPWRS.2004.825981.

[4] N. Hatziargyriou et al., "Definition and Classification of Power System Stability – Revisited & Extended," in IEEE Transactions on Power Systems, vol. 36, no. 4, pp. 3271-3281, July 2021, doi: 10.1109/TPWRS.2020.3041774.

[5] North American Electric Reliability Corporation, "Reliability Guideline - Operating Reserve Management: Version 3," Jun. 8, 2021. [Online]. Available: https://www.nerc.com/comm/RSTC_Reliability_Guidelines/Reliability_Guideline_Template_Operating_Reserve_Management_Version_3.pdf

[6] Federal Energy Regulatory Commission, “Glossary,” Market Assessments. Accessed: Aug. 31, 2020. [Online]. Available: https://www.ferc.gov/industries-data/market-assessments/overview/glossary

[7] North American Electric Reliability Corporation, "Ancillary Service and Balancing Authority Area Solutions to Integrate Variable Generation," Mar. 2011. [Online]. Available: https://www.nerc.com/pa/RAPA/ra/Reliability%20Assessments%20DL/IVGTF2-3.pdf
