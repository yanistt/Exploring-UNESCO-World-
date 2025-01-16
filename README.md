# Geospatial Knowledge Graph Project

This repository contains the RDF knowledge graph for exploring the relationship between **major cities** and **UNESCO World Heritage Sites**. The project uses geospatial data and SPARQL queries to answer complex questions and visualize results on a map.

---

## Files in the Repository

### 1. `cities.ttl`
This file contains the RDF data for major cities, including:
- **CityName**: The name of the city.
- **Population**: The population of the city.
- **Location**: The geographic coordinates of the city in WKT (Well-Known Text) format.
- **Language**: The official language spoken in the city.

---

### 2. `heritages.ttl`
This file contains the RDF data for UNESCO World Heritage Sites, including:
- **SiteLabel**: The name of the heritage site.
- **Location**: The geographic coordinates of the site in WKT format.

---

## How to Use This Repository

### 1. **Set Up a Triplestore**
To query and visualize the data, load the `.ttl` files into a triplestore like **GraphDB**:
1. Download and install [GraphDB](https://www.ontotext.com/products/graphdb/).
2. Create a new repository.
3. Import the `cities.ttl` and `heritages.ttl` files into the repository.

---

### 2. **Run SPARQL Queries**
Use SPARQL to query the knowledge graph. You can write queries to:
- Retrieve all cities or heritage sites.
- Find heritage sites within a specific distance of a city.
- Combine geospatial calculations with other data (e.g., population, language).

---

### 3. **Visualize Results**
Use **YASGUI** to visualize the results on a map:
1. Open [YASGUI](https://yasgui.triply.cc).
2. Connect to your GraphDB endpoint.
3. Run the SPARQL queries and switch to the **Map** tab to visualize the results.

---

## Replicating the Project
To replicate this project:
1. Download the `cities.ttl` and `heritages.ttl` files from this repository.
2. Load the files into a triplestore (e.g., GraphDB).
3. Run SPARQL queries to explore the data.
4. Use YASGUI or another tool to visualize the results.

---

## Resources
- **GraphDB**: [https://www.ontotext.com/products/graphdb/](https://www.ontotext.com/products/graphdb/)
- **YASGUI**: [https://yasgui.triply.cc](https://yasgui.triply.cc)
- **GeoSPARQL Documentation**: [https://opengeospatial.github.io/ogc-geosparql/](https://opengeospatial.github.io/ogc-geosparql/)

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact
For questions or feedback, please open an issue in this repository or contact the author directly.
