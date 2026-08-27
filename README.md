# Haroon Khawaja

**Data & AI engineer.** I work on model efficiency — pruning, distillation, low-rank adaptation — and on the enterprise data platforms that put models into production.

Two tracks, deliberately: the research is where I go deep, the platform work is what I ship day to day.

---

## Research — model efficiency

Making large models smaller, cheaper to adapt, and still worth running.

**[BaCP](https://github.com/HaroonKhawaja/BaCP)** — *Backbone Contrastive Pruning*

Prunes a pretrained network to **99% sparsity** while preserving its representations, using a four-term contrastive objective (PrC / SnC / FiC + CE). Benchmarked against magnitude pruning, SNIP-it and WANDA at 0.95 / 0.97 / 0.99 sparsity across ResNet, VGG, ViT, DistilBERT and RoBERTa.

Every equation the code computes is derived to its source in `docs/foundation.md`, with a full citation audit beside it, and the invariants are covered by a pytest suite.

**[LoRA](https://github.com/HaroonKhawaja/LoRA)** — *Low-rank adaptation, from scratch*

Why fine-tuning updates have low intrinsic rank, and what falls out of that — rank decomposition injected into frozen weights, derived and implemented end to end.

**[DPO](https://github.com/HaroonKhawaja/DPO)** — *Direct Preference Optimization*

Preference alignment without reinforcement learning. Built on SmolLM from first principles: no reward model, no PPO, just log-probability ratios between chosen and rejected responses.

---

## Engineering — data platforms

Warehouses, pipelines and the movement of data at enterprise scale. This is the day job.

**[Azure](https://github.com/HaroonKhawaja/Azure)** — change data capture, Delta Live Tables pipelines and ETL patterns on Azure Databricks.

**[SQL-Data-Warehouse-Project](https://github.com/HaroonKhawaja/SQL-Data-Warehouse-Project)** — a dimensional warehouse built from scratch in T-SQL, bronze through gold.

---

## Applied

**[LUMSegmentation](https://github.com/HaroonKhawaja/LUMSegmentation)** — semantic and instance segmentation of field-collected plant imagery. A U-Net with LSTM units and an optimised Mask R-CNN, trained on data I cleaned and annotated by hand. LUMS Directed Research Project.

**[StructureFromMotion](https://github.com/HaroonKhawaja/StructureFromMotion)** — 2D-to-3D reconstruction on the heritage-recon dataset, in OpenCV.

**[machine_learning](https://github.com/HaroonKhawaja/machine_learning)** — backpropagation, knowledge distillation and regression, implemented without frameworks.

---

### Toolkit

`Python` · `PyTorch` · `T-SQL` · `TypeScript`

`Azure Databricks` · `Delta Live Tables` · `Power BI` · `Next.js` · `Prisma`

`OpenCV` · `scikit-learn` · `pandas`
