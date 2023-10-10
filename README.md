# Hold and Tap Dataset

Number of users = 95

# Activities
Sitting - 2850 (95 x 30)   <br />
Standing - 2850 (95 x 30) <br />
Walking - 2850 (95 x 30)

# Features
Each activity has two types of data hold-movement and touch. Hold movements is collected using seven 3-dimensional motion sensors
(i.e., the accelerometer, the high-pass sensor, the low-pass sensor, the orientation sensor, the gravity sensor, the gyroscope, and the magnetometer) and touch data is collected using touchscreen sensor.

Sensor: 112 Features and 113th Column is label<br />
**Description:** 4 statistical features, namely Mean (μ), Standard Deviation (σ), Skewness (s), and Kurtosis (k), that gives 16 statistical features
per sensor. Thus, a total of 16 features are obtained from a sensor. Since there are seven sensors in total so 112 satistical features are obtained.

![image](https://github.com/apachetechnology/HoldandTapDataset/assets/26899308/b2b5f158-d301-4fd5-ae64-10672f1ed1ea)

Touch: 30 features and 31st Column is label<br />
**Description:** Touch-typing features consist of 8 Type0 (timing difference between each key release and key press), 7 Type1 (timing difference a key press and previous key release, 7 Type2 (timing difference two successive keys release), 7 Type3 (timing difference two successive keys press), and 1 Type4 (timing difference between last and first key press). Thus, 30 touch-typing features from the 8-digit random-text entry are extracted.

# Citations
Please cite our following papers to use the dataset.

@article{buriro2021risk,<br />
  title={Risk-driven behavioral biometric-based one-shot-cum-continuous user authentication scheme},<br />
  author={Buriro, Attaullah and Gupta, Sandeep and Yautsiukhin, Artsiom and Crispo, Bruno},<br />
  journal={Journal of Signal Processing Systems},<br />
  volume={93},<br />
  pages={989--1006},<br />
  year={2021},<br />
  publisher={Springer}<br />
}

@phdthesis{gupta2020next, <br />
  title={Next-generation user authentication schemes for iot applications}, <br />
  author={Gupta, Sandeep}, year={2020}, <br />
  school={PhD thesis, Ph. D. dissertation, University of Trento, Italy} <br />
}
