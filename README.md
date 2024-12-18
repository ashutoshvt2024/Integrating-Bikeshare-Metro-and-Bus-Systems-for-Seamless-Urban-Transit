# Integrating-Bikeshare-Metro-and-Bus-Systems-for-Seamless-Urban-Transit


This project provides optimal routes for urban transportation by integrating Capital Bikeshare, Metro, and Metrobus datasets. Using OpenRouteService (ORS) and Folium, it calculates and visualizes the best routes based on user-provided start and end coordinates.

📌 Project Overview

The application allows users to:

	1.	Input starting coordinates and ending coordinates.
 
	2.	Identify:
	•	The nearest Capital Bikeshare station to the starting point.
	•	The nearest Capital Bikeshare station to the ending point.
	•	The nearest metro station and metrobus stop to the ending Capital Bikeshare station.
 
	3.	Calculate optimal routes:
	•	From the start point to the nearest starting Capital Bikeshare station.
	•	From the starting Capital Bikeshare station to the ending Capital Bikeshare station.
	•	From the ending Capital Bikeshare station to the nearest metro station.
	•	From the ending Capital Bikeshare station to the nearest metrobus stop.
 
	4.	Visualize all routes and points on an interactive Folium map.

🚀 Technologies Used

	•	Python Core programming language.
 
	•	Pandas For data preprocessing and handling.
 
	•	Folium For interactive map generation.
 
	•	OpenRouteService (ORS) API for route calculation.
 
	•	scikit-learn For NearestNeighbors search.
 
	•	Geopy For geodesic distance computation.

🗄️ Datasets

1. Capital Bikeshare Data
	•	Includes detailed information about bike station locations (latitude, longitude, and station names).
	•	Note: Due to the large file size, this dataset is hosted on Google Drive.
[Download Capital Bikeshare Dataset Here](https://drive.google.com/file/d/18znZGwNzCEvguEdTSY7I_ZU84IgMDI2V/view?usp=sharing)

2. Metro Station Data
	•	Contains metro station names and their respective geographical coordinates.

3. Metrobus Stop Data
	•	Provides the latitude, longitude, and descriptions of metrobus stops.

🌍 OpenRouteService (ORS) Usage

The project uses OpenRouteService to calculate optimal routes between specified coordinates for:
	•	Cycling routes between bike stations.
	•	Walking routes to metro stations and metrobus stops.

🔑 API Key:

This project uses the following OpenRouteService API Key: 5b3ce3597851110001cf6248da749d4d165f4265be8436d5d967afe9

**Note: Replace this key in the script if using your own ORS API key.**

📊 How to Run the Project

	1.	Clone the repository
 
 	2.	Install the required dependencies : pip install pandas folium openrouteservice geopy scikit-learn
  
  3.	Download all three Datasets(CapitalBikeShare, MetroBus, MetroStations)
	
  4.	Run the script
     
  5.	Provide the starting coordinates and ending coordinates when prompted.
     
	6.	View the generated map: The map will be saved as full_routes_map.html in the project directory. Open it in your browser.
  
