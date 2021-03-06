# ROS simulation for Fetch Mobile Manipulator

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This repository contains a ROS package to use Fetch robot in Gazebo simulator. It contains a modified model of [kitchen_dining](https://github.com/osrf/gazebo_models/tree/master/kitchen_dining).


![Simulation Screenshot][simulation-screenshot]


<!-- GETTING STARTED -->
## Getting Started


### Prerequisites

* Install General packages for Fetch robots: 
  ```sh
  sudo apt install ros-melodic-fetch-calibration ros-melodic-fetch-open-auto-dock \
  ros-melodic-fetch-navigation ros-melodic-fetch-tools -y 
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/hri-group/fetch_simulator.git
   ```
2. Build package
    ```sh
    catkin build
    ```
3. Source setup file
    ```sh
    source devel/setup.bash
    ```

<!-- USAGE EXAMPLES -->
## Usage
1. Run launch file
    ```sh
    roslaunch fetch_simulator simulation.launch
    ```


<!-- MARKDOWN LINKS & IMAGES -->
[simulation-screenshot]: https://user-images.githubusercontent.com/63774344/102276863-8f249a00-3f7b-11eb-8b8d-3ac47e720c67.png
