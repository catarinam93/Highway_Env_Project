# Highway-Env-Tests

**Notebooks:**
- highway.ipynb: Notebook onde são treinados os modelos
- features_extraction.ipynb: Notebook onde são extraídas as features
- pca_clusters.ipynb: Notebook com pre processamento e onde são extraídas as features PCA com variância acima de 90%

**Datasets:**
- summary_df_combined_updated: Dataset onde estão as features extraídas
- summary_df_combined_updated_1: Dataset onde estão as features extraídas e com pre processamento inicial
- pca_dataset_updated: Dataset com as features PCA extraídas
- general_dataset: Dataset com as features e com pre processamento total

**Outros Ficheiros:**
- environment_config: Consiguração do ambiente de cada modelo
- ignored_models: Modelos que estão a dar erro na extração de features (os que têm lidar e time to collision)
- highway_* : Pastas dos modelos treinados
- pyhard_v1: Ficheiros da geração do pyhard
