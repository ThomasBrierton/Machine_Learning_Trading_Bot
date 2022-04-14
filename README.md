# Machine_Learning_Trading_Bot

This Machine Learning Trading Bot combines algorithmic trading skills with Python programming and machine learning that learns and adapts to new data and evolving markets. This gives firms a competitive advantage in terms of data processing speed, decision making, and atomated algorithmic trading. 

---

## Approach

The following steps are completed in a Jupyter notebook:

1. Implement an algorithmic trading strategy that uses machine learning to automate the trade decisions.
2. Adjust the input parameters to optimize the trading algorithm.
3. Train a new machine learning model and compare its performance to that of a baseline model.

---

## Technologies

This project uses Jupyter notebook and the standard Python 3.8 libraries. This project requires the following libraries and/or dependencies:

- [Pandas](https://pandas.pydata.org/) - a software library designed for open source data analysis and manipulation.
- [NumPy](https://numpy.org/) - The fundamental package for scientific computing with Python.
- [sklearn](https://scikit-learn.org/stable/) - HoloViews is an open-source Python library designed to make data analysis and visualization seamless and simple.
- [hvPlot](https://hvplot.holoviz.org/)) - A high-level plotting API for the PyData ecosystem built on HoloViews.
- [matplotlib](https://matplotlib.org/) - Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python.

---

## Results

**3 Month Offest**

![](https://github.com/ThomasBrierton/Machine_Learning_Trading_Bot/blob/main/Photos/cum_prod_plot_3.png)
![](https://github.com/ThomasBrierton/Machine_Learning_Trading_Bot/blob/main/Photos/3_month_results.png)

**6 Month Offest**

![](https://github.com/ThomasBrierton/Machine_Learning_Trading_Bot/blob/main/Photos/cum_prod_plot_6.png)
![](https://github.com/ThomasBrierton/Machine_Learning_Trading_Bot/blob/main/Photos/6_month_results.png)

Adjusting the DateOfSet helps improve the recal and precision slightly better on the 6 month offset.

**short_window=10, long_window=200**

![](https://github.com/ThomasBrierton/Machine_Learning_Trading_Bot/blob/main/Photos/cum_prod_plot_10_200.png)
![](https://github.com/ThomasBrierton/Machine_Learning_Trading_Bot/blob/main/Photos/10_200_results.png)

The short_window=10 and the long_window=200 helps imporve the model slightly. 

**short_window=10, long_window=200, 6 Month Offset**

![](https://github.com/ThomasBrierton/Machine_Learning_Trading_Bot/blob/main/Photos/cum_prod_plot_10_200_6month.png)
![](https://github.com/ThomasBrierton/Machine_Learning_Trading_Bot/blob/main/Photos/10_200_6_month_results.png)

The short_window=10, long_window=200, and the DateOfSet at 6 months helps improve the recall for the -1.0. More tuning and choosing different parameters would be helpful to improve the results.

**Logistic Regression Classifier Model**

![](https://github.com/ThomasBrierton/Machine_Learning_Trading_Bot/blob/main/Photos/lr_cum_prod_plot.png)
![](https://github.com/ThomasBrierton/Machine_Learning_Trading_Bot/blob/main/Photos/lr_results.png)

The results for the logistic regression model are more balanced than the previous models. All models are better at predicting the 1 than the -1 (as seen in all models, but the logistic regression model did a better job at balanced results.

## Contributors 

Thomas Brierton and UCB

---

## License

MIT