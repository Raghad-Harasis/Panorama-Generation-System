This system was developed by Eng. Raghad O. Al-Harasis and Prof. Belal H. Sababha at Princess Sumaya University for Technology. 

The system utilizes two wide-angle cameras that capture images continuously and blend them seamlessly in real-time to generate natural-looking viewing. The system is implemented using LabVIEW, and it is adaptable to any hardware type. A demonstration of the system is available in the "Video record link.txt" file. 


Follow the "User Steps" below to try the program. 

1. Download the "Grid.png" image to be used for camera calibration.
2. Download the "Panorama Generation- cameras. vi" if you want to try the system with cameras or "Panorama Generation-samples. vi" if you want to try the system with sample images. 
3. Open the VI and Navigate to the "Tuning Control Tab."
4. Select Grid Image Path: Specify the path for the grid image.
5. Input Grid Image Name: Enter the grid image name as saved in the device, including its extension.
6. Choose Left and Right Cameras: Indicate the cameras for the left and right images.
7. Correction Interpolation Type: Determine the interpolation type for the correction process (Zero-Order or Bilinear).
8. Set Wrapping Factor: Define the wrapping factor based on the angle between the cameras.
9. ROI Resolution: Specify the resolution for the Regions of Interest (ROIs).
10. Blending Method: Select the preferred blending method (Weighted Average - Default, Multi-Band Blending, Wavelet Extraction).
11. Run the VI.
