# somatic_mutations_protein_abundance

Raw data is available at:  
https://drive.google.com/file/d/1Q4P8kpQ7sx3CKaJ-GrI1fvVj96NH6VtT/view?usp=drive_link

data_processing.ipynb:  
Draws on raw data  
Creates new directory "data_computed/data_processing_[current_datetime]" with processed data for each time the script is run

data_viz.ipynb:  
Draws on processed data in "data_computed/data_processing_[current_datetime]"
Adjust the folder name in the second cell of the notebook to match the name of your directory containing the processed files  
Creates new directory "data_computed/data_processing_[current_datetime]/figures" with (partial) figures

r_alluvial_plot.ipynb:  
R script for the alluvial plot comparing FoldX and AlphaMissense classifications

summary_statistics.ipynb:
Creates all summary statistics mentioned throughout the paper
