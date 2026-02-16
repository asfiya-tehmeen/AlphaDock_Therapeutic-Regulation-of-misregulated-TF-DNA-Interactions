# Therapeutic Targeting of Misregulated Transcription Factor–DNA Interactions

## 📌 Project Overview
Transcription factors (TFs) are master regulators of gene expression and play critical roles in cancer progression. However, TFs are often considered *“undruggable”* due to the lack of well-defined binding pockets. This project explores a **structure-based therapeutic strategy** to inhibit TF–DNA interactions using **minor groove–binding small molecules**.

The study focuses on the ETS family transcription factor **PU.1**, a known oncogenic driver in cancers such as acute myeloid leukemia (AML), and investigates whether a minor groove binder (**DB293**) can interfere with PU.1’s major groove DNA binding.

---

## 🎯 Objective
- To evaluate whether a **sequence-selective minor groove binding ligand** can disrupt or inhibit **major groove transcription factor binding**
- To assess the **structural stability and dynamic behavior** of:
  - PU.1–DNA complex (PDB: 1PUE)
  - DB293–DNA complex (PDB: 2I2I)
- To explore the feasibility of **minor groove binders as selective anti-ETS cancer therapeutics**

---

## 🧪 Methodology
- Molecular Dynamics (MD) simulations performed on:
  - Protein–DNA system (PU.1–DNA)
  - Drug–DNA system (DB293–DNA)
- Simulation duration: **100 ns**
- Structural and dynamic analyses conducted using:
  - RMSD/RMSF trends
  - DNA geometry and groove analysis
  - Nucleic acid interaction plots (nucplots)
- MD simulations executed using **AMBER / AmberTools**

---

## 📊 Key Results & Discussion
- The **DB293–DNA complex** demonstrated stable minor groove binding with local DNA conformational changes.
- These changes may hinder PU.1 binding via **steric or allosteric mechanisms**, consistent with known ETS inhibitors such as mithramycin.
- MD simulations of the **PU.1–DNA system showed anomalous behavior**, indicating the need for protocol refinement.
- Comparative nucplot analysis suggests that DB293 may alter the ETS binding site geometry enough to disrupt TF recruitment.

---

## 🔮 Future Scope
- Refine MD protocols to address abnormal simulation behavior (force fields, equilibration, replicas)
- Simulate **ternary complexes** (PU.1–DNA–DB293) to directly quantify inhibition mechanisms
- Screen **DB293 derivatives** to identify compounds with improved binding affinity and selectivity
- Extend this approach toward rational design of **anti-ETS cancer therapeutics**

---

## 🧠 Significance
This project provides **computational evidence** supporting the concept that **minor groove binders can indirectly target transcription factors**, offering a promising strategy against traditionally undruggable cancer targets.

---

## 📚 References
1. Hsing et al., *Medicinal Research Reviews* (2019) – ETS transcription factors as cancer targets  
2. Munde et al., *Nucleic Acids Research* (2013) – Diamidine inhibition of PU.1  
3. RCSB Protein Data Bank  
4. NCBI  
5. Clustal Omega  
6. AmberTools24  

---

## 👩‍🔬 Author
**Asfiya Tehmeen**  
BITS Pilani – Dubai Campus  
Design Project (Feb 2025 – Jan 2026)
