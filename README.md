# 🧬 Offline scRNA-seq Functional Analysis Pipeline

**GO + KEGG + Reactome | Reproducible | Publication-ready**

---

## 📌 Overview

This project presents a **fully reproducible single-cell RNA-seq (scRNA-seq) functional analysis pipeline** with a strong emphasis on:

* Gene Ontology (GO) enrichment
* Pathway analysis (KEGG & Reactome)
* Fully **offline-compatible execution** (critical under restricted network environments)
* Automated biological interpretation and reporting

The pipeline is designed for **research-grade analysis**, suitable for:

* Postdoctoral applications
* Collaborative research
* Manuscript preparation

---

## 🚀 Key Features

### 🔬 Functional Enrichment

* GO: Biological Process (BP), Molecular Function (MF), Cellular Component (CC)
* Pathways:

  * KEGG
  * Reactome

### ⚡ Offline Capability

* Local `.gmt` databases
* No dependency on external APIs (e.g., Enrichr)
* Robust against network restrictions

### 📊 Visualization

* Bubble plots (per cluster)
* Combined enrichment maps
* Category-specific barplots
* Multi-page PDF reports

### 🧠 Intelligent Annotation

* Semi-automated cluster labeling
* Integration of GO + pathway signals
* Biological interpretation-ready output

### 📄 Automated Reporting

* Structured final report
* Clean summary tables
* Ready for manuscript drafting

---

## 🗂 Project Structure

```
project/
│
├── notebooks/
│   ├── n1_preprocessing.ipynb
│   ├── n3_GO_analysis.ipynb
│   ├── n4_pathway_analysis.ipynb
│
├── resources/
│   ├── go/
│   ├── kegg/
│   ├── reactome/
│
├── results/
├── figures/
│
├── README.md
├── requirements.txt
```

---

## ⚙️ Installation

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run notebooks sequentially:

1. Preprocessing & clustering
2. Differential expression analysis
3. GO enrichment (offline)
4. Pathway enrichment (offline)
5. Visualization
6. Integrated summary
7. Cluster annotation
8. Final report generation

---

## 📊 Output

* Enrichment tables (CSV)
* Publication-quality figures (PNG)
* Integrated biological summaries
* Final report (TXT)

---

## 🧪 Example Results

The pipeline identifies:

* Immune-related clusters (T cells, inflammatory responses)
* Pathway-level signatures (KEGG, Reactome)
* Functional heterogeneity across clusters

---

## 💡 Why This Pipeline?

Many existing workflows rely heavily on online services.
This pipeline:

✔ Works **fully offline**
✔ Ensures **reproducibility**
✔ Produces **publication-ready outputs**

---

## 🔧 Technologies Used

* Python (pandas, numpy)
* Scanpy
* GSEApy
* Matplotlib

---

## 📈 Future Directions

* Integration with ligand-receptor analysis
* Multi-omics support
* Automated manuscript drafting

---

## 👤 Author

**Kavoos Momeni**
PhD in Molecular Genetics
Specialized in Bioinformatics & Transcriptomics

---

## 🤝 Collaboration

I am open to:

* Postdoctoral opportunities
* Research collaborations
* Bioinformatics consulting

---

## ⭐ If you find this useful

Please consider starring the repository!

---
