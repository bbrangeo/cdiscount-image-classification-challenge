# cdiscount-image-classification-challenge

## Description

the challenge focuses on building a model that automatically classifies the products based on their images. As a quick tour of [Cdiscount.com's](https://www.cdiscount.com/) website can confirm, one product can have one or several images. The data set Cdiscount.com is making available is unique and characterized by superlative numbers in several ways:

- Almost 9 million products: half of the current catalogue
- More than 15 million images at 180x180 resolution
- More than 5000 categories: yes this is quite an extreme multi-class classification!

## Data Description
Data is provided in bson file structure in both train and test set in the format of dictonary i.e. Each dictionary contains a product id (key: _id), the category id of the product (key: category_id), and between 1-4 images, stored in a list (key: imgs).
