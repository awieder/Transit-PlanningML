# Transit-PlanningML
This is a transit system station planning tool that uses a gradient boosted decision tree model to predict where the best station locations would be in a given metro area. Building infrastructure is an increasingly expensive and difficult task, thus it is incredibly important to utilize every tool at our disposal to speed up every step of the process, including planning. It is also just an interesting visualization of where the important places that people, jobs, and wealth congregate for different USA metro areas.

# Getting Started
## Dependencies

Install all dependencies with:

pip install numpy pandas geopandas shapely folium xgboost matplotlib scikit-learn scipy requests

## Data Sources

- **Census API key** — required, free at https://api.census.gov/data/key_signup.html
- **ACS 5-year estimates** — pulled automatically via Census API (2023)
- **TIGER tract boundaries** — downloaded automatically from Census TIGER/Line
- **LODES workplace data** — downloaded automatically from LEHD (2021)

- ## Requirements

Python 3.9+

## Running Transit Planner
Running the model is easy and customizable on any metro area of choice! Once you have a census key, in /finished_prod/final_flow.ipynb simply fill in the necessary information in the first cell and hit run all. You will need to input geographical bounds with latitude and longitude, a list of counties you want to include, the state name and  FIPS code, as well as any specefics about the station network you want to create. There are example values for all of these inputs do get an initial visualization quickly.
