🎬 Netflix Content Analytics Dashboard
📌 Project Overview

The Netflix Content Analytics Dashboard is an interactive Power BI data analytics project designed to explore and understand Netflix's content catalog.

The dashboard transforms raw Netflix catalog data into meaningful visual insights covering:

🎥 Movies vs TV Shows
📅 Release-year trends
⭐ Ratings and audience categories
🌍 Country-wise content distribution
⏱️ Movie and TV Show duration
🎬 Director-wise content analysis
📊 Data-quality indicators

The project uses a Netflix-inspired dark cinematic theme with red accents to create a professional streaming-analytics experience.

🎯 Project Objectives

The main objectives of this project are:

Analyze the overall size of the Netflix content catalog.
Understand the distribution of Movies and TV Shows.
Analyze content trends across release years.
Explore ratings and audience categories.
Analyze Netflix content distribution across countries.
Understand movie duration and TV Show season patterns.
Analyze content contribution by directors.
Identify missing director information and other data-quality issues.
Build an interactive and visually engaging Power BI dashboard.
🛠️ Tools & Technologies
Tool	Purpose
Power BI Desktop	Dashboard development and visualization
Power Query	Data cleaning and transformation
DAX	KPI and analytical measure creation
Microsoft Excel / CSV	Dataset handling
GitHub	Project documentation and portfolio
📂 Dataset

The project uses a Netflix catalog dataset containing information related to titles available on the platform.

Main Data Entity

Netflix Catalog

Important Fields
Title
Type
Director
Country
Release Year
Rating
Age_Category
Duration-related fields

The project also contains a dedicated:

Dax measures

table for reusable Power BI calculations.

📊 Dashboard Pages

The Power BI report contains four analytical pages.

1️⃣ Executive Overview

The Executive Overview provides a high-level summary of the Netflix catalog.

Key KPIs
Total Titles
Total Movies
Total TV Shows
% Movies
% TV Shows
Visualizations
Movie vs TV Show distribution
Total titles by release year
Total titles by age category
Business Questions

How large is the Netflix catalog?

What is the balance between Movies and TV Shows?

How has the catalog changed across release years?

2️⃣ Rating & Audience Insights

This page focuses on audience and rating-related analysis.

Key Metrics
Mature Content %
Distinct Countries
Visualizations
Rating distribution by age category
Country-wise title distribution
Business Questions

What type of audience categories are represented?

How much mature content exists?

How geographically diverse is the catalog?

3️⃣ Duration Analysis

This page analyzes the duration characteristics of Netflix content.

Key Metrics
Longest Movie
Shortest Movie
Average Movie Duration
Average TV Seasons
Business Questions

What is the typical movie duration?

What are the shortest and longest movies?

How many seasons do TV Shows have on average?

4️⃣ Directors & Quality

This page combines director analysis with data-quality monitoring.

Key Metrics
Distinct Countries
Missing Director Count
Missing Director %
Visualization
Total Titles by Director
Business Questions

Which directors have contributed the most titles?

How complete is the director information?

How much of the catalog has missing director data?

📈 Key DAX Measures

The project contains reusable DAX measures including:

Total Titles
Total Movies
Total TV Show
% Movies
% TV Shows
Mature Content %
Distinct Countries
Longest Movie
Shortest Movie
Average Movie Duration
Average TV Seasons
Missing Director
Missing director%

These measures are organized within the dedicated Dax measures table for better maintainability and reuse.

🎨 Dashboard Design

The dashboard follows a Netflix-inspired cinematic design.

Design Characteristics
Dark background
Netflix-style red accent
White/light typography
KPI cards
Clean analytical charts
Page-specific analytical sections
Strong visual hierarchy

The design was chosen to make the dashboard visually consistent with a modern streaming-platform analytics experience.

🔄 Data Analytics Workflow
Raw Netflix Dataset
        ↓
Data Cleaning
        ↓
Power Query Transformation
        ↓
Data Modeling
        ↓
DAX Measures
        ↓
Power BI Visualizations
        ↓
Interactive Dashboard
        ↓
Business Insights
🧹 Data Cleaning & Transformation

Power Query can be used to prepare the Netflix catalog before visualization.

Typical preparation includes:

Removing duplicate records
Handling missing values
Standardizing categorical values
Cleaning country information
Cleaning rating values
Preparing duration fields
Creating age-category classifications
Validating release-year values

Data-quality analysis is also incorporated into the dashboard through missing-director measures.

🧪 Testing & Validation

The dashboard should be validated using the following checks:

Test	Expected Result
Total title calculation	Correct catalog count
Movie count	Matches source data
TV Show count	Matches source data
Movie/TV percentage	Percentages are consistent
Release-year trend	Correct year-wise distribution
Age category	Valid categories displayed
Country analysis	Correct country distribution
Rating analysis	Correct rating categories
Duration metrics	Correct min/max/average
Director analysis	Correct director distribution
Missing Director	Correct count and percentage
📁 Recommended GitHub Structure
Netflix-Content-Analytics/
│
├── README.md
│
├── Netflix Dashboard.pbix
│
├── Netflix_Dashboard_PDD_SDD.pdf
│
├── Screenshots/
│   ├── Executive_Overview.png
│   ├── Rating_Audience_Insights.png
│   ├── Duration_Analysis.png
│   └── Directors_Quality.png
│
├── Dataset/
│   └── Netflix_Catalog.csv
│
└── Documentation/
    ├── PDD.pdf
    └── SDD.pdf
💡 Key Insights

The dashboard enables users to investigate:

Overall Netflix catalog size
Movie and TV Show composition
Content growth across release years
Audience and rating patterns
Geographic distribution of content
Movie duration patterns
TV Show season patterns
Director contribution
Missing data and catalog-quality issues

Note: Specific numerical insights should be taken directly from the latest refreshed dashboard rather than hard-coded in the README.

🚀 Future Enhancements

Possible future improvements include:

⭐ Rating trend analysis
🌍 Interactive geographic map
📅 Monthly/yearly content addition analysis
🎭 Genre analysis
🎬 Top directors and actors
🔍 Advanced title search
📈 Content growth forecasting
🤖 Machine-learning-based content recommendations
📊 More advanced audience segmentation
📚 Documentation

The project documentation includes a combined:

Product Design Document (PDD) + Software Design Document (SDD)

The documentation covers:

Business requirements
Product objectives
Functional requirements
Dashboard architecture
Data model
DAX measures
Visual specifications
UI/UX design
Testing
Data quality
Deployment
Maintenance

👩‍💻 Author
Madhumitha

Data Analytics | Power BI | SQL | Excel | Python

⭐ Project Highlights

Domain: Entertainment / Streaming Analytics

Technology: Microsoft Power BI

Analysis Type: Descriptive & Exploratory Analytics

Dashboard Pages: 4

Primary Dataset: Netflix Catalog

Key Areas: Content, Ratings, Audience, Geography, Duration & Directors

📌 Project Status

Completed — Power BI Dashboard & Documentation

This project demonstrates practical skills in:

Power BI • Power Query • DAX • Data Cleaning • Data Visualization • Dashboard Design • Business Analysis
