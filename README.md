# Telco Customer Data
 briefly covers your process, methodology and findings.

    Take the time to make sure that you craft your story well, and clearly explain your process and findings in a way that shows both your technical expertise and your ability to communicate your results!
    Begin with framing questions, describe your data source, include relevant, well labeled visualizations that support your conclusions, which come at the end.
    
## Data
wher it came from
### Source
explaination of columns
distrobutions
    
## Process

After getting the data, we took the time to explore the features. In the EDA notebook, we identified column data types to be sure that they were consistient. The TotalCharges column had to be made numeric. Additionally, the SeniorCitizen column was not consistient with the rest of the columns. The zeros and ones were mapped to 'No' and 'Yes'. Next, we checked for null values and found that the TotalCharges column had eleven missing values. I think that these are just customers who haven't been charged yet so those were filled with zeros. Next, we tried engineering some features, among which were the division of monthly charges and total charges and if customers are single parents or not.

Next, I preprocessed the data by identifying column types and making lists of each column name. Then, I could apply encoding, scaling, or imputing as appropriate. Finally, we plotted each variable against churn and not churn.

![Example of a plot showing contract type by churn](images/contract_type.png)

eda
impute, scale, encode
choosing a scoring metric
modeling process
scoring

## Findings
final model 
visuals of all models
why chosen
interpretability
feature import
precision quantiles
some graphs
recommendations
