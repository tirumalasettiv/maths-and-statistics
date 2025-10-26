# Mathematics and Statistics

## Data & Visualization Basics

### Types of Data
1. **Structured data** is organized, follows a clear format,
and is easy to work with. (Ex: Table data, JSON,
XML)
2. **Unstructured data** lacks a specific structure, is
more diverse in content, and requires specialized  tools and techniques for analysis. (Ex: Audio, Video,
Free Form Text)

3. **Numeric data** consists of numerical values that
represent measurable quantities or continuous variables 

    - **Continuous data** encompasses an infinite range of
    precise values, often with decimals. (Ex. Stock prices over a period of time)

    - **Discrete data**, on the other hand, comprises
    distinct, countable numerical values. (Ex. a film released in 2025)

4. **Categorical data** represents categories, labels, or
distinct groups. It is used to classify and categorize
items or observations based on certain
characteristics or attributes.
    - **Nominal data** consists of categories or labels with
    no inherent order or ranking. (Ex. Product categories)

    - **Ordinal data** unlike nominal data, has a specific
    order or ranking among categories.(Ex. Students grades)

### Pie and Bar Chart

1. Use a **bar chart** when you have benchmark values
to compare with.

2. Use a Horizontal bar chart when **category labels**
are long.
3. Use a Horizontal bar chart instead of a pie chart
when the number of categories is **more than 5**.
4. Use a vertical bar chart for **time series data**.
5. Consider a **Clustered Column** chart for comparing
multiple data series within distinct categories.

### Histogram and Line Chart

1. Histograms are primarily used to show the
**frequency distribution** of a continuous or discrete
dataset.
2. In a histogram, all bins are of **equal size**.
3. A line chart is useful in presenting the **trend or
change** in data over a period.
4. A stacked column chart used to represent and
compare multiple categories in a single bar, while
also displaying the overall total.

### Scatter and Bubble Plot

 1. A **scatter plot** is a graph that uses a grid to present
data values, typically involving two variables within
a dataset.

 2. Scatter plots help to visualize the **relationship
between two variables**.

3. A **Bubble chart** is a variation of a Scatter Plot that
allows you to represent a third variable through the
size of the bubbles.

4. **Scatter plots** and Bubble Charts help to detect
outliers, visualize the relationship between two
variables, and also Identify trends.

### Univariate vs Bivariate vs Multivariate analysis

1. **Univariate analysis** = Analysis of a **single** variable
2. **Bivariate analysis** = Analysis of **two** variables
3. **Multivariate analysis** = Analysis of > **two** variables

## Measures of Central Tendency and Dispersion 

### Descriptive vs Inferential Statistics 

1. **Inferential Statistics** involve making predictions or drawing conclusions about a population based on a sample. 

    >Examples: 
    > - Predicting election results based on a sample poll.
    >- Estimating average income of a city from a survey sample. 


    
2. **Descriptive Statistics** are used to summarize or decribe data , providing an overview of its main characteristics.

    > Examples:
    > - Calculating average monthly sales.
    > - Creating a histogram of customer ages.

### Measures of Central Tendency: Mean, Median, Mode

1. **Mean** - Synonym for average.

2. **Median** -Middle value of a dataset 
when it is
ordered in ascending order. If the dataset has an even number of values, the median is the average of the two middle values.

3. **Mode** - Most frequently occurring data value.
    > Examples:
    > - Mean: Average marks of students in a class.
    > - Median: Middle salary in a sorted list of employee salaries. 
    > - Mode: Most common shoe size sold in a store.

### Percentile

1. A percentile is a statistical measure used to rank a
value within a dataset, indicating what percentage
of the data falls below or is equal to that value.
2. 25th Percentile: The value below which 25% of the
data falls; it represents the lower quartile.

3. 50th Percentile (Median): The middle value of the
dataset; it divides the data in half.

4. 75th Percentile: The value below which 75% of the data falls; it corresponds to the upper quartile
    >Examples:
    > - A student scoring in the 90th percentile on SAT is above 90% of test-takers.
    > - 25th percentile of delivery times indicates 25% of orders arrived faster than that time.


### Measures of Dispersion: Range, IQR

1. IQR" and "Range" also referred to as measures of **dispersion or variability**.

2. Range, calculated as **Maximum Value - Minimum
Value**, reflects data spread.

3. Unlike Range, IQR(Inter Quartile Range) is less influenced by **outliers**, making it a robust measure.

4. Quartiles **Q1, Q2, and Q3** correspond to the **25th, 50th, and 75th**  percentiles, respectively.

5. The **50th** percentile is commonly known as the
median.

6. IQR is the difference between **Q3 and Q1**, showing the spread of the **middle 50%** of data.
    > Examples:
    > - Range: Highest temperature (40°C) – Lowest (20°C) = 20°C.
    > - IQR: Q3 (75th percentile) = 80, Q1 (25th percentile) = 60 → IQR = 20.

### Box or Whisker Plot

1. Box/Whisker Plots provide a visual summary of the **central tendency, spread, and presence of outliers** in a dataset.
2. The **"box"** in a Box Plot shows the **middle 50%** of the data, with the line inside representing the **median**. It gives insights into the central data values and their spread.
3. The **"whiskers"** in a Box Plot show the **minimum and maximum** values within a specific range.

    >Examples:
    > - Visualizing income distribution across departments.
    > - Comparing test score spreads between two schools.


## Outlier treatment using IQR and box plot

1. The **Interquartile Range (IQR)** is determined by subtracting the first quartile (Q1) from the third quartile (Q3).
2. The Lower Limit is calculated as the first quartile (Q1) **minus 1.5 times** the IQR.
3. The Upper Limit is derived by **adding 1.5 times** the IQR to the third quartile (Q3).
    > Examples:
    > - Q1 = 50, Q3 = 70 → IQR = 20 → Lower limit = 50 - 1.5×20 = 20, Upper = 70 + 1.5×20 = 100.
    > - A value of 110 would be an outlier in this case.


### Measures of Dispersion: Variance and Standard Deviation

1. Variance is a measure of how spread out a distribution is. It is calculated as **the average of the squared differences from the mean**.
2. The smaller the variance, the less spread out the data is. Conversely, the larger the variance, the **more spread out** the data is.
3. Standard deviation is a measure of the amount of variation or dispersion of a set of values. It is calculated as the **square root** of the variance.
4. The smaller the standard deviation, the closer the data points are to the mean. Conversely, the larger the standard deviation, the more spread out the
data points are.
5. The stock market's volatility is the best use case for variance and standard deviation.
    >Examples:
    >- Variance: Comparing consistency of delivery times between two courier services. 
    >- Standard Deviation: Analyzing volatility of two different stocks.

### Correlation

1. Correlation is a statistical measure that shows the degree to which two variables are related.
2. A correlation coefficient can range from -1 to 1
    - -1 (perfect negative correlation) < 0 (no correlation) < 1 (perfect positive correlation)
    > Examples:
    > - Positive: Height and weight tend to increase together.
    > - Negative: Number of hours watching TV vs exam scores.


### Correlation vs Causation

1. **Correlation**: A statistical relationship between two variables, where changes in one variable are associated with changes in another, but it doesn't
imply causation.
2. **Causation**: A cause-and-effect relationship between variables, where changes in one variable directly lead to changes in another
    >Examples:
    >- Correlation: Ice cream sales and drowning incidents (both rise in summer).
    >- Causation: Increasing study time leads to better grades.


## Probability Theory

### Probability Basics

1. **Probability** is a measure of the chance of an
event happening. It ranges from **0 (impossible)** to
**1 (certain)**.
2. It's calculated by dividing **favorable** outcomes by
**possible outcomes**.
    >Examples:
    >- Probability of rolling a 4 on a die = 1/6.
    >- Probability of drawing a red card from a deck = 26/52 = 0.5.

### Addition and Multiplication Rule

1. **Addition Rule**:
    - Non-overlapping Events: p(E ∪ F) = p(E) + p(F) where
    event E and F don't overlap.
    - Overlapping Events: p(E ∪ F) = p(E) + p(F) - p(E ∩ F)
    >Examples:
    >- p(rolling 2 or 4) = p(2) + p(4) = 1/6 + 1/6 = 1/3.
    >- p(rolling even or prime) = p(even) + p(prime) - p(even ∩ prime).

2. **Multiplication Rule**:
    - Independent Events ("And" Rule): p(E ∩ F) = p(E) * p(F)
    - Dependent Events ("Conditional" Rule): p(E ∩ F) = p(E) * p(F | E)
    >Examples:
    >- Independent: p(Heads on coin) × p(6 on die) = 0.5 × 1/6 = 1/12.
    >- Dependent: p(Drawing 2 red cards without replacement).
3. **Complement Rule**:

    - p(E′) = 1 - p(E), where E' is the complement of event E.
    > Example:
    >- p(Not getting heads) = 1 - p(Heads) = 0.5.
### Conditional Probability and Bayes Theorem

1. **Conditional probability** means finding the **chance of an event happening** when we already know that another related event has occurred.
2. **Bayes’ Theorem** is a mathematical formula for **determining conditional probability**.
3. The formula for Bayes' theorem is: p(E∣F)= p(F∣E)⋅p(E) / p(F)
    >Examples:
    >- Conditional: p(Passed | Studied) = 0.9.
    >- Bayes: Given a positive test result, what’s the probability the person actually has the disease?

## Distributions

### What is a Distribution?

1. **Distribution** refers to the **arrangement or spread** of different values.
2. **Normal distribution** features most values clustered in the middle, forming a **bell-shaped curve**.
3. **Probability distribution** estimates the **likelihood of various outcomes** based on chance.
4. In a **discrete distribution**, things only happen in **specific steps or groups**, like counting numbers.
5. **Continuous distribution** deals with values occurring **anywhere within a range**, such as height or weight measurements.

    >Examples:
    >- Discrete: Number of cars sold per day.
    >- Continuous: Heights of students in a class.

### Skewness

1. **Right-skewed distribution**: Most data on the left with a few high values extending right.
2. **Left-skewed distribution**: Most data on the right with a few low values extending left.
3. **Zero-skewed distribution**: Data evenly spread around the mean, forming a symmetrical shape.
4. In a **right**-skewed distribution: **Mean > Median**.
5. In a **left**-skewed distribution: **Median > Mean**.
6. In a **normal** distribution, Mean = **Median = Mode**.

    >Examples:
    >- Right-skewed: Income distribution in a city.
    >- Left-skewed: Age at retirement in a government job.

### Normal Distribution

1. **Mean**: Average value, calculated by **summing** all values and **dividing** by their count.
2. **Standard Deviation**: Measures how far data is **spread from the mean**; lower indicates **closer to average**, higher indicate more spread out.
3. **68-95-99.7 Rule**: In a normal distribution, 68% of data falls within **one standard deviation** from the mean, 95% within **two**, and nearly 99.7% within **three** standard deviations.

    >Examples:
    >- Heights of adult males.
    >- IQ scores in a population.

### Detect Outliers Using Normal Distribution

1. An **outlier** is a number/value in a set that is much **higher or lower** than the others.
2. Outliers can be identified using a **normal distribution** and **standard deviation**, as they typically fall far outside the typical range of values.
    >Examples:
    >- A test score of 20 when the mean is 70 and SD is 10.
    >- A stock price jump from $100 to $300 in one day.

### Z Score

1. **Z-score** shows how many **standard deviations** a data point is from the **mean**.
2. **Formula** for z-score: (x-μ) / σ
3. It is used in **comparing datasets** and **removing outliers**.
4. **Outliers** are typically identified when the z-score **exceeds 3 or falls below -3**.

    >Examples:
    >- A student’s score of 85 when class mean is 70 and SD is 10 → z = (85-70)/10 = 1.5.
    >- A delivery time of 50 mins when average is 30 mins with SD 5 → z = 4 (likely an outlier).

### Standard Normal Distribution (SND)


1. The **SND(standard normal distribution)** is a bellshaped curve with a **mean of 0** and a **standard deviation of 1**.
2. It is used in **comparing datasets, calculating probabilities**, and in **Z-tests** to assess differences between means.

    >Examples:
    >- Comparing two students’ scores from different exams using z-scores.
    >- Calculating probability of a value falling within ±2 SDs.
