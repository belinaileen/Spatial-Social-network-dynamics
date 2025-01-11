import folium

# Coordinates for Groningen
latitude = 53.2194
longitude = 6.5665

# Create and save Groningen map
map_groningen = folium.Map(location=[latitude, longitude], zoom_start=12)
folium.Marker([latitude, longitude], popup="Groningen").add_to(map_groningen)
map_groningen.save("map_groningen.html")
