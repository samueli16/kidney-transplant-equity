#  Socioeconomic Disparities in Kidney Transplantation
Georgia Tech OMSA Applied Practicum · Sponsor: Mickey Dale Family Foundation Team: Elizabeth Samuel, Kevin Yu, Joshua Roach

**Data note:** This analysis uses Scientific Registry of Transplant Recipients (SRTR) Standard Analysis Files. The data is available through the SRTR under a data use agreement and is not included in this repository.

## Overview

Getting a kidney transplant isn't one decision. It's a series of hurdles: getting referred, getting on the waitlist, staying active on it, and finally receiving an organ. Our sponsor wanted to know whether race and insurance status independently predict how far patients get, even after accounting for how sick they are.

We also compared patients listed before and after the 2022 race-neutral eGFR mandate, which removed a race-based adjustment that had made Black patients' kidney disease look less severe than it was.

## My role

I worked on a three-person team where each of us owned one stage of the pipeline, and together we built the cross-stage synthesis. I owned Stage 4, transplant receipt: data cleaning, merge strategy, feature engineering, modeling, sensitivity analysis, and visualizations. I also wrote the data, methods, and results sections for that stage.

## Data
- SRTR Standard Analysis Files covering every U.S. kidney waitlist candidate and transplant recipient (`cand_kipa`, `tx_ki`)
- Restricted to listings after the December 2014 Kidney Allocation System reform, so all records fall under the same allocation rules
- Kidney-only registrations (kidney-pancreas and pancreas-alone listings excluded)
- About 370,000 patients with known outcomes in the Stage 4 analysis

