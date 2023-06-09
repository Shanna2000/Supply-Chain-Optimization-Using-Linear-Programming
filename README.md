# Supply Chain Optimization Using Linear Programming
###  Background 
The supply chain plays a vital role in the industrial landscape as it encompasses various activities such as production, transportation, storage, and distribution of goods and services from producers to consumers. Consequently, it is imperative for companies to establish robust supply chain management systems to optimize industrial processes and ensure their smooth functioning. 

### Goal
Minimizing shipping and warehouse costs as much as possible from the company's supply chain activities.

### Objective
Creating a linear programming model to identify plant and port combinations that result in the least shipping and warehouse costs.

## About Dataset
The dataset is Supply Chain Logistics Problem Dataset, taken from Brunel University London website. There are seven tables in total:
1. **OrderList Table**: contains order data from customers which includes Order ID, Product ID, Customer, Unit Quantity, and item weight. <br>
2. **FreightRates Table**: contains data on available couriers, shipping prices based on weight, weight ranges, and other shipping-related information.
3. **PlantPorts Table**: describes the allowed links between the warehouses and shipping ports in real world.
4. **ProductsPerPlant Table**: Contains lists all supported warehouse (plant) - product combinations
5. **The VmiCustomers Table**: Contains lists all special cases, where warehouse is only allowed to support specific customer, while any other non-listed warehouse can supply any customer
6. **WhCapacities Table**: Contain lists warehouse capacities measured in number of orders per day
7. **WhCosts Table**: specifies the cost associated in storing the products in a given warehouse (plant) measured in dollars per unit.

## Tools
The tools used for this project are pyhton as programming language, Jupyter Notebook/Google Colab, and several libraries such as: Pandas, Numpy, and Pulp to help buliding the Linear Programming Model. This project also use Looker Data Studio to help on data visualization and presentation

## Contents
### Data Preparation

---Still in progress
