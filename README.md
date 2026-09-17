# REGIONAL MERCURY THREAT ASSESSMENT AND MONITORING IN THE AMAZON BASIN
## Evaluating Regional Patterns in Mercury Threat to Humans and Biota 

The Amazon Basin has been identified as a priority area for understanding patterns in mercury threat because it sits at the confluence of pervasive anthropogenic mercury emissions, releases, and remobilization driven by anthropogenic activities (e.g., Artisanal and Small-scale Gold Mining [ASGM], oil and gas infrastructure, deforestation, fire, dams) and ecosystems with characteristics and biogeochemical conditions (e.g., intact wetland forests, floodplains, blackwater river systems) that are conducive to mercury methylation. 

We implemented a Regional Mercury Threat Assessment (RMTA) framework across the Amazon Basin. Ultimately, the results of this threat assessment, when combined with efforts being driven by the Minamata Convention on Mercury and national regulations and policies, can inform strategies to reduce the adverse impacts from this persistent and ubiquitous threat to human and ecosystem health across the Amazon Basin.

This repository includes the spatial Regional Mercury Threat Assessment (RMTA) Version 1.0 layers for the Amazon Basin. 

The RMTA framework is designed to be adaptively refined. As future data becomes available, the RMTA will be updated to better reflected the conditions observed in the Amazon. 

### Contents of Data Folder
| Folder | File | Type | Description |
| --- | --- | --- | --- | 
|Amazon_RMTA.gpkg | amz_threat_20260912 | GeoPackage | Amazon Basin RMTA including: 1) ecosystem sensitivity to mercury methylation, 2) risk of mercury contamination from anthropogenic sources, and 3) threat of mercury impacts to human and ecosystem health 
| Field Samples | Amazon_Water-Quality Parameters_2026.xlsx | .xlsx | Ten water quality parameters measured across 51 points in Colombia, Ecuador, and Peru during July and August, 2026 | 


## Amazon RMTA 
### Data Dictionary
#### Amazon_RMTA.gpkg 
| Field | Type | Description |
| --- | --- | --- | 
| grid_id | text | Unique identifier for each Amazon RMTA grid cell |
| sensitivity_score | numeric | Relative sensitivity to mercury methylation - how likely mercury inputs are to enter the food web and adverse impacts |
| sensitivity_score_scale | numeric | sensitivity_score rescaled to 0-1 for visualization |
| risk_score | numeric | Relative risk of mercury contamination from anthropogenic sources - how much mercury is being input into a system |
| risk_score_scale | numeric | risk_score rescaled to 0-1 for visualization |
| threat_score | numeric | Equally weighted combination of sensitivity and risk - potential for adverse impacts on human and ecosystem health |
| threat_score_scale | numeric | threat_score rescaled to 0-1 for visualization |

Higher scores indicate relatively higher sensitivity, risk, or threat, respectively. 

### Notes 
1) All scores are relative within the Amazon RMTA and magnitudes are not comparable across other RMTAs or the Global Mercury Threat Assessment (RMTA)
2) The framework, including driver weights and input data, are expected to be refined as data becomes available.
3) Version 1.0 has not been validated with field measurements. It is expected to be soon.
4) The RMTA is intended to aid decision- and policy-makers designing targeted biomonitoring, conservation planning, and implementation of interventions and actions consistent with obligations under the Minamata Convention on Mercury.  

### Recommended Citation
Burton MEH, Vargas K. 2026. Regional Mercury Threat Assessment and Monitoring in the Amazon Basin: Evaluating Regional Patterns in Mercury Threat to Humans and Biota. Biodiversity Research Institute. Portland, Maine.

### Acknowledgements

_The initial mercury sensitivity mapping and subsequent Global Mercury Threat Assessment (GMTA) concepts were developed and supported by the Biodiversity Research Institute (BRI). Initial development of the Regional Mercury Threat Assessment (RMTA) framework received support from The Nature Conservancy (TNC), the US Department of State, and BRI. In particular, this report builds extensively on the 2026 RMTA framework developed in eastern Ecuador and funded by TNC. Continued development of the RMTA was funded by TNC, whose partnership was crucial in the evolution of the framework. The Amazon Basin RMTA was additionally supported, in part, by the Gordon and Betty Moore Foundation through Grant GBMF12201 to the Wildlife Conservation Society (WCS)._
