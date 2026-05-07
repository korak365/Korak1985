# Airbnb Shadow Inventory Tracker Scraper

This Actor identifies properties listed on both Airbnb and VRBO platforms. By comparing property details (title, location, pricing), it flags potential shadow inventory and highlights pricing discrepancies across platforms.

## How it works:
- Scrapes listings from both Airbnb and VRBO.
- Matches listings based on location, price, and other details.
- Outputs structured data for further analysis.

## Usage:
1. Provide Airbnb and VRBO listing URLs as input.
2. Run the scraper locally or on the Apify platform.
3. Analyze matched listings in the Dataset to identify overlaps.
