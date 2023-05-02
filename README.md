-- WORKING WITH (software_dev_v1.yml) --
FIRST STEP
I forked the assignment repository and downloaded the two files.
SECOND STEP
I recreated the conda environment using the commands: conda env create -n geo_soft_conda --file software_dev_v1.yml

THIRD STEP
I installed the geoplot package which is useful for geospatial data. I used the following code: conda install -c conda-forge geoplot

FOURTH STEP
I exported the file using the following code: conda env export --from-history>geo_soft_conda1.yml

I made a comit to the GitHub folder ‘geo-software-dev’
