# Fabric Simulator

This project was completed in 2022 for the course COS426: Computer Graphics @ Princeton University. The code implements a cloth object with simulated phyisics.

## Description

The following features are implemented:
### Fabric Structure
* Structural Springs: Attached current point to neighbors on right and down
* Shear Springs: Attached current point to diagonal neighbors
* Bending Springs: Attached current point to neighbors two positions to the right and two positions down

### Physics
* Gravity
* Verlet Integration
* Collisions: Floor, Sphere, Box

### Extra
* Rain
* Changing Winds

### Installing and Executing

Download repository and run the following in terminal:
```
python3 -m http.server
```
to start a locally hosted server. Navigate to browser and open the server.

## Authors

Source code from Princeton University
