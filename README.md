# "Adapting Transformer in Image Segmentation tasks"
2020021461 Heejo Kong \
1st project for Applications and Practice in Neural Networks \
This repository is based on official code of mmsegmentation \
https://github.com/open-mmlab/mmsegmentation

## Installation

For install and data preparation, please refer to the guidelines as follows

```
pip install torchvision==0.8.2
pip install timm==0.3.2
pip install mmcv-full==1.2.7 -f https://download.openmmlab.com/mmcv/dist/{cuda version}/{torch version}/index.html
# example, https://download.openmmlab.com/mmcv/dist/cu101/torch1.7.0/index.html
pip install opencv-python==4.5.1.48
cd NN_project1_kong && pip install -e .
```

```
NN_project1_kong
├── mmseg
├── tools
├── local_configs
├── data
│   ├── semantic_drone_dataset
│   │   ├── images
│   │   ├── labels
│   │   ├── split
│   │   │   ├── train.txt
│   │   │   ├── val.txt
│   │   │   ├── test.txt
```


## Training



## Evaluation




