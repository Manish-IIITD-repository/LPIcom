# LPIcom: Analysis, Comparison, and Prediction of Protein-Ligand Binding Sites

Welcome to the official documentation for **LPIcom**, a comprehensive web server designed to facilitate the understanding of protein-ligand interactions. As understanding how proteins interact with a wide range of ligands is a major challenge in systems biology, LPIcom provides tools to analyze, compare, and predict interacting residues for over 800 different ligands.

**Web Server:** [http://crdd.osdd.net/raghava/lpicom/](http://crdd.osdd.net/raghava/lpicom/)

---

## Citation

Singh, H., Srivastava, H. K., & Raghava, G. P. S. (2016). 
**A web server for analysis, comparison and prediction of protein ligand binding sites.** *Biology Direct*, 11, 14. 
[https://doi.org/10.1186/s13062-016-0118-5](https://doi.org/10.1186/s13062-016-0118-5)

Zenodo:-(https://doi.org/10.5281/zenodo.20097695)

---

## About the Platform

LPIcom was developed to bridge the gap in ligand-binding site prediction, which has traditionally been limited to a small number of well-studied ligands. By utilizing data from the Protein Data Bank (PDB), LPIcom offers insights into the binding preferences and structural motifs of 824 unique ligands.

### Database Criteria
* **Ligand Inclusion**: Every ligand included in the server has at least 30 experimentally determined protein-binding sites in the PDB.
* **Binding Site Definition**: Interacting residues are defined based on a distance-based cutoff between the protein atoms and the ligand atoms.

---

## Key Modules

### 1. Analysis Module
This module allows users to identify residue preferences and binding motifs for a specific ligand.
* **Residue Propensity**: Calculates which amino acids are frequently involved in binding (e.g., Glycine, Lysine, and Arginine are preferred in ATP binding sites).
* **Motif Discovery**: Identifies conserved sequence patterns that characterize the binding site of a given ligand.

### 2. Comparison Module
This module enables the comparison of binding sites across multiple ligands to identify similarities in their interaction profiles.
* **Clustering**: Groups ligands based on the similarity of their interacting residues.
* **Cross-Ligand Insights**: Useful for discovering why certain ligands (like ATP, ADP, and GTP) share similar binding environments.

### 3. Prediction Module
A propensity-based method to predict potential ligand-binding residues within a protein sequence or structure.
* **High-Throughput Screening**: Allows for the rapid identification of potential interaction sites for hundreds of ligands.

---

## Technical Overview

LPIcom utilizes a robust computational framework to process and visualize complex interaction data.

* **Data Source**: Derived from the PDB using the CCPDB (Compilation and Creation of data sets from Protein Data Bank) tool.
* **Metrics**: Uses standard propensity scores and residue conservation metrics to define binding signatures.
* **Visualizations**: Integrated tools for viewing sequence logos and interaction clusters.

---

## Applications

* **Drug Discovery**: Identifying potential off-target interactions by comparing binding site similarities across different drug classes.
* **Protein Engineering**: Designing or modifying binding sites to alter ligand specificity.
* **Functional Annotation**: Predicting the function of uncharacterized proteins by identifying their potential ligand-binding partners.

---

## Contact & Authors

**Prof. Gajendra P. S. Raghava**
Department of Computational Biology, Indraprastha Institute of Information Technology (IIIT-Delhi), New Delhi, India.
**Email**: raghava@iiitd.ac.in / raghava@imtech.res.in

---

## License

This resource is open-access and distributed under the terms of the **Creative Commons Attribution 4.0 International License**, permitting unrestricted use and distribution provided the original work is properly credited.
