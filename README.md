# Search_newspaper_images_for_occurrences_of_keywords_and_faces
Search_newspaper_images_for_occurrences_of_keywords_and_faces

Motivation:

The files in the ZIP file are newspaper images. The python code allows one to search through the images looking for the occurrences of keywords and faces. E.g. if you search for "pizza" it will return a contact sheet of all of the faces which were located on the newspaper page which mentions "pizza". 

Data:

Each page of the newspapers is saved as a single PNG image in a file called images.zip. These newspapers are in english, and contain a variety of stories, advertisements and images. Note: This file is fairly large (~200 MB) and may take some time to work with, I would encourage you to use small_img.zip for testing.

Method:

I used zipfile to read the images in the ZIP file, OpenCV to detect faces, tesseract to do optical character recognition and PIL to composite images together into contact sheets.

