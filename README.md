# Introduction
In this project, I performed supervised classification for Land Use and Land Cover (LULC) from provided EuroSAT dataset using simple Decision Tree algorithm leveraging Dask parallel computing and incorporating hyperparameter optimization to find the best parameters for the task.

I used Decision Tree algorithm for the classification since I extracted only 4 features from the dataset (Mean, Median, Range, and NDVI index), assumed to be simple enough to not using more sophisticated algorithm such as Random Forest or ANN. Those statistical features were extracted using Rasterio and stored into Dask dataframe. Hyperparameter optimization was performed to find the best Decition Tree parameters combination for the task. The decision tree algorithm resulted in prediction scores after validation, feature importance visualized in histogram, and classification report for each LULC type.

## Implementation
Download the Jupyter Notebook 'hpo_assignment.ipnyb'.

Upload the file to CRIB where the data is located (since moving the data is not convenient due to the very big size).

Run the cells accordingly.
