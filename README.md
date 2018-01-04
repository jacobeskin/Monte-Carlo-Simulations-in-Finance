# Monte Carlo Simulations in Finance

This repo contains some Jupyter Notebook projects on the application of Monte Carlo methods in different subjects in finance. Since Github does not properly support LaTex in .md files, and not even in displaying .ipynb files, in addition to including the notebooks, links will be provided to NBViewer for proper viewing. Unfinished projects will have a lable above the link, but will still be readable (unfortunately sometimes the website won't work properly).

# A study of Monte Carlo simulations in options pricing
This project explores the different ways Monte Carlo simulation can be used in pricing options. The emphasis is on looking at different ways of improving the estimates and computational efficiency. Most of the calculations are done with Python, but in the end with Asian options where computational speed is needed, the methods that do the heavy lifting will be written in Fortran usin OpenMP for multithreding and wrapping the subroutines into Python modules. 

https://nbviewer.jupyter.org/github/jacobeskin/Monte-Carlo-Simulations-in-Finance/blob/master/A%20study%20of%20MC%20in%20option%20pricing/Options.ipynb
