# Marker-Based AR using Vuforia Engine

## Overview

This project is a Marker-Based Augmented Reality application developed using Unity and Vuforia Engine.

The application uses an Image Target as a marker. When the marker is detected through the device camera, a 3D virtual object appears on the marker and follows its position and rotation.

## Technologies Used

- Unity
- Vuforia Engine
- C#
- Android
- 3D Models
- Image Target

## Features

- Marker-Based Augmented Reality
- Image Target detection
- Real-time tracking
- 3D object placement
- Object follows the detected marker
- Android support

## How It Works

1. Open the AR application on an Android device.
2. Point the camera toward the registered image marker.
3. Vuforia Engine detects the Image Target.
4. The 3D object appears on the detected marker.
5. The virtual object follows the marker as it moves.

## Requirements

- Unity
- Vuforia Engine
- Android device with a camera
- Vuforia License Key
- Registered Image Target

## Project Structure

```text
Assets/
├── Scenes/
├── Scripts/
├── Prefabs/
├── Models/
├── Materials/
└── ImageTargets/

Packages/
ProjectSettings/
README.md
