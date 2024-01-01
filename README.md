This VI meticulously generates panoramic images through a carefully structured process:

Lens Distortion Correction: Specifically addressing Barrel Distortion to ensure precise visual accuracy.
Brightness Variation Compensation: Achieving a seamless transition by compensating variations in brightness.
ROI Blending: Merging carefully determined Regions of Interest (ROIs) using a selected method (Weighted Average - Default, Multi-Band Blending, Wavelet Extraction).
Final Panorama Output: Projecting the corrected and blended elements to produce the ultimate panorama.

User Steps: Navigate to the "Tuning Control Tab" and follow these steps:

Select Grid Image Path: Specify the path for the grid image.
Input Grid Image Name: Enter the grid image name as saved in the device, including its extension.
Choose Left and Right Cameras: Indicate the cameras for the left and right images.
Correction Interpolation Type: Determine the interpolation type for the correction process (Zero-Order, or Bilinear).
Set Wrapping Factor: Define the wrapping factor based on the angle between the cameras.
ROI Resolution: Specify the resolution for the Regions of Interest (ROIs).
Blending Method: Select the preferred blending method (Weighted Average - Default, Multi-Band Blending, Wavelet Extraction).
Run the VI.
