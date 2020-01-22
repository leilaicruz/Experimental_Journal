---
title: "FACs with the microscopy/bulk conditions for the paper "
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



# Title: FACs experiment with the same conditions as the microscopy done to quantify the cell sizes for the pAl1-Cdc42-sfGFP strains.

## Date
20012020-23012020

## Objective
To be able to compare the results of the FACs with the microscopy conditions.
And also to see if we get a difference in expression when increasing the incubation temperature to 36C.

## Method
Insights from the Gal1 promoter

  - The location in the genome at which the gal promoter was inserted can have a strong effect on the expression pattern of the gal promoter (*Ramon feedback*). Hence we should not compare different studies of the Gal1 promoter with ours if the integration in the genome is in a different location and also if it is a plasmid or not.
  - We should compare systematically the Gal1p expression pattern of the strains that has the sfGFP (Werner strains) and the mneonGreen ones (Ramon/Miranda strains), because they have the same type of genomic integration of the Gal1 promoter.

    - [x] **Ask Reza for his data with WT+mneongreen to compare with mine**
      - Look for the postprocessing results, in this [folder](N:\tnw\BN\LL\Shared\Leila\Images-postprocessing-FACS-REZA)
- Follow the same protocol as I followed for the microscopy measurements

![Experimental Design for the microscopy measurements](../images/experimental-design-microscopy.png){#fig:experimental-design}

--------------

**Planned procedure**

  - 15 hours of incubation in 2% Gal +2% Raff (i.e. overnight incubation from 17:00 to 08:00 )
  - Washing step  with CSM+2% Raff+0%Gal to the respective Galactose (at 08:00-09:00) concentrations. Incubate
  - Measure FACs after 24 hours of incubation . (next day of the washing step)
    - Use the references cdc42-GFP ywkd038 and ywkd001 in  2% dextrose +2% Raff, in CSM-met and CSM respectively.

-----------

- In order to have the same conditions as the microscopy done in December 2018 , where we quantify the cell sizes after 24 hours of incubation in X% galactose (after a washing step from a firsto overnight incubation in 2% galactose), the media has to have 4x the normal amount of aminoacids. This maybe has an impact on the regulation of the promoter.
- The new plate design for this is shown in @fig:plate-design

![Plate design for this FACS experiment](../images/96-well-plate-design-01-2020-03-03.png){#fig:plate-design width=50% height=50% }

- The strain ywkd024 will be measured to still compared with previous measurements done by Marit, in 2017.
- Strains :
  -  ywkd024 : RWS119	Wedlich-Söldner Lab collection	a	W303 *can 1 1-100		his3 11,15	Galpr-myc-**GFP**-CDC42	YipLac204-MET-CLN2	cln1$\Delta$::HisG, cln2$\Delta$, cln3$\Delta$::HisG*	(**strain to compare with ywkd065(sfGFP)**)
  - ywkd065a	New	YWKD055c		W303		*URA-Gal1pr-**sfGFP**-Cdc42 sandwich (pWKD011 integrated)	leu2 3,112	his 3 11,15*
  -  ywkd069 : New	YWKD055c	a	W303	*bem1$\Delta$::KanmX URA-Gal1pr-sfGFP-Cdc42 sandwich (pWKD011 integrated)	MFAprHIS3	3,112	11,15*
  -  ywkd070 : YWKD070a,b,c	New	YWKD055c	a	W303	*bem1$\Delta$::KanmX		bem3$\Delta$::clonNAT	URA-Gal1pr-sfGFP-Cdc42 sandwich (pWKD011 integrated)	MFAprHIS3	3,112	11,15*
  -  ywkd038: RWS1421	Wedlich-Söldner Lab collection	a	W303	*can1 1-100		his3 11,15	CDC42pr-myc-**GFP**-CDC42		YipLac204-MET-CLN2	cln1$\Delta$::HisG, cln2$\Delta$, cln3$\Delta$::HisG*	 (**Reference for the native CDC42 expression**)
-  Settings of the FACs experiment

    - **Equipment-Model**: BDFACSCelesta
    - **Lasers**: Alexa Fluor 488 at 495V
    - **Flow Rate**: 1ul/sec
    - **Sample volume**: 180ul
    - **Plate**: 96 well plate with flat bottom
    - **# of events per well**: 30000
    - **FSC threshold**:20000
    - **FSC voltage**: 407V
    - **SSC volatge**: 275V
    - **Mixing volume**: 90ul
    - **Mixing speed**: 200ul/sec
    - **Nr. of mixes**: 2

--------------
**Actual procedure**

- 1st Incubation , at 14:15 in 21012020 in 2% Gal.
  - Notes after this 1st incubation:
    - Neither ywkd001, ywkd038 and ywkd024 had enough cells after 24 hours of incubation in 2% Gal in 36C. (?)

- 2nd incubation, at 15:00 in 22012020 in the respective gal concentrations.
  - I washed two times the 1st incubation in CSM and CSM-met for ywd024 and ywd038 with 2% Raff, with no GAL.
  - I put the same amount of cells per strain in all conditions, aka I pipetted the same volume of a concentrated cell culture (from 5ml to ~400ul) in every tube of the same strain.
  - For ywkd024 I could not pipette any cell in 0.1% Gal and 0.2% Gal, because I ran out of cells :( but this is not a big problem anyways.
## Results

## Conclusion
