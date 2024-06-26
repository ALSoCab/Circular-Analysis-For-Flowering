# :cherry_blossom: Circular Statistics for Flowering Data Analysis in R
## Keypoints 
- Phenology is defined by the US/IBP Phenology Committee as *'the study of the rhythms of recurring biological events and their causes, influenced by both biotic and abiotic forces, and examining the interrelationship between phases of the same or different species.'*
- Flowering and fruiting phenology (FFP) are critical aspects of plant fitness, with important implications for ecological processes such as interspecific interactions.
- FFP as a periodic phenomenon can be best interpreted in terms of uniformity and directionality over time if appropriate analysis are use ⬇️

<img src="https://github.com/ALSoCab/FFP-Circular-Analysis/assets/163931084/101eb9d7-589a-4d04-a605-5a9b30bea9f4" width="350" height="300" style="right">

>The nature of circular data is an inherent periodicity no considered on a linear scale [(Landler et al., 2018)](https://doi.org/10.1007/s00265-018-2538-y).

# 1. What the R script does?
This repository contains an R script designed to facilitate the analysis of flowering data using circular statistics. Circular statistics are particularly useful for analyzing periodic data, such as the timing of flowering events over the course of a year. Here, monthly abundance of flowers [^1] was represented on the circle where the circumference corresponds to an annual period of observation [(Jammalamadaka & SenGupta, 2001)](https://doi.org/10.1142/4031). 

The provided R script implements various circular statistical methods to analyze flowering data, including circular mean, circular variance, and circular-linear correlation. It also includes functions for visualizing circular distributions and relationships between circular variables and linear variables.
 
[^1]: It can also be easily used in data on the abundance of ripe or unripe fruits.
