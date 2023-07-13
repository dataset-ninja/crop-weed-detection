Please visit dataset [homepage](https://www.kaggle.com/datasets/ravirajsinh45/crop-and-weed-detection-data-with-bounding-boxes) to download the data. 

Afterward, you have the option to download it in the universal supervisely format by utilizing the *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Crop and Weed Detection data with bounding boxes', dst_path='~/dtools/datasets/Crop and Weed Detection data with bounding boxes.tar')
```
