# Scientific Visualization Project – GO Terms & HPO Analysis
Porcelli Angelica - 78083A, 
Roveda Gianluca - 73814A,
Stefanelli Marta - 84393A

---

This repository contains the work developed for the **Scientific Visualization course project (Exercise 2)**.  
The goal of the project is to explore and visualize biological datasets based on **Gene Ontology (GO) terms** and **Human Phenotype Ontology (HPO)**, and to build a complete analysis pipeline.

---

## Repository Structure

The repository includes several Jupyter notebooks representing different stages of the workflow:

### **Final_Workflow.ipynb**
**This is the main and complete pipeline selected for the final analysis.**  
It includes:
- Data cleaning and preprocessing  
- GO integration  
- Affinity matrix construction  
- Data fusion - SNF
- Clustering  - HDBSCAN and UMAP visulization
- Visualization and interpretation  
- Try MOFA

### **Individual Workflows**
These notebooks contain the separate analyses performed before merging them:
- `Workflow_BP.ipynb` – Biological Process (GO BP)
- `Workflow_MF.ipynb` – Molecular Function (GO MF)
- `Workflow_CC.ipynb` – Cellular Component (GO CC)
- `Workflow_HPO.ipynb` – Human Phenotype Ontology (HPO)

Each workflow explores the structure of the data and performs feature filtering, affinity estimation, and preliminary visualizations.

### **Union_Workflow Files**
These notebooks represent the **intermediate fusion step** where GO BP, MF, CC, and HPO were combined:
- `Union_Workflow*.ipynb`

They were used to test multi-view integration approaches before defining the final pipeline.

---

## Final Output

**The authoritative and complete analysis is in `Final_WorkFlow.ipynb`.**  
All other notebooks document the steps taken to reach the final solution.

---

## Conclusion
In conclusion, this repository presents the full development of a multi-view analysis pipeline built on GO terms (BP, MF, CC) and HPO data. After an initial phase in which each ontology was explored independently, we implemented an integration strategy using Similarity Network Fusion (SNF), followed by clustering (HDBSCAN) and visualization (UMAP). This approach enabled the identification of biologically meaningful clusters.

For each identified cluster, we analyzed the most impactful GO terms to interpret their functional significance. The results of this analysis are summarized in two PDF documents, which provide a detailed description of the key GO terms associated with each cluster. These documents also include a discussion produced with the support of AI tools, which were given the full GO enrichment results to help synthesize and interpret the findings.
