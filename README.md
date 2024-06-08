The project correlates movement transitions and patterns of photometry-based neuronal activity.

The files are code for
1) Detecting movement initiation and arrest events based on Deeplabcut data ('Movement_activity_correlation_detection_optimization.ipynb')
2) Generating photometry activity templates for movement initiation (e.g. '20220118_init_template_1_5_1_0.npy') and arrest events (e.g. '20220118_arrest_template_1_0_1_6.npy'),
   and then perform template matching to detect events in a specific photometry trace ('Movement_neuronal_activity_cross-correlation_analysis.ipynb')
