

### H003: Tissue-Specific Antigenome Hypothesis
**Assumption to Challenge:** Immunopeptidome findings from accessible tissues represent universal patterns.

**Novel Hypothesis:** Each tissue has fundamentally different 'antigenome signatures' based on unique proteasomal activity, stress responses, metabolic states.

**Specific Predictions:**
- >50% of presented peptides will be tissue-specific across major organ systems
- Metabolically active tissues (liver, muscle, brain) will show 2-4x higher presentation diversity
- Tissue-specific transcription factors will be over-represented in tissue-matched antigenomes
- Proteasomal subunit composition differences will predict presentation patterns
- Cross-tissue antigenome similarity will correlate with developmental origin (R² > 0.6)

**Falsifiability Criteria:**
- If <20% of peptides show tissue specificity
- If proteasomal composition fails to predict presentation differences
- If developmental origin shows no correlation with antigenome patterns (R² < 0.3)

**Mechanistic Basis:** Tissue-specific proteasomal subunits (β1i, β2i, β5i immunoproteasomes vs. constitutive) create different cleavage preferences. Unique stress responses, metabolic pathways, and transcriptional programs generate tissue-specific protein pools with distinct degradation signals.

**Impact:** Would transform precision immunotherapy requiring tissue-specific strategies.

### H004: Dynamic Stress-Response Antigenome Hypothesis
**Assumption to Challenge:** MHC presentation remains relatively stable across cellular states.

**Novel Hypothesis:** Cellular stress fundamentally rewires the antigenome by altering proteasomal targeting, revealing normally 'invisible' proteins.

**Specific Predictions:**
- Heat shock, oxidative stress, or ER stress will alter >30% of presented peptides within 4-8 hours
- Stress-induced proteins (HSPs, chaperones, antioxidants) will show 5-10x increased presentation
- Normally nuclear proteins will appear in antigenome under stress due to nuclear envelope breakdown
- Stress-specific peptides will correlate with unfolded protein response activation markers
- Recovery from stress will restore baseline antigenome within 12-24 hours

**Falsifiability Criteria:**
- If <10% of peptides change under any stress condition
- If stress proteins fail to show increased presentation
- If nuclear proteins remain absent from stress antigenomes
- If changes persist >48 hours after stress removal

**Mechanistic Basis:** Stress induces proteasomal remodeling (constitutive → immunoproteasome), alters protein folding states exposing cryptic degradation signals, disrupts compartmentalization, and activates quality control pathways preferentially targeting damaged proteins for degradation.

**Impact:** Would enable timing-based interventions, explain variable immune responses.

## Methodological Approach

### Phase 1: Establish the Priors
- Systematic literature review identifying implicit assumptions about MHC presentation
- Map contradictions and gaps in current models
- Document tissue-specific and context-dependent findings

### Phase 2: Hypothesis Testing Framework
1. **Data Integration**: Collect comprehensive MHC peptide datasets across tissues, conditions, disease states
2. **Structural Analysis**: Integrate protein disorder, degradation signals, localization predictions
3. **Bias Quantification**: Calculate presentation scores normalized for abundance, size, turnover
4. **Pattern Discovery**: Machine learning to identify structural determinants of visibility classes
5. **Validation Experiments**: Design targeted experiments to test specific predictions

### Phase 3: Impact Validation
- Demonstrate how findings affect existing immunotherapy approaches  
- Show predictive power for vaccine design and immune evasion
- Validate tissue-specific and dynamic presentation patterns

## Research Vectoring Strategy

**Highest Risk Dimension:** The structural determinism hypothesis - if protein structure doesn't predict presentation bias better than abundance, the entire framework needs revision.

**Critical Validation:** Can we predict which proteins will be over/under-represented based solely on structural features, independent of abundance data?

**Immediate Risk Assessment:**
1. **H001 Structural Determinism** (HIGHEST RISK): Foundation for entire framework
   - **Test First**: Cross-validate structural features vs. abundance in existing datasets
   - **Success Metric**: Structure explains ≥60% variance in presentation bias
   - **Failure Point**: <30% variance explained by structural features

2. **H002 Micro-protein Invisibility** (MEDIUM RISK): Well-supported mechanistically
   - **Test First**: Analyze size-bias in current immunopeptidome databases
   - **Success Metric**: Clear inverse correlation (R² > 0.7) between size and presentation
   - **Failure Point**: No size correlation (R² < 0.3)

3. **H003 Tissue Specificity** (LOW-MEDIUM RISK): Literature suggests tissue differences exist
   - **Test First**: Compare existing tissue datasets for overlap patterns
   - **Success Metric**: <50% peptide overlap between distant tissue types
   - **Failure Point**: >80% overlap across all tissues

4. **H004 Dynamic Stress Response** (MEDIUM RISK): Least prior evidence but mechanistically plausible
   - **Test First**: Meta-analysis of stress vs. control immunopeptidomes
   - **Success Metric**: ≥30% peptide changes under stress conditions
   - **Failure Point**: <10% changes under any stress condition

**Failure Modes:** 
- If patterns are purely stochastic (no structural determinism)
- If tissue differences are minimal (no tissue specificity)  
- If dynamic changes are marginal (no stress rewiring)

**Risk Mitigation Strategy:**
- Test H001 first with existing data before generating new experiments
- Develop structural prediction models using machine learning
- Design orthogonal validation experiments for each hypothesis

## Expected Deliverables

### Immediate Outputs
- Comprehensive human antigenome bias map with mechanistic explanations
- Predictive models for protein visibility based on structural features
- Tissue-specific antigenome signatures
- Dynamic presentation patterns under cellular stress

### Long-term Impact
- Paradigm shift from abundance-based to structure-based understanding of immune presentation
- Rational design principles for vaccines targeting 'invisible' proteins
- Precision immunotherapy strategies based on tissue-specific antigenomes
- Temporal intervention windows based on dynamic presentation patterns

## Experimental Validation Pipeline

1. **Structural Predictions**: Test whether disorder/degradation motifs predict under-representation
2. **Size Effects**: Validate micro-protein invisibility through targeted MS analysis  
3. **Tissue Specificity**: Compare antigenomes across multiple tissue types
4. **Dynamic Changes**: Map presentation changes under defined stress conditions
5. **Therapeutic Validation**: Test predictions in relevant disease models

