## ORB-SLAM3-STEREO-FIXED

This repository is a modified version of [ORB-SLAM3-STEREO-FIXED](https://github.com/zang09/ORB-SLAM3-STEREO-FIXED)  

--- 

## Modification
- Succesfully tested in **Ubuntu 22.04** and **ROS2 humble**(with OpenCV 4.5.4)
- Updated minimum CMake version to 3.5

## How to build
Clone the repository:
```
git clone https://github.com/cadkimbj/ORB-SLAM3-STEREO-FIXED.git ORB_SLAM3
```

Install same required dependencies as original version.
Execute:
```
cd ORB_SLAM3
chmod +x build.sh
./build.sh
```
This will create *build* folder, **libORB_SLAM3.so**  at *lib* folder, and the executables in *Examples* folder.
