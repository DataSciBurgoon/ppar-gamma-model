# PPAR-gamma Deep Learning QSAR Model

This is a deep learning model that was developed to predict PPAR-gamma ligands (agonists and antagonists). Here are some specs:

1. Accuracy (5-fold cross-validation): 99.74%
2. True Positive Rate: 99%
3. False Positive Rate: 0.5%
4. Probably that a PPAR-gamma ligand will be predicted to be a ligand: P(ligand | predict: ligand): 89%
5. Probability that a non-ligand will be predicted to be a ligand: P(\not{ligand} | predict: ligand): 11%.

You can see the [Jupyter notebook](https://github.com/DataSciBurgoon/ppar-gamma-model/ppar-gamma_ligand_mlp.ipynb).
