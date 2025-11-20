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
