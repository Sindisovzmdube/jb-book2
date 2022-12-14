---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---


## Data Visualization
![](C:\Users\sindi\Pictures\overpopulated.png)

```{figure} C:\Users\sindi\Pictures\overpopulated.png

```
Assignment Learning Goals: By the end of the module, students were expected to:

- Choose effective visual channels for information display. - Visualize frequencies with bar plots.
- Facet plots to explore more variables simultaneously.
- Customize axes labels and scales. This assignment covers [Module 2](https://viz-learn.mds.ubc.ca/en/module2) of the online course:


The Gapminder.csv dataset was used for most of the chapter. Read_csv from Pandas was used to load the dartaset.

```{code-cell} ipython3
gapminder_df = pd.read_csv("data/world-data-gapminder.csv", parse_dates=['year'])
gapminder_df.head()
```

![](C:\Users\sindi\Downloads\7GFY4xEtGEgGdR3WZNkL--1--f0wme.jpg)

#### Some useful equations used in calculations

$
\displaystyle \mu_A= \frac{(n_1+n_2+n_3 \cdots+n_m)}{m}=\frac{1}{m}\sum_{i=1}^m n_i
$

Sample regression line:
\begin{equation}
\hat{Y}_i = \hat{\beta}_0 + \hat{\beta}_1 X_i + \hat{\epsilon}_i
\end{equation}


"cells": [
{
"attachments": {},
"cell_type": "markdown",
"metadata": {},
"source": [
"<img src="image/logo.png" width=300 height=890 align ='left' />"
]


