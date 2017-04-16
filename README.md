# Extended Kalman Filter
---
![overview](https://s3.cn-north-1.amazonaws.com.cn/u-img/75c63dca-b21e-402e-8dc6-be8846c10b3a)

![kf&ekf](https://s3.cn-north-1.amazonaws.com.cn/u-img/2930f37d-5f4a-4dd4-9403-ada33da6df3a)
* EKF update for radar
* KF update for lidar

And here, h(x') is :
![latex](http://latex.codecogs.com/gif.latex?h%7B%28x%27%29%7D%20%3D%20%5Cbegin%7Bpmatrix%7D%20%5Csqrt%7B%7Bp%27_x%7D%5E%7B2%7D&plus;%7Bp%27_y%7D%5E%7B2%7D%7D%5C%5C%20%5Carctan%7B%5Cfrac%7Bp%27_y%7D%7Bp%27_x%7D%7D%5C%5C%20%5Cfrac%7B%7Bp%27_x%7D%7Bv%27_x%7D&plus;%7Bp%27_y%7D%7Bv%27_y%7D%7D%7B%5Csqrt%7B%7Bp%27_x%7D%5E%7B2%7D&plus;%7Bp%27_y%7D%5E%7B2%7D%7D%7D%20%5Cend%7Bpmatrix%7D)
## Dependencies

* cmake >= 3.5
 * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools]((https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./ExtendedKF path/to/input.txt path/to/output.txt`. You can find
   some sample inputs in 'data/'.
    - eg. `./ExtendedKF ../data/sample-laser-radar-measurement-data-1.txt output.txt`






