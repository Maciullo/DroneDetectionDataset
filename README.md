# Real World Object Detection Dataset For Quadcopter Unmanned Aerial Vehicle (UAV)
* Effort show within the repository below and subsequent processing has been performed as a part of ongoing PhD on Engineering Applications of Artificial Intelligence under Warsaw University of Technology, Faculty of Power and Aeronautical Engineering, Warsaw, Poland.

|Author|Maciej Pawełczyk|Marek Wojtyra|

****

## License:

The project is released under the MIT License for image tags. Video sources and corresponding  video images/frames were extracted from a list of videos available publically in the popular video service YouTube (full list of videos provided in the Video_Sources.txt file).

****


## Originality:

To our current knowledge there are two currently available UAV datasets:
- https://github.com/ZhaoJ9014/Anti-UAV
- https://github.com/CenekAlbl/drone-tracking-datasets

The difference between above and proposed datasets is that our proposed dataset focuses more on drone detection in a range of environments rather than drone tracking. The motivation for this approach is an intrinsic challange of drone tracking (which can be easily disturbed by sudden obstruction) and model overfitting (when presenting too many images from the same distribution).

****

## Motivation:
Recent high publicity events connected to UAVs pose both a risk of privacy intrusion and critical infrastructure trespassing, possibly posing a danger of human harm in case of airports, power stations, water treatment plants and other. In order to reduce surveillance costs machine learning based methods can be applied to constantly monitor surroundings of such areas. Depending on the application low power and well established applications such as Haar Cascades (with easy to use OpenCV application) and/or Artificial Neural Networks (allowing greater accuracy, but suffering from higher computational requirements and difficulty in edge applications) can be used to protect sensitive areas from UAV intrusion.

****

## Drone Detection Dataset:
<div align="center">
    <img src="https://github.com/Maciullo/DroneDetectionDataset/blob/master/Fig/pos_G2P8362.jpg" width="400"/><img src="https://github.com/Maciullo/DroneDetectionDataset/blob/master/Fig/pos_G3P378.jpg" width="400"/>
</div>
And subsequent Haar Cascade/ANN training results:
[YouTube Video](https://www.youtube.com/watch?v=o6mxjR6GdA40

****

- Dataset description: The Drone Detection Dataset consists of 51446 train and 5375 test 640x480 RGB images presenting drones in different types, sizes, scales, positions, environments, times-of-day with corresponding XML labels set, prepared for Haar Cascade training (which can and was easily modified for ANN training applications). Presented frames were manually annotated by the first author. While initial labelling (test set plus approximately 2000 images) required extensive author work, the subsequent images were initially labelled by trained Haar Cascade/ANN to reduce annotation time. Dataset frames were automatically extracted from the beforementioned videos (approximately 50-140 frame). 

****

Dataset availability: before full paper publication only snippet of 100 test & train images is available:
- [Train Set Snippet](https://drive.google.com/file/d/1UOfNPwkenGH4x1rOAbUr3TVtXN_RcKya/view?usp=sharing)
- [Test Set Snippet](https://drive.google.com/file/d/1uGXdLrQ9sZ4e2RaP2kMGa073jxeNQnIS/view?usp=sharing)
Full dataset will be provided directly after article publication (approximately 5GB).

****


## Citation:
When using or referring to the dataset please consider citing the following papers: 
- TO BE PROVIDED
