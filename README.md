# Vehicle-Number-Detection---Image-Processing
                                       Vehicle Number Prediction Using Image Processing Technique:
Introduction:
============
    Detecting vehicle numbers using their Images. extracting alpha numeric text from images and store it in list and then converting that list into Pandas DataFrame which will help us in future to search easily, process effectively and we can add addtional columns to add information in that dataframe. using cv2 images are fetched from the folder which have collection of images, using pytessaract texts are extracted from images, after extracting texts are loaded in list and then converted that list into DataFrame.

Problem Statement:
=================
    The primary aim of this task is twofold: first, to identify and locate the license plates affixed to the vehicles in the images, and second, to perform character recognition on these license plates, deciphering the alphanumeric text they contain.
    
Objective:
==========
    * To read images from image folder and img_id from csv file match that both
    * To extract alphanumeric values from images and store it in list
    * To convert that list into Pandas DataFrame for future assistance.

Tools used:
===========
    Python, cv2, Pytessaract, Pandas, Image Processing
    
Findings:
========
    * we can extract data from images and that can be more useful for security process in
malls, offices, tech parks, government places, public areas and so on.
    * The accuracy varied depending on the quality of the images and the clarity of the license plates. 
Higher resolution images with clear, unobstructed views of the license plates yielded better results.
    *Preprocessing steps like grayscale conversion and adaptive thresholding
significantly improved OCR performance by enhancing the contrast between the text and the background.
    * Preprocessing steps like grayscale conversion and adaptive thresholding significantly improved OCR 
performance by enhancing the contrast between the text and the background.
    * Applying these preprocessing techniques helped in reducing the noise and improving the readability of characters.

Conclusion:
==========
The quality of input data is critical for the success of OCR-based text extraction. High-quality images and precise annotations lead to more accurate and reliable results.Future work could include the development of a more sophisticated image preprocessing pipeline that can handle a wider range of image quality issues, such as glare, shadows, and low resolution.The findings of this project have practical implications for applications in automated license plate recognition (ALPR) systems used in traffic monitoring, toll collection, and security surveillance.Improving the robustness and accuracy of such systems can lead to more efficient and reliable automated processes, reducing the need for manual intervention.
