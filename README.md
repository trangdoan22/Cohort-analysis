# Python-Cohort-analysis

**What is cohort and cohort analysis?**

A cohort is a collection of users who have something in common. A traditional cohort, for example, divides people by the week or month of which they were first acquired. When referring to non-time-dependent groupings, the term segment is often used instead of the cohort.
Cohort analysis is a tool to measure user engagement over time. It helps to know whether user engagement is actually getting better over time or is only appearing to improve because of growth. Customers are divided into mutually exclusive cohorts, which are then tracked over time. Vanity indicators don’t offer the same level of perspective as cohort research.

Generally, there are three major types of Cohort:

●	Time cohorts: customers who signed up for a product or service during a particular time frame.

●	Behavior cohorts: customers who purchased a product or subscribed to service in the past.

●	Size cohorts: refer to the various sizes of customers who purchase the company’s products or services.

However, we will focus on performing Cohort Analysis based on Time. Customers will be divided into acquisition cohorts depending on the month of their first purchase. The cohort index would then be assigned to each of the customer’s purchases, which will represent the number of months since the first transaction.

From Python, I will use KPMG transaction data to make a cohort to evaluate user engagement from their first transaction 

**COHORT MAP**

![image](https://github.com/trangdoan22/Python-Cohort-analysis/assets/140712745/9f35b1d6-62b2-4091-95c6-8da070788de8)

**INSIGHTS**

- KPMG's month-over-month retention rate is good (greater than or equal to 30% except 25.5% in Aug 2017)
- Customers visiting firstly in July 2017 have the highest retention rate in 2017 (up to 48.1%) after 5 months of engagement.
- Customers visiting firstly in mid-year (from Apr-2017 to Aug-2017) tend to have stable and higher retention rate compared to the rest months of the year

In details:

- Retention rate in Apr-2017: 45.1% (4-month engagement), 42.1% (5-month) and 42.7% (7-month)
- Retention rate in May-2017: 40.4%, 39%, and 41.3% in the 2-month, 3-month and 4-month engagements
