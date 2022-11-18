# ImageCaptioning-MotionCNN
In this project we try to combine image features, motion features and object detection to generate highly accurate captions.
<br>
## Objectives
To generate image captions.
* To improve the quality of captions by considering motion features and the relation between motion features and verbs.
* To improve the quality of caption by considering only the motion features around the object region and ignoring background motion features using object detection.
* To try different datasets / models / parameter tuning and do a comparative study.

The following table shows some previous works associated with the topic:<br>
![img1](/lit_survey.jpg)

## Methodology:<br>
1. Data-set information<br>  MS-COCO [ Microsoft - Common Objects in Context ] dataset, Flickr8 dataset
2. Analyzing data-sets
3. Data visualization 
4. Object Detection
5. Motion CNN
    1. Motion Encoding
    2. Im2Flow
    3. Motion CNN with Object Detection
    4. Caption Generation

## Experimental Results and Analysis
<br>

* MSCOCO Dataset<br>
![img2](/res_MSCOCO.jpg)<br>
* Flickr8 Dataset<br>
![img3](/res_Flickr8.jpg)<br>

## Concluding Remarks:<br>
Our project experimentation was targeted to produce captions for images using basic image captioning and motion estimation using a pre-trained model Im2Flow. Image captioning is important as it helps in bringing out meaning to that images when the scenario is not known. These captions generated using NLP techniques helps in giving a better description of the image to visually impaired people. The motion estimation produces an image which determines direction of motion. This motion estimation helps in producing the captions more accurately. This combination of basic image features and motion estimation produces an accurate model for producing captions. Object detection is implemented into our model toemploy motion characteristics, as stated in this study. Object detection, on the other hand, can provide bounding boxes that encompass all picture areas, as discussed in the preceding discussion.Our future research will focus on how to better incorporate motion aspects.
