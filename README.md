##############################################################
# BG-NBD ve Gamma-Gamma ile CLTV Prediction
##############################################################

# 1. Data Preperation
# 2. Expected Number of Transaction with BG-NBD Model
# 3. Expected Average Profit with Gamma-Gamma Model
# 4. Calculation of CLTV with BG-NBD and Gamma-Gamma Model
# 5. Creating Segments Based on CLTV
# 6. Functionalization of the work


##############################################################
# 1. Data Preperation
##############################################################

# An e-commerce company divides its customers into segments and Wants to determine marketing strategies.

# Dataset Story

# The data set includes the sales of a UK-based online store between 01/12/2009 and 09/12/2011.

# Variables

# InvoiceNo: Invoice number. Unique number for each transaction, i.e. invoice. Things starting with C mean canceled transactions.
# StockCode: Product code. It is a unique number for each product.
# Description: Product name
# Quantity: Number of products. It indicates how many of the products on the invoices were sold.
# InvoiceDate: Invoice date and time.
# UnitPrice: Product price (GBP).
# CustomerID: Unique customer number.
# Country: Country name. Country where the customer lives
