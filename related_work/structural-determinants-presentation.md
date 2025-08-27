# Structural Determinants of MHC Presentation

## Problem Framework
- **Problem**: Why are some proteins systematically over/under-represented in immunopeptidomes independent of abundance?
- **Core Assumption**: MHC presentation bias is random or purely allele-dependent
- **Gap**: Limited understanding of structural features that determine "protein visibility"

## Key Findings on Structural Determinants

### Secondary Structure Biases

**Perez et al. (2019) - HLA-I Ligand Secondary Structure Analysis**
- **Technical Innovation**: 3D mapping of HLA-I peptides to source protein structures
- **Key Finding**: Enriched sampling of helical fragments in source proteins for HLA-I presentation
- **Assumption Challenged**: Secondary structure is irrelevant to peptide sampling
- **Impact**: Reveals structural preferences in antigen processing
- **Citation**: Perez, M.A.S., et al. (2019). Analysis of Secondary Structure Biases in Naturally Presented HLA-I Ligands. Front Immunol 10, 2731.

### Hydrophobicity and Binding Characteristics

**Solanki et al. (2022) - Hydrophobicity in Peptide-MHC Binding**
- **Problem**: Prediction tools miss hydrophobicity as binding determinant
- **Key Finding**: NetMHC-4.0 shows bias toward hydrophobic peptides for HLA-A*0201
- **Technical Issue**: Hydrophobic false positives and hydrophilic false negatives
- **Impact**: Suggests retraining needed with biochemical attributes
- **Citation**: Solanki, A., et al. (2022). Hydrophobicity identifies false positives and false negatives in peptide-MHC binding. Front Oncol 12, 1034810.

### Protein Degradation and Structural Properties

**Pereira et al. (2024) - 20S Proteasome Substrate Analysis**
- **Core Finding**: 20S substrates enriched in RNA/DNA-binding proteins with intrinsically disordered regions
- **Key Insight**: Structural disorder predisposes proteins to degradation and presentation
- **Technical Approach**: Systematic MS analysis of 20S vs 26S substrates
- **Impact**: Links protein structure to degradation pathway selection
- **Citation**: Pereira et al. (2024). Systematic identification of 20S proteasome substrates. EMBO Mol Med.

### Post-translational Modifications

**Kacen et al. (2022) - Modified Immunopeptidome**
- **Innovation**: Systematic analysis of PTM peptides in immunopeptidome
- **Key Finding**: PTM peptides show different structural properties and stability
- **Assumption Challenged**: PTMs are rare or irrelevant in MHC presentation
- **Impact**: Reveals new dimension of antigen diversity
- **Citation**: Kacen, A., et al. (2022). Uncovering the modified immunopeptidome reveals insights into principles of PTM-driven antigenicity. Nat Biotechnol 41, 239-251.

## Mechanistic Insights

### Thermostability Profiling

**Tran et al. (2020) - pMHC Stability Measurement**
- **Technical Innovation**: MS-based measurement of pMHC stability for thousands of ligands
- **Key Finding**: Stability profiles broader than previously appreciated
- **Clinical Application**: Improved neoepitope immunogenicity prediction
- **Impact**: New dimension for immunopeptidome analysis
- **Citation**: Tran, E., et al. (2020). Thermostability profiling of MHC-bound peptides: a new dimension in immunopeptidomics and aid for immunotherapy design. Nat Commun 11, 6305.

### MHC Conformational Dynamics

**Li et al. (2023) - MHC I Conformational States**
- **Problem**: MHC I intermediate conformations during peptide editing poorly understood
- **Key Finding**: Crystal structures reveal distorted N-terminal groove conformations
- **Technical Innovation**: Structural visualization of peptide-dependent conformational motions
- **Impact**: Explains molecular dynamics of high-affinity peptide selection
- **Citation**: Li, L., et al. (2023). Crystal structures of MHC class I complexes reveal the elusive intermediate conformations explored during peptide editing. Nat Commun 14, 5122.

## Clinical and Therapeutic Implications

### Structural Information in Prediction

**Xue et al. (2024) - Geometric Deep Learning for MHC**
- **Problem**: Sequence-based prediction methods have limited generalizability
- **Innovation**: Structure-aware deep learning for MHC binding prediction
- **Key Finding**: 90x data efficiency improvement with structural information
- **Impact**: Challenges assumption that large datasets are always required
- **Citation**: Xue, L.C., et al. (2024). Geometric deep learning improves generalizability of MHC-bound peptide predictions. Commun Biol 7, 1613.

### Engineering Approaches

**Finton et al. (2023) - HLA Single Chain Trimer Design**
- **Problem**: HLA single chain trimers may not accurately represent native molecules
- **Key Finding**: Design affects peptide conformation for non-9mer peptides
- **Technical Innovation**: Novel stabilizing mutations and crystallization reagents
- **Impact**: Improves tools for structural immunology research
- **Citation**: Finton, K.A., et al. (2023). Effects of HLA single chain trimer design on peptide presentation and stability. Front Immunol 14, 1170462.

## Common Assumptions Identified

1. **Structural properties are irrelevant** - Multiple studies show secondary structure biases
2. **Hydrophobicity is adequately captured** - Prediction tools show systematic biases
3. **PTMs are rare in immunopeptidome** - Significant PTM peptide populations exist
4. **Protein degradation is structure-independent** - Disorder predisposes to degradation
5. **Stability measurements are optional** - Stability profiling reveals new complexity

## Research Gaps for Our Project

1. **Systematic structural scoring** - Need integrated metrics for protein "visibility"
2. **Disorder-degradation relationships** - Quantitative models needed
3. **Cross-tissue structural patterns** - Do structural biases vary by tissue?
4. **Dynamic structural changes** - How does stress alter structural determinants?
5. **Predictive structural models** - Can structure predict presentation bias?