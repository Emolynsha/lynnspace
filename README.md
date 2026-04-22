# lynnspace
# Research Design — Master Project
## Design of Solid Polymer Electrolytes Using VAE and GNN

**Student:** Marcelle Lynsha Emo Meguedjeu  
**Supervisor:** Prof. Ernest Fokoue, Rochester University  
**Institution:** AIMS Rwanda  
**Submission:** June 2026  

---

## How to Use This Research Design

This folder contains the complete blueprint for your master thesis. Each file corresponds to one phase of the project. Read them in order, follow the tasks, and by Week 10 you will have all the material needed to write your manuscript.

```
research_design/
├── 00_README.md                  ← You are here
├── 01_scientific_context.md      ← Background, problem statement, objectives
├── 02_literature_review.md       ← What to read, key papers, synthesis guide
├── 03_data_pipeline.md           ← Dataset construction (step-by-step)
├── 04_chgnet_prediction.md       ← GNN model: CHGNet fine-tuning
├── 05_vae_architecture.md        ← VAE model: architecture + supervised loss
├── 06_training_strategy.md       ← Training, hyperparameters, evaluation
├── 07_results_analysis.md        ← How to analyze, visualize, interpret results
├── 08_10week_schedule.md         ← Week-by-week execution plan
└── 09_thesis_writing_guide.md    ← Chapter-by-chapter manuscript guide
```

---

## Project in One Sentence

> Use a **Supervised Variational Autoencoder** to generate novel solid polymer electrolyte candidates, guided by a fine-tuned **CHGNet** model that predicts ionic conductivity — enabling AI-driven inverse design of next-generation battery materials.

---

## Core Stack

| Tool | Purpose |
|---|---|
| `chgnet` | GNN for ionic conductivity prediction |
| `torch` + `torch-geometric` | VAE implementation |
| `pymatgen` | Crystal structure manipulation |
| `rdkit` | Polymer SMILES → 3D graphs |
| `matminer` | Feature engineering |
| `mp-api` | Materials Project data |
| `ase` | Atomic simulation environment |
