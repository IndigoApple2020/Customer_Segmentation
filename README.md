# Customer_Segmentation

In this code I used unsupervised clustering to identify customer segments from retail data.

Firstly I loaded, cleaned and added some new useful features to the data. I checked for redundant features by correlating the feature values (ignoring categorical features).

Secondly I converted all features to numerical and scaled using a standard scaler - this ensures each feature is weighted equally. 

Next I used Principal Component Analysis to generate 3 'artificial' features which allow for a good spread/variation in the data. I applied clustering on this plot to identify the 4 most distinct groupings within the data.

Finally, I plotted the original features (colour coded for the clustering number) to characterise what defined each grouping. This profiling (e.g. Younger, No Kids, High Income) will help for understanding the demographics of our most valuable customers and targeting campaigns.

# Credits 

Unsupervised clustering of data to identify customer segments.
Code inspiration - kaggle datasets Customer Segmentation: Clustering [Karnika Kapoor]

This approach could be used to segment customers in a new way unbiased by prior groupings.
