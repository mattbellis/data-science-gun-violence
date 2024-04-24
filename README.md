# For use in capstone project
Gun Ownership Dataset:
https://www.rand.org/pubs/tools/TLA243-2-v2.html


Population Dataset: 
https://www2.census.gov/programs-surveys/popest/datasets/2020-2021/state/totals/NST-EST2021-alldata.csv


Purpose:
The purpose of our project is to explore school shootings in the US by using data anlysis skills



Sandbox_for_play:
This notebook was used to look into the datastes and understand the features in the datastes. We also used this notebook to play around with some numbers and make some plots to further understand the datasets. 


Generate_file_of_coordinates:
This notebook provides latitude and longitude coordinates for a list of cities that are stored in a parquet file. We did this beacuse there were 2000 entries and it took a long time to run through each of them individually, storing it into a parquet file made it easier for us to work with it.


Maps:
This notebook uses the parquet file made in "Generate_file_of_coordinates" to make maps of all the gun violence incidents. This helps us look at all the victims killed and victims_injured all over the US. We used tools like folium and base map for this process.


Normalization:
This notebook combined all of our datastes to do further analysis. First we combined our population dataset with our school shootings dataset to get incidents per 100,000 people by state. We then did this for all the injuries and fatalities. Once we had all of these plots, we then combined population datset, school shootings dataset and our gun laws dataset to get the normalization for all the incidents and fatalities in each state distributed by the different types of gun laws. 
