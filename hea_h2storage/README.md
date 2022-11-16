The cleaned ML-ready HydPARK database as per (https://pubs.acs.org/doi/abs/10.1021/acs.jpclett.9b02971) is at HYDPARK_ML_ready.csv

Some pre-extracted MP data is at ElementalH_Ef_MP.csv, to reproduce you will need your own API key

Main jupyter notebook is metal_hydride_ML_v4.ipynb which contains:
- Model by default is now trained on HydPARK+ feature and data augmentation by default (https://chemrxiv.org/articles/preprint/Data-Driven_Discovery_and_Synthesis_of_High_Entropy_Alloy_Hydrides_with_Targeted_Thermodynamic_Stability/13697464) 
- Added in an H/M model
- Screens a more comprehensive chemical space and identifies Pareto optimal materials
- To use for future investigation of active learning
- Large chunks of old content (mainly plotting experimental and DFT results, SHAP analysis, etc) commented out for now but retained for when new batches of experimetnal/DFT data arrive

