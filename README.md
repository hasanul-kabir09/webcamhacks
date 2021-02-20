# webcamhacks
Control your social media using simple python code
#Install packages 
pip install opencv-python
import cv2
#open camera using below command
cap = cv2.VideoCapture(1)

#install another packages 
pip install numpy

#cv2 yellow color range

lower = np.array([22, 93, 0])
upper = np.array([45, 255, 255])

#PyautoGUI package installation
pip install pyautogui
