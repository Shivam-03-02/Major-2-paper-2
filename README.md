# LACM-Score: Enhanced Node Influence Detection in Complex Networks

This project revisits community detection and centrality measures by introducing **LACM-Score**, a novel composite influence metric. It integrates four structural properties of nodes—**Local Clustering Coefficient**, **Articulation Point Centrality**, **K-Core Number**, and a **Dominating Set–Based Influence Measure**—to provide a deeper, multi-faceted understanding of node importance within networks.

---

## 🔍 Problem Statement

Traditional centrality measures (like Degree, Betweenness, or PageRank) capture limited perspectives of node importance. Our objective is to:
- Combine structural, resilience, and spread potential insights.
- Improve influence-based tasks like community detection and MDS (Minimum Dominating Set) identification.

---

## 🚀 Key Contributions

- 📊 **LACM-Score**: A composite metric combining:
  - **Local Clustering Coefficient**
  - **Articulation Point Centrality**
  - **K-Core Number**
  - **MDS Influence Contribution**
- 📈 Correlation analysis of LACM with other influence measures.
- 🧠 Integration with **Label Propagation Algorithm** to enhance community detection.
- 🧪 Empirical validation using real-world ego networks from Facebook.

---

## 🛠️ Tech Stack

- **Python**
- **NetworkX**
- **Matplotlib & Seaborn** (for visualization)
- **Pandas & NumPy**
- **Jupyter Notebook** (for reproducible analysis)

---

## 📌 Features

- ✅ Computes and visualizes **LACM-Score** for each node.
- ✅ Implements **Label Propagation** for community detection.
- ✅ Detects **Articulation Points** and evaluates their impact.
- ✅ Computes the **Minimum Dominating Set**.
- ✅ Correlates LACM with existing centrality measures.
- ✅ Heatmap visualization of influence measure relationships.

---

## 📉 Sample Heatmap Output

![heatmap](graphs/heatmap.png)

---

## 🧠 Insights

- Nodes with high LACM-Score tend to be both structurally central and resilient.
- Strong positive correlation between LACM and community significance.
- The approach is suitable for social, biological, and communication networks.

---

## 📚 Research Context

This repository supports our research paper:

> **Title:** *Revisiting Community Detection and Centrality: Integrating Label Propagation, and the LACM‑Score for Enhanced Network Insights*  
> **Authors:** Shivam Singh, [Your Teammates Here]  
> *Jaypee Institute of Information Technology, 2025*

---
