# ROS2 Humble Learning

This repository is dedicated to learning and experimenting with ROS2 (Robot Operating System 2), specifically targeting the Humble Hawksbill distribution. It serves as a resource for notes, code samples, and custom ROS2 packages developed during the learning process.

## Repository Structure

- **notes/**
  - _gitkeep_: Placeholder for organizing and storing learning notes related to ROS2 concepts, commands, and best practices. You can add your own `.md` or `.txt` files here to document your progress.
- **src/**
  - **my_phoneix_controller/**: Custom ROS2 package (or workspace) for experimenting with controller development. This directory is intended for ROS2 nodes, launch files, and other related code.

## Getting Started

### Prerequisites

- ROS2 Humble Hawksbill installed ([installation guide](https://docs.ros.org/en/humble/Installation.html))
- Colcon build tool
- Python 3.x

### Building Packages

```bash
cd src
colcon build
source install/setup.bash
```

### Running Nodes

_Note: Update the commands based on the actual nodes/scripts you add to `my_phoneix_controller`._

```bash
ros2 run my_phoneix_controller <node_name>
```

## Notes

Keep your learning notes and documentation in the `notes/` directory for easy reference.

## Contributing

Feel free to fork this repository, add your own notes, and experiment with new packages or nodes.

## License

This project is open source and available under the [MIT License](LICENSE).
