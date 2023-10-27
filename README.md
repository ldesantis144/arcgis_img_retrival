# arcgis_img_retrival
First part: 
  
  A. Takes a curated dataset in ArcGIS, gets long, lat, date, and time from the ArcGIS dataset, and saves this information in an external file for faster processing.

Second part: 
  B. Processes the external dataset file, and pulls the longitude, latitude, date, and time for each data point. 
  C. Constructs bounding box by centering longitude and latitude provided, and moves the view of the current layer to those coordinates. 
  D. Uses the camera to take an image, then exports image as TIFF file for every set of coordinates. 
