 # Zomato Data Analysis  

This repository contains a Python script and notebook for exploratory data analysis (EDA) of a Zomato restaurant dataset. The analysis uses Pandas, Matplotlib, and Seaborn to clean and explore the data, generating various visualizations for insights.  

## Data  

The analysis uses a CSV file containing information about Zomato restaurants. Key columns include:  
- **name**: Restaurant name.  
- **online_order**: Online ordering availability (Yes/No).  
- **book_table**: Table booking availability (Yes/No).  
- **rate**: Ratings provided by users (e.g., "4.1/5").  
- **votes**: Number of user votes.  
- **approx_cost(for two people)**: Approximate cost for two people.  
- **listed_in(type)**: Restaurant category (e.g., Buffet).  

Ensure the dataset (`data.csv`) is placed in the root directory of the repository for analysis.  

## Analysis and Visualizations  

The script performs the following operations:  

### Data Cleaning  
- Handles missing or incorrect values.  
- Converts ratings to numerical values for analysis.  
- Renames columns for consistency and easier handling.  

### Exploratory Data Analysis (EDA)  
The script generates various visualizations using Matplotlib and Seaborn to provide insights into:  
1. **Restaurant Availability**:  
   - Proportion of restaurants offering online orders and table bookings.  
2. **Rating Analysis**:  
   - Distribution of restaurant ratings.  
   - Top-rated restaurants by votes and rating.  
3. **Cost Analysis**:  
   - Average cost for two people by restaurant category.  
   - Correlation between cost, ratings, and votes.  
4. **Category Insights**:  
   - Number of restaurants in each category (e.g., Buffet, Cafes).  
5. **Top Restaurants**:  
   - Restaurants with the most votes.  
6. **Visualizations**:  
   - Bar chart of restaurants by category.  
   - Pie chart showing the availability of online orders and table bookings.  
   - Scatter plot of cost vs. rating by category.  
   - Histogram of restaurant ratings.  
   - Heatmap showing correlations between numerical columns.  

## Usage  

### Prerequisites  
Ensure you have Python 3.x installed with the following libraries:  
- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  

Install them using pip:  
```bash  
pip install pandas numpy matplotlib seaborn  
```  

### Running the Script  
Run the Python script or notebook:  
```bash  
python zomato_analysis.py  
```  
Or open the notebook in Jupyter and run the cells sequentially.  

## Output  
The script generates visualizations as PNG images and provides insights in the notebook itself.  

Would you like any adjustments or further details?

