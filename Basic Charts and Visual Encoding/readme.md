# Experiment 16 - Basic Charts and Visual Encoding

Charts trasform numerical data into visual patterns, to identify trends, outliers and correlations much fatser than scanning raw tables. They provide a clear, intuitive summary of information that simplifies storytelling and supports data-driven decision-making.

### Aim:

To implement Basic charts in Python for Viualizing data

### Tools used:

Google Colab or Jupyter Notebook

### Theory:

#### Matplotlib

**Matplotlib** is the foundational library in Python which is used to create static and creative visualization. It provides Object Oriented interface that allows granular control over every element of the figure which includes axes, labels, Line styles, Edge color, etc. It is designed to resemble MATLAB's plotting capabilties. 

It is widely used for generating publication-quality plots such as line graphs, scatter plots, and histograms. While it is incredibly powerful, creating complex visualizations often requires writing extensive code to manage fine details. It serves as the base upon which many other specialized plotting libraries are built.


#### Seaborn

It is the high level data visualization library built on Matplotlib which is used for advanced statistical graphs. It simplifies the creation of complex plots by providing a more concise syntax and integrating seamlessly with Pandas Data Frames. 

Seaborn comes with built - in themes and color patterns which makes the plot look professionaly good and presentation ready with minimal effort. The addition of features like Edge color and Line width are added by default without any specificatiins while writing the code. It excels at visualizing multivariate relationships, offering specialized functions for heatmaps, violin plots, and regression models.


#### Types of Charts:

**1. Line Graph:**

* A line graph displays information as a series of data points called "markers" connected by straight line segments to show how a value changes over a continuous interval.
* It is primarily used to track changes over short and long periods of time or to identify trends in data.
* By visualizing the slope between points, users can quickly determine if a variable is increasing, decreasing, or remaining stable.
* They are the standard choice for time-series analysis, such as monitoring temperature fluctuations or stock market trends.

**2. Bar Chart:**

A bar chart represents categorical data with rectangular bars where the lengths or heights are proportional to the values they represent. These charts can be plotted vertically or horizontally and are used to compare distinct groups or categories against one another. They are highly effective for showing large differences in data and making specific values easy to read at a glance. Common uses include comparing the populations of different countries or the sales performance of various products within a single quarter.

**3. Histogram:**
A histogram is used to represent the distribution of a single continuous numerical variable by dividing the data into "bins" or intervals. Unlike a bar chart, the bars in a histogram are adjacent to each other, indicating a continuous range of values rather than discrete categories. Its primary purpose is to show the underlying frequency distribution, such as whether the data is normal (bell-shaped), skewed, or contains outliers. It is essential for understanding the spread and central tendency of datasets, like exam scores or height measurements.


**4. Scatter Plot:**
A scatter plot uses dots to represent the values for two different numeric variables, with the position of each dot representing a single data point on the horizontal and vertical axes. This visualization is used to observe and show relationships or correlations between two variables. It helps in identifying patterns such as positive or negative trends, clusters, or gaps in the data. Researchers often use scatter plots to determine if one variable might be a predictor of another, such as the relationship between study hours and test results.

**5. Seaborn Line Plot:**

A Seaborn line plot is a high-level statistical visualization that enhances the basic line graph by automatically aggregating data and displaying uncertainty. It is specifically designed to handle Pandas DataFrames, making it easy to plot multiple observations for the same x-value, which it represents as a single line with a translucent "shadow" representing the confidence interval. The purpose of use is to visualize the relationship between two variables while accounting for variance or noise in the data. It is ideal for scientific research where showing the reliability of a trend is just as important as the trend itself.


### Learning Outcomes:

* There are three commands that can be used in conditional statements: if, elif, and else.

* While writing the commands mentioned above, a semicolon (:) must be used at the end. While proceeding to the next line, a small space will be present at the start of the line, which is called "indentation."**

* In Python, if indentation is not there, it shows an error.

* The else statement is not compulsory in the conditional statement, but it is used as a safety block of code.

### Applications of lists:

* Automated Control Systems: Conditional statements are used to maintain *homeostasis** in a system.

* Automotive Safety Systems: Real-time embedded systems in cars use conditionals to make split-second decisions.

* It is used for *fraud detection** in financial technology.

### Advantages:

* Dynamic Decision Making: It has the ability to handle various inputs at the same time. Without conditionals, programs would be "static," performing the same task regardless of the data.

* Error Handling and Robustness: Conditionals allow for guard clauses, which prevent a program from crashing when it encounters bad data.

* Flexibility via "Truthiness": Python allows you to check for the existence of data without formal comparisons.

### Conclusion:

Thus various types of conditional statements are executed in Python and the output is verified.

