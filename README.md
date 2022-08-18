# matplotlib-challenge
UCI Bootcamp: Matplotlib Challenge

A study on mice was done to test the effectiveness of Pymaceutical's new squamous cell carcinoma (SCC) treatment called Capomulin among ten other treatments. Data was collected over 45 days where they measured the tumor volume per mouse. The following data variables were recorded:

- Mouse ID
- Drug Regimen: Capomulin, Ceftamin, Infubinol, Ketapril, Naftisol, Placebo, Propriva, Ramicane, Stelasyn, and Zoniferol
- Sex
- Age (months)
- Weight (g)
- Timepoint (days): 45 days total
- Tumor Volume (mm3)
- Metastatic Sites

Python libraries such as Pandas and Numpy were used to develop data summary tables and aggregations to find the average tumor volume per treatment. Developed statistical summaries such as the mean, median, variance, standard deviation, and standard error measurement for the tumor size per treatment using Scipy.stats. In addition, calculated the IQR and find any outliers per treatment. Created data visualizations with Matplotlib. Developed boxplots to display the distribution of the average tumor volume among each treatment. Built a line plot to visualize the progression of the Capomulin treatment on one mouse. Used scatterplots to visualize the correlation between mouse weight and tumor size. Built a linear regression model to predict the average tumor volume size based on the weight of each mouse. 

Data Insights:
Discovered that the new treatment Capomulin performs well compared to the majority of the other treatments. It's results were fairly close to Ramicane with the mean tumor size differing by approximately 0.5 mm3. In addition, the standard error of mean was lower than the other treatments by approximately 25-50%. Therefore, the sample mean calculated for the tumor volume for Capomulin is more accurate compared to other treatments excluding Ramicane who's results were slightly better. The standard deviation and variance for Capomulin was lower compared to other treatments excluding Ramicane. Thus, Capomulin effects were more consistent among the mouse being treated. 