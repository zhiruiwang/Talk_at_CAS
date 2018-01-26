# Diving into Visualization and Communication in Data Science
Invited talk at Chinese Academy of Sciences

## Abstract
Data visualization is a way to communicate information clearly and efficiently via statistical graphics, plots and information graphics. Effective visualization helps users analyze and reason about data and evidence. It makes complex data more accessible, understandable and usable. In the talk, I will emphasize the importance of data visualization and communication in the workflow of data science, introduce a general scheme for data visualization: grammar of graphics, demonstrate exhaustive usage of ggplot2, showcase some commonly used interactive plot library in R, and present a real example of how to generate publication level report using rmarkdown. If time permits, I will also share some professional experience of mine at BCG.

## Biograhpy
[My resume](https://github.com/zhiruiwang/Talk_at_CAS/blob/master/Resume_Zhirui_Wang.pdf)

## Packages Used
`install.packages(c('tidyverse','repr','ggthemes','plotly','dygraphs','xts','visNetwork','DT','leaflet'))`  
It may take few minutes for these packages to download and compile. Please install them before the talk starts.

## Slides
The jupyter notebook `Invited Talk at CAS.ipynb` is the presentation slides.  
Opening it on GitHub shows all the code and ggplot graphs in a flat notebook view. If you want to open it in a slide view, you can just go to this [link](https://nbviewer.jupyter.org/format/slides/github/zhiruiwang/Talk_at_CAS/blob/master/Invited%20Talk%20at%20CAS.ipynb#/). The way to generate the link it is to go to [nbviewer](https://nbviewer.jupyter.org/) and copy the URL of the notebook into the blank, hit `Go！` and then click `View as Slides` bottom (in a shape of wrapped present) on the upper-right corner.  
If you want to run the notebook, you have to install Python and Jupyter (recommend install [Anaconda](https://www.anaconda.com/download/) as your Python environment), and then follow the instruction of [IRkernel](https://github.com/IRkernel/IRkernel). Or you can click the `View as Code` bottom (in a shape of `</>`) in the [previous link](https://nbviewer.jupyter.org/format/slides/github/zhiruiwang/Talk_at_CAS/blob/master/Invited%20Talk%20at%20CAS.ipynb#/). That will render a webpage with all the R code from the notebook, and then you can copy and paste it into your Rstudio and run each line of them.
