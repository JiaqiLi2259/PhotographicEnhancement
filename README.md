# Image-enhancement
This graduation project is a mobile terminal of Android platform for image enhancement under uneven lighting conditions.   
The algorithm which this project used can be roughly divided into two steps:   
1.The initial enhanced image is generated based on a simplified retinex model using guided image filter.   
2.The final result is achieved by a linear fusion with lightness map, in which the lightness map weighs between the enhanced weakly-illuminated regions and the reserved normally-illuminated regions.
 ![image](https://github.com/JiaqiLi2259/Image-enhancement/raw/master/app/src/main/res/drawable-xxhdpi/AlgorithmFramework.png)
