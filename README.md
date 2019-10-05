<script type="text/javascript" async
src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.2/MathJax.js? 
config=TeX-MML-AM_CHTML"
</script>
# Zebrafish_runx1_analysis

## Xiaonan Wang
## Summary: Analysis notebooks for the Zebrafish runx1 project for Mathilda T.M. Mommersteeg, in preparation

## Introduction
Runx1 is a transcription factor that plays a key role in determining the proliferative and differential state of multiple cell types, during both development and adulthood. Here, we report how \textit{runx1} is specifically upregulated at the injury site during zebrafish heart regeneration, but unexpectedly, absence of \textit{runx1} results in enhanced regeneration. Using single cell sequencing, we found that the wild-type injury site consists of Runx1-positive endocardial cells and thrombocytes that induce expression of smooth muscle and collagen genes without differentiating into myofibroblasts. Both these populations are absent in \textit{runx1} mutants, resulting in a less collagenous and fibrinous scar. The reduction in fibrin in the mutant is further explained by reduced myofibroblast formation and by upregulation of components of the fibrin degradation pathway, including plasminogen receptor Annexin 2A as well as downregulation of plasminogen activator inhibitor \textit{serpine1} in myocardium and endocardium, resulting in increased levels of Plasminogen. In addition, we find enhanced myocardial proliferation as well as increased myocardial survival in the mutant. Our findings suggest that Runx1 controls the regenerative response of multiple cardiac cell-types and that targeting Runx1 is a novel therapeutic strategy to induce endogenous heart repair.  

## Notebooks
- [All cells](https://github.com/SharonWang/Zebrafish_runx1_analysis/blob/master/Notebooks/Zebrafish_allcells_analysis.ipynb): 
    * The overall analysis of all 3 samples, including Uninjured WT, Injured WT and Injured Runx1 KO
- [DBpos cells](https://github.com/SharonWang/Zebrafish_runx1_analysis/blob/master/Notebooks/Zebrafish_DBpos_analysis.ipynb) ((Runx1+ \cup Citrine+) \cap (Kdrl+ \cup mCherry+)): 
    * Analysis of double positive cells for all 3 samples
- [DBpos_no_KO cells](https://github.com/SharonWang/Zebrafish_runx1_analysis/blob/master/Notebooks/Zebrafish_DBpos_noKO_analysis.ipynb): 
    * Analysis of double positive cells for Uninjured WT and Injured WT
- [CM cells](https://github.com/SharonWang/Zebrafish_runx1_analysis/blob/master/Notebooks/Zebrafish_CM_analysis.ipynb):
    * Analysis of cardiomyocytes for all 3 samples 
- [EpiSMC cells](https://github.com/SharonWang/Zebrafish_runx1_analysis/blob/master/Notebooks/Zebrafish_EpiSMC_analysis.ipynb):
    * Analysis of Epicardial and smooth muscle cells for all 3 samples
- [Additional plots](https://github.com/SharonWang/Zebrafish_runx1_analysis/blob/master/Notebooks/Zebrafish_Additional_Plots.ipynb):
    * Dotplots and violinplots that require later version of scanpy
