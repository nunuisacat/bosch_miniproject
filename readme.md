# Bosch Mini Project

This project is an enhancement of the original D* Lite motion planning algorithm proposed by vss2sn under [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics/blob/master/PathPlanning/DStarLite/d_star_lite.py).

## Introduction

D* Lite is a powerful path planning algorithm designed for partial-known environments, commonly utilized in robotics, autonomous vehicles, and similar applications. It efficiently computes optimal or near-optimal paths while adapting to dynamic changes in the environment.

The primary goal of this project is to improve the functionality of the D* Lite algorithm by incorporating an additional feature. This feature allows the conversion of an input image into an obstacle map, which can then be fed into the D* Lite algorithm for path planning.

## Features

- **Image to Obstacle Map:** The core enhancement involves introducing a new function that enables the transformation of an input RGB or greyscale image into an obstacle map. This obstacle map is then utilized as input for the D* Lite algorithm.

## Getting Started

To make use of this improved D* Lite algorithm, follow these steps:

1. **Clone the Repository:** Begin by cloning this repository to your local machine.
2. **Prerequisites:** Ensure you have the necessary dependencies installed. These include Python relevant libraries OpenCV and NumPy.
3. **Run the Code:** Utilize the enhanced D* Lite algorithm by running the provided script. This script incorporates the image-to-obstacle-map conversion and path planning functions.

## Usage

1. **Converting Image to Obstacle Map:** Use the provided function to convert an input image into an obstacle map. This function will be available as part of the project's codebase.
2. **Path Planning:** Leverage the enhanced D* Lite algorithm to plan paths within the created obstacle map. The algorithm can effectively navigate through dynamic environments and generate optimal or near-optimal paths.

## Acknowledgments

This project builds upon the D* Lite algorithm originally proposed by vss2sn. The enhancements and image-to-obstacle-map functionality were added to extend the algorithm's capabilities.

## License

This project retains the original license of the D* Lite algorithm by vss2sn. Please refer to the [LICENSE](https://chat.openai.com/LICENSE) file for more details.