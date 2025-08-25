

# Literature Review

## Overview

This literature review examines the current understanding of MHC Class I antigen presentation with particular focus on systematic biases in protein representation - the core question driving the Human Antigenome Bias Map project. Through analysis of 34 recent papers (2020-2025), we identify key assumptions across the field and position our work within the broader research landscape.

## Core Research Areas

### 1. Mass Spectrometry-Based Immunopeptidomics

**Technical Evolution and Sensitivity**

The field has undergone rapid technical advancement in MS-based immunopeptidome profiling. Wahle et al. (2024) introduced IMBAS-MS, revolutionizing the field by enabling identification of >5000 HLA class I peptides from only 200μL of plasma in 30 minutes, challenging the previous assumption that large plasma volumes (mL scale) were required. This automation breakthrough enables clinical-scale applications.

Complementing this, Walz et al. (2023) implemented time-of-flight ion mobility separation (TOF IMS MS), providing next-generation sensitivity without specificity loss. This challenges the assumption that standard Orbitrap MS represented the technical ceiling, opening new possibilities for rare peptide detection.

**High-Throughput Targeted Approaches**

Bruno et al. (2023) developed EpiScan, a functional genetics screening platform that leverages the principle that MHC molecules only traffic to the cell surface after binding high-affinity peptides. This targeted approach complements discovery-based methods by enabling focused analysis of specific protein regions.

### 2. Systematic Presentation Biases

**Tissue-Specific and Evolutionarily Conserved Patterns**

Kubiniok et al. (2022) made a fundamental discovery: MHC immunopeptidome architecture shows evolutionarily conserved, tissue-specific patterns that are independent of simple protein abundance. Using cross-species comparative immunopeptidomics, they demonstrated that presentation biases follow systematic biological principles rather than stochastic processes.

This challenges the widespread assumption that protein abundance is the primary determinant of MHC presentation, revealing intrinsic protein properties that systematically affect immune visibility.

**Protein Degradation Pathway Dependencies**

Mamrosh et al. (2023) provided quantitative evidence that challenges a fundamental assumption in the field: they found that 30% of MHC class I peptides are independent of the ubiquitin-proteasome system (UPS), with these UPS-independent peptides enriched in mitochondrial proteins. This systematic analysis revealed alternative degradation pathways contribute significantly to antigen generation.

### 3. Non-Canonical Protein Sources

**Cryptic Proteins and Small ORFs**

Hardy et al. (2021) conducted integrated RNA-seq, ribosome profiling, and mass spectrometry analysis revealing that 72% of non-canonical proteins are "cryptic proteins" encoded by ostensibly non-coding regions. Critically, these cryptic proteins generate MHC-I peptides 5-fold more efficiently per translation event than canonical proteins, likely due to lower stability and higher intrinsic disorder.

Chen et al. (2021) developed an integrated approach combining ribosome profiling with MS-based validation, identifying 308 noncanonical immunopeptides from small ORFs (sORFs). Their complementary three-pipeline approach for sORF database construction represents a methodological advance for detecting these overlooked antigen sources.

**Frameshift and Alternative Reading Frame Products**

Laumont et al. (2016) pioneered proteogenomic approaches demonstrating significant contribution from non-canonical reading frames, including non-AUG initiated translation. This work revealed pervasive translation outside annotated protein-coding genes, expanding the universe of potential antigens.

### 4. Computational Prediction and Machine Learning

**Next-Generation Deep Learning Approaches**

The field has rapidly evolved toward sophisticated deep learning methods. Feng et al. (2025) introduced UniPMT, a unified framework predicting peptide-MHC-TCR binding with up to 15% improvement in performance. This represents advancement beyond previous approaches that analyzed components separately.

Xue et al. (2024) demonstrated that geometric deep learning using structural information achieves superior generalizability across unseen MHC alleles with 90-fold data efficiency compared to sequence-based methods. This challenges the assumption that large training datasets are always required.

**Machine Learning for MS Enhancement**

Wahle et al. (2024) developed MHCvalidator, a machine learning algorithm enhancing MS-based immunopeptidomics sensitivity. Their approach identified unique frameshift-derived epitopes, including one from truncated SARS-CoV-2 spike protein, demonstrating clinical relevance for vaccine development.

## Common Assumptions Across Literature

Through systematic analysis, we identified five prevalent assumptions that are frequently challenged by recent findings:

1. **Protein abundance determines presentation** - Contradicted by tissue-specific bias patterns independent of expression
2. **Proteasomal degradation is the primary source** - 30% of peptides are UPS-independent  
3. **Only canonical proteins contribute significantly** - Non-canonical proteins are over-represented per translation event
4. **Presentation is primarily allele-specific** - Systematic tissue-specific patterns exist across alleles
5. **Mass spectrometry captures the complete immunopeptidome** - Technical limitations create systematic blind spots

## Research Gaps and Our Positioning

**Critical Knowledge Gaps Identified:**

1. **Systematic bias quantification**: No comprehensive framework exists for quantifying over/under-representation across the entire proteome
2. **Protein property integration**: Limited integration of stability, localization, and turnover data with presentation patterns
3. **Non-canonical source integration**: Systematic inclusion of small ORFs and alternative frame products in presentation analysis
4. **Clinical translation**: Gap between discovery research and therapeutic applications
5. **Cross-tissue comparative frameworks**: Standardized methodologies for tissue-specific bias analysis

**Our Research Position:**

The Human Antigenome Bias Map directly addresses these gaps by:

- **Challenging**: The assumption that protein abundance is the primary determinant of MHC presentation
- **Building on**: Recent discoveries of systematic presentation biases and non-canonical protein contributions
- **Extending**: Current immunopeptidomics approaches to include comprehensive bias quantification
- **Integrating**: Multiple data sources (MS data, protein properties, ribosome profiling) into unified bias scoring

## Key Papers Influencing Our Approach

### Methodological Framework
- **Kubiniok et al. (2022)**: Cross-tissue comparative immunopeptidomics methodology
- **Hardy et al. (2021)**: Integration of ribosome profiling with immunopeptidomics
- **Mamrosh et al. (2023)**: Quantitative analysis of presentation pathway dependencies

### Technical Approaches
- **Wahle et al. (2024)**: High-throughput, small-volume immunopeptidome profiling
- **Chen et al. (2021)**: Computational pipeline for non-canonical peptide discovery
- **Xue et al. (2024)**: Machine learning approaches for presentation prediction

### Biological Insights
- **Mishto et al. (2024)**: Proteasomal processing complexity beyond simple hydrolysis
- **Trentini et al. (2020)**: Role of quality control in antigen sampling
- **Balakrishnan et al. (2025)**: ncRNA-derived peptides and extracellular vesicle transport

## Future Directions

The literature points toward several critical research directions that align with our project goals:

1. **Comprehensive bias mapping** across tissue types and conditions
2. **Integration of protein biophysics** with presentation data
3. **Machine learning models** incorporating systematic biases
4. **Clinical translation** of bias understanding to therapeutic applications
5. **Standardized frameworks** for cross-study comparison and validation

This literature review establishes the scientific foundation for systematic analysis of presentation biases and positions the Human Antigenome Bias Map as addressing a critical knowledge gap in understanding immune surveillance of the human proteome.

