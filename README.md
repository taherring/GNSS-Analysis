## Documentation overview
This notebook reads and displays velocity fields and time series from the NGF (EarthScope data center), UNR (University Nevada Reno), and JPL (Jet Propulsion Laboratory).  Most likely additional packages such as folium, pandas, numpy, ipywidgets, matplotlib, tabulate, geopy, json will need to be installed.  Conda installations from conda-forge should be possible for all packages.

The widget interface at the bottom of the notebook has three cells:

<b>Availability:</b> The “Latest NGF”, “Latest UNR”, and “Latest JPL” buttons must be used the first time the Notebook is run to create the data directory and subdirectories for each center that will used to save JSON files with information about all sites at the centers and time series files from each center as they are requested.  Latest updates should be selected to ensure the most up-to-date information is available.  The Availability check can used to see what is known about a 4-char code site name at each of the centers.

<b>Map:</b> The Map interface allows locations of sites, along with other sites within a user-specified radius to be plotted, along with 3-D velocities if available and selected.  Distance table for the 10 nearest sites to a site can be generated.

<b>Timeseries:</b> The Time series interface allows time series to be detrended, with optionally breaks from the EarthScope database removed.  Time series from different sites and centers can be overlayed.  Different backends can be used for plotting time series, with the ipympl backend allowing zooming and saving and the interactive one allowing identification of points.  The default inline backend should work on all systems.  The other backends may not work on all systems. 

At the very bottom of the NoteBook is an NGF_test cell which may need to be executed to access Earthscope (user registration needed.

All of the cells in the Notebook can be run, and the widgets and additional documentation will be at the bottom of the Notebook.  The code should run in a Jupyter Notebook or VSCode.

