# Accessibility to Essential Services in Sheffield

## Project Overview

Access to essential services such as supermarkets and pharmacies is a key component of urban livability and social equity. These services provide residents with access to food, medication, and daily necessities. Understanding their spatial distribution helps identify areas with strong service provision as well as neighbourhoods that may experience limited access.

This project presents a spatial analysis of essential service accessibility in Sheffield using GIS techniques. The analysis focuses on the geographic distribution of supermarkets and pharmacies across Lower Layer Super Output Areas (LSOAs). By mapping the number of services within each LSOA, the project highlights spatial patterns of service concentration and potential inequalities in access across the city.

---

## Map Visualization

Below is the final map produced from the spatial analysis.

<p align="center">
<img src="Accessibility to essential services.jpg" width="850">
</p>

The map illustrates the spatial distribution of supermarkets and pharmacies within Sheffield. Each point represents a service location, while the shaded polygons represent the number of services located within each LSOA.

---

## Map Components

The map includes several key cartographic elements that support interpretation and spatial understanding:

### Service Locations
Purple points represent the locations of supermarkets and pharmacies. These points indicate where essential services are physically located within the city.

### LSOA Polygons
The map uses Lower Layer Super Output Areas (LSOAs) as the primary spatial unit of analysis. LSOAs are commonly used in UK spatial analysis and allow service distribution to be examined at a neighbourhood scale.

### Choropleth Classification
LSOAs are shaded according to the number of essential services within each area. The classification scheme includes four categories:

- **0–1 services** – Very low service availability
- **2–3 services** – Moderate service availability
- **4–6 services** – High service availability
- **7–12 services** – Very high service concentration

Darker shades represent areas with a higher concentration of services.

### Cartographic Elements
The map also includes standard cartographic features such as:

- **Legend** explaining map symbols and service categories
- **North arrow** indicating map orientation
- **Scale bar** showing distances in kilometers
- **Basemap** providing geographic context for surrounding areas

---

## Spatial Distribution Patterns

The spatial pattern displayed on the map reveals a clear concentration of services within central Sheffield. Several LSOAs in the city centre fall within the highest service categories, indicating strong clustering of supermarkets and pharmacies in commercial districts.

Moving away from the urban core, the density of services decreases. Peripheral neighbourhoods and suburban areas are more frequently classified within the lowest service category (0–1 services). This reflects common urban spatial structures where retail and healthcare services concentrate in central areas with higher population density and economic activity.

Secondary service clusters can also be observed along major transport corridors and district centres. These areas function as local hubs that serve surrounding residential neighbourhoods.

---

## Accessibility Implications

Access to essential services directly affects residents' quality of life. Areas with a high concentration of services benefit from shorter travel distances and a greater number of options for food and healthcare needs.

In contrast, neighbourhoods with fewer services may require residents to travel longer distances. This can particularly impact:

- Elderly populations
- Individuals without access to private vehicles
- Low-income households
- Residents with mobility limitations

Public transport availability, walkability, and road connectivity therefore play an important role in determining real accessibility beyond simple service counts.

---

## Potential Service Gaps

The map highlights several peripheral areas where only a small number of services are present. These areas may represent potential service gaps or emerging service deserts.

Identifying such locations is important for urban planners and policymakers, as targeted interventions could improve service access. Possible strategies include:

- Encouraging retail development in underserved areas
- Supporting local pharmacies and small food retailers
- Improving public transportation links to major service centres

---

## Relevance to Urban Change and Gentrification

Changes in the spatial distribution of essential services can also provide insights into broader urban transformation processes. An increasing concentration of supermarkets and pharmacies often accompanies economic investment, population growth, and neighbourhood revitalization.

For researchers studying neighbourhood change or gentrification, monitoring service accessibility over time can serve as an early indicator of urban transformation. When combined with other indicators such as housing prices, demographic change, and business turnover, service distribution can reveal emerging patterns of socio-economic change.

---

## Methods

The map was produced using Geographic Information Systems (GIS) techniques.

### Data Sources

- Supermarket locations
- Pharmacy locations
- Sheffield LSOA boundary data
- OpenStreetMap basemap

### GIS Workflow

1. Collect service location datasets
2. Import LSOA boundary shapefile
3. Map supermarket and pharmacy locations as point features
4. Perform a **spatial join** to count services within each LSOA
5. Classify service counts into four categories
6. Create a **choropleth map** to visualize service distribution
7. Add cartographic elements (legend, north arrow, scale bar)

---

## Repository Structure


---

## Software Used

- ArcGIS Pro / QGIS
- OpenStreetMap Basemap
- GIS Spatial Analysis Tools

---

## Future Work

Future research could extend this analysis by incorporating:

- Network-based travel time analysis
- Public transportation accessibility
- Population demographic data
- Temporal analysis of service changes
- Integration with neighbourhood change indicators

These improvements would provide a deeper understanding of how service accessibility affects urban inequality and neighbourhood transformation.

---

## Author

Marvis Esivue

GIS Spatial Analysis Project  
Accessibility to Essential Services in Sheffield

