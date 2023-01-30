A tool for visualizing storage usage.

Inspired by WizTree, a highly optimized visualizer, and duviz, a python command line visualizer.

Project goals:

Going to use Python to get more comfortable, I want to work with Python ML libraries in future projects.
For the visualization, ideally I will end up using a treemap, but I will attempt to use horizontal bar graphs initially.


Current progress/goals:

Use os.walk as a starting point for implementation, as a predefined method for scanning a directory tree. Probably want it to operate topdown. The python docs have an example of getting the filesize of subdirectories through using os.path.getsize for each subdirectory.

Look into https://docs.python.org/3/library/os.html, specifically os.walk, os.path, and os.stat
