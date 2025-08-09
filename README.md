# Overview

This repository contains the deliverables for a DS 7374 class project focused on generating actionable business insights for a fictional coffee chain, Green Bean Coffee.  
The dataset, originally created by IBM and published on Kaggle, has been expanded with custom, engineered datasets created by merging and transforming the original files.

Within this repository, you will find:

- Raw Data obtained from Kaggle.
- Compiled Data featuring additional engineered variables for analysis.
- Presentations summarizing our findings and model recommendations.
- Code (in HTML format) for easy review of our data processing, modeling, and visualization workflows.

The project specifically explores the implementation of Recommender Systems trained on April sales data from Stores 3, 5, and 8, with results and recommendations presented for both business and technical audiences.  
Accompanying PowerPoint slides are included in the Presentations folder.

------------------------------------------------------------
# Data

The data is organized into two main folders:

- Raw Data — Unmodified datasets from Kaggle.
- Compiled Data — Datasets generated from the raw data with feature engineering.

------------------------------------------------------------
## Raw Data

Unmodified datasets obtained from IBM on coffee shop sales. Includes the following CSV files:

- dates.csv  
  Calendar dates mapped to fiscal quarters.

- customer.csv  
  Records for registered customers.

- generations.csv  
  Birth years grouped by generation.
  
- pastry inventory.csv  
  Daily pastry inventory per store, including starting quantity, units sold, and quantity wasted.

- product.csv  
  Product information including category, type, production cost, and sales price.

- sales receipts.csv  
  April sales records for Stores 3, 5, and 8.

- sales targets.csv  
  April sales targets for all eight stores.

- sales_outlet.csv  
  Information on sales outlet locations and types.

- staff.csv  
  Staff records and associated outlet locations.

------------------------------------------------------------
## Compiled Data

Custom datasets created by merging and augmenting the raw datasets. Includes:

- modified_sales_data  
  Consolidated sales receipts with product details, costs, sales prices, and customer information.

- modified_waste_records  
  Consolidated pastry inventory with product names, costs, prices, and calculated wastage costs per day and store.

------------------------------------------------------------
# Presentations

Two presentation decks are provided:

- Business Presentation – Boosting Profit with Recommender Systems  
  Prepared for the CEO, focusing on the financial implications and potential revenue gains from implementing a customer recommender system.

- Analytics Presentation  
  Prepared for the CTO, detailing the methodology, model design, and integration plan for recommender systems within existing business platforms.

------------------------------------------------------------
# Other Documents

This folder includes mock project proposals for the CEO and an evaluation of the company’s data architecture using the DELTTAA, FACE, and Pachinko frameworks.

- Project Proposal
- Coffee Shop Data Evaluation

------------------------------------------------------------
# Data Source

Kaggle – Coffee Shop Sample Data by IBM  
https://www.kaggle.com/datasets/ylchang/coffee-shop-sample-data-1113?select=201904+sales+reciepts.csv
