# Week 4

## Tasks
- [X] Formulating research objectives for the project.

- [X]  Further Data Cleaning Steps including rectifying errors in data entries and taking care of sparse rows.
    - Analysing both the data files of year 2016 and 2020.
    - Cleaned the `data/simd2020 (1).csv` ([group-coursework-valhalla/notebooks/Data_Cleaning_simd_2020.ipynb](https://github.com/dmml-heriot-watt/group-coursework-valhalla/blob/main/notebooks/Data_Cleaning_simd_2020.ipynb)) to generate a clean dataset for year 2020 (`data/cleaned_2020.xlsx`).
		- Checked if the "id" column has value of "geom" column, then shifted all the columns to right.
    - Created pipeline ([group-coursework-valhalla/notebooks/preprocessed_combined_dataset.ipynb](https://github.com/dmml-heriot-watt/group-coursework-valhalla/blob/main/notebooks/preprocessed_combined_dataset.ipynb)) to combine the dataset (`data/combined_dataset.csv`).
		- Created dataframes of both the files.
		- Dropping unnecessary columns from SIMD 2020 dataframe.
		- Creating Data Dictionary for mapping header names.
		- Renamed headers in SIMD 2020 dataframe.
		- Added column "year" in both 2016 and 2020 dataframes.
		- Combined both the dataframes.

- [X] Initiated application of clustering algorithms on the dataset:
	
	* [1. K-Means](../notebooks/Kmeans_clustering.ipynb)
    * [2. BIRCH(Balanced iterative reducing and clustering using hierarchies) Clustering](../notebooks/BIRCH_Clustering.ipynb)
    * [3. Affinity Propagation Clustering](../notebooks/Clustering_Scripts.ipynb)
    * [4. DBSCAN Clustering](../notebooks/DBSCAN_Clustering_Output.ipynb)
	* [5. OPTICS Clustering](../notebooks/OPTICS_Clustering.ipynb)
	* [6. Gaussian Clustering](../notebooks/Clustering_Scripts.ipynb)
	* [7. K-medoid Clustering](../notebooks/KMediod_Cluster.ipynb)
    
    Applied the above clustering algorithms on a test dataset to ensure everything works as intended before applying it on our dataset.
