# Nethra-A-vision-in-dark
An android application which detects and recognizes the objects and specifies them to the user by converting the text to speech. It is useful for visually challenged people for identifying objects in their surroundings.

## Software
* Tensorflow
* Android Things
* Etcher

## Hardware
* Raspberry pi3 module (It supports Android things)
* Camera
* Button
* Earphones
* Board

## Working
* In order to run android application on an IOT platform we need a board which is compatabile for **Android Things** (An android based operating system platform). And **Raspberry pi3** is an perfect choice for the requirement.
* Etcher is used for writing image files of android things into SD card which is later installed into the Raspberry pi board.
* Camera is used for capturing a picture triggered by a button action. This captured image is preprocessed and bit maps are generated whcih are sent to **Tensorflow API** for **image recognition**.
* Tensorflow gives the ouput in text format which is later converted into speech using **google text-to-speech** services.
* Power to the board can be given directly using **Micro USB port** of the board with recommended input voltage 5V and input current 2A.

## Dependencies
* **Tensorflow - 1.2**
* **Android Things - 0.4.1**

## Work Flow
![workflow-illustration](https://github.com/mohan-veer/Nethra-A-vision-in-dark/blob/master/images/workflow.jpg)

## Device
![Device-image](https://github.com/mohan-veer/Nethra-A-vision-in-dark/blob/master/images/Nethra.jpg)



