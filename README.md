## Project Objective
The project aims to evaluate the effectiveness of a $5 million marketing campaign aimed at promoting a debt relief program and to provide strategic recommendations for future campaign improvements. The analysis utilized client, deposit, and calendar data to assess campaign success and predict potential performance changes if launched in a different time frame.

## Key Metrics
- **New Client Acquisition Rate (North Star Metric)**

Definition: The number of new clients acquired during and immediately after the campaign period.

Explanation: This metric directly measures the campaign's effectiveness in attracting new customers, which is a primary goal of most marketing campaigns. It provides a clear indicator of growth and market penetration. As you noted, more clients acquired typically corresponds to a higher success rate of the campaign.

- **Total Deposit Amount**

Definition: The sum of all deposits made by clients during and after the campaign period.

Explanation: This metric reflects the financial impact of the campaign. An increase in total deposits indicates not only that new clients were acquired, but that they are actively engaging with the debt relief program. It also captures any increase in deposits from existing clients who may have been influenced by the campaign.

- **Customer Lifetime Value (CLV) by Demographic Segment**

Definition: The predicted net profit attributed to the entire future relationship with a customer, segmented by demographic factors (e.g., age, region, homeownership status).

Explanation: This metric helps identify which demographic groups contribute the most value over time. It can be used to refine future marketing strategies by targeting the most profitable segments. CLV takes into account not just initial deposits, but also the long-term value each client brings to the business.

## Technical Details
- Analyzed a dataset of 480,394 client deposits spanning 5 months using Python libraries including pandas, matplotlib, and seaborn to assess campaign effectiveness.
- Demonstrated campaign success by identifying an increase of 11,544 new clients during the campaign month, as measured by unique client ID analysis before and after the campaign period.
- Quantified campaign impact by observing a $9.8 million increase in monthly deposit amounts from pre-campaign to campaign month, rising from $29.9 million to $39.7 million, using time series analysis and visualization.
![](https://github.com/najmisyazani/Marketing-Campaign-Performance/blob/main/Growth%20in%20deposit.png)
- Identified key demographic for targeted marketing, revealing that middle-aged homeowners (40-60 years old) contributed 42% of extra deposits while representing only 37% of clients, using customer segmentation and descriptive statistics.
![](https://github.com/najmisyazani/Marketing-Campaign-Performance/blob/main/Highest%20contribution%20sub-group%20of%20clients.png)
- Simulated campaign postponement scenario, revealing that delaying the campaign would have resulted in only a $2.5 million increase in deposits compared to the actual $10 million increase, guiding future campaign timing decisions.
