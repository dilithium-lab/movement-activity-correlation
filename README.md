The project correlates movement transitions and patterns of photometry-based neuronal activity.

The project provides python code in Jupyter Notebook for analyses
1) Generate photometry activity templates corresponding to movement onsets and offsets based on Deeplabcut tracking ('1. Template_generation.ipynb')
2) Generate set of actual movement events  ('2. Movement_detection.ipynb')
3) Event detection based on photometry templates for movement onsets (e.g. '20241220_init_template_2_0_1_5.npy') and offets (e.g. '20241220_arrest_template_2_0_1_5.npy') ('3. Template_matching.ipynb')
4) Analysis of detected events to actual movement events ('4. Event_analysis.ipynb')

The analysis code is specifically designed for photometry data acquired via the TDT photometry system and behavioral coordinates obtained via Deeplabcut.

Example photometry data for template matching can be found here:
TDT photometry file: https://figshare.com/s/96a6e3b55a524c79e396
Deeplabcut file: https://figshare.com/s/eca7c516e26adcdfe828

Installation
Jupyter Notebook is provided via Anaconda (https://www.anaconda.com/download/success) with Python 3.11.
Code has specifically been tested on the Windows version.

Dependencies
pandas
operator
cv2
csv
math
matplotlib
numpy
operator
scipy
seaborn
tdt

Other notes:
To test the code, it is necessary for the folder paths to be changed to the locations of the photometry and deeplabcut-generated files. Sample code output is shown in Jupyter Notebook.


