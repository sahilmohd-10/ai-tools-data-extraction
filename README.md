# AI Tools Data Extraction & Analysis Pipeline

Freelance project focused on building a scalable pipeline for collecting, cleaning, and organizing structured information about AI tools from public web sources.

The project demonstrates practical skills in web scraping, data preprocessing, and data analysis using Python.

---

## Project Overview

The goal of this project was to collect structured data for more than **1000 AI tools** from various public web directories and prepare the dataset for further business analysis and reporting.

Manual collection would have been extremely time-consuming.  
To solve this problem, I created an automated workflow using web scraping tools and Python-based data processing.

---

## Key Features

• Automated extraction of structured AI tool data  
• Data collected from multiple webpages using Chrome scraping tools  
• Data cleaning and preprocessing using Python  
• Organized dataset ready for analytics and reporting  
• Reduced manual data collection effort by **~90%**

---

## Technologies Used

- Python
- Pandas
- NumPy
- Chrome Web Scraper Extension
- Jupyter Notebook
- Excel / CSV Data Processing

---

## Data Collected

The dataset includes the following information about each AI tool:

- Tool Name
- Category
- Pricing
- Description
- Features
- Pros
- Cons
- Website Link
- Images

---

## Web Scraping Workflow

1. Identify AI tool listing pages
2. Create sitemap using Chrome Web Scraper
3. Define selectors for each element
4. Extract structured data from multiple pages
5. Export dataset as CSV/Excel
6. Process and clean dataset using Python

---

## Data Processing Pipeline

After scraping the raw data, the dataset was cleaned using Python.

Steps included:

- Removing duplicates
- Handling missing values
- Formatting text fields
- Structuring columns
- Exporting clean dataset for analysis

Example libraries used:

```python
import pandas as pd
import numpy as np
