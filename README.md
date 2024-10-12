# **Oracle Crystal Ball Monte Carlo Simulation Project Report**

**Project Overview**

This project focuses on evaluating the potential market entry for ONC Inc., a private company specializing in oncology patient treatment, into the Kentucky market, specifically south of Louisville. The leadership at ONC Inc. aims to determine if there is sufficient demand for infusion services among newly diagnosed cancer patients to justify investment.

**Problem Statement**

ONC Inc. was considering entering a market where an estimated 30,630 new cancer cases will be diagnosed in Kentucky in 2024, with a total population of approximately 4,526,154. The company needs to analyze various factors, including market share, patient treatment requirements, and infusion visit projections, to make an informed investment decision.

**Methodology**

A Monte Carlo simulation was conducted using Oracle Crystal Ball to assess the feasibility of ONC Inc.'s entry into the Kentucky market based on different market share assumptions and patient demand estimates.

**Key Variables**

**New Cancer Cases:** Estimated total for Kentucky in 2024 is 30,630.
**Market Share:** Assumed at 20% initially, later adjusted to 30%.
**Percentage of Patients Requiring Infusion:** Estimates range from 50% (minimum) to 85% (maximum), with a likeliest estimate of 75%.
**Average Number of Treatments per Patient:** Estimates range from 8 (minimum) to 20 (maximum), with a likeliest estimate of 10.
**Minimum Infusion Visits Requirement:** ONC Inc. needs at least 4,000 infusion visits per year to ensure profitability.

**Simulation Model**

The model calculates the total annual infusion visits using the formula:

Total Annual Infusion Visits = New Cancer Cases × Average Percentage Requiring Infusion × Average Treatments per Patient × Market Share

**Results**

**Model Quality**

The base model was assessed based on its construction and logical flow. The supporting Excel file provided detailed outputs from the simulation.

**Investment Decision at 20% Market Share**

The Monte Carlo simulation results indicated only a 14.6% certainty of achieving the minimum required 4,000 infusion visits per year at a 20% market share. Given this low certainty, ONC Inc. should not invest in the south Louisville area.

**Forecast Results at 20% Market Share:**

Trials: 10,000
Certainty: 14.60%
Selected Range: From 4,000 to ∞

**Investment Decision at 30% Market Share**

At a 30% market share, the simulation results showed an 83.33% certainty of achieving the required infusion visits. While this represents an improvement over the 20% scenario, it still falls below the 90% certainty threshold set by the CEO. Therefore, ONC Inc. should not pursue investment at this level.

**Forecast Results at 30% Market Share:**

Trials: 10,000
Certainty: 83.33%
Selected Range: From 4,000 to ∞

**Recommendations for Market Share Improvement**

The simulation results indicate that achieving a 32% market share yields a 91.17% certainty of meeting the infusion visit requirement, while a 35% market share increases certainty to 97.13%. ONC Inc. should assess strategies to realistically achieve and maintain a market share in this range.

**Forecast Results:**

At 32% Market Share:
Certainty: 91.17%
At 35% Market Share:
Certainty: 97.13%

**Recommendations**

**Market Share Assessment:** Conduct a thorough analysis to understand how ONC Inc. can realistically achieve the target market share of 32-35%.
**Review Assumptions:** Reassess assumptions regarding the percentage of cancer patients requiring infusion services and the average number of treatments per patient, as slight changes can significantly impact results.
**Explore New Regions:** Identify regions with higher cancer incidences or increasing trends and consider including them in the market analysis.
**Partnerships:** Form partnerships with local healthcare providers to increase market share.
**Competition Analysis:** Continuously reassess competition and adjust operational strategies to improve profitability.

**Conclusion**

The Monte Carlo simulation provided valuable insights into the viability of ONC Inc.'s potential market entry into Kentucky. The company should proceed with caution and reassess key factors that could influence its market share and demand for infusion services. By implementing strategic adjustments based on simulation insights, ONC Inc. can position itself for successful expansion in the future.
