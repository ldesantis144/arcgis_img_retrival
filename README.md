# arcgis_img_retrival
First part: 
  
  A. Takes a dataset, gets long, lat, date, and time from the dataset.
  
  B. Removes data points that fall within a long of .75 and a lat of .5 of each other to prevent duplicate images

  C. Saves this information in an external file for faster processing.

Second part: 
  
  D. Processes the external dataset file, and pulls the longitude, latitude, date, and time for each data point.
  
  E. Constructs bounding box by centering longitude and latitude provided, and moves the view of the current layer to those coordinates. 
  
  F. Uses the camera to take an image, then exports image as TIFF file for every set of coordinates.

  Authors: Laura DeSantis, Ethan Patten
