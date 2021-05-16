# CleanerUpper.py
Python script to quickly categorise images into folders based on the date and location of their EXIF data.<br>
Year > Country > City folders will be created for their respective images as long as images contain EXIF with coordinates.

Using [reverse-geocoder](https://github.com/thampiman/reverse-geocoder), a nearest-neighbour algorithm over a database prevents having to repeatedly hit an API's rate limit. 
