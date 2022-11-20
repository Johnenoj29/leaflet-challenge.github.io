# leaflet-challenge
Visit my page on: https://johnenoj29.github.io/leaflet-challenge.github.io/Leaflet-Part-1/index.html

Part 1: Create the Earthquake Visualisation
![image](https://user-images.githubusercontent.com/107616415/202879143-b15bcb6f-ade7-48ed-b2ee-dccbb255cdf5.png)

Your first task is to visualise an earthquake dataset. Complete the following steps:

1. Get your dataset. To do so, follow these steps:

 - The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php and choose a dataset to visualise. The following image is an example screenshot of what appears when you visit this link:

![image](https://user-images.githubusercontent.com/107616415/202879160-df3eb508-b39e-4204-a905-8343edb94528.png)

- When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualisation. The following image is a sampling of earthquake data in JSON format:
![image](https://user-images.githubusercontent.com/107616415/202879187-efd0f7b3-83c8-436f-96b3-da639f67a5cd.png)

2. Import and visualise the data by doing the following:

- Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.

- Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by colour. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in colour.

- Hint: The depth of the earth can be found as the third coordinate for each earthquake.

- Include popups that provide additional information about the earthquake when its associated marker is clicked.

- Create a legend that will provide context for your map data.

Once challenge is complete, the map should look something like below:

![image](https://user-images.githubusercontent.com/107616415/202879245-26649d67-4d8e-4484-83d9-482fdb9baf52.png)
