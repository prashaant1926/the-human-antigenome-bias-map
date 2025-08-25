

# The Human Antigenome Bias Map

**Core Question:** Which human proteins (including tiny or overlooked ones) are most often shown to the immune system on **MHC molecules** (the cell’s “billboards”), and which are almost never shown?

**Why it matters:**

* The immune system “sees” cells by scanning short protein fragments (peptides) displayed on MHC molecules.
* Some proteins are consistently visible (over-represented), while others are almost invisible (under-represented).
* Knowing these biases can explain **why some tumors or viruses escape immune detection** and guide **better vaccine/therapy design**.

**What the agent does:**

1. Collects all **public datasets** of MHC peptides (from mass spectrometry).
2. Maps those peptides back to their source proteins, including tiny overlooked ORFs from ribosome-profiling studies.
3. Calculates, for each protein: *how many peptides are displayed vs how many you’d expect given size, abundance, and turnover*.
4. Builds a “bias score” → over-represented, under-represented, or neutral.
5. Uses machine learning to find **patterns** that explain the bias: short-lived proteins, disordered regions, transmembrane proteins, etc.
6. Outputs **ranked lists, heatmaps, and explanations** for why each protein is (in)visible.

**Deliverables:**

* A searchable map of all proteins and their “MHC visibility score.”
* Explanations (“Protein X is invisible likely because it’s very stable and sits in mitochondria”).
* A shortlist of **testable experiments** (e.g. “adding a degron should make Protein Y visible”).

