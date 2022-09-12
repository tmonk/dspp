## Course overview

Instructor: [Thomas Monk](https://personal.lse.ac.uk/monkt/) (t.d.<span style="display:none">spam</span>monk@lse.ac.uk)
 
This short course will introduce students to the Python programming language as a tool for applied data science. In PP455 we utilised Stata, the primary environment used by economists and public policy academics for regression analysis. Python is a more general-purpose tool from which we can perform a range of tasks, from data cleaning, transformation, and visualisation to more advanced techniques on the social science research frontier, such as natural language processing and machine learning.

The two-week course will take students from the first principles of Python programming to the application of data science packages such as NumPy and Pandas. Each class will be practical and hands-on, with the course focusing on the application of these tools in the public policy space.
 
### Prerequisites 
A pass mark in PP455, or equivalent.

### Schedule 
We meet daily 11:00-13:00 in NAB 2.09, with an additional class scheduled on Tuesday, 30 August 2022 from 14:00-16:00.


## Syllabus
This course is designed as an intensive two-week introduction to programming and data science for public policy students. The content covered will include:

- Programming in a setting of public policy - why should we care?
- Thinking algorithmically, taking policy questions to the data via a general-purpose programming language.
- Fundamentals of programming: code syntax, libraries, variables, data types, program control, functions, and IO.
- Data science through open-source python libraries. Cleaning, obtaining and analysing structured data.
- Introducing more advanced applications, such as natural language processing and machine learning.

## Lecture Slides & Problem Sets
- [Class 1](https://raw.githubusercontent.com/tmonk/dspp/main/Class%201/DSPP___Class_1-3.pdf) - introduction to data science from the perspective of public policy
- [Class 2](https://github.com/tmonk/dspp/tree/main/Class%202) - variables, functions and conditionals
- [Class 3](https://github.com/tmonk/dspp/tree/main/Class%203) - lists and strings.
- [Class 4](https://github.com/tmonk/dspp/tree/main/Class%204) - loops and other flow controls.
- [Class 5](https://github.com/tmonk/dspp/tree/main/Class%205) - data assignment.
- [Class 6](https://github.com/tmonk/dspp/tree/main/Class%206) - introduction to NumPy and Pandas.
- [Class 7](https://github.com/tmonk/dspp/tree/main/Class%207) - more advanced Pandas, merging.
- [Class 8](https://github.com/tmonk/dspp/tree/main/Class%208) - text as data, sentiment analysis.
- [Class 9](https://github.com/tmonk/dspp/tree/main/Class%209%20%26%2010) - introduction to machine learning concepts, relation to causal inference with linear models.
- [Class 10](https://github.com/tmonk/dspp/tree/main/Class%209%20%26%2010) - machine learning with non-linear models.

<!-- IPUMS USA census data 	https://usa.ipums.org/usa/ -->
## Course Outline

| Date                        | Class         | Content I                                       | Content II                                           | Application                           |
| --------------------------- | ------------- | ----------------------------------------------- | ---------------------------------------------------- | ------------------------------------- |
| Tuesday, 30 August 2022     | Class 1 - AM  | Intro to Programming                            | Python basics                                        | Setting up the Python environment     |
| Tuesday, 30 August 2022     | Class 2 - PM  | Python basics                                   | Functions & conditionals                             | Working with notebooks                |
| Wednesday, 31 August 2022   | Class 3       | Lists, strings and dictionaries                 | Loops and list comprehensions                        |                                       |
| Thursday, 1 September 2022  | Class 4       | Recap: lists, strings and dictionaries          | Loops                                                | Nested loops: in the casino           |
| Friday, 2 September 2022    | Class 5       | Data assignment                                 | Data assignment                                      | Chicago city employee data            |
| Tuesday, 6 September 2022   | Class 6       | NumPy                                           | Introduction to Pandas                               | Wine ratings & crime data             |
| Wednesday, 7 September 2022 | Class 7       | More advanced Pandas                            | Merging with Pandas                                  | Chicago city employee data            |
| Thursday, 8 September 2022  | Class 8       | Text as Data                                    | Sentiment analysis                                   | Twitter as data                       |
| Friday, 9 September 2022    | Class 9 - AM  | Introduction to machine learning - linear model | Applied machine learning task                        | House price data                      |
| Friday, 9 September 2022 PM | Class 10 - PM | Machine learning: non-linear models             | Applied machine learning: Random Forests and XGBoost | House price data: better predictions? |


## Resource list

### Programming, Numpy and Pandas
- There is not an assigned textbook for this course, but [Automate the Boring Stuff in Python](https://automatetheboringstuff.com/) is a well written, free resource. It will cover everything we discuss in class, at least the Python side, and allow you to dive as deep as you wish into the language. 
- I'm grateful to Eric Potash for his [30550 course](https://harris-ippp.github.io/) at the University of Chicago, which provided a useful basis for the material presented in this course, and some of the assigned Problem Sets.
  - We didn't have time to cover the Split-Apply-Combine paradigm. This is covered well in the [official Pandas documentation](https://pandas.pydata.org/docs/user_guide/groupby.html), and Problem Set 7b is available for you to practice this.
- For more fundamental programming instruction, Google's Kaggle [Python](https://www.kaggle.com/learn/python) and [Pandas](https://www.kaggle.com/learn/pandas) courses are excellent, as are the rest of their learning materials.

### Text as Data
- Chris Bail (Duke) provides an excellent course in [Data Scraping and Text Analysis](https://cbail.github.io/ids704/Home.html).
  - His undergraduate level course [Data Science and Society](https://dssoc.github.io/schedule/) provides a useful accompaniment, and his graduate level [Computational Social Science](https://cbail.github.io/comp_soc_grad/Home.html) extends the topics we have discussed.
- The courses above use R, I also recommend the R oriented [Text Mining with R](https://www.tidytextmining.com/) as a useful reference resource . Now we have worked to understand Python and programming as an abstract concept, it will be simple for you to transition to R if you wish.

### Machine Learning
- [An Introduction to Statistical Learning](https://www.statlearning.com/) (2021, James et al.) is the basis of the material I presented.
- LSE's [ME314](https://lse-me314.github.io/), Introduction to Data Science and Machine Learning, uses this book as a basis, and is an excellent adaption and extension. The course as a whole goes further than we were able to, and is clearly presented with many useful assignments.
- The mathematics and statistics used may be a barrier to understanding the material.
  - If you're interested in developing these skills Sydsaeter et al's (2008) [Essential & Further Mathematics for Economic Analysis](https://www.pearson.com/en-gb/subject-catalog/p/further-mathematics-for-economic-analysis/P200000005529/9780273713289) and Miller & Miller's (2021) [John E. Freund's Mathematical Statistics with Applications](https://www.pearson.com/en-us/subject-catalog/p/john-e-freund-s-mathematical-statistics-with-applications/P200000006294/9780137547432) are my preferred resources for mathematics and statistics respectively. 
  - As an aside, to link this topic more formally to the econometrics we've covered in PP455, Bruce Hansen's (2022) [Econometrics](https://www.ssc.wisc.edu/~bhansen/econometrics/) is a well written, rigorous presentation of the material.
