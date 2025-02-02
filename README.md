# Lost Ark Fishing bot release 1.5
A quick and easy way to farm any fish you need. For example, all the fish and materials to craft simple oreha fusion material and basic oreha fusion material.

## Lastest changes/additions
* Added support for 4k resolution
* Added automatic tool repair function (only tested on monitors with 16:9 resolution sofar)

# Download guide
* Click at latest release:\
  ![latest release](https://i.imgur.com/2QW7b3y.jpg)
* Download and extract main.zip or the antiafk.zip.
* Then run either the file main.exe or antiafk.exe. A console window will open, just go back into the game.\
  ![main.exe](https://i.imgur.com/oQ0B55h.jpg)
* Main.zip fishes without any pauses between casts and automatically repairs at certain intervals.
* Antiafk.zip waits between 8 to 10 minutes between casts, to prolong your fishing energy, preventing you from being kicked for being AFK.

# Game settings and key bindings
* By default, the bot uses the default Lost Ark key bindings for fishing and opening the pet inventory:
* E for fishing:\
  ![fishing on slot e](https://i.imgur.com/zI3m8Bd.png)
* ALT+P to open the pet inventory (for automatic repairs):\
  ![pet inventory window](https://i.imgur.com/L85XF6q.png)
* If you have changed your key bindings ingame, you can also change the key bindings the bot uses, in the file resources/keybindings.yaml:\
  ![key bindings file location](https://i.imgur.com/iyarDPN.png)\
  ![key bindings file](https://i.imgur.com/GpMy9sq.png)
* If you don't use a modifier (for example alt) to open the pet menu, just leave the field pet-inventory-modifier empty:\
  ![key bindings without modifier](https://i.imgur.com/KbZTbzO.png)

# Usage guide
To start fishing, go to a fishing spot ingame, start main.exe or antiafk.exe and tab back into the game. If you have a second monitor you can watch the bot output in the console window that opened.

The start of the fishing bot in the console window:
![fishing bot console window](https://i.imgur.com/viQGaqW.png)

Visual output in the console when a fish is caught:
![fishing bot console window](https://i.imgur.com/s7jpMZ7.png)

The fishing bot will continue to fish forever. Since your fishingrod will slowly break, after every 50 casts the bot will automatically repair all of your tools and then continue fishing.

## Tier 1 and Tier 2
In T1 and T2 I suggest fishing in East Luterra -> Wavestrand Port:
![t1 and t2 fishing spot](https://user-images.githubusercontent.com/22813288/158251293-58e40762-2abd-4cee-b29a-b980476221b2.png)

## Tier 3
Once in T3 I suggest fishing in Punika -> Starsand Beach:
![t3 fishing spot](https://user-images.githubusercontent.com/22813288/158258635-6937508f-9aab-480c-9e91-9346e88c3353.png)

# Supported resolutions
* HD (1080p)
* 2k (1440p)
* 4k (2160p)

# If you would like to create your own .exe file:
1. Install: ```pip install pyinstaller```
2. Run following command: ```pyinstaller --add-data "resources;resources" main.py```
3. Your exe file should generate in ```dist\main\main.exe ```

# Code installation guide
* Clone repo ```git clone https://github.com/DamienShahan/LostArkFishingBot.git```
* Install python https://www.python.org/downloads/

# Donations
* Any donations are greatly appreciated: https://www.paypal.com/donate/?hosted_button_id=G3GRAKMYJGEMC
* I hope you have fun with the Lost Ark fishing bot