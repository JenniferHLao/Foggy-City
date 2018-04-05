# Foggy-City
Searches through a picture and determines how foggy a picture is based on the percentage of pixels containing a specific RGB value.   

This program is for practice in using RGB values and the PIL operator to sort pixels based off of a numeric value, while timing the process. Initially both the time and PIL module were imported, and then a jpeg is uploaded into the program. After the upload the number of foggy pixels is initialized  to 0, and then a nested for loop is used to traverse to each individual pixel to assess whether it is in the “fog colored” range. If the pixel is determined to be within the "foggy" range, the fog counter is incremented. Once the for loop is done traversing through each pixel, the total count for fog pixels is then divided by the total resolution of the photo (width times height) and multiplied by 100 to produce the percent of the city that was foggy. Moreover, by using the time.time function the program is timed, and execute in roughly .7 seconds. 

This program is used as a practical application for the PIL operator within python.
