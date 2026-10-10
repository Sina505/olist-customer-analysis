# Olist Customer & Order Analysis

A basic exploratory analysis of the Olist Brazilian e-commerce data, done as part of my internship course.

## What's inside

Everything is in one notebook, `Customers - Olist.ipynb`:

- **Cleaning:** checking missing values and removing "delivered" orders that are missing delivery dates
- **Repeat purchases:** how many customers bought once vs. more than once
- **Order value:** how much a typical order is worth (I cut off the top 5% so a few huge orders don't squash the chart)
- **Order timing:** number of orders by month, day of the week and hour

## Dataset

The data is the [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) on Kaggle. I haven't included it in this repo, so you'll need to download it yourself.

1. Download the dataset from Kaggle and unzip it.
2. Put the CSV files in a folder called `data/` next to the notebook.
3. If the notebook still points to my local Windows paths, change them to something like `data/olist_customers_dataset.csv`.

## Running it

You need Python with `pandas`, `matplotlib`, `seaborn` and Jupyter:

    pip install pandas matplotlib seaborn notebook
    jupyter notebook Customers - Olist.ipynb

## About this project

I did this for my internship course, so it's a fairly basic look at the data rather than a full analysis. There's a lot more you could do with this dataset (customer segmentation, delivery delays, review scores and so on), but I kept it to the questions above.