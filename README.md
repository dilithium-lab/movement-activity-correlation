The project correlates movement transitions and patterns of photometry-based neuronal activity.

The project provides python code in Jupyter Notebook for analyses
1) Detecting movement initiation and arrest events based on Deeplabcut data ('Movement_detection_optimization.ipynb')
2) Generating photometry activity templates ('Movement_activity_template_generation.ipynb') for movement initiation (e.g. '20220118_init_template_2_5_0_7.npy') and arrest events (e.g. '20220118_arrest_template_1_5_2_0.npy'),
   and then perform template matching to detect events in a specific photometry trace ('Movement_activity_template_matching.ipynb')

The analysis code is specifically designed for photometry data acquired via the TDT photometry system and behavioral coordinates obtained via Deeplabcut.

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


