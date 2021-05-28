---
permalink: /r/
title: "R software"
toc: true
toc_label: "Index"
toc_icon: "cog"
---

## Machine Learning using R
One will need R and may need RStudio to work on data science project using R. The installations and repositories for working with R software are as below:

### Installation - R with R Studio
One should have latest version of R and R Studio installed on their system. First Install R and then R Studio. Latest version of the software can be found at: 

  > *  Download and install the operating sysytem specific version of R software from this [link](https://cran.r-project.org/).
  > *  RStudio can be downloaded [here](https://www.rstudio.com/products/rstudio/download). Once the download completes, install RStudio as well.

Post the successful installation, you can launch RStudio to work in data analysis projects. RStudio interface looks like:
 
![image](/assets/images/RStudio.png)

Note that, R software installation will be needed before one can work on data analysis using R Studio.

### Installation - R with Anaconda 
RStudio may not be needed if using jupyter notebook. `Anaconda with jupyter notebook can also be used to work with R software.` 

> * Install operating system specific version of [Anaconda](https://www.anaconda.com/products/individual){:target="_blank"}.
> * Install operating system specific version of [R software](https://cran.r-project.org/){:target="_blank"}.
> * open R console in windows (or open R console through Terminal in Mac). Enter the below command:

    ##install the IR kernel
    > install.packages('IRkernel’) 
    ## Invoke the package
    > library(IRkernel)
    ## Make Jupyter Notebook point to the R kernel
    > IRkernel::installspec() 
    
 The above commands were tested in MacOs Big Sur 11.0.1:
 
![image](/assets/images/JupyterR1.png)
![image](/assets/images/JupyterR2.png)

Now you can open Jupyter Notebook and you can write your R script by using R kernel. One is expected to resolve any installation issues of the software. You may google about the installation issues and resolution may follow.

### Repository
* R software for statistical analysis is yet another popular langauge for working on data science project. Here is the  [link](https://github.com/rahul235/ML_using_R/archive/refs/tags/v1.0.zip){:target="_blank"} to download the repository for Machine learning using R.
* Download the repository for data visualization and programming with R from [this link](https://github.com/rahul235/R_Programming/archive/refs/tags/v1.0.zip){:target="_blank"}.
