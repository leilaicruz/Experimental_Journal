# Project outline

The most general assumption for this analysis is that the changes on the organism are mainly due its internal structure. That structure is defined depending on the task we want to observe. For instance, the normal cell cycle of budding yeast, is due to the tighted genetic regulation and protein expression processes happening inside the cell.

The external environment acts as trigger to unfold specific changes in the organism determine by its internal structure. Hence, I do not take the organism as a passive entity, that is just, able to react to the environment and adapt to it.


As a motivation of this idea, I would like to refer the reader to this experiment done in the 70's, with a [salamander](http://h-maturana-libros.blogspot.com/2007/08/epistemologa-de-un-experimento-prksen.html). Essentially, the scientists show that if the organism does not have an internal structure that allows it to interact succesfully with the environment, it can not maintain its living.

The project outline is guided by the research questions of the project. The first part is to look at how the genetic connections are rearranged during the consecutives deletions that occurred on the evolutionary trajectory.



## **Question 1**: How can we quantified the re-organization of the genetic interaction/epistasis dynamics of network along this evolutionary trajectory?

1. Epistasis, as desviations from the multiplicative model considering no interactions among genes.
   * Using the growth rate of a population, as a proxy to detect genetic interactions.

2. Shift in the number of essential genes, positive and negative interactions, along the different genetic backgrounds on the evolutionary pathway.

   * Genomic mapping using transposon, to detect essential and non-essential genes, using SATAY.

<!-- ![nombre](link) command for figure -->


## **Question 2**: Can we understand/make sense of  the accessibility/reproducibility of this evolutionary pathway assuming  a linkage model, among genetic interactors?

### Linkage Model:
In order for two genes to have a casual relation, they must interact. Casual relation is defined as if I change gene A , gene B appears to be changed as well, more than the 50% of the cases.

- Fact in favor: During the experimental evolution experiment done in bem3nrp1 background, BEM2 was not found mutated. This could be explained by the linkage model, as the following: Since BEM2 and NRP1 does not have any genetic interaction (so far studied), it is very unlikely that upon BEM3 and NRP1 deletion , BEM2 would be also deleted. Hence, the essence of the evolutionary trajectory we are studying, is the initial deletion of BEM1. And this trigger together with the experimental conditions, the emergence of new interactions. 

- Ideas about the role of BRE5 as minihub that has more than 40% interactors that are common to the interactors of BEM1,BEM3,NRP1,BEM2. BRE5 is a protein involved in deubiquitination, ribophagy, regulation of ER to Golgi vesicle-mediated transport and retrograde vesicle-mediated transport (golgi to ER); localizes to the cytoplasmic mRNA processing body and has been shown to bind to mRNA in large scale studies.
-  However, no direct connection/linkage/interaction is registered for BEM3,NRP1. There is just registered direct genetic interactions with BEM1, and BEM2. The type of the interaction is negative, e.g. the double mutation is deletirous.
   - Hypothesis: Upon BEM1 deletion, the interaction between BEM3 and NRP1, is based on the common interactions with BRE5. This idea is based on the amount of interactors genes shared between them. Bre5 interactors share nearly 60% with Nrp1 interactors (so far studied). Bre5 is the highest connected to Nrp1, from all BEM1 negative interactions. In addition, BRE5 interactors share 40% with BEM3 interactors. Hence, BRE5 should be a negative interactor of the bem1bem3 background. And NRP1 should be a direct genetic interactor of BEM3 in the bem1 background (**how to proof experimentally this?**).
   - Ideas to proof the hypothesis:
    - Find that BRE5 is a negative interactor in bem1bem3 background (SATAY).
    - Find that NRP1 is a positive interactor in the bem1bem3 background (control check in SATAY)

- Ideas about the role of CLA4, ACT1 and CDC3 as minihubs that couple BEM1,BEM3,NRP1 and BEM2 together. They are the only common interactors they have. These genes are very important for establishment and maintenance of the polarity in budding yeast.
 - BRE5 only interacts directly with ACT1 and CDC3.
 - The idea is that upon Bem1 deletion the evolution happens by transforming the subnetworks connected to the hubs of the system, that is, CLA4, ACT1, and CDC3. Is a similar idea of what was found out about HSP90 in this [paper](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.2006450).
 - However this does not answer why such evolutionary trajectory is reproducible, because the fact that BEM3, NRP1 and BEM2 are connected by those genes it doesn mean that they are the only genes the mini hubs shared in common.
- The coupling of the network upon BEM1 deletion based on the entanglement of CLA4,ACT1 and CDC3 and with the internal connection with BRE5 will drive an understanding of the genetic structure of the organism that ultimately determine the recurrent mutations along the evolutionary trajectory.



## **Question 3**: Can we elucidate potential recovery evolutionary/mutational pathways from a  genetic interaction network of a sick organism?
