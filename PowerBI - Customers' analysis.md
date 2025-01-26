# Power BI - Customers' analysis

To view and interact with the dashboards, download the file [here](https://github.com/Marco10292/Customer-segmentation-for-targeted-marketing-campaigns/blob/main/PBI%20Clustering%20Project.pbix)
To visualize variables' specifications, look at the full analysis [here](https://github.com/Marco10292/Customer-segmentation-for-targeted-marketing-campaigns/blob/main/Customer_segmentation_for_targeted_marketing_campaigns.ipynb)

In this Dashboard, **Customer Segmentation and Behavior** we get different valuable insights.

Cluster distribution is as follows:

Cluster 0: *14.67%*

Cluster 1: *28.12%*

Cluster 2: *19.21%*

Cluster 3: *38%*

We can see different average, median and max balance values for each cluster and also how ONEOFF_PURCHASES_FREQUENCY, INSTALLMENTS_PURCHASES, BALANCE and MINIMUM_PAYMENTS are distributed for each cluster.

The bars are displayed in logarithmic scale for clarity purposes.

Using **Key influencers** graph, we determine that PURCHASES and PURCHASES_FREQUENCY are the variables that influence the most the different clusters.

The **Matrix graph** is showing, according to tenure (how many years customers have had an account in the bank), who maintains an higher PURCHASES_FREQUENCY, with 0 and 1 substantially ahead.
 
![Screenshot 2025-01-26 154410](https://github.com/user-attachments/assets/ac8a0d95-b08b-478c-9c8c-b084ffa1b375)

The second Dashboard, **Customer Risk & Financial Health**, is primarily focused on locating possible risk behaviors by customers.

For the **Gauge chart**, I established a scale from 0 to 100 based on a calculated measure, *"Credit utilization"*, made by dividing BALANCE/CREDIT LIMIT *100. Threshold established is 30, and a value above that indicates a healthy use of credit by the customers.

Cluster 2 is the only one that surpasses this threshold by a significant amount, 59.38! The bank should be aware of this in building its strategies over these customers.

The other visualization, **Line and clustered column chart**, is composite and showcases PAYMENTS, PURCHASES and PRC_FULL_PAYMENTS among different clusters.

Finally, **Scatter plot chart** shows BALANCE and MINIMUM_PAYMENTS and takes into account again TENURE (which is indicated in years).

![Screenshot 2025-01-26 154434](https://github.com/user-attachments/assets/e9ec2bd2-b4e8-4a17-a6b2-5eeabb6f5db9)

# Conclusion

This part of the project in Power BI concentrates in possible findings on clusters, which are the main results of the previous analysis on Colab.

Different interesting insights have been discovered: it is suggested to download and explore the Dashboards, to concentrate on the desired aspects of the analysis!
