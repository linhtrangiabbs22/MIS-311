<img width="700" height="466" alt="4df8f9b5142a98a4a98749bcafa3dbe5" src="https://github.com/user-attachments/assets/b1cbfb37-3fe5-4f51-bfa8-8792c9a4cec8" />

# 1. Data Overview
Size: The dataset consists of 207 rows in total (including 1 header row and 206 data rows for countries/territories) and 6 columns.

Data Sources: Historical baselines are sourced from the World Bank, combined with international tourism statistics and predictive models for recent years. 

Context/Background: The dataset tracks international tourist arrivals to monitor the
recovery and growth trends of global tourism over recent years (2022, 2023) and provides forecasts for 2024 against historical benchmarks.
 

# 2. Data Cleaning

## Identify missing values and decide how to handle these missing values: 

The dataset was reviewed to identify incomplete or empty values using Excel data cleaning tools. Records containing missing information were cleaned and adjusted to improve the accuracy and consistency of the dataset before conducting further analysis. 

## Identify any duplicate rows and remove duplicate rows if necessary: 
The dataset was also examined for duplicate entries to avoid repeated information. Duplicate records were removed to ensure each country would only appear once.

# 3. Descriptive Statistics
<img width="701" height="157" alt="Descriptive_Statistics png" src="https://github.com/user-attachments/assets/c20f1979-d26c-4c18-8bc9-aa4aacf54531" />
Table 1: Descriptive Statistic Result



Across all three years (2022–2024), the descriptive statistics reveal a highly unequal and right-skewed distribution in global tourist arrivals. Due to the massive gaps between the minimums and maximums each year, the Mean is consistently inflated by a few mega-destinations. For instance, in 2024, the Mean is 24.10 million while the Median is only 16.80 million, meaning 66% of the countries actually perform below average. This pattern of high dispersion is further confirmed by the large Standard Deviations (around 20 million each year). Therefore, to avoid distortion from these extreme outliers, the Median should be used as the primary benchmark to evaluate typical country performance across the entire 2022–2024 period. 


<img width="269" height="155" alt="Top10_Countries_2024 png" src="https://github.com/user-attachments/assets/78c63ee3-d8f7-4fad-bd3b-53a5d199c779" />

Figure 1: Top 10 predictive Countries in 2024

## Insight 1 
Western Europe's Great Success in 2024: France and Spain led the list because global travel returned strongly after the pandemic, combined with their rich culture and smart timing. France became the top destination due to the massive crowds from the Paris 2024 Olympics, while Spain attracted millions with its warm weather and easy visas for remote workers. This shows that hosting huge events and having flexible travel rules are the best ways for top countries to stay popular and beat the competition. 

<img width="287" height="183" alt="Tourist_Arrivals_2022_2023 png" src="https://github.com/user-attachments/assets/1b2233e3-9ee3-4382-96e7-5aec0cb4c944" />

Figure 2: Comparison Tourist Arrivals between 2022 and 2023

## Insight 2
Mixed Travel Recovery in 2023: While Western destinations like France and Spain grew quickly because they fully opened their borders to international tourists early, countries like China and Turkey saw sharp drops due to strict pandemic delays and natural disasters. Specifically, China's slow post-Zero-COVID border reopening kept numbers low, while Turkey's tragic February 2023 earthquake deeply hurt traveler confidence. For businesses, this meant they had to quickly shift their focus away from struggling regions and invest more in the booming Western markets. 

# Conclusion 
In conclusion, the data shows that global tourism recovered in very different ways between 2022 and 2023. Western Europe, especially France and Spain, stayed on top because they opened their borders early, and this success is predicted to continue into 2024 with big events like the Paris Olympics. On the other hand, countries like China and Turkey faced sudden drops due to slow border openings and natural disasters, showing how sensitive the travel industry is to unexpected challenges. For travel businesses, these changes mean they must remain flexible and quickly shift their focus to safe, fast-growing markets to stay successful. 
