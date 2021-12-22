# Clinical drug response prediction using Lasso
## [Report](https://github.com/YazdanZ/ClinicalDrugResponse_CCL_LASSO/blob/master/report/report.pdf)

We performed a variety of studies on the transcriptomic dataset obtained from
GDSC. We first performed dimensionality reduction using PCA, t-SNE, and UMAP and
compared them together. We the used k-means and agglomerative clustering with different
configurations and studied the concordance between formed clusters using each method.
Finally, we used Lasso regression for drug response prediction of cancer cell lines. The latter
was a challenging task due to the high dimensionality of the data and a lack of samples. This
method has many limitations as it can not directly be applied to combination treatment.
Furthermore, as we used preclinical samples in our predictions, the clinical drug response of
real patients can be different. There are many areas of improvement and future directions to
this study. For example, it is possible to incorporate information about tissue type of CCLs
to improve predictions either by using a labelled dataset or by clustering CCLs.
