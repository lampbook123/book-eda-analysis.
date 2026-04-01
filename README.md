# book-eda-analysis.
books eda and extracting insights.

This project focuses on Exploratory Data Analysis (EDA) of a book dataset to understand patterns between ratings, price, and categories.
The goal was to extract meaningful insights and validate assumptions using data.


 Objectives
-Analyze distribution of book ratings
-Understand relationship between price and ratings
-Identify high-performing categories
-Explore whether expensive books are better rated

 Tools & Technologies
-Python
-Pandas
-Matplotlib / Seaborn
-Jupyter Notebook

 Key Analysis Performed
1. Ratings Distribution
Most books are rated between 2 and 3
High ratings (4–5) are relatively rare
2. Price vs Ratings
No strong correlation found between price and ratings
Books across all rating levels have a wide price range
3. Category-wise Analysis
Calculated mean rating and count per category
Filtered categories with sufficient data for reliable insights
4. High-Rated Books Analysis
Identified categories with more books rated ≥ 4
Found that high-rated books are limited but present in specific categories

 Key Insights
- Ratings are skewed towards lower values
 -High-rated books are relatively rare
 -Price does not determine quality (rating)
 -Some categories consistently perform better in terms of ratings
📁 Project Structure
├── scraping.ipynb     # Data extraction & analysis
├── README.md          # Project documentation
