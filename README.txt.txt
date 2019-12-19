CPSC 481 Final Project
Abhyuday Vatsavai
Louis Tagatac
Juan Linares
Project Name: The Vibe Check

OS: Windows 10
Python Version: 3.6.8

References: 
Dependency Installation Guide:
https://www.codingforentrepreneurs.com/blog/install-opencv-3-for-python-on-windows/
Tutorial Video For Making The Bot:
https://www.youtube.com/watch?v=PmZ29Vta7Vc&t=9s


Dependencies Required:
numpy 1.17.2
opencv-contrib-python 4.1.2.30
opencv-python 4.1.2.30
Pillow 6.2.1

How to run:
launch Windows Powershell:
Navigate to main project directory in powershell, this could be in your downloads folder, wherever you downloaded it
To Train the bot you must run this command within powershell: python trainingfaces.txt
//the more images that we have within the/sauce folder the more we can train the bot to recognize genuine smiles, this is an example of supervised learning
To Run the bot, within the same directory, input this command: python faces.txt


Issues:
Issues may arise if there are too many shapes in the background. To continuously train the bot using supervised learning we must 
continue to drop pictures of smiles into the smiles folder, this way we can get much more accurate vibe checks

note: It is recommended you test this with pictures of your own face to ensure that the vibe check works, in addition to that 
make sure you are testing this in a clear background behind you facing the camera.

