# burned_area_product_analysis
Analysis of burned area products for given regions using the Google Earth Engine (GEE) Python API using a Jupyter Notebook. Note that if you use Google Colab you will need to edit the authentication to include access to Colab.

The burned area products (such as MCD64A1, FireCCI v5.1) are either stored in the GEE Data Catalog, GEE Community Catalog or locally as assets within GEE. Ensure you are registered on a project with GEE to be able to have access.

The analysis can be used to find the total burned area, and annual seasonality where applicable.

Each product has its own set of area boundaries depending on pixel scale to be compatible with GEE's processing limits. These are set for North American boreal and tundra regions, central/northern Siberia and south Siberia.

If you would like access to the products stored as assets on my GEE account, please email me at andell84@bas.ac.uk for permission.
