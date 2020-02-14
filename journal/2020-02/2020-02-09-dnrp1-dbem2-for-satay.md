---
title: "Design of the genomic transformation to make dnrp1 and dbem2 strains usable for SATAY"
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

# Title : Design of the genomic transformation to make dnrp1 and dbem2 strains usable for SATAY

## Date
09022020

## Objective
- To design an strategy to make the following strains, in order to test SATAy on them :
  - $\Delta nrp1$ *ura3-* *ade2-*
  - $\Delta bem2$ *ura3-* *ade2-*

## Method 1
- PCR the genomic prep of yll137 with primer 1 and 6 for nrp1 deletion and transfrom it to ylic133
- PCR the genomic prep of yll140 with prmer 1 and 6 for bem2 deletion and transform it to ylic133.

> Pros: less PCRs

> Cons: I have to do two genomic preps.

- The procedure consists on:
  - Perform an Overlap Extension (OEP) PCR in order to get a DNA fragment in high concentration to insert in ylic133 and kick out the *nrp1* and *bem2* gene by replacing the HYGRO and LEU2 markers, respectively.
- The sequence for designing the primers is taken from SGD, in the sequence tab of the gene of interest to delete and its chromosome.
  - First download the CDS genomic sequence of the gene of interest.
  - Then ,download the sequence of the chromosome of the gene of interest.
  - Open SnapGene and import the chromosome sequence and search for the sequence of the gene of interest.
  - Add the corresponding feature that says that in that location is where the gene X is in the chromosome.
  - Note the gene start with ATG which is the start codon Methionine and ends with a stop codon ATT.
  - Start designing the primers!

  #### Procedure to design the right primers for the OEP:

  ![Sketch of how to design the 6 primers per gene deletion transformation](../images/strategy-sketch-OEP-02.png){#fig:primer-design}

  In general :

  - Primers should end with a G or C nucleotide.
  - Avoid AAA or TTT in the primer design because this may cause failures in the  correct annealing to the template.
  - Melting temperatures should be from 55C to 60C .

  Specific design for this OEP:

  - primer 1: Upstream primer pointing towards the start of the gene to knock out.
  - primer 2: Upstream reverse pointing outside the gene of interest. The upstream homology arm (left one) should around 200-250bp. This is the length from primer 1 to primer 2. This primer has to have an overlap [^1] that is the reverse complement of the annealed region of primer 3.
  - primer 3: Upstream primer pointing towards the marker sequence (top strand/bottom strand) in a plasmid ( I am using plasmid 32 HphMX4 for HYGRO and 105 PRS405 ) with an extra overlap sequence  that is the reverse complement of the annealed part of primer 2.
  - primer 4: downstream primer towards the marker sequence (bottom strand/top strand) with an extra overlap sequence that is the reverse complement of the annealed part of primer 5.
  - primer 5: downstream primer pointing away  the end of the gene to knock out, with the extra overlap that is the reverse complement of annealed primer 4.
  - primer 6: downstream primer pointing  towards the end of the gene to knock out.

  [^1]: The extra sequence should be in front of 5' of the annealed part of the primer, leaving the 3' free for the DNA polymerase to work.

  PCR reactions:

  1. PCR1: primer 1 and 2 with genomic DNA of ylic133
  2. PCR2: primer 3 and 4 with DNA  of plasmid 32 or 105
  3. PCR3: primer 5 and 6 with genomic DNA of ylic133


## Method 2

> Pros: No genomic preps

> Cons: I have to do 6 more PCRs!!!.

- The strategy is to delete *nrp1* using the HYGRO cassette and *bem2* in the leu2 locus as Liedewij has in her strains, in my ylic133 strain.

The procedure using Method 2 is as follows:

- Perform a PCR using primers 1 and 6 for each gene (nrp1 and bem2) in yll137 (for nrp1) and yll140 (for bem2).
  - Try to get around 3ug of DNA after PCR for each strain to ensure plenty of transformants.  
- Transform it into ylic133 each fragment separately.
- Check the integration by plate.


## Results

## Conclusion
