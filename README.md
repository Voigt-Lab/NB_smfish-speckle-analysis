# smfish-speckle-analysis

This repository contains the notebooks used for segmentation and quantitative
analysis of smFISH images.

## Software environment

`environment-full-macos.yml` contains a snapshot of the Conda environment used
for the original analysis.

It includes additional packages that may not be required by the notebooks and
has not been tested on other operating systems.

### Create the environment

```bash
conda env create -f environment-full-macos.yml
conda activate speckle_analysis
```


## Repository structure

```text
smfish-nuclear-speckle-analysis/
├── README.md
├── environment-full-macos.yml
└── notebooks/
    └── nuclei_speckle_segmentation.ipynb
```

## Notes

- Raw microscopy data are not included because of their size.
- Input and output directories must be specified in the notebook.
- Biological conditions are determined by the contents of the input folders.
