# **Functional QTL mapping and genomic prediction of canopy height in wheat measured using a robotic field phenotyping platform**

 [Manuscript webpage - *Lyra et al.* 2020. *Journal of Experimental Botany*, 71(6), 1885-1898](https://academic.oup.com/jxb/article/71/6/1885/5757976)

### Danilo H. Lyra<sup>1</sup>, Nicolas Virlet<sup>2</sup>, Pouria Sadeghi-Tehran<sup>2</sup>, Kirsty L. Hassall<sup>1</sup>, Luzie U. Wingen<sup>3</sup>, Simon Orford<sup>3</sup>, Simon Griffiths<sup>3</sup>, Malcolm J. Hawkesford<sup>2</sup>, Gancho T. Slavov<sup>1</sup>

<sup>1</sup>Department of Computational & Analytical Sciences, Rothamsted Research, Harpenden AL5 2JQ, UK
<sup>2</sup>Department of Plant Sciences, Rothamsted Research, Harpenden AL5 2JQ, UK
<sup>3</sup>John Innes Centre, Norwich Research Park, Colney Lane, Norwich NR4 7UH, UK

## Background
Genetic studies increasingly rely on high-throughput phenotyping, but the resulting longitudinal data pose analytical
challenges. We used canopy height data from the Field Scanalyzer phenotyping platform (LemnaTec GmbH) to compare several approaches
to scanning for quantitative trait loci (QTLs) and performing genomic prediction in a wheat recombinant inbred line
mapping population based on up to 26 sampled time points (TPs). These results will inform the development of an integrated, semi-automated analytical pipeline, which will be more broadly applicable to similar data sets in wheat and other crops.

## Readme
The phenotypic and genotypic data, as well as the R scripts used for all analyses in this study, can be found at Mendeley (Lyra, 2019; https://data.mendeley.com/datasets/pkxpkw6j43/2).

## Table of contents
1. **Factor-analytic (time series) analysis (phenotypic model) - ASReml-R**

2. **Smoothing and dimensionality reduction - fda-R**

3. **Time point selection**
     - Systematic (SY) approach - TPs were selected as equally spaced as possible
     - Growth stage (GS) approach - TPs were allocated preferentially to later stages
     
4. **Interval mapping (IM) and composite interval mapping (CIM) - R/qtl**
    
5. **Functional QTL mapping - funqtl-R**

6. **Power simulations**

7. **Genomic prediction - GBLUP model - BGLR-R**
     - Individual TP BLUPs
     - B-spline coefficients
     - First functional PCs     
     
## Funding
Rothamsted Research receives support from the Biotechnology and Biological Sciences Research Council (BBSRC) of the UK as part of the
Designing Future Wheat Institute Strategic Programme (BB/P016855/1)

<p float="left">
<img src="https://github.com/DaniloLyra/exome_HiBAP_data/blob/master/Pictures/rothamsted-logo.png" width="200" height="60">
<img src="https://github.com/DaniloLyra/exome_HiBAP_data/blob/master/Pictures/DFW-logo.jpg" width="100" height="100">
<img src="https://github.com/DaniloLyra/exome_HiBAP_data/blob/master/Pictures/bbsrc-logo.jpg" width="200" height="100">
</p>
