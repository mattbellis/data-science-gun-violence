# For use in capstone project

## Purpose

The purpose of our project is to explore school shootings in the US and spread awareness about what factors might be contributing gun violece by displaying gun control in each state.

[Google Slides](https://docs.google.com/presentation/d/1Fs6EmTkQ76oPxwkTp5y7ONc0uyhaCgDG3mYhUP3d-aE/edit?usp=sharing) for final presentation.

## Jupyter notebooks used in analysis

`sandbox_for_playing around.ipynb`:
This notebook was used to look into the datastes and understand the features in the datastes. We also used this notebook to play around with some numbers and make some plots to further understand the datasets. 


`generate_file_of_coordinates.ipynb`:
This notebook provides latitude and longitude coordinates for a list of cities that are stored in a parquet file. We did this beacuse there were 2000 entries and it took a long time to run through each of them individually, storing it into a parquet file made it easier for us to work with it.


`maps.ipynb`:
This notebook uses the parquet file made in "Generate_file_of_coordinates" to make maps of all the gun violence incidents. This helps us look at all the victims killed and victims_injured all over the US. We used tools like folium and base map for this process.


`Normalization.ipynb`:
This notebook combined all of our datastes to do further analysis. First we combined our population dataset with our school shootings dataset to get incidents per 100,000 people by state. We then did this for all the injuries and fatalities. Once we had all of these plots, we then combined population datset, school shootings dataset and our gun laws dataset to get the normalization for all the incidents and fatalities in each state distributed by the different types of gun laws. 

## Datasets

**Gun Ownership Dataset**:
https://www.rand.org/pubs/tools/TLA243-2-v2.html


**Population Dataset**: 
https://www2.census.gov/programs-surveys/popest/datasets/2020-2021/state/totals/NST-EST2021-alldata.csv


**School Shootings Dataset**:
https://www.gunviolencearchive.org/school-shootings



