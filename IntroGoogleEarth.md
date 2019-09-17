# Google Earth, Lab Exercise

## Get Set...

Download [Google Earth](https://www.google.com/earth/versions/) If you have space constraints, let me know.

Google Earth uses satellite imagery and aerial photography along with a suite of mapping tools. Google Earth is not as robust as geographic information systems (GIS) like ArcGIS. If you run into limitations and need more power, the UMD library has an excellent set of resources within the [GIS and Spatial Data Center](https://www.lib.umd.edu/gis).

### Important Vocabulary
* GIS - geographic information systems
* Vector-based systems, use points, lines and polygons to create a map based on the real world
* Rastor-based systems use pictures in the form of grids. Grids are made of up columns and pixels, which use color to indicate different features.

_Note_ Google Earth uses raster-based images to render the earth's surface, and users use vector-based points to "draw" on top of the raster-image.

* Placemarks (also called points) - used to represent a point on the map (a town, house, feature)
* Paths (also called lines) - used to draw linear features, such as a road or river. Paths are made up of two or more points and are connected to create a line.
* Polygons - enclosed areas that can show the area of buildings, forests, etc.

## Explore
1. Open Google Earth
2. Search for Lakeland, College Park MD
3. What do you notice about the interface? What can you do?
  * Try going back in time. How much as Lakeland changed? What is different between April 1989 and the present?
  * Can you zoom in or out?

### Adding Info
4. Add a Placemark by clicking the thumbtack icon. You can change the color and add information, images, and links via the icon menu. You can adjust information, delete, and share online by left-clicking the icon you've just created.
  * Try changing the icon's shape and color (hint - click the upper right hand icon in the dialogue box)
5. Add a path. Click the path icon, name your path, and while the dialogue box is still open, use your mouse to create the path. Click save to close the dialogue box and save your path.
    * Try changing the properties of your path, including add a description, change the appearance of your path, and measure the path's length.
6. Create a polygon. Click the polygon icon and use your mouse to trace the outline of your desired shape. Much like creating a path, you will create the polygon while the dialogue box is open. You can name the shape, add information, links, and/or images as well as alter the line and fill colors.

_Review_: Test yourself - can you navigate to a place? Place a maker? Create a path? Designate space, ie make a polygon?

## Skills!
Let's add the Lakeland data to Google Earth.
1. Export a csv file from the Lakeland Airtable by clicking the ... to the right side of the table menu.
2. In Google Earth, click on File, then Important
3. Select your csv file and click open
4. You will see a "Data Import Wizard" along with a preview of your data. If this looks correct, hit 'Next'.
5. Continue through the import wizard to denote if your data does not include latitude/longitude and field types. Note, your place name and descriptions are strings; latitude and longitude are integers.
6. Once imported, you can style your icons.
7. Using 'control click' on any placename will enable you to edit, rename, add images, etc.
_Note_: If you have images in your Airtable data, they will appear as links in your imported points.

## Homework
Explore the features of Google Earth. What are the affordances, especially for your own research interests? What are the limitations? Create a tour of Lakeland. 
