# Honey-Production-Analysis-Project

## Project Description

In 2006, global concern was raised over the rapid decline in the honeybee population, an integral component to American honey agriculture. Large numbers of hives were lost to Colony Collapse Disorder, a phenomenon of disappearing worker bees causing the remaining hive colony to collapse. Speculation to the cause of this disorder points to hive diseases and pesticides harming the pollinators, though no overall consensus has been reached. Twelve years later, some industries are observing recovery but the American honey industry is still largely struggling. The U.S. used to locally produce over half the honey it consumes per year. Now, honey mostly comes from overseas, with 350 of the 400 million pounds of honey consumed every year originating from imports. This dataset provides insight into honey production supply and demand in America by state from 1998 to 2012.

## Dataset

[Honey Production Dataset](https://github.com/Rahul1097/Honey-Production-Analysis-Project/blob/master/honeyproduction.csv)

Useful metadata on certain variables of the honeyproduction dataset is provided below:

- numcol: Number of colonies producing honey. Honey producing colonies are the maximum number of colonies from which honey was taken during the year. It is possible to take honey from colonies which did not survive the entire year
- yieldpercol: Honey yield per colony. Unit is pounds
- totalprod: Total production (numcol x yieldpercol). Unit is pounds
- stocks: Refers to stocks held by producers. Unit is pounds
- priceperlb: Refers to average price per pound based on expanded sales. Unit is dollars.
- prodvalue: Value of production (totalprod x priceperlb). Unit is dollars.
- Other useful information: Due to rounding, total colonies multiplied by total yield may not equal production. Also, summation of states will not equal U.S. level value of production.

## Objectives

- How has honey production yield changed from 1998 to 2012?
- Over time, which states produce the most honey? Which produce the least? Which have experienced the most change in honey yield?
- Does the data show any trends in terms of the number of honey producing colonies and yield per colony before 2006, which was when concern over Colony Collapse Disorder spread nationwide?
- Are there any patterns that can be observed between total honey production and value of production every year?
- How has value of production, which in some sense could be tied to demand, changed every year?

## Project Solution

- [Honey Production Analysis](https://github.com/Rahul1097/Honey-Production-Analysis-Project/blob/master/Honey%20Production%20Analysis.ipynb)

## Technology Stack
- Python - Pandas,Numpy,Seaborn,Matplotlib
- Data Analysis
- Jupyter Notebook

## References
- Kaggle
