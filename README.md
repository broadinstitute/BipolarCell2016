# BipolarCell2016

Welcome to the GitHub page associated with Shekhar, Lapan, Whitney et al., "Comprehensive classification of retinal bipolar neurons by single-cell transcriptiomics", *Cell*, 2016. Bipolar cells are key interneurons in the retina that are involved in processing visual information from photoreceptors. In this work, we generated and validated a comprehensive molecular taxonomy of bipolar neurons using droplet based single-cell transcriptomics or **Drop-seq** (see Macosko et al., *Cell*, 2015). The resulting 15 molecular types found by clustering were validated 1:1 against the morphology of 13 known types and 2 novel molecular types discovered in this work. 

This GitHub page maintains documentation and code to enable interested readers to reproduce the main results reported in the paper. Most of the computational results were obtained using previously published techniques/algorithms either implemented by the author or through existing software packages. While the paper entailed analysis of multiple datasets (Drop-seq and Smart-seq2 data from multiple mouse lines), we restrict our attention here to the Bipolar cell Drop-seq data (or *Vsx2*-GFP Drop-seq data), outlining the key results of the paper. 

The key steps, implemented in the R statistical language, are summarized in the tutorial file `BCanalysis.pdf`. Users are recommended to install the RStudio IDE to follow the tutorial.  The PDF describes R packages that users will have to install to get started. Users will require `class.R`, which contains essential code, and an Rdata file `bipolar_data_Cell2016.Rdata` to carry out the steps. The Rdata file can be downloaded at the following link,

URL ....

Questions and comments on this code, or on additional computational aspects of the paper can be e-mailed to karthik@broadinstitute.org.
