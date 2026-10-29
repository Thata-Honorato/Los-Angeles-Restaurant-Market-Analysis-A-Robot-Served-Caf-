# 📊 Los Angeles Restaurant Market Analysis: A Robot-Served Café

## Project Overview

This project explores the restaurant market in Los Angeles to assess the feasibility of opening a small café featuring **robot servers**. The goal was to analyze the existing food service landscape, identify market patterns, and develop data-driven recommendations for potential investors.

The project emphasizes **exploratory data analysis (EDA), data visualization, and data storytelling** to turn raw data into actionable business insights.

## Business Objectives

- Analyze the distribution of restaurant types across Los Angeles.
- Compare chain establishments with independent restaurants.
- Investigate seating capacity patterns among restaurant chains.
- Identify the most common restaurant types and their average seating capacity.
- Explore streets with the highest and lowest concentrations of restaurants.
- Develop recommendations for the café concept, seating capacity, and potential expansion into a chain.
- Communicate findings through a presentation designed for investors.

## Dataset

The analysis used `rest_data_us_upd.csv`, containing information about restaurants in Los Angeles.

| Column | Description |
|---|---|
| `object_name` | Name of the establishment |
| `chain` | Indicates whether the establishment belongs to a chain |
| `object_type` | Type of establishment |
| `address` | Full street address |
| `number` | Number of seats |

## Methodology

### 1. Data Preparation
- Loaded the dataset into a Pandas DataFrame.
- Inspected data types and checked for missing values and duplicates.
- Extracted street names from addresses to support geographic analysis.

### 2. Exploratory Data Analysis
- Analyzed the distribution of restaurant types.
- Compared chain and independent establishments.
- Investigated seating capacity patterns among restaurant chains.
- Calculated average seating capacity by establishment type.
- Identified streets with the highest number of restaurants.
- Examined streets with only one restaurant.
- Analyzed seating capacity on streets with high restaurant concentrations.

### 3. Conclusions and Recommendations
- Evaluated which establishment type could best suit the proposed robot-served café.
- Used seating capacity analysis to inform recommendations about the café's size.
- Considered the potential for developing a chain of robot-served cafés.
- Prepared an investor-oriented presentation summarizing the analysis and recommendations.

## Tools and Technologies

- **Python**
- **Pandas** — data preparation and analysis
- **Jupyter Notebook** — interactive analysis and documentation
- **Seaborn** — statistical data visualization
- **Matplotlib** — charts and plots
- **Data Storytelling** — communicating insights and business recommendations

## Project Deliverables

- **Jupyter Notebook:** Data preparation, exploratory analysis, visualizations, and conclusions.
- **Investor Presentation (PDF):** Key findings and strategic recommendations.

*Add links to your notebook and PDF presentation here.*

## Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Data visualization and interpretation
- Geographic data analysis
- Business-oriented analytical thinking
- Data storytelling and presentation design
- Translating analytical findings into actionable recommendations

## Key Takeaway

This project demonstrates how exploratory data analysis and data storytelling can support business decisions by identifying market patterns, evaluating potential opportunities, and communicating evidence-based recommendations to stakeholders.
