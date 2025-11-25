SHOPPING BEHAVIOUR DATA ANALYSIS USING PYTHON

PROJECT OVERVIEW:-
    This project analyzes customer shopping behaviour using Python. The dataset contains about demographics,shopping patterns,spending habits,seasonal trends,and product preferences. The goal is to uncover insights that can help businesse in:
     1. Customer Segmentation
     2. Trend analysis
     3. Marketing strategy improvement
     4. Sales optimization

OBJECTIVE:-
    1. Understood customer demographics and shopping characteristics.
    2. Clean and preprocess the dataset for accurate analysis.
    3. Perform exploratory data analysis(EDA) to find trends and correlations.
    4. Build visualization to present customer behaviour insights.
    5. Segment customers using age, spending, category, and season.

TOOLS & LIBRARIES USED:-
    1. Pandas - Data manipulation & cleaning
    2. NumPy - Numerical computation
    3. Matplotlib & Seaborn - Visualization

DATASET OVERVIEW:-
    File Name - SHOPPING_BEHAVIOUR.csv
    Records - 3899
    Columns - 17
    Domain - Retail Analysis

DATASET DESCRIPTION:-
    Column Name               DESCRIPTION
                                    
    GENDER                    Male/Female
    AGE                       Customer Age
    ITEM PURCHASED            Product name     
    CATEGORY                  Product Category
    PURCHASE AMOUNT(USD)      Amount spent
    LOCATION                  State
    SIZE                      S/M/L/XL
    COLOR                     Product color
    SEASON                    Season of purchase
    SUBSCRIPTION STATUS       Active/Inactive
    SHIPPING TYPE             Standard/Express
    DISCOUNT APPLIED          Yes/No
    PROMO CODE USED           Yes/No
    PAYMENT METHOD            Card/UPI/COD
    FREQUENCY OF PURCHASES    Weekly/Monthly/Rarely

DATA PREPROCESSING:-
    1. Handling missing values
    2. Removing Duplicates
    3. Converting appropriate columns to category datatype
    4. Feature Engineering
        1. Age group using pd.cut()
        2. Customer segmentation using pd.cut()

EXPLORATATORY DATA ANALYSIS (USD):-
     Aggregation using groupby
        1. Average Purchase by gender
        2. Total previous purchase by category
        3. Number of Customers in each age group
        3. Purchase trend by category and gender
    
VISUALIZATION:-
    1. Purchase Trend by Gender Across Categories - Lineplot
    2. Average Purchase Amount by Age Group - Lineplot
    3. Purchase Amount Distribution by Gender - Pie chart
    4. Average Purchase Amount by Season - Barplot
    5. Items Purchased by Season and Category - Countplot
    6. Top 10 Locations - Average Purchase Amount by Category - Heatmap
    7. Distribution of Previous purchases by Category - Histplot
    8. Purchase Amount by Category and Size - Barplot
    9. Purchase Amount Distribution by Subscription Status - Pie chart
    10. Purchase Amount by Category with Discount Applied - Boxplot

KEY INSIGHTS:-
    1. Males spend more in every category, while females show steadier spending patterns.
    2. Teens spend unpredictably, whereas Seniors show low and stable spending.
    3. Male customers drive higher overall spending, revealing an opportunity to better engage female shoppers.
    4. Seasonal spending stays consistent, with only a slight rise in the Fall.
    5. Clothing leads across all seasons, Accessories stay steady, Footwear varies slightly, and Outerwear stays lowest.
    6. Illinois shows the highest spending—especially in Outerwear and Accessories—while Clothing remains stable across states.
    7. Clothing is the most purchased category, followed by Accessories, then Footwear, with Outerwear last.
    8. Sizes S and XL generate the highest spending, while Size L performs the weakest.
    9. Most revenue comes from non-subscribed customers, signaling a need to improve subscriber engagement.
    10. Discounts show little impact on purchase amounts across categories.

CONCLUSION:-
    Customers show stable spending patterns across seasons, locations, and discount conditions, with strong dominance in Clothing purchases and higher spending from males, teens, and non-subscribed buyers; overall, the data reveals clear demographic and category-based preferences but no meaningful impact from discounts, highlighting opportunities to enhance subscription value and target lower-performing segments like females, seniors, Outerwear, and Size L buyers.

FUTURE RECOMMENDATION:-
    1. Use gender-specific marketing to boost female engagement while maintaining male spending.
    2. Apply age-focused promotions—trend deals for teens, value bundles for adults and seniors.
    3. Strengthen Fall-season campaigns and keep steady promotions in other seasons.
    4. Prioritize Clothing and Accessories inventory; limit Outerwear stock.
    5. Adjust inventory and marketing by location to match state-wise demand.
    6. Increase availability of high-demand sizes (S & XL) and review issues with size L.
    7. Improve subscription benefits to convert non-subscribed customers.
    8. Reduce reliance on discounts since they don’t significantly change spending behavior.
    
    








