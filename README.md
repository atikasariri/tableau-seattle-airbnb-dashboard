# **Seattle Airbnb Data Analysis & Tableau Dashboard**

An end-to-end data analytics project exploring Airbnb listing prices, spatial distribution, bedroom supply, and revenue seasonality across Seattle. This project combines data processing in Google Sheets with interactive visual analytics in Tableau Public.

_**Preview Dashboard**_

<p align="center">
<img width="1366" height="636" alt="Dashboard preview" src="https://github.com/user-attachments/assets/5d251b75-7c6a-4b06-94a0-311a6796f590" width="800">
</p>


_**Project Links:**_

- **[Google Sheets Data Processing](https://docs.google.com/spreadsheets/d/1RpL9e9Sbf0yFHJwcYCS00o_C8AWtWxPi/edit?usp=sharing&ouid=114390769350717534247&rtpof=true&sd=true)**
- **[View Live Interactive Tableau Dashboard](https://public.tableau.com/views/fullproject_17881553465990/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**


_**Data Pipeline & Workflow**_

1. **Data Cleaning & Preparation :**
   - Cleaned raw listing records and calendar booking datasets.
   - Formatted currency values, addressed missing values, and created aggregated summary fields for downstream modeling.
   - Access the working calculations and cleaned tables via the [Google Sheets Spreadsheet](https://docs.google.com/spreadsheets/d/1RpL9e9Sbf0yFHJwcYCS00o_C8AWtWxPi/edit?usp=sharing&ouid=114390769350717534247&rtpof=true&sd=true).

2. **Visual Analytics & Dashboarding :**
   - Connected processed data to Tableau to build interactive map layers, dynamic bar charts, and trend lines[cite: 3].

_**Project Overview**_

The goal of this project is to provide actionable market insights for real estate investors and Airbnb hosts looking to optimize their pricing strategies and property locations in Seattle.
By preparing raw calendar and listing data in Google Sheets and visualizing it through an interactive Tableau dashboard, the analysis highlights key drivers of rental revenue, spatial pricing variations, and seasonal demand[cite: 3].


_**Key Dashboard Features & Insights**_

**1. Average Price per Bedroom (Bar Chart)**
- Evaluates how listing prices scale with the number of bedrooms[cite: 3].
- **Average Prices:**
- 1 Bedroom: **$96.2**[cite: 3]
- 2 Bedrooms: **$175.4**[cite: 3]
- 3 Bedrooms: **$249.7**[cite: 3]
- 4 Bedrooms: **$315.4**[cite: 3]
- 5 Bedrooms: **$450.0**[cite: 3]
- 6 Bedrooms: **$584.8**[cite: 3]

**2. Distinct Count per Bedroom Listings (Summary Table)**
- Displays the supply distribution of listings in Seattle[cite: 3].
- **1-Bedroom listings** dominate the market with **1,811 listings**, followed by 2-bedroom units (**483 listings**)[cite: 3].
- Larger homes (5–6 bedrooms) are extremely scarce, with only **25 total listings** combined[cite: 3].

**3. Price per Zipcode (Map & Bar Chart Visualizations)**
- Map and ranking bar charts illustrate the location-based price variation across Seattle[cite: 3].
- Higher average prices are heavily concentrated around downtown zipcodes (e.g., **98101 at $166.7**), whereas peripheral areas (e.g., **98106 at $82.1**) offer lower pricing[cite: 3].

**4. Revenue for Year (Line Chart)**
- Tracks weekly aggregate listing prices and revenue seasonality throughout 2016[cite: 3].
- Shows a sharp rise in revenue starting from February through the spring and summer peak months, stabilizing towards the end of the year[cite: 3].


_**Repository Structure**_
```text
├── data/
│   └── raw_airbnb_data.csv          # Raw input dataset
├── Tableau/
│   └── Seattle_Airbnb_Dashboard.twbx # Tableau Packaged Workbook
├── LINKS.md                         # Direct links to external resources
└── README.md                        # Project documentation
