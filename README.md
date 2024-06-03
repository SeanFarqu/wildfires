# Wildland Fires Mapping Project

This project visualizes wildland fire data in the USA using GIS software and Python. The data is retrieved from the ArcGIS Living Atlas, and the interactive map is created using the `folium` library. The map displays fire perimeters and centroids, providing a clear visual representation of wildland fires.

## Project Overview

- **Data Source:** ArcGIS Living Atlas ("USA Wildfire Activity" layer)
- **Libraries Used:** ArcGIS API for Python, GeoPandas, Pandas, Folium
- **Output:** Interactive HTML map with fire perimeters and centroids

## Features

- Retrieve wildland fire data using the ArcGIS API for Python
- Convert the data to a GeoPandas DataFrame for spatial analysis
- Visualize fire perimeters and centroids on an interactive Folium map
- Save the interactive map as an HTML file

## Installation

To run this project, you need to have Python installed along with the following libraries:

```bash
pip install arcgis geopandas pandas folium
```

## Usage

1. **Clone the repository:**

```bash
git clone https://github.com/SeanFarqu/wildfires.git
cd wildfires
```

2. **Run the script:**

```bash
python Wildfires_visualize.py
```

3. **Open the generated map:**

The script will generate an HTML file named `wildland_fires_map.html`. Open this file in your web browser to view the interactive map.

## Script Details

- **`Wildfires_visualize.py`**: The main script that retrieves data, processes it, and generates the interactive map.

## Example Output

The generated map will display fire perimeters in red and centroids in blue. Clicking on a centroid marker will show the fire name.

## Contributing

If you have suggestions for improvements or find any issues, please open an issue or submit a pull request.

