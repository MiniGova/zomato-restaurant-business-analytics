# Zomato Restaurant Analytics Dashboard

A Power BI dashboard and presentation that analyze Zomato restaurant data: ratings, cities, cuisines, price ranges, online delivery and table booking.

## Files

| File | Description |
|---|---|
| `ZOMATO_PROJECT1.pbix` | Power BI report (interactive dashboard) |
| `zomato123.xlsx` | Raw dataset |
| `cleaned_zomato.xlsx` | Cleaned dataset used for analysis |
| `Screenshot_2026-09-28_120810.png` | Screenshot of the dashboard |
| `Zomato_Restaurant_Analytics.pptx` | 7-slide presentation summarizing the dashboard |

## Dataset

- 9,551 restaurants across 15 countries, 141 cities and 21 columns.
- Key columns: Restaurant Name, Country Code, City, Cuisines, Average Cost for two, Has Table booking, Has Online delivery, Price range, Aggregate rating, Rating text, Votes.
- Country codes are numeric (for example 1 = India, 216 = USA, 162 = Philippines).

## Dashboard contents

**KPI cards:** Total Restaurants, Average Rating, Cities, Cuisines, Votes.

**Charts:**
- Top cities by restaurant count
- Average rating by price range
- Online delivery availability
- Price range distribution
- Top cuisines by restaurant count
- Table booking availability
- Table of restaurants with city, rating and votes

**Filter:** a country slicer on the left side of the dashboard.

## Key results (Philippines view shown in the screenshot)

- 22 restaurants in 9 cities, 19 cuisine combinations, 8,963 votes
- Average rating of 4.47; 12 of 22 restaurants rated Excellent
- Mandaluyong and Taguig lead with 4 restaurants each
- Average rating stays about 4.4 to 4.5 across price ranges
- 0% offer online delivery; 63.6% offer table booking
- Top rated (4.9): Silantro Fil-Mex (Pasig), Spiral - Sofitel (Pasay), Ooma (Mandaluyong)

## Global context (full dataset)

- Average rating is 2.67, and 2,148 restaurants have no rating (shown as 0)
- 25.7% offer online delivery; 12.1% offer table booking
- Restaurants with delivery or table booking average higher ratings (3.25 vs 2.47 and 3.44 vs 2.56)

## How to use

1. Open `ZOMATO_PROJECT1.pbix` in Power BI Desktop.
2. If prompted, point the data source to `cleaned_zomato.xlsx`.
3. Use the country slicer to switch between countries.
4. Open `Zomato_Restaurant_Analytics.pptx` for a summary without Power BI.

## Notes

- The dashboard's 22-restaurant totals match the Philippines rows, so the screenshot and presentation reflect that country.
- The `Currency` column in the source data is inconsistent (Philippine rows say "Botswana Pula"), so cost figures are shown without a reliable currency label in the deck.

## Tools

Power BI Desktop, Microsoft Excel, PowerPoint.