# Sarcinelli_ITGAV
scRNAseq reanalysis from Ke2024

```
.
├── env.yml
└── notebooks
    ├── nb01_integrins.ipynb
    └── nb02_matrisome.ipynb
```


## preprocessing
- preprocessing of this dataset can be found here: [MIL-TARGID/Italia_TLR4](https://github.com/MIL-TARGID/Italia_TLR4)

## nb01_integrins.ipynb

- UMAPs colored by mesenchymal cell type labels
    - all mesenchymal
    - divided by condition `("CRC_Proximal", "CD_Proximal", "CD_Inflamed", "CD_Stenotic")`
- UMAP with `ITGAV` gene expression in mesenchymal cells, divided by condition
- violin plot with `ITGAV` gene expression in mesenchymal cell types (boxplot with median and 25-75 percentile range)

## nb02_matrisome.ipynb

- calculation of [matrisome](https://www.gsea-msigdb.org/gsea/msigdb/human/geneset/NABA_CORE_MATRISOME.html) score on the full Ke2024 dataset
- UMAP with `matrisome score` in mesenchymal cells, divided by condition