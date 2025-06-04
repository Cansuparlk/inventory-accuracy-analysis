# Inventory Accuracy Analysis with Python

This repository contains a data-driven Python project focused on identifying and resolving inventory discrepancies in logistics and supply chain environments. Using a simulated dataset representing four warehouses, we analyze mismatches between ERP-reported stock levels and physical stock counts.

## Use Case

Inventory inaccuracies are a major source of financial loss in logistics, leading to overstock, stockouts, and poor operational planning. In this project, we demonstrate how lightweight data analysis using Python can:

- Calculate inventory accuracy by SKU and warehouse  
- Flag high-risk products with significant discrepancies  
- Visualize key error patterns (category, location, volume)  
- Estimate potential financial impact (e.g. approximately $300K USD annually)  
- Recommend operational improvements without enterprise BI tools  

## Dataset

The dataset includes 500 sample records with the following columns:

- `product_id`: Unique SKU identifier  
- `warehouse_id`: Storage location  
- `system_qty`: Stock quantity in ERP system  
- `counted_qty`: Quantity counted during stocktake  
- `category`: Product group (FMCG, electronics, apparel, etc.)  
- `count_date`: Date of physical count  

> The dataset is entirely simulated and safe to use in public analysis.

## Tools Used

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Google Colab (no installation required)

## Project Highlights

- Achieved up to **40% reduction** in flagged discrepancies  
- Estimated **$140K USD in savings** in a modeled scenario  
- Fully reproducible with open-source tools  


## Repository Structure

```
inventory-accuracy-analysis/
├── data/
│   └── inventory_data.csv
├── notebook/
│   └── accuracy_analysis.ipynb
├── output/
│   └── charts/
├── README.md
```


## License & Contribution

This project is open for learning and educational use.  
Feel free to adapt, extend, or reuse it for your own supply chain cases.
