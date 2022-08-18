# SurfsUp Backgroud
The stakeholder has requested summary statistics on weather for the months of June and December for Oahu, HI. 

# Methodology
The weather was extracted from a SQLite database using sqlalchemy. The database contained two tables: measurement and station. These tables were identified after reflecting the database and tables using automap_base within sqlalchemy. Using Pandas, the tables were transformed into DataFrames and were used to generate the requested summary statistics.

# Findings