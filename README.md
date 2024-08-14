# Code for Simulation-Based Active Learning for Systematic Reviews: A Scoping Review of the Literature
[![DOI](https://zenodo.org/badge/DOI/10.17605/OSF.IO/T9HGM.svg)](https://doi.org/10.17605/OSF.IO/T9HGM)

 Code visualization notebooks for "Simulation-Based Active Learning for Systematic Reviews: A Scoping Review of the Literature"
 
This repository contains code used for the visualization of data for an Active
learning research paper. Visualizations are done using Python and MatPlotLib.

This repository contains the information for both the original search and the search updates.

## Abstract
This study investigated the utility of active learning in accelerating the systematic review process. We reviewed literature from 2006 onwards, using the open-source software ASReview, and selected 48 relevant articles out of 1548, while incorporating 208 out of 305 collected datasets. Our analysis overwhelmingly recommends active learning for improving the efficiency of the screening phase in systematic reviews, despite some limitations. Future research should focus on standardizing metrics, promoting open data, and diversifying models to advance active learning in systematic reviews.

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
Jelle Jasper Teijema 1*, Guilherme Ribeiro 1,2, Sofie Seuren 1, Daniel Anadria 1, Ayoub Bagheri 1, and Rens van de Schoot 1

1 Department of Methodology and Statistics, Faculty of Social and Behavioral
Sciences, Utrecht University, The Netherlands

2 Department of Informatics, Faculty of Sciences, University of Lisbon, Portugal

*Corresponding author: J. J. Teijema: Department of Methodology and Statistics,
Utrecht University, P.O. Box 80.140, 3508TC, Utrecht, The Netherlands; Tel.: +31
302534468; E-mail address: j.j.teijema@uu.nl.

## Examples:
![Image](/Code/Papers/Distribution%20of%20Datasets%20Used%20for%20Simulations.png)
![Image](/Code/Papers/Actual%20Availability%20of%20Reported%20Resources.png)
![Image](Code/Datasets/Density%20Plot%20of%20Log(Number%20of%20Records).png)

## License

This repository is openly published on GitHub, https://github.com/JTeijema/Code-for-Simulation-Based-Active-Learning-for-Systematic-Reviews/ under MIT license. Therefore it is 'Open Access' and thus available for anyone. This repository will remain online for at least 10 years.
