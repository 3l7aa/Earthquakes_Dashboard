#  Earthquakes Data Analysis Dashboard

This is a Streamlit dashboard for analyzing global earthquake data using Python and visualization libraries like Plotly and GeoPandas.

##  Project Structure

- `Earthquakes_Dataset.csv`: The dataset used in this dashboard.
- `EarthQuakes.py`: Streamlit dashboard script.
- `env/`: Python virtual environment (not recommended to upload).
- `README.md`: Project overview.

##  Features

- Date and magnitude filters
- Global earthquake map
- Yearly earthquake trends
- Depth vs Magnitude scatter plot
- Top 5 strongest earthquakes
- Frequent earthquake-prone areas

##  How to Run

```bash
# Activate virtual environment (PowerShell)
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.\env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run EarthQuakes.py
