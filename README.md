# Project Setup Guide

## 1. Install Anaconda and Jupyter Notebook

- Download and install **Anaconda** from the official website:
  [https://www.anaconda.com/products/distribution](https://www.anaconda.com/products/distribution)

- After installation, launch **Jupyter Notebook** using Anaconda Navigator or by running the following command in the terminal or Anaconda Prompt:

  ```bash
  jupyter notebook
  ```

## 2. Install Required Dependencies

Open your terminal (or Anaconda Prompt) and install the necessary libraries:

```bash
pip install opencv-python numpy playsound
```

> Note:
> - `threading` and `os` are standard Python libraries and do not require installation.

### Required Imports in the Code

```python
import cv2
import numpy as np
from playsound import playsound
from threading import Thread
import os
```

## 3. Run the Code

- Open **Jupyter Notebook**.
- Navigate to the folder where your code file is saved.
- Open the `.ipynb` file and run the cells to execute the code.

Alternatively, if you are working with a `.py` script, you can run it directly from the terminal:

```bash
python your_script_name.py
```

