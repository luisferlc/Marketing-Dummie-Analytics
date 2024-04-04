# iFood Marketing Analytics
Este repositorio contiene un análisis de los datos públicos de iFood (https://www.ifood.com.br/), una empresa que se dedica a la venta y entrega a domicilio de comida por medio de su App, así como un Uber Eats o Rappi Food, pero esta empresa es Brasileña. Datos públicos, obtenidos de: https://github.com/nailson/ifood-data-business-analyst-test

# Diccionario de datos:
- AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
- AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
- AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
- AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
- AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
- AcceptedCmpOverall: overall number of accepted campaigns
- Response: 1 if customer accepted the offer in the last campaign, 0 otherwise
- Complain: 1 if customer complained in the last 2 years
- DtCustomer: date of customer’s enrolment with the company
- Education: customer’s level of education
- Marital: customer’s marital status.
- Kidhome: number of small children in customer’s household
- Teenhome: number of teenagers in customer’s household
- Income: customer’s yearly household income
- MntFishProducts: amount spent on fish products in the last 2 years
- MntMeatProducts: amount spent on meat products in the last 2 years
- MntFruits: amount spent on fruits products in the last 2 years
- MntSweetProducts: amount spent on sweet products in the last 2 years
- MntWines: amount spent on wine products in the last 2 years
- MntGoldProds: amount spent on gold products in the last 2 years
- NumDealsPurchases: number of purchases made with discount
- NumCatalogPurchases: number of purchases made using catalogue
- NumStorePurchases: number of purchases made directly in stores
- NumWebPurchases: number of purchases made through company’s web site
- NumWebVisitsMonth: number of visits to company’s web site in the last month
- Recency: number of days since the last purchase

## Columnas creadas para análisis:
- Age_Type: clasificación para distintos rangos de edades con base a cuartiles: 1) Menor a 43: I  || 2) Entre 43 y 50: II || 3) Entre 50 y 61: III || 4) Mayor a 61: IV
- Income_Type: clasificación con base a salario anual (Income) basado en cuartiles también: "High" siendo el mayor rango, "Low" el menor.
- Customer_Type: unión de Age_Type y Income_Type, al final tenemos 8 tipos distintos de clientes, por ejemplo "II-Medium".
- Marital_Status:	si esta casado o no el cliente.
- Total_Sons: número total de hijos.
- Sons_Class: clasificación de padres: si tiene 0, 1 o 2 o más hijos.
- Total_Purchases: número total de compras hechas por el cliente.

## Plots
<img src="https://github.com/luisferlc/Marketing-Dummie-Analytics/blob/main/newplot.png"> 
<img src="https://github.com/luisferlc/Marketing-Dummie-Analytics/blob/main/newplot%20(1).png"> 
<img src="https://github.com/luisferlc/Marketing-Dummie-Analytics/blob/main/newplot%20(2).png"> 
<img src="https://github.com/luisferlc/Marketing-Dummie-Analytics/blob/main/newplot%20(3).png"> 
<img src="https://github.com/luisferlc/Marketing-Dummie-Analytics/blob/main/newplot%20(4).png"> 
<img src="https://github.com/luisferlc/Marketing-Dummie-Analytics/blob/main/newplot%20(5).png"> 
