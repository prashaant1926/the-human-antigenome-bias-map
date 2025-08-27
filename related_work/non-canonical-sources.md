# Non-canonical Sources of MHC Peptides

## Problem Framework
- **Problem**: Standard proteome annotation misses significant sources of immunopeptides
- **Core Assumption**: Only canonical protein-coding sequences contribute meaningfully to immunopeptidome
- **Gap**: Systematic characterization of non-canonical peptide sources and their efficiency

## Major Non-canonical Source Categories

### Small ORFs and Cryptic Proteins

**Hardy et al. (2021) - Non-canonical Protein Contribution**
- **Core Finding**: 72% of non-canonical proteins are cryptic proteins, 28% are novel isoforms
- **Key Efficiency Insight**: Cryptic proteins generate MHC-I peptides 5-fold more efficiently than canonical proteins
- **Technical Approach**: Integrated multi-omics with clinical B-cell lymphoma samples
- **Assumption Challenged**: Non-canonical contributions are negligible
- **Impact**: Reveals major source of immunotherapeutic targets
- **Citation**: Hardy, M.P., et al. (2021). Most non-canonical proteins uniquely populate the proteome or immunopeptidome. Cell Rep 34, 108815.

**Chen et al. (2021) - sORF Detection Pipeline**
- **Innovation**: Three-pipeline approach integrating Ribo-seq with MS detection
- **Key Finding**: 308 noncanonical immunopeptides identified from tumor cell lines
- **Technical Advance**: Systematic approach for sORF-derived peptide discovery
- **Validation**: Experimental confirmation of computationally predicted peptides
- **Impact**: Methodological framework for detecting overlooked antigens
- **Citation**: Chen, L., et al. (2021). An Integrated Approach for Discovering Noncanonical MHC-I Peptides Encoded by Small Open Reading Frames. J Am Soc Mass Spectrom 32, 2015-2024.

### Alternative Reading Frames

**Laumont et al. (2016) - Proteogenomic Analysis**
- **Innovation**: Pioneering proteogenomic approach to identify non-canonical reading frame peptides
- **Key Finding**: Significant contribution from non-AUG initiation sites
- **Assumption Challenged**: Only canonical reading frames produce presented peptides
- **Technical Limitation**: Older methodology, limited computational tools available
- **Impact**: Foundation work establishing non-canonical translation importance
- **Citation**: Laumont, C.M., et al. (2016). Global proteogenomic analysis of human MHC class I-associated peptides derived from non-canonical reading frames. Nat Commun 7, 10238.

**Deutsch et al. (2024) - High-quality Peptide Evidence**
- **Problem**: Lack of standardized evidence for annotating non-canonical ORFs
- **Innovation**: Comprehensive proteome-wide analysis of peptide evidence
- **Key Finding**: Systematic identification of stable non-canonical proteins
- **Technical Advance**: High-quality peptide evidence framework
- **Impact**: Enables accurate annotation of functional non-canonical ORFs
- **Citation**: Deutsch, E.W., et al. (2024). High-quality peptide evidence for annotating non-canonical open reading frames as human proteins. bioRxiv 2024.09.09.612016.

### ncRNA-Derived Peptides

**Balakrishnan et al. (2025) - ncRNA Peptides and Extracellular Vesicles**
- **Innovation**: Focus on non-coding RNA-derived peptides in immune response
- **Key Finding**: EVs transport ncRNA-derived peptides for systemic distribution
- **Novel Mechanism**: Enhanced surface presentation through EV packaging
- **Clinical Potential**: Diagnostic and therapeutic applications
- **Impact**: Reveals new pathway for immune surveillance modulation
- **Citation**: Balakrishnan, A., et al. (2025). Unlocking the secrets of the immunopeptidome: MHC molecules, ncRNA peptides, and vesicles in immune response. Front Immunol 16, 1540431.

### Stable Non-canonical Peptides

**Ji et al. (2024) - Ribosome Profiling Integration**
- **Problem**: Distinguishing functional from spurious non-canonical translation
- **Innovation**: PepScore model based on ORF features (length, domains, conservation)
- **Key Finding**: Stable non-canonical proteins follow conventional rules and localize properly
- **Technical Insight**: Short peptides with low PepScores are directly degraded
- **Impact**: Statistical framework for identifying functional non-canonical peptides
- **Citation**: Ji, Z., et al. (2024). Widespread stable noncanonical peptides identified by integrated analyses of ribosome profiling and ORF features. Nat Commun 15, 1839.

## Mechanistic Understanding

### Translation Quality Control

**Trentini et al. (2020) - Ribosome-Associated Quality Control**
- **Core Finding**: Co-translational quality control contributes to antigen sampling
- **Key Mechanism**: Ribosome stalling enhances MHC presentation of defective proteins
- **Assumption Challenged**: Protein degradation for MHC is purely post-translational
- **Technical Validation**: Experimental demonstration of co-translational sampling
- **Impact**: Links protein synthesis quality to immune surveillance
- **Citation**: Trentini, D.B., et al. (2020). Role for ribosome-associated quality control in sampling proteins for MHC class I-mediated antigen presentation. PNAS 117, 4099-4108.

### RiboSeq and Immunopeptidome Connection

**Holly & Yewdell (2023) - RiboSeq Expansion**
- **Core Insight**: Ribosome profiling reveals extensive non-canonical translation contributing to immunopeptidome
- **Key Finding**: Translatome diversity far exceeds annotated proteome
- **Technical Application**: RiboSeq data essential for comprehensive immunopeptidome analysis
- **Impact**: Paradigm shift toward translation-based understanding of antigen sources
- **Citation**: Holly, J. & Yewdell, J.W. (2023). Game of 'Omes: RiboSeq Expands the MHC I Immunopeptidome. Curr Opin Immunol 83, 102342.

## Quantitative Insights

### Efficiency of Non-canonical Sources

**Key Quantitative Findings:**
1. **Cryptic proteins**: 5-fold higher MHC peptide generation efficiency
2. **Non-canonical proteins**: 28% novel isoforms, 72% cryptic proteins
3. **sORF peptides**: 308 identified from two cell lines (substantial contribution)
4. **UPS-independent peptides**: 30% enriched in mitochondrial proteins (often small)

### Clinical Relevance

**Xu et al. (2024) - Non-canonical Antigens in AML**
- **Clinical Finding**: 6 of 13 prioritized neoantigens derived from non-canonical sources
- **Patient Relevance**: ncMAPs quality comparable or superior to canonical peptides
- **Prognostic Value**: Risk model performance improved with ncMAP inclusion
- **Impact**: Expands therapeutic target space significantly
- **Citation**: Xu, J., et al. (2024). MHC-I-presented non-canonical antigens expand the cancer immunotherapy targets in acute myeloid leukemia. Sci Data 11, 760.

## Technology Enabling Discovery

### High-throughput Detection

**Chang et al. (2025) - Massively Parallel Immunopeptidome**
- **Technical Breakthrough**: DNA sequencing-based approach for immunopeptidome analysis
- **Scale**: Population-wide understanding of HLA binding preferences
- **Sensitivity**: Addresses low-abundance peptide detection challenges
- **Impact**: Overcomes MS limitations for rare but clinically relevant peptides
- **Citation**: Chang, H.Y., et al. (2025). Massively parallel immunopeptidome by DNA sequencing provides population-scale epitope discovery. Nat Genet (in press).

## Common Assumptions Challenged

1. **Canonical proteins dominate immunopeptidome** - Non-canonical sources over-represented
2. **Small proteins contribute proportionally** - Size-efficiency inverse relationship
3. **Alternative reading frames are rare** - Systematic contribution demonstrated
4. **ncRNA translation is non-functional** - Produces functional immunopeptides
5. **Translation quality control is separate from presentation** - Co-translational sampling occurs

## Research Gaps for Our Project

1. **Size-efficiency quantification** - Systematic analysis across protein size ranges
2. **Structural features of cryptic proteins** - What makes them more efficient?
3. **Tissue-specific non-canonical patterns** - Do efficiency patterns vary by tissue?
4. **Stress-induced non-canonical expression** - Dynamic regulation of cryptic sources
5. **Predictive models for source efficiency** - Can we predict which sources will be over-represented?

## Methodological Considerations

### Detection Challenges
- **Sensitivity**: Non-canonical peptides often low abundance
- **Database completeness**: Missing annotations limit discovery
- **Validation**: Experimental confirmation of computational predictions essential

### Integration Approaches
- **Multi-omics**: RiboSeq + MS + proteomics for comprehensive coverage
- **Computational pipelines**: Multiple complementary approaches reduce false negatives
- **Quality metrics**: PepScore-like approaches for functional vs spurious identification