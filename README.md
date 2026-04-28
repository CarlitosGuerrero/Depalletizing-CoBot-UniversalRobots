# Depalletizing-CoBot-UniversalRobots
This project implements a depalletizing system using a Universal Robots cobot programmed in PolyScope. The system handles pallets where boxes are arranged in an alternating, non-uniform pattern, combining horizontal and vertical orientations across layers (e.g., two horizontal and one vertical, followed by two vertical and one horizontal).

The robot identifies and picks each box sequentially using a vacuum gripper, ensuring stable handling regardless of orientation. A separation layer between stacking patterns is also considered during the process. Each box is then placed onto a conveyor belt for downstream operations.

The solution focuses on flexibility and reliable handling of mixed-orientation pallet patterns, demonstrating practical cobot integration for semi-structured depalletizing tasks.

![Depalletizing System](https://github.com/CarlitosGuerrero/Depalletizing-CoBot-UniversalRobots/blob/main/depalletizing.png)

![Depalletizing Simulation](https://github.com/CarlitosGuerrero/Depalletizing-CoBot-UniversalRobots/blob/main/image.png)
