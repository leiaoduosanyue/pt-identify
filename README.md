# py-mnist-try-cpu
本人通过学习python神经网络编程这本书后，跟着书本写出的简单的手写数字识别cpu版本1.0beta

#此处为调用库  
import numpy  
import scipy.special  
import matplotlib.pyplot  
%matplotlib inline  


下列图片为需要改动的地方，需应人而异  
![images](https://github.com/leiaoduosanyue/py-mnist-try-cpu/blob/main/pictures/test-mnist.png)  
![images](https://github.com/leiaoduosanyue/py-mnist-try-cpu/blob/main/pictures/test-mnist.png)


此次更新提供pytorch  gpu版本的简单数字识别1.0beta  
  
import torch  
import torch.nn as nn  
import torch.nn.functional as F  
import torch.optim as optim  
from torchvision import datasets, transforms  
import random  
import pylab  
import matplotlib.pyplot as plt  

  
2023.10.14 更新手写数字识别GPU版本beta1.1   

此处为新增内容说明：  
增加了简单的ui界面，可利用鼠标绘制数字，并识别。  

![images](https://github.com/leiaoduosanyue/py-mnist-try-cpu/blob/main/pictures/屏幕截图 2023-10-14 211618.png)

 本次更新新调用的库：  
import tkinter as tk  
from tkinter import Canvas, Button  
from PIL import Image, ImageDraw,ImageGrab  
from PIL import ImageOps  
