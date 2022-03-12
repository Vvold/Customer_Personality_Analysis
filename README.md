# Customer Personality Analysis
____

Customer Personality Analysis is a detailed analysis of a company’s
ideal customers. It helps a business to better understand its 
customers and makes it easier for them to modify products according
to the specific needs, behaviors and concerns of different types 
of customers.

#### Project Tasks:
Clustering is performed to generalize customer segments.

### Data
Data for this project were taken from **kaggle**:  
https://www.kaggle.com/imakash3011/customer-personality-analysis

To perform the task was used clustering by the method of [k-means](https://en.wikipedia.org/wiki/K-means_clustering)

The features that will have the greatest impact on categorization have been selected:
* `Days_Enrolled` - how long a customer is in the company
* `Spend_all` - how much the client spent
* `NumAllPurchases` - how many purchases the customer made
* `AvergeCheck` - averge customer check

### Preprocessing
After preparing the data for clustering, quantitative data was scaled using `StandardScaler()`
```
from sklearn.preprocessing import StandardScaler
```

## Clustering
There was implemented `K-means` method from `sklearn.cluster`

Using [The Elbow Method](https://en.wikipedia.org/wiki/Elbow_method_(clustering))  it was decided to divide customers into **4** clusters

![num of cluster](https://github.com/Vvold/Customer_Personality_Analysis/blob/master/num_of_cluster.png)

## Contacts

---
### Vitkovskiy Volodymyr
- email: VitkovskyiVB@gmail.com
- telegram: @wvld_11
- github: [Vvold](https://github.com/Vvold)
