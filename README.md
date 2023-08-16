# McFarlin et al. (2023) supplemental

This repository holds data and supplementary source code needed to reproduce the calculations and plots of McFarlin et al. "Aquatic plant wax hydrogen and carbon isotopes in Greenland lakes record shifts in methane cycling during past Holocene warming."

Data that is original to this study can be found within the data folder and is also archived with the NOAA paleoclimate database. Published data used in the analyses here and contained within the data folder comes from the following work:

Y. Axford, E. C. Osterberg, A. de Vernal, Past warmth and its impacts in Greenland during the Holocene Thermal Maximum. Annu Rev Earth Planet Sci. 49, 279–307 (2021).*
*and references therein (Axford et al. 2013, 2017, 2019)

G. J. Bowen, The Online Isotopes in Precipitation Calculator, version 3.1 (2020), (available at http://wateriso.utah.edu/waterisotopes/pages/data_access/oipc.html).

M. C. Corcoran, E. K. Thomas, C. Morrill, Using a Paired Chironomid δ18O and Aquatic Leaf Wax δ2H Approach to Reconstruct Seasonality on Western Greenland During the Holocene. Paleoceanogr Paleoclimatol. 36, 1–18 (2021).

IAEA/WMO, Global Network of Isotopes in Precipitation. The GNIP Database. (2020).

S. Kusch, O. Bennike, B. Wagner, M. Lenz, I. Steffen, J. Rethemeyer, Holocene environmental history in high‐Arctic North Greenland revealed by a combined biomarker and macrofossil approach. Boreas. 48, 273–286 (2019).

G. E. Lasher, Y. Axford, J. M. McFarlin, M. A. Kelly, E. C. Osterberg, M. B. Berkelhammer, Holocene temperatures and isotopes of precipitation in Northwest Greenland recorded in lacustrine organic materials. Quat Sci Rev. 170, 45–55 (2017).

B. S. Lecavalier, D. A. Fisher, G. A. Milne, B. M. Vinther, L. Tarasov, P. Huybrechts, D. Lacelle, B. Main, J. Zheng, J. Bourgeois, A. S. Dyke, High Arctic Holocene temperature record from the Agassiz ice cap and Greenland ice sheet evolution. Proc Natl Acad Sci U S A. 114, 5952–5957 (2017).

J. M. McFarlin, Y. Axford, M. R. Osburn, M. A. Kelly, E. C. Osterberg, L. B. Farnsworth, Pronounced summer warming in northwest Greenland during the Holocene and Last Interglacial. Proceedings of the National Academy of Sciences. 115, 6357–6362 (2018).

J. M. McFarlin, Y. Axford, A. L. Masterson, M. R. Osburn, Calibration of modern sedimentary δ2H plant wax-water relationships in Greenland lakes. Quat Sci Rev. 225, 105978 (2019).

E. K. Thomas, J. P. Briner, J. J. Ryan‐Henry, Y. Huang, A major increase in winter snowfall during the middle Holocene on western Greenland caused by reduced sea ice in Baffin Bay and the Labrador Sea. Geophys Res Lett. 43, 5302–5308 (2016).

E. K. Thomas, K. V. Hollister, A. A. Cluett, M. C. Corcoran, Reconstructing Arctic Precipitation Seasonality Using Aquatic Leaf Wax δ 2 H in Lakes With Contrasting Residence Times. Paleoceanogr Paleoclimatol. 35 (2020), doi:10.1029/2020PA003886.

M. van Hardenbroek, A. Chakraborty, K. L. Davies, P. Harding, O. Heiri, J. Schilder, C. N. Trueman, M. J. Wooller, The stable isotope composition of organic and inorganic fossils in lake sediment records : Current understanding , challenges , and future directions. Quat Sci Rev. 196, 154–176 (2018).

B. M. Vinther, S. L. Buchardt, H. B. Clausen, D. Dahl-Jensen, S. J. Johnsen, D. a Fisher, R. M. Koerner, D. Raynaud, V. Lipenkov, K. K. Andersen, T. Blunier, S. O. Rasmussen, J. P. Steffensen, a M. Svensson, Holocene thinning of the Greenland ice sheet. Nature. 461, 385–388 (2009).

# What can I do with this code?
We hope that this code, or any part of it, might prove useful to other members of the scientific community interested in the subject matter. This repository is released under a [Creative Commons BY (CC-BY)](https://creativecommons.org/licenses/by/4.0/) license, which means all code can be shared and adapted for any purpose as long as appropriate credit is given. See [Attribution section](https://creativecommons.org/licenses/by/4.0/) for details. Code is provided in [R Markdown](http://rmarkdown.rstudio.com/).

# What is R Markdown?
[R Markdown](http://rmarkdown.rstudio.com/) is a so-called "literate programming" format that enables easy creation of dynamic documents with the [R](http://www.r-project.org/) language. HTML and PDF reports can be generated from R Markdown files using [knitr](http://yihui.name/knitr/) and [pandoc](http://johnmacfarlane.net/pandoc/), which can be installed automatically with [RStudio](http://www.rstudio.com/), and are fully integrated into this cross-platform IDE. All software used for these reports (R, RStudio, etc.) is freely available and completely open-source.

# How can I run this code?
The quickest and easiest way is to use RStudio.
1. Download and install [R](http://cran.rstudio.com/) for your operating system
2. Download and install [RStudio](http://www.rstudio.com/products/rstudio/download/) for your operating system
3. Download a zip file of this repository and unpack it in an easy to find directory on your computer
4. Navigate to the directory and double-click the project.Rproj file to start RStudio.
5. Open the .Rmd notebook titled 'Code for McFarlin et al 2023' in the file browser
6. Install the required libraries by running the following command in the Console in RStudio: install.packages(c("ggplot2", "GGally", "cowplot", "ggcorrplot", "stats", "dplyr","plyr","tidyverse","viridis","magick")) or by installing them manually in RStudio's Packages manager.    
7. To generate an HTML report ("knit HTML"), select the Knit icon followed by "Knit to HTML."  The HTML report will be displayed upon successful completion and is saved as a standalone file in the same directory. 
8. To generate a PDF report ("knit PDF"), select the Knit icon followed by "Knit to PDF."  The PDF report will be displayed upon successful completion and is saved as a standalone file in the same directory. 
    
# Troubleshooting Notes
The R Markdown file in this repository makes use of various R modules for data processing, plotting and modelling. All of these should be installed automatically when the first R Markdown file is knitted (if the knitting fails because of a missing package, please install it manually, an error will indicate which package could not be installed).



