# Saline System Database Visualizer

This project is the final assignment for the **Python Foundation for Spatial Analysis** course offered by **Spatial Thoughts** <https://spatialthoughts.com/> and guided by Ujaval Gandhi and Vigna Purohit.

The National Geology and Mining Service (Sernageomin) of Chile maintains a repository of publicly accessible databases on their website: <https://repositorio.sernageomin.cl/home>

In 2023, Sernageomin released a database on saline systems titled "Composición química y mineralogía de los salares de Pajonales, La Isla, Las Parinas y Aguilar, regiones de Antofagasta y Atacama, Chile" (Chemical Composition and Mineralogy of the Salt Flats of Pajonales, La Isla, Las Parinas, and Aguilar, Regions of Antofagasta and Atacama, Chile). This database contains detailed information on four saline systems.

The data is provided in XLSX format and is organized into five sheets:
+ Crust Mineralogy
+ Crust Chemistry
+ Water Chemistry
+ Isotopic Data
+ Sample Locations

This project utilizes the published data to create an interactive HTML map. The map displays the locations of the samples, and when a sample is clicked, a pop-up window appears with the following information:
+ Classification of the most abundant minerals
+ Sample IDs
+ The three most abundant minerals and their classifications
+ A pie chart showing the proportion of the main anions of the saline crust: carbonate, sulfate, and chloride.

The dataset includes values below the detection limit and missing carbonate data for certain samples, particularly from the Las Parinas and Pajonales salt flats, which were replaced with 0 to facilitate calculations. This approach, while necessary, introduces artifacts that must be accounted for in subsequent analysis.

The database file can be downloaded from: <https://repositorio.sernageomin.cl/items/fe59c11b-c077-4fd7-821a-e03cc19972ab>
