## The project is divided in two notebooks: 

The 1_data_processing.ipynb uses the following files in data/raw/:

- offers.json — information about promotional offers.
- profile.json — customer  profiles.
- transactions.json — transaction historic data.

The 2_modeling.ipynb expects the following files inside data/processed/:

- clients_processed.json - information about clients
- offers_processed.json - offers to be distributed
- transactions_processed.json - transactions


## Requirements- dependencies listed in requirements.txt:
Python 3.8+
Java 17
Apache Spark / PySpark

## How to Run
Clone the repository. In your terminal:

git clone https://github.com/drica-monteiro/ifood-case.git

cd cust_seg

Then run the notebooks.

## If you are using Google Colab or Databricks Community Edition, you don't need to install Apache Spark / PySpark. The requirements are already native to these environments.
## In order to avoid version conflicts, it is preferable to run this project in Google Colab.
