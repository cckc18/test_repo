## Instruction for generating EDA data


Generate processed data per SHA/brick: 

1) run the python script 'main.py' to generate preliminary input file in data_input folder; use '-h' to see detailed options

2) run jupyter notebook 'data_processing.ipynb' to generate processed data and modeling input files

3) run jupyter notebook 'Maps.ipynb' to generate Voronoi maps

data_raw_csv folder stores raw data in CSV format

data_processed folder contains output files

data_input folder contains input files from which one can modify the input

a) COLUMN_NAMES: rename feature names in output files

b) FACTORS_EXCLUDED: exclude features in all output files

c) FACTORS FOR MODEL: edit features to be included as the model input




