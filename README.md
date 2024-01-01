This system was developed by Eng. Raghad O. Al-Harasis  and Prof. Belal H. Sababha at Princess Sumaya University for Technology. The system utilizes two wide-angle cameras that capture images continuously and blend them seamlessly in real-time to generate natural-looking viewing.  The system is implemented using LabVIEW and it is adaptable to any hardware type. 

User Steps: 
Download the attached "Grid.png" image to be used for camera calibration. 
Navigate to the "Tuning Control Tab" and follow these steps:
Select Grid Image Path: Specify the path for the grid image.
Input Grid Image Name: Enter the grid image name as saved in the device, including its extension.
Choose Left and Right Cameras: Indicate the cameras for the left and right images.
Correction Interpolation Type: Determine the interpolation type for the correction process (Zero-Order, or Bilinear).
Set Wrapping Factor: Define the wrapping factor based on the angle between the cameras.
ROI Resolution: Specify the resolution for the Regions of Interest (ROIs).
Blending Method: Select the preferred blending method (Weighted Average - Default, Multi-Band Blending, Wavelet Extraction).
Run the VI.
