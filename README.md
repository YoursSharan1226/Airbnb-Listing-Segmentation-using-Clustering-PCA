# Airbnb Listing Segmentation using PCA and K-Means
## Project Overview
This project implements an end to end unsupervised machine learning pipeline to segment NYC Airbnb listings using Principal Component Analysis (PCA) and K-Means clustering. The objective was to identify meaningful listing and host segments, reduce dimensional complexity while preserving information, and visualize geographic cluster distributions using interactive mapping.
## Business Context
### Understanding listing segmentation helps:
* Identify distinct property and host behavior patterns
* Detect pricing and availability trends
* Analyze geographic concentration of listing types
* Support data-driven strategic decisions
* This project clusters listings into interpretable segments that reflect structural patterns in the NYC Airbnb market.
## Technical Approach
### Data Preprocessing
* Cleaned missing and inconsistent values
* Standardized numerical features
* Selected relevant variables for clustering
### Dimensionality Reduction
**Applied Principal Component Analysis (PCA) to:**
* Reduce feature dimensionality
* Retain approximately 98% of total variance
* Improve clustering stability and interpretability
### Clustering
* Implemented K-Means clustering
* Determined optimal number of clusters
* Identified four distinct listing segments
* Analyzed cluster centroids for interpretability
### Geospatial Visualization
**Used Folium to:**
* Map clustered listings interactively
* Visualize borough-level spatial distribution
* Identify geographic concentration patterns
## Results
* Segmented listings into four distinct market groups
* Preserved 98% variance after dimensionality reduction
* Revealed spatial clustering trends across NYC boroughs
* Generated interpretable host and listing behavior groupings
## Technologies Used
* Python
* Pandas
* NumPy
* Scikit-learn
* PCA
* K-Means
* Folium
* Matplotlib
## Potential Improvements
* Evaluate clustering performance using Silhouette Score or Davies-Bouldin Index
* Compare results with DBSCAN or hierarchical clustering
* Convert notebook into modular production-ready pipeline
* Deploy interactive map using GitHub Pages
