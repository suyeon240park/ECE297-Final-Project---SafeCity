# ECE297 Final Project - SafeCity
SafeCity is a GIS-based application designed to improve urban safety by mapping and visualizing dangerous areas in Toronto based on incidents reported in 2023. Leveraging Geographic Information Systems (GIS) technology, SafeCity provides real-time information on high-risk zones, enabling users to make informed decisions about their routes and locations. By highlighting areas prone to crime and other incidents, SafeCity empowers users to navigate the city more safely.

## Key Features
### 1. Incident Mapping
- Visualizes Points of Interest (POIs) in major cities.
- Displays 2023 crime incidents in Toronto using data from the Toronto Police Service CSV.
- Shows real-time traffic incidents from the TomTom traffic API.
![POI](https://github.com/suyeon240park/ECE297-SafeCity/assets/123034036/2799ddd8-da98-4137-a40e-c0e551cdd6c1)

 
### 2. User-Friendly Interface
- Analyzes incident concentration on the map.
- Adjusts map elements dynamically based on zoom level for improved visibility.


https://github.com/suyeon240park/ECE297-SafeCity/assets/123034036/8ec684b3-38ee-4c2a-aeba-e71ddcec1a88


  
### 3. Path Finding with A* algorithm
- Efficient route planning considering travel time and street turn penalties.
- Process:
1. Initialize: Create a graph
2. Explore: Explore legally connected intersections
3. Evaluate: Check if it is the destination. Or, calculate the cost
4. Return: Backtract and return if the path exists

- 93% of searches complete in under 100 ms for an instantaneous user experience.
![path finding](https://github.com/suyeon240park/ECE297-SafeCity/assets/123034036/02c3f6c8-f775-47cd-9bcc-44791ba68888)


### 4. Safe Path:
- Identifies safer routes by minimizing the number of incidents along the path

### 5. Multi-Route Planning:
- Allows users to select optimal paths for multiple destinations

## Impact
- Enables users, especially those who are new to a city, such as travellers or newcomers, to avoid dangerous areas and lead to safe areas
- Reduces safety concerns and provides insights into incident trends in urban environments
- enhances navigation efficiency and promotes city-wide safety

## Limitation
- Incident data cannot be perfectly real-time due to time takes for API delivery
- Map elements do not provide perfectly understandable visual cues about the incidents
- Areas with high population naturally have higher crime rates, which do not reflect the crime rate per population

## Future Pitch
- 
