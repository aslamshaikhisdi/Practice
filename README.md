# Practice

## We will be uploading data set to the SQL and analysing it for the results we are looking for.

### lets bgin with uploading the data set to the SQL and cleanign the data for the analysis. 

Select s.SPID, sum(amount) as 'Total', Product
From Sales as s
Join Products as p on s.PID=p.PID
Group by Product Limit 10;

| Rank | THING-TO-RANK |
|-----:|---------------|
|     1|               |
|     2|               |
|     3|               |
