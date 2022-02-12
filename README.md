# Lost Ark Fishing bot release 1.1

# Download guide
* Click at latest release:\
  ![alt text](https://i.imgur.com/Dj1hNl2.png)
* Download and extract main.zip
* Then run the file main.exe. A console window will open, just go back into the game.
  ![alt text](https://i.imgur.com/oQ0B55h.jpg)

# Game settings
* The resolution is set to 2560x1440. You might have to change this in main.py to your resolution. Also you might then have to create your own template images in /resources/.

# Usage guide
* To start fishing, go to the spot ingame, start main.exe and tab back into the game. If you have a second monitor you can watch the bot output in the console window that opened.

# Personalization guide
* Resolution: in main.py, on rows 12 and 13, you can set your resolution.
* Template Images: the template images of the bobber and exclamation point are placed in /resources/. You can create your own without any issue.
* After any changes you can either run main.py in a powershell console with ```py main.py```, or create a new .exe file. This is explained in the next section.

# If you would like to create your own .exe file:
1. Install: ```pip install pyinstaller```
2. Run following command: ```pyinstaller --add-data "resources;resources" main.py```
3. Your exe file should generate in ```dist\main\main.exe ```

# Code installation guide
* Clone repo ```git clone https://github.com/DamienShahan/LostArkFishingBot.git```
* Install python https://www.python.org/downloads/