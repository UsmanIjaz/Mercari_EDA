## Mercari Data Analysis

In this project, We analyzed the mercai dataset which contained information about 1.4 million products to be sold on the platform.

Dataset used in this project can be found here: https://www.kaggle.com/c/mercari-price-suggestion-challenge

# Installation
Following libraries are used for this project:
- numpy
- pandas
- matplotlib
- seaborn
- bokeh
- math
- warnings

# File Description
- Mercari_EDA.ipynb : This file contains the data analyis done for Mercari dataset. 
- categories_mean.html : Bokeh visualization of mean prices for categories
- Electronics_subcategories_mean.html : Bokeh visualization of mean prices for subcategories in category "Electronics"

# Project Motivation
I am always fascinated by the e-commerce platforms as these provides a new shopping experience which is different than the centuries old traditional shopping experience. It's first time for me to look into an e-commerce platform with a lens ofa data scientist. Some of the questions, I tried to answer in this notebook are:

- What is the overall condition of the products? 
- What is the shipment process and how it impacts the product price?
- How important is the brand name, which brands are popular and which ones are most expensive?
- What kind of products are popular and what kind of products are more expensive?
- Is there any free product?

# Summary 
- 75% of the products are under $30 and 99% of the products are under $170.
- ~43% of the products are in the best condition. ~25% are in very good condition and ~30% products are in good/average condition. On the other hand, ~2% of the products are in bad/worse condition. 
- ~55% of the products shipping is paid by the buyers and for ~45% of the products shipping is paid by the sellers.
- ~57% of the products have brand names. PINK is the most popular brand in terms of number of products whereas DEmdaco is the most expensive brand. 
- ~45% of the products are in category “Women”. Top 2 most popular subcategories for category “Women” are “Athletic Apparel” and “Tops and Blouses”.
- Most expensive category in terms of mean prices is “Electronics” with a mean price of $35.18. In Electronics, the most expensive subcategory is “Computers and Tablets” with a mean price of $87.88.
- There are 874 free products. :)

A blogpost related to this project can be found here: https://medium.com/@uijaz59/mercari-japanese-leading-e-commerce-app-f5ab77ee258

# Licensing, Acknowledgements
I have worked on this project to understand different aspects of e-commerce platform related to product information. Feel free to use it for further analysis. 

Doing this project, I benfitted from stackoverflow, pandas, seaborn and bokeh documentation. 

