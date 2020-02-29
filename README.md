# automatic_license_plate_recognition

December 2019 University of Chicago Master's of Science in Analytics final capstone presentation with [`adsmaniotto`](https://github.com/adsmaniotto), [`benjaminjka`](https://github.com/benjaminjka) and [`agnesreband`](https://github.com/agnesreband)


## How to use this repository
Clone or download the entire repo.

Open the ipython notebook `end_to_end_license_plate_recognition`

This will read in all of the necessary utilities, then it will load the networks and model weights for our final YOLO model and Keras OCR engine.

Next the notebook will read in the set of 100 validation images with which to test the model and it's accuracy and to demonstrate the included functions. 

And finally we will put all of our functions together to read in a validation image, apply the YOLO model to find the bounding boxes and crop the license plate. 

This cropped license plate gets passed into the Keras OCR engine for final character recognition, and then we have added some plotting functions to view the cropped plate and the OCR results.


## The models

### YOLO
_Coming soon..._

### OCR
_Coming soon..._

## The validation images

We have included a set of 100 images used for validation. These are yours to keep. The model was trained on thousands of images, which took a lot of time to collect and label, so we have opted to not include those here.0

## Questions
Please email if you have questions.
