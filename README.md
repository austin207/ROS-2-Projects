# ROS 2 Beginner Projects

## Description
This directory contains some of the beginner projects I did to learn ROS 2. These projects are designed to help new users understand the basics of the Robot Operating System 2 (ROS 2) and its functionalities.

## Installation Instructions
To get started with these projects, ensure you have ROS 2 installed on your system. Follow the official [ROS 2 installation guide](https://docs.ros.org/en/jazzy/Installation.html) for your operating system.

## Usage
Each project can be built and run using the following commands:

```bash
# Navigate to the project directory
cd <project_directory>

# Build the project
colcon build --packages-select <package name> --symlink-install

# Source the setup file
source install/setup.bash

# Run the project
ros2 run <package_name> <executable_name>
```

Replace `<project_directory>`, `<package_name>`, and `<executable_name>` with the appropriate values for each project.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have suggestions or improvements.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
