# Enhancing Construction Site Safety: Advanced Deep Learning Approaches for Accurate Helmet Detection
Eleanna Panagiotou, Zack Sifakis 

This is a project created for course ECE766 (Spring24)

## Project webpage
https://eleannapanagiotou.github.io/ECE766-HelmetDetection/


## Environment Preparation
During experimentation, we used Linux machines.

### Start by cloning this repo
```bash
git clone https://github.com/EleannaPanagiotou/ECE766-HelmetDetection.git
```

## Conda
To set up the necessary environment for this project, install the Conda environment using the provided `environment.yml` file:
```bash
conda env create -f environment.yml
```

Activate the environment:
```bash
conda activate helmet_det
```

## Model Evaluation

### YOLOv5n
To run a few demos with YOLOv5n approach, open the `Helmet_yolov5.ipynb` file and run all the cells sequentially. 

Code for the model from here: Glenn Jocher. Ultralytics YOLOv5. Version 7.0. 2020. DOI: 10.5281/zenodo.3908559. URL: https://github.com/ultralytics/yolov5.

### YOLOv8n
To run a few demos with YOLOv8n approach, open the `Helmet_yolov8.ipynb` file and run all the cells sequentially. 

Code for the model from here: Glenn Jocher, Ayush Chaurasia, and Jing Qiu. Ultralytics YOLOv8. Version 8.0.0. 2023. URL: https://github.com/ultralytics/ultralytics.

### DEtection TRansformer
To run a few demos with DETR approach, at first download the `output` folder from here: https://drive.google.com/file/d/1PFBXzpQINCa1DZ3SpD74o2k4G_VUeIB1/view?usp=sharing
Then, move the folder inside the `helmet_detr` folder. Finally, open the `Helmet_detr.ipynb` file and run all the cells sequentially.

Code for the model from here: https://github.com/facebookresearch/detr

## Model Training 
TBA
