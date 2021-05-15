# uep239-final-project
My final project for UEP-239

Abstract project summary:
This project highlights where Boston-area recent college graduates should look to live if they're seeking low rent, a high concentration of similarly-aged neighbors, good local food, and good access to transit. I will use 5 sets of data focused on the Boston Metropolitan Area to assess suitability by creating my own 0-1 index for each factor and generating a final weighted suitability map at the end indicating what are thus the most desirable neighborhoods. Follow along for maps that will tell you where in Boston you'd encounter the highest rent or the most friends your age if you're a recent grad too!

Description of all the data files in the data directory, sources, preprocessing steps:
First, the data directory "project_data" includes ACS files on age/sex and financial characteristics. These are used for demographic suitability analyses and are sourced from the U.S. Census Bureau 2015-2019 American Community Survey 5-Year Estimates. Next, the project uses data on farmers' markets and T stops sourced from the MassGIS geospatial data portal. The MBTA Bus Stops are sourced from MassDOT. The folders MPO_Boundaries and OUTLINE25K_POLY delineate our geographic areas of interest, while "tl_2010_25_zcta510" includes the zip code tabulated areas that will be our project unit of analysis (source: 2010 ACS data). MPO_Boundaries is sourced from the Massachusetts Department of Transportation.

Instructions on how to run project notebook: 
Welcome to anyone who may have come across my Urban and Environmental Planning final project! To run my notebook, know that you will need to have Miniconda or Anaconda installed as a primary dependency. First you will need to clone my repository and once you've navigated inside my final project folder, you will use my environment.yml file to create a new environment on your computer. You can do this by typing "conda env create -f" in your terminal, then activating by writing "conda activate myenv" and verifying by checking with "conda env list." 
Next, you can launch jupyter lab to run the notebook by typing "jupyter lab" in your terminal. 
you should instruct them to create a new environment using your environment.yml file, activate the environment, launch jupyterlab and open up your project notebook. To be more thorough and courteous, you should also include the relevant commands and notify the end user that they need to have either Miniconda or Anaconda installed as a primary dependency. If you have configured your repo to work with Binder, include the Launch Binder button and state that they could either run it via Binder or on their local machine, and then provide instructions to do so. Does this clear it up?

Brief overview of all Python packages used:
For this project, I'll be using NumPy, Pandas and Geopandas to work with both spatial and nonspatial tabular data. I am working in Jupyter Lab with Python 3. Other key plotting materials include contextily and matplotlib.

List of acknowledgements and referenced resources:
Thank you to Uku-Kaspar Uustalu and Kyle Monahan for the guidance and reference code provided throughout this process! https://github.com/tuftsdatalab
Other extensively used resources include GeoPandas documentation for plotting and Contextily for its basemaps.
