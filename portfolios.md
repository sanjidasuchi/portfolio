**Image segmentation using eCognition**<br>
<p style="text-align: justify;">
Image segmentation is a core computer vision task that divides the image into several objects or important parts. The new challenge here is to reconstruct images by exploding them into simpler parts so that they can be produced and understood. Image segmentation in ArcGIS Pro, or eCognition: ArcGIS Pro has an extra extension called the Spatial Analyst where it can have some pixel image analysis capabilities for either segmentation or classification processes, and object-oriented ones as well so no need to separately run things.In contrast, eCognition has better segmentation and feature extraction capabilities designed specifically for object-oriented image analysis (OBIA). Even however ArcGIS Pro supplies a whole GIS environment, eCognition is more suitable since it has comprehensive graphic analysis and
segmentation capabilities. Based on the level of information you need in your segmentation results, complexity of images and requirements for specific project will define which option works for you. In this report with sentinel 2 image, I am going to make a comparison between eCognition and arcgis pro and can see what differences it will make and give a better image object.
</p>
![](images/01.png)

<p style="text-align: center;">
Figure 1: Image segmentation using eCognition
</p>
![](images/2.png)
<p style="text-align: center;">
Figure 2: Image segmentation using Arcgis Pro
</p>
<p style="text-align: justify;">
eCognition:
For ecogntion, even after adjusting the parameters, the algorithm is still not detecting correctly the areas<br>
- The lake as being significantly over-segmented, into several segmentation regions.<br>
- The borders between segments, especially in hilly areas are not quite as well defined and sometimes jagged.<br>
Arcgis Pro:<br>
-The regionalization algorithm under-segments in some areas, combining regions should be kept separate.<br>
- it can detect those areas in somehow correctly like the lake so to conclude that both softwaresdemands manual adjustment for seeing which parameters are better and result in optimal solution<br>
</p>


