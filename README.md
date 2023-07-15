# Project: Modelling the Impact of Vaccination Rates on the Transmission Dynamics of the Coronavirus using Epidemological models

This project intends to predict the effect of vaccination rates on the dynamics of coronavirus transmission while taking into account the virus's rate of reproduction and the rate of decreasing instances. The objective is to find out how different levels of vaccine coverage can affect how the virus spreads and help understand how government policies affected the impact of COVID-19 across various regions.

## Project Plan:

### Data Gathering:

- Obtain data from Google data sources on COVID-19, such as Google COVID-19 Mobility Reports, [Google Trends](https://trends.google.com), and [Google COVID-19 Open Data Repository](https://health.google.com/covid-19/open-data/).
- Collect data from online data resources, such as government health agencies, research institutions, and publicly available datasets.
- Ensure data includes information on coronavirus cases, vaccination rates, hospitalizations, deaths, decline rates, reproduction rates, and various countries including Nigeria,  South Africa, United States, United Kingdom, Canada, Australia, New Zealand, Germany, France, China, Saudi Arabia etc, Brazil and Argentina. The idea is to gather data for at least, two countries per continent.

#### Government Policies Collected
The following are various government policies implemented during the pandemic to reduce the adverse impact of COVID-19, across specific countries of interest:

- United Kingdom of Great Britain and Northern Ireland:
1. Lockdowns: The UK implemented several lockdowns throughout the pandemic. The first lockdown was implemented on March 23, 2020. The lockdowns helped to reduce the spread of the virus by limiting social contact and reducing the number of people who were infected (https://www.bmj.com/content/369/bmj.m1937).

2. Vaccination campaigns: The UK began its vaccination campaign in December 2020. The vaccination campaign has been successful in reducing the number of hospitalizations and deaths due to COVID-19 (https://www.frontiersin.org/articles/10.3389/fpos.2021.624068/full).

- United States of America:
1. Travel restrictions and entry bans were imposed on certain countries. The first travel restrictions were imposed on China on January 31, 2020 (https://crsreports.congress.gov/product/pdf/R/R46606) . Later, travel restrictions were extended to other countries such as Iran and Europe (https://www.hks.harvard.edu/faculty-research/policy-topics/public-leadership-management/how-covid-19-has-changed-public-policy). These restrictions helped to slow down the spread of the virus by limiting the number of people entering the country from high-risk areas.

2. Lockdown measures and stay-at-home orders were implemented in various states. The first stay-at-home order was issued by California on March 19, 2020 (https://www.census.gov/library/stories/2021/03/initial-impact-covid-19-on-united-states-economy-more-widespread-than-on-mortality.html). Other states followed suit and implemented similar measures. These measures helped to reduce the number of people who were infected with the virus by limiting social interactions.

3. Mandated use of face masks in public places. The Centers for Disease Control and Prevention (CDC) recommended the use of face masks in public places on April 3, 2020 (https://www.cfr.org/report/pandemic-preparedness-lessons-COVID-19/recommendations/). This policy helped to reduce the spread of the virus by limiting respiratory droplets that could transmit the virus.

4. The Coronavirus Aid, Relief, and Economic Security (CARES) Act was signed into law on March 27, 2020. The CARES Act provided financial assistance to individuals and businesses affected by the pandemic. The act included provisions such as direct payments to individuals, expanded unemployment benefits, and loans for small businesses. The CARES Act helped to mitigate the economic impact of the pandemic.

- Nigeria:
1. The closure of schools was implemented on March 19, 2020 (https://pubdocs.worldbank.org/en/961791611161231868/pdf/COVID-19-and-Welfare-in-Nigeria-New-Evidence-for-Policy-October-2020.pdf). This policy helped to reduce the spread of the virus by limiting social interactions.

2. The lockdown measures were implemented in various states. The first lockdown was implemented in Lagos, Abuja, and Ogun on March 30, 2020 (https://www.brookings.edu/articles/understanding-the-impact-of-the-covid-19-outbreak-on-the-nigerian-economy/). Other states followed suit and implemented similar measures. These measures helped to reduce the number of people who were infected with the virus by limiting social interactions.

3. The Central Bank of Nigeria (CBN) intervention funds were implemented to mitigate the economic impact of the pandemic. The CBN provided intervention funds for households and businesses affected by the pandemic (https://pubdocs.worldbank.org/en/961791611161231868/pdf/COVID-19-and-Welfare-in-Nigeria-New-Evidence-for-Policy-October-2020.pdf).

- South Africa 
1. Conducted widespread testing and established testing centers: South Africa implemented a comprehensive testing strategy that included both public and private testing centers. The country also implemented a contact tracing program to identify people who may have been exposed to the virus. The testing strategy was implemented in March 2020 (https://www.gov.za/covid-19/resources/regulations-and-guidelines-coronavirus-covid-19).

2. Rolled out vaccination campaigns and established vaccination sites: South Africa began its vaccination campaign in February 2021. The country has established vaccination sites across the country to ensure that people have access to the vaccine (https://www.gov.za/covid-19/about/transitional).

3. Provided financial relief and support to individuals and businesses: South Africa implemented several measures to provide financial relief and support to individuals and businesses affected by the pandemic. These measures included tax relief, loan guarantees, and social grants. The measures were implemented in March 2020 https://www.csis.org/analysis/south-africas-bold-response-covid-19-pandemic.

4. South Africa's COVID-19 policy allows 21 land borders to remain open and fully operational, while 32 land borders will continue to stay closed. The Cabinet member responsible for Home Affairs has the authority to decide on the opening and closing of any further Ports of Entry (https://www.gov.za/covid-19/about/transitional).

The policies mentioned above were similarly implemented in other countries of focus. For example, many countries around the world implemented lockdowns to reduce the spread of the virus. Similarly, vaccination campaigns were launched in many countries to reduce the number of hospitalizations and deaths due to COVID-19. Financial support was also provided to individuals and businesses affected by the pandemic in many countries.

#### Additional Notes
There are several reasons why lockdown and social distancing policies did not work in Nigeria during the pandemic. One reason is that many people in Nigeria rely on the informal sector for their livelihoods. These people were unable to work during the lockdown, which led to economic hardship (https://theconversation.com/nigerias-pandemic-lockdown-measures-were-hard-on-informal-workers-177466). Another reason is that many people in Nigeria live in crowded conditions, which made it difficult to practice social distancing (https://pubdocs.worldbank.org/en/961791611161231868/pdf/COVID-19-and-Welfare-in-Nigeria-New-Evidence-for-Policy-October-2020.pdf). Additionally, there was a lack of trust in the government’s ability to manage the pandemic(https://www.bbc.com/news/world-52526923).


### Data Preprocessing:

- Clean the collected data by handling missing values, outliers, and inconsistencies.
- Perform data scaling and normalization techniques to make variables comparable.
- Explore data distributions and correlations to gain insights into the dataset.

### Exploratory Data Analysis:

- Analyze the dataset based on various factors, including hospitalization rate, death rate, decline rate, reproduction rate, and policies developed across the various regions.
- Visualize data through graphs, charts, and maps to identify patterns and trends.
- Calculate descriptive statistics to summarize key aspects of the spread of COVID-19.

### Model Selection:

- Determine the appropriate epidemiological model for the analysis, such as compartmental models (e.g., SIR, SEIR) or agent-based models.
- Consider the strengths, limitations, and assumptions of different models.
- Discuss the selected model and its justification with you, I will be providing additional information on the model's theoretical foundations, equations, and parameters.

### Model Implementation:

- Implement the chosen epidemiological model using a suitable programming language, such as Python.
- Define the model's equations, initial conditions, and parameters based on the dataset and relevant literature.
- Validate the model by comparing its outputs to real-world data and existing epidemiological studies.

### Model Calibration and Parameter Estimation:

- Calibrate the model's parameters using optimization techniques or statistical methods.
- Fit the model to observed data to ensure it accurately represents the transmission dynamics of the coronavirus.
- Document the calibration process, including the chosen optimization algorithm and the criteria for parameter estimation.

### Model Simulation and Analysis:

- Run simulations with different vaccination rate scenarios to assess their impact on the transmission dynamics.
- Calculate relevant metrics, such as effective reproduction number, herd immunity threshold, and reduction in hospitalizations and deaths.
- Analyze the simulation results to evaluate the effectiveness of various vaccination policies and identify optimal strategies.

### Interpretation and Reporting:

- Interpret the findings from the model simulations and analysis.
- Discuss the implications of the results, including the relationship between vaccination rates and transmission dynamics.
- Provide recommendations for effective policies based on the observed outcomes.
- Document the entire process in the dissertation, including details on data sources, model equations, parameter estimation methods, and limitations of the project.

## Project Challenges

This section will account for chanllenges met during the implementation of this project.

Contents on this plan are subject to change as I move forward on the project.
