# AR Head Tracker 

![Unity](https://img.shields.io/badge/Unity-2022.3%2B-black?logo=unity)
![Platform](https://img.shields.io/badge/Platform-Meta_Quest-blue?logo=meta)
![Language](https://img.shields.io/badge/Language-C%23-239120?logo=c-sharp)

A Unity AR application built for Meta Quest headsets that utilizes real-time Passthrough. It is designed to visualize live 6 Degrees of Freedom (6DoF) pose data and seamlessly log head-tracking metrics into on-device CSV files for further analysis.

## Features
* **Real-time Passthrough:** Blends the virtual tracking elements with the real-world environment.
* **Live 6DoF Pose Visualization:** Tracks and displays the exact position and rotation of the user's head in real-time.
* **On-device Data Logging:** Automatically records the tracking metrics into a `.csv` file stored locally on the Meta Quest headset.

## Demo
https://github.com/user-attachments/assets/53438c7e-63af-44b6-8759-946b79867989

## Tech Stack
* **Engine:** Unity AR
* **Language:** C#
* **Hardware:** Meta Quest (2 / Pro / 3)

## How to Use / Installation*
1. Clone the repository.
2. Open the project in Unity.
3. Build and run on your Meta Quest device.

## 📄 Output Data (CSV Format)
The application generates a CSV file containing the following tracking metrics:
`Timestamp, Position_X, Position_Y, Position_Z, Rotation_X, Rotation_Y, Rotation_Z, Rotation_W`
