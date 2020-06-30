## OHBM 2020

Welcome to a brief preview of our work on "Changes in Functional Network Redundancy During Human Lifespan". This work was presented during OHBM Annual Meeting 2020.

### Abstract

## Introduction: 
Several aging studies have revealed that up to 25% of older adults who met pathological criteria for Alzheimer’s disease postmortem, showed no signs of cognitive impairment prior to death, suggesting individual variations in the brain’s ability to cope with pathology (Stern, 2012). These differences have been attributed to differences in the brain’s propensity to withstand disease. Redundancy, defined as the existence of alternate elements within a system that ensure functionality in case of failure, can be a critical factor in the survival of brain function when facing neurodegeneration. This preliminary study examined the trajectory of redundancy changes over the lifespan in comparison with other graph-based features. 
## Methods: 
To assess redundancy changes over the lifespan, our study used data from the publicly available Nathan Kline Institute Rockland Sample (NKI-RS). Data presented in the poster are composed of N = 654 subjects (male = 246, female = 408) over a wide age range (6-85 years, median = 44). Subjects underwent resting-state functional MRI scans with a Siemens TrioTM 3T MRI scanner, using an echo-planar imaging (EPI) sequence with TR/TE= 1400/30 ms, voxel size = 2mm isotropic, (FA) = 65°, FOV = 224 × 224 mm2, number of slices = 64, scan length = 2.5 min. Additionally, T1-weighted images were acquired using a rapid gradient echo sequence. Resting-state functional images were analyzed using the MATLAB Conn (conn18b) pipeline for volume-based analysis. Pre-processing included motion correction (realignment and unwarping), registration to structural images, spatial normalization and outlier detection (subject motion threshold = 0.9mm). Functional time-series were obtained using a functionally defined atlas with 300 regions of interest (ROIs), encompassing cortex, subcortex and cerebellum (Seitzman et al., 2018). Connectivity matrices were computed for each subject and binarized prior to analysis. The matrices were used to compute the total number of direct and indirect edges between each pair of ROIs, at a range of network densities preserving 2.5% - 15% of all edges.
## Results: 
The NKI-RS sample analyzed had a uniform age distribution (Ages 8-18: n = 118; 19-40: n = 179; 41-60: n = 198; 61-85: n = 159). A 3rd order polynomial was fit to the average redundancy with R2 = 0.35, p-value = 3.4x10-7, DoF = 75 (Figure 1a). The number of redundant edges accumulated over the ages 18-60, subsequently reducing over the ages 61-85. Redundancy was also compared with other graph metrics (mean degree, mean weighted clustering-coefficient) and the R2 for their respective polynomial fits were calculated (Figure 1b). Degree and clustering coefficient had lower fits (R2 = 0.18 and 0.17 respectively) compared to redundancy. Further, regional redundancy changes with progressing age were computed (Figure 2) along with the contribution of each network in whole-brain redundancy. Somatomotor-Dorsal and Visual-Attention networks underwent the most significant changes, with adults aged (40-60) having the highest number of redundant edges in these networks.
## Conclusions:
Our study investigated redundancy changes over the human lifespan offering insight into resilience against age-related cognitive decline. It was previously hypothesized (Cabeza et al., 2018) that factors affecting brain reserve (i.e., individual differences in brain’s reserve capacity to cope with pathology) follow a pattern of accumulation followed by age-related decline. As these neural resources accrue, the number of redundant neural pathways grows as expected, till the onset of decline. Other network metrics (e.g. degree and clustering) did not exhibit the same changes, suggesting that redundancy more closely follows the putative dynamics of brain reserve. In this context, redundancy in functional networks shows promise as a neuroimaging biomarker for cognitive decline.

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/usadiqgriffin/ohbm2020.lifespan/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
