# EuroTrip Insights 

The **Tourist Travel Modes** in Europe dataset provides insights into the travel behaviors of tourists visiting various European destinations. The dataset includes information on travel duration, transport modes, costs, accommodation type , and seasonal trends. This analysis aims to uncover patterns in tourism, inform budget-friendly travel decisions, and help businesses and Tourists optimise their services.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Overview 
 https://www.kaggle.com/datasets/ashaychoudhary/tourist-travel-modes-in-europe-dataset/data 
* Rows: 1000
* Columns: 10
* No missing values detected.
* Data types:
  *  **Categorical**: Country_Visited, City_Visited, Mode_of_Travel, Accommodation_Type, Main_Purpose, Season_of_Visit
  * **Numerical**: Travel_Duration_Days, Number_of_Companions, Total_Travel_Cost

## Columns Descriptions 

| Column Name            | Description                                      |
|------------------------|--------------------------------------------------|
| Tourist_ID            | Unique identifier for tourists                   |
| Country_Visited       | The European country visited                     |
| City_Visited          | The city visited                                 |
| Mode_of_Travel        | Mode of transport used (e.g., Train, Bus, Flight, Car, Bicycle) |
| Travel_Duration_Days  | Duration of stay in days                         |
| Number_of_Companions  | Number of people traveling together              |
| Total_Travel_Cost     | Total cost of travel in euros                    |
| Accommodation_Type    | Type of accommodation (e.g., Hotel, Hostel, Airbnb, Camping) |
| Main_Purpose         | Main purpose of travel (e.g., Leisure, Business, Family Visit) |
| Season_of_Visit       | Season of travel (Spring, Summer, Fall, Winter)  |


## Objective of Dateset 
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
    * Provide insights for travelers to plan budget-friendly trips. H8
    * Help transportation and accommodation providers improve their offerings based on demand trends.


## Hypotheses and Validation
This project aims to analyse Eurpoean tourist travel patterns, focusing on cost, transport modes and seasonal trends. The following hypotheses will be tested: 

(Talk to conor and haf and base hypotheses on what they have coded and we can further update the readme)

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

| Business Requirement                                | Visualization Method                                  |
|-----------------------------------------------------|------------------------------------------------------|
| Identify most visited destinations                 | Bar chart of top cities/countries                   |
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


## Dashboard Design
* **Main Dashboard:** Overview of travel trends (popular destionations, transport modes, seasonality)
* **Cost Analysis Page:** Breakdown of travel expenses based on season, country and travel type 
* **Transport & Accomodation Trends:** Preferred travel and lodging options for different traveller types. 
* **Interactive Filters:** Users can filter data by country, season, travel mode and purpose. 

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

## Development Roadmap
**Challenges Faced:**
* **Data Formatting Issues:** Inconsistent categorical values required cleaning. 
* **Complexity in Visualisation Selection:** Adjusted approacjes based on sights gained from EDA 

**Future Improvements:**
* **Integration of External Data:** Including economic and toursim data for enriched insights. 
* **Predictive Modelling:** Estimating future travel costs based on historical trends. 
*  **Further Skills Development:** Advancing knowledge in Power BI and advanced machine learning techniques 

## Deployment
### Heroku

* The App live link is: https://YOUR_APP_NAME.herokuapp.com/ 
* Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. From the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.


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

### Media

* Code Institute logo [CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Acknowledgements (optional)
* Hackathon Team: Mukti, Conor, Hafeezah and Tamika for contribution in data cleaning, analysis and dashboard development. 