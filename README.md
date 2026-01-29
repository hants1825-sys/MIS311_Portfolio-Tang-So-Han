# MIS-311
## Introduction to Business Analytics
### *Data Analysis and Insight*
## Data Overview
- Source of data: Electric Vehicle Population Data
- Washington State Department of Licensing (DOL); Statistical Organizations.
- Number of rows: 203 rows
- Number of columns: 6 columns
- The context: The Electric Vehicle Registration data for Washington State provides insight into how the Electric Vehicle adoption is spreading throughout the state. In addition to providing information on how many Electric Vehicles there are in each year and the various makes and models of Electric Vehicles, it also gives a general view of which brands are gaining dominance (such as Tesla), what years are growing the most rapidly and where (urban vs. rural) the most growth is happening. This type of information is vital for local governments that are trying to determine where to put charging infrastructure, companies that are determining what types of EV market strategies to pursue, energy providers that are trying to plan for future demand and consumers that are considering switching to an Electric Vehicle. The trends of sustainable transportation, the impact on the environment and the level of penetration of new Electric Vehicle technology into daily living are all important factors to be considered.
## Data Cleaning

- Handling Missing Values: Detected 14 missing entries in location-based columns. These records were excluded from the analysis as they represent a negligible portion of the dataset and would not impact the overall trend.
- Vehicle Identification Number: Missing 4 values (A70, A74, A79, A93)
- City: Missing 2 values (B24, B31)
- Make: Missing 2 values (E16, E97)
- Model: Missing 1 value (F59)
- Handling Duplicates: Identified and removed 3 duplicate records to ensure data integrity and avoid overcounting specific vehicles.

=> After deletion, there are 189 rows and 6 columns left.
## Descriptive Statistics

<img width="567" height="550" alt="image" src="https://github.com/user-attachments/assets/53ceba41-c869-42e6-b368-1c0a8931e618" />

Based on the provided dataset of 188 vehicles, the electric vehicle (EV) market exhibits a high degree of brand concentration, with Tesla maintaining a dominant market share of approximately 39.4% (74 units). This leadership, followed by established players like Nissan (38 units) and Kia (19 units), underscores a consumer preference for brands with mature EV infrastructures. Furthermore, the aggregate mean model year of 2018.7 indicates a relatively modern fleet, while the recent emergence of 2024 models from diverse manufacturers such as Lexus and Mercedes-Benz reflects an accelerating trend toward electrification across both the mass-market and luxury automotive sectors.

- **Insight 1: Chronological Growth and Diversification of the Electric Vehicle Fleet**. The data illustrates a dual trend of exponential volume growth and expanding brand portfolio over the last decade
<img width="839" height="512" alt="image" src="https://github.com/user-attachments/assets/407fdf34-b0f3-4aaa-87fa-5691196e9a3e" />

The bar chart illustrates a significant surge in vehicle acquisition between 2018 and 2020, accounting for approximately 45.7% of the total fleet (86 out of 188 units). While adoption peaked in 2020 with 31 units (16.5%), there was a noticeable contraction in 2021, followed by a steady recovery through 2023 and 2024, each contributing 14 units (7.4%). This trend suggests that while the market experienced a period of rapid expansion in the late 2010s, it is currently entering a new phase of sustained growth with the introduction of latest-generation models.
- **Insight 2: Competitive Landscape and Manufacturer Dominance**. 
<img width="745" height="454" alt="image" src="https://github.com/user-attachments/assets/85f09c69-d8f2-4d22-9499-1a6dd2422bce" />

The chart shows that Tesla maintains an overwhelming lead in the market with 74 units, nearly doubling the volume of its closest competitor, Nissan (38 units). This significant gap, followed by a long tail of manufacturers like Kia (19 units) and BMW (15 units), highlights a highly concentrated market structure dominated by early EV specialists. However, the presence of over 20 different brands, including luxury and emerging makers like Rivian, Lucid, and Mercedes-Benz, indicates a rapidly diversifying ecosystem where traditional automakers are steadily expanding their footprint.
