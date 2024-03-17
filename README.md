# EDA_Project

Google Colab File Link :- https://colab.research.google.com/drive/1_8PAnxAF9EgTh_1-wZxocGbPuHB6vv7I#scrollTo=5VeYQ4FIicwR

# Importing Necessary Libraries.
import io
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt

io: This library provides functions for working with input and output streams. It's often used to handle file-like objects.

pandas (imported as pd): Pandas is a powerful library for data manipulation and analysis. It provides data structures like DataFrame and Series, which are widely used in data science tasks.

numpy (imported as np): NumPy is a library for numerical computations in Python. It provides support for arrays, matrices, and mathematical functions, making it essential for numerical operations in data analysis.

seaborn (imported as sns): Seaborn is a statistical data visualization library built on top of Matplotlib. It provides a high-level interface for creating attractive and informative statistical graphics.

matplotlib.pyplot (imported as plt): Matplotlib is a plotting library for creating static, animated, and interactive visualizations in Python. The pyplot module provides a MATLAB-like interface for creating plots and visualizations.

# Uploading Dataset / File.
from google.colab import files
uploaded = files.upload()

from google.colab import files: This line imports the files module from the google.colab package. The files module provides functions for uploading and downloading files in Colab.

uploaded = files.upload(): This line prompts the user to upload a file from their local system to the Colab environment. When you run this code cell, it will display a file upload dialog box where you can select a file from your computer.

After the file is uploaded, the uploaded variable will contain a dictionary-like object that maps file names to their content. You can then use this uploaded file in your code for further processing, such as reading the data into a Pandas DataFrame for analysis.
