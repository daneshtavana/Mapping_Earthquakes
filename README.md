# Mapping_Earthquakes
UCB Extension Module 13 Challenge

## Basic Project Plan
### Purpose
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

### Tasks
To complete this project, use a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. Then add the data to a map.

### Approach
Our approach will be to use the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. I’ll use the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

We'll need to set up a Mapbox account and get the API token needed to create geographical maps

## Create Example Maps as Branches and check into main

Follow these steps to create a branch off of the master branch:
#### First, Navigate to your repository on your computer
#### Make sure you’re on the master branch by typing: git branch #### If you’re not on the master branch, type: git checkout master
#### Pull the changes from the master branch by typing: git pull
#### Create a new branch by typing: git checkout -b [name_of_your_new_branch]

Follow these steps to push changes to a new branch:
#### Type: git status
#### Add the folders and files by typing: git add
#### Confirm the correct files will be added by typing: git status
#### Commit the changes by typing: git commit -m
#### Push the changes to the branch by typing: git push --set-upstream origin [name_of_your_new_branch]


## Example 1: Simple_Map 

### To open the index.html file in the browser:
Open the command line and navigate to Mapping_Earthquakes/Simple_Map folder. The index.html file should be in the top-level of that folder. On the command line, type python -m http.server and press Enter. Using a web browser access http://localhost:8000/

## Example 2: Mapping-Single_Points 

### To open the index.html file in the browser:
Open the command line and navigate to Mapping_Earthquakes/Mapping-Single_Points. The index.html file should be in the top-level of that folder. On the command line, type python -m http.server and press Enter. Using a web browser access http://localhost:8000/