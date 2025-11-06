# Listings Data Dictionary (auto-generated from your file's columns)

This document explains the meaning, units/encodings, and shows an example value for each column present in the uploaded dataset.

| variable | meaning | units_or_encoding | inferred_dtype | example_value |
|---|---|---|---|---|
| accommodates | Capacity/room count. | Count | int64 | 3 |
| amenities | — | Text / category | object | ["Extra pillows and blankets", "Wifi", "Luggage dropoff allowed", "Hair dryer", "Dishes and silverware", "Heating", "Refrigerator", "Shampoo", "Microwave", "Private entrance", "Hot water", "Bed linens |
| availability_30 | Availability count over the specified lookahead window. | Days (count) | int64 | 30 |
| availability_365 | Availability count over the specified lookahead window. | Days (count) | int64 | 336 |
| availability_60 | Availability count over the specified lookahead window. | Days (count) | int64 | 60 |
| availability_90 | Availability count over the specified lookahead window. | Days (count) | int64 | 90 |
| availability_eoy | Availability count over the specified lookahead window. | Days (count) | int64 | 185 |
| bathrooms | Bathroom count/description. | Count (may include halves) | float64 | 1.0 |
| bathrooms_text | Bathroom count/description. | Text label | object | 1 bath |
| bedrooms | Bedroom count. | Count | float64 | 1.0 |
| beds | Bed count. | Count | float64 | 2.0 |
| calculated_host_listings_count | Derived count of listings associated with the host. | Count | int64 | 1 |
| calculated_host_listings_count_entire_homes | Derived count of listings associated with the host. | Count | int64 | 1 |
| calculated_host_listings_count_private_rooms | Derived count of listings associated with the host. | Count | int64 | 0 |
| calculated_host_listings_count_shared_rooms | Derived count of listings associated with the host. | Count | int64 | 0 |
| calendar_last_scraped | Date field from reviews/scraping. | Date (YYYY-MM-DD) | object | 2025-06-13 |
| calendar_updated | Calendar update status label (from API). | Text label | float64 |  |
| description | Text description of the listing. | Text / category | object | Great central  location for walking to Convention Center, Rainey Street, East 6th Street, Downtown, Congress Ave Bats.<br /><br />  Free wifi<br /><br />No Smoking,  No pets |
| estimated_occupancy_l365d | Estimated occupancy percentage in the last 365 days. | Percent (0–100) | int64 | 162 |
| estimated_revenue_l365d | Estimated revenue in the last 365 days. | Currency (e.g., USD) | float64 | 16362.0 |
| first_review | Date field from reviews/scraping. | Date (YYYY-MM-DD) | object | 2009-03-08 |
| has_availability | Boolean indicator. | Boolean | object | t |
| host_about | Free text about the host. | Text / category | object | I am a licensed Real Estate Broker and owner of Armadillo Realty.  I attended The University of Texas at Austin and fell in love with the small town that it was back in 1979; I have been here every si |
| host_acceptance_rate | Host metric expressed as a percentage. | Percent (0–100) | object | 92% |
| host_has_profile_pic | — | Text / category | object | t |
| host_id | Unique identifier. | Text / category | int64 | 8028 |
| host_identity_verified | Boolean indicator. | Boolean | object | t |
| host_is_superhost | Boolean indicator. | Boolean | object | t |
| host_listings_count | — | Text / category | float64 | 1.0 |
| host_location | — | Text / category | object | Austin, TX |
| host_name | Host's displayed name. | Text / category | object | Sylvia |
| host_neighbourhood | — | Text / category | object | East Downtown |
| host_picture_url | Link/URL to a web resource. | URL | object | https://a0.muscache.com/im/users/8028/profile_pic/1329882962/original.jpg?aki_policy=profile_x_medium |
| host_response_rate | Host metric expressed as a percentage. | Percent (0–100) | object | 100% |
| host_response_time | — | Text / category | object | within a few hours |
| host_since | Date the host account was created. | Date (YYYY-MM-DD) | object | 2009-02-16 |
| host_thumbnail_url | Link/URL to a web resource. | URL | object | https://a0.muscache.com/im/users/8028/profile_pic/1329882962/original.jpg?aki_policy=profile_small |
| host_total_listings_count | — | Text / category | float64 | 2.0 |
| host_url | Link/URL to a web resource. | URL | object | https://www.airbnb.com/users/show/8028 |
| host_verifications | Verification methods associated with host. | Text / category | object | ['email', 'phone'] |
| id | Unique identifier. | Text / category | int64 | 5456 |
| instant_bookable | Boolean indicator. | Boolean | object | f |
| last_review | Date field from reviews/scraping. | Date (YYYY-MM-DD) | object | 2025-04-27 |
| last_scraped | Date field from reviews/scraping. | Date (YYYY-MM-DD) | object | 2025-06-13 |
| latitude | Latitude coordinate of the listing. | Decimal degrees | float64 | 30.26057 |
| license | Local license/permit identifier (text). | Text ID | float64 |  |
| listing_url | Link/URL to a web resource. | URL | object | https://www.airbnb.com/rooms/5456 |
| longitude | Longitude coordinate of the listing. | Decimal degrees | float64 | -97.73441 |
| maximum_maximum_nights | Minimum/maximum nights policy. | Nights (count) | int64 | 90 |
| maximum_minimum_nights | Minimum/maximum nights policy. | Nights (count) | int64 | 2 |
| maximum_nights | Minimum/maximum nights policy. | Nights (count) | int64 | 90 |
| maximum_nights_avg_ntm | Minimum/maximum nights policy. | Nights (count) | float64 | 90.0 |
| minimum_maximum_nights | Minimum/maximum nights policy. | Nights (count) | int64 | 90 |
| minimum_minimum_nights | Minimum/maximum nights policy. | Nights (count) | int64 | 2 |
| minimum_nights | Minimum/maximum nights policy. | Nights (count) | int64 | 2 |
| minimum_nights_avg_ntm | Minimum/maximum nights policy. | Nights (count) | float64 | 2.0 |
| name | Listing title/name. | Text / category | object | Walk to 6th, Rainey St and Convention Ctr |
| neighborhood_overview | — | Text / category | object | My neighborhood is ideally located if you want to walk to bars and restaurants downtown, East 6th Street or Rainey Street.  The Convention Center is only 3 1/2 blocks away and a quick 10 minute walk.  |
| neighbourhood | Neighborhood / administrative area label. | Text / category | object | Neighborhood highlights |
| neighbourhood_cleansed | Neighborhood / administrative area label. | Text / category | int64 | 78702 |
| neighbourhood_group_cleansed | Neighborhood / administrative area label. | Text / category | float64 |  |
| number_of_reviews | Count of reviews in the specified window. | Count | int64 | 711 |
| number_of_reviews_l30d | Count of reviews in the specified window. | Count | int64 | 0 |
| number_of_reviews_ltm | Count of reviews in the specified window. | Count | int64 | 27 |
| number_of_reviews_ly | — | Text / category | int64 | 33 |
| picture_url | Link/URL to a web resource. | URL | object | https://a0.muscache.com/pictures/14084884/b5a35a84_original.jpg |
| price | Monetary amount. | Currency (e.g., USD) | object | $101.00 |
| property_type | Type of property (e.g., Apartment, House). | Text / category | object | Entire guesthouse |
| review_scores_accuracy | Customer review score component. | Score (0–5) | float64 | 4.88 |
| review_scores_checkin | Customer review score component. | Score (0–5) | float64 | 4.9 |
| review_scores_cleanliness | Customer review score component. | Score (0–5) | float64 | 4.86 |
| review_scores_communication | Customer review score component. | Score (0–5) | float64 | 4.82 |
| review_scores_location | Customer review score component. | Score (0–5) | float64 | 4.73 |
| review_scores_rating | Customer review score component. | Score (0–5) | float64 | 4.85 |
| review_scores_value | Customer review score component. | Score (0–5) | float64 | 4.79 |
| reviews_per_month | Average reviews per month. | Count per month | float64 | 3.59 |
| room_type | Room type (e.g., Entire place, Private room). | Text / category | object | Entire home/apt |
| scrape_id | Unique identifier. | Text / category | int64 | 20250613040113 |
| source | Origin/source of the row (e.g., scrape feed). | Text / category | object | city scrape |
