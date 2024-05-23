Context
Welcome to "The Grand Tourists Database Challenge"! Imagine you are working for a tourism company that specializes in providing unique travel experiences to tourists from around the world. The company has collected data on their tourists, including their names, addresses, ages, and the coordinates of places they have visited. Your task is to combine this data, perform some statistical analysis, and visualize the tourists' most visited locations on a map.

Task Description
Generate Data:
Use the Faker library to create two DataFrames with random data about the tourists.
The first DataFrame should contain the following columns: 'name', 'address', 'latitude', 'longitude', 'age'.
The second DataFrame should contain the following columns: 'name', 'visit_date', 'latitude', 'longitude'.
Merge Data:
Merge the two DataFrames on the 'name' column.
Statistical Operations:
Calculate the average age of the tourists.
Determine the most common locations (latitude and longitude) visited by the tourists.
Plotting the Map:
Use the Folium library to plot the most common locations on a map.
Highlight the top 5 most visited locations with markers on the map.
