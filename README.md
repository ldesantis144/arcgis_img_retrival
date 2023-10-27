# arcgis_img_retrival
First part: 
  
  A. Takes a dataset, gets long, lat, date, and time from the dataset, and saves this information in an external file for faster processing.

Second part: 
  
  B. Processes the external dataset file, and pulls the longitude, latitude, date, and time for each data point.

  C. Removes data points that fall within the same bounding box as another point to prevent duplication
  
  D. Constructs bounding box by centering longitude and latitude provided, and moves the view of the current layer to those coordinates. 
  
  E. Uses the camera to take an image, then exports image as TIFF file for every set of coordinates.

  Authors: Laura DeSantis, Ethan Patten
