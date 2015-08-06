# python_generate_google_map_access_google_doc
python script generate google map and  access google online excel 

Sample project 1:  draw_google_map_python_read_write_google_doc

Generate google map, manipulate google online excel doc with python script:

1.  people can draw polygons on google map, such as this one:

https://www.google.com/maps/d/edit?hl=en&authuser=0&mid=z5QeVGweEEJc.k78J8kdMHGMQ

2.  python script  pygooglespread.py
    will download those polygons we drew on the map as KML file
3. the script will parse the KML and get each polygon we have drawn on the map

4.  For each polygon we have drawn,
       
       a google excel doc will be inserted with one row, with map url
       to represent this individual polygon 

       https://docs.google.com/spreadsheets/d/1qsgpOdxXZv_wz6TJF__3fvK4FdIezcfrutI0r4x5_Nc/edit#gid=0
   
       a related htm file with google map will be generated
       these htm files can be uploaded to the ftp site, where the map url pointing to

