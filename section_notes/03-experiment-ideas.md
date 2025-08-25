

### Experiment 1: Structural Determinism Validation (H001)

**Thesis Statement:** Intrinsic protein structural features determine MHC presentation bias independent of protein abundance.

**Testable Hypotheses:**
- H1a: Proteins with high intrinsic disorder (>30% disordered regions) show 2-fold lower presentation rates when normalized for abundance
- H1b: Proteins with specific degradation motifs (PEST sequences, degrons) show predictable presentation patterns
- H1c: Subcellular localization significantly affects presentation probability (cytoplasmic > nuclear > ER > mitochondrial)

**Dependent Variables (Measurements):**
- Presentation Index: (observed peptides/protein length) normalized by protein abundance
- Structural Disorder Score: % residues in disordered regions (IUPred2A)
- Degradation Signal Density: PEST motifs and degron count per 100 amino acids
- Localization Confidence: UniProt/HPA subcellular localization scores

**Independent Variables (Manipulations):**
- Protein structural class: ordered vs. disordered vs. mixed
- Degradation motif presence: high vs. low PEST density
- Subcellular compartment: 5 major localizations
- Tissue type: 8-12 representative human tissues

**Experimental Tasks/Procedures:**
1. Curate comprehensive MHC-I peptide datasets (IEDB, SysteMHC, tissue atlases)
2. Calculate presentation indices for 15,000+ human proteins
3. Predict structural features using IUPred2A, PEST-find, DeepLoc
4. Perform multivariate regression: Presentation ~ Structure + Localization + Controls
5. Validate with independent test set (20% holdout)
6. Cross-validate across different MHC allotypes

**Validity Threats & Mitigations:**
- *Confounding by abundance*: Include protein abundance as covariate, use tissue-matched proteomics
- *Technical MS bias*: Include peptide detectability scores, validate across MS platforms
- *Annotation errors*: Use multiple prediction tools, validate key predictions experimentally
- *Population stratification*: Include diverse HLA backgrounds, population-stratified analysis

**Required Resources & Timeline:**
- Computational: AWS/Azure credits for large-scale predictions (~$2K)
- Personnel: 1 bioinformatician (3 months), 1 statistician (1 month)
- Data: Public datasets (free), commercial structure predictions ($500)
- Timeline: 4 months for complete analysis and validation

---

### Experiment 2: Micro-protein Invisibility Test (H002)

**Thesis Statement:** Small proteins and cryptic ORFs are systematically invisible to immune surveillance due to insufficient processing sites.

**Testable Hypotheses:**
- H2a: Proteins <100 amino acids show 3-fold lower presentation rates per amino acid
- H2b: Cryptic ORFs (alt-ORFs, uORFs) are under-represented despite detectable expression
- H2c: Processing site density (proteasomal cleavage sites/length) predicts small protein visibility

**Dependent Variables:**
- Size-normalized Presentation Rate: peptides per 100 amino acids
- Processing Site Density: predicted cleavage sites per protein length
- Expression Detection Rate: fraction of small proteins detected in proteomics vs. transcriptomics

**Independent Variables:**
- Protein size classes: <50, 50-100, 100-200, 200-500, >500 amino acids
- ORF type: canonical, alternative, upstream, overlapping
- Processing context: cytoplasmic vs. ER-processed proteins

**Experimental Tasks/Procedures:**
1. Compile comprehensive small protein catalog (canonical + cryptic ORFs)
2. Map all detected small proteins in immunopeptidome datasets
3. Calculate size-stratified presentation statistics
4. Predict proteasomal cleavage sites using NetChop, ProteaSMM
5. Correlate processing site density with observed presentation
6. Validate predictions with targeted MS analysis of selected small proteins

**Validity Threats & Mitigations:**
- *Detection limits*: Use high-sensitivity MS data, include technical detection controls
- *Annotation bias*: Include computational ORF predictions, ribosome profiling data
- *Sample preparation bias*: Validate across different cell lysis and enrichment methods

**Required Resources & Timeline:**
- Bioinformatics analysis: 2 months
- Targeted MS validation: $5K for custom peptide synthesis and analysis
- Timeline: 3 months total

---

### Experiment 3: Tissue-Specific Antigenome Mapping (H003)

**Thesis Statement:** Each tissue maintains distinct antigenome signatures reflecting tissue-specific proteasomal activity and cellular functions.

**Testable Hypotheses:**
- H3a: Tissue pairs show >30% difference in protein presentation rankings
- H3b: Tissue-specific proteins (Tau >0.8) show enhanced presentation in cognate tissues
- H3c: Immunoproteasome vs. constitutive proteasome tissues show distinct presentation patterns

**Dependent Variables:**
- Tissue Presentation Signature: ranked list of presentation indices per tissue
- Tissue Specificity Score: correlation between tissue-specific expression and presentation
- Proteasome Activity Pattern: immunoproteasome vs. constitutive subunit ratios

**Independent Variables:**
- Tissue type: brain, liver, kidney, heart, lung, spleen, muscle, skin
- Proteasome composition: high vs. low immunoproteasome content
- Cellular stress state: baseline vs. inflammation-induced

**Experimental Tasks/Procedures:**
1. Collect tissue-specific MHC peptide datasets (GTEx-based, organ transplant studies)
2. Calculate tissue-specific presentation indices for each protein
3. Perform hierarchical clustering of tissues by presentation signatures
4. Correlate with tissue-specific gene expression (GTEx, HPA)
5. Map proteasome subunit expression patterns across tissues
6. Validate key predictions with tissue-specific cell culture experiments

**Validity Threats & Mitigations:**
- *Sample heterogeneity*: Use carefully matched tissue samples, control for cellular composition
- *Technical batch effects*: Include cross-tissue controls, batch correction methods
- *Confounding by disease*: Use healthy tissue controls, exclude diseased samples

**Required Resources & Timeline:**
- Data curation and analysis: 3 months
- Validation experiments: $8K for cell culture and targeted MS
- Timeline: 5 months total

---

### Experiment 4: Dynamic Stress-Response Antigenome (H004)

**Thesis Statement:** Cellular stress fundamentally rewires the antigenome by altering proteasomal targeting and revealing cryptic proteins.

**Testable Hypotheses:**
- H4a: Heat shock (42°C, 2h) increases presentation of normally invisible proteins by >50%
- H4b: Oxidative stress reveals mitochondrial and ER stress response proteins
- H4c: Proteasomal inhibition followed by recovery shows wave-like presentation changes

**Dependent Variables:**
- Stress-Induced Presentation Change: fold-change in presentation indices
- Protein Visibility Class Transition: proteins switching between visible/invisible classes
- Temporal Presentation Pattern: time-course of presentation changes

**Independent Variables:**
- Stress type: heat shock, oxidative (H2O2), ER stress (tunicamycin), proteasome inhibition (MG132)
- Stress intensity: low, medium, high (dose-response)
- Recovery time: 0, 2, 6, 12, 24 hours post-stress

**Experimental Tasks/Procedures:**
1. Design cell culture stress protocols with multiple timepoints
2. Perform MHC peptide immunoaffinity purification and MS analysis
3. Map stress-induced changes in presentation patterns
4. Correlate with stress response protein expression (proteomics)
5. Track temporal dynamics of antigenome rewiring
6. Validate key findings with targeted stress response experiments

**Validity Threats & Mitigations:**
- *Cell viability effects*: Monitor cell death markers, use sub-lethal stress levels
- *Indirect effects*: Include appropriate controls, time-matched unstressed samples
- *Technical variability*: Use biological replicates, standardized stress protocols

**Required Resources & Timeline:**
- Cell culture and MS analysis: $12K for reagents and instrument time
- Personnel: 1 experimentalist (4 months)
- Timeline: 6 months including optimization and validation

## Ablations & Control Experiments

### Critical Controls
- **Remove abundance normalization**: Test if structural effects persist without abundance correction
- **Randomize protein assignments**: Shuffle structural features to test specificity
- **Single-allotype analysis**: Test if patterns hold within individual HLA allotypes
- **Cross-species validation**: Test key predictions in mouse immunopeptidome data

### Parameter Sensitivity
- **Disorder threshold variation**: Test 20%, 30%, 40% disorder cutoffs
- **Size boundary optimization**: Test 75, 100, 125 amino acid cutoffs for small proteins
- **Stress duration titration**: Test 1h, 2h, 4h stress treatments

## Baselines & Comparisons

### Baseline Models
- **Abundance-only model**: Presentation predicted solely by protein expression levels
- **Random selection**: Null model with random peptide selection proportional to protein size
- **Current MHC prediction tools**: NetMHCpan, MixMHCpred for binding prediction comparison

### State-of-the-art Comparisons
- **DeepHLApan**: Latest deep learning MHC presentation predictor
- **IEDB analysis resource**: Established immunoinformatics benchmark
- **HLA-CNN**: Convolutional neural network for HLA binding prediction

**Expected Performance:**
- Structural model should outperform abundance-only by >20% AUC
- Tissue-specific models should improve prediction accuracy by >15%
- Dynamic models should capture stress-induced changes with >0.7 correlation

## Priority Classification

### Must Have (Critical for Validation)
1. **Experiment 1** (Structural Determinism): Core hypothesis validation
2. **Abundance normalization controls**: Essential for establishing causality
3. **Cross-tissue validation**: Required for generalizability claims
4. **Size effect quantification**: Critical for micro-protein hypothesis

### Nice to Have (Robustness & Impact)
1. **Full stress-response mapping**: Extends impact but not essential for core claims
2. **Cross-species validation**: Important but can be follow-up work
3. **Clinical validation**: High impact but resource-intensive
4. **Therapeutic predictions**: Future applications, not immediate validation

### Resource Allocation
- **Phase 1** (Months 1-3): Experiments 1 & 2 (structural determinism, size effects)
- **Phase 2** (Months 4-6): Experiment 3 (tissue specificity)
- **Phase 3** (Months 7-9): Experiment 4 (stress response) and validation

**Total Estimated Cost:** $30K
**Total Timeline:** 9 months
**Expected Publications:** 2-3 high-impact papers + multiple follow-up studies