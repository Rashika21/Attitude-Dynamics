# Detumbling, Slew Manoeuvre and Sun Tracking of a Cube-Satellite on a Low Earth Orbit
Course work: Attitude Dynamics and Control of Spacecraft  
Professor: Biggs James Douglas - [Research page](https://www4.ceda.polimi.it/manifesti/manifesti/controller/ricerche/RicercaPerDocentiPublic.do?evn_didattica=evento&k_doc=548867&polij_device_category=DESKTOP&__pj0=0&__pj1=8fe8b50ef34811518f4e049d06747ab1)

## Description
A CubeSat (U-class spacecraft) is a miniaturized satellite made for space purposes and is composed by multiples of 10 x 10 x 10 cm cubic units. CubeSats are commonly
put in orbit by deployers on the International Space Station, or launched as secondary payloads on a launch vehicle. The intent is to provide affordable access to space for the university science community, Government agencies and commercial groups thanks to a standardized design of the whole structure. In satellites, the attitude determination and control subsystem are the module which is responsible for maintaining, monitoring and controlling the satellite attitude against the environmental disturbances torques, which affect the satellite orientation and leads to angular destabilization of the satellite while it is in orbit. In this report design of attitude and control system for the 12 U cube-satellite which is at given orbit is presented.

## Mission Analysis and Design
### Mission Requirements and assigned Parameters 
Project requisites are given below in the table. 

| Requirements  | Details | 
|    :---:    |     :---:      | 
|Type of Cubesat | 12 U |
|Sensors | Sun sensor and Earth Horizon sensor |
|Actuators | 8 Cold Gas Thrusters and 4 Reaction wheels |
|Detumbling | starting with ! > 5deg/s;!final close to 0 deg=s |
|Tracking | Point to Sun with a pointing error Theta < 3 deg |
|Altitude | 500 km |

### Satellite physical properties
The selected spacecraft is in cuboid shape as shown in figure 1. It is assumed that the solar panels are not deployed yet. Various quantities such  as weight, length and moment of inertia are appreciated in the below table.

|Quantity | Value |
| :---: | :---:
| L*W*H* | 20 x 20 x 30 cm^3 |
| Weight | 25 Kg |
| J| 0.2666 ; 0.26; 0.1666 kgm^2 |

12 U Cubesat can be found in the Figure 1. 
![image](https://user-images.githubusercontent.com/64012053/189497641-9590d0e4-5ed5-4e8a-a843-2562d740012c.png)




