---
title: "Comparison between Wener setting in FAcs with mine"
output: pdf_document
documentclass: article
classoption: onecolumn
pdf_document:
latex_engine: pdflatex
toc: true
lof: true
numberSections: true
highlight: tango
sectionsDepth: 3
chapters: True
figPrefix:
  - "Fig."
  - "Figs."
secPrefix:
  - "Section"
  - "Sections"
fontsize: 12pt
geometry: margin=1in
autoEqnLabels: true
cref: true
crossref: true
---

# Title : Comparison between the fAcs dettings used for Werner in 2017 with the ones I am using currently.

## Date
13022020-14022020

## Objective
To understand what happen to the output fluorescence signal if the settings are slightly changed, and perhaps we can understand why in 2017 when he measured with Marit they measured 6-7 fold between 0-2% gal while I am only measuring 1.5-2.5 fold change, when taking the geometric means of the histograms.

![Marit-Werner data 2017](../images/Normalized-024-hist-fold-change-Werner_marit-2017.png){#fig:marit-data width=50%}

![Leila Data 06022020](../images/Normalized-024-hist-fold-change-leila-2020.png){#fig:leila-data width=50%}

- From @fig:marit-data we can observe that already the sugar source it was used is different than mine experiments. The used glucose as a second sugar source for the galactose promoter , and all the reamining controls are in incbated in glucose. The cells here were incubated in 30C and I incubated them in 36C (as Ilse measured in the bulk growth).  I used raffinose as a second sugar source , and also for the controls without galactose promoter, as Ilse used in her bulk growth experiments.
- From the histograms, we can see that @fig:marit-data have a long tail for 2% gal (gray curve), going until 25000.
- The 2% Raff in my case(@fig:leila-data) is more spread than the 2% glu for @fig:marit-data. maybe because Raffinose has some galactose???
- Looking from peak to peak in @fig:leila-data, we can see that the fold change is around 8, from 1000 to 8000.

## Method

- I am going to use only the following strains:
  - ywkd024 : RWS119	Wedlich-Söldner Lab collection	a	W303 *can 1 1-100		his3 11,15	Galpr-myc-**GFP**-CDC42	YipLac204-MET-CLN2	cln1$\Delta$::HisG, cln2$\Delta$, cln3$\Delta$::HisG*	(**strain to compare with ywkd065(sfGFP)**)
  - ywkd038: RWS1421	Wedlich-Söldner Lab collection	a	W303	*can1 1-100		his3 11,15	CDC42pr-myc-**GFP**-CDC42		YipLac204-MET-CLN2	cln1$\Delta$::HisG, cln2$\Delta$, cln3$\Delta$::HisG*	 (**Reference for the native CDC42 expression**)
  - ywkd001: 	$\alpha$	W303 *can 1 1-100		his3 11,15	leu2 3,112*		S288C ,yLL3a -Laan Lab collection (**Reference for the background fluorescence**)
- The incubation is going to be for 15 hours from glycerol stock to the measurement point, in 0% and 2% Gal.
    - Incubation started at 8:50 am on 13022020

### Different setting used for Werner (2017) and for me (2020)

- **Equipment-Model**: BDFACSCelesta
- **Lasers-488nm**: 375V (Werner) // 495V (Leila)
- **FSC threshold**: 50000 (Werner) // 20000 (Leila)
- **FSC voltage**: 375V (Werner) // 407V (Leila)
- **SSC volatge**: 233V (Werner) // 275V (Leila)

## Results

![](../images/Non-normalized-hist-14022020.png)
![](../images/Non-normalized-bead-leila-area-14022020.png){width=50%}![](../images/Non-normalized-bead-werner-area-14022020.png){width=50%}

![Considering Leila settings to normalize](../images/Ratio-mean-comparison-leila-settings-14022020.png){#fig:mean-leila}

![Considering Werner settings to normalize](../images/Ratio-mean-comparison-werner-settings-14022020.png){#fig:mean-werner}

## Conclusion

- The settings of Werner , what does is to shift the signal to the left including the signal from the beads.
- After the analysis of the height and the area output from the GFP output pulse , we can say that we can see 7 fold variation among the means of intensities when taking the height measure as the intensity signal. 
