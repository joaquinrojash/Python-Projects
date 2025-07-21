# Airbnb Data Analysis

This project performs an exploratory data analysis (EDA) on Airbnb listings by combining data from multiple sources — including prices, room types, and reviews. The goal is to merge, clean, and analyze the data to gain insights into listing trends such as pricing, review frequency, and room distribution.

## 📂 Files Included

- `airbnb_price.csv` — Contains price information for Airbnb listings.
- `airbnb_room_type.xlsx` — Lists room types (private, shared, entire home).
- `airbnb_last_review.tsv` — Shows the last review dates for each listing.
- `airbnb-data-analysis.ipynb` — Main Jupyter Notebook for cleaning, merging, and analyzing the data.

## 🚀 Features

- Merges data from multiple formats (CSV, Excel, TSV).
- Cleans and preprocesses review dates and room types.
- Analyzes distribution of room types and pricing.
- Identifies earliest and latest reviews in the dataset.

##📊 Example Insights

- Earliest and most recent Airbnb review dates.
- Number of listings by room type.
- Distribution of prices across room types.

🔓 License

MIT License — feel free to use, modify, and distribute.

---

### 📦 `requirements.txt`

```txt
pandas
numpy
openpyxl  # required for reading .xlsx files
