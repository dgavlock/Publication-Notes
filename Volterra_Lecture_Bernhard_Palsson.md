# [An Emerging Era of Genome-Scale Science](https://www.youtube.com/watch?v=JrZ3BHw0imY)
***Bernhard Palsson***

2017

 

## Introduction: (5:00)
### Two approaches to Systems Biology

1. Bottom-Up Approach
2. Top-Down Approach

### Two Types of Causation
1. Proximal Causation
    * personalized metabolic states
    * Metabolic Shifts
    * Cancer metabolism from exo-metabolomic data
2. Distal Causation
    * Laboratory evolution of metabolic gene KO strains
    
### Bottom Up Approach 8:00

* Integrated approaches came from the generation of large data sets:
  * Genomic
  * High-throughput analytical chemistry
  * transcriptomics
  * Proteomics
  
and using these data to do various bioinformatics, create various mathematical models (COBRA Tool site)

* Pathways are a part of a metabolic network

### Network Reconstruction 10:30

* Necessary for understanding relationships in biological systems
* Workflows--> A coordinated QC process of integrating computational methods and experimental data to produce a desired result
* Hypotheses can be true or false, but models can be irrelavant
* Knowledgebase gather of similar information to gain stronger understanding over time
  * Mathematically interogate knowlegdebase to better understand biological processes in a queryable way
* Cellular systems are multidemensional, thus hard to represent and understand
* You must understand your *solutions space*

### COBRA Resources and Methods (16:00)
* Textbook
* Conferences
* Primers
* Barrier to entry is low
* [BiGG Models](bigg.ucsd.edu)
* COBRApy (python library)
* Visualizations (issue, by symphomy was the best) (Esher is the new tool)
* [Lectures](http://bit.ly/1HXgKzj)

### Available Reconstructions--E. coli (17:47)

* MK55 E. coli
  * Genome reducded
  * strain they used for metabolic biological reconstruction
* Continuous stream of genomic data allow group to map other E. coli stains and study the comparison to MG55
  * Biggest differences were in catabolic substrates and transporters
  * Profiles could prodict auotrophies and where cells prefer to colonize on hosts
  
* \>1,000 profiles of E. Coli
  * Common metabolic networks
  * Pangenome determines differences in strains
  * HisD has largest variations across strains
  
 * iML1515 for clinical isolates and metagenomes (24:16)
  * 552 sequences from clinical isolates to compare to MG55 for strain-specific models of E.coli
  * Reconstructing E. coli for IBD patients 
  * Many applications of this biological reconstructions
  
* Sequencing all infections 
  * Investigate **personized cases** of infections and compare to the larger community (knowledgebase)
  * 2020 is the predicted time for all infections being sequences

* ME models 27:00
  * Transcription/translation
  * Protein Localization

* Looking at Proteostasis Network of E. coli
  * FoldME
  * Growth based on temperature
    * Protein synthesis
    * Chaperones
    * Metabolism
* StressME- Genome-scale Model of Oxidative Stress Response (30:00)

* Recon3D
  * Human metabolism--RECON1
  
### Proxial Causation (35:00)

* How is this data used in practice?
* Red Blood Cell (RBC) storage

1. Gather clinical samples, 
2. Sequence
3. Overlap metabolic pathways
4. Multi-Variate Analysis (PCA)
5. We want to perturb somebiological process (RCB storage)
6. Define biomarkers from analysis
7. Biomarkers can inform statistical models
  * Shows demensionality
8. Interrogate mechanistic models to elucidate systems-level physiology


### Personalizing Red Cell Fasting MEtabolic States (43:00)

* High-Throughput Kinetic Modeling
* Predict drug toxicity to ribavirin toxicity
* Machine-learning to find potential mechanisms

### Distal Causation
* Building adpative laboratory evolution machines
* Gathering many endpoints in very control conditions
* Automating ALE
* Response to evolutionary outcome are usually similar but different, and how they get there is different

### System Adaptation

1. Knockout
2. Changed pathway usage
3. Perturbed levels of key metabolites trigger specific and nonspecific global network responses through transcription factor activation
4. suboptimal expression
5. Competing and overlapping layers of regulation
6. mutations re-wired many counterproductive effects of global and local reulatores
7. Mutations introduced innovations that targeted specific metabolites imbalances

