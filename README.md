# Indian-State-cities-sql

SQL scripts to create and populate tables of all Indian states and their cities. This repository is meant to be dropped into any relational database (MySQL or compatible) to quickly seed location data for India.[web:12]

## Features

- Separate `states.sql` and `cities.sql` files for flexible imports.[web:12]
- Normalized structure so each city references its corresponding state by id.
- Ready to use for dropdowns, address forms, and location filters in Indian applications.[web:11]
- Easy to extend with additional columns like latitude, longitude, or pin codes.

## Files

- `states.sql`: Creates and inserts all Indian states into a `states` table.
- `cities.sql`: Creates and inserts Indian cities mapped to their state ids into a `cities` table.
- `README.md`: Project overview and usage instructions.

## Getting started

1. Create a new database:

   ```sql
   CREATE DATABASE indian_locations;
   USE indian_locations;
