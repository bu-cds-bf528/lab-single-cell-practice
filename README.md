# Lab 0: Seurat Practice (ifnb)

This lab is practice with Seurat itself.  Every later lab assumes you can do the
things below.

**Dataset:** `ifnb` from SeuratData. Human PBMCs, half untreated and half
stimulated with interferon-beta, with cell-type labels provided.

**Time:** about 2 hours

## Objectives

By the end of this lab, you should be able to:

1. **Research the setting before the analysis:** state what cell types and
   biological effects you expect, with sources, and use those expectations to
   judge your results.
2. **Navigate a Seurat object:** find its cells, genes, assays, layers,
   metadata, reductions, and identities.
3. **Work with metadata:** read columns, add new ones, and tabulate them.
4. **Subset cells and confirm the result:** subset by metadata values, combine
   conditions, and check that each subset contains the cells you expected.
5. **Split and merge objects:** combine samples, and understand how layers
   behave when you do.
6. **Run the standard workflow:** normalization, variable genes, PCA,
   neighbors, clustering, and UMAP.
7. **Choose a clustering resolution with evidence:** use clustree, your
   expectations, and the provided labels to justify the resolution you pick.
8. **Find and interpret marker genes:** identify markers for each cluster and
   relate them to cell types.
9. **Record your decisions:** fill in a decision record, as you will in every
   lab.

## Files

| File | What it is |
| --- | --- |
| `seurat_practice_ifnb.Rmd` | The lab. Work through it in order. |
| `checkpoint_counts.md` | Values you compute in Part 2. Fill in the table. |
| `decision_record.md` | Your choices and thresholds. Fill it in as you go. |
