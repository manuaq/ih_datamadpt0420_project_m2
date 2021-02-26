

<p align="left"><img src="https://cdn-images-1.medium.com/max/184/1*2GDcaeYIx_bQAZLxWM4PsQ@2x.png"></p>

## __ih_datamadpt0420_project_m2__

![Image](https://venngage-wordpress.s3.amazonaws.com/uploads/2020/06/What-is-Data-Visualization-Blog-Header.jpg)


### For this project we will perform exploratory data analysis on the __diamonds_train.csv__ dataset.

---
## **Purpose:**

- To get familiar with visualization libraries & tools: matplotlib, Seaborn and Tableau.
- Use summary statistics and visualization as a first exploratory analysis on dataset.
- Explain why your dashboard functionalities are the best for getting meaningful data insights.

---
## **Deliverables:**

A GitHub repository, preferably named: __ih_datamadpt0420_project_m2__, including:

- `data_analysis_report.ipynb` file that holds the results of __Challenge 1__ + __Bonus Challenge__. 

- `Tableau Public Dashboard` including your dashboard proposal (__Challenge 2__).

- `README.md` file explaining the job done, your main conclusions and the __link to your Tableau Public Dashboard__. You may find more info of how to build a README file [here](https://github.com/potacho/data-project-template/blob/master/README.md).

---

## **Context:**

### **Dataset:**

- __Rows:__ Contains information about 4055 unique diamonds (4055 rows).
- __Columns:__ 7 relevant attributes or characteristics for diamonds.
  ['carat'], ['depth'], ['table'], ['price'], ['x'], ['y'], ['z']
<p align="center"><img src="https://www.diamonds717.com/wp-content/uploads/2019/03/lab-diamond-1024x320.jpg"></p>


> __IMPORTANT NOTE:__ Although numbers and statistics on their own can provide a lot of useful and relevant information, probably any appropriate Data Exploration effort should start with getting familiar with the fundamentals of the business or topic on which data will be analyzed.

---

## __The Diamonds 4 C's:__

<p align="center"><img src="https://selectingadiamond.com/wp-content/uploads/2019/10/The-4Cs.jpg"></p>

The 4Cs are a big factor when it comes to evaluating a diamond. Having a good understanding of the 4Cs will make the exploratory job easier.

The individual characteristics of a diamond can play more or less of a role depending on the diamond’s specific shape, so knowing the shape should play a big role in terms of knowing how to evaluate a diamond. (This attribute or characteristic it's not included on our dataset columns.)

<p align="center"><img src="https://www.havelustre.com/wp-content/uploads/shape-1536x247.png"></p>


\
The relevant categorical variables we do have, are:

### **Carat:**
<p align="center"><img src="https://selectingadiamond.com/wp-content/uploads/2019/09/how-size-and-weight.jpg"></p>
Diamonds are graded by their weight. The more a diamond weighs, the greater its value. Simple!

If you want to get technical, a carat is divisible by 100 points. If a diamond is 0.50ct, it may be referred to as 50 points. Diamonds over the 1 carat weight use carat and decimals. For example, a 1.25ct diamond would be “one point 25 carats.”

### **Cut:**
<p align="center"><img src="https://www.havelustre.com/wp-content/uploads/cut.png"></p>
The cut of a diamond primarily focuses on the quality of its proportions, symmetry, and polish.

- Proportions = measurements and angles relative to each other.
- Symmetry = alignment of the facets (triangular “cuts”) relative to each other.
- Polish = smoothness of the outer surface

Diamonds are graded on a scale from Excellent to Poor (Excellent, Very Good, Good, Fair, Poor). The closer a diamond is to Excellent, the rarer it is.

### **Color:**
<p align="center"><img src="https://www.havelustre.com/wp-content/uploads/color.png"></p>
The “color” of a diamond focuses on the LACK of color it contains; the closer to colorless, the higher the value. Although, colored diamonds are becoming increasingly more popular and have a scale all to themselves.

### **Clarity:**
<p align="center"><img src="https://www.havelustre.com/wp-content/uploads/clarity-1536x482.png"></p>
The “color” of a diamond focuses on the LACK of color it contains; the closer to colorless, the higher the value. Although, colored diamonds are becoming increasingly more popular and have a scale all to themselves.


---



## **Challenge 2: Tableau Data Dashboard**

Dashboards are powerful tools for communicating important information __at-a-glance__. The goal of this challenge is to build a data dashboard using our diamonds dataset that will help the final user (i.e.: yourself) to perform better during _Module 3 project (Kaggle Competition)_. 

> __Tip:__ you should first considerate which data and which indicators should be put on the dashboard. Then, decompose the key indicators from multiple dimensions. 

<p align="center"><img src="https://media.giphy.com/media/l46Cy1rHbQ92uuLXa/giphy.gif"></p>


A data dashboard is not exactly a sequential set of descriptive charts like those you have built in challenge 1. Instead, a data dashboard should be __a single interactive interface built around a specific objetive and which components are logically arranged in order to provide data relevant insights effectively__. Therefore, bear in mind the main objective of the competition: _understand the relationship between diamonds attributes (features) or group of attributes, and its price_.



--- 



## **Bonus Challenge: Hypothesis Testing**

<p align="center"><img src="https://github.com/potacho/ih_datamadpt1120_project_m2/blob/master/images/htesting.jpg"></p>

We might want to know if our sample and sub-samples are representative of diamonds in general. Moreover, we might want to reach some conclusions about the influence of certain diamonds features in their price. In that sense, we propose you to perform two statistical tests:

**Test 1 - one sample vs constant hypothesis test.** We know from the available literature that diamonds average price rounds about 4000 USD. The aim is to test whether the prices in our sample are significantly different from the literature value. Give some conclusions about the implications of your test results.

**Test 2 - two independent samples.** Our sample includes diamonds with different features (carat, cut, color clarity, etc.). It seems clear that the carat plays an important role in price. However, it's not that clear whether the prices of some "sub-groups" are significantly different from each other. These are the "sub-groups" that you might feel suspicious about it:

- **Sub-Test 1:** Fair cut + color G vs. Fair cut + color I

- **Sub-Test 2:** Good cut + color E vs. Good cut + color F

- **Sub-Test 3:** Ideal cut + color D vs. Ideal cut + color E

- **Sub-Test 4:** Premium cut + color D vs. Premium cut + color E

- **Sub-Test 5:** Very Good cut + color I vs. Very Good cut + color J

- **Sub-Test 6:** All cuts + color D vs. All cuts + color E

<p align="center"><img src="https://media.giphy.com/media/26vUAAwkzAMnBj9x6/giphy.gif"></p>

> __IMPORTANT NOTE:__ Remember to also include your conclusions about the implications of your test results and all metrics involved (e.g.: samples size).

---

## **References:**

- [Visual Analysis Best Practices](https://github.com/potacho/ih_datamadpt1120_project_m2/blob/master/images/visual-analysis-guidebook.pdf)

- [Financial Times Visual Vocabulary](https://github.com/ft-interactive/chart-doctor/tree/master/visual-vocabulary)

- [Matplotlib](https://matplotlib.org/)

- [Pandas Visualization](https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html)

- [Seaborn](https://seaborn.pydata.org/)

- [Introducing plotly express](https://medium.com/plotly/introducing-plotly-express-808df010143d)

- [Tableau Public](https://public.tableau.com/)

- [Tableau Viz of the Day](https://public.tableau.com/es-es/gallery/?tab=viz-of-the-day&type=viz-of-the-day)

- [Statistical functions (scipy.stats)](https://docs.scipy.org/doc/scipy/reference/stats.html)

- [Two-sample one-tailed t-test with Scipy](https://stackoverflow.com/questions/15984221/how-to-perform-two-sample-one-tailed-t-test-with-numpy-scipy)
