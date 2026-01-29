Industry Carbon Emissions Analysis
Project Overview

This project analyzes product-level carbon emissions data to identify which industry groups contribute the most to global carbon footprints. Since product emissions account for a significant portion of total global emissions, understanding industry-level impact is critical for sustainability insights and policy decisions.

Dataset

The analysis uses the product_emissions table, which contains information on:

Company identifiers

Industry group classifications

Product carbon footprint (PCF)

Reporting year

Only data from the most recent year available in the database is included in the analysis to ensure relevance.

Key Objective

Determine, for each industry group:

The number of unique companies reporting emissions

The total industry carbon footprint (PCF)

Analysis Approach

Using SQL, the project performs:

Filtering to select records from the most recent year

Aggregation to count unique companies per industry

Summation of product carbon footprints by industry

Rounding of numerical results for clear reporting

Sorting industries by total carbon footprint (highest to lowest)

Output

The final query returns the following columns:

industry_group

num_companies

total_industry_footprint (rounded to one decimal place)

The result is saved as carbon_emissions_by_industry.

Tools & Technologies

SQL

PostgreSQL

Key Insight

Industry-level aggregation reveals how a relatively small number of industries can account for a disproportionate share of total carbon emissions, highlighting where sustainability efforts may have the greatest impact.

Learning Outcome

This project demonstrates how SQL can be used to analyze real-world environmental data, apply aggregation and filtering techniques, and generate insights relevant to sustainability and data-driven decision-making.
