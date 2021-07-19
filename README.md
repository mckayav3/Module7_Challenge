# Module 7 Challenge: Web Application for an ETF Analyzer


This application utilizes SQL, Python and Voila to analyze a fintech ETF. The web application will give the daily returns of the ETF stocks individually and as a whole portfolio. The information that we gain from the analysis is then displayed through data visualizations using hvplot.

---

## Technologies

This was run on a pc using Windows 10

This project leverages python 3.8.8 with the following packages:


* [pandas](https://pandas.pydata.org/docs) - For manipulating the DataFrame.

* [Jupyter Lab](https://jupyterlab.readthedocs.io.en/stable) - For code and visualizations.

* [hvplot](https://hvplot.holoviz.org/user_guide/Introduction.html) - For creating the visualization of our data from the DataFrame.

* [numpy](https://numpy.org/install/) - For scientific computing with python.

* [sqlalchemy](https://docs.sqlalchemy.org/en/14/) - For working with our ETF database
---

## Installation Guide

In gitbash after you have activated your dev environment, install the following:

```python
  pip install jupyter lab
```
   
*Plotly

    `conda install -c plotly plotly=4.13`
    
![install plotyly](https://github.com/mckayav3/Module7_Challenge/blob/main/images/install_plotly.JPG)


*Pyviz Hvplot

    `conda install -c pyviz hvplot`
    
![install pyviz hvplot](https://github.com/mckayav3/Module7_Challenge/blob/main/images/install_pyviz_hvplot.JPG)

*Sqlalchemy

    `conda list sqlalchemy`
    
    `pip install SQLAlchemy`
    
![list sqlalchemy](https://github.com/mckayav3/Module7_Challenge/blob/main/images/list_sqlalchemy.JPG)

![install sqlalchemy](https://github.com/mckayav3/Module7_Challenge/blob/main/images/install_sqlalchemy.JPG)



*Voila

    `conda install -c conda-forge voila`
    
    `voila etf_analyzer.ipynbn`
    
![install voila](https://github.com/mckayav3/Module7_Challenge/blob/main/images/install_voila.JPG)

![run voila](https://github.com/mckayav3/Module7_Challenge/blob/main/images/run_voila.JPG)

---

## Examples
The images below show the different types of charts and graphs that should result from running the code in the ETF analyzer. By reviewing the charts and graphs we can analyze the Fintech ETF.


![pypl head and tail](https://github.com/mckayav3/Module7_Challenge/blob/main/images/head_tail_pypl.JPG)

![pypl daily returns](https://github.com/mckayav3/Module7_Challenge/blob/main/images/pypl_daily_returns.JPG)

![pypl cumulative returns](https://github.com/mckayav3/Module7_Challenge/blob/main/images/cum_returns_pypl.JPG)

![pypl higher than 200](https://github.com/mckayav3/Module7_Challenge/blob/main/images/pypl_higher_200.JPG)

![etf portfolio inner join](https://github.com/mckayav3/Module7_Challenge/blob/main/images/inner_join_portfolio.JPG)

![etf portfolio cumulative returns](https://github.com/mckayav3/Module7_Challenge/blob/main/images/etf_portfolio_cum_returns.JPG)

![Voila etf screenshot](https://github.com/mckayav3/Module7_Challenge/blob/main/images/Screenshot_etf_analyzer.jpg)