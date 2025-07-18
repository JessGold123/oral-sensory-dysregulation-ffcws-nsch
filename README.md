# Oral Sensory Pathways and Emotion Dysregulation in Children

This repository contains a pre-analysis plan for a secondary data project examining the relationship between oral sensory behaviors and observable emotion dysregulation in children, with and without autism spectrum disorder (ASD). The project uses data from the **Fragile Families and Child Wellbeing Study (FFCWS)** and the **National Survey of Children’s Health (NSCH)**.

## Project Overview

Children with autism often show heightened reactivity to taste, texture, and other oral sensations. This sensory reactivity may contribute not only to selective eating, but also to broader emotion regulation difficulties. This project explores how early oral sensory behaviors, particularly during feeding, predict later emotion dysregulation, and whether this pathway is moderated by parenting behaviors and ASD diagnosis.

## Data Sources

- **FFCWS (Waves 3, 5, and 9)**  
  Used to track early feeding reactivity, parenting behaviors, and later emotion dysregulation in a large, diverse U.S. sample.
  
- **NSCH (2023)**  
  Used to replicate key associations and test moderation by ASD diagnosis.

## Aims

1. **Aim 1a:** Examine whether oral sensory reactivity during early feeding predicts observable emotion dysregulation at age 9.  
2. **Aim 1b:** Test whether parenting behaviors (e.g., harsh discipline, responsiveness) moderate this association.  
3. **Aim 2:** Evaluate whether the strength or direction of these pathways differs between children with and without an autism diagnosis.

## Files

- `OralSensoryPathways_Proposal_July_2025ASD.docx`  
  Full pre-analysis plan including background, aims, variable selection, analytic strategy, and embedded conceptual figures.

## Analysis Scripts

The `/analysis/` folder contains separate R scripts for each dataset used in this project:

- `ffcws_analysis.R` – Data cleaning, variable construction, and modeling for the Fragile Families and Child Wellbeing Study (FFCWS).
- `nsch_analysis.R` – Parallel pipeline for the National Survey of Children’s Health (NSCH) 2023 dataset.

Each script is structured to run independently but follows the logic outlined in the pre-analysis plan.

## Authorship

This project was developed by **Jess Goldschlager**, B.S., during their time as a Postbaccalaureate IRTA Fellow in the **Section on Sensory Science and Metabolism (SenSMet)** at the **National Institute on Alcohol Abuse and Alcoholism (NIAAA)**, NIH.  
Mentorship was provided by **Dr. Paule Joseph**.

## License

This repository is shared under a [CC-BY 4.0 License](https://creativecommons.org/licenses/by/4.0/). You are welcome to adapt or reuse content with attribution.

## Disclaimer

All views expressed here are those of the author and do not necessarily reflect the views of the National Institutes of Health.

