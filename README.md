# Bike Sharing Data Analysis

A Fall 2024 course project analyzing Capital Bikeshare (2011–2012) to explore factors that affect rentals and to build models that predict daily rental counts.

[View Here](https://mdeik.github.io/Bike-Sharing-Data-Analysis/)

**Notebook (release)**
[Download the notebook (latest release)](https://github.com/mdeik/Bike-Sharing-Data-Analysis/releases/latest)



## Quick start

1. Download the released notebook from the Releases page above.
2. (Optional) Convert to standalone HTML:

```bash
jupyter nbconvert --to html Bike_Sharing_Data_Analysis.ipynb
```

3. Open `Bike_Sharing_Data_Analysis.html` or view the hosted Pages site.



## What’s inside

* Data curation & preprocessing (Capital Bikeshare + UCI weather)
* Exploratory Data Analysis (station usage, weekend vs weekday, weather effects)
* Hypothesis testing (chi-square, t-test, ANOVA)
* ML modeling (Polynomial LR, Elastic Net, Bayesian Ridge, Gradient Boosting — GBR performed best)
* Visualizations, insights, and operator recommendations


## Dependencies

Python 3.8+ and:

* pandas, numpy
* matplotlib, seaborn
* scipy, scikit-learn



## Contributors

Matthew Deik, Abhiram Kidambi, Albert Jeng, Matthew Guo, Rishi Anusuri, Samuel Waters.


## Sources

* 2011 Capital Bikeshare Data: [capitalbikeshare-data](https://s3.amazonaws.com/capitalbikeshare-data/index.html)
* 2012 Capital Bikeshare Data: [capitalbikeshare-data](https://s3.amazonaws.com/capitalbikeshare-data/index.html)
* 2011–2012 Capital Bikeshare + weather: [UCI Machine Learning Repository — Bike Sharing Dataset](https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset)



## Further reading & resources

* Gradient Boosting overview — [https://www.geeksforgeeks.org/ml-gradient-boosting/](https://www.geeksforgeeks.org/ml-gradient-boosting/)
* Top ML methods — [https://towardsdatascience.com/10-machine-learning-methods-that-every-data-scientist-should-know-3cc96e0eeee9](https://towardsdatascience.com/10-machine-learning-methods-that-every-data-scientist-should-know-3cc96e0eeee9)
* Data processing with pandas — [https://www.geeksforgeeks.org/data-processing-with-pandas/](https://www.geeksforgeeks.org/data-processing-with-pandas/)
* scikit-learn tutorials — [https://scikit-learn.org/1.4/tutorial/index.html](https://scikit-learn.org/1.4/tutorial/index.html)
* Intro to hypothesis testing — [https://www.geeksforgeeks.org/understanding-hypothesis-testing/](https://www.geeksforgeeks.org/understanding-hypothesis-testing/)
