# Object Detection in coral Images using Pytorch/Detectron2
In this repository,  I implemented the object detection in coral images using [Pytorch/Detectron2](https://github.com/facebookresearch/detectron2).
# Task Description
The task is to detect bounding box in the format xmin,ymin, xmax & ymax. The coral images consists of 13 classes.
We used Mask RCNN to detect bounding box.

## Table of contents
* [Folder Structure](#FolderStructure)
* [Results](#Results)
* [Acknowledgement](#Acknowledgement)
## Task Description

```
The task is to generate real images from landscape paintings.
```
Folder structure
--------------

```
├── data
│   ├── allcoral --- this folder contains input images with coral species.
│   └── annotations_boxes_training.csv -- this .csv file contains location of species in format(xmin,ymin,xmax,ymax)
│   └── detectron2.csv  ---this csv contains improvised format of species.
│
│
├── annotated_results    -- this folder contains output images with bounding box.
│
├──  coco_eval     
│   └──coco_instances_results.json --- this folder contains location of coral species in all output images
│  
├── output
│   ├── instances_prediction --- this file cotains weights of the model in .pth format
│   └── 
│   └── --------------------
│   
├──  result        - this folder contains generated test images.
│ 
└──logs/tensorlogs     

```

## Results

<table>
    <tr>
    <td>
     <img src="https://github.com/Nisnab/coralchallenge/blob/main/download.png?raw=true" />
    </td>
      </tr>
  
  </table>
