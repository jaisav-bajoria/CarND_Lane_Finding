
File P1.ipynb contains the code to identify the lanes for an autonomous vehicle
  The code uses a pipeline 
  Step 1: Convert to grayscale
  Step 2: Smoothen the image using gaussian blur
  Step 3: Cannny edge detection used to identify the differentiating surfaces
  Step 4: Image was masked to keep features important/features in the area of interest
  Step 5: Hough transformation of the image to choose line features with certain characteristics

/test_images contains the test images against which the code is tested before testing for videos
/test_videos contains the videos for testing the code for lane identification
/test_videos_output contains the results
