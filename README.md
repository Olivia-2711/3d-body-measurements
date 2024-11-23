# 3D Body Measurements

Through this library you can obtain the body measurements of a human body made up of vertices and faces generated by SMPL model.

## Requirements
- Python 3.8+
- Trimesh

## Installation
You can install the package by running
```
pip install body_measurements
```

## Body Measurements
- A: Height 163cm
- B: Chest 81cm
- C: Hip 81cm
- D: Waist 77cm
- E: thigh 45cm
- F: Outer leg 41cm
- G: Inner leg 29cm
- H: Neck-Hip 35cm
- I: Shoulder 45cm
- Weight (Kilos - 47kg


## IMPORTANT
We strongly recommend generate the vertices with 'A' pose of human body to make the measurements to more accurate as possible. 

To get the 'A' pose throught SMPL model you can set all values of the pose param in zero except the positions 50 and 53, the values of these positions must be 5.6 and -5.6 respectively.



![Measurements](https://raw.githubusercontent.com/vcarlosrb/3d-body-measurements/main/images/measurements.png)
