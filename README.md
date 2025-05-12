#  Amazon Product Reviews - Data Cleaning Project

This project involves cleaning and preprocessing a raw dataset of Amazon product reviews using Python and Pandas.

##  Dataset

- **File**: `amazon.csv`
- **Size**: 1465 records
- **Content**: Product information, pricing, ratings, user reviews, and metadata.

## Objective

Clean and standardize the dataset to make it analysis-ready by:
- Handling missing values
- Removing duplicates
- Standardizing column formats and names
- Converting price and percentage fields to numeric
- Verifying and correcting data types



##  Tools Used

- Python
- Pandas



##  Cleaning Steps Performed

1. **Renamed columns** to lowercase and replaced spaces with underscores.
2. **Removed duplicate rows** (if any).
3. **Handled missing values** by filling missing `rating_count` with 0.
4. **Cleaned and converted**:
   - `discounted_price`, `actual_price` → removed ₹ and commas, converted to float
   - `discount_percentage` → removed `%`, converted to float
   - `rating_count` → removed commas, converted to integer
   - `rating` → converted to float
5. **Saved cleaned data** as `amazon_cleaned.csv`.



##  How to Use

1. Clone the repository or download the files.
2. Ensure `amazon.csv` is in the same directory as the script.
3. Run the Python script:


python clean_amazon_data.py
