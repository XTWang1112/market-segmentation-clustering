# market-segmentation-clustering

##Factors
Satisfaction: self-reported, discrete, range from 1 to 10
Loyalty: -number of purchase for 1 year + other factors
         -There is no widely accepted technique to measure it but there are proxies like churn rate, retention rate, or customer lifetime value(CLV), but here I use 
          the formula above as a measurement of Loyalty
         -continuous, range(-2.5 to 2.5)
         
##Standardization
In this exercise, I need to standardize Satisfaction, becuase when I cluster data without it, it ignore the factore Loyalty and group data by high and low Satisfaction.

##Elbow method is used to decide number of clusters I should have. I can try 2, 3, 4, 5

##Result
After tring different numbers of clusters, I found 4 clusters is optimal. I named purple group as 'Alienated' as they have low satisfaction and low loyalty, red group as supporters as they have low satisfaction but how loyalty, greenish blue group as Fans as they have high satisfaction and high loyalty and the rest (yellow group) as Roamers, high satisfaction but low loyalty.
