Each set of data includes a remote sensing image and annotated data corresponding to the remote sensing image, including the rotating bounding box of the object in the remote sensing image and its object type. The object types include: Airplane, Ship, Vehicle, Basketball Court, Tennis Court, Football field, Baseball field, Intersection, Roundabout, Bridge.
  

The annotation data is stored in the xml file, in which x.xml stores the json text of the training set image x.tif annotation data, the objects field stores the annotation information of different objects, and the annotation information of each object includes the possibleresult field, which stores the object. Category name; points field, stores five points, of which the first and fifth points are the same, representing a quadrilateral, corresponding to the rotating bounding box of this object. Please refer to the files in the dataset for details of the labeled data.



The data set is divided into three parts: training set (5000 pictures), preliminary test set (1000 pictures) and final test set (2000 pictures). According to the schedule and different stages, the test set will only publish images but not label data. .
