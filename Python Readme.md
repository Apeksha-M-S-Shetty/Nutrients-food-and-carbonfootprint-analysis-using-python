Step 1: Load & Inspect Data
- Read the CSV file using pandas.
- Check structure and missing values using .info() and .isnull().sum().

 Step 2: Handle Missing Numeric Values
- Identify numeric columns.
- Fill missing values with column-wise mean to preserve distribution.

 Step 3: Standardize Data Types
- Convert specific columns to numeric if needed.
- Normalize text columns by stripping spaces and converting to lowercase.

 Step 4: Logical Imputation for Categorical Columns
- Fill missing values in:
- Food: Based on Category and Type.
- Associativity: Based on Type (e.g., vegetarian/non-vegetarian).
- Region: Based on Food and Category.
- Type: Based on Category (e.g., plant-based or animal-based).
- Category: Based on food (e.g., leafy-green or tropical fruit).
- Allergy: Based on Food (e.g.,leafy-green or tropical fruit ).
- Serving: Based on Food & type (e.g.,leafy-green or tropical fruit ).


Step 5: Visualize Insights
- Bar Plot: Count of food items by region.
- Grouped Bar Plot: Distribution of food types across regions.
- Distribution of energy
- outlier detection  in energy content

Summary
- Cleaned and enriched dataset using logical rules.
- Visualized regional and categorical trends.
- Ready for further analysis or modeling.


