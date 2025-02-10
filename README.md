# EuroTrip Insights 

The **EuroTrip Insights** dataset provides insights into the travel behaviors of tourists visiting various European destinations. The dataset includes information on travel duration, transport modes, costs, accommodation type , and seasonal trends. This analysis aims to uncover patterns in tourism, inform budget-friendly travel decisions, and help businesses and Tourists optimise their services.

# ![alt text](eurotravel.jpg)

## Dataset Overview 
 https://www.kaggle.com/datasets/ashaychoudhary/tourist-travel-modes-in-europe-dataset/data 
* Rows: 1000
* Columns: 10
* No missing values detected.
* Data types:
  *  **Categorical**: Country_Visited, City_Visited, Mode_of_Travel, Accommodation_Type, Main_Purpose, Season_of_Visit
  * **Numerical**: Travel_Duration_Days, Number_of_Companions, Total_Travel_Cost

## Columns Descriptions 

| Column Name           | Description                                      |
|-----------------------|--------------------------------------------------|
| Tourist_ID            | Unique identifier for tourists                   |
| Country_Visited       | The European country visited                     |
| City_Visited          | The city visited                                 |
| Mode_of_Travel        | Mode of transport used (e.g., Train, Bus, Flight, Car, Bicycle) |
| Travel_Duration_Days  | Duration of stay in days                         |
| Number_of_Companions  | Number of people traveling together              |
| Total_Travel_Cost     | Total cost of travel in euros                    |
| Accommodation_Type    | Type of accommodation (e.g., Hotel, Hostel, Airbnb, Camping) |
| Main_Purpose          | Main purpose of travel (e.g., Leisure, Business, Family Visit) |
| Season_of_Visit       | Season of travel (Spring, Summer, Fall, Winter)  |


## Objective of Dataset 
The Tourist Travel Europe Date aims to analyse travel pattern, cost, preferences of tourist visiting European countries. The primary of this dataset analysis are:

1. **Understand Tourist Behaviour**
    * Identify the most visited countries and cities in Europe 
    * Analyse the primary reason for travel (business, leisure, family visit)
    * Determine the most common modes of transportation used by travellers 

2. **Analyse Travel Cost & Spending Patterns**
    * Investigate the average cost of travel based on country, season, and travel purpose. 
    * Examine the relationship between travel duration and total cost. 
    * Identify the most expensive and budget-friendly destinations. 

3. **Study Seasonal Travel Trends**
    * Explore how travel varies across different seasons (summer, winter, etc.).
    * Assess how costs fluctuate based on seasonality.

4.  **Optimise Travel Decision-Making**
    * Provide insights for travelers to plan budget-friendly trips. 
    * Help transportation and accommodation providers improve their offerings based on demand trends.

## Hypotheses and Validation
This project aims to analyse Eurpoean tourist travel patterns, focusing on cost, transport modes and seasonal trends. The following hypotheses will be tested: 
* H1: Outlier summary for each column present in the dataset. 
**(Validation: Use box plot analysis.)**

* H2: Correlation between travel and travel duration. 
**(Validation: Scatter plot with trend line.)**

* H3: Perform regression analysis to check impact of duration on cost per day. 
**(Validation: Regression modeling.)**

* H4: Cities with higher tourist traffic show distinct travel patterns based on location. 
**(Validation: Map visualisation.)**

* H5: Travel duration and number of companions influence total travel costs. 
**(Validation: Relationship analysis.)**

* H6: Tourists traveling by flight have higher costs than other modes. 
**(Validation: Bar plot comparison.)**

* H7: Relationship between total travel cost, season, and main purpose.
**(Validation: Heatmap correlation analysis.)**

## Tableau Dashboard Overview 
Our Tableau dashboard provides an interview visualisations of travel patterns across Europe: 
* **KPI's:** Total tourist, average travel cost, top destinations.
* **Filters:** Seasonality, travel mode, cost range 
* **Charts:** Bar Charts, line graphs, heatmaps  for deep insights. 
* (link the dashboard here)

## Tableau Dashboard Screenshots 
Here are some insights from our interactive Tableau dashboard: 
- Add Image: Screenshot of Travel Cost 
- Seasonal Trends Visualisation 
- Filter Interactivity Demo 


## Project Plan
This project follows a structured analytical approach: 

1. **Data Collection & Prepareation**
    * Dataset obatined from Kaggle
    * Initial review for missing values and inconsistencies 
    * Cleaning steps: removing duplicates, standardising catergorical values, converting numerical data

2. **Exploratory Data Analysis (EDA)**
    * Summary statistics for numerical columns 
    * Identification of key trends in travel behaviour, cost and seasonal impacts 
    * Initial visualisations of correlations between travel modes, cots and accommodation types. 

3. **Data Visualsations & Insights**
    * Tableau dashboards designed for interactive analysis 
    * Python(Pandas, Matplotlib, Seaborn) used for additional insights 
    * Key findings highlighted through charts, graphs and comparative metrics 

4. **Interpretation and Recommendations**
    * Findings presented to support industry insights 
    * Budget travel suggestions for toruists 
    * Business recommendations for tourism and hospitality sectors 

## Mapping Business Requirements to Data Visualisations 
This project aligns business requirements with data visualisations methods: 

| Business Requirement     | Visualization Method    |
|-----------------------------------------------------|------------------------------------------------------|
| Identify most visited destinations  | Bar chart of top cities/countries                   |
| Analyse seasonal travel trends                     | Line graph of trips per season                      |
| Compare travel costs across transport modes        | Boxplot or bar chart                                |
| Evaluate accommodation preferences                 | Pie chart or stacked bar chart                      |
| Assess spending patterns by travel purpose         | Heatmap or scatter plot                             |


## Analysis Techniques Used
* **Descriptive Analysis:** Summary statistics to understand central tendencies in cost and duration 
* **Correlation Analysis:** Identifying relationships between trip duration, cost and travel modes 
* **Regression Analysis:** Quantifying cost impact based on travel duration and seasonality 
* **Visual Analysis:** Charts and dashboards in Tableau to communicate insights effectively 

**Challenges & Alternative Approaches**
* **Data Limitations:** Lack of addictional demographic details (e.g. age and income) required assumptions for behavioural insights. 
* **Mitigation Strategies:** External travel pricing trends were reviwed for contextual accuracy. 
* **Generative AI Tools:** Used for ideation, code structuring and optimisation in Python. 

## Ethical considerations
* **Data Privacy:** The dataset does not include personal or sensitive user data 
* **Bias & Fairness:** Ensured balanced analysis by examining all travel modes and purposes. 
* **Legal Compliance:** Used open-source data within ethical and legal boundaries 

**Communication Strategy**
* **Technical Users:** Detailed correlation charts and statistical analyses 
* **Non-Technical Users:** Clear graphs, summary insights and key takeaways 

## Unfixed Bugs
No major bugs found. However some challenges included: 
* **Data Gaps:** Limited atrributes affecting deeper segmentation analysis.
* **Visualisations Adjustments:** Some chart selections were refined post-EDA for better insights

**Knowledge Gaps &  Learning Process**
* Addressed gaps in Tableau expertise through peer feedback and online resources 
* Improved Statistical Hypothesis testing skills during analysis. 

## Main Data Analysis Libraries
The following Python libraries were used: 
| Library   | Usage                                      |
|-----------|--------------------------------------------|
| Pandas    | Data cleaning, manipulation               |
| Matplotlib| Data visualization (static charts)        |
| Seaborn   | Statistical visualization                 |
| Plotly    | Interactive charts                        |
| Tableau   | Dashboard visualization                   |


## Conclusion 
The Tourist Travel Modes in Europe dataset reveals key trends in how travelers move, spend, and experience destinations across Europe. Travel preferences vary significantly based on purpose, season, and location. Business travelers typically spend more on flights and hotels, while leisure travelers opt for budget-friendly options like Airbnb and hostels. Seasonal trends heavily influence costs, with summer and winter being the most expensive travel periods. 

Additionally, longer trips tend to increase overall costs, though travelers may benefit from discounts on accommodations and travel packages.

* This study provides the following insights into the actors involved:
    * Travelers may therefore choose wisely where they would want their trip: cheap destinations during off-peak seasons.
    * Marketing, pricing strategies, and service development for the tourism sector may be improved according to traveler behavior.
    * Transporting and accommodation service providers may be able to adjust their offerings accordingly based on the needs of different tourist segments.

Future work can extend further predictive modeling toward estimating travel costs related to various influential factors. The incorporation of external data such as flight prices, economic conditions, or local events might significantly increase the accuracy of travel forecast trends.

Overall, the project serves as a base to understand European tourism trends and offers practical recommendations for which travelers and personnel within the industry can benefit.


## Credits 
**Content**
* Data sourced from [Tourist Travel Modes in Europe](https://www.kaggle.com/datasets/ashaychoudhary/tourist-travel-modes-in-europe-dataset/data)
* Research methodology inspired by online case studies on travel analytics. 

## Media

![alt text](https://www.logoku.com/image/c/data/items1/1726852370_logokucom_eurotravel.jpg)

## Acknowledgements
* Hackathon Team: Mukti, Conor, Hafeezah and Tamika for contribution in data cleaning, analysis and dashboard development. Thank You Neil and Vasi for their help on resolving VS code application and Git related issues.