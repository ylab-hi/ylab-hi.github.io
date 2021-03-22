---
title: "Yang Lab - Research"
layout: textlay
excerpt: "Yang Lab -- Research"
sitemap: false
permalink: /research/
---

# Research Highlights

---

![]({{ site.url }}{{ site.baseurl }}/images/respic/scanitd.png){: style="width: 250px; float: left; margin-right: 30px; border: 10px"}

## Genomic alterations detection
<div style="text-align: justify">
We have developed multiple algorithms specilized in analyzing high-throughput sequencing data to detect DNA alterations including insertions and deletions (INDELs) and large-scale structural variations (SVs). We developed the ScanIndel algorithm to address the challenge of reliably detecting medium- and large-sized indels from whole-exome or whole-genome sequencing data. Our contributions for SV detection are highlighted by two algorithms developed in my group: [SVfinder](https://github.com/cauyrd/SVfinder) and ScanITD. Application of these algorithms in cancer genomic data, we were able to detect diverse genomic rearrangement events involving androgen receptor (AR) in [prostate cancer](https://doi.org/10.1038/ncomms13668) as well as a t(11;17) translocation event causing the SPI-ZNF287 gene fusion in [multiple myeloma](https://doi.org/10.4137/CIN.S13783).

**Reference**

- Wang TY, **Yang R**. ScanITD: Detecting internal tandem duplication with robust variant allele frequency estimation, **GigaScience**, Volume 9, Issue 8, August 2020, giaa089.
- **Yang R**, Nelson AC, Henzler C, Thyagarajan B, Silverstein KA. ScanIndel: a hybrid framework for indel detection via gapped alignment, split reads and de novo assembly. **Genome Medicine**. 2015 Dec 7;7:127.

</div>

---- 

![]({{ site.url }}{{ site.baseurl }}/images/respic/exitron.png){: style="width: 250px; float: left;margin-right: 30px; border: 10px"}

## Transcriptomic mis-splicing events discovery
<div style="text-align: justify">
We were the first to discover a novel type of non-canonical splicing named “exitron” that result in internally deleted protein sequences from annotated coding exons in [prostate cancer](https://doi.org/10.1186/s12864-018-4671-4). We observed exitron splicing events frequently occurred in tumor suppressor genes. Moreover, we identified various types of RNA mis-splicing and alterations, such as [cryptic exon](https://doi.org/10.1158/1078-0432.CCR-17-0017), [alternative polyadenylation](https://doi.org/10.1158/0008-5472.CAN-17-0320) and [non-linear splicing](https://doi.org/10.1158/1078-0432.CCR-19-3023) in AR that contributed constitutive activity of the broad androgen/AR transcriptional program. These activities resulted from AR splicing variants are completely insensitive to all current prostate cancer targeted therapies, including the second-generation AR antagonist enzalutamide. There is now intense interest in the field to develop AR splicing variants as pharmacogenomic biomarkers of resistance, and develop new therapies that can inhibit their constitutive transcriptional activity. 

</div>

---

![]({{ site.url }}{{ site.baseurl }}/images/respic/egonet.png){: style="width: 250px; float: left;margin-right: 30px; border: 10px"}

## Multi-omics integrative analysis
<div style="text-align: justify">
A major goal of our research is to develop integrative computational tools that leverage multi-omics biological and clinical datasets to infer disease-associated genes, regulatory interactions and patient-specific therapeutic targets. Our contributions in this area include: 1) developing the EgoNet algorithm by integrating gene expression data and protein-protein interaction networks to identify gene markers that are associated with clinical phenotypes; 2) Constructing transcriptional regulatory networks of major transcriptional factors [AR, BRD4](https://doi.org/10.1038/nature13229) and [STAT5](https://www.nature.com/articles/ni.3716) with ChIP-seq and gene expression data that drive prostate cancer and leukemia and 3) Integrating transcriptomic and proteomic data to predict patient-specific tumor neoantigens for immunotherapy treatment.

**Reference**

- Wang TY, Wang L, Alam SK, Hoeppner LH, **Yang R**. ScanNeo: identifying indel derived neoantigens using RNA-Seq data. **Bioinformatics**. 2019 Mar 18.
- **Yang R**, Bai Y, Qin Z, Yu T. EgoNet: identification of human disease ego-network modules. **BMC Genomics**. 2014 Apr 28;15:314.
</div>


