---
title: "Essential genes in WT insights"
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
cref: true
crossref: true
---

# Title:14012020-Mapping essential genes  in WT and getting insights from it.

## Date
14012020

## Objective
To analyze and get some insights from the essential genes in WT.
Useful questions:

- How many essential genes in WT are also bem1 interactors?
- How many essential genes in WT are also bem1 synthetic lethals?
- What is the dependency of the number of synthetic lethals of specif gene with the fitness of a knockout cell from that gene.

## Method

- I mainly used for this analysis the software [Tableau](https://www.tableau.com/) under an academic license, for free.
- This software is handy to quickly inspect a difficult dataset with many dimensions and variables.

## Results
- The list of essential genes I downloaded from [Here](http://www.essentialgene.org/). Essentially it consists of 1110 genes , around 20% of yeast genome , measured in rich media for *Saccharomyces cerevisiae*.
  - The reference of the study is [this paper from 2002](Giaever G, et al (2002). Functional profiling of the Saccharomyces cerevisiae genome. Nature, 418:387-91.), called: *Functional profiling of the Saccharomyces cerevisiae genome*.

   ![Essential genes on the yeast genetic interaction map](../images/essential-genes-yeast.png){#fig:essential }

- How many essential genes in WT are also bem1 interactors?

34 genes out of 321 bem1 interactors genes are also essential in WT.
This represents the 3% of all essential genes in WT interacts with Bem1.

- Bem1 synthetic lethals mapping -38 genes

 ![mapping of synthetic lethals genes of Bem1](../images/synthetic-lethals-of-Bem1.png){#fig:lethals}

- How many bem1 synthetic lethals are also essential genes in WT?

Insight 1: Out of the 34 essential genes that intersect with Bem1 interactors, 13 are Bem1 synthetic lethals (~ 1/3 of them ). ***This means that 21 essential genes in WT looses their essentiality in dbem1 background***.

Insight 2: 13 genes out of 38 bem1 synthetic lethals are also WT essential genes (~ 1/3 of them). ***This means  that 15 synthetic lethals genes of bem1 have gained essentiality in this background***.

  ![Essential genes that are also Bem1 synthetic lethals](../images/bem1-synthetic-lethals-that-are-also-essential-genes-in-WT.png){#fig:intersection-with-Bem1-lethals}

## Conclusion

- In dbem1 background some essential genes from WT background losses their essentiality(21/34), others gain essentiality (15/38), and other remains essential in both backgrounds(13=intersection of 34 essential genes and 38 bem1 synthetic lethals).
