---
title: "Materials and methods "
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

## FACs

#### Media
The media used for incubation of the yeast strains was *Complete Supplement Mixture* (CSM) and CSM without methionine (CSM-MET). The sugar source used was Raffinose for growth and Galactose to express the Gal1 promoter. We did not use Dextrose in our experiments for his known effect on inhibiting the expression of the galactose promoter in yeast [**REF**].

#### Strains

The yeast strain used are ywkd065,ywkd069, ywkd070, ywkd001, ywkd24 and ywkd038. For their details in their genotype , see Table **XXX**.

#### Incubation details

The yeast strains used in this study were first incubated in 2% Galactose, for 24 hours. After this time, they were washed out with CSM/CSM-MET(depending on their genotype) and resuspended in this media. Subsequently, they were transfer to the galactose concentrations used in this study, namely, 0%,0.01%,0.02%,0.06%,0.08%,0.1%,0.2% and 2% Galactose.



## Controls

#### Comparable expression between sfGFP and GFP

![Individual comparison between GFP and sfGFP fluorophuores at 2% Galactose.](../images/sfGFP-GFP-fluorophuores.png){#fig:comparison-fluorophuores width=50X height=50X}

![Correlation between both fluorophuores, in the same conditions as @fig:comparison-fluorophuores.](../images/Correlation-between-sfGFP-GFP-fluorophuores.png){#fig:correlation width=50X height=50X}


#### Expression at 0% galactose

We confirmed that in 0% galactose there is no growth of the strains that has the Cdc42 production controlled by the Gal1 promoter.
Although,in the setup used in this study, we could measured cells in 0% galactose, we tested for longer incubation times in this galactose concentration to confirm that all the cells die, as expected. We let them grow for 48 hours in 0% galactose from the glycerol stock, then we did a flow cytometry measurement and we found there was no cells in the well. This was reflected in the lack of values for those wells containing 0% galactose.
