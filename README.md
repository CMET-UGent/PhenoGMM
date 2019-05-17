# _PhenoGMM_: Gaussian mixture modelling of microbial cytometry data enables efficient predictions of biodiversity 

This repository accompanies the manscript "*_PhenoGMM_: Gaussian mixture modelling of microbial cytometry data enables efficient predictions of biodiversity*" by P. Rubbens, R. Props, F.-M. Kerckhof, N. Boon and W. Waegeman. Biorxiv ID: 641464. 

## Abstract
*Motivation*: Microbial flow cytometry allows to rapidly characterize microbial community diversity and
dynamics. Recent research has demonstrated a strong connection between the cytometric diversity and
taxonomic diversity based on 16S rRNA gene amplicon sequencing data. This creates the opportunity to
integrate both types of data to study and predict the microbial community diversity in an automated and
efficient way. However, microbial flow cytometry data results in a number of unique challenges that need
to be addressed.
*Results*: The results of our work are threefold: i) We expand current microbial cytometry fingerprinting
approaches by using a model-based fingerprinting approach based upon Gaussian Mixture Models, which
we called PhenoGMM. ii) We show that microbial diversity can be rapidly estimated by PhenoGMM. In
combination with a supervised machine learning model, diversity estimations based on 16S rRNA gene
amplicon sequencing data can be predicted. iii) We evaluate our method extensively by using multiple
datasets from different ecosystems and compare its predictive power with a generic binning fingerprinting
approach that is commonly used in microbial flow cytometry. These results confirm the strong connection
between the genetic make-up of a microbial community and its phenotypic properties as measured by flow
cytometry.
*Availability*: All code and data supporting this manuscript is freely available on this repository. Raw flow cytometry data is additionally available via FlowRepository and raw sequences via the NCBI Sequence Read Archive. The functionality of PhenoGMM has been incorporated in the R package [PhenoFlow](https://github.com/CMET-UGent/Phenoflow_package), which we recommend R users to use.

## Structure of repository: 

### Examples of workflow: 
Two running examples are given, one for the _in silico_ data study, and one for studying natural communities: 
-
-

### Results: 
The presented results are an average of multiple runs on multiple datasets: 
- Flow cytometry data can be found in the folder [Data](https://github.com/prubbens/PhenoGMM/tree/master/Data). See also the [FlowRepository](https://flowrepository.org/), with IDs FR-FCM-ZZSH, FR-FCM-
ZZNA, FR-FCM-ZY9J and FR-FCM-ZYZN. 
- OTU-tables can be found there as well, for the [cooling water](https://github.com/prubbens/PhenoGMM/blob/master/Data/OTU_table_Cycles.csv) and for the [lake systems](https://github.com/prubbens/PhenoGMM/tree/master/Data/Lakes/ByLake_Filtering/1in3). 
- Summary of results can be found for the [_in silico_](https://github.com/prubbens/PhenoGMM/blob/master/Results/calc_summary_insilico.py), [cooling water](https://github.com/prubbens/PhenoGMM/blob/master/Results/calc_summary_cycles.py) and [freshwater setups](https://github.com/prubbens/PhenoGMM/blob/master/Results/calc_summary_lakes.py) by clicking the links and running the code. 
- Code to reproduce the figures (Python scripts starting with `plot`) and all results in the document can be found [here](https://github.com/prubbens/PhenoGMM/tree/master/Results). 
