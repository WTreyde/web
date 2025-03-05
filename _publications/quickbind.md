---
title: "QuickBind: A Light-Weight And Interpretable Molecular Docking Model"
collection: publications
category: conferences
permalink: /publication/quickbind
date: 2024-09-04
venue: 'Proceedings of the 19th Machine Learning in Computational Biology meeting'
paperurl: 'https://proceedings.mlr.press/v261/treyde24a.html'
citation: 'Treyde, Wojtek. (2024). &quot;QuickBind: A Light-Weight And Interpretable
Molecular Docking Model.&quot; <i>Proceedings of the 19th Machine Learning in Computational Biology meeting</i>. 261(129).'
---

Predicting a ligand’s bound pose to a target protein is a key component of early-stage computational drug discovery. Recent developments in machine learning methods have focused on improving pose quality at the cost of model runtime. For high-throughput virtual screening applications, this exposes a capability gap that can be filled by moderately accurate but fast pose prediction. To this end, we developed QUICKBIND, a light-weight pose prediction algorithm. We assess QUICKBIND on widely used benchmarks and find that it provides an attractive trade-off between model accuracy and runtime. To facilitate virtual screening applications, we augment QUICKBIND with a binding affinity module and demonstrate its capabilities for multiple clinically-relevant drug targets. Finally, we investigate the mechanistic basis by which QUICKBIND makes predictions and find that it has learned key physicochemical properties of molecular docking, providing new insights into how machine learning models generate protein-ligand poses. By virtue of its simplicity, QUICKBIND can serve as both an effective virtual screening tool and a minimal test bed for exploring new model architectures and innovations. Model code and weights are available at [this GitHub repository](https://github.com/aqlaboratory/QuickBind).