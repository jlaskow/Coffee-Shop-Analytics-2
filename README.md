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


- sales reciepts.csv:

April sales records for Stores 3, 5, and 8


<img width="1911" height="427" alt="image" src="https://github.com/user-attachments/assets/e432c265-e49d-4d4d-bb51-0051dbec75a7" />



- sales targets.csv:

April sales targets for all 8 stores


<img width="941" height="410" alt="image" src="https://github.com/user-attachments/assets/cd467907-70c8-420a-8b91-052cee8321f9" />

- sales_outlet.csv:

Information on sales outlet location and type


<img width="1861" height="452" alt="image" src="https://github.com/user-attachments/assets/d348f4e5-6c81-4057-9553-d04897cad66c" />

- staff.csv:

Staff records and outlet location. 


<img width="1417" height="552" alt="image" src="https://github.com/user-attachments/assets/2586812f-c192-405a-bdce-769dbed001f2" />


## Compiled Data
Custom datasets compiled from raw data and engineered features. Compiled data includes:
- modified_sales_data:
  Compiled data on sales reciepts, product names, product cost and sales price, and purchaser information

<img width="1517" height="233" alt="image" src="https://github.com/user-attachments/assets/abd60132-d88d-443f-aa3a-6e67896ab157" />

- modified_waste_records:
  Compiled data on pastry inventory by day and store, along with product name, product cost, sales price, and total wastage cost


<img width="1274" height="281" alt="image" src="https://github.com/user-attachments/assets/1cda2ba7-1a6e-47a2-a941-fb87191f88d9" />




# Presentations

There are 2 powerpoints available:

- Business Presentation:  Boosting Profit for the Grean Bean Coffee Company with Recommender Systems

  A business presentation tailored for the company's CEO, focusing on the financial costs and benefits associated with a customer recommender system designed to boost monthly revenue.

<img width="1917" height="1034" alt="image" src="https://github.com/user-attachments/assets/0b67ed12-b6d6-442c-ac80-9552a7360c85" />


- Analytics Presentation

  A technical presentation tailored for the company's CTO, focusing on the methodology for designing the recommender systems and well as the next steps for model integration with the company's business platforms.


  <img width="723" height="376" alt="image" src="https://github.com/user-attachments/assets/aa4520d6-539b-4033-9675-b9c16cc0ed3d" />











# Data Source


https://www.kaggle.com/datasets/ylchang/coffee-shop-sample-data-1113?select=201904+sales+reciepts.csv
