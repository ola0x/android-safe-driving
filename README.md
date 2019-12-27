# Android Safe Driving
## Problem Statement</br>
The leading cause of <b>Accidents</b> on the road is due to drowsey driving. In the United states alone over 80,000 crashes in a year on the road was due to drowsey driving</br>
- National Highway Traffic Safety Administration (NHTSA)</br>

<b>NHTSA</b> defines distracted driving as any activity that diverts attention from driving, including talking or texting on your phone, eating and drinking, talking to people in your vehicle, fiddling with the stereo, entertainment or navigation system, anything that takes your attention away from the task of safe driving.</br>
According to the CDC motor vehicle safety division, one in five car accidents is caused by a distracted driver. Sadly, this translates to 425,000 people injured and 3,000 people killed by distracted driving every year.</br>
You cannot drive safely unless the task of driving has your full attention. Any non-driving activity you engage in is a potential distraction and increases your risk of crashing.</br>
Nowadays, thanks to the help of new technologies, car companies are integrating systems with cutting edge technologies that can prevent crash accidents and reducing the number of deaths and injuries.</br>

## What to Implement
For this project an ML model will be trained on images from a competition, hosted on kaggle by State Farm called State Farm Distracted Driver Detection.</br>
The goal was to predict the likelihood of what the driver is doing in each picture.</br>
### The dataset consist of 2D dashboard camera images that fall in the following 10 categories:
- c0: Safe driving
- c1: Texting — right
- c2: Talking on the phone — right
- c3: Texting — left
- c4: Talking on the phone — left
- c5: Operating the radio
- c6: Drinking
- c7: Reaching behind
- c8: Hair and makeup
- c9: Talking to passengers

## How it works
The ML model will be trained using tensorflow 2.0 and will be deployed to an android application.</br>
The app will be placed in front of the car facing the driver and would run inference in real time. The classified images will will be automatically voiced out by the application in real time</br>


## Technology Stacks
- Keras with Tensorflow 2.0 backend
- Google Colab
- Android studio
- Android TextToSpeech

## Why Deploy to the smartphone
The number of smartphone users as of <b>2019</b> was 3.2 billions and that number is expected to 3.8 billions by <b>2021</b> According to [Statista.com](https://www.statista.com/statistics/330695/number-of-smartphone-users-worldwide/) </br>
With a smartphone, all the drive needs is to install the android application.

## Future
- Implement Object detection
- Deploy to an IoT device
- Train the model on more data other than images.
- Gather data on the vehicle navigation position

