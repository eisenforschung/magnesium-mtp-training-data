# Supplementary Data & Code

This is the supplementary for the paper [Systematic Atomic Structure Datasets for Machine Learning Potentials: Application to Defects in Magnesium](https://arxiv.org/abs/2207.04009).
It contains notebooks and pyiron projects to analyse the training data used in the potential and run lammps simulations with the potentials fitted in it.
The full training data needs to be downloaded from [Edmond](https://edmond.mpdl.mpg.de/dataset.xhtml?persistentId=doi:10.17617/3.A3MB7Z).
The `Unpack.ipynb` notebook contains code to do this and import the pyiron projects.
To fully utilize the code here you will need a running version of pyiron, which you can install with the `requirements.txt` file provided in this repository.
From a linux/macos shell run
```bash
pip install -r requirements.txt
```
then run the `Unpack.ipynb` jupyter notebook.
See [the official documentation](https://jupyter.org/install) on how to install jupyer.

## Example Structure Generation

The `RandSPGExample.ipynb` notebook shows how to setup a similar training set as in the paper for any unary.  Binary or higher compounds are also possible, but require some straightforward modifications in the code.

## Citation

If you use this training data or the potentials in your work, please cite the paper and dataset linked above.

```
@data{3.A3MB7Z_2022,
author = {Poul, Marvin},
publisher = {Edmond},
title = {{Data For: Systematic Atomic Structure Datasets for Machine Learning Potentials: Application to Defects in Magnesium}},
year = {2022},
version = {V1},
doi = {10.17617/3.A3MB7Z},
url = {https://doi.org/10.17617/3.A3MB7Z}
}
```

```
@article{poul2023systematic,
  title={Systematic atomic structure datasets for machine learning potentials: Application to defects in magnesium},
  author={Poul, Marvin and Huber, Liam and Bitzek, Erik and Neugebauer, J{\"o}rg},
  journal={Physical Review B},
  volume={107},
  number={10},
  pages={104103},
  year={2023},
  publisher={APS}
}
```
