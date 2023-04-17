# meat-freshness

## About Dataset - Meat Freshness Dataset
### Data Description
It includes 2266 images.
Color-Marbling-Freshness are annotated in Multi-Class Classification format.

The following pre-processing was applied to each image:

    - Auto-orientation of pixel data (with EXIF-orientation stripping)
    - Resize to 416x416 (Stretch)

The following image augmentation techniques were applied as a layer of CNN:

    - Random flip horizontal
    - Random flip vertical
    
## Classes
  - Fresh
  - Half-Fresh 
  - Spoiled

## Inspiration
  How can we detect whether meat is fresh or not?
