# Cryptocurrencies
## Overview
Reprocessed the cryptocurrencies data with cluster, reducing dimensions, and PCA method. Created a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for new investment. 

## Results
### Preprocessing the Data for PCA
- Final filtered tradable cryptocurrencies name data frames(top rows):

![Screen Shot 2021-10-24 at 5 47 34 PM](https://user-images.githubusercontent.com/66225050/138619759-e190c0b6-033d-48df-9609-3d5e6983eb9c.png)

![Screen Shot 2021-10-24 at 5 49 02 PM](https://user-images.githubusercontent.com/66225050/138619805-5947a647-6b35-4eaf-9bfc-40177ddf7d2a.png)

- Standardize the data

![Screen Shot 2021-10-24 at 5 50 02 PM](https://user-images.githubusercontent.com/66225050/138619835-e81d42d8-108f-4f57-b589-fddbebc4fffb.png)

### Reducing Data Dimensions Using PCA
- PCA with 3 components:

![Screen Shot 2021-10-24 at 5 51 06 PM](https://user-images.githubusercontent.com/66225050/138619883-422e7c0f-798c-4a58-8395-bc97f8a513c4.png)

### Clustering Crytocurrencies Using K-Means
- Found best `k` with Elbow Curve -- `k=4"
![Screen Shot 2021-10-24 at 5 56 12 PM](https://user-images.githubusercontent.com/66225050/138620137-94d8c0f0-0c41-4461-bef9-5b10d5537304.png)

- predicted clusters 
![Screen Shot 2021-10-24 at 6 04 53 PM](https://user-images.githubusercontent.com/66225050/138620455-19c0bb1a-8496-4cf2-a72a-33c148bbd55e.png)

### Visualizing Cryptocurrencies Results
- 3D Scatter
![Screen Shot 2021-10-24 at 6 05 43 PM](https://user-images.githubusercontent.com/66225050/138620524-4f31dd57-59cd-43fd-842d-5c77dbc95a69.png)

- hvplot table

![Screen Shot 2021-10-24 at 6 06 25 PM](https://user-images.githubusercontent.com/66225050/138620530-fe743fc5-7156-4fdc-b5d6-8d7fe00faf0c.png)

- `hvplot.scatter` plot
![Screen Shot 2021-10-24 at 6 06 32 PM](https://user-images.githubusercontent.com/66225050/138620547-ae4c822c-6e52-4fb9-9f19-79a7f8a2e581.png)

