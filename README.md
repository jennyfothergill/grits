# GRiTS : Grits Reduce/Restore (i) Topology with SMILES
A toolkit for working with coarse-grain systems using mbuild and fresnel

Minimal install
```
conda create -yn grits -c conda-forge -c omnia -c mosdef pillow numpy matplotlib jupyterlab mbuild fresnel pyside2 freud openbabel gsd foyer hoomd;
conda activate grits
```

My install
```
conda create -yn grits -c conda-forge -c mosdef -c omnia pillow numpy matplotlib black isort jupyterlab mbuild fresnel pyside2 freud py3dmol openbabel gsd foyer hoomd nodejs;
conda activate grits;
jupyter labextension install @ryantam626/jupyterlab_code_formatter;
pip install jupyterlab_code_formatter;
jupyter serverextension enable --py jupyterlab_code_formatter
```
