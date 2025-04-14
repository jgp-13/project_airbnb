# Exploring Airbnb Market Trends

This project investigates short-term rental market trends in New York City using Airbnb listing data. As part of a real estate consultancy initiative, the analysis focuses on private room availability, pricing, and guest review trends to inform business decisions in the rental market.

## Objective

To apply data importing, cleaning, and manipulation skills to derive insights from NYC Airbnb datasets. Specifically, the project aims to answer the following:

- Identify the time range of available guest reviews.
- Determine the total number of private room listings.
- Calculate the average listing price.
- Consolidate these insights into a clean summary data structure.

## Data Sources

The project utilizes three datasets stored in the `data` directory:

- `airbnb_price.csv`: Contains listing prices.
- `airbnb_room_type.xlsx`: Contains room type information.
- `airbnb_last_review.tsv`: Contains the dates of the most recent guest reviews.

## Summary Table

All derived metrics were compiled into a single DataFrame named `review_dates`, featuring:

1. `first_reviewed`: Date of the earliest review.
2. `last_reviewed`: Date of the most recent review.
3. `nb_private_rooms`: Total number of private room listings.
4. `avg_price`: Average nightly price across all listings.

This structured data snapshot supports real estate decision-making by offering clear and concise metrics derived from raw Airbnb data.

---

*This analysis was completed as part of a DataCamp project on data importing and manipulation.*