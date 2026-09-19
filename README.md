# Graph-Driven Multi-Omics Network Modeling for Sickle Cell Disease Biomarker Discovery

## Overview

This project presents a computational bioinformatics framework for **Sickle Cell Disease (SCD) biomarker discovery** using multi-omics data and graph-based network analysis.

The approach integrates biological information from multiple omics sources and represents relationships between relevant molecular entities as networks. Graph-theoretic analysis is then used to identify important nodes, interaction patterns, and potential biomarkers associated with Sickle Cell Disease.

The project combines **bioinformatics, network science, machine learning, and explainable analysis** to support data-driven biomarker discovery.

---

## Objectives

- Analyze omics datasets related to Sickle Cell Disease.
- Perform preprocessing and feature-level analysis of biological data.
- Integrate information from multiple omics sources.
- Construct biological interaction networks using graph-based modeling.
- Analyze network structure using centrality and community-based techniques.
- Identify influential genes/proteins and potential SCD biomarkers.
- Apply explainable computational methods to improve interpretation of discovered biomarkers.

---

## Dataset

Publicly available gene-expression datasets from the **NCBI Gene Expression Omnibus (GEO)** were used in the analysis.

The project works with the following GEO datasets:

- `GSE53441`
- `GSE165689`
- `GSE221740`

The original GEO dataset files are **not included in this repository** because of their size. They can be downloaded directly from the NCBI Gene Expression Omnibus.

---

## Methodology

The overall workflow of the project is:

### 1. Data Acquisition

Relevant Sickle Cell Disease datasets are obtained from public biological repositories such as GEO.

### 2. Data Preprocessing

The datasets are processed and prepared for downstream analysis, including handling biological features and transforming the data into a suitable representation.

### 3. Multi-Omics Analysis

Information from different biological layers is analyzed to capture complementary molecular information associated with Sickle Cell Disease.

### 4. Graph Construction

Biological entities and their relationships are represented as a network:

- **Nodes** represent biological entities such as genes or proteins.
- **Edges** represent relationships or interactions between these entities.

### 5. Network Analysis

Graph-based analysis is performed to identify important structures within the biological network.

This includes techniques such as:

- Degree-based analysis
- Centrality analysis
- Community detection
- Network topology analysis

These measures help identify highly connected or influential biological entities.

### 6. Biomarker Discovery

Important nodes and network patterns are analyzed to identify potential biomarkers associated with Sickle Cell Disease.

### 7. Explainable Analysis

Explainability techniques are incorporated to improve the biological interpretation of computationally identified features and biomarkers.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Network/Graph Analysis
- Data Visualization
- Bioinformatics Data Processing
- Explainable AI (XAI)

---

## Repository Structure

```text
Multi-Omics-Sickle-Cell-Biomarker-Discovery/
│
├── Bioinformatics_improved.ipynb
│   └── Main notebook containing preprocessing, analysis,
│       network modeling, and biomarker discovery workflow
│
├── Graph-Driven-Multi-Omics-Network-Modeling-for-
│   Sickle-Cell-Disease-Biomarker.pptx
│   └── Project presentation
│
├── Outputs/
│   ├── image1.png
│   ├── image2.png
│   ├── ...
│   └── image13.png
│       └── Visualizations and experimental outputs
│
├── .gitignore
│
└── README.md
```

---

## Key Features

- Multi-omics approach to Sickle Cell Disease analysis
- Graph-driven biological network modeling
- Identification of influential molecular entities
- Centrality and community-based network analysis
- Biomarker discovery from biological interaction networks
- Explainable and interpretable analysis
- Visualization of biological relationships and experimental results

---

## Applications

The framework can support research in:

- Sickle Cell Disease biomarker discovery
- Disease-associated gene identification
- Molecular network analysis
- Multi-omics data integration
- Computational biology
- Precision medicine research
- Explainable AI for biomedical applications

---

## Future Work

Future extensions of the project can include:

- Integration of additional omics datasets
- Validation of identified biomarkers using independent cohorts
- Graph Neural Networks (GNNs) for biomarker prediction
- Improved multi-omics fusion techniques
- Pathway enrichment and functional analysis
- Experimental validation of candidate biomarkers

---

## Author

**Sree Darshne J**  
Integrated M.Tech – Computer Science and Engineering  
Business Analytics Specialization  
Vellore Institute of Technology (VIT), Chennai

---

## Disclaimer

This project is intended for **academic and research purposes**. The identified biomarkers and computational results require further biological and clinical validation before they can be considered for medical applications.
