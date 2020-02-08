# plant-growth-monitoring

## Requirements :

Install plantcv and requirements :
```bash
pip install plantcv
pip install -r requirements.txt
```

## Contents and notes:
This repository contains two jupyter notebooks that allow to monitor plant growth from images. Each implementing a different method.

- segmentation.ipynb : 
  - Segments and counts the number of plant leaves.
  - The distance parameter as well as the thresholds and closing filter size have to be tuned for every dataset.

- Lettuce_volume.ipynb :
  - Computes the volume of the plant. 
  - Threshold and closing filter size have to be tuned. 

More info about plantcv on github and on the documentation :
https://github.com/danforthcenter/plantcv
