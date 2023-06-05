=====================================================
HTAN BigQuery Notebooks
=====================================================
`HTAN <https://humantumoratlas.org>`_ is a National Cancer Institute (NCI)-funded Cancer Moonshot<sup>SM</sup> initiative to
construct 3-dimensional atlases of the dynamic cellular, morphological, and molecular features of human cancers as they
evolve from precancerous lesions to advanced disease
`(Cell, April 2020) <https://www.sciencedirect.com/science/article/pii/S0092867420303469>`_.

In order to access the cloud-based data used in these notebooks, please see:
 `Getting started with the ISB-CGC <https://isb-cancer-genomics-cloud.readthedocs.io/en/latest/sections/HowToGetStartedonISB-CGC.html>`_


Clinical data, sample biospecimen data and assay files in HTAN have a rich set of annotations supplied by HTAN data
contributors.  These annotations are made according to the  `HTAN Data model <https://data.humantumoratlas.org/standards>`_ ,
a set of standards defined by the HTAN consortium. The supplied values of these attributes have been collected into
comprehensive data tables in the cloud, accessed using
`Google BigQuery standard SQL <https://cloud.google.com/bigquery/docs/query-overview>`_.

This folder contains example notebooks that illustrate how to query and process both file metadata and molecular data
that are available in Google BigQuery tables.

Notebooks are available in both the R programming language (R markdown) and in python (Jupyter).
There is a also a folder with templates, if you would like to create and share your own notebooks.

Contents:

**R Notebooks/Explore_HTAN_Clinical_Biospecimen_Assay_Metadata.Rmd** - illustrates how to make use of HTAN Google
BigQuery metadata tables to tabulate and plot available HTAN clinical, biospecimen, and assay metadata in R

**Python Notebooks/Explore_HTAN_Clinical_Biospecimen_Assay_Metadata.Rmd** - illustrates how to make use of HTAN Google
BigQuery metadata tables to tabulate and plot available HTAN clinical, biospecimen, and assay metadata in Python

**Python Notebooks/Investigating_Single_Cell_HTAN_Data.ipynb** - illustrates how to query HTAN single-cell RNA
sequencing data for cell content and gene expression

**Python Notebooks/Building_AnnData_with_Subset_of_Cells_from_BQ.ipynb** - illustrates how to query HTAN single-cell RNA
sequencing data for specific cell types and construct an Scanpy Anndata object from the result

**HTAN_Notebook_Templates** - these templates serve as a guide for notebook construction. 

