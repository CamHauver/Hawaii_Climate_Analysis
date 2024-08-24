# Hawaii_Climate_Analysis
Data exploration and climate analysis of Honolulu, Hawaii using Python, SQLAlchemy, ORM queries, Pandas, and Matplotlib. Also includes the creation of a local API app using Flask API.

Original code sources: Data Analytics course Module 10 Challenge Starter_Code files, Data Analytics course instructor, Andrew Hoang's, speed run Zoom recording for Module 10 Challenge

See climate_analysis.ipynb jupyter notebook for data exploration and analysis of a SQLite file (hawaii.sqlite). This includes an analysis and bar graph of precipitation data within a given time-frame, a count and ranking of weather station activity, and an analysis and histogram of temperature observation data (tobs)

See app.py file with code for creating a local API Climate App using Flask API based on queries formulated in climate_analysis.ipynb. The API includes jsonified precipitation data, station data, temperature observation data (tobs), and min/avg/max temperature calcuation data for a given date/date range.

