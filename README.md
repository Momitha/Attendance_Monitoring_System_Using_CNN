# Attendance_Monitoring_System_Using_CNN

Made using Google Colab platform.
First step is to either upload the images of the user using live capture or upload a zip file consisting of all the students along with their rollnumbers.
Second is to perform data augmentation.
Use CNN modules for face detection.
Face can be identified by three methods- Capture a live picture and the model predicts the person, give a image manually or by live streaming video.
Attendance is calculated and excel sheet is created.

Libraries need to be imported:
import matplotlib.pyplot as plt 
import pandas as pd
import seaborn as sns
import numpy as np
import cv2
import os
import warnings
warnings.filterwarnings('ignore')
from google.colab.patches import cv2_imshow
from IPython.display import display, Javascript, Image
from google.colab.output import eval_js
from base64 import b64decode, b64encode
import PIL
import io
import html
import time
import pytz
from datetime import datetime
