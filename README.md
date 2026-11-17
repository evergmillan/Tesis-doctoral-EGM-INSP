# Tesis-doctoral-EGM-INSP
Tuberías bioinformáticas, análisis estadístico de RT-qPCR (R/tidyverse) y modelado estructural 3D (AlphaFold/TM-align/Foldseek) correspondientes a mi tesis doctoral sobre inmunidad innata en Rhodnius prolixus, vías de RNAi y patogénesis del virus Triatoma (TrV).
# Innate Immune Response and RNAi Mechanisms in *Rhodnius prolixus* During Triatoma Virus (TrV) Infection

This repository contains the supplementary datasets, raw qPCR reports, 3D structural models, sequence homology analyses, and R scripts associated with my doctoral thesis.

## 🔬 Project Overview
*Rhodnius prolixus* is a primary vector of *Trypanosoma cruzi*, the etiological agent of Chagas disease. Triatoma virus (TrV) is an entomopathogenic dicistrovirus that infects triatomines and represents a promising candidate for biological control. This research characterizes the molecular interplay between *R. prolixus* innate immunity and TrV pathogenesis, focusing on:
* **Antiviral RNA interference (RNAi):** Functional characterization of *Dicer-2* (`dcr-2`) via *in vivo* dsRNA microinjection and oral TrV challenge.
* **Transcriptional immune profiling:** RT-qPCR differential expression analysis (`2^-ΔΔCt`) of immune-related genes in the digestive tract.
* **Structural immunology:** 3D protein modeling and structural alignment of *R. prolixus* immune effectors and cytokines (**TEP1** and **Vago**) against arthropod orthologs.

## 📁 Repository Structure

```text
Datos Suplementarios/
├── qPCR_Reportes/               # Raw amplification curves, Ct exports, and thermal cycler run reports
├── Tep1_Rp/                     # AlphaFold 3D models (.pdb) and TM-align/Foldseek alignments for TEP1 (GECK01112131.1)
├── Vago_Rp/                     # AlphaFold 3D models (.pdb) and TM-align/Foldseek alignments for Vago (GAHY01002276.1)
├── Analisis_qPCR_Rp_TrV.xlsx    # Compiled Ct values, ΔCt/ΔΔCt calculations, and relative expression datasets
├── BLASTN_genes_Rp_TrV.xlsx     # Nucleotide homology searches, primer specificity, and target gene annotations
└── Figuras_Suplementarias.docx  # High-resolution supplementary figures and detailed captions
