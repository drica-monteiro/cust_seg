## The project is divided in two notebooks: 

The 1_data_processing.ipynb uses the following files in data/raw/:

- offers.json — information about promotional offers.
- profile.json — customer  profiles.
- transactions.json — transaction historic data.

The 2_modeling.ipynb expects the following files inside data/processed/:

- clients_processed.json - information about clients
- offers_processed.json - offers to be distributed
- transactions_processed.json - transactions


## Requirements- dependencies:
You need to install java 17.0.12 on the link below:

https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html

If you are using conda, run

conda env create -f pyspark_env.yml

conda activate pyspark_env

If you are using pip,

pip install -r requirements.txt

## How to Run
Clone the repository. In your terminal:

git clone https://github.com/drica-monteiro/ifood-case.git

cd ifood-case

Then run the notebooks.

## If you are using Google Colab or Databricks Community Edition, you don't need to install Apache Spark / PySpark. The requirements are already native to these environments.

## The easiest way to run the notebooks is to clone the repository and run this project in Google Colab. That way there is no need to install anything and there will be no version conflicts.
