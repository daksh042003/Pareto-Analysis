Pareto Analysis Dashboard
Overview

This project showcases an advanced Pareto Analysis dashboard built in Power BI using Visual Calculations, Field Parameters, and dynamic interactivity.
The report enables users to analyze Sales or Profit concentration across multiple business dimensions while applying the Pareto Principle (80/20 rule) through a fully dynamic threshold selector.

All Pareto logic is implemented at the visual calculation layer, ensuring flexibility, performance, and alignment with the latest Power BI best practices.

Business Objective

The objective of this project is to help business users and decision-makers:

Identify top-contributing products, customers, or countries

Understand revenue and profit concentration

Detect dependency risks on a small subset of entities

Focus efforts on high-impact contributors

The dashboard provides instant insights without requiring complex manual analysis.

Key Features

Dynamic Pareto Threshold selection (50%–95%)

Metric switching between Sales and Profit

Dimension switching using Field Parameters

Product

Customer

Country

Pareto Combo Chart with:

Descending contribution sort

Cumulative percentage line

Dynamic threshold reference line

Conditional bar coloring based on Pareto category

Executive-level KPI summary cards

Detailed Pareto table with ranking and cumulative metrics

Technical Implementation

All Pareto logic implemented using Power BI Visual Calculations:

Rank

Running Total

Individual %

Cumulative %

Pareto Category (Top Contributor / Long Tail)

Minimal traditional DAX used only for base measures

Calculations handled at the visual layer for better performance

Fully interactive single-page report

Tech Stack

Power BI Desktop

Visual Calculations (New Calculation Layer)

Field Parameters

DAX (base aggregations only)

Dataset

Embedded sample dataset included within the Power BI file.

No external data connections required

Ready to open and explore immediately

Report Details

Single-page interactive dashboard

Resolution: 1920 × 1080

Optimized for executive reporting and portfolio presentation

Clean and professional UI aligned with modern Power BI design standar
