---
layout: page
title: "Machine Learning using R"
output:
    html_document:
    toc: true
    toc_depth: 2
permalink:https://rahul235.github.io/data2decisions/R
---

## Machine Learning using R
One will need R and may need RStudio to work on data science project using R. The installations and repositories for working with R software are as below:

### Installations
Participants should have latest version of R and R Studio installed on their system. First Install R and then R Studio. Latest version of the software can be found at: 
  > *  R software can be downloaded from this [link](https://cran.r-project.org/). Download the version specific to your operating system.
  > *  RStudio can be downloaded [here](https://www.rstudio.com/products/rstudio/download)
  
RStudio may not be needed if using jupyter notebook. `Anaconda with jupyter notebook can also be used to work with R software.` 

> * Install operating system specific version of [R software](https://cran.r-project.org/)
> * open R console (or open R through Terminal in Mac). Enter the below command:

    > install.packages('IRkernel’) ##install the IR kernel
    > library(IRkernel) ## Invoke the package
    > IRkernel::installspec() ## Make Jupyter Notebook point to the R kernel
    
 The above commands were tested in MacOs Big Sur 11.0.1:
 
![image](JupyterR1.png)
![image](JupyterR2.png)

Now you can open Jupyter Notebook and you can write your R script by using R kernel. Participants are expected to resolve any installation issues of the software prior to the commencement of the session.

### Repositories
* R software for statistical analysis is yet another popular langauge for working on data science project. Here is the  [repository link](https://github.com/rahul235/ML_using_R/) for Machine learning using R.
* More about data visualization and programming with R can be found at [this link](https://github.com/rahul235/R_Programming/).
