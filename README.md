# Visualizing Data Based on College Majors

This project analyzes the job outcomes of students who graduated from college between 2010 and 2012. The dataset can be found [here](https://github.com/fivethirtyeight/data/tree/master/college-majors).

Each row represents a different major and contains information on gender diversity, employment rates, median salaries, and more. Here is a description of the dataset:

* `Rank` - Rank by median earnings (dataset is order by this column
* `Major_code` - A unique code for each major
* `Major` - Major's description
* `Major_category` - Category of the major
* `Total` - Total number of people with this major
* `Sample_size` - Unweighted sample size of full-time students
* `Men` - Number of male graduates
* `Women` - Number of female graduates
* `Sharewomen` - Share of female graduates
* `Employed` - Number of employed graduates
* `Median` - Median salary of full-time workers
* `Low_wage_jobs` - Graduates in low-wage service jobs
* `Full_time` - Number of graduates employed 35h or more
* `Part_time` - Number of graduates employed less than 35h

**Objective**: The objective is to visualize different parts of the data based on the college major.

**Techniques used:**
* Pandas, Numpy, Matplotlib
* Scatter plot, histograms, bar plots, scatter matrix plots
* Grouped bar plot
* Box plot
* Hexagonal bin plot
