# Characterising rocky intertidal biodiversity using environmental DNA metabarcoding from local to national scales

*Simons D-L, Hipperson H, Webb TJ, Spencer M, Mieszkowska N*

This GitHub repository contains data and R code for reproducing analyses presented in Simons et al 2025, "Characterising rocky intertidal biodiversity using environmental DNA metabarcoding from local to national scales". If you reuse any scripts or data in this project, please cite the paper.

> **Abstract:** Efficient and scalable methods for monitoring marine biodiversity are critical for understanding ecological change in coastal environments, given the limited resources available. Environmental DNA (eDNA) metabarcoding shows promise for monitoring coastal taxa, but its ability to differentiate communities from different locations remains insufficiently understood, particularly in dynamic marine environments. Here, we evaluate the effectiveness and resolution capacity of eDNA metabarcoding in detecting rocky intertidal taxa across three spatial scales – national, regional, and local - in the United Kingdom. Onshore surface-water samples were collected from 32 sites across five UK Regional Seas from rockpools in high and low shore zones, as well as directly from the sea. We detected 1026 target taxa within 441 families and 19 phyla using two established markers targeting invertebrates (COI) and macroalgae (18S). Distinct eDNA signals were found at all spatial scales, indicating local discreteness even between vertical shore heights within the same sites. Communities were more discrete at larger scales (i.e., between regions) than smaller scales (i.e., between shore heights). eDNA signals were more strongly structured by geographical location than by vertical shore height, as a probable consequence of greater DNA homogenisation over the tidal cycle at smaller spatial scales. Established ecological zonation patterns were reflected in eDNA signals, with higher richness at lower shore heights, reflecting abiotic stress gradients. Detections of cold-affinity boreal species increased with latitude, while warm-affinity Lusitanian species declined with latitude. Our work supports the utility of eDNA metabarcoding for multiscale biodiversity monitoring in dynamic marine environments and for detections beyond this study’s target taxa. We recommend the adoption of scale-appropriate sampling protocols to optimise the benefits of eDNA, such as prioritising open water sampling at high tide for broad-scale assessments, and rockpool sampling at low tide for capturing local-scale patterns. Future work should validate detections through direct visual comparisons.

## Repository Structure
Figures/ - Stores all figures produced from the analyses.

Input_Data/ - Contains raw data files used for analyse, including metadata, phyloseq object and long data.

Processed_Data/ - Stores processed data files used for analyses.

intertidal-eDNA-spatial-analyses.Rproj - RStudio project file to manage the project environment.

intertidal-eDNA-spatial-analyses.qmd - Quarto file containing the analysis code and documentation.

intertidal-eDNA-spatial-analyses.html - HTML output generated from the Quarto file, providing a rendered version of the analysis. This file can be download and viewed as a standard guide.

## How to Rerun
1. Clone the repository to your local machine.
2. Open the RStudio project file (intertidal-eDNA-spatial-analyses.Rproj) to set up the project environment.
3. Run the Quarto file (intertidal-eDNA-spatial-analyses.qmd) to reproduce the analyses and generate the figures.

## Contact
For questions or suggestions, please contact Dina-Leigh Simons at dinathebiologist@gmail.com.
