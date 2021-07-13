
---
## **00 ROS**


### Robot Operating System (ROS) - The Complete Reference 3 (2018)
> **INDEX**: 00_00

> **ABOUT**: Compilation of papers describing some interesting ROS packages. Not necessarily very helpful, tbh. One of the other volumes contains the paper on elevation_mapping.

---
## **01 mapping**

### Slides - Techniques for 3D Mapping
> **INDEX**: 01_00

> **ABOUT**: A slide deck containing a conceptual overview of different 3D mapping techniques and terrain representations, including 2D/3D costmaps, height maps, multi-level surface maps, and more.

### Layered Costmaps for Context-Sensitive Navigation
> **INDEX**: 01_01

> **ABOUT**: Paper by prominent ROS navigation developer (David Lu!!) that talks about layered costmaps. Both conceptual reasoning behind them, and some sparse implementation details.

### Occupancy Grid Map Merging for Multiple-Robot Simultaneous SLAM
> **INDEX**: 01_02

> **ABOUT**: Contains a useful description of feature and segment detection in Occupancy Grids. Mainly though, it's about fusing the maps of two robots into one, using feature and segment detection.

> **NOTE**: DEFINITELY come back to this and do a more thorough read, has a lot of information about feature and segment detection that could be very useful.

### Vision Feature Extraction Algorithm for Occupancy Grid Maps Merging
> **INDEX**: 01_03

> **ABOUT**: Similar to 01_02 (though less in-depth), discusses map merging via feature detection/extraction via ORB.

### A fast incremental map segmentation algorithm based on spectral clustering and quadtree
> **INDEX**: 01_04

> **ABOUT**: Paper that develops an algorithm for map segmentation to generate semantic maps (both geometric and semantic info).

---
## **02 terrain**

### Probabilistic Terrain Mapping for Mobile Robots with Uncertain Localization
> **INDEX**: 02_00

> **ABOUT**: Paper that describes the rationale behind the elevation_mapping package and its robot-centric terrain mapping.

### Terrain classification in complex 3D outdoor environments
> **INDEX**: 02_01

> **ABOUT**: Very technical paper discussing methods for obstacle-detection and path-planning in complex outdoor terrain.

---
## **03 SOAR**


### SOAR User's Manual
> **INDEX**: 03_00

> **ABOUT**: Definitive documentation on the SOAR cognitive architecture; concepts, implementation details, syntax, etc.

### An Introduction to Soar as an Agent Architecture
> **INDEX**: 03_01

> **ABOUT**: Concepts of SOAR

### Cognitive Robotics using the Soar Cognitive Architecture
> **INDEX**: 03_02

> **ABOUT**: Using the SOAR cognitive architecture to directly control an autonomous robot. 

### Application of Soar Cognitive Agent Based on Utilitarian Ethics Theory for Home Service Robots
> **INDEX**: 03_03

> **ABOUT**: Very strange paper about implementing a SOAR architecture with Bentham-style Utilitarian ethics.

### Implementation of a Refusable Human-Robot Interaction Task with Humanoid Robot by Connecting Soar and ROS
> **INDEX**: 03_04

> **ABOUT**: Paper that goes into some depth about a combined SOAR/ROS system as well as the interface between them, implemented as a ROS node "wrapper" around a SOAR client.

### Completing Ambiguous Plans in Cognitive Robotics with Delayed Information
> **INDEX**: 03_05

> **ABOUT**: Goes into more implementation details than (03_04) about an interface between SOAR and ROS using a SOAR Markup Language (SML) client program.
