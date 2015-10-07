# Citibike

###Process

We are testing whether Citibike riders ride slower on the weekends than on the weekdays, assuming that riders are more likely to take “leisure” rides on the weekends and use Citibikes for commuting and other necessary trips on the weekdays.

Our null hypothesis the average weekday Citibike trip is of the same or slower speed than the average weekend trip.

Our testable hypothesis is that the average weekend Citibike trip is slower than the average weekday trip.

We chose September, 2014 data as our sample. This sample included approximately 954,000 records. Our data wrangling is described in the comments of our python notebook.

We measured at a confidence level of p = 0.05. We tested our hypothesis with a one-tailed, greater-than t-test. We found that there is a statistically significant difference in speed between weekday and weekend rides, allowing us to reject our null hypothesis. 

While our result was statistically significant, the effect is small (less than one mph difference between weekday and weekend ride mean speeds).

###Our contributions

We started working together to develop and refine our concept and hypothesis. We each worked on our own to attempt to clean and parse data, and then combined our efforts to develop the best final code to perform the analysis. 

Carlyle and Michael focused on distance calculations, while Linda and Rachel worked on verifying and testing statistical processes and project documentation.

###Instructions to run notebook

No additional installations are needed to run our notebook. Packages are all common python packages and are imported in our notebook.