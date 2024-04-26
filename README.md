# pandas-challenge

Written Report:

1. Report Summary:
    This analysis shows how various factors impact school performance:
        a. First, we created a high-level snapshot of the district's key metrics which included total schools, students, budget, scores, and passing percentages, to understand the general education performance of the dsitrict.
        b. Then, we went a bit narrower by detailing the key metrics by school which included similar metrics that we captured with the district summary along with school type, allowing the comparison of schools directly.
        c. Then, we observed the score trends for math and reading within individual schools.
        d. Then, schools were categorized based on their spending per student.  This enables us to identify correlations between school spending and student performance.
        e. Then, we looked at the size of the schools to identify how the size of the school impacts student performance.
        f. Lastly, we compared student performance by school type to observe any correlations.
    2. Two Conclusions from the Analysis:
        a. Charter schools have significantly higher average passing rates for math and reading, and a significantly higher overall passing rate as opposed to District schools.  This may suggest that students in smaller more managable environments are more likely to perform better.
        b. Looking at performance by shool size, we see that performance is relativey stable between schools that have less than 1,000 students and schools that have 1,000 - 2,000 students.  However, schools with more than 2,000 students, see a significant decrease in performannce (passing rates).  This confirms the hypothesis that, smaller environments are likely to produce more successful passing rates.
        
Sources and Citation:
    - Use of "nunique ()" to return total counts: https://www.w3schools.com/python/pandas/ref_df_nunique.asp#:~:text=By%20specifying%20the%20column%20axis,unique%20values%20for%20each%20row.
    - Use of "groupby ()" to aggregate columns: https://www.geeksforgeeks.org/python-pandas-dataframe-groupby/
    - Use of "sort_values ()" function to display top 5 rows an place in ascending or descending order: https://www.geeksforgeeks.org/python-pandas-dataframe-sort_values-set-1/
    - Use of "to_numeric" to convert non-numeric values: https://www.geeksforgeeks.org/python-pandas-to_numeric-method/
        
    
