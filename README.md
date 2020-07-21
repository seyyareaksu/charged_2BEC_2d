# charged_2BEC_2d

Gross-Pitaevskii solution of charged two component Bose-Einstein Condensates in two dimensions using XMDS2  software package. 

Notation follows [Phase separation in a mixture of charged Bose-Einstein condensates](https://arxiv.org/abs/2005.08055).

# Installation 

- Create conda environment from file 

> conda env create -f environment_c2bec2d_xmds.yml

- Export conda environment if updated:

> conda env export > environment_c2bec2d_xmds.yml

- Install explicit conda environment for linux

> conda create --name myenv --file spec-file_c2bec2d_xmds.txt

- Export explicit conda environment for linux if updated:

> conda list --explicit > spec-file_c2bec2d_xmds.txt

- Scripts require that [xmds](http://www.xmds.org/) to be installed on the system.

# Example

Follow busch.ipynb for implementation of [Emergence of classical rotation in superfluid Bose-Einstein condensates](https://arxiv.org/abs/1509.01911).
