# Head-Pose-Estimation

Head pose estimation from a single image is a challenging problem. Head pose is a 3D vector containing the angles of yaw, pitch and roll. Estimating the head pose from an image essentially requires to learn a mapping between 2D and 3D spaces.

## Tools Used

* [Jupyter Notebook Python](https://jupyter.org/)
* [Google Colab](https://colab.research.google.com/)
* [Python](https://www.python.org/)
* [mediapipe](https://techtutorialsx.com/2021/05/19/mediapipe-face-landmarks-estimation/)
* [OpenCV](https://opencv.org/)

## Usage

* Just Download the github repository and you will find all the used files inside it.
* To run the project you will need to use those 4 commands
** [!pip install mediapipe]
** [!pip install protobuf==3.20.]
** [!pip install opencv-python]
** [!pip install opencv-contrib-python]
** [!pip install "opencv-python-headless<4.3"]

## Steps
* Download the AFLW2000-3D => [Link!](http://www.cbsr.ia.ac.cn/users/xiangyuzhu/projects/3DDFA/Database/AFLW2000-3D.zip )
* Get Face Mesh points of each image in the dataset
* Get the labels from the (.mat) file of each image in the dataset
* Draw the 3-axis for the images => (yaw, pitch, roll)
* Collecting all these data in one dataframe
* Traing the model to predict the 3-axis
* Use Live stream to test the model in real videos

## Results

* Face Mesh Points
* [](https://github.com/shrookehab/Head-Pose-Estimation/blob/main/Results/index.png)
* [Head-Pose-Detection-Video]()

## Author 

* [Shrook Ehab](https://github.com/shrookehab) [ORIGINAL]
