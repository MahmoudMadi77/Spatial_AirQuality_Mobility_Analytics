# Ultimate Final Code – Full Project Repository

This folder contains the **complete implementation and dataset** for the project _Traffic & Air Pollution Analysis in Chicago_, including code, data files, and result visualizations.

---

## Contents

### Notebook & Code
- **`True Final FDS Project.ipynb`**  
  Main Jupyter notebook with the full analysis pipeline: data preprocessing, spatio-temporal aggregation, clustering (DBSCAN), and visualizations.

### Plots
- All final output plots are organized in the [`Plots/`](./Plots) folder.
  - Includes: DBSCAN clusters, heat maps, data exploration visuals, and joined-data maps.

### Data
- The [`Data/`](./Data) folder contains all required input files for analysis:
  - **Chicago air quality data**: split across **19 CSV files** named `chicago_eclipse_data_part_X.csv`.
  - **Taxi data**: compressed as `taxi_data.rar` due to large file size.
  - **Shapefiles** for Chicago community areas (e.g. `.shp`, `.dbf`, `.shx`, etc.) for geospatial operations.

### Presentation
- Presentation of our project in Powerpoint

---

## Notes

- The project requires extracting `taxi_data.rar` before use.
- Make sure all shapefiles stay in the same folder to ensure they load correctly in GeoPandas.
- Run the notebook from this folder to ensure relative paths work as expected.

---

## Usage

1. Clone the repository.
2. Extract `taxi_data.rar` inside the `Data/` directory.
3. Open and run `True Final FDS Project.ipynb`.

---

For a high-level overview, methodology, and team details, refer to the main project [`README.md`](../README.md) in the root directory.
