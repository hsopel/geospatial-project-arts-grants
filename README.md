# Introduction to geospatial analysis in python
Using the techniques taught in these notebooks, I created a map to show the impact that grants from the Metro Nashville Arts Commission have on schools in Davidson County. I decided to focus specifically on grants given by the Nashville Children Theatre (NCT). NCT uses the grant money to make a class field trip to attend a production affordable for all students. Having worked on a show at NCT, I've seen first-hand how meaningful this experience is to the students.

I used geopandas, spatial joins, and folium to create this map with school district boundaries and markers for each school that received a grant, color coded by the number of students impacted. I used layer control to make it possible for the user to focus on specific school districts. Interactive map can be found in the notebooks folder --> geopandas_project.ipynb

![Map](/maps/arts_grants_map.png)

![zoomed_map](/maps/zoomed_in_map.png)

## Class Instructions
### 1. Getting Started With the Geospatial Environment
To run the notebooks for this project, you will need some additional python packages.
You can install these using conda.
We have provided an `environment.yaml` file with the packages to be used for the project.
This `environment.yaml` file will create a new environment for you called `geospatial`.

Open your terminal, and `cd` into this project.
From there run:
```bash
conda env create -f environment.yaml
```

Once this has been created for you, it is easiest to run from the command line.
For example, to open a new session with jupyter run:
```
conda activate geospatial
jupyter notebook
```
To close the notebook, type ctrl-c
To stop using the geospatial environment:
```
conda deactivate
```


### 2. Introduction slide deck and notebooks  
##### slides
 - importance of location to some kinds of analysis
 - `geopandas` GeoDataFrames
 - types of geometry
 - intro to coordinate reference systems
 - spatial joins
 - adding context with `folium` maps
    - constructing maps
    - markers
    - marker clusters
    - popups
##### notebooks
- geospatial_intro.ipynb (geopandas and foilum)
- qualitative_maps.ipynb (geopandas and matplotlib styling elements)
- choropleth_tutorial.ipynb (geopandas choropleth)
