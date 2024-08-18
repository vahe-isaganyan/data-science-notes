## Data Vs. Information

Information is derived knowledge. You can derive knowledge from many activities: measuring a process, thinking about something new, looking at art, and debating a subject. Information is continually created, but communicating and capturing that information is not always simple. Some things are easily measurable while others are not. We try to communicate knowledge for the benefit of others and to store what is already learned. One way to communicate and store information is to encode it. When we do this, we create data. Data is essentially encoded information.

## Example Dataset

| Date       | Ad Spending | Units Sold | Profit | Location   |
|------------|-------------|------------|--------|------------|
| 2021-01-01 | 2000        | 100        | 10452  | Print      |
| 2021-02-01 | 1000        | 150        | 15349  | Online     |
| 2021-03-01 | 3000        | 200        | 25095  | Television |
| 2021-04-01 | 1000        | 175        | 12443  | Online     |

A table like the one above is called a dataset. It has rows and columns that serve specific functions in how we understand the table. Each row of the table is a measured instance of associated information. Each column of the table is a list of information we're interested in, organized into a common encoding so that we can compare each instance.

Rows are commonly known as observations, records, tuples, or trials. Columns of datasets often go by the names features, fields, attributes, predictors, or variables.

A data point is the intersection of an observation and a feature. For example, 150 units sold on 2021-02-01 is a data point.

Some datasets have a header row that helps us understand what each feature means.

## Data Types

There are many ways to encode information, but data workers use a few specific types of encodings that store information and communicate results. The two most common data types are described as numeric or categorical.

- **Numeric data** is mostly made up of numbers but might use additional symbols to identify units.
- **Categorical data** is made up of words, symbols, phrases, and sometimes numbers such as zip codes. Numerical and categorical data both split into different subcategories.

### The Main Types of Numeric Data

- **Continuous data:** Represents measurements and can assume any numeric value within a certain range. This type of data can be split into smaller parts and consequently have valid fractional and decimal values. Continuous data can have an infinite number of potential values between any two points. For example:
  - A local news station might measure a temperature of 65.62 Fahrenheit. However, they may choose to report this number to the viewer as 65 degrees, 66 degrees, or 65.6.

- **Count (discrete) data:** Restricts the precision of the data to a whole number. For example:
  - The number of cars you own can be 0, 1, 2, or more, but not 1.23.

### The Main Types of Categorical Data

- **Ordered (ordinal) data:** Categorical data with an inherent order. For example:
  - Surveys take advantage of ordinal data when they ask you to rate your experience from 1 to 10. While this may look like count data, it's not possible to say the difference between survey ratings 10 and 9 is the same as the difference between 1 and 0. Ordinal categorical data is not limited to numbers; shirt size can be ordinal as well.

- **Unordered (nominal) data:** Categorical data without an underlying order. For example:
  - In the table used for the example dataset, there is a location feature with values of print, online, and television. Other nominal variables include yes or no responses or political party affiliation. The order represented is always arbitrary. It is not possible to say one category is greater than another.
```
