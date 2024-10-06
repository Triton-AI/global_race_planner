# Global Race Planner

Global Race Planner is a ROS2-based package that provides tools and algorithms to facilitate global path planning for autonomous racing vehicles. This package has been developed and modified from components of the [ForzaETH/race_stack](https://github.com/ForzaETH/race_stack/tree/ros2-humble) repository, with additional modifications and features for our specific use case.

## Features

- Path planning algorithms for autonomous racing
- Enhanced sensor integration for better race performance
- Modular architecture for easy extension and customization
- ROS2 Humble / Foxy compatibility

## Installation

### Prerequisites

- ROS2 Humble / Foxy
- Python 3.8+
- Colcon build system

### Steps to Install

1. Clone this repository:
   ```bash
   git clone https://github.com/Triton-AI/global_race_planner.git
   cd global_race_planner
2. Install dependencies:
   ```bash
   rosdep install --from-paths src --ignore-src -r -y
3. Build the workspace:
   ```bash
   colcon build
4. Source the workspace:
   ```bash
   source install/setup.bash
## Contributing
We welcome contributions! Please fork this repository and submit a pull request for any enhancements or bug fixes. Make sure to follow the coding standards and provide relevant documentation.

## Acknowledgment
This project incorporates code from the open-source project [ForzaETH/race_stack](https://github.com/ForzaETH/race_stack/tree/ros2-humble). Significant portions of the global planning logic are derived from this repository and have been modified to suit the needs of this project. Please review the original repository for more information on the original implementation.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## License Information
Global Race Planner incorporates components from ForzaETH/race_stack, which is licensed under the MIT License. The license from ForzaETH is included in the LICENSE file.