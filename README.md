# Introduction to Statistical Analysis of Climate Time Series in HPC systems 2026
## By Danny Vargas PhD.

## Introduction

### Objectives
1. To learn about more efficient methods to carry out research
2. To improve the statistical analysis of noisy climate data
3. To speed up spectral and wavelet analyses using HPC systems


### GitHub (first time)
==========================

username: revistalagranja

password: DonBosco2026*

==========================

echo "# testing" >> README.md

git init (e.g., git init bin)

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin git@github.com:revistalagranja/WaveletsHPC.git (only the first time, after that skip to next line)

git push -u origin main


*If the github is ahead (e.g., there were changes made into the README.m or .gitignore) then the main branch is ahead of the others. Use the following:

git fetch

git pull



# In case of subdirectories or .git files

git rm --cached -r docs/Article_pandoc docs/pandoc_article_template

git add docs/Article_pandoc docs/pandoc_article_template

git commit -m "Track pandoc folders as regular directories"

git push


# root (sudo privileges)
enroot start -r -w enrootubuntu

enroot start -w --mount "$PWD:/workspace" enrootubuntu



### References

-Crockett R. A Primer on Fourier Analysis for the Geosciences. Cambridge University Press; 2019.
https://www.cambridge.org/core/books/primer-on-fourier-analysis-for-the-geosciences/F7D83A033DF1B413E99C6D057D38DA4C

-Emile-geay, Julien (2017). Data Analysis in the Earth & Environmental Sciences. figshare. Book.
https://doi.org/10.6084/m9.figshare.1014336.v11

-Percival, Donald B., and Andrew T. Walden. Wavelet Methods for Time Series Analysis. of Cambridge Series in Statistical and Probabilistic Mathematics. Cambridge: Cambridge University Press, 2000.
https://www.cambridge.org/core/books/wavelet-methods-for-time-series-analysis/A2018601E6907DE4953EEF7A5D0359E5

-Mudelsee M. Climate Time Series Analysis: Classical Statistical and Bootstrap Methods. Second edition.
https://link.springer.com/book/10.1007/978-3-319-04450-7
 
-Mudelsee M. Statistical Analysis of Climate Extremes
https://www.cambridge.org/core/books/statistical-analysis-of-climate-extremes/8950D5D7306AE2BFC4EFB882CF5B33B6

-Robert H. Shumway, David S. Stoffer. Time Series Analysis and Its Applications
https://link.springer.com/book/10.1007/978-3-031-70584-7#bibliographic-information

-Trauth M. H. Python Recipes for Earth Sciences
https://doi.org/10.1007/978-3-031-07719-7

-Vaughan, Simon. University of Leicester. Scientific Inference: Learning from Data
https://www.cambridge.org/core/books/scientific-inference/D93CAC2C8E858A9CFE7B7A3B6F2999F4

-Donald B. Percival, Andrew T. Walden. Wavelet Methods for Time Series Analysis
https://www.amazon.com/Analysis-Cambridge-Statistical-Probabilistic-Mathematics/dp/0521685087

-Donald B. Percival, Andrew T. Walden. Spectral Analysis for Univariate Time Series
https://www.cambridge.org/core/books/spectral-analysis-for-univariate-time-series/308BC6C9B881E490ED3D4C9F89ED8058





