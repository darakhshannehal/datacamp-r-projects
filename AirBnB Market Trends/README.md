## Exploring AirBnB Market Trends

This project serves as a consultancy analysis for a real estate start-up, focusing on investigating the short-term rental market in New York City.

### Questions answered

-   What are the dates of the earliest and most recent reviews?

-   How many of the listings are private rooms?

-   What is the average listing price for all rooms (rounded to the nearest penny)?

### Data dictionary

| File | Format | Key Columns | Description |
|--------------------------|---------|---------------------------|------------------------------------|
| airbnb_price | CSV | listing_id, price, nbhood_full | Listing prices and neighborhood location. |
| airbnb_room_type | XLSX | listing_id, room_type | Listing description and room type (Shared, Private, Entire Home). |
| airbnb_last_review | TSV | listing_id, host_name, last_review | Host names and the date of the last review. |

### Tools Used

-   **`tidyverse`**: Data wrangling

-   **`readxl`**: Reading Excel files (.xlsx)

-   **`skimr`**: Quick data summaries and structure checks