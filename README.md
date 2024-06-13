# Fabric Simulator

<img width="800" alt="gravity" src="https://github.com/lauren-e-gardner/Fabric_Simulator/assets/157167532/482596e9-c3fc-4c78-b73e-8196bd2bb7fd">

This project was completed in 2022 for the course COS426: Computer Graphics @ Princeton University. The code implements a cloth object with simulated phyisics.

## Description

The following features are implemented:
### Fabric Structure
* Structural Springs: Attached current point to neighbors on right and down
* Shear Springs: Attached current point to diagonal neighbors
* Bending Springs: Attached current point to neighbors two positions to the right and two positions down

<img width="600" alt="spring" src="https://github.com/lauren-e-gardner/Fabric_Simulator/assets/157167532/ac1cebab-0a20-429c-b8a2-d89eb2804252">

### Physics
* Gravity

<img width="600" alt="gravity" src="https://github.com/lauren-e-gardner/Fabric_Simulator/assets/157167532/02ffbe40-8347-4f95-9de1-5fe28da9ea5f">

* Verlet Integration

![grav](https://github.com/lauren-e-gardner/Fabric_Simulator/assets/157167532/539702bc-1c1f-4bbb-9346-98ffd286d487)

* Collisions: Floor, Sphere, Box

![floor](https://github.com/lauren-e-gardner/Fabric_Simulator/assets/157167532/41fd8cf0-135e-42fc-8f1e-1abf523eaa83)

![sphere](https://github.com/lauren-e-gardner/Fabric_Simulator/assets/157167532/7f4d744c-e0af-40be-9c23-6db3392835b4)

![box](https://github.com/lauren-e-gardner/Fabric_Simulator/assets/157167532/a5f7bc96-2fa9-4027-b797-6c3216168962)



### Extra
* Rain

![rain](https://github.com/lauren-e-gardner/Fabric_Simulator/assets/157167532/aff6ea74-f1e6-481d-8644-0be5b9200a43)

* Changing Winds

![wind](https://github.com/lauren-e-gardner/Fabric_Simulator/assets/157167532/727ded32-7e05-43b7-ae56-e479321b2e68)


### Installing and Executing

Download repository and run the following in terminal:
```
python3 -m http.server
```
to start a locally hosted server. Navigate to browser and open the server.

## Authors

Source code from Princeton University
