# YouTube Data Harvesting and Warehousing using SQL and Streamlit

## Project Overview

- This project extracts data from YouTube using the YouTube Data API, stores it in a SQL database, and provides an interactive dashboard using Streamlit for data analysis and visualization.

## Technologies Used

- Python
- Streamlit
- MySQL (or SQLite)
- YouTube Data API v3

## Packages Used

- `streamlit`
- `pandas`
- `sqlalchemy`
- `mysql-connector-python` or `sqlite3`
- `google-api-python-client`
- `requests`
- `datetime`
- `json`

## Workflow and Execution Flow

1. **Data Extraction**:  
   Fetch channel, playlist, and video data from YouTube using the YouTube Data API.

2. **Data Transformation**:  
   Clean and structure the data using pandas.

3. **Data Warehousing**:  
   Store the processed data into a SQL database (MySQL or SQLite).

4. **Visualization**:  
   Use Streamlit to create an interactive dashboard for querying and visualizing the data.

## Project Development

- Modular Python scripts for API calls, data processing, and database operations.
- Streamlit app for user interface and data exploration.
- SQL scripts for database schema and queries.

## How to Run the Project

1. Install required packages:

   ```
   pip install -r requirements.txt
   ```

2. Set up your database (MySQL or SQLite).

3. Obtain YouTube Data API credentials and configure them in the project.

4. Run the Streamlit app:

   ```
   streamlit run outputfile.py
   ```

5. Access the dashboard in your browser at `http://localhost:8501`.

## Notes

- Ensure your API key has sufficient quota.
- Update database connection settings as needed in the configuration files.
