The dataset includes 7741 images.
annotated in YOLOv11 format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 5 versions of each source image:
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Random shear of between -6° to +6° horizontally and -18° to +18° vertically


