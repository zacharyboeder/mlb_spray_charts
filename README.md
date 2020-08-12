# mlb_spray_charts
Using MLB savant pitch-by-pitch data to create spray charts superimposed on an image of a baseball field

#Detailed Description
baseballsavant.mlb.com makes avaiable the pitch-by-pitch data for every player in the mlb. Accessing this data, you can create a spray chart of balls put into play using this data. Look at "Example image 1" and "Example image 2" for examples of MLB spray charts using various software and images. "Example image 3" is the exact image we are aiming for here. To do this, we will take the following steps: 

  1. Download data as .csv from baseballsavant.mlb.com
  2. Upload .csv file into RStudio
  3. Install and load all necessary packages in RStudio
  4. Ensure the variables needed are numeric (cleaning the data)
  5. Plot the scatter plot
  6. Superimpose the image of a baseball field underneath the scatterplot and adjust as needed
  8. Clean up the aesthetics of the chart
  7. Create a function to replicate spray chart for any player over any number of years

#Packages needed
1. ggplot2
2. png
3. grid
