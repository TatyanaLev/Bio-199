# Bio-199: Fall 2022
## Bio-199 & Lab Rules

* Independent research project, achievable in 1 quarter (flexible)
* Enrollment packet (A?)
* Weekly progress check ins (Tell me your availability for 1 hour zoom or in-person)
* Final write-up at the end of the quarter
* 1 lab meeting presentation (20 minutes)
* 1 credit hour = 2 lab hours
* First time enrollment: 3 credit hour maximum (6 lab hours per week)
* Second quarter and beyond: can take more than 3 credit hours

## Lawson Laboratory Goals
* Uncover cellular and molecular mechanisms controlling breast cancer metastasis
    * Metastasis = Lethal spread of cancer cells from primary site (breast) to other organs in the body. 
    * Use mouse models and single cell genomic technology to study how intratumor heterogeneity contributes to metastatic spread
        * How heterogeneous are primary tumors?
            * How many distinct cell groups, as defined by gene expression, exist in the primary tumor?
            * How are these cell groups related or how do they arise and evolve?
        * Which genes and/or regulatory regions are involved in metastasis?

## Projects Overview:
* Use the popular Python-based single cell genomics package Scanpy
* Follow tutorials to analyze a mouse tumor dataset

### <ins>Project 1: Clustering and Visualization<ins>
#### _Data: single-nucleus gene expression matrix from mouse mammary tumor_ 
* _RNA gene expression (GEX) counts matrix: genes by cells_
#### _Goal: quality control, cluster to identify cell types, compare to my results from Seurat (R equivalent of Scanpy)_

### <ins>Project 2: PAGA Trajectory Inference<ins>
#### _Data: subset of single-nucleus gene expression matrix in project 1_ 
* _RNA gene expression (GEX) counts matrix for selected cells only: genes by cells_
#### _Goal: pseudo-order the cells using PAGA trajectory inference. Analyze and compare 2 such datasets_  


## Start of Quarter Goals
1. Install JupyterLab and familiarize yourself with how jupyter notebooks work
    * Install: https://jupyter.org/install 
        * Code blocks vs comments vs markdown
            * Cheatsheet: http://datacamp-community-prod.s3.amazonaws.com/21fdc814-3f08-4aa9-90fa-247eedefd655 
2. Make GitHub account & Bio199 repository. 
    * You will share your notebooks with me through that GitHub repository:
        * https://reproducible-science-curriculum.github.io/sharing-RR-Jupyter/01-sharing-github/ 
3. Start the Scanpy Tutorials (clustering & visualization, trajectory inference)
    * Install Scanpy and other packages that the tutorial requires
        * https://scanpy.readthedocs.io/en/stable/installation.html 
    * Download the data that the tutorial uses (Project1 only; Project 2 data is built-in) 
    * Go once through the tutorial, reproduce tutorial results
        * Troubleshoot if needed 
            * Github “Issues”
            * Stack overflow

## Once the tutorial works, I will give you real data
