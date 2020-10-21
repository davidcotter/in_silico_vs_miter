# in_silico_vs_miter

## NOTEBOOK
[See notebook revel_vs_p_causing_fpld3.ipynb](./revel_vs_p_causing_fpld3.ipynb)

## BACKGROUND
* The increasing application of NGS in clinical laboratories has enabled a rapid
and less labour-intensive analytical capability to be applied in the search for
deleterious genetic variants associated with the aetiopathogenesis of many
different diseases.
* One of the limitations of this approach is the degree of uncertainty relating to the
functional consequences and clinical relevance of any novel variants identified.
* Guidelines developed by the American College of Medical Genetics have proven
a useful resource in standardising the classification of variants, with the
functional characterisation of any putative genetic variant being afforded a very
high pathogenicity weighting.
* However, for many genes comprehensive functional impact assessments are not
available and therefore alternative methods of analysing variants need to be
utilised, including in silico prediction tools. To date many such tools have been
applied in routine clinical genetics practice with limited success.
* Recent refinements of in silico methods have focused on the development of
Meta-Predictors devised by machine learning algorithms e.g. REVEL1
* Furthermore, the recent use of novel in vitro approaches has facilitated the
functional assessment of multiple potential protein variants coded by specific
genes. An example of this is the functional classifier programme MITER derived
from a pooled functional assay for PPARG variants, where genetic variation in
PPARG is associated with the condition Familial Partial Lipodystrophy Type 3
causing a severe metabolic phenotype with significant morbidity.

## OBJECTIVES

* To compare the concordance between REVEL and MITER in the clinical
prediction of FPLD3 susceptibility
* To determine if a selected combination of in-silico tools provides an effective
means of predicting PPARG variant pathogenicity relative to MITER
* To examine whether the most effective combination of in-silico tools selected
using MITER is also applicable to genetic variants identified in other genotypephenotype paradigms e.g. HMBS and Acute Intermittent Porphyria3

## METHODS

* PPARG and HMBS variants annotated using Pynnotator2 with scores from a
combination of in-silco prediction tools MutPred, MutationAssessor,
MutationTaster, CADD, PROVEAN and Polyphen2
* A definitive functionally characterised HMBS variant bank(HMBS-FC) will be
selected from available literature
* Logistic Regression and Random Forest Machine Learning analysis will be
applied to determine the performance of REVEL and other in-silico tools
relative to MITER for PPARG
* Subsequent to training using MITER and a combination of selected in-silico
tools will be applied to HMBS dataset.
* Clinical performance characterisation will be reported in terms of Specificity
and Sensitivity.

