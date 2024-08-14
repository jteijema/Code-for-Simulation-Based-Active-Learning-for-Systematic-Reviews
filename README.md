# Code for Simulation-Based Active Learning for Systematic Reviews: A Systematic Review of the Literature
[![DOI](https://zenodo.org/badge/DOI/10.17605/OSF.IO/T9HGM.svg)](https://doi.org/10.17605/OSF.IO/T9HGM)

 Code visualization notebooks for "Simulation-Based Active Learning for Systematic Reviews: A Systematic Review of the Literature"
 
This repository contains code used for the visualization of data for an Active
learning research paper. Visualizations are done using Python and MatPlotLib.

## Abstract
Background: Active learning (or: TAR - Technology Assisted Review, CAL -
Continuous Active Learning) has emerged as a promising approach to improve the
efficiency and effectiveness of the screening phase in systematic reviews. The
exploration of active learning solutions in systematic reviews has been
extensive, encompassing both theoretical research and simulation studies.
However, the field of research is currently fragmented, resulting in an
environment where the benefits of active learning have not been fully realized.
To help conventionalize active learning as the solution for systematic review
automation and help inform researchers on the status of active learning review
research, this study collects and reports on literature related to active
learning reviews. The aim is to answer whether active learning is to be
recommended for use in systematic review acceleration. Furthermore, the study is
intended to benefit future research on active learning by identifying which
areas have been well-studied and which require further investigation.


Method: We conducted a systematic review to investigate the use of active
learning in systematic reviews. We searched multiple databases for literature on
the topic published after 2005 and used the open-source software ASReview with
an active learning algorithm to screen the abstracts for relevance. The
resulting datasets were screened for relevant literature. From these documents
information is extracted. We collect information on study set-up and design, on
dataset availability and usage, and how active learning is used.


Results: Out of 1548 articles, 48 were labeled as relevant to the study. These
articles focus on the use of active learning to improve the efficiency of the
screening phase in systematic reviews. Many variables were extracted, and are
presented in tables.


Discussion: Our systematic review highlights the potential of active learning as
a means to accelerate the screening phase in systematic reviews, with every
single analyzed paper recommending its use. The diverse array of studies and
methodologies supports the generalizability of our findings across papers,
datasets, and models. Despite the identified limitations, the consistent
recommendation for active learning showcases its promise in improving systematic
review automation. To further advance the field, future research should focus on
standardizing metrics, promoting open data practices, and exploring a wider
variety of models, ultimately benefiting both researchers and practitioners in
the systematic review domain.

## Repository structure
This repository contains the following:
```
📁 Code-for-Simulation-Based-Active-Learning-for-Systematic-Reviews/
├── 📖 README.md
├── LICENSE
├── .gitattributes
├── .gitignore
└── 📁 Code/
    ├── 📁 datasets/
    │   ├── 📊 Density Plot of Log(Number of Records).png
    │   ├── 📊 Distribution of Fields.png
    │   ├── 📊 Distribution of Log(Number of Records).png
    │   ├── 📊 Distribution of Publication Years.png
    │   ├── 📊 Number of Records vs. Number of Inclusions.png
    │   ├── 📊 Number of Records vs. Number of Inclusions (without outliers).png
    │   ├── 📊 Number of Records vs. Number of Inclusions with regression (without outliers).png
    │   └── 📄 datasets.ipynb
    ├── 📁 models/
    │   ├── 📊 Hyperparameter Optimization.png
    │   ├── 📊 Machine Learning Models Used.png
    │   └── 📄 models.ipynb
    ├── 📁 papers/
    │   ├── 📊 Actual Availability of Reported Resources.png
    │   ├── 📊 Distribution of Datasets Used for Simulations.png
    │   ├── 📊 Distribution of Datasets Used for Simulations barplot.png
    │   ├── 📊 Distribution of Publication Years.png
    │   ├── 📊 Frequency of Metrics Used in Studies.png
    │   ├── 📊 OS_Reported.png
    │   ├── 📊 Prelabeled Datasets.png
    │   ├── 📊 Prelabeled Datasets 2.png
    │   ├── 📊 Types of Data Used to Train the Model.png
    │   └── 📄 papers.ipynb
    └── 📁 recall_plot/
        ├── 📊 recall_plot.png
        ├── 📊 recall_plot.svg
        ├── 📄 recall_plot.ipynb
        ├── 📊 recall_plot_update.png
        └── 📊 recall_plot_update.svg

5 directories , 30 files
📖README 📜Data 📄Code 📊Figures 📦Serial Data 📁Folder
```

> This tree structure was generated using [Scitree](https://github.com/J535D165/scitree).


## Authors
Jelle Teijema 1*, Ayoub Bagheri 1, and Rens Van De Schoot 1

1 Department of Methodology and Statistics, Faculty of Social and Behavioral
Sciences, Utrecht University, The Netherlands

*Corresponding author: J. J. Teijema: Department of Methodology and Statistics,
Utrecht University, P.O. Box 80.140, 3508TC, Utrecht, The Netherlands; Tel.: +31
302534468; E-mail address: j.j.teijema@uu.nl.

## Examples:
![Image](/Code/Papers/Distribution%20of%20Datasets%20Used%20for%20Simulations.png)
![Image](/Code/Papers/Actual%20Availability%20of%20Reported%20Resources.png)
![Image](Code/Datasets/Density%20Plot%20of%20Log(Number%20of%20Records).png)

## License

This repository is openly published on GitHub, https://github.com/JTeijema/Code-for-Simulation-Based-Active-Learning-for-Systematic-Reviews/ under MIT license. Therefore it is 'Open Access' and thus available for anyone. This repository will remain online for at least 10 years.
