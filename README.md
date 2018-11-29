# Introduction
For this project, I will be working to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. 

The test was run for 22 days in January of 2017 and collected about 300,000 records.  Users were segmented into eiher a control group that viewed the current page (old_page), or a treatment group that viewed the test page (new_page).  Data wrangling for this analysis included dropping duplicate user IDs and records that could not be trusted (e.g., control group user that viwed test page).  







The Jupyter notebook in this repository looks at the collected data using the following three approaches:

1. Simple Conversion Rate Calulations for all users, the treatment group, and the control group,
2. Calculating the p value for a type 1 error rate where null hypothesis is that the old and new converstion rates are equal, and 
3. Using Logistic Regression.

# Conclusion
1. Given that the test duration was close to a month with almost 300,000 records I would not recommend running this test for a longer duration.
2. Based on the analysis in this notebook I would recommend against the implementation of the new page. Three approaches  where used to review the conversion rate data for the old and new pages and none of the approaches provided statistically significant evidence that the new page performs better than the old page.
