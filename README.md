# CNV and SV tools for NGS data
Relevant studies with Structual Variants and Copy Number Variants in NGS (Genome, Exome and Amplicon Sequencing) pipelines.
---

## Background CNV and SV
* [2011 Genome structural variation discovery and genotyping](http://www.nature.com/nrg/journal/v12/n5/full/nrg2958.html?foxtrotcallback=true)
* [2014 An Evaluation of Copy Number Variation Detection Tools from Whole-Exome Sequencing Data](http://onlinelibrary.wiley.com/doi/10.1002/humu.22537/abstract)
* [2014 Refining analyses of copy number variation identifies specific genes associated with developmental delay](http://www.nature.com/ng/journal/v46/n10/abs/ng.3092.html)
* [2015 Allele-specific copy-number discovery from whole-genome and whole-exome sequencing](https://academic.oup.com/nar/article-lookup/doi/10.1093/nar/gkv319)
* [2015 Copy number variant analysis from exome data in 349 patients with epileptic encephalopathy](http://onlinelibrary.wiley.com/doi/10.1002/ana.24457/abstract)
* [2015 Evaluation of somatic copy number estimation tools for whole-exome sequencing data](https://academic.oup.com/bib/article-abstract/17/2/185/1744035/Evaluation-of-somatic-copy-number-estimation-tools?redirectedFrom=fulltext)
* [2016 Frequency and Complexity of De Novo Structural Mutation in Autism](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4833290/)
* [2016 Evaluation of somatic copy number estimation tools for whole-exome sequencing data ](https://academic.oup.com/bib/article-abstract/17/2/185/1744035/Evaluation-of-somatic-copy-number-estimation-tools?redirectedFrom=fulltext)
* [2016 Detection of Clinically Relevant Copy Number Variants with Whole-Exome Sequencing](http://www.nature.com/gim/journal/vaop/ncurrent/full/gim2016163a.html)
* [2016 Sacral agenesis: a pilot whole exome sequencing and copy number study](http://bmcmedgenet.biomedcentral.com/articles/10.1186/s12881-016-0359-2)
* [2016 Assessing the reproducibility of exome copy number variations predictions](http://genomemedicine.biomedcentral.com/articles/10.1186/s13073-016-0336-6)
* [2016 Statistical models for DNA copy number variation detection using read-depth data from next generation sequencing experiments](http://onlinelibrary.wiley.com/doi/10.1111/anzs.12175/abstract)
* [2016 Patterns of genic intolerance of rare copy number variation in 59,898 human exomes](http://www.nature.com/ng/journal/v48/n10/abs/ng.3638.html)
* [2016 Challenges in detecting genomic copy number aberrations using next-generation sequencing data and the eXome Hidden Markov Model: a clinical exome-first diagnostic approach](https://www.nature.com/articles/hgv201625)
* [2017 CLImAT-HET: detecting subclonal copy number alterations and loss of heterozygosity in heterogeneous tumor samples from whole-genome sequencing data](https://bmcmedgenomics.biomedcentral.com/articles/10.1186/s12920-017-0255-4)
* [2017 Profiling copy number variation and disease associations from 50,726 DiscovEHR Study exomes](http://biorxiv.org/content/early/2017/03/22/119461)
* [2017 Validation of copy number variation analysis for next-generation sequencing diagnostics](http://dx.doi.org/10.1038/ejhg.2017.42)

## WES
* [2015 CODEX: a normalization and copy number variation detection method for whole exome sequencing](https://academic.oup.com/nar/article/43/6/e39/2453417/CODEX-a-normalization-and-copy-number-variation)
* [2016 Enhanced copy number variants detection from whole-exome sequencing data using EXCAVATOR2](https://academic.oup.com/nar/article/44/20/e154/2607979/Enhanced-copy-number-variants-detection-from-whole)
* [2016 CLAMMS: a scalable algorithm for calling common and rare copy number variants from exome sequencing data](https://academic.oup.com/bioinformatics/article/32/1/133/1743911/CLAMMS-a-scalable-algorithm-for-calling-common-and) - [github](https://github.com/rgcgithub/clamms)
* [2017 ExCNVSS: A Noise-Robust Method for Copy Number Variation Detection in Whole Exome Sequencing Data](https://www.hindawi.com/journals/bmri/2017/9631282/)
* [2017 Anaconda: AN automated pipeline for somatic COpy Number variation Detection and Annotation from tumor exome sequencing data](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-017-1833-3)

## WGS
* [FindSV](https://github.com/J35P312/FindSV): FindSV is a structural variation pipeline written in nextflow and python. FindSV performs variant calling using TIDDIT and CNVnator, and Manta.
* [SvABA](https://github.com/walaj/svaba): Structural variation and indel analysis by assembly.
* [2007 PennCNV: An integrated hidden Markov model designed for high-resolution copy number variation detection in whole-genome SNP genotyping data](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2045149/)
* [2012 DELLY: structural variant discovery by integrated paired-end and split-read analysis](https://academic.oup.com/bioinformatics/article/28/18/i333/245403/DELLY-structural-variant-discovery-by-integrated) - [github](https://github.com/dellytools/delly): Delly2 was the best sv caller in the [DREAM challenge]()
* [2014 LUMPY: a probabilistic framework for structural variant discovery](http://genomebiology.biomedcentral.com/articles/10.1186/gb-2014-15-6-r84) - [github](https://github.com/arq5x/lumpy-sv)
* [2015 Wham: Identifying Structural Variants of Biological Consequence](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004572) - [github](https://github.com/zeeev/wham) - [mergeSVcallers](https://github.com/zeeev/mergeSVcallers)
* [2015 MetaSV: an accurate and integrative structural-variant caller for next generation sequencing](https://academic.oup.com/bioinformatics/article/31/16/2741/321286/MetaSV-an-accurate-and-integrative-structural) - [github](http://bioinform.github.io/metasv/)
* [2016 Manta: rapid detection of structural variants and indels for germline and cancer sequencing applications](https://academic.oup.com/bioinformatics/article-lookup/doi/10.1093/bioinformatics/btv710) - [github](https://github.com/Illumina/manta)
* [2017 SV2: Accurate Structural Variation Genotyping and De Novo Mutation Detection](http://biorxiv.org/content/early/2017/03/17/113498) - [github](https://github.com/dantaki/SV2)
* [2017 GRIDSS: sensitive and specific genomic rearrangement detection using positional de Bruijn graph assembly](http://biorxiv.org/content/early/2017/02/21/110387) - [github](https://github.com/PapenfussLab/gridss)
* [2017 Detection of complex structural variation from paired-end sequencing data](https://www.biorxiv.org/content/early/2017/10/08/200170?rss=1)

## AS 
* [2017 An enhanced method for targeted next generation sequencing copy number variant detection using ExomeDepth](https://wellcomeopenresearch.org/articles/2-49/v1)
* [2017 panelcn.MOPS: Copy-number detection in targeted NGS panel data for clinical diagnostics](http://dx.doi.org/10.1002/humu.23237)
* [2017 SeqCNV: a novel method for identification of copy number variations in targeted next-generation sequencing data](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-017-1566-3)
* [2016 Accurate clinical detection of exon copy number variants in a targeted NGS panel using DECoN](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5409526/)
* [2016 CoNVaDING: Single Exon Variation Detection in Targeted NGS Data](http://onlinelibrary.wiley.com/doi/10.1002/humu.22969/abstract?systemMessage=Wiley+Online+Library+will+be+unavailable+on+Saturday+7th+Oct+from+03.00+EDT+%2F+08%3A00+BST+%2F+12%3A30+IST+%2F+15.00+SGT+to+08.00+EDT+%2F+13.00+BST+%2F+17%3A30+IST+%2F+20.00+SGT+and+Sunday+8th+Oct+from+03.00+EDT+%2F+08%3A00+BST+%2F+12%3A30+IST+%2F+15.00+SGT+to+06.00+EDT+%2F+11.00+BST+%2F+15%3A30+IST+%2F+18.00+SGT+for+essential+maintenance.+Apologies+for+the+inconvenience+caused+.)
* [2015 VisCap: inference and visualization of germ-line copy-number variants from targeted clinical sequencing data](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4940431/)
* [2012 A robust model for read count data in exome sequencing experiments and implications for copy number variant calling](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3476336/)

## Annotation
* [StructuralVariantAnnotation](https://github.com/PapenfussLab/StructuralVariantAnnotation): contains useful helper functions for dealing with structural variants in VCF format.
* [2015 SpeedSeq: ultra-fast personal genome analysis and interpretation](http://www.nature.com/nmeth/journal/v12/n10/full/nmeth.3505.html) - SVTyper - [github](https://github.com/hall-lab/svtyper)
* [2016 SVScore: an impact prediction tool for structural variation](https://academic.oup.com/bioinformatics/article/doi/10.1093/bioinformatics/btw789/2748212/SVScore-an-impact-prediction-tool-for-structural) - [github](https://github.com/lganel/SVScore)
* [2016 Prioritisation of Structural Variant Calls in Cancer Genomes](http://biorxiv.org/content/early/2016/11/04/084640) - [github](https://github.com/AstraZeneca-NGS/simple_sv_annotation)

## Visualization
* [CNVplot](https://github.com/dantaki/CNVplot): Plot CNV data with a genome viewer in R.
* [cnvgram](https://github.com/cc2qe/cnvgram): Draw CNV diagrams.
* [Stupid Simple Structural Variant View](https://github.com/ryanlayer/svv): A two-step process that can help visualize the coverage near a variant across multiple BAMs.
* [CNView](https://github.com/RCollins13/CNView): Visualization, quantitation, and annotation of CNVs from population-scale whole-genome sequencing data.
* [2015 svviz: a read viewer for validating structural variants](https://academic.oup.com/bioinformatics/article-lookup/doi/10.1093/bioinformatics/btv478) - [github](https://github.com/svviz/svviz)
* [2016 Ribbon: Visualizing complex genome alignments and structural variation](http://biorxiv.org/content/early/2016/10/20/082123) - [github](https://github.com/MariaNattestad/Ribbon)

## Others
* [SVsim](https://github.com/GregoryFaust/SVsim): a tool that generates synthetic Structural Variant calls as benchmarks to test/evaluate SV calling pipelines.
* [Structural Variant Catalog](https://github.com/tobiasrausch/svcatalog): A repository for human genetic structural variants (SVs) discovered by Delly in the 1000 Genomes cohort of samples.
* [SVDB](https://github.com/J35P312/SVDB): SVDB is a toolkit for constructing and querying structural variant databases. The databases are constructed using the output vcf files from structural variant callers such as TIDDIT, Manta, Fermikit or Delly. [The thousand genomes structural variant calls may also be used as a database](ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/phase3/integrated_sv_map/).
