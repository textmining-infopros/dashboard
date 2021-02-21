# Case Study : Making a Dashboard using R

This repository contains a reproducible research compendium for the case study used in the book:
Manika Lamba and Margam Madhusudhan (2021) Text Mining: An Uncharted Territory for Librarians, Springer.

# How to cite
Please cite this compendium as: xxxxxxx

# Contents
The compendium contains the data, code, and notebook associated with the case study. This case study is further divided into 7A, and 7B. 7A case study used RapidMiner, and 7B case study used R programming language to perform sentiment analysis. It is organized as follows:

  - The `data.csv` file contains the data. The same dataset was used for both the case studies.
    - The `negative_book_reviews.csv` file contains the supplementary data associated with 7B case study.
    - The `neutral_book_reviews.csv` file contains the supplementary data associated with 7B case study.
    - The `positive_book_reviews.csv` file contains the supplementary data associated with 7B case study.
  - The `sentiment_analysis.R` file contatins the R code for 7B case study.
  - The `Case_Study_7B.ipynb` file contatins the Jupyter notebook for 7B case study.

# How to download or install
There are several ways to use the compendium’s contents and reproduce
the analysis:

  - **Download the compendium as a zip archive** from this [GitHub
    repository](https://github.com/textmining-utl/chapter9/archive/main.zip).
    
      - After unpacking the downloaded zip archive, you can explore the
        files on your computer.

  - **Reproduce the analysis in the cloud** without having to install
    any software. The same Docker container replicating the
    computational environment used by the authors can be run using
    BinderHub on [mybinder.org](https://mybinder.org/):
    
      - Click
        **Jupyter+R**: [![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/textmining-utl/chapter9/main?filepath=Case_Study_9.ipynb) to launch an                           interactive Jupyter notebook session in your web browser.
      - Click
        **RStudio**: [![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/textmining-utl/chapter9/main?urlpath=rstudio)
        to launch an interactive RStudio session in your web browser.

   - **Limitations of Binder**
        1. The server has limited memory so you cannot load large datasets or run big computations.
        2. Binder is meant for interactive and ephemeral interactive coding so an instance will die after 10 minutes of inactivity.
        3. An instance cannot be kept alive for more than 12 hours.

### Licenses

**Text and figures :** ©2021 Lamba and Madhusdhan - all rights reserved, unless stated otherwise.
**Code :** [CC-BY-4.0](http://creativecommons.org/licenses/by/4.0/)
**Data :** [CC-BY-4.0](http://creativecommons.org/licenses/by/4.0/)
