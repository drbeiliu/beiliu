# Welcome to Bei Liu's personal website.
I am currently a postdoc at the University of North Carolina at Chapel Hill. I am a dedicated ***microscopist*** with a great passion on engineering ***biosensors*** and ***optogenetic*** tools. The purpose of this site is to provide useful information related to my research interests. If you are interested in my literatures sharing, please go [here](https://github.com/shepherd87/shepherd87.github.io/blob/master/pages/literatures.md).

| Microscopy  |  Biotech.  | Probes | Computational Bio.
|:------------: |:----------:|:--------:|:-------------------:|
[Single molecule imaging](#single-molecule-imaging) | [Biosensors](#biosensors)   | [Fluorescent proteins](#fluorescent-proteins) | [SM data processing](#SM-data-processing)
[Superresolution imaging](#superresolution-imaging) | [Optogenetics](#optogenetic-tools) | [Organic dyes, quantum dots](#organic-dyes) | [FRET biosensor](#FRET-biosensor-data-processing)
[Light-sheet imaging](#light-sheet-imaging)         | --- | [*in vivo* labeling](#in-vivo-labeling) | ---
   

----------
## Microscopy techniques

[// ]: # (this is comment )

### single molecule imaging



- **Introduction:** No two molecules are alike. Single molecule imaging (SMI) also you to follow one molecule at a time, reserving the heterogenous information that may easily ignored by ensemble fluorescence measurement. Meanwhile, SM sensitivity allows researcher to study rare happend events. No over-expression is needed, thus maintaining the system under physilogical situation.
  
  SM techniques             | Suitable scenarios
  --------------------------| ------------------
  Single molecule tracking  | diffusivity, protein-protein interaction
  Single molecule FRET      | conformational change
  Single molecule bleaching | oligomerization states
  PALM/STORM                | superresolution

  Generally, SMI data processing consists of four steps: 1) picking molecules from raw movie; 2) linking correspondent molecules on consecutive frames; 3) rendering tracking/reconstruction results; 4) post-analysis.

- Useful links
- Refs

### superresolution imaging

- Introduction
- Useful links
- Refs

### light-sheet imaging

- Introduction
- Useful links
- Refs

## Biotech.

### biosensors

- Introduction
- Useful links
  1. [Hahn lab at UNC-Chapel Hill](http://www.hahnlab.com/)
  2. [Biosensor database](https://biosensordb.ucsd.edu/index.php)
- Refs
  
### optogenetic tools

- Introduction
  
  I am not a molecular biologist, but I'm always fansnated in controlling singnaling pathway using optogenetic tools. Here, I tried to summarize currently aviliable optogenetic tools based on LOV, Cry2, et. al. 

  <a name='LOV2-based'>LOV2 Based</a>
  
  <a name='CRY2-based'>CRY2 Based</a>
   1. [**Cry2-mCh:**](https://www.nature.com/articles/nmeth.2360) The photolyase homology region (PHR) of Cry2 fused to mCherry (Cry2-mCh) formed distincet fluorescent puncta within 10 s of 405 or 488 nm light illumination. Light-induced Cry2-LRP6c clustering modulates the Wnt/β-catenin pathway. Light-induced clustering activates **Rac1** and **RhoA**. Add a constitutively oligomerizing DIX domain to mCherry-RhoA, the resulting protein was membrane localized.
   2. [**CRY2olig:**](http://dx.doi.org/10.1038/ncomms5925) Light-Induced Co-clustering (LINC), can be used to interrogate protein interaction dynamics, and to probe protein interactions. CRY2olig bears a E490G mutation, that greatly enhanceds light-induced clustering of CRY2. *LINC* assay takes CRY2olig-tagged 'bait'  protein and a fluorescent-tagged 'prey'. *LINK-FRAP* is for querying interactions at compact sites, where resident proteins already appear punctate. 
   3. [**optoTrk**](http://dx.doi.org/10.1038/ncomms5057); [**optoFGFR**](http://dx.doi.org/10.1016/j.chembiol.2014.05.013);
   4. [**CLICR:**](http://dx.doi.org/10.1038/ncomms7898) short for Clustering Indirectly using Cryptochrome 2. CLICR can be used to photocontrol of the clustering of diverse transmembrane receptors including **FGFR, PDGFR and Integrins**, as well as  manipulating endogenous receptor tyrosine kinase (RTK); Strategy: Cry2 fused to a binding domain (Cry2-BD) possessing limited affinity for a garget receptor, which would remain largely in the cytoplasm in the absence o light. 
   5. [**CRY2clust:**](http://dx.doi.org/10.1038/s41467-017-00060-2) This paper investigated how fusion proteins or tags influence the efficiency of CRY2-based oligomerization. Indentified a short peptide (nine residues), which substantially enhanced light-induced CRY2 clustering. 
   6. [**CRY2high** and **CRY2low**:](http://dx.doi.org/10.1038/s41467-017-00648-8) CRY2 can undergo light-dependent CRY2-CRY2 homo-oligomerization and CRY2-CIB1 hetero-dimerization. N-terminal charges are critical for CRY2-CIB1 interaction, while two C-terminal charges impact CRY2 homo-oligomerization, whith positive charges facilitating oligomerization and negative charges inhibiting it.
- Useful links
  1. [Hahn lab at UNC-Chapel Hill](http://www.hahnlab.com/)
  2. [Optogenetics database](https://www.optobase.org/)
- Refs 

## Fluorescent probes

### fluorescent proteins

- Introduction
- Useful links
    1. [FPs database](https://www.fpbase.org/)

### organic dyes

- Introduction

### *in vivo* labeling

- **self-labeling-enzymes**
  
  SNAP, Halo, Clip-tag

- **unnature-amino-acid**
  
  UAA
## Computational Bio.
### SM-data-processing
1. Picking molecule from raw movie
2. Localization methods
3. Liking methods
4. Post-analysis: diffusion 
5. Post-analysis: clustering
### FRET-biosensor-data-processing