# arcgis_img_retrival
Takes in a csv of data, getting longitude, latitude, date, and time for each data point. Constructs bounding box by centering longitude and latitude provided, and moves the view of the current layer to those coordinates. Once view has moved, it uses the camera to take an image, then exports image as TIFF file
