## Introduction 👋

From the website, “Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informational statistical graphs.”

Seaborn excels at doing Exploratory Data Analysis (EDA) which is an important early step in any data analysis project. Seaborn uses a “dataset-oriented” API that offers a consistent way to create multiple visualizations that show the relationships between many variables. In practice, Seaborn works best when using Pandas dataframes and when the data is in tidy format.

## What’s New?
In my opinion the most interesting new plot is the [relationship](https://seaborn.pydata.org/generated/seaborn.relplot.html#seaborn.relplot) plot or `relplot()` function which allows you to plot with the new `scatterplot()` and `lineplot()` on data-aware grids. Prior to this release, scatter plots were shoe-horned into seaborn by using the base matplotlib function `plt.scatter` and were not particularly powerful. The `lineplot()` is replacing the `tsplot()` function which was not as useful as it could be. These two changes open up a lot of new possibilities for the types of EDA that are very common in Data Science/Analysis projects.

The other useful update is a brand new [introduction](https://seaborn.pydata.org/introduction.html) document which very clearly lays out what Seaborn is and how to use it. In the past, one of the biggest challenges with Seaborn was figuring out how to have the “Seaborn mindset.” This introduction goes a long way towards smoothing the transition.

 ---

 ## Table of contents 📋

| **No.** | **Name** |
| ------- | -------- |
| 01 | **[Seaborn_Loading_Dataset](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/001_Seaborn_Loading_Dataset.ipynb)** |
| 02 | **[Seaborn_Controlling_Aesthetics](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/002_Seaborn_Controlling_Aesthetics.ipynb)** |
| 03 | **[Seaborn_Matplotlib_vs_Seaborn](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/003_Seaborn_Matplotlib_vs_Seaborn.ipynb)** |
| 04 | **[Seaborn_Color_Palettes](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/004_Seaborn_Color_Palettes.ipynb)** |
| 05 | **[Seaborn_LM Plot_&_Reg_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/005_Seaborn_LM%20Plot_%26_Reg_Plot.ipynb)** |
| 06 | **[Seaborn_Scatter_Plot_&_Joint_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/006_Seaborn_Scatter_Plot_%26_Joint_Plot.ipynb)** |
| 07 | **[Seaborn_Additional_Regression_Plots](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/007_Seaborn_Additional_Regression_Plots.ipynb)** |
| 08 | **[Seaborn_Categorical_Data_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/008_Seaborn_Categorical_Data_Plot.ipynb)** |
| 09 | **[Seaborn_Dist_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/009_Seaborn_Dist_Plot.ipynb)** |
| 10 | **[Seaborn_Strip_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/010_Seaborn_Strip_Plot.ipynb)** |
| 11 | **[Seaborn_Box_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/011_Seaborn_Box_Plot.ipynb)** |
| 12 | **[Seaborn_Violin_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/012_Seaborn_Violin_Plot.ipynb)** |
| 13 | **[Seaborn_Bar_Plot_and_Count_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/013_Seaborn_Bar_Plot_and_Count_Plot.ipynb)** |
| 14 | **[Seaborn_TimeSeries_and_LetterValue_Plot](XXX)** |
| 15 | **[Seaborn_Factor_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/015_Seaborn_Factor_Plot.ipynb)** |
| 16 | **[Seaborn_PairGrid_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/016_Seaborn_PairGrid_Plot.ipynb)** |
| 17 | **[Seaborn_FacetGrid_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/017_Seaborn_FacetGrid_Plot.ipynb)** |
| 18 | **[Seaborn_Heat_Map](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/018_Seaborn_Heat_Map.ipynb)** |
| 19 | **[Seaborn_Cluster_Map](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/019_Seaborn_Cluster_Map.ipynb)** |
|    | **[datasets](https://github.com/milaan9/12_Python_Seaborn_Module/tree/main/datasets)** |
| 11 | **[Python Seaborn Statistical Data Visualization.pdf](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/Python%20Seaborn%20Statistical%20Data%20Visualization.pdf)** |

These are online **read-only** versions. However you can **`Run ▶`**  all the codes **online** by clicking here ➞ <a href="https://mybinder.org/v2/gh/milaan9/12_Python_Seaborn_Module/HEAD"><img src="https://mybinder.org/badge_logo.svg" alt="binder"/></a>


 ---

## Install Seaborn Module:

Open your [![Anaconda](https://img.shields.io/badge/Anaconda-342B029.svg?&style=flate&logo=anaconda&logoColor=white)](https://www.anaconda.com/products/individual) Prompt <img alt="propmt" src="https://img.shields.io/badge/-__-000000?style=flat-square&logo=Plex&logoColor=white"> and type and run the following command (individually):

 -       pip install seaborn


Once Installed now we can import it inside our python code.
