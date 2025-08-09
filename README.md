# Overview
This a a repository for a DS 7374 class project where we seek to build novel insights for a fictional coffee chain called 'Grean Bean Coffee'. Data was originally created by IBM and is available on Kaggle. In this repository you will find the Raw Data obtained from Kaggle as well as the custom data files we made by merging raw datasets. Final Presentations on the models we suggest implementing can be found in the Presentations repository. Here we discuss implementing Recommender Systems trained on April sales data from Stores 3, 5, and 8. Accompanying powerpoint slides can also be found in this folder. 

Lastly, all code has been uploaded in HTML format for easy viewing and is in the Code folder. 





# Data

Data files are divided into 2 folders: 
- Raw Data
- Compiled Data

## Raw Data
Unmodified datasets obtained from IBM on coffeeshop sales data. Contains the following csv files:

- Dates.csv:
  Information on calendar dates by fiscal quarter.

  <img width="1221" height="320" alt="image" src="https://github.com/user-attachments/assets/ba03b5e7-7c9d-4ee9-a25e-0f3405815b0e" />

- customer.csv:
  Information for registered customers.

  <img width="928" height="292" alt="image" src="https://github.com/user-attachments/assets/dda76442-6bbc-4240-aae6-14f62223e54b" />

- generations.csv:

  Birth years by generation.


<img width="927" height="448" alt="image" src="https://github.com/user-attachments/assets/17f248e2-c5d1-4853-ab88-157cf86ffdf5" />
  
- pastry inventory.csv:

Daily pastry records by store, includes starting quantity of each pastry, number sold, and quantity wasted.


<img width="840" height="389" alt="image" src="https://github.com/user-attachments/assets/e5fa6a05-a385-4f9c-9a4e-18f7056ded13" />

- product.csv
Product information detailing category, product type, production cost and sales price


<img width="1758" height="427" alt="image" src="https://github.com/user-attachments/assets/fedd8f0e-9aed-4e53-ac3b-d393d5eaeb40" />


- sales reciepts.csv
- sales targets.csv
- sales_outlet.csv
- staff.csv

## Compiled Data
Custom datasets compiled from raw data and engineered features. Compiled data includes:
- modified_sales_data:
  Compiled data on sales reciepts, product names, product cost and sales price, and purchaser information

- modified_waste_records:
  Compiled data on pastry inventory by day and store, along with product name, product cost, sales price, and total wastage cost




# Presentations

There are 2 powerpoints available. 










# Data Source


https://www.kaggle.com/datasets/ylchang/coffee-shop-sample-data-1113?select=201904+sales+reciepts.csv
