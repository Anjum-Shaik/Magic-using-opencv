# Magic-using-opencv
Hlo all, this code is just opposite to GREEN SCREENING.In green screening we remove the background ,here we remove the foreground frames.
Steps involved:
     1.capturing and storing of background frame
     2.Detecting the defined color usimg color detection and segmentation algorithm.
     3.Generating a mask for the segmented defined color.
     4.Finally,generating the augmented output to create a magical video.
LIBRARIES USED:
we need to import 3 libraries.
     1.cv2
     2.time
     3.numpy 
NOTE:
 one need to adjust the value of HSV for the colour you choose accordimgly in the code and set the values.
HSV:Hue Saturation Value
HUE is expressed as a number from 0 to 360 ,for RED(0-60),for YELLOW(61-120), for GREEN(121-180),for CYAN(181-240),for BLUE(241-300) and for MAGENTA(301-360).
SATURATION isthe amount of grey in a colour ranging from 0 to 100%.reducing from 100 to 0 gives us more grey color sometimes it ranges from 0-1,whre 0 is grey and 1 is the primary color.
VALUE describes the brightness or intensity of colour from 0-100 where 0 is fully black and 100 is upmost brightest colour.


step by step processing of the code has been done using the comment lines in the code.
