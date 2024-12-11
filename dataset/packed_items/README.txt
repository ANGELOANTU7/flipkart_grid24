The dataset includes 9,540 images.
annotated in YOLOv11 format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 5 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Random rotation of between -45 and +45 degrees
* Random shear of between -13° to +13° horizontally and -14° to +14° vertically
* Random blur upto 2.5px 


