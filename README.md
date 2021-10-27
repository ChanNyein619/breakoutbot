# breakoutbot
[image](https://user-images.githubusercontent.com/80990018/138997898-dbe21beb-a82e-4df0-bd40-187a7c49a964.png)

This repository contains an example project of a text-based adventure game built with Rasa. 
The goal is to host and maintain a proper text based escape room that you can play with. !
This project is open to outside contributions and we're recording the milestones/lessons learned in a series on Youtube.

# Start Locally
If you want to play around with this game locally you can clone this repository and setup Rasa. This project currently uses Rasa version 2.2.

git clone git@github.com:RasaHQ/breakoutbot.git
pip install rasa
rasa train
Once you've done this, you should be able to run rasa actions and play the game.

rasa run actions & rasa shell
If you want to run this with Rasa X locally, you'll need to install it first.

python -m pip install rasa-x==0.31 -i https://pypi.rasa.com/simple
rasa x
Remember, when you're running Rasa X you'll also need to make sure that the custom actions are running in the background.
