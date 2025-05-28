FedEx Logistic Performance Analysis

About This Project

This project analyzes FedEx’s logistics performance using a supply chain dataset. It helps find the best products, vendors, and regions, and fixes problems to save money, manage stock better, and increase profits.

Dataset

The dataset has details about FedEx shipments:





ID: Unique number for each shipment.



Country: Destination (e.g., South Africa, Nigeria).



Shipment Mode: Transport method (e.g., Air, Ocean, Truck).



Fulfill Via: Fulfillment method (e.g., From RDC, Direct Drop).



Line Item Value: Item cost in USD.



Cleaned_Freight_Cost: Shipping cost in USD.



Total Cost (USD): Total cost (items + shipping).



Delivery Delay (days): Days late or early.



Line Item Insurance (USD): Insurance cost.



Vendor: Supplier (e.g., Aurobindo, Cipla).



Plus columns for weight, dates, and product details.

Goals





Find top products, vendors, and regions.



Reduce shipping costs.



Manage stock better.



Fix delays.



Increase profits.

What We Did

We used Python to analyze the data and made charts:





Heatmap: To see how costs, weights, and delays connect.



Pair Plot: To compare costs and delays by shipment mode.



Bar Plots: To check costs by country, vendor, and fulfillment method.

Key Findings





South Africa and Nigeria have the most shipments.



Air shipping costs more ($5000) than Ocean ($2000).



Heavy shipments cost more but are cheaper per kg.



From RDC (warehouse) is used 60% of the time and is cheaper.



Aurobindo (vendor) has high costs (40% of total).



Delays don’t affect costs much, but Ocean has more delays (over 20 days).

How to Use





Clone the repository:

git clone <repository-url>



Install libraries:

pip install pandas seaborn matplotlib numpy



Run the code in Jupyter Notebook to see the charts.



Check saved charts (e.g., correlation_heatmap_updated.png).

Tools





Python



Pandas



Seaborn



Matplotlib



Jupyter Notebook

Author

Created on May 28, 2025, for FedEx logistics analysis.
