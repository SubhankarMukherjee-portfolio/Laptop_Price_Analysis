# Laptop Price Analysis (By using Python – Jupyter Notebook)
This project explores a comprehensive dataset of laptops, analyzing their specifications, pricing, and features across multiple brands and models. The dataset includes key attributes such as brand, type, screen size, RAM, storage, CPU, GPU, operating system, display features, and price (in Euros). The data was cleaned, transformed, and analyzed using Python in a Jupyter Notebook environment. The goal of the analysis was to uncover pricing trends, performance-to-price relationships, and feature-based value metrics. Techniques like correlation analysis, statistical testing, and machine learning (Random Forest Regression & Classification) were used to predict laptop prices and identify the most influential features affecting cost.

## Dataset used
Dataset = "https://github.com/SubhankarMukherjee-portfolio/Laptop_Price_Analysis/blob/main/laptop_prices.csv"

## Objectives of the project
1) Perform exploratory data analysis (EDA) on laptop specifications and pricing
2) Identify patterns and trends across brands, laptop types, and hardware features
3) Analyze the impact of components (RAM, storage, CPU, GPU, etc.) on pricing
4) Evaluate value-for-money configurations based on performance and cost
5) Apply machine learning models to predict laptop prices and classify price categories
6) Visualize key insights using Python and data visualization libraries such as Matplotlib and Seaborn

## Questions solved
1) What is the average laptop price by brand?
2) What is the average laptop price by laptop type (e.g., Gaming, Ultrabook, Netbook)?
3) How does the combination of brand and type influence average price?
4) Which primary storage capacities offer the best value for money?
5) What is the impact of Retina display on laptop pricing?
6) Which GPU brands are most common in high-end laptops?
7) How does CPU brand affect laptop pricing and market share?
8) What is the correlation between screen size and laptop price?
9) What is the relationship between laptop weight and cost?
10) How does CPU frequency relate to price variation?
11) What is the combined effect of RAM and storage on laptop pricing?
12) How do Retina and IPS displays relate to screen resolution?
13) Which OS and laptop type combinations are most common in premium laptops?
14) What is the pricing difference between touchscreen and non-touchscreen laptops?
15) Which RAM and storage configurations deliver the best value per euro?
16) How accurately can laptop prices be predicted using Random Forest Regression?
17) How well do predicted laptop prices match actual prices?
18) What are the most influential features in predicting laptop price?
19) How accurately can laptops be classified into price categories using machine learning?
    
## Libraries Used
The following Python libraries were used during the data cleaning, exploration, visualization, and analysis phases:
1) NumPy – for performing numerical computations and handling array operations
2) Pandas – for reading the dataset and performing data manipulation and analysis
3) Matplotlib – for creating basic plots and data visualizations
4) Seaborn – for advanced and statistical visualizations with enhanced styling
5) Scikit-learn (sklearn) – for implementing machine learning models and evaluating their performance

## Python file (Jupyter Notebook)
Python File =  "https://github.com/SubhankarMukherjee-portfolio/Laptop_Price_Analysis/blob/main/Laptop%20Price%20Analysis%20_%20ML%20_%20FA%20_%20DA%20Project.ipynb"


## PowerPoint presentation
PPT = "https://github.com/SubhankarMukherjee-portfolio/Laptop_Price_Analysis/blob/main/Laptop_Price_Analysis_Presentation.pptx"

## PDF File of PowerPoint presentation
PDF file = "https://github.com/SubhankarMukherjee-portfolio/Laptop_Price_Analysis/blob/main/Laptop_Price_Analysis_Presentation.pdf"

## Final Observations & Storyline
1) Brand & Type Positioning:
Razer leads the premium laptop segment with an average price of €3346.14, far surpassing other brands, indicating its strong focus on high-performance gaming. Conversely, Mediacom, Vero, and Chuwi offer the most affordable options, all priced under €320. Among laptop types, Workstations and Gaming laptops are the costliest due to specialized hardware, while Netbooks and Notebooks dominate the budget market. This sharp segmentation reflects distinct consumer tiers and targeted pricing strategies.
2) Specs & Value Analysis:
RAM is the most influential driver of price, accounting for 56% importance in the Random Forest model. Laptops with 8GB RAM and 2TB storage offer the best value per euro (score: 3.81), showing that balanced configurations outperform raw specs in price efficiency. Interestingly, storage capacity shows a slight negative correlation with price, with lower-capacity models (16–64 GB) offering the highest value and 240 GB models showing an unexpected price spike.
3) Feature Impact on Pricing:
Display and input features strongly affect pricing. Retina display laptops average €1657.85, significantly more than non-Retina models (€1127.90), supported by statistical testing (t = 3.569, p = 0.0024). Similarly, touchscreen laptops average €1453.12, compared to €1079.94 for non-touch versions (t = 6.149, p = 0.0). These features drive up costs due to higher component and manufacturing expenses, signaling a clear economic trade-off between utility and affordability.
4) Market Share & Component Trends:
Intel dominates both CPU and GPU markets in high-end laptops, with 95%+ share in CPUs and over 47% GPU share, closely followed by Nvidia (46.8%). AMD remains a budget option with just 5% GPU and limited CPU presence, reflected in a lower average price of €560.99 versus €1163.73 for Intel. Despite their minimal presence, AMD-powered laptops cater to cost-sensitive segments, showing economic diversity in consumer demand.
5) Predictive Insights & Economic Implications:
The Random Forest Regression model achieves R² = 0.85 and an MSE of ~€78,798, accurately predicting price from features like RAM, CPU frequency, and weight. Classification models also performed well with 82.25% accuracy. Weak correlations with screen size and weight suggest these physical traits have limited pricing power. Overall, the data indicates a value-driven market where internal performance specs (especially RAM) and premium features justify higher prices, while consumers seeking affordability should prioritize balanced mid-range configurations over high-end branding.


