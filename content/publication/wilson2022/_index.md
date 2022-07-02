---
title: Sensitive and reproducible cell-free methylome quantification with synthetic spike-in controls

# Listing view
#view:
publication_types: "3"
Date: 2021-01-01

# Optional banner image (relative to `assets/media/` folder).
banner:
  caption: ''
  image: ''
---
Authors: Samantha L Wilson, Shu Yi Shen, Lauren Harmon, Justin M Burgener, Tim Triche, Scott V Bratman, Daniel D De Carvalho, Michael M Hoffman

Publication date: 2021/1/1

Journal: bioRxiv

Publisher: Cold Spring Harbor Laboratory

URL link: [Sensitive and reproducible cell-free methylome quantification with synthetic spike-in controls](https://www.biorxiv.org/content/10.1101/2021.02.12.430289v1)

Abstract: Background Cell-free methylated DNA immunoprecipitation-sequencing (cfMeDIP-seq) identifies genomic regions with DNA methylation, using a protocol adapted to work with low-input DNA samples and with cell-free DNA (cfDNA). This method allows for DNA methylation profiling of circulating tumour DNA in cancer patients’ blood samples. Such epigenetic profiling of circulating tumour DNA provides information about in which tissues tumour DNA originates, a key requirement of any test for early cancer detection. In addition, DNA methylation signatures provide prognostic information and can detect relapse. For robust quantitative comparisons between samples, immunoprecipitation enrichment methods like cfMeDIP-seq require normalization against common reference controls.

Methods To provide a simple and inexpensive reference for quantitative normalization, we developed a set of synthetic spike-in DNA controls for cfMeDIP-seq. These controls account for technical variation in enrichment efficiency due to biophysical properties of DNA fragments. Specifically, we designed 54 DNA fragments with combinations of methylation status (methylated and unmethylated), fragment length (80 bp, 160 bp, 320 bp), G+C content (35%, 50%, 65%), and fraction of CpG dinucleotides within the fragment (bp, bp, bp). We ensured that the spike-in synthetic DNA sequences do not align to the human genome. We integrated unique molecular indices (UMIs) into cfMeDIP-seq to control for differential amplification after enrichment. To assess enrichment bias according to distinct biophysical properties, we conducted cfMeDIP-seq solely on spike-in DNA fragments. To optimize the amount of spike-in DNA required, we added varying quantities of spike-in control DNA to sheared HCT116 colon cancer genomic DNA prior to cfMeDIP-seq. To assess batch effects, three separate labs conducted cfMeDIP-seq on peripheral blood plasma samples from acute myeloid leukemia (AML) patients.

Results We show that cfMeDIP-seq enriches for highly methylated regions, capturing 99.99% of methylated spike-in control fragments with 0.01% non-specific binding and preference for both high G+C content fragments and fragments with more CpGs. The use of 0.01 ng of spike-in control DNA total provided sufficient sequencing reads to adjust for variance due to fragment length, G+C content, and CpG fraction. Using the known amount of each spiked-in fragment, we created a generalized linear model that absolutely quantifies molar amount from read counts across the genome, while adjusting for fragment length, G+C content, and CpG fraction. Employing our spike-in controls greatly mitigates batch effects, reducing batch-associated variance to ≤ 1% of the total variance within the data.

Discussion Incorporation of spike-in controls enables absolute quantification of methylated cfDNA generated from methylated DNA immunoprecipitation-sequencing (MeDIP-seq) experiments. It mitigates batch effects and corrects for biases in enrichment due to known biophysical properties of DNA fragments and other technical biases. We created an R package, spiky, to convert read counts to picomoles of DNA fragments, while adjusting for fragment properties that affect enrichment. The spiky package is available on GitHub (https://github.com/trichelab/spiky) and will soon be available on Bioconductor.
