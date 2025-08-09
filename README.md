# Overview

This repository contains the deliverables for a DS 7374 class project focused on generating actionable business insights for a fictional coffee chain, **Green Bean Coffee**.  
The dataset, originally created by IBM and published on Kaggle, has been expanded with custom, engineered datasets created by merging and transforming the original files.

Within this repository, you will find:

- **Raw Data** obtained from Kaggle.  
- **Compiled Data** featuring additional engineered variables for analysis.  
- **Presentations** summarizing our findings and model recommendations.  
- **Code** (in HTML format) for easy review of our data processing, modeling, and visualization workflows.

The project specifically explores the implementation of **Recommender Systems** trained on April sales data from Stores 3, 5, and 8, with results and recommendations presented for both business and technical audiences.  
Accompanying PowerPoint slides are included in the `Presentations` folder.

---

# Data

The data is organized into two main folders:

- **Raw Data** — Unmodified datasets from Kaggle.  
- **Compiled Data** — Datasets generated from the raw data with feature engineering.

---

## Raw Data

Unmodified datasets obtained from IBM on coffee shop sales. Includes the following CSV files:

- **dates.csv**  
  Calendar dates mapped to fiscal quarters.  
  <img width="900" alt="dates" src="https://github.com/user-attachments/assets/ba03b5e7-7c9d-4ee9-a25e-0f3405815b0e" />

- **customer.csv**  
  Records for registered customers.  
  <img width="900" alt="customer" src="https://github.com/user-attachments/assets/dda76442-6bbc-4240-aae6-14f62223e54b" />

- **generations.csv**  
  Birth years grouped by generation.  
  <img width="900" alt="generations" src="https://github.com/user-attachments/assets/17f248e2-c5d1-4853-ab88-157cf86ffdf5" />
  
- **pastry inventory.csv**  
  Daily pastry inventory per store, including starting quantity, units sold, and quantity wasted.  
  <img width="900" alt="pastry inventory" src="https://github.com/user-attachments/assets/e5fa6a05-a385-4f9c-9a4e-18f7056ded13" />

- **product.csv**  
  Product information including category, type, production cost, and sales price.  
  <img width="900" alt="product" src="https://github.com/user-attachments/assets/fedd8f0e-9aed-4e53-ac3b-d393d5eaeb40" />

- **sales receipts.csv**  
  April sales records for Stores 3, 5, and 8.  
  <img width="900" alt="sales receipts" src="https://github.com/user-attachments/assets/e432c265-e49d-4d4d-bb51-0051dbec75a7" />

- **sales targets.csv**  
  April sales targets for all eight stores.  
  <img width="900" alt="sales targets" src="https://github.com/user-attachments/assets/cd467907-70c8-420a-8b91-052cee8321f9" />

- **sales_outlet.csv**  
  Information on sales outlet locations and types.  
  <img width="900" alt="sales outlet" src="https://github.com/user-attachments/assets/d348f4e5-6c81-4057-9553-d04897cad66c" />

- **staff.csv**  
  Staff records and associated outlet locations.  
  <img width="900" alt="staff" src="https://github.com/user-attachments/assets/2586812f-c192-405a-bdce-769dbed001f2" />

---

## Compiled Data

Custom datasets created by merging and augmenting the raw datasets. Includes:

- **modified_sales_data**  
  Consolidated sales receipts with product details, costs, sales prices, and customer information.  
  <img width="900" alt="modified sales data" src="https://github.com/user-attachments/assets/abd60132-d88d-443f-aa3a-6e67896ab157" />

- **modified_waste_records**  
  Consolidated pastry inventory with product names, costs, prices, and calculated wastage costs per day and store.  
  <img width="900" alt="modified waste records" src="https://github.com/user-attachments/assets/1cda2ba7-1a6e-47a2-a941-fb87191f88d9" />

---

# Presentations

Two presentation decks are provided:

- **Business Presentation – Boosting Profit with Recommender Systems**  
  Prepared for the CEO, focusing on the financial implications and potential revenue gains from implementing a customer recommender system.  
  <img width="900" alt="business presentation" src="https://github.com/user-attachments/assets/0b67ed12-b6d6-442c-ac80-9552a7360c85" />

- **Analytics Presentation**  
  Prepared for the CTO, detailing the methodology, model design, and integration plan for recommender systems within existing business platforms.  
  <img width="900" alt="analytics presentation" src="https://github.com/user-attachments/assets/aa4520d6-539b-4033-9675-b9c16cc0ed3d" />

---

# Other Documents

This folder includes mock project proposals for the CEO and an evaluation of the company’s data architecture using the **DELTTAA**, **FACE**, and **Pachinko** frameworks.

- **Project Proposal**  
  <img width="900" alt="project proposal" src="https://github.com/user-attachments/assets/d1149191-f898-4ef7-b943-072a5ee40d7c" />

- **Coffee Shop Data Evaluation**  
  <img width="900" alt="coffee shop data evaluation" src="https://github.com/user-attachments/assets/663705c2-3438-4916-9001-7ff7796fd897" />

---

# Data Source

[Kaggle – Coffee Shop Sample Data by IBM](https://www.kaggle.com/datasets/ylchang/coffee-shop-sample-data-1113?select=201904+sales+reciepts.csv)
