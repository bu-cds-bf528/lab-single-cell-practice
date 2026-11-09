# Decision Record: Seurat practice (ifnb)

| # | Choice | Your value | Where it came from | One-line reason |
| --- | --- | --- | --- | --- |
| 1 | Assay and design (cells or nuclei, platform, samples, conditions, batches) | Whole cells, 10x Genomics; human PBMCs, control vs. IFN-β stimulated; donors not recorded in the metadata | The authors | |
| 2 | Pre-processing (alignment tool, reference genome, intron counting, cell calling) | Not stated | Not stated | The object was provided already processed |
| 3 | QC metrics computed | | | |
| 4 | QC cutoffs (genes, UMIs, % mito, any others) | | | |
| 5 | Cells remaining after QC | | | |
| 6 | Normalization method | | | |
| 7 | Number of variable genes | | | |
| 8 | Number of PCs | | | |
| 9 | Clustering resolution, and number of clusters | | | |
| 10 | Integration (what was treated as a batch, and the method, or none) | | | |
| 11 | Annotation (how labels were assigned: markers, reference, or provided) | Cell-type labels provided with the data (`seurat_annotations`) | The authors | |
| 12 | Marker gene analysis test | | | |