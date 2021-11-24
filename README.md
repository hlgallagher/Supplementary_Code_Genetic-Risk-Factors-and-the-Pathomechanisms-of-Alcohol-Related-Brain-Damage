# Genetic-Risk-Factors-and-the-Pathomechanisms-of-Alcohol-Related-Brain-Damage
Repository for code relating to enome wide association study and allele specific expression analysis for ARBD related pathomechanism study. 
This project was conducted as part of an honours thesis at the University of Syndey, under the supervision of A/Prof Greg Sutherland.

**Genome Wide Association Study of AUDIT Score**
This code depends on the initial input files being created from extracted UKB data and summation of AUDIT score using Microsoft Excel. input file mus then be converted to Plink format. These steps are not detailed in this repository.
Code for the UKB GWAS was adapted from a tutorial by Marees et al. 2018
R-scripts for this code are not provided as they were created my Marees et al. 2018, they are available at: https://github.com/MareesAT/GWA_tutorial/
For use of the R-scripts with the code provided on this repository edits must be made to the names of input files in the scripts directly, otherwise they are incomptible.

**Allele Specific Expression Analysis of AUD groups**
This code details the process for alignment and read counting for a single sample only, in practice this would be looped for multiple samples using the given commands.
Code for the ASE analysis of PFC and Controls was based on a study that previosuly performed the same analysis on tissue by Rao et al. 2021
The purposes of this repository in its current state is for documentation of the methodologies used for the project.




References
Marees, AT, de Kluiver, H, Stringer, S, Vorspan, F, Curis, E, Marie-Claire, C & Derks, EM 2018, 'A tutorial on conducting genome-wide association studies: Quality control and statistical analysis', Int J Methods Psychiatr Res, vol. 27, no. 2, p. e1608.

Rao, X, Thapa, KS, Chen, AB, Lin, H, Gao, H, Reiter, JL, Hargreaves, KA, Ipe, J, Lai, D, Xuei, X, Wang, Y, Gu, H, Kapoor, M, Farris, SP, Tischfield, J, Foroud, T, Goate, AM, Skaar, TC, Mayfield, RD, Edenberg, HJ & Liu, Y 2021, 'Allele-specific expression and high-throughput reporter assay reveal functional genetic variants associated with alcohol use disorders', Mol Psychiatry, vol. 26, no. 4, pp. 1142-51.
