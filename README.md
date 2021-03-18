Job-Postings
Business Case
This Organization is a contracting firm that is rapidly expanding and needs to leverage data to win more contracts. It offers technology and scientific solutions and wants to be competitive in the hiring market.

!["indeed"](https://github.com/noelialopez/Job-Postings/blob/master/Indeed.jpg)


My Goals are: Scraping data from a Indeed.com job aggregation tool in order to collect the data to best answer these two questions. Determining the industry factors that are most important in predicting the salary amounts for these data. Determining the factors that distinguish job categories and titles from each other.

To limit the scope, I will be focus on data-related job postings, e.g. data scientist, data analyst, research scientist, business intelligence, and others.

Step 1: Factors that impact salary To predict salary I will be building a classification model, using features like the location, title, and summary of the job. I will be framing this as a regression problem creating labels from these salaries as high vs. low salary according to median salary as a threshold.

Step 2: Factors that distinguish job category Using the job postings you scraped for part 1, I will identify features in the data related to job postings that can distinguish job titles from each other.
