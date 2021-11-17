# Greetings! 

Welcome to my GitHub site.  The most important stuff (the more sophisticated projects, a.k.a., "portfolio" repos) is still primarily "work in progress". However, you can also find (1) less advanced work related to the many classes I've taken since spring 2020 and (2) some "demo" repos showing some examples of code I've done completely outside GitHub.

## Some repos of note
### GPS Tracks
This is an app that will have four parts: a React frontend (_gpstracks-frontend_), a Node.js user management API (_users-api_), a Node.js authorization API (_auth-api_) and a Node.js GPS tracks database manager (_tracks-api_).  The first three are operational while the last exists only on paper. While the frontend runs, it needs a great deal of work to implement the project.

The _gpstracks_ repo brings the four components together using git submodules.

### Courses database
This app is structurally similar to GPS Tracks and reuses the _users-api_ and _auth-api_ repos first developed in that project. It adds a customized React frontend (_courses-frontend_) and a Node.js courses database manager (_courses-api_).  As with GPS Tracks, this is a work in progress: the frontend needs development and _tracks-api_ still needs to be started.

The related but not-yet-created _courses_ repo will bring the four components together using git submodules.

### check_network
This is a Python app to do some basic monitoring of your internet connection (on your desktop or laptop).  Briefly, it cycles through a list of URLs that are "pinged" at a regular interval to see if they respond normally.  Results are saved in a log file.  This program is highly configurable and comes with utility scripts to run it as a daemon and to manage the log.

### mainSite
My main personal Web site.

### Some examples of past work in Python, Fortran and C++.

#### Python: pythonExamples
_hpc_bin_: utility scripts related to running the WRF model on the NCAR supercomputer.

_jupyternb_: Jupyter notebooks for various research tasks.  Dominated by plotting scripts but also includes data-analytical code such as for finding the nearest model grid point to a specific lat/lon coordinate (e.g., the location of an automatic weather station) and interpolating a grid to a specific location.

_python_modules_: Some commonly used functions repackaged as modules (used heavily by the Jupyter notebooks).

_utils_: a simple utility for macOS that helps manage free space on Time Machine volumes.

#### Fortran: fortranExamples
_geodesic_grids_: Regrid from rectilinear lat/lon grids to a geodesic mesh.  Reads/writes netCDF.

_seaice_: Convert binary, remote sensing-based sea ice data into a different binary format used by the meteorological forecast model WRF.  Includes supporting scripts.

#### C++: CplusplusExamples
_cs819_: Fairly simple example from a graduate school class.  

_Computer Science M.Sc._: Unfortunately the _extensive_ code from my Master’s thesis appears to be lost.

<!--
**dbreusch/dbreusch** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:
👋
- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
