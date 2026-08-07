# Dataset Documentation

This directory documents the datasets used throughout the Summer 2026
Data Science Projects.

The original raw datasets are downloaded separately from their
respective sources and are stored locally for analysis.

**The original raw datasets are intentionally NOT redistributed through
this GitHub repository.**

The datasets are used for educational and portfolio-analysis purposes.
Each dataset remains subject to its respective ownership, license,
attribution requirements, and terms of use.

---

# 1. Demand & Inventory — Retail Store Inventory Dataset

## Dataset source

**Platform:** Kaggle

**Dataset:** Retail Store Inventory Forecasting Dataset

**Dataset author:** Anirudh Singh Chauhan

**Original dataset page:**

https://www.kaggle.com/datasets/anirudhchauhan/retail-store-inventory-forecasting-dataset

## License

**CC0: Public Domain**

The Kaggle dataset page currently identifies this dataset as
**CC0: Public Domain**.

## Local location

The dataset is stored locally at:

`data/demand_inventory/`

The primary raw file is:

`retail_store_inventory.csv`

## Purpose

This dataset is used for educational and portfolio analysis involving:

- Business problem framing
- Retail sales analysis
- Demand analysis
- Inventory analysis
- Exploratory Data Analysis (EDA)
- Statistical decision support
- Demand forecasting
- Predictive modeling
- Inventory-related decision support

## Dataset characteristics

The dataset is described on Kaggle as a synthetic dataset designed for
inventory management and demand forecasting practice.

It contains daily retail data involving stores, products, sales,
inventory, pricing, promotions, weather and other demand-related
attributes.

## Repository status

**Raw dataset: NOT REDISTRIBUTED IN THIS REPOSITORY.**

The raw CSV remains stored locally and is excluded from Git tracking.

## Usage

**Purpose:** Educational / portfolio analysis.

The dataset is used to demonstrate data-processing, analytical,
statistical and machine-learning techniques.

The repository contains the original analysis and implementation work,
but does not redistribute the original raw dataset.

---

# 2. Fraud Detection — Credit Card Transactions Fraud Detection Dataset

## Dataset source

**Platform:** Kaggle

**Dataset:** Credit Card Transactions Fraud Detection Dataset

**Dataset uploader:** Kartik2112

**Original dataset page:**

https://www.kaggle.com/datasets/kartik2112/fraud-detection

## License

**CC0: Public Domain**

The Kaggle dataset page currently identifies this dataset as
**CC0: Public Domain**.

## Important dataset note

This dataset is a **simulated credit-card transaction dataset**.

According to the dataset documentation, the transactions were
generated using the Sparkov data-generation approach and represent
legitimate and fraudulent transactions covering the period from
January 1, 2019 to December 31, 2020.

Therefore, the dataset should not be represented as real banking
transaction data.

## Local location

The dataset is stored locally at:

`data/fraud/`

The downloaded raw files may include:

- `fraudTrain.csv`
- `fraudTest.csv`

## Purpose

This dataset is used for educational and portfolio analysis involving:

- Fraud detection
- Fraudulent transaction analysis
- Class imbalance analysis
- Feature engineering
- Statistical analysis
- Binary classification
- Fraud-risk prediction
- Anomaly detection
- Model evaluation

## Expected analytical / ML applications

The dataset may be used to investigate questions such as:

- What characteristics are associated with fraudulent transactions?
- How does transaction amount relate to fraud?
- Are fraudulent transactions associated with particular times,
  categories or locations?
- Can a transaction be assigned a fraud probability?
- Can machine learning distinguish fraudulent from legitimate
  transactions?

## Repository status

**Raw dataset: NOT REDISTRIBUTED IN THIS REPOSITORY.**

The raw dataset remains stored locally and is excluded from Git
tracking.

## Usage

**Purpose:** Educational / portfolio analysis.

The dataset is used to demonstrate data cleaning, exploratory
analysis, feature engineering, statistical analysis and machine
learning.

The dataset is simulated and should not be presented as evidence of
actual financial-fraud patterns in a real financial institution.

---

# 3. Recommendation — Retailrocket E-commerce Dataset

## Dataset source

**Platform:** Kaggle

**Dataset:** Retailrocket Recommender System Dataset

**Dataset uploader:** Retailrocket

**Original dataset page:**

https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset

## License

**CC BY-NC-SA 4.0**

The Kaggle dataset page currently identifies this dataset as
**CC BY-NC-SA 4.0**.

This license requires appropriate attribution and includes
non-commercial and share-alike conditions.

The applicable license terms should be respected whenever the dataset,
a derivative of the dataset, or material based upon it is
redistributed.

## Local location

The dataset is stored locally at:

`data/recommendation/`

The downloaded dataset may contain files such as:

- `events.csv`
- `item_properties.csv`
- `category_tree.csv`

The exact filenames may depend on the downloaded dataset version.

## Dataset characteristics

The dataset contains e-commerce interaction data collected from a
real-world e-commerce website.

The published data includes events such as:

- Views
- Add-to-cart interactions
- Transactions

It also contains item properties and a category hierarchy.

The published values are hashed for confidentiality purposes.

## Purpose

This dataset is used for educational and portfolio analysis involving:

- Customer behaviour analysis
- Customer segmentation
- Product interaction analysis
- Recommendation systems
- Collaborative filtering
- Implicit-feedback modeling
- Product personalization
- Ranking
- AI recommendation use cases

## Expected analytical / ML applications

The dataset may be used to investigate questions such as:

- What products does a visitor interact with?
- What categories are associated with a visitor's behaviour?
- Can similar users or items be identified?
- Can products be recommended based on previous interactions?
- Can products be ranked according to their predicted relevance?

## Attribution

The dataset is attributed to **Retailrocket** and is obtained through
the Kaggle publication identified above.

The original dataset source and applicable license are retained in
this documentation.

## Repository status

**Raw dataset: NOT REDISTRIBUTED IN THIS REPOSITORY.**

The raw dataset remains stored locally and is excluded from Git
tracking.

## Usage

**Purpose:** Educational / portfolio analysis.

The dataset is used for non-commercial educational and portfolio
demonstration purposes.

The applicable CC BY-NC-SA 4.0 license terms are respected.

---

# Dataset Usage & Reproducibility Policy

## Raw datasets

The original raw datasets are **not included in this GitHub
repository**.

They are downloaded separately from their respective original
sources and stored locally.

The repository therefore does not redistribute the original raw CSV
files.

## What this repository contains

This repository contains original work developed for the projects,
including:

- Python code
- Jupyter notebooks
- Data-processing logic
- Data-cleaning logic
- Feature-engineering logic
- Exploratory Data Analysis
- Statistical analysis
- Machine-learning implementations
- Model evaluation
- Visualizations
- Documentation
- Analytical results

## Reproducing the projects

To reproduce a project:

1. Obtain the required dataset from its original source.
2. Review the dataset's current license and usage conditions.
3. Place the downloaded dataset in the corresponding local
   `data/` directory.
4. Run the relevant notebook or source code.

## Licensing and attribution

Each dataset remains subject to its respective license.

The license information documented above reflects the license shown
on the respective Kaggle dataset pages at the time this documentation
was prepared.

Users should verify the current license and terms on the original
dataset page before redistributing the dataset or derivatives of it.

## Educational / portfolio purpose

The datasets are used for **educational and portfolio-analysis
purposes**.

This repository does not claim ownership of any third-party dataset.

All dataset ownership and applicable rights remain with the respective
dataset owner/provider.

---

## Summary

| Dataset | Business Domain | Source | License | Raw Dataset in GitHub? |
|---|---|---|---|---|
| Retail Store Inventory Forecasting | Demand & Inventory | Kaggle | CC0: Public Domain | No |
| Credit Card Transactions Fraud Detection | Fraud | Kaggle | CC0: Public Domain | No |
| Retailrocket E-commerce | Recommendation | Kaggle | CC BY-NC-SA 4.0 | No |