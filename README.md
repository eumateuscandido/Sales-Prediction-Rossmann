# Sales-Prediction-Rossmann 

Hi, so good to see you. My name is Mateus and this repository is about study of Sales Prediction Rossmann drug store. 

You can contact me:

  <a href="https://instagram.com/_mateuscandido" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href = "mailto:mateuscandsantos@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>

##
# Rossmann Store Sales
<div align="center">
<img src="https://user-images.githubusercontent.com/80724923/147797456-e3bb8c48-f8d3-483d-9acc-f5027232b0bb.png" width="700px" />
</div>

# Bussiness Question

Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.

# Data Fields

Most of the fields are self-explanatory. The following are descriptions for those that aren't.

Id - an Id that represents a (Store, Date) duple within the test set

Store - a unique Id for each store

Sales - the turnover for any given day (this is what you are predicting)

Customers - the number of customers on a given day

Open - an indicator for whether the store was open: 0 = closed, 1 = open

StateHoliday - indicates a state holiday. Normally all stores, with few exceptions, are closed on state holidays. Note that all schools are closed on public holidays and weekends. a = public holiday, b = Easter holiday, c = Christmas, 0 = None

SchoolHoliday - indicates if the (Store, Date) was affected by the closure of public schools

StoreType - differentiates between 4 different store models: a, b, c, d

Assortment - describes an assortment level: a = basic, b = extra, c = extended

CompetitionDistance - distance in meters to the nearest competitor store

CompetitionOpenSince[Month/Year] - gives the approximate year and month of the time the nearest competitor was opened

Promo - indicates whether a store is running a promo on that day

Promo2 - Promo2 is a continuing and consecutive promotion for some stores: 0 = store is not participating, 1 = store is participating

Promo2Since[Year/Week] - describes the year and calendar week when the store started participating in Promo2

PromoInterval - describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb,May,Aug,Nov" means each round starts in February, May, August, November of any given year for that store

# Procediments

This project is based on the CRISP-DM methodology which involves n interactions and is divided into 6 steps, namely:

1. Understanding the business: Here it is seen how the business works and what the business problem is

2. Understanding the data: For point 2, the definition of which data will be used, collection and exploration are addressed.
 
3. Data preparation: Here the data are converted, the features are extracted and other procedures that bring the project closer to the solution are carried out.

4. Data modeling: Here the data is modeled and explored.

5. Model Evaluation: Where models are used and evaluated.

6. Deployment: We put the model into production.

# ML Performance

# Results

# References

1. Data Source: KAGGLE, Kaggle. Rossmann Store Sales: Forecast sales using store, promotion, and competitor data. [S. l.], 2016. Disponível em: https://www.kaggle.com/c/rossmann-store-sales. Acesso em: 12 nov. 2021.

2. CRISP-DM: A metodologia ideal para Ciência de Dados. Internet, 28 out. 2020. Disponível em: https://dnc.group/blog/data-science/metodologia-crisp-dm/. Acesso em: 12 dez. 2021
