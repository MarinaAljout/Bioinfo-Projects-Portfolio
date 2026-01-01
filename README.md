# My Bioinformatics Learning Journey 🧬💻

This repository documents my transition from Pharmacy to Bioinformatics, showcasing Python tools developed to solve real-world biological and clinical problems.

---

## 🚀 Projects & Exercises

### 1. Clinical Dosage & Safety Basics
**Stage:** Python Basics & Mathematical Modeling.
- **Description:** A simple tool for calculating patient-specific dosages and checking basic safety interactions.
- **Files:** `Clinical_Dosage_Analyzer.ipynb`

### 2. Pharmacogenomics (PGx) Support Tool
**Stage:** Data Management & Clinical Logic.
- **Description:** An exercise to link genomic variants (e.g., CYP2C19) with drug recommendations based on CPIC guidelines.
- **Files:** `PGx_Analysis_Tool.ipynb`, `drugsdata.csv`

### 3. DNA Sequence Mutation Scanner
**Stage:** Advanced Logic & Genomic Parsing.
- **Description:** A tool that searches for specific gene segments (Motifs) within raw DNA sequences. It calculates sequence length and detects "Frameshift Mutations" by validating if the segment length is a multiple of 3 (Codon logic).
- **Files:** `DNA_Sequence_Analysis.ipynb`

### 4. Protein Synthesis & Mutation Analyzer
**Stage:** Biochemical Modeling & Physicochemical Analysis.

* **Description:** A more advanced tool that simulates the translation of mRNA into protein sequences. It features a mutation simulator and calculates the total Molecular Weight (in Daltons) of the resulting protein, helping to visualize the impact of Nonsense and Missense mutations.
* **Files:** `Protein_Synthesis_Tool.ipynb`

### 5. Genomic Data Statistics & Visualization
**Stage:** Advanced Data Handling & Statistical Plotting.

* **Description:** A robust tool for processing multi-sequence FASTA files. It performs comparative sequence analysis (calculating total counts, average/max/min lengths, and GC content) and generates a distribution histogram to visualize genomic data variability.
* **Files:** `Genomic_Data_Analysis_Orchid_Dataset.ipynb`

### 6. COVID-19 Virtual Drug Screening Tool
**Stage:** Computational Chemistry & Molecular Docking.

* **Description:** A simulation tool that performs "Molecular Docking" to predict the effectiveness of various FDA-approved drugs against the COVID-19 virus. The tool automates testing multiple molecules (e.g., Etoricoxib, Ibuprofen, Codeine) against the SARS-CoV-2 Main Protease (PDB: 6LU7), calculates binding affinities (kcal/mol), and ranks them to identify the most potent inhibitor. It includes interactive 3D visualization of the protein-drug complex to analyze binding sites.
* **Files:** `COVID19_Docking_Screening.ipynb`, `receptor.pdbqt`

---

## 🛠 Skills I'm Practicing
- **Clinical Decision Support Systems (CDSS):** Dosage calculation and safety logic.
- **Genomic Data Parsing:** DNA/RNA sequence analysis and mutation scanning.
- **Computational Drug Discovery:** Molecular docking simulations and virtual screening.
- **3D Molecular Visualization:** Rendering protein-ligand complexes using `py3Dmol`.
- **Chemical Informatics:** Handling SMILES strings and molecular file formats (PDB, PDBQT).
- **Python for Healthcare:** Using logic and data handling to solve pharmacological problems.


## 💡 How to explore
Run the notebooks in Google Colab. Each file represents a different step in my learning journey.
