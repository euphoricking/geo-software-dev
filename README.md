**-- WORKING WITH (software_dev_v1.yml) --**

**FIRST STEP**

I forked the assignment repository and downloaded the two files.


**SECOND STEP**

I recreated the conda environment using the commands: conda env create -n geo_soft_conda --file software_dev_v1.yml

<img width="460" alt="step 1" src="https://user-images.githubusercontent.com/31923777/235752169-642eb1b0-6fed-4d5b-aa37-8c8632c9b771.png">

**THIRD STEP**

I installed the geoplot package which is useful for geospatial data. I used the following code: conda install -c conda-forge geoplot

<img width="399" alt="second step" src="https://user-images.githubusercontent.com/31923777/235752220-d003ef9a-c826-4ad4-87f5-f7990da7d6d3.png">


**FOURTH STEP**

I exported the file using the following code: conda env export --from-history>geo_soft_conda1.yml

<img width="461" alt="third step" src="https://user-images.githubusercontent.com/31923777/235752333-cd8628c2-bd04-433c-be7c-f3949a9b5f85.png">


I made a comit to the GitHub folder ‘geo-software-dev’
