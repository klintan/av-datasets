# Autonomous vehicle datasets

There are a lot of collections of datasets, but unfortunately the majority of these datasets are not truly FREE to use. They are only for research purposes. 

Here we'll list all datasets that have an MIT-type license, aka they are allowed to be used for both research, hobby and commercial purposes.

Data is mostly considered one of the most valuable things for a robotic company, however I think even using smaller datasets as a baseline for further fine-tuning or comparing to without ever worrying about any license issues are worth pursuing. Truly open knowledge and data is the future. 


### Lidar

|  Dataset | License  | Annotations | Year  |  Link |
|---|---|---|---|---|
|   |   |   |   |   |


### Vision

|  Dataset | License  |  Annotations | Year  |  Link |
|---|---|---|---|---|
|  Caltech Pedestrian detection |  CC4.0 | Pedestrian bbox  |   |  http://www.vision.caltech.edu/Image_Datasets/CaltechPedestrians/index.html |
| GM-ATCI Rear-view pedestrians  | CC4.0/MIT [1] |   |   |  https://sites.google.com/site/rearviewpeds1/ |
|  SullyChen AutoPilot Dataset |  MIT | Steering angle  |   |  https://github.com/SullyChen/Autopilot-TensorFlow |
| COCO  | CC4.0  |  Segmentation |   | http://cocodataset.org/  |
| Self driving car data | CC0 | None | | https://www.kaggle.com/ajaysh/self-driving-car | 
| CSAIL LabelMe dataset | CC0 (with attribution) | Segmentation | |http://labelme2.csail.mit.edu/Release3.0/browserTools/php/publications.php |
| Udacity | MIT | Bounding boxes | | https://github.com/udacity/self-driving-car/tree/master/annotations |
| Udacity (Roboflow cleaned)| MIT | Bounding boxes | | https://public.roboflow.ai/object-detection/self-driving-car |
| NGSIM Vehicle Trajectories and Supporting Data| CC4.0 | Vehicle trajectory data | | https://data.transportation.gov/Automobiles/Next-Generation-Simulation-NGSIM-Vehicle-Trajector/8ect-6jqj |


[1] Confirmed with GM per email. No responsibility whatsoever from GM. So something similar to MIT

### Multi-sensor

|  Dataset | License  |  Annotations | Sensors  |  Link |
|---|---|---|---|---|
|  Udacity | MIT  |  None |  IMU/GPS/LIDAR |  https://github.com/udacity/self-driving-car/tree/master/datasets |
|  Velodyne SLAM KIT |  CC4.0 [2] | None  |  LIDAR/Stereo camera |  https://www.mrt.kit.edu/z/publ/download/velodyneslam/dataset.html |
|  NCLT Dataset |  Open Database License |   |  Camera/IMU/GPS/LIDAR/Wheel odometry |  http://robots.engin.umich.edu/nclt/ |
|  Brno Urban Dataset | MIT  |  None |  Camera/Thermal/RTK/GPS/LIDAR/IMU  | https://github.com/Robotics-BUT/Brno-Urban-Dataset  |
|  Audi Autonomous Driving Dataset (A2D2) | CC BY-ND 4.0 | 3D bounding boxes/Semantic Segmentation | Camera/LIDAR | https://www.a2d2.audi/a2d2/en.html | 
|  comma2k19| MIT | None | Camera/IMU/GPS | https://github.com/commaai/comma2k19 | 

[2] This data can be freely used with one restriction: In case it is used for scientific publication
you are required to cite the article "Velodyne SLAM" of Moosmann et al

### Synthetic data
|  Dataset | License  | Annotations | Year  |  Link |
|---|---|---|---|---|
|  Semantic Segmentation for Self Driving Cars | CC0  | semantic segmenation  |   | https://www.kaggle.com/kumaresanmanickavelu/lyft-udacity-challenge  |
|   |   |   |   |   |

## References

https://www.datasetlist.com/

