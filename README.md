# ABC_XYZ_segmentation
Using ABC-XYZ analysis method to segment 'Stock Code' into each category by 'Revenue' and 'Order Quantity'.

Based on Pareto(80/20 rule) principle, states that for many outcomes, roughly 80% of consequences come from 20% of causes. I applied this for my project to classify StockCode into ABC and XYZ categories. 

In my project, it is a combination of ABC(by Cumulative Percent of Revenue) and XYZ(by Coefficient of Variation) analysis methods. With the ABC analysis: 
1. Category A (80-20) consists of the types of products that absorb 80 percent of total revenue, with the number of goods accounting for around 20 percent of all types of goods handled.
2. Category B (15-30), Kinds of goods that absorb about 15% of total revenue given for inventory (after category A), with the number of types of goods accounting for approximately 30% of all types of goods handled.
3. Category C (5-50) consists of the kinds of goods that absorb just about 5% of total revenue and the number of types of goods that absorb approximately 50% of all types of goods managed.

As for XYZ analysis:
1. X-class is an item with constant demand that has very little change and can be forecasted with high accuracy(CV less than 0.5).
2. Y-class goods with variable demand with modest changes and a medium level of predicting accuracy(CV between 0.5 and 1)
3. Z-class, the number of requests for various commodities varies greatly from time to time and is impossible to estimate(CV greater than 1)

The integration of ABC and XYZ finally identified into 9 specific groups namely AX, AY, AZ, BX, BY, BZ, CX, CY, and CZ.
In my uploaded documents, the file 'ABC-XYZ.pdf' also states the method specific to perform segmentation.

I also drew the Pareto diagram to see the organization based on the cumulative proportion of Revenue and SKU.

I use the dataset 'online_retail_II.xlsx' for this project, you can download it from my repository.
Source of the dataset:https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset


