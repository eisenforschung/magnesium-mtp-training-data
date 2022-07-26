# Supplementary Data & Code

This is the supplementary for the paper [Systematic Atomic Structure Datasets for Machine Learning Potentials: Application to Defects in Magnesium](https://arxiv.org/abs/2207.04009).
It contains notebooks and pyiron projects to analyse the training data used in the potential and run lammps simulations with the potentials fitted in it.
The full training data needs to be downloaded from [Edmond](https://edmond.mpdl.mpg.de/dataset.xhtml?persistentId=doi:10.17617/3.A3MB7Z).
The `Unpack.ipynb` notebook contains code to do this and import the pyiron projects.
To fully utilize the code here you will need a running version of pyiron, which you can install with the `requirements` file provided in this repository.
From a linux/macos shell run
```bash
pip install -r requirements
```
then run the `Unpack.ipynb` jupyter notebook.
See [the official documentation](https://jupyter.org/install) on how to install jupyer.

## Citation

If you use this training data or the potentials in your work, please cite the paper linked above.

```
@article{poul2022systematic,
  title={Systematic Structure Datasets for Machine Learning Potentials: Application to Moment Tensor Potentials of Magnesium and its Defects},
  author={Poul, Marvin and Huber, Liam and Bitzek, Erik and Neugebauer, J{\"o}rg},
  journal={arXiv preprint arXiv:2207.04009},
  year={2022}
}
```