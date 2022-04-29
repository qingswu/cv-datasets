# Computer Vision Datasets

- [Computer Vision Datasets](#computer-vision-datasets)
  - [Autonomous Driving/ADAS](#autonomous-drivingadas)
    - [Thermal Imaging](#thermal-imaging)
    - [Motion Planning](#motion-planning)
    - [Synthetic Dataset](#synthetic-dataset)
  - [Face](#face)
  - [Human](#human)
  - [Video Object Segmentation](#video-object-segmentation)
  - [Dataset Search Engine](#dataset-search-engine)

## Autonomous Driving/ADAS
1. [Argoverse 2](https://www.argoverse.org/av2.html)

| Argoverse 2 Sensor Dataset | Argoverse 2 Motion Forecasting Dataset | Argoverse 2 Lidar Dataset | Argoverse 2 Map Change Dataset |
| -------------------------- | -------------------------------------- | ------------------------- | ------------------------------ |
| 1,000 3D annotated scenarios with lidar, stereo imagery, and ring camera imagery.<br/>This dataset improves upon the Argoverse 1 3D Tracking dataset. | 250,000 scenarios with trajectory data for many object types.<br/>This dataset improves upon the Argoverse 1 Motion Forecasting Dataset. | 20,000 unannotated lidar sequences. | 1,000 scenarios, 200 of which depict real-world HD map changes |

1. [The Cityscapes Dataset](https://www.cityscapes-dataset.com/)
  * 5000 images with high quality annotations
  * 20000 images with coarse annotations
  * 50 different cities
4. [All-In-One Drive](http://www.aiodrive.org/index.html), A Large-Scale Comprehensive Perception Dataset with High-Density Long-Range Point Clouds
  * Full sensor suite (3x LiDAR, 1x SPAD-LiDAR, 4x Radar, 5x RGB, 5x depth camera, IMU, GPS)
  * 100 sequences with 1000 frames (100s) each
  * 500,000 annotated images for 5 camera viewpoints
  * 100,000 annotated frames for each LiDAR/Radar sensor
  * 26M 2D/3D bounding boxes precisely annotated for 4 object classes (car, cyclist, motorcycle, pedestrian)
  * <img src="http://www.aiodrive.org/resources/home/inclusiveness.png"/>
5. [DAIR-V2X](https://thudair.baai.ac.cn/index), The world's first vehicle-road collaboration dataset release
  * Totally 71254 LiDAR frames and 71254 Camera images:

    | DAIR-V2X Cooperative Dataset<br/>(DAIR-V2X-C) | DAIR-V2X Infrastructure Dataset<br/>(DAIR-V2X-I) | DAIR-V2X Vehicle Dataset<br/>(DAIR-V2X-V)  |
    | --------------------------------------------- | ------------------------------------------------ | ------------------------------------------ |
    | 38845 LiDAR frames<br/>38845 Camera images    | 10084 LiDAR frames<br/>10084 Camera images       | 22325 LiDAR frames<br/>22325 Camera images |
  * <img src="https://thudair.baai.ac.cn/static/img/road05.91a9e0fe.png" />
6. [Dense Depth for Autonomous Driving - DDAD dataset](https://github.com/TRI-ML/DDAD)
  * The training and validation scenes are 5 or 10 seconds long and consist of 50 or 100 samples with corresponding Luminar-H2 pointcloud and six image frames including intrinsic and extrinsic calibration.
  * The training set contains 150 scenes with a total of 12650 individual samples (75900 RGB images), and the validation set contains 50 scenes with a total of 3950 samples (23700 RGB images).
  * train+val 257 GB
  * <img src="https://github.com/TRI-ML/DDAD/raw/master/media/figs/ddad_viz.gif" />
7. [Audi Autonomous Driving Dataset (A2D2)](https://www.a2d2.audi/a2d2/en.html)
  * The dataset features 2D semantic segmentation, 3D point clouds, 3D bounding boxes, and vehicle bus data
  * Sensor setup:

| Five LiDAR sensors | Front centre camera | Surround cameras (5x) |
| ------------------ | ------------------- | --------------------- |
| <ul><li>Up to 100 m range</li><li>+/- 3 cm accuracy</li><li>16 channels</li><li>10 Hz rotation rate</li><li>360° horizontal field of view</li><li>+/- 15° vertical field of view</li> </ul> | <ul><li>1920 × 1208 resolution</li><li>60° horizontal field of view</li><li>38° vertical field of view</li><li>30 fps framerate</li></ul> | <ul><li>1920 × 1208 resolution</li><li>120° horizontal view angle</li><li>73° vertical view angle</li><li>30 fps framerate</li></ul> |
  * <img src="https://www.a2d2.audi/content/dam/a2d2/sensor-setup/1920x1080-desktop-aev-sensor-grafik-1.jpg?imwidth=1920&imdensity=1" />

### Thermal Imaging
1. [FREE Teledyne FLIR Thermal Dataset for Algorithm Training](https://www.flir.ca/oem/adas/adas-dataset-form/)
  * A total of 26,442 fully annotated frames with 520,000 bounding box annotations across 15 different object categories
  * 9,711 thermal and 9,233 RGB training/validation images with a suggested training/validation split. Includes 16-bit pre-AGC frames
  * 7,498 total video frames recorded at 24Hz. 1:1 match between thermal and visible frames. Includes 16-bit pre-AGC frames
  * <img src="https://www.flir.ca/contentassets/56f6b890db8b42919e792db742cf3a73/skateboarder-ir13.png"/>

### Motion Planning
1. [SafetyNet: Safe planning for real-world self-driving vehicles using machine-learned policies](https://www.self-driving-cars.org/papers/2022-safetynet)
<img src="https://lh6.googleusercontent.com/pU0PsapK0_4U841iF1pMGzVjbWFoQq9AUsDuwp6TaZdfC78pViAQFNwRg8hRfQUcnmkduC_HXNr7oX-x6DjQCmXRqguOGPzxuMLc_7p23l2DNS0bOIBH2OEiGZZiGqmJkg=w1280" />

### Synthetic Dataset
1. [The SYNTHIA dataset](http://synthia-dataset.net/)
  * SYNTHIA consists of a collection of photo-realistic frames rendered from a virtual city and comes with precise pixel-level semantic annotations for 13 classes: misc, sky, building, road, sidewalk, fence, vegetation, pole, car, sign, pedestrian, cyclist, lane-marking.
  * <img src="http://synthia-dataset.net/wp-content/uploads/2016/06/s_000_22-06-2016_17-35-02_000000.png" />


## Face

## Human
* Crowdhuman

## Video Object Segmentation
1. [Occluded Video Instance Segmentation (OVIS)](http://songbai.site/ovis/)
  * Highlights: ***occluded video instances***
  * OVIS consists of 296k high-quality instance masks from 25 semantic categories, where object occlusions usually occur.


## Dataset Search Engine
1. [BIFROST](https://datasets.bifrost.ai/)
