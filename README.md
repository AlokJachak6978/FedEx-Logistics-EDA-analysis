# 🚚 **FedEx Logistic Performance Analysis**

This project delivers an in-depth analysis of FedEx’s logistics performance using a supply chain dataset. It uncovers actionable insights on shipping costs, delivery delays, and operational efficiency to help FedEx optimize its processes, reduce costs, and boost profitability.

---

## 📁 **Project Overview**

The goal of this project is to analyze FedEx’s supply chain data and provide insights to improve logistics operations. It explores key metrics like shipping costs, delivery delays, fulfillment methods, and regional performance to support data-driven decisions.

**What We Analyzed:**

- Shipping costs and methods (Air, Ocean, Truck)  
- Delivery delays and their impact  
- Fulfillment methods (From RDC, Direct Drop)  
- Vendor performance and costs  
- Regional shipment patterns  

---

## 📊 **Analysis & Visualizations**

We created several visualizations in Python to explore the data and find insights.

### 📌 **Overview Analysis**

**Key Metrics:**

- Total Shipments  
- Total Shipping Cost (`Cleaned_Freight_Cost`)  
- Total Cost (`Total Cost (USD)`)  
- Average Delivery Delay (`Delivery Delay (days)`)  
- Total Insurance Cost (`Line Item Insurance (USD)`)  

**Visuals & Features:**

- **Heatmap**: Shows how costs, weights, and delays are connected (e.g., `Line Item Value` and `Total Cost (USD)` have a strong 0.9 correlation).  
- **Bar Plots**: Breakdown of costs by country, vendor, and fulfillment method.  
- **Dynamic Filtering**: Analyze by Country, Shipment Mode, and Vendor.  
- **Insights Highlight**: Top regions (South Africa, Nigeria) and costly vendors (Aurobindo).  

---

## ⏰ **Delivery & Cost Analysis**

**Key Metrics:**

- Average Shipping Cost by Shipment Mode  
- Average Delay by Shipment Mode  
- Cost per Kilogram (`Freight Cost per Kilogram (USD/kg)`)  

**Visuals:**

- **Pair Plot**: Compares costs, delays, and weights, with colors for Shipment Mode (Air, Ocean, Truck).  
- **Pie Chart**: Shows Fulfill Via usage (60% From RDC, 40% Direct Drop).  
- **Bar Plot**: Insurance costs by country and shipping method.  

**Features:**

- Darker colors for opposite correlations (e.g., `Cleaned_Weight` vs `Freight Cost per Kilogram` at -0.4).  
- Legend on the right for easy understanding.  

---

## 📂 **Detailed Insights**

- **Grid View**: Table with all shipment details (e.g., `ID`, `Country`, `Vendor`, `Line Item Value`).  
- **Drill-Down**: Filter by Product Group (e.g., ARV), Vendor, or Country.  
- **Export Option**: Save filtered data for deeper analysis.  

---

## 🛠 **Tools & Technologies Used**

- **Python**: For coding and analysis  
- **Pandas**: To manage the dataset  
- **Seaborn & Matplotlib**: For creating charts  
- **Jupyter Notebook**: To run and display the analysis  
- **Data Cleaning**: Handled missing values and inconsistencies (`Cleaned_Freight_Cost`, `Cleaned_Weight`)  

---

## 📈 **Key Insights**

- **Top Regions**: South Africa and Nigeria have the most shipments—focus on improving logistics there.  
- **Shipping Costs**: Air shipping costs the most (~$5000), while Ocean is cheaper (~$2000). Use Ocean more to save money.  
- **Fulfillment Efficiency**: From RDC is used 60% of the time and is cheaper than Direct Drop.  
- **Vendor Costs**: Aurobindo accounts for 40% of total costs—negotiate better prices.  
- **Delivery Delays**: Ocean shipments have more delays (over 20 days), but delays don’t impact costs much.  
- **Cost Efficiency**: Heavier shipments (`Cleaned_Weight`) have lower cost per kg—combine shipments to save more.  

These insights help FedEx reduce shipping costs, manage stock better, and improve delivery times.

---

## 📁 **Project Files**

- `fedex_logistic_analysis.ipynb`: Jupyter Notebook with all code and charts  
- `dataset.csv`: Supply chain dataset  
- `README.md`: Project documentation  
- Saved charts (e.g., `correlation_heatmap_updated.png`, `pair_plot_shipment_mode_updated.png`)  

---

## 🚀 **How to Use**

**Clone this repository:**

```bash
git clone <repository-url>
