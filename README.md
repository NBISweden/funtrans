# Fungal metatranscriptomics workflow

A snakemake workflow for analysis of fungal metatranscriptomics data

## Installation
### Linux
Simply clone the repository from GitHub:
```
git clone git@github.com:NBISweden/funtrans.git
```

Then install and activate the conda environment:
```
conda env create -f environment.yml
conda activate funtrans
```

### OSX
Some workflow dependencies are not available on OSX. It is recommended to run
the workflow using Docker:

```
docker pull nbisweden/funtrans
```