
<!-- PROJECT LOGO -->
<div align="center">
  <a href="https://github.com/jauharmuhammed/README-template">
    <img src="https://github.com/Jauharmuhammed/README-Template/blob/main/assets/github-logo.svg" alt="Logo" width="80" height="80" border-radius="50%">
  </a>

  <h3 align="center">Title</h3>

  <p align="center">
    Short Discription of the Project
    <br />
    <a href="https://github.com/jauharmuhammed/README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <a href="https://github.com/jauharmuhammed/README-Template">View Site</a>
    ·
    <a href="https://github.com/jauharmuhammed/README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/jauharmuhammed/README-Template/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#running-this-project">Running this project</a>
    </li>
    <li><a href="#screenshots">Screenshots</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>


## About The Project

### Face Recognition with Real Time Database

<br>
<p align='center'>
<img src="https://data-flair.training/blogs/wp-content/uploads/sites/2/2021/06/yolo-v5-vs-others.png" width='70%' >
</p>
<br>

In this project,  how to create a real-time Face Attendance system. We will add an elegant graphical interface along with a live database to create a real-world system. We will cover the following topics: 1. Introduction 2. Overview 3. Setup 4. Webcam 5. Graphics 6. Encoding Generator 7. Face Recognition 8. Database Setup 9. Add Data to the Database 10. Upload Images to the Database 11. Download User Data 12. Update Attendance 13. Check if already Marked 14. Loading

- Webcam
- Graphics
- Encoding Generator
- Face Recognitions
- Database Setup
- Add data to database
- add Image into database
- Real-time  Databse update
- Limit number of attendence per day

<br>

### Built With

![Python](https://img.shields.io/badge/Python%20-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)
![Google Colaboratory](https://res.cloudinary.com/nholmber/image/upload/v1536751563/jupyter_colab_small_axbdcm.png)
![make sense](https://repository-images.githubusercontent.com/191981426/3981ea80-a62f-11e9-9815-cd3293dbdd22)

![Github Pages](https://img.shields.io/badge/GitHub%20Pages-%23327FC7.svg?style=for-the-badge&logo=github&logoColor=white)
![AWS](https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)


![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
<br>

## Running this project

This is a sample for Project of License Plate Detection and Classification
The training a custom YOLOv5 model requires a significant amount of computational resources, such as a powerful GPU and large amounts of memory. You may also need to fine-tune the hyperparameters to achieve the best performance.
Use in Google Colab

## Gather and label your dataset:
Collect a dataset of images that contain numberplates and label them using a labeling tool like LabelImg. Make sure to label the numberplate regions in each image and save them in the YOLO format.

```
https://www.makesense.ai/
```
## Split the dataset into training and validation sets:
Split the dataset into two sets - training and validation - in a ratio of 80:20. This will ensure that your model can learn from a diverse set of images.

## Clone trained Model Yolov5 /Download YOLOv5

```
https://github.com/ultralytics/yolov5.git
```

Then install the project dependencies with

```
pip install -r requirements.txt

```
## Configure the YOLOv5 model:
Modify the YOLOv5 configuration file to include your custom numberplate detection class. You will also need to adjust the number of classes, filters, and other parameters based on your specific requirements.

```
data/custom.yaml file
```

## Train the model:
Use the YOLOv5 train.py script to train your custom numberplate detection model. This will take several hours or days, depending on the size of your dataset and the complexity of your model.

```
!python train.py --img 640 --batch 16 --epochs 60 --data customdata.yaml --weights yolov5s.pt --cache

```



# Detect the Photo
```
!python detect.py --weights  runs/train/exp2/weights/best.pt --img 640 --conf 0.25 --source /content/drive/MyDrive/Yolov5Numberplate/yellow.jpeg
```
# Detect the video

```
!python detect.py --weights  runs/train/exp2/weights/last.pt --img 640 --conf 0.25 --source /content/drive/MyDrive/Yolov5Numberplate/road.mp4
```

<br>

## Screenshots



<table width="100%"> 
<tr>

<td width="50%">
<p align="center">
Test Mode
</p>
<img src="https://github.com/shaloofsaleem/Number-plate-detection-and-classification/blob/main/model/val_batch0_pred.jpg?raw=true">  
</td>
  <td width="50%">      
<p align="center">
Train Mode
</p>
<img src="https://github.com/shaloofsaleem/Number-plate-detection-and-classification/blob/main/model/val_batch0_pred.jpg?raw=true">
</td> 
</table>
<br/>

## Contact

<div align='left'>

<a href="https://linkedin.com/in/jauharmuhammed" target="_blank">
<img src="https://img.shields.io/badge/linkedin-%2300acee.svg?color=405DE6&style=for-the-badge&logo=linkedin&logoColor=white" alt=linkedin style="margin-bottom: 5px;"/>
</a>
	
<a href="https://twitter.com/jauharmuhammed_" target="_blank">
<img src="https://img.shields.io/badge/twitter-%2300acee.svg?color=1DA1F2&style=for-the-badge&logo=twitter&logoColor=white" alt=twitter style="margin-bottom: 5px;"/>
</a>
	
<a href="mailto:jauharmuhammedk@gmail.com" target="_blank">
<img src="https://img.shields.io/badge/gmail-%23EA4335.svg?style=for-the-badge&logo=gmail&logoColor=white" t=mail style="margin-bottom: 5px;" />
</a>
	
		
<a href="https://codepen.io/jauharmuhammed" target="_blank">
<img src="https://img.shields.io/badge/codepen-%23000000.svg?style=for-the-badge&logo=codepen&logoColor=white" t=mail style="margin-bottom: 5px;" />
</a>

</div>
