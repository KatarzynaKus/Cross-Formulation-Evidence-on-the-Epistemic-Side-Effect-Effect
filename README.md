# Cross-Formulation Evidence on the Epistemic Side-Effect Effect

This project investigates the Epistemic Side-Effect Effect (ESEE), which describes the tendency to attribute knowledge differently for negative versus positive foreseen side effects of an agent's action. Specifically, these studies examine how the linguistic formulation of the knowledge claim influences the magnitude of this effect. The project consists of two experiments that test the impact of three distinct phrasings of the knowledge question (agentive, causal, and change-of-state) on judgments in classic harm and help scenarios.

To test this, we designed two studies with a 2 (side effect: harm vs. help) × 3 (formulation: agentive, causal, standard) factorial design. Study 2a manipulated the formulation of the knowledge claim between-subjects, while Study 2b manipulated it within-subjects. Participants for both studies were recruited via Prolific. The studies included several dependent measures, primarily knowledge attribution on a 7-point Likert scale, binary intentionality judgments, and open-ended justifications for participants' responses.

The results robustly replicate the ESEE in both the between-subject and within-subject designs. The findings also reveal a significant effect of linguistic formulation on knowledge judgments, indicating that the way a knowledge question is phrased interacts with the moral valence of the side effect. This repository provides the data and analysis scripts necessary to reproduce all reported findings and allows for a direct comparison of between- and within-subject methodologies for studying the ESEE.

OSF PAGE: https://osf.io/your_unique_project_id/

## Citation

If you used the this dataset, please cite it as:

> Kuś, K., Maćkiewicz, B., Zaręba, M., & Paprzycka-Hausman, K. (2025). Cross-Formulation Evidence on the Epistemic Side-Effect Effect. https://doi.org/10.17605/OSF.IO/X8SED

## Structure of the repository
- `Study_2a`
	- `analysis`
  		- `analysis_2a.rmd` - script for cleaning data (produces `study2a_clean.csv` from raw dataset) and simple analyses; a short description of variables can be also found there
  		- `analysis_2a.html` - compiled report 
	- `data`
		- `demo/prolific_export_...csv` - demographic data provided by Prolific
		- `H[M|P]_[AG|PR|ST]results-...csv` - raw datasets 
	- `questionnaire` - materials for Study 2a
- `Study_2b`
	- `analysis`
  		- `analysis_2b.rmd` - script for cleaning data (produces `study2b_clean.csv` from raw dataset) and simple analyses; a short description of variables can be also found there
  		- `analysis_2b.html` - compiled report 
	- `data`
		- `demo/prolific_export_...csv` - demographic data provided by Prolific
		- `H[M|P]_3_[A|P|S][A|P|S][A|P|S]results-...csv` - raw datasets
	- `questionnaire` - materials for Study 2a

