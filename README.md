# FXR-RXR_analysis

Allosteric signal transduction in FXR/RXR heterodimers bound to steroidal antagonists.

## Background

Bile acids are steroidal signalling molecules that regulate glucose, lipid and energy homeostasis through the farnesoid X receptor (FXR) and the G-protein bile acid receptor 1 (GPBAR1). FXR is a nuclear receptor and a transcription factor: an N-terminal DNA-binding domain is connected to a ligand-binding domain (LBD) made of a three-layered α-helical sandwich (helices H1–H12). The LBD holds a large lipophilic ligand-binding pocket and the activation function-2 (AF2) surface (helices 3, 4, 5 and 12), which recruits coactivators or corepressors depending on the bound ligand.

This repository analyzes how steroidal antagonists change the conformational dynamics and allosteric communication of the FXR/RXR heterodimer.

## Contents

| File | Description |
|---|---|
| `MSM_FXR-RXR-gmf.ipynb` | Markov state model (PyEMMA): featurization, clustering, implied timescales, metastable states |
| `Angle-Vector-domain.ipynb` | Angle between domain vectors along the trajectory (MDAnalysis) |
| `n5states_state01–05.pdb` | Representative structures of the five metastable states |

## Requirements

Python 3 with Jupyter and the libraries listed below. Trajectories and
Schrödinger Suite outputs are **not** included in this repository.

```bash
pip install jupyter numpy matplotlib MDAnalysis pyemma mdtraj nglview mdshare
```

## Author

**Glaucio Monteiro Ferreira** — Research Associate, Institute of Chemistry, University of São Paulo (IQ-USP) · [LIBNM · Ferreira Lab](https://ferreiralab.com.br) · [ORCID](https://orcid.org/0000-0002-1952-9428) · [FAPESP profile](https://bv.fapesp.br/pt/pesquisador/703612/glaucio-monteiro-ferreira/) · [gmf@usp.br](mailto:gmf@usp.br)
