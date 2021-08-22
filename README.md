# CFG-FinalProject

Welcome to out project!
![team](GirlsWhoCode.jpeg)

Team: Chloé Koura, Irina Mateescu, Mayumi (Mayu) Hamaoka, Patricia Pedro, Oludare (Dáre) Soniran


## Project folder structure
All the source code can be found under team_project.ipynb, which can be run as a normal jupyter notebook.
We also saved all graphs and data separately. They are available in separate directories as seen in the tree directory structure below.

    [nina@Irinas-MBP CFG-FinalProject]$ tree
    .
    ├── README.md
    ├── data --------------------------> all our data saved to csv
    │   ├── basic_water.csv
    │   ├── children_receiving_ORS.csv
    │   ├── cholera_cases_1971_2016.csv
    │   ├── cholera_deaths.csv
    │   ├── cholera_fatality_rate.csv
    │   ├── diarrhea_deaths.csv
    │   ├── health_per_county.csv
    │   ├── inadequate_water.csv
    │   ├── safe_drinking_water.csv
    │   └── school_data.csv
    ├── graphs ------------------------> all our graphs saved to png
    │   ├── children_ORS.png
    │   ├── cholera_cases.png
    │   ├── counties_malaria_expected_behavior.png
    │   ├── counties_malaria_unexpected_behavior.png
    │   ├── counties_to_benchmark.png
    │   ├── counties_to_improve.png
    │   ├── diarrhea_deaths.png
    │   ├── diarrhea_inadequate_water.png
    │   ├── edu_malaria_county_corr_matrix.png
    │   ├── education_enrollment.png
    │   ├── education_gender_scatterplots.png
    │   ├── education_map.png
    │   ├── female_edu_malaria_county_corr_matrix.png
    │   ├── malaria_corr_matrix.png
    │   ├── male_edu_malaria_county_corr_matrix.png
    │   ├── pop_using_basic_drinking_water.png
    │   ├── pop_using_safe_water.png
    │   └── sleeping_under_bed_net_malaria_scatterplots.png
    ├── kenya_shapefiles --------------> shape files used through geopandas to generate our choropleth maps
    │   ├── ken_admbnda_adm1_iebc_20180607.cpg
    │   ├── ken_admbnda_adm1_iebc_20180607.dbf
    │   ├── ken_admbnda_adm1_iebc_20180607.prj
    │   ├── ken_admbnda_adm1_iebc_20180607.shp
    │   ├── ken_admbnda_adm1_iebc_20180607.shp.xml
    │   └── ken_admbnda_adm1_iebc_20180607.shx
    ├── new_data ----------------------> empty dir where all csvs and pngs will go once the code is run
    └── team_project.ipynb ------------> our code
    

## Steps for running the code
- Clone the git repo locally
- Install the following packages via pip (or conda, depending on preference):
  - pandas, numpy, sklearn, matplotlib.pyplot, matplotlib.dates, seaborn, plotly.graph_objects, geopandas, mpl_toolkits.axes_grid1
  - requests, logging, urllib.request, json, pprint, datetime, collections, pyodata, string
- Open team_project.ipynb in jupyter notebook
- Run the code (that simple :) )