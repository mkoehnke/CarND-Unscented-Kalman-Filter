# Unscented Kalman Filter Project 

This project utilizes an Unscented Kalman Filter to estimate the state of a moving object of interest with noisy lidar and radar measurements. Passing the project requires obtaining RMSE values that are lower that the tolerance outlined in the project reburic. 

This project involves the Term 2 Simulator which can be downloaded [here](https://github.com/udacity/self-driving-car-sim/releases)

## Installation

Install the uWebSocketIO using the following command:

```
sh install-mac.sh
```

Compile the source code by entering the following commands:

```
mkdir build
cd build
cmake ..
make
./UnscentedKF
```

![EKF Simulator](https://github.com/mkoehnke/CarND-Extended-Kalman-Filter/raw/master/ekf-simulator.png)
