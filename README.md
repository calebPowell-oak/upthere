# UpThere

## Description

__UpThere__ is an application for mobile devices that creates a visualization of the orbits of satellites currently in orbit. Augmented reality is used as a means for creating a real-time, location specific visualization of satellites and their associated orbits. Through the application's interfaces, users can select from a catalogue of active (and inactive) satellites to view. Using the mobile device's location information and orientation sensors, a dynamic view can be constructed to reflect the users real-world situation in an AR visualization. Multiple views will be made available to the user: POV and Birdseye. POV will frame the visualization from the perspective of the user. Birdseye will allow the user to view the 3D situation from a high altitude.
#### Technologies Utilized
* [Unity Development Engine](https://unity.com/) - For multiple device compatibility and native 3D environment
  * [Simple Kepler Orbits](https://assetstore.unity.com/packages/tools/physics/simple-kepler-orbits-97048) - Asset for displaying keplerian orbits
* [MySQL Database](https://mysql) - storing orbital parameters in standardized format
* [Spring Boot Web Service](https://spring.io/projects/spring-boot) - Facilitate the transfer of orbital parameters to a mobile client and the update of satellite parameters over time
* [CelesTrak](https://celestrak.com/NORAD/elements/) - Datasource for current two-line element sets.

#### GPS Integration (pending)
Using mobile device's GPS connection information, GPS satellites that a user is actively connected to can be highlighted in the POV view. In birdseye view, lines of sight between the user on the ground and satellites in space can be highlighted as GPS satellites come into view and connect with the user.

# Preview Images

<details>
  <summary>POV Images</summary>
 
## User Ground POV
![ground view with menus](https://github.com/calebPowell-oak/upthere/blob/master/images/povMenu.png "something")
![ground view](https://github.com/calebPowell-oak/upthere/blob/master/images/povNoMenu.png)
</details>

<details>
  <summary>Bird's Eye Images</summary>
 
## Bird's Eye View
![birdeye view with menus](https://github.com/calebPowell-oak/upthere/blob/master/images/birdeyeMenu.png "something")
![birdeye view](https://github.com/calebPowell-oak/upthere/blob/master/images/birdeyeNoMenu.png "something")
</details>
