---
title: "Transformation of ylic133_5 with the PCR products from yll137 and yll140 "
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
geometry: margin=0.5in
autoEqnLabels: true
cref: true
crossref: true
colorlinks: true
---


# Title: Transformation of ylic133_5 with the PCR products from yll137 and yll140

## Date
23022020-

## Objective

Transformation-1: To replace the nrp1 locus with the HYGRO cassette using the PCR product of yll137.

Transformation-2: To replace bem2 locus with the leu2 marker using the PCR product of yll140.


## Method
- Following this [Yeast Transformation Protocol](../Protocols/Yeast-transformation.md)
- Day0: 16:00 , Incubation of ylic133_5A from glycerol stock from 01202019 in YPD+6xADE. 10mL per transformation with its negative control.
- Day1: Measure OD of overnight cultures
  - | Sample |10X dilution OD  |Real OD|
  |---|---|---|
  | yll133_5 (1)  |0.1  | 1|
  | yll133_5 (2) |0.07  | 0.7|
- At 10:00 am 2nd incubation with a 2x dilution down to OD~0.5
- Check at 14:00 the OD
- | Sample |10X dilution OD  |Real OD|
|---|---|---|
| yll133_5 (1)  |0.28  | 2.8|
| yll133_5 (2) |0.23  | 2.3|
- DNA amount for transformations
    - nrp1::HYGRO - 806 ng (73.3ng/ul*9ul)
    - bem2::leu2 - 1.296 ug(144.4 ng/ul*9ul)
- The plates to check the success of the transformations are:
  - YPD+HYGRO+6xADE
  - -leu2+6xADE
  - The only autoclave component was the agar (4g) with 100ml MiliQ, the rest was added by filtering (in 80ml MiliQ). To avoid degradation of aminoacids in the autoclave machine.
- **Plating**:
  - ylic133_5 + bem2::leu2   , low and high concentrated , 90x and 10x dilution, for a final volume of 200ul.
- **Recovery step for ylic133_5+nrp1::HyGRO**
  - After removing the transformation mix , I added 1ml of YPD+6xADE to incubate in 30C overnight, and then plate that next morning on the selection plates.
  - This choice for the recovery way is based on the experience when selecting using 5FOA plates for not having URA, [here](../2019-07/2019-07-11_Exp_URA-kickout-transformation-ylic132_1_2.md).


## Results
25022020- Samples were spilled out from the eppi tube after the overnight incubation (I put too much YPD that cause the burst due to CO2 production)

> Next time put parafilm, around it , to prevent spilling.

![](../images/25022020-samples-spilled-out.png){width=50%}

**Note**:

> In general it is not advisable to wait more a whole overnight for recovery, because then we decrease the changes to have different biological replicates, since maybe one population will take over during the overnight incubation.

> Esentially the stadistics will go down , and if we have suppresor they will be "hidden" when plating on the selection plates.

## Conclusion
