# Paper title: Genetic interaction networks: better understand to better predict.
[1] B. Boucher and S. Jenna, “Genetic interaction networks: better understand to better predict.,” Front. Genet., vol. 4, p. 290, Dec. 2013.


## What they do:
* In this article, we will review the later knowledge acquired on GI networks in metazoans by looking more closely into their relationship with pathways, biological processes and molecular complexes but also into their modularity and organization.
* We will also review the different in silico methods developed to predict GIs and will discuss how the knowledge acquired on GI networks can be used to design predictive tools with higher performances.

## Review of the main concepts
* The existence of a Genetic Interaction (GI) between two genes does not necessarily means that these two genes code of interacting protein, or even , that the two genes are expressed in the same cell, for multicellular organisms.
* What a GI implies for two genes is that they share a functional relationship. These two genes may be involved in the same biological processes or pathway; or they may also be involved in compensatory pathways with unrelated apparent function.
* Epistasis is one of the functional relationships covered by the term genetic interactions.
* Negative GIs: They are also called aggravating or synergistic interactions, refer to an observed phenotype higher (mathematically) than expected when considering the phenotypes of single mutants. A synthetic lethal interaction is an extreme case of negative interaction in which the double mutant is lethal.
* Positive GIs: They are also called buffering or alleviating interactions where the biological effect of an allele is mitigated by a second one. Also the supressive interactions in which the double mutant is healthier than the sickest single mutant.
* The development of additive, multiplicative, Min and Log
models to calculate the expected phenotype of double mutants was mostly motivated bythe development of systematic and large-scale
screening of GIs, especially in the yeast Saccharomyces cerevisiae.

###Models to calculate the expected phenotype of a double mutant.
 ####The additive and multiplicative models.
 They are originally used by developmental geneticists (additive model) and fitness measurements in yeast (multiplicative).

 They consider the expected phenotype of a double mutant to be the sum (or the product) of the phenotypes measured for the single mutants if the two mutated genes function independently one from the other.

 ####The Log model

 It has been specifically designed to identify GIs from measurements on a logarithmic fitness scale .

 ####The Min model
 This considers that for non-interacting genes, the fitness of the double mutant should be similar to the fitness of the less-fit single mutant.

The Min model appears to be highly suitable for pairs of genes with more extreme single-mutant defects, however this model is clearly not ideal for defining alleviating interactions and more particularly, several epistatic interactions for which a double mutant phenotype is similar to that of the single mutant with the most severe phenotype.

**Unfortunately, GIs identified "in silico" using this model account for a large part of all GIs found in interaction databases. This tends to bias the yeast genetic interactome against this later kind of GIs**

## Levels of abstraction in biology

From the genomic sequence to the phenotype.
At the lower level we have:
1. Networks representing the physical structure and organization of the genome.
  > In these networks, nodes could be genes/coding sequences, single-nucleotide polymorphisms(SNPs) or coding sequences linked by edges representing their physical proximity and organization within chromosomes, their homology etc.

2.  Expression of the genome into physical components: proteins and RNA.
  > Edges between these elements would indicate that they are co-expressed in different contexts or that their expression profiles throughout multiple experimental conditions are highly correlated.

3. Physical interactions between different elements - protein- protein (PPI), protein-DNA (PDI) or protein-RNA (PRI) interactions.
4.  Functional relationships linking these physical elements.
  > These are GI networks, signaling and metabolic pathways.
5.  The fifth level would level the biological processes.
  > This level would contain networks where protein implicated in the same biological proces would be linked by an edge.

6.  The sixth and last level of abstraction would represent phenotypes and show the relationships between elements associated with similar phenotypes and diseases.

A huge amount of effort is being made to establish the links and the dynamics underlying the relationships between networks located at the different levels.
  > The relationship between the second (gene expression) and the third level (mainly PPI and PDI) has been well documented.
