# Rock_Paper_Scissors-CNN-Python
A simple Rock-Paper-Scissors game using Convolution Neural Network in Python, where using the webcam (using OpenCV) you can play your move and see yourself who's the winner - You or the Computer.

# Requirements:
Major requiremnets are-
* Python3
* Keras
* Tensorflow
* OpenCV

Other requirements and dependencies alongwith the above ones are mentioned in the ```requirements.txt``` file.

# Usuage:
1. Clone the repository.
2. Install dependencies using the following command in a terminal.
``` 
pip install -r requirements.txt
```
3. Collect images for each 4 gestures(i.e. rock, paper, scissors and none) along with proper arguements. For e.g.-
```
python gather_images.py scissors 200
```
4. Train the model using the following command-
```
python train.py
```
5. Test teh model with any image. For e.g.-
```
python test.py 5.jpg
```
6. Play the game with your computer!
```
python play.py
```

# References:
* Sourav Johar's Youtube Channel(https://www.youtube.com/channel/UCbsI5Rw9_yLccfoMEYYxDCg)
