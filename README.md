# Wound-Measurement
wound measurement app to improve clockface method for BN3101A project
heck yea

Main app is WoundMeasurementPortable.zip under releases

To run, just click Start_Wound_System.vbs and to stop click Stop_Wound_System.vbs and do not forget if not it will run in the background.
Connect to a local ESP-32 CAM via IP address or upload pictures from your phone to start. Example pictures have been uploaded, zip file is just all the pictures together if you lazy download all the pictures individually, the pictures are the same. If the picture is too zoomed in (see example 50degreeclockwise.png) or out from the original the program will not be able to detect if the wound is the same so don't be stupid

For initial picture you will need:

an Aruco Marker sticker attached for calibration (included in example pictures)

to mark the centre of the wound manually

to generate the boundaries of the wound semi-automatically (draw a rectangle around the approx area)

a picture of your choice to act as a clockface

Compiled mostly by Chatgpt for BN3101A
