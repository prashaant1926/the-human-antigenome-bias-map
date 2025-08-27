
# Literature Review: The Human Antigenome Bias Map

## Overview

This literature review examines the current state of knowledge regarding systematic biases in MHC Class I presentation, integrating 27 papers from 2016-2025 across high-impact journals including Nature, Science, Cell, Nature Communications, and other leading venues. The review reveals consistent challenges to fundamental assumptions about protein visibility in immunopeptidomes and identifies critical research gaps that our project aims to address.

## Core Assumptions Challenged Across the Literature

### Assumption 1: Protein Abundance Determines Presentation
**Traditional View**: MHC presentation directly correlates with protein abundance  
**Evidence Against**: Kubiniok et al. (2022) demonstrated systematic, evolutionarily conserved tissue-specific patterns independent of abundance. Hardy et al. (2021) showed cryptic proteins generate peptides 5-fold more efficiently than canonical proteins despite lower abundance.

### Assumption 2: Structural Properties Are Irrelevant
**Traditional View**: Peptide sampling is purely sequence-driven  
**Evidence Against**: Perez et al. (2019) revealed enriched sampling of helical fragments in source proteins. Our systematic analysis identifies intrinsic disorder as a key determinant of degradation pathway selection (Pereira et al., 2024).

### Assumption 3: Canonical Proteins Dominate
**Traditional View**: Only protein-coding sequences contribute meaningfully  
**Evidence Against**: Multiple studies (Hardy et al., 2021; Chen et al., 2021; Xu et al., 2024) demonstrate that non-canonical sources are over-represented and clinically relevant, with 6 of 13 prioritized cancer neoantigens derived from non-canonical sources.

## Research Themes and Findings

### Theme 1: Systematic Presentation Biases

**Kubiniok et al. (2022)** - *Foundational Discovery*
- **Problem**: Understanding constitutive MHC presentation patterns in primary tissues
- **Key Finding**: Systematic, evolutionarily conserved tissue-specific patterns independent of abundance
- **Impact**: Establishes biological principles governing presentation beyond random sampling
- **Relevance to Our Project**: Direct validation of systematic bias hypothesis

**Mamrosh et al. (2023)** - *Degradation Pathway Diversity*
- **Problem**: Role of alternative degradation pathways in MHC presentation
- **Key Finding**: 30% of MHC peptides are UPS-independent, enriched in mitochondrial proteins
- **Impact**: Challenges ubiquitin-proteasome system monopoly assumption
- **Relevance**: Supports multiple pathways contributing to presentation bias

### Theme 2: Non-canonical Source Efficiency

**Hardy et al. (2021)** - *Efficiency Quantification*
- **Problem**: Contribution of non-canonical proteins to immunopeptidome
- **Key Finding**: Cryptic proteins generate MHC peptides 5-fold more efficiently than canonical proteins
- **Technical Approach**: Integrated multi-omics analysis in clinical samples
- **Impact**: Demonstrates systematic over-representation of specific protein classes

**Chen et al. (2021)** - *sORF Detection Methods*
- **Problem**: Limited detection methods for small ORF-derived peptides
- **Innovation**: Three-pipeline approach integrating Ribosome profiling with MS
- **Outcome**: 308 noncanonical immunopeptides identified from two cell lines
- **Impact**: Methodological framework for detecting overlooked antigens

**Ji et al. (2024)** - *Stability Prediction Framework*
- **Problem**: Distinguishing functional from spurious non-canonical translation
- **Innovation**: PepScore model based on ORF features (length, domains, conservation)
- **Finding**: Stable non-canonical proteins follow conventional rules
- **Impact**: Statistical framework for identifying functional peptides

### Theme 3: Structural Determinants

**Perez et al. (2019)** - *Secondary Structure Bias*
- **Problem**: Role of protein structure in peptide sampling
- **Innovation**: 3D mapping of HLA-I peptides to source protein structures
- **Key Finding**: Enriched sampling of helical fragments
- **Impact**: First systematic evidence of structural bias in presentation

**Li et al. (2023)** - *Conformational Dynamics*
- **Problem**: Understanding MHC conformational changes during peptide editing
- **Innovation**: Crystal structures of intermediate conformations
- **Finding**: Visualization of peptide-dependent conformational motions
- **Impact**: Mechanistic understanding of high-affinity peptide selection

**Tran et al. (2020)** - *Thermostability Profiling*
- **Problem**: Assessing pMHC stability for natural ligands
- **Innovation**: MS-based stability measurement for thousands of ligands
- **Finding**: Broader stability profiles than previously appreciated
- **Clinical Impact**: Improved neoepitope immunogenicity prediction

### Theme 4: Technological Advances

**Wahle et al. (2024)** - *Clinical Translation*
- **Problem**: Large sample requirements limit clinical applications
- **Innovation**: IMBAS-MS platform requiring only 200μL plasma
- **Impact**: Enables routine clinical immunopeptidomics
- **Significance**: Tissue-specific patterns detectable in plasma

**Chang et al. (2025)** - *Population-Scale Analysis*
- **Problem**: MS sensitivity limitations for rare peptides
- **Innovation**: DNA sequencing-based approach for immunopeptidome analysis
- **Impact**: Population-wide understanding of HLA binding preferences
- **Significance**: Overcomes fundamental MS limitations

**Bruno et al. (2023)** - *Targeted Screening*
- **Problem**: Discovery approaches limited by sensitivity
- **Innovation**: EpiScan functional genetics platform
- **Capability**: >100,000 peptide screening with built-in validation
- **Impact**: Complements discovery-based approaches

### Theme 5: Clinical and Therapeutic Implications

**Xu et al. (2024)** - *Cancer Immunotherapy*
- **Problem**: Limited therapeutic target space
- **Finding**: Non-canonical peptides are high-quality therapeutic targets
- **Clinical Validation**: 6 of 13 prioritized AML neoantigens from non-canonical sources
- **Impact**: Significantly expands therapeutic opportunities

**Rana et al. (2024)** - *Immunoproteasome Targeting*
- **Strategy**: Pharmacological expansion of tumor immunopeptidome
- **Mechanism**: Immunoproteasome activation unmasks neoantigens
- **Clinical Outcome**: Enhanced T-cell anti-myeloma activity
- **Impact**: Therapeutic approach to modulate antigen presentation

## Literature-Level Hypothesis Validation

Our comprehensive analysis reveals **three major literature-level hypotheses** that reshape understanding of MHC presentation:

### H1: Systematic Structural Determinism
**Literature Support**: 8 papers (Perez 2019, Li 2023, Tran 2020, Kubiniok 2022, Pereira 2024, Solanki 2022, Kacen 2022, Xue 2024)
- Structural features systematically determine protein "visibility"
- Secondary structure, disorder, hydrophobicity all influence presentation
- Contradicts random sampling assumption

### H2: Non-canonical Source Over-representation
**Literature Support**: 9 papers (Hardy 2021, Chen 2021, Ji 2024, Xu 2024, Balakrishnan 2025, Laumont 2016, Deutsch 2024, Holly 2023, Trentini 2020)
- Small proteins and cryptic ORFs disproportionately represented
- Efficiency inversely related to protein size
- Clinical relevance demonstrated in cancer therapy

### H3: Context-Dependent Presentation Plasticity
**Literature Support**: 6 papers (Kubiniok 2022, Wahle 2024, Mamrosh 2023, Rana 2024a, Rana 2024b, Merbl 2025)
- Tissue-specific presentation signatures exist
- Cellular stress fundamentally alters presentation patterns
- Multiple degradation pathways contribute differentially

## Research Gaps and Opportunities

### Gap 1: Integrated Structural Scoring
**Current State**: Individual structural features studied in isolation  
**Need**: Comprehensive protein "visibility" scoring system  
**Opportunity**: Machine learning integration of multiple structural determinants

### Gap 2: Cross-tissue Systematic Analysis
**Current State**: Limited tissue coverage in most studies  
**Need**: Systematic comparison across multiple tissue types  
**Opportunity**: Plasma-based tissue signature discovery (enabled by Wahle et al.)

### Gap 3: Dynamic Presentation Modeling
**Current State**: Static snapshots of presentation under specific conditions  
**Need**: Understanding of presentation changes under cellular stress  
**Opportunity**: Temporal mapping of antigenome plasticity

### Gap 4: Predictive Framework Integration
**Current State**: Separate models for different aspects of presentation  
**Need**: Unified predictive framework for protein visibility  
**Opportunity**: Integration of structural, non-canonical, and contextual factors

## Methodological Standards and Evidence Quality

### High-Quality Evidence Standards Met:
- **Systematic Experimental Design**: All 27 papers employ rigorous experimental controls
- **Cross-species Validation**: Kubiniok et al. demonstrate conservation across species
- **Clinical Validation**: Multiple papers (Xu et al., Rana et al.) include patient samples
- **Technical Replication**: Advanced MS methods validated across multiple labs
- **Computational Validation**: Prediction improvements systematically measured

### Evidence Hierarchy:
1. **Foundational Discoveries** (n=5): Kubiniok, Hardy, Mamrosh, Perez, Li
2. **Methodological Advances** (n=8): Wahle, Chang, Bruno, Zhao, Chen, Ji, Tran, Mishto
3. **Clinical Applications** (n=6): Xu, Rana 2024a/b, Balakrishnan, Rana 2023, Lemke
4. **Technological Innovation** (n=8): Walz, Feng, Xue, Koohi, Yu, Finton, Peng, Darley

## Positioning of Our Research

### Novel Contributions Supported by Literature:
1. **Systematic Bias Quantification**: Literature establishes bias existence; we provide quantitative framework
2. **Multi-modal Integration**: Literature studies individual factors; we integrate structural, size, and contextual determinants
3. **Tissue-Specific Modeling**: Literature shows tissue differences exist; we model systematic patterns
4. **Dynamic Presentation Mapping**: Literature shows plasticity; we map temporal changes

### Alignment with Literature Trends:
- **Structural Integration**: Follows trend from Perez → Li → Xue toward structure-based understanding
- **Non-canonical Recognition**: Builds on Hardy → Chen → Ji progression of non-canonical source discovery
- **Clinical Translation**: Extends Wahle → Xu → Rana pathway toward therapeutic applications
- **Technological Innovation**: Leverages Chang → Zhao → Feng computational advances

## Conclusion

This literature review of 27 high-quality papers from 2016-2025 reveals a paradigm shift away from abundance-based, random sampling models toward systematic, structure-determined, context-dependent understanding of MHC presentation. The consistent challenge to fundamental assumptions across multiple independent studies provides strong foundation for our hypothesis-driven research framework.

**Key Literature-Supported Insights:**
1. Protein structure systematically determines presentation bias
2. Non-canonical sources are over-represented and therapeutically relevant  
3. Tissue-specific and dynamic presentation patterns exist
4. Current prediction models miss critical determinants
5. Clinical applications require comprehensive bias understanding

**Research Imperative:** The literature converges on the need for integrated, systematic approaches to understand and predict protein visibility in immunopeptidomes - precisely the gap our project addresses through the Human Antigenome Bias Map framework.

