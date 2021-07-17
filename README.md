# Object Detection in coral Images using Pytorch/Detectron2
In this repository,  I implemented the object detection in coral mages using [Pytorch/Detectron2](https://github.com/facebookresearch/detectron2).
## Table of contents
* [Folder Structure](#FolderStructure)
* [Results](#Results)
* [Acknowledgement](#Acknowledgement)
## Task Description

```bash
```
Folder structure
--------------

```
├── datasets/Train/a       - this folder contains landscape images.
│   ├── image1001.png
│   └── image1002.png
│   └── --------------------
│
│
├── datasets/Train/b      - this folder contains Real-world images.
│   ├── image1001.png
│   └── image1002.png
│   └── --------------------  
│
├── datasets/Test-set/a             - this folder contains Test images(landscapes).
│   └── image1001.png
│   └── -------------------- 
│
├── save_model    -- this folder contains saved model
│
│── Python-scripts      - this folder contains  python files(can be run driectly in Jupyter notebook/IDE)
│
├──  train-MANET.py        - this file is used for training image.
│   
├──  testing.py         - this file is used for generating test images.
│   
├──  result        - this folder contains generated test images.
│ 
└──logs/tensorlogs     

```
## Results


<table>
    <tr>
    <td>
     <img src="https://raw.githubusercontent.com/Nisnab/coralchallenge/download.png" />
    </td>
      </tr>
  
  </table>

## Acknowledgement

Due to the fixed image size, the generated images are smaller in size. However, the generated images can be viewed in folders.

The repository borrows heavily fron (https://github.com/suhoy901/ImageTranslation)
