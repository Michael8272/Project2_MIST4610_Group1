# Group 1 MIST 4610 Project 2
Team Name: Group 1

Group Members:
1. Connor Hatfield [@connorhat4](url)
2. Jordan Peterkin [@jpeterkin29](url)
3. Michael Espinoza [@Michael8272](url)
4. Naysa Rokkala [@naysarokk](url)

# Dataset Description:

The "Air Quality" dataset, sourced from the public database (https://catalog.data.gov/dataset/air-quality), contains 18,025 rows and 12 columns, providing detailed information about air quality indicators and measurements. Key columns include a unique identifier (Unique ID), indicator ID, and the name of the air quality indicator (e.g., "Fine particles (PM 2.5)" or "Boiler Emissions - Total SO2 Emissions"). Measurements are described by type (Measure) and unit (Measure Info), such as "Mean" or "Number per km²" with corresponding units like "mcg/m³." Geographic information is detailed through region types (Geo Type Name), spatial identifiers (Geo Join ID), and place names (Geo Place Name). The dataset includes temporal attributes, such as a descriptive time period (Time Period) and precise start dates (Start_Date), alongside the recorded air quality value (Data Value). The data integrates temporal, spatial, and environmental metrics, covering regions and periods like "Annual Average 2012" or "Summer 2022," and is useful for analyzing pollution trends, public health impacts, and environmental policy development.

# Our 2 Questions and Why they are Important:
1. How do the average levels of fine particulate matter (PM 2.5) vary across different geographic areas over time?

This question is critical due to the significant social and health implications of fine particulate matter (PM 2.5). PM 2.5 is a key air pollutant that poses severe risks to human health, including respiratory and cardiovascular diseases, particularly in vulnerable populations such as children and the elderly. Understanding its variation across geographic areas allows policymakers and public health officials to target high-risk regions with interventions, such as stricter regulations or public health campaigns. Economically, reducing PM 2.5 levels can decrease healthcare costs associated with treating pollution-related illnesses and improve workforce productivity. Culturally, this question addresses environmental justice, as historically underserved communities often bear a disproportionate burden of air pollution. This question is tied directly to the dataset, which provides geographic, temporal, and measurement-specific data for PM 2.5 levels, enabling analysis of trends and disparities.

2. Is there a relationship between specific emission types (e.g., SO2 emissions) and air quality indicators like PM 2.5 levels across different geographic areas?

This question is important as it investigates the causal or correlative factors affecting air quality, particularly the role of specific emissions like sulfur dioxide (SO2). SO2 is a precursor to secondary particulate matter, such as PM 2.5, which exacerbates air quality issues. Exploring this relationship can inform policy and regulatory frameworks, guiding industries to adopt cleaner technologies or reduce emissions. This has significant economic implications, as improving air quality can reduce public health expenditures and mitigate the long-term costs of environmental degradation. Additionally, it aligns with global sustainability goals, fostering a transition to cleaner energy sources and promoting environmental stewardship. The dataset is well-suited for this analysis, as it includes detailed emissions data (e.g., SO2) and air quality measurements (e.g., PM 2.5), categorized by geographic areas and time periods, enabling the study of spatial and temporal patterns.

# Manipulations Applied as a Part of our Analysis:
1. How do the average levels of fine particulate matter (PM 2.5) vary across different geographic areas over time?

Manipulations: Due to the extensive air quality studies conducted across various parts of NYC, several filters were applied to ensure the data was consistent and comparable across districts. One key filter included selecting only studies that calculated the annual average micrograms per cubic meter, excluding seasonal studies that could skew the results by focusing on data from only a few months. Additionally, the data was restricted to borough-level data and focused exclusively on PM2.5 levels, ignoring other forms of pollution to maintain a clear and specific scope.


# Analysis and Results:
1. How do the average levels of fine particulate matter (PM 2.5) vary across different geographic areas over time?

![Fine Particles Over Time by Borough](https://github.com/user-attachments/assets/cff11d21-d88c-45e0-a5b4-f398577c1cf7)

Analysis: New York City can be divided into five major governmental districts (AKA boroughs). This visualization displays the fine particulate matter pollution in the five boroughs of NYC by measuring the average micrograms per cubic meter of air. The overall trend shows that from 2008 to 2022, the pollution levels in all boroughs have steadily decreased. According to the article "Environmental Initiatives" from the NYCdata website, NYC implemented PlaNYC to combat the high levels of pollution in the city. The downward trend of pollution among all five of the boroughs in the city shows a clear correlation between the efforts of the program and overall air quality. Manhattan consistently experienced the highest pollution levels during this period, while Staten Island enjoyed the cleanest air. The average pollution levels have decreased by 43.6% in Queens, 44.4% in Manhattan, 44.8% in Brooklyn, 45% in The Bronx, and 46.9% in Staten Island. The visualization contains many peaks and valleys throughout the years, but the one that occurred during 2020 can likely be attributed to the COVID-19 pandemic. Pollution levels took a sharp fall from 2019 to 2020, then quickly rose again in 2021. People staying indoors resulted in lower usage of vehicles and other polluting devices, which likely explains why fine particle pollution levels rose once people started going outside again. A notable observation is that, for the majority of the graph, the lines representing the boroughs remain distinct and do not intersect. However, in 2020, there is a clear overlap among The Bronx, Brooklyn, and Queens. Certain boroughs, being more industrialized and densely populated, typically experience higher pollution levels. However, with much of life coming to a standstill for a significant portion of 2020, the pollution levels in these three boroughs, which were already relatively close, ultimately converged to equally low levels.

2. Is there a relationship between specific emission types (e.g., SO2 emissions) and air quality indicators like PM 2.5 levels across different geographic areas?


# Tableau Packaged Workbook:




