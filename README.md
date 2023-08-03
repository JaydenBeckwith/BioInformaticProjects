# BioInformaticProjects

A repo where I have uploaded my bioinformatics research projects as pdf papers I completed at the Institute for Molecular Bioscience (2022-2023), University of Queensland. Copyright Jayden Beckwith (and UQ IMB) 2022-2023. Most code was performed in Jupyter notebook and R markdown with some parts performed on HPC

Project 1 - Understanding the Mechanism of ALS through RNA Sequencing 

Summary: Amyotrophic lateral sclerosis (ALS) is a severe neurodegenerative condition characterised by motor neuron degradation, muscle disability, and TDP-43 protein aggregation. We investigated the role of gene expression and aberrant splicing (AbS) in the disease, utilising RNA from matched blood and skeletal muscle. Gene expression changes in ALS detected 58 differentially expressed (DE) protein-coding genes related to inflammation and tissue regeneration. Analysis revealed significant local changes and aberrant splicing sites, including in known ALS-related genes. However, the extent of these alterations varied between individuals and tissues, suggesting a complex, non-uniform disease landscape. The study concludes that while ALS-related aberrant splicing is not necessarily widespread, exploring these variations with a larger cohort is necessary. Furthermore, it suggests that targeting splicing therapeutically could help reduce disease risk or progression.

Overview of the RNA-seq pipeline used in this project
![image](https://github.com/JaydenBeckwith/BioInformaticProjects/assets/55827127/06d4ad13-d299-4e03-80ef-a0991cb88d60)


Project 2 - Exploring Blood Collection Techniques in ALS through Transcriptomics

Summary: This project assessed the effectiveness of an economical method to extract RNA from blood in EDTA tubes, called Ethylenediamine (eRNA), for RNA sequencing (RNA-seq) studies. The study compared the eRNA method with the gold standard PAXgene™ blood collection technique using six matched samples. The results showed no significant difference in average read count between the two methods, supporting eRNA as a viable alternative. However, differential gene expression analysis revealed some differences, with several protein coding ribosomal genes showing variable expression between the two techniques. Furthermore, more frequent aberrant splice events were observed in the PAXgene™ collections, suggesting reduced power in eRNA. Despite these variations, both methods provided high-quality RNA-seq data. The study underscores the need for further refinement of the eRNA collection method and the benefits of using a single collection method within an experiment. Considering the economical advantages of eRNA, its potential applications across the scientific community are significant. The study also identifies some novel aberrant splice events that could further our understanding of motor neurone disease.

Overview of RNA-seq pipeline used in this project 

![Picture](https://github.com/JaydenBeckwith/BioInformaticProjects/assets/55827127/087ab5c7-4d81-4201-b7a3-2147fde9bee5)

Project 3 - GWAS and trait analysis

Summary: This project aimed to analyze single nucleotide polymorphisms (SNPs) in the HapMap 3 of around 11,000 people from the UK Biobank study, specifically targeting the fasting glucose (FG) phenotype, which could shed light on genomic information for metabolic conditions. To identify genomic regions associated with the FG phenotype, Genome-wide association study (GWAS) analysis was used. Despite its effectiveness in detecting genetic variation, GWAS doesn't fully explain the genetic architecture of complex human traits, which are influenced by multiple genetic and environmental factors and their interactions. To better understand this, the study employed Genome wide complex trait analysis (GCTA), a two-step process which estimates genetic correlation between study participants and SNP data using the Genetic Relationship Matrix (GRM), and uses genome-based restricted maximum likelihood (GREML) to maximize the likelihood of the target traits provided by the GRM. This approach helps to effectively compare phenotypic similarity to genetic similarity in individuals. GREML also involves fitting a mixed linear model to measure the effects of SNPs. This was apart of STAT7306 course at UQ. 
