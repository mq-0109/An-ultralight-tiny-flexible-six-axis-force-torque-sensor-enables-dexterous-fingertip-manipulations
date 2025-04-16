# README
Code repository of article `An ultralight, tiny, flexible six-axis force/torque sensor enables dexterous fingertip manipulations`. The Matlab file has been tested on Matlab 2021b. 

### 1. `six_force.m`

#### Overview
The input of this function is the 8xQ matrix (output voltages of the sensor), where Q is the sample numbers. The output of this function is the 6xQ matrix (six-axis force/torque), where Q is the sample numbers. 

### 2. `data.mat`

#### Overview
The data contains 418 examples, the first to eighth columns are input voltages, and the ninth to fourteenth columns are output six-axis force/torque.
