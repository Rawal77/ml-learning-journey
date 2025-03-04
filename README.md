# ml-learning-journey
A well-structured repository showcasing my journey through Python and ML concepts, documenting each step of progress


## Progress

**Day 1:** Python Fundamentals
  - Covered basics like "Hello World" and variables
  - Explored arithmetic and logical operators
  - Practiced useful functions: round(), divmod(), isinstance()
  - Documented with comments for better understanding

**Day 2:** Exploring File Handling and OOP in Python
  - Learned how to read, write, and append data to text files.
  - Discovered the convenience of the with statement for automatically closing files.
  - Classes and Objects: Understood how to model real-world entities using Python classes.

**Day 3:** Exploring Advanced Functions in Python
  - Explored the power of lambda functions for creating concise, anonymous functions.
  - Learned how to use filter(), map(), and reduce() to process and transform data efficiently.

**Day 4:** Introduction to Numpy
  - Explored the fundamentals of NumPy and created 1D, 2D, and 3D arrays to understand their structure and behavior.
  - Learned about array attributes like shape, size, dtype, and ndim, which help analyze and manipulate arrays.
  - Practiced reshaping arrays and converting between data types, such as int, float, and datetime.
  - Gained hands-on experience with array methods like sum(), mean(), min(), and max() for quick data analysis.

**Day 5:** Exploring Numpy, Arrays, Methods and Broadcasting
  - Explored the difference between array and ndarray in NumPy.
  - Learned array methods for reshaping, axis-specific operations, and calculations like sum, mean, min, and max.
  - Practiced creating arrays using zeros, ones, and asarray from lists and tuples.
  - Understood broadcasting rules for performing operations on arrays with different shapes.
  - Discovered how to create arrays from iterables using fromiter.

**Day 6:**  NumPy – Iteration, Updates, and Array Manipulation
  - Practiced generating numerical ranges using arange, linspace, and logspace.
  - Explored array iteration with standard loops, nditer, and ndenumerate for advanced traversal.
  - Learned to update arrays using fill, indexing, put, and condition-based updates.
  - Worked on array manipulation techniques like reshaping, flattening (flatten, ravel), concatenation, and splitting 
    arrays.

**Day 7:**  NumPy – String Manipulation and Mathematical Functions
  - Performed string manipulations like concatenation with char.add(), title-casing with char.title(), and splitting, joining, and replacing characters in arrays.
  - Applied bitwise operations like bitwise_and() for array-level binary calculations.
  - Worked with trigonometric functions (sin, cos, arccos) and mathematical functions (exp, power, absolute, log).
  - Performed arithmetic operations like addition, subtraction, and division, and explored statistical functions (mean, median, std, var) for data analysis.

**Day 8:**  NumPy – Indexing, Sorting, Searching, and Views
  - Practiced fancy indexing and boolean indexing to select and filter array elements efficiently.
  - Sorted arrays using np.sort(), argsort(), and axis-based sorting for multi-dimensional arrays.
  - Explored searching techniques like np.searchsorted(), np.where(), np.argwhere(), and np.nonzero() to locate elements based on conditions.
  - Worked on filtering arrays using boolean indexing, np.where(), np.extract(), and np.compress() with masks.

**Day 9:**  Pandas – Introduction and Core Data Structures
  - Learned about Series, a one-dimensional labeled array, and practiced creating Series from lists, tuples, and string values.
  - Worked with DataFrames, a two-dimensional tabular data structure, and created DataFrames using dictionaries.
  - Understood that Panels, previously used for three-dimensional data, are now deprecated, and explored concatenation as an alternative

**Day 10:**  Pandas – Series Creation, Indexing and Arithmetic Operations
  - Explored different methods to create a Pandas Series, including direct initialization, lists, tuples, and dictionaries.
  - Practiced indexing techniques in Series:
      - Label-based indexing (.loc[]) for accessing elements by custom labels.
      - Integer-based indexing (.iloc[]) for position-based selection.
      - Boolean indexing to filter elements based on conditions.
        
**Day 11:**   Pandas – Series Comparisons, Aggregations, and Advanced Methods
  - Practiced comparison operations on Series, including equality (==), inequality (!=), greater than (>), and less than (<) to compare elements efficiently.
  - Explored aggregation functions such as mean(), min(), max(), count(), and sum() to derive insights from Series data.
  - Worked with essential Series methods, including:
    - head(n) & tail(n) for previewing data.
    - describe() for statistical summaries.
    - unique() & value_counts() for identifying distinct values and their frequencies.
  - Handled missing data using fillna() to replace NaN values and dropna() to remove them.
  - Used concat() to merge multiple Series, with ignore_index=True to reset indexing after concatenation.

**Day 12:**   Pandas – DataFrame Creation, Indexing, and Operations
  - Explored different ways to create a DataFrame using lists, dictionaries, list of dictionaries, and Series.
  - Practiced selecting, adding, and deleting columns using indexing and drop().
  - Worked with row operations, including selecting with .loc[] and .iloc[], adding new rows, and deleting rows.
  - Used aggregation functions like mean(), sum(), and count() to summarize data.

**Day 13:**   Pandas – Filtering, Missing Data Handling, and Advanced Methods
  - Practiced filtering DataFrame rows based on conditions, such as selecting records with a specific grade or age above a threshold.
  - Explored handling missing data using fillna() to replace NaN values and dropna() to remove them.
  - Explored DataFrame attributes like index, columns, values, shape, and data types for better understanding.
  - Applied functions to DataFrame columns using apply(), demonstrating transformations like multiplying numerical values.

**Day 14:**   Pandas – Descriptive Statistics, Function Applications, and String Methods
  - Learned reindexing to rearrange DataFrame rows and change Series indexes.
  - Iterated through DataFrames using items(), iterrows(), and itertuples() for extracting and processing data efficiently.
  - Sorted data using sort_values() and sort_index(), both for single and multiple columns.   
  - Mastered string operations:
     - Case transformations (lower(), title(), capitalize(), swapcase()).
     - Whitespace handling (strip(), lstrip(), rstrip()).
     - String manipulations (join(), replace(), contains(), startswith(), endswith()).
     - Character counting and indexing (find(), rfind(), count(), len())
   
**Day 15:**   Pandas – Customization, Querying, Window Functions, and Grouping
  - Customized Pandas display settings using set_option() and reset them with reset_option('all').
  - Converted data types with astype(), ensuring proper handling of numerical and categorical data.
  - Filtered data efficiently using the query() method with logical conditions (and, or).
  - Applied rolling window functions (rolling(), expanding()) to compute moving aggregates.
  - Used groupby() to group data and performed aggregations (sum(), mean(), min(), max()).

**Day 16:**   Pandas – Reading & Writing Files (CSV, Excel, JSON)
  - Used read_csv() to load CSV files into a DataFrame.
  - Extracted specific columns and displayed subsets of data using head() and tail().
  - Explored count(), shape, and column selection for basic data insights.
  - Saved a DataFrame as a CSV file using to_csv(), and disabled index writing with index=False.
  - Loaded Excel files with read_excel(), specifying the sheet name to extract data from specific sheets.
  - Saved DataFrames to Excel files with to_excel() and ExcelWriter, ensuring a clean format by disabling index storage.

**Day 17:**   Pandas – Date & Time Handling
  - Used to_datetime() to convert date strings into Pandas datetime objects.
  - Extracted specific date components like year, month, day, and hour.
  - Converted lists and DataFrame columns to datetime format for structured analysis.
  - Handled different date formats using to_datetime(date, format='%Y/%m/%d') and formatted output with strftime().

**Day 18:**    Data Visualization with Matplotlib (Part 1)
  - Used plt.bar() to create bar charts for visualizing categorical data.
  - Created plt.plot() line graphs to analyze trends over time with markers and styles.
  - Explored plt.scatter() for scatter plots to show relationships between numerical variables.
  - Worked with real-world datasets like expense tracking and employee data to create meaningful visualizations.

**Day 19:**    Data Visualization with Matplotlib (Part 2)
  - Used plt.pie() to create pie charts for visualizing proportions and distributions.
  - Applied customization options like explode, autopct, startangle, and custom colors for better readability.
  - Grouped and visualized real-world expense data by payment mode using pie charts.

**Day 20:**    Data Visualization with Matplotlib (Part 3)
  - Used plt.boxplot() to create box plots for analyzing data distribution and detecting outliers.    
  - Explored key box plot components, including quartiles, median, whiskers, and outliers.
  - Used plt.hist() to generate histograms for visualizing frequency distributions.

**Day 21:**    Data Visualization with Matplotlib (Part 4)
  - Used plt.violinplot() to visualize data distributions with density estimation, combining aspects of box plots and KDE.
  - Implemented plt.stem() for stemplots to analyze small datasets and identify patterns.
  - Applied real-world datasets like Titanic passenger ages and meal calorie distributions for meaningful insights.

**Day 22:**    Data Visualization with Matplotlib (Part 5)
  - Used plt.step() to visualize discrete changes over time, ideal for stepwise data trends.
  - Explored where parameter (pre, post, mid) to control step transitions and their real-world applications.
  - Applied plt.step() on an expense dataset to analyze cumulative spending trends across different categories.

**Day 23:**    Data Visualization with Matplotlib (Part 6)
  - Used plt.legend() to enhance readability by distinguishing multiple data series in a single plot.
  - Implemented legends in line plots, pie charts, and real-world datasets for better data interpretation.
  - Analyzed real-world data like stock prices, monthly expenses, and workout trends using legends to compare multiple categories.

**Day 24:**    Data Visualization with Matplotlib (Part 7)
  - Used plt.subplot() to create multiple plots within a single figure for better comparison.
  - Highlighted why subplots are essential by first plotting separate graphs and then using plt.subplot() to organize them efficiently.
  - Implemented multiple examples, including visualizing age vs. weight trends and analyzing real-world datasets like student performance and expense 
    tracking.

**Day 25:**    Data Visualization with Seaborn (Part 1)
  - Used sns.heatmap() to visualize correlations between numerical variables, ensuring proper data formatting for accurate representation.
  - Implemented sns.barplot() and sns.countplot() to analyze categorical data distributions, making comparisons more insightful.

**Day 26:**    Data Visualization with Seaborn (Part 2)
  - Used sns.stripplot() and sns.swarmplot() to visualize individual data points for categorical variables, ensuring better clarity in dense 
    distributions.
  - Implemented sns.lmplot() and sns.residplot() to analyze linear relationships and residual variations, aiding regression analysis.

**Day 27:**    Data Visualization with Seaborn (Part 3)
  - Used sns.lineplot() to visualize trends in time series data, such as stock prices and weather patterns.
  - Explored techniques for handling missing time series data using interpolation and forward-filling methods.
  - Implemented multiple time series comparisons using the hue parameter to differentiate trends across categories.

**Day 28:**    Data Visualization with Seaborn (Part 4)
  - Used sns.relplot() with the kind="line" parameter to visualize multi-category time series data in a flexible way.
  - Implemented rolling averages with .rolling().mean() to smooth trends and highlight long-term patterns.
  - Analyzed seasonal patterns and anomalies in real-world datasets like sales trends and website traffic fluctuations.

**Day 29:**    Data Visualization with Seaborn (Part 5)
  - Used sns.scatterplot() to visualize relationships between bill length and depth in the Penguins dataset, highlighting species differences.
  - Implemented sns.regplot() to analyze the correlation between flipper length and body mass, adding trend lines for better insights.
  - Explored data distributions using sns.boxplot() and sns.violinplot(), comparing body mass across different species.

**Day 30:**    Introduction to Statistics
  - Defined statistics and explored its applications in various fields such as health, psychology, business, and sports.
  - Discussed how statistics can sometimes be misleading due to factors like history effects and third-variable problems.
  - Introduced descriptive statistics, distinguishing it from inferential statistics.

**Day 31:**    Inferential Statistics
  - Explored the concepts of populations and samples, understanding how a subset of data can be used to make inferences about a larger group.
  - Analyzed sampling bias through real-world examples, highlighting how improper sampling methods can lead to misleading conclusions.
  - Learned about simple random sampling, ensuring that every member of a population has an equal chance of being selected.
  - Discussed stratified sampling, a method that ensures proportional representation of different groups within a population for more accurate 
    results.

**Day 32:**    Understanding Variables & Data Collection
  - Explored the fundamentals of independent and dependent variables, understanding how changes in one affect the other in research studies.
  - Learned about discrete and continuous variables, understanding how data can be countable or measured on a scale.
  - Covered the basics of data collection, emphasizing the importance of selecting the right method for accurate and reliable insights.

**Day 33:**    Data Visualization & Measurement
  - Covered the basics of data collection through measurement examples, understanding how different approaches impact data accuracy.
  - Learned how to graph quantitative variables effectively to uncover patterns and insights.
  - Created stem-and-leaf displays, examined their variations, and discussed their advantages in displaying data distributions.
  - Summarized histograms, highlighting their role in visualizing frequency distributions.

**Day 34:**    Mastering Frequency Polygons & Bin Widths
  - Choosing the Right Bin Width –  Striking the right balance is key for meaningful insights! 
  - Frequency Polygons: Summary & Examples
  - Cumulative Frequency Polygons – A powerful tool to track running totals and analyze percentiles, making trends easier to spot!

**Day 35:**    Box Plots & Bar Charts – Visualizing Data Effectively 
  - Box Plots – A great way to summarize data distribution, highlight medians, quartiles, and detect outliers. Perfect for comparing datasets!
  - Bar Charts: Summary & Uses – Best for categorical data, trends, and comparing means across groups. (e.g., Comparing sales across different regions)
  - Why Use Bar Charts for Categories, Trends & Means? – They provide clear comparisons, making it easy to spot differences across groups.

**Day 36:**    Reinforcing Concepts Through Practice
  - Frequency Histogram vs. Relative Frequency Histogram
    - Frequency histograms show raw counts 
    - Relative frequency histograms display proportions or percentages, making comparisons easier across different sample sizes 
  - Stem-and-Leaf Diagrams – A simple yet effective way to organize numerical data while preserving individual values. Great for quick insights!
  - Percentiles & Real-World Applications

**Day 37:**    Mastering Measures of Central Tendency
  - Mean, Median & Mode – The Three Pillars of Central Tendency
  - Mean vs. Median – When to Use What?
  - When Are Mean & Median the Same?


**Day 38:**    Understanding Variability in Statistics
  - What is Variability?
  - Range – The Simplest Measure
  - Interquartile Range (IQR) – Better than Range?
  - Variance – The Foundation of Spread!
  - Standard Deviation – Making Variance Meaningful

**Day 39:**    Percentiles & Pearson Correlation Coefficient
  - What is a Percentile?
  - How to Calculate Percentiles
  - Pearson Correlation Coefficient (r) and it's key properties

**Day 40:**    Computing Pearson’s Correlation & Introduction to Probability
  - What is a Percentile?
  - Introduction to Probability - Classical Approach, Empirical Approach, Subjective Approach
  - Basic Probability Concepts
  - Probability of Independent Events

**Day 41:**    Conditional Probability, The Birthday Paradox & More!
  - Conditional Probability & Dependent Events
  - The Gambler’s Fallacy
  - Sample Space & Events
  - Three-Child Family (Tree Diagram Representation)

**Day 42:**    Exploring Key Probability Rules & Concepts
  - Probability of Complements
  - Intersection & Mutually Exclusive Events
  - Union of Events & The Additive Rule of Probability
  - Conditional Probability &  Independent Events

**Day 43:**    Probability, Counting & Random Variables!
  - Tree Diagrams for Probability
  - Permutation vs. Combination 🔢
    - Permutation (Order Matters!)
    - Combination (Order Doesn't Matter!)
  - Random Variables & Their Types 🎲
  - Probability Distribution of Discrete Random Variables
