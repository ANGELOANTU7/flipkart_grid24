The dataset includes 24938 images.
Grocery_detection are annotated in YOLOv11 format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 5 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Random rotation of between -45 and +45 degrees
* Random shear of between -45° to +45° horizontally and -45° to +45° vertically
* Random brigthness adjustment of between -48 and +48 percent
* Random exposure adjustment of between -12 and +12 percent


