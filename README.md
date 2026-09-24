# **Seattle Airbnb Data Analysis & Tableau Dashboard**

An end-to-end data visualization project exploring Airbnb listing prices, revenue trends, and spatial distribution across Seattle using Tableau Public.

**[View Live Interactive Tableau Dashboard](https://public.tableau.com/views/fullproject_17881553465990/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**


_**Project Overview**_

This project analyzes the Seattle Airbnb market to identify pricing dynamics, listing distribution, and revenue seasonality. By breaking down listings by bedroom counts and zipcodes, property owners and real estate investors can make data-driven decisions on listing strategies and location investments[cite: 3].


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


_**Tools & Technologies**_

- **BI / Visualization:** Tableau Public[cite: 3]
- **Data Processing:** SQL / Excel (Data Cleaning & Aggregation)[cite: 1, 2]
- **Geospatial Mapping:** OpenStreetMap / Mapbox integration in Tableau[cite: 3]


_**Repository Structure**_
```text
├── data/
│   ├── raw_airbnb_listings.csv     # Raw dataset
│   └── cleaned_airbnb_data.csv     # Processed dataset
├── Tableau/
│   └── Seattle_Airbnb_Dashboard.twbx  # Tableau Packaged Workbook
└── README.md                       # Project documentation
