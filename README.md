# Unsupervised Learning Cryptocurrencies

## *Introduction*

This **Jupyter notebook** will used **unsupervised learning** to scale down a DataFrame of cryptocurrency price percentage changes, and it will create a scatter plot grouped by resulting cluster groups created by the **K-Means algorithm**.

---

## Technologies

**Python 3.7.9** was used to code this **Jupyter notebook** application.  The primary Python libararies used to make this analysis possible are: **Pandas** and **Sci-Kit Learn**.  The following modules were imported from **Sci-Kit Learn**:  the **K-Means algorithm**, **Standard Scaler**, and **Principal Component Analysis (PCA)**.  The resulting DataFrames will be plotted using **hvplot** from the **Pandas** library.

---

## Installation Guide

To run this notebook, you must have **Jupyter notebook** installed.  From there you can run **Git Bash**, **Terminal**, or any **command line interface**, and do the following to launch the notebook:

```python
jupyter lab
```

After opening **Jupyter notebook**, navigate to where your notebook is located, and you can open the notebook from there.

![install1](https://user-images.githubusercontent.com/80929342/120078891-69410c80-c066-11eb-8fb5-be67e4a02f4e.JPG)

---

## Examples & Usage

The notebook will start off by importing all the required libraries to run to the analysis on the initial DataFrame:

![use1](https://user-images.githubusercontent.com/80929342/120079032-00a65f80-c067-11eb-8d7c-a5d188a5cf00.JPG)

---

**Standard Scaler** will be used to convert all the values of the DataFrame into a more easily comparable (hence **scalable**) data set for analysis:

![use2](https://user-images.githubusercontent.com/80929342/120079137-6c88c800-c067-11eb-99fa-65e352a877a2.JPG)

---

We will be able to obtain elbow data by using the **K-Means algorithm** to create a DataFrame and use **hvplot** to create a visualization.  This will help us determine what the best value for **'k'** would be for our final scatter plot visualizations:

![use3](https://user-images.githubusercontent.com/80929342/120079204-b671ae00-c067-11eb-87a9-2330603ae952.JPG)

---

After finding the best value for **'k'**, we will then compare scatter plots for different clusters to help us see which cluster group is the most accurate to visualize the resulting profits of crytocurrencies:

![use4](https://user-images.githubusercontent.com/80929342/120079289-0ea8b000-c068-11eb-899d-40c450fbf3c0.JPG)

---

## Contributors

**I would like to thank and acknowledge my UCB FINTECH Class for their questions and input that contribute to the success and knowledge base for the class!**

---

## License

No license is needed to use this app.
