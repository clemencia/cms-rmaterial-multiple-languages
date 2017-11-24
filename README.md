# CMS Open Data: Plotting an Invariant Mass Histogram in R

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/cms-opendata-education/cms-rmaterial-multiple-languages/master)

In this repository, you will find introductions to both the R programming language and to a simple analysis with R using CMS Open Data from the [CERN Open Data portal](http://opendata.cern.ch).
The tutorial is available in interactive form as a Jupyter notebook using the [IR Kernel](https:/irkernel.github.io) (in English only, for the moment) and as a PDF (in English and Spanish).
You can run the Jupyter notebook in your browser without installing any software on your machine, through the power of [Binder](https://mybinder.org).
However, installation instructions are available below if you wish to play with the notebook files offline.
Note that the data will require at least a temporary connection to the CERN Open Data portal.

## Tutorial files

|Language|Jupyter notebook|For print|
|:--|:--|:--|
|English (EN)|[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/cms-opendata-education/cms-rmaterial-multiple-languages/master?filepath=EN-R-tutorial.ipynb)|[View PDF](https://github.com/cms-opendata-education/cms-rmaterial-multiple-languages/blob/master/EN-R-tutorial.pdf)|
|Spanish (ES)|Coming soon!|[View PDF](https://github.com/cms-opendata-education/cms-rmaterial-multiple-languages/blob/master/ES-R-Tutorial.pdf)

## Instructions for offline use

1. [Install Jupyter](https://jupyter.org/install.html).
1. [Install R](https://www.r-project.org/).
1. [Make the IR kernel available to Jupyter](https://irkernel.github.io/installation/).
1. In the terminal, clone this repo onto your machine, and change directories so you're inside the repo.
1. Still in the terminal, type `$ jupyter notebook`. Your default browser will open with the Jupyter interface.
1. Click on the file ending with `.ipynb` to begin the interactive tutorial.

## Credits

- Original text and code: [Edith Villegas Garcia](https://github.com/edithvillegas)
- Additions and suggestions (the `tidyverse` example): [Andrew John Lowe](https://github.com/andrewjohnlowe)
- Editing and conversion to Jupyter notebook by [Achintya Rao](https://github.com/RaoOfPhysics)

## Technical information

You can use [Binder](https://mybinder.org) to interact with any such notebook via a browser without installing Jupyter or R, by hosting your notebooks on GitHub.
To do so, make sure that your GitHub repository contains the Dockerfile shown here: [https://github.com/binder-examples/dockerfile-r](https://github.com/binder-examples/dockerfile-r).
Install any additional packages you want to interact with (e.g. `tidyverse`) by including them in the Dockerfile.

## Licence

Coming soon!
