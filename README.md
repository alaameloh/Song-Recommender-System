# Songs-Recommender
Recommendation System written in Python, using the pySpark framework and other Data Science libraries

## Project overview
### Purpose
The goal of this project is to build a recommender system able to suggest song artists to users. Given the artists and the user behaviours datasets, the first step is to analyze them and clean the data (for example: several artist names could refer to the same person or band).

Then, the model is built. The idea is to find "similar" users, so that the system can suggest new artists according to these similarities. In other words: if user "A" likes artist "X", a similar user "B" could like "X" too.


## Technical details
### Apache Spark
The adopted framework is Spark: in particular, we have used the Spark-SQL and Spark-MLLib modules to access several specific functionalities.

### Data Science Python libraries
- Pandas and Numpy: data processing and analysis
- Matplotlib and Seaborn: data visualization

### The mathematical model
According to the collaborative-filtering approach, the adopted training technique is ALS (Alternating Least Squares)
