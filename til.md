### Today I learned...

- 09-20-21: Today I learned how to use MySQL clauses WHERE, ORDER BY, LIMIT, and OFFSET.

- 09-21-21: Today I learned that I can return things that start and end with a specification by using "..%.." eg. "E%e" will return strings that start and end with "e". Use option and click to add multiple cursors in VS Code. 
Knowing when to refine your while using GROUP BY by WHERE and HAVING clauses can be confusing. If your specifications are dependent on the GROUP BY being there, it must be coded after the GROUPY BY using the HAVING clause. If you're refining your SELECT before being grouped, it can be coded in the WHERE clause.

eg. Last names that start and end with an 'e' would be included in the WHERE clause, while querying the number of unique last names where the count is greater than a number would be included in the HAVING clause.

- 09-22-21: Today I learned that when a question may be subjected to interpretation to leave a note on my personal judgement calls. If that judgement call is above my head or pay grade, ask questions. Alternate viewpoints on code may reveal these scenarios.

- 09-23-21: Today I learned how powerful aliases can be. When joining tables and there's a lot of information being passed around, lengthy names can create clutter and confusion when analyzing code. Using aliases on tables reduces the clutter and confusion. I also learned about self joins.

- 09-27-21: Today I learned about subqueries and how quickly they can become complicated. I also learned how to create temporary tables using queries and how to add and remove things from them, along with how critical it is to make sure you're working from a personal database so you don't ruin the main database.

- 09-28-21: Today I learned about case statements and how they can be used to create pivot tables.

- 09-29-21: Today I learned that the solution I come up with might not always be the most efficient or simple and to always pay attention to your table for undesired duplicates.

- 09-30-21: Today I learned how complicated environment setup could potentially become. A simple misinterpretation of where something is installing can interrupt the entire process. Being able to identify where homebrew is installing may enable a more streamlined effort in future environment setups. I also learned broadly about how powerful jupyter notebook is and what can be done with it.

- 10-01-21: Today I learned that converting for loops into list comprehensions is both complicated and simple. I also learned that googling the answer sometimes makes things a lot more difficult than working through a solution on your own.

- 10-04-21: Today I was able to practice with dictionaries a little more and I learned that the more you use them, the less intimidating they become.

- 10-05-21: Today I learned of a better method to break while loops than using a user choice variable, setting while True, then breaking if the user decides not to continue.

- 10-06-21: Today I learned that an argument being passed through a function will not be modified by methods in loops or if statements. I also learned about .isnumeric() and .isalpha() checking if something is a number or in the alphabet. .isalnum() checks if it is alphanumeric. I learned of unicode on characters and how it can be used in basic calculations. I feel my overall understanding of for loops has improved immensely sinced my first day using them in python.

- 10-07-21: Today I learned about importing modules/packages/libraries in python. I learned how to call on my own functions by importing them. I also learned how to use itertools and importing a json.

- 10-08-21: Today I learned about matplotlib. It was a lot of information and I'm going to have to process it over the weekend. The anatomy of a plot is a figure with axes, wich contain the actual graphs, with their own x and y axis, titles, etc. What I did not expect was to be able to change the style that the plots output and how it can be modified.

- 10-12-21: Today I learned about numpy and how much easier it makes a lot of problems. Majority of the exercises we've done could be completed a lot quicker with numpy.

- 10-13-21: Today I learned several different ways you can manipulate arrays with numpy, such as reshaping, flattening, dotproduct. I also learned you can fill an array with 0s or 1s with np.zeroes and zp.ones

- 10-14-21: Today I learned about series in pandas and the methods available to use with them.

- 10-15-21: Today I learned that dataframes are built of multiple series and many of the functions and methods that apply to series can be used on dataframes.

- 10-18-21: Today I learned how to connect to a SQL database and run a query through pandas and how to import the results into a pandas dataframe.

- 10-19-21: Today I learned about aggregating, merging, and reshaping dataframes. Using crosstab with separate dataframes can give complicated results if things, such as indeces, don't match up properly. .map() can be used to assign values to a dataframe with values from a dictionary without using if's and numerous elif's.

- 10-20-21: Today I learned about seaborn and the various plots it provides.

- 10-21-21: Today I learned how to clone someone else's repository and push the work I do to my own repository, following these steps.
Clone the other repo
Git remote remove origin
Then make a brand new blank repo on your own account
Then copy the git remote add origin git@github.com:my-git-hub/my-repository.git
1) do work, 2) add, 3) commit, and push

- End of November: I learned about tableau and how to use it

- 11-01-21: Today I learned about basic statistics operations in numpy 
- 11-02-21: Today I learned about probability distributions and how python can be used to calculate statistical distributions. I also learned more about using python and pandas to solve simulations
- 11-04-21: Today I learned about hypothesis testing, what a null hypothesis and alternate hypothesis are and how to decide which hypothesis is correct using t-tests.

- 11-05-21: Today I learned how to test and visualize correlations using python
- 11-08-21: Today I learned about chi**2 and how to apply it to find correlations between two categorical variables

- 11-09-21: Today I learned an overview of classification in machine learning and reinforced data acquisition skills.

- 11-10-21: Today I learned about preparing data for classification. This involved cleaning data, splitting data, and imputing data.

- 11-12-21: Today I learned about exploring data, and a step-by-step process to use as a guide in the exploration.

- 11-15-21: Today I learned how easy it is to get lost in exploring data and how dense of a task it can be. I also learned about tidy data, melting and pivoting tables to tidy it up prior to cleaning.

- 11-16-2021: Today I learned how confusing a confusion matrix can be and how important deciding how to define your positive and negative is. I still don't understand how to best define this and require further practice. I also learned about classification metrics and how to choose which is most important.

- 11-17-2021: Today I learned about decision tree modeling and practiced utilizing the confusion matrix and using sklearn.metrics to measure classification metrics easier than doing it manually.

- 11-18-2021: Today I learned about random forest modeling and how depth weighs heavily on overfitting models.

- 11-19-2021: Today I learned about KNN and linear regression models and that while developing models, using a random state ensures consistency while developing models for production teams.

- 11-22-2021: Today I learned about starting an end-to-end data science project with machine learning and how starting one is a fairly rough process for the inexperienced.

- 11-23-2021: Today I learned how to apply stats module to an end-to-end data science project and how keeping the work process clearly defined can help with workflow and staying on task.

- 11-29-2021: Today I learned the variety of solutions you can find in a machine learning project. Even working with similar datasets, there was a variety of solutions. I also learned I should make sure that my final report for projects reflects current information all the way through, especially in the conclusion.

- 11-30-2021: Today I learned the acquire and prepare portions of regression projects have different steps than classification projects. I also learned of a general overview of what regression is and how it is used.

- 12-01-2021: Today I learned of various topics from the senior Cohort's capstone projects. It was interesting to see how domain knowledge isn't necessary in completing a project, but being flexible and willing to learn can lead to success. I also learned that removing outliers can potentially handle nulls as well, but to be aware of what steps to take if it does not handle all nulls.

- 12-02-2021: Today I learned about scaling data. Though I felt I had a sense of scaling things from previous experiences with AutoCAD, that experience is with drafting. I learned scaling data has many different methods, all with mathematical definitions to each.

- 12-03-2021: I learned that processing millions of data points can take a long time and this is a good opportunity to use .sample() to reduce the time it takes to run a cell.

- 12-06-2021: Today I learned of Regression Evaluation techniques and about regression errors.

- 12-07-2021: Today I learned about feature engineering, adding onto basic knowledge and ideas of what feature engineering is. I also learned of kbest and RFE to choose best features.

- 12-08-2021: Today I learned about the many regression models and how to use them.

- 12-09-2021: Today I practiced how to apply what I've learned to a project, in this case a zillow project. I also revisited scaling and was reminded that you always scale data in models that incorproate a distance metric. Regression is one of them.

- 12-10-2021: Today I continued applying what I learned of regression modeling to a project.

- 12-14-2021: Today I learned about general clustering concepts.

- 12-16-2021: Today I learned about exploring data in preparation for cluster modeling.

- 01-03-2022: After a long break, today I learned about modeling clusters on data and how scaling data affects the clusters.

- 01-04-2022: Today I learned how to use clusters and performing additional exploration with clusters, using them as engineered features. I also learned about dimensionality reduction.

- 01-05-2022: Today I began creating clusters in a project setting

- 01-06-2022: Today I learned I need to add clusters to my validate and test datasets as I add clusters to my training data to prevent having to correct more errors.