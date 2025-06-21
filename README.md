# burned_area_product_analysis
Analysis of burned area products for given regions using the Google Earth Engine (GEE) Python API using a Jupyter Notebook. Note that if you use Google Colab you will need to edit the authentication to include access to Colab.

The burned area products (such as MCD64A1, FireCCI v5.1) are either stored in the GEE Data Catalog, GEE Community Catalog or locally as assets within GEE. Ensure you are registered on a project with GEE to be able to have access.

The analysis can be used to find the total burned area, and annual seasonality where applicable.
* `Analyse_BA_RESOLVE.ipynb` finds the burned area for each northern hemisphere boreal/tundra ecoregion as per the RESOLVE (2017) boundaries for FireCCI v5.1 and MCD64A1 only.
* `Analyse_BA_self_defined.ipynb` finds the burned area for self-defined areas in North America and Eurasia for all products.
* `Analyse_BA_seasonality.ipynb` finds the monthly burns for a given year and for all applicable products.
* `Plot_BA_from_csv.ipynb` produces several plots based on the burned area saved to csv files. This Notebook does not require GEE authentication.

Each product has its own set of area boundaries depending on pixel scale to be compatible with GEE's processing limits. These are set for North American boreal and tundra regions, central/northern Siberia and south Siberia. See our paper: https://doi.org/10.3390/rs16173306 for more details.

If you would like access to the products stored as assets on my GEE account, please email me at andell84@bas.ac.uk for permission.
