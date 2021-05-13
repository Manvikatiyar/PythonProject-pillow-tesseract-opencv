# PythonProject-pillow-tesseract-opencv

Take a ZIP file of images and process them, using a library built into python that you need to learn how to use. A ZIP file takes several different files and compresses them, thus saving space, into one single file. The files in the ZIP file we have provided are newspaper images . The task is to write python code which allows one to search through the images looking for the occurrences of keywords and faces. E.g. if we search for "Mark" it will return a contact sheet of all of the faces which were located on the newspaper page which mentions "Mark". This tests our ability to learn a new (library), ability to use OpenCV to detect faces, ability to use tesseract to do optical character recognition, and ability to use PIL to composite images together into contact sheets.

Each page of the newspapers is saved as a single PNG image in a file called img.zip. These newspapers are in english, and contain a variety of stories, advertisements and images.

Note: This file is fairly large (~200 MB) and may take some time to work with - for me it took nearly 10 minutes! , I would encourage you to use small_img.zip consisting of 4 different small_img.png  for testing. 
