# New York Vehicle Collisions (Tilemaps)

## Web Map URL
**Link to the web map:**

---

## Screenshots of Map Layers

### 1. Custom Basemap Layer
![Custom Basemap Screenshot](assets\screenshots\basemap.png)

---

### 2. Collision Density Layer
![Collision Density Screenshot](assets\screenshots\collisions.png)

---

### 3. Collisions on Basemap Layer
![Collisions on Basemap Screenshot](assets\screenshots\collisionsonbasemap.png)

---

### 4. Collision Analysis Layer
![Collision Analysis Screenshot](assets\screenshots\analysis.png)

---

## Examined Geographic Area
**Description of the area covered in the map:**

- The area that I chose to focus on was New York City, New York. The reason I chose this was partially because I happened to already have the collisions geoJSON file sitting on my computer from a previous research project so I thought it would be pretty cool if I could repurpose it for this project. New York City is also a place with very dense streets and very high traffic, so it lends itself to this analysis of the spatial patterns of vehicle collisions pretty well.

---

## Tile Set Zoom Levels

### All of the map layers have the same zoom levels to save storage space.
- **Minimum Zoom Level: 11**
- **Maximum Zoom Level: 14**

---

## Tile Set Descriptions

### Custom Basemap

- This is a custome basemap made by me, its based off the classic Mapbox dark theme map. The changes I made to this map were basically me trying to make it appear bolder by making the dark elements more black and the text for the major city names whiter so that everthing would pop out more. This layer is turned on by default when viewing the project.

---

### Collision Density

- This layer contains raw point data for each vehicle collision across the city of New York. We can see where clusters of data point are but with just the raw data it can be very difficult to spot any real spatial patterns. There is no basemap for this layer.

---

### Collisions on Basemap

- This layer contains the raw vehicle collision data on top of the custom basemap from the first layer. With this layer it becomes far easier to see where collisions occur througout the city of New York but once again we are really unable to find any spatial patterns with this layer.

---

### Collision Analysis

- This layer contains the collision data after its been processed into a discrete kernel density map then placed on top of the cutom baselayer. With this layer we can finally begin to understand the spatial patterns of collisions throughout New York. From the farthest zoom we can see a big hotspot over the Manhatten area. And as we zoom further in we can see where the other collision hotspots are located around the city.

---
