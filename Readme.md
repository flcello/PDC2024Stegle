#  Single cell multi-omics integration using muon

In this tutorial you will learn how to use the muon framework for multi-modal analysis of single cell data, covering important data formats for single cell data, normalization strategies, clustering and visualization. You will apply this framework for the analysis of multimodal single cell data such as CITE-seq or scNMT-seq data. During this, they will learn about weightest nearest neighbors analysis and discover more advanced options of the MOFA method, such as integration of data with distinct groups of samples and learn how it can be interfaced with the muon framework. 

*Topics*:  normalization strategies, clustering,  visualization,CITE-seq, scNMT-seq data, muon, weightest nearest neighbors analysis, MOFA+

## Software requirements

Conda environment with jupyter notebook/lab:

```
conda create -n pdcstegle jupyterlab python=3.10
conda activate pdcstegle
```

and the following dependencies:

```
pip install muon==0.1.5 mudatasets mofapy2 mofax leidenalg seaborn==0.12.2 "numpy<2.0" anndata==0.10.2
```
