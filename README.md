# Highway-Env-Tests

**Notebooks:**  
- **highway.ipynb:** Notebook where the models are trained  
- **features_extraction.ipynb:** Notebook where features are extracted  
- **pca_clusters.ipynb:** Notebook with preprocessing and where PCA features with variance above 90% are extracted  

**Datasets:**  
- **summary_df_combined_updated:** Dataset containing the extracted features  
- **summary_df_combined_updated_1:** Dataset containing the extracted features with initial preprocessing  
- **pca_dataset_updated:** Dataset with the extracted PCA features  
- **general_dataset:** Dataset containing the features with full preprocessing  

**Other Files:**  
- **environment_config:** Environment configuration for each model  
- **ignored_models:** Models that produce errors during feature extraction (those with LiDAR and time to collision)  
- **highway_*:** Folders containing the trained models  
- **pyhard_v1:** Files for the generation of pyhard  
