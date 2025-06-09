# lagos-waste-analysis
DESIGN OF METHOD BASED ON BLOCKCHAIN TECHNOLOGY FOR ASSESSMENT OF ILLEGAL WASTE MANAGEMENT FOR LOW CARBON URBAN DEVELOPMENT OF LAGOS, NIGERIA.


## 🌍 Overview
This project explores waste infrastructure, emissions, and spatial accessibility in Lagos, Nigeria using Python-based geospatial tools. The goal is to support informed urban planning by analyzing the distribution and access to legal/illegal dumpsites, street networks, and related services.


## 📘 Notebooks

| Notebook | Description | Colab |
|----------|-------------|-------|
| [satellite_segmentation_sam.ipynb](https://github.com/ChizobaNzeakor/lagos-waste-analysis/blob/main/satellite_segmentation_sam.ipynb) | Segment satellite imagery using Segment Anything Model (SAM) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ChizobaNzeakor/lagos-waste-analysis/blob/main/satellite_segmentation_sam.ipynb) |
| [carbon_emissions_waste_ikeja_ipynb.ipynb](https://github.com/ChizobaNzeakor/lagos-waste-analysis/blob/main/carbon_emissions_waste_ikeja.ipynb) | Estimate carbon emissions from dumpsites and visualize with Folium | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ChizobaNzeakor/lagos-waste-analysis/blob/main/carbon_emissions_waste_ikeja.ipynb) |
| [kaivopuisto_building_visualization.ipynb](https://github.com/ChizobaNzeakor/lagos-waste-analysis/blob/main/kaivopuisto_building_visualization.ipynb) | Visualize Kaivopuisto buildings using OSM and Contextily | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ChizobaNzeakor/lagos-waste-analysis/blob/main/kaivopuisto_building_visualization.ipynb) |
| [ikeja_street_network_accessibility.ipynb](https://github.com/ChizobaNzeakor/lagos-waste-analysis/blob/main/ikeja_street_network_accessibility.ipynb) | Analyze street network access to dumpsites using OSMNX & NetworkX | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ChizobaNzeakor/lagos-waste-analysis/blob/main/ikeja_street_network_accessibility.ipynb) |
| [illegal_dumpsite_locations_mapping.ipynb](https://github.com/ChizobaNzeakor/lagos-waste-analysis/blob/main/illegal_dumpsite_locations_mapping.ipynb) | Plot illegal waste dumpsites on interactive maps | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ChizobaNzeakor/lagos-waste-analysis/blob/main/illegal_dumpsite_locations_mapping.ipynb) |
| [lagos_state_boundary_extraction.ipynb](https://github.com/ChizobaNzeakor/lagos-waste-analysis/blob/main/lagos_state_boundary_extraction.ipynb) | Extract Lagos boundary from OpenStreetMap using OSMNX | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ChizobaNzeakor/lagos-waste-analysis/blob/main/lagos_state_boundary_extraction.ipynb) |
| [lagos_buildings_waste_infrastructure.ipynb](https://github.com/ChizobaNzeakor/lagos-waste-analysis/blob/main/lagos_buildings_waste_infrastructure.ipynb) | Map waste infrastructure and buildings across Lagos | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ChizobaNzeakor/lagos-waste-analysis/blob/main/lagos_buildings_waste_infrastructure.ipynb) |


---
## 🚀 Run the Notebooks

- Open locally using **Jupyter Notebook** or **JupyterLab**
- Launch in **Google Colab** by pasting this repo's notebook URL
- Use **Binder** (requires repo + environment config) for full reproducibility

---

## 🔗 Key Libraries

- `osmnx`: for querying OpenStreetMap data
- `geopandas`: for spatial data handling
- `folium`: for interactive mapping
- `networkx`: for graph-based accessibility analysis
- `matplotlib`, `contextily`: for static map visualization

---

## 📌 Project Goals

- Evaluate gaps in legal waste service infrastructure
- Map building footprints and waste sites
- Analyze spatial accessibility and environmental inequality
- Provide a reproducible, open-source framework for Lagos spatial planning

---

## 📚 References

- [OSMNX](https://osmnx.readthedocs.io)
- [GeoPandas](https://geopandas.org)
- [Folium](https://python-visualization.github.io/folium)
- IPCC Guidelines for Greenhouse Gas Inventories
- Lagos Waste Management Authority (LAWMA)

---

## ❓ Questions to Explore

- What spatial inequality exists in access to legal waste infrastructure?
- How do informal dumpsites align with dense residential areas?
- How can remote sensing validate or enhance infrastructure datasets?




