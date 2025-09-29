Business Case for a New Database System:

This project is a Streamlit web app that demonstrates how upgrading from a messy legacy database (like old Excel/Access systems) to a clean relational database can solve critical business problems.

It uses fuzzy matching to normalize donor names, removes duplication, and links data across multiple sources (donations and volunteer hours). The app shows how structured data enables powerful insights with just a few clicks.# Donor_System

Features

1. The Problem: Messy Legacy Data:

Duplicate donor names (e.g., Mike Smith, Michael J. Smith).
No unique identifiers, leading to reporting errors.
Inability to link donations with volunteer data.

2. The Solution: Normalized Database

Creates a clean Donors table with unique IDs.
Creates a Donations table linked by DonorID.
Uses fuzzy string matching (fuzzywuzzy) to merge duplicate names.

3. The Payoff: Business Insights

Total Donations Per Donor (bar chart of top donors).
Total Money by a Specific Donor (via dropdown).
Donation Trends Over Time (line chart).
Donor Engagement (linking donations with volunteer hours).
Comparison Table (Old vs. New system).

