# somatic_mutations_protein_abundance

Raw data is available at:  
https://drive.google.com/file/d/1Q4P8kpQ7sx3CKaJ-GrI1fvVj96NH6VtT/view?usp=sharing

data_processing.ipynb:  
Draws on raw data  
Creates new directory "data_computed/data_processing_[current_datetime]" with processed data

data_viz.ipynb:  
Draws on processed data in "data_computed/data_processing_[current_datetime]" (adjust folder name in code)  
Creates new directory "data_computed/data_processing_[current_datetime]/figures" with (partial) figures

r_alluvial_plot.ipynb:  
R script for the alluvial plot comparing FoldX and AlphaMissense classifications
