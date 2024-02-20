# ComputerVisionReconstruction

# Overview
This project focuses on creating a pipeline for 3D high-definition scanning and reconstruction. Utilizing two cameras and a projector, the system reconstructs objects in 3D by projecting structured light and processing the captured images with advanced algorithms.

# Key Features
Stereo Imaging & Calibration: Employs stereo imaging for capturing object details from multiple angles, with an emphasis on accurate camera calibration to minimize errors.

3D Reconstruction: Implements techniques like triangulation and mesh alignment for reconstructing the 3D shape of objects.

Error Handling: Addresses potential inaccuracies caused by factors like camera distortion and image blurring.

# Usage
The process begins with camera calibration using the provided scripts, followed by image capturing, point cloud reconstruction, and mesh generation. The final output is a 3D model of the scanned object, with considerations for mesh cleaning and alignment.
