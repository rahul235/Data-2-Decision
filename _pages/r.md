---
permalink: /r/
title: "R software"
toc: true
toc_label: "Index"
toc_icon: "cog"
---

## Machine Learning using R
One will need R and may need RStudio to work on data science project using R. The installations and repositories for working with R software are as below:

### Installation
Participants should have latest version of R and R Studio installed on their system. First Install R and then R Studio. Latest version of the software can be found at: 
  > *  R software can be downloaded from this [link](https://cran.r-project.org/). Download the version specific to your operating system.
  > *  RStudio can be downloaded [here](https://www.rstudio.com/products/rstudio/download)
  
RStudio may not be needed if using jupyter notebook. `Anaconda with jupyter notebook can also be used to work with R software.` 

> * Install operating system specific version of [R software](https://cran.r-project.org/)
> * open R console (or open R through Terminal in Mac). Enter the below command:

    ##install the IR kernel
    > install.packages('IRkernel’) 
    ## Invoke the package
    > library(IRkernel)
    ## Make Jupyter Notebook point to the R kernel
    > IRkernel::installspec() 
    
 The above commands were tested in MacOs Big Sur 11.0.1:
 
![image](/assets/images/JupyterR1.png)
![image](/assets/images/JupyterR2.png)

Now you can open Jupyter Notebook and you can write your R script by using R kernel. Participants are expected to resolve any installation issues of the software prior to the commencement of the session.

### Repository
* R software for statistical analysis is yet another popular langauge for working on data science project. Here is the  [repository link](https://github.com/rahul235/ML_using_R/) for Machine learning using R.
* More about data visualization and programming with R can be found at [this link](https://github.com/rahul235/R_Programming/).
