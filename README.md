# salary_prediction
Data was scrapped from seek.com by keywords (data analyst, data engineer, data scientist, data architect) in Australia, which returned 13965 jobs. After dropping irrelevant jobs and duplicates, 5130 observations were kept for machine learning.

Target variable is salary range, which has been classified as low(80k and under), mid(80k - 120k) and high(120k and above) with reletively balanced distribution. The hypothsis was that location, industry, employment type would impact on salary band. 65% accuracy was returned from LogisticRegression model taking these features into account, whereas 62% accuracy when learning from job description only.

The findings are below:

Contract/temporary employment is more likely to offer high salary, whereas full-time employment is more popular for mid and low salary range.
With high salary band, employers are looking for senior business and architect experience. In low salary band, employees are expected to be junior, graduate and supportive role.
Location-wise, ACT, Melbourne and Sydney offer the most high salary data related jobs. On the other hand, Brisbane and Adelaide offer low salary jobs.
Industry-wise, employers labelled as Information and Communication Technology tend to offer high salary for data-related jobs. By that, it means that employers in other industries are more likely to offer lower salary.
