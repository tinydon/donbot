
**All the files are in ZIP archive. Please download the zip and extract it to the desired folder. It is a complete package with pyamf folder included. The only thing you need to change is the config.py file wehre you need to enter the registered tinychat username instead of CHANGE_TO_YOUR_USERNAME & your password for the same username instead of CHANGE_TO_YOUR_PASSWORD.

Thanks,
Team Tinydon.**


# Tinydon - Donbot - Basic (beta)
This is just a slimmed down version of the Tinydon Donbot tinychat bot and with basic functions and a few Administrator commands

** This contains no YouTube or Soundcloud, It only has general functions, Check the wiki for commands. **



![Github code](https://img.shields.io/badge/Code-Python-green.svg) <br>

**To run the bot please open config.py and add your credentials, change the keys then save, Then to run don.py**
<br>
**Please check the [commands](https://github.com/tinydon/donbot/wiki) for the full list.**
<br><br>
This is a bot to use in your Tinychat room,<br>
It's an aid to help moderate a room from spam and bad users,<br>
This is using the pinylib library by [nortxort](https://github.com/nortxort/),<br>
You'll need all the dependencies for this to work,<br>
You can install the modules directly in your python library or run them from the bot folder,<br>
Just make sure you have [Python 2.7](https://www.python.org/downloads/) installed.


**I've also provided my own Api key World Weather Online,<br>
I would recommend that you register with each provider and use your own Api key, The link are provided below.**

* [World Weather Online](http://developer.worldweatheronline.com/api/)

**Windows**
* `C:\Python27\Scripts\pip2 install bs4 requests colorama goslate` or

* `cd c:\Extracted folders directory\ python setup.py install` 

or

* open command prompt or Powershell and type `pip install bs4 requests colorama goslate`

**Mac**
Open the terminal and type

* `sudo easy_install pip` then

* `pip install bs4 requests colorama goslate`

**Help running Python and pip from inside command prompt or windows shell.
To be able to run `pip` inside command prompt on Windows use the below info,<br>
Open start, locate control panel and open it, click `System and Security`,<br>
Then click `System`, on the Right click `Advanced system settings`,<br>
Then click `Environment Variables`, In the System variables box scroll to Path and double click it,<br>
It will open a box, Click `Edit` or `New` depending on your version of Windows,<br>
Now type `C:\Python27\;C:\Python27\Scripts\;` Click Ok<br>
Now open Command Prompt or Shell and type in `python` and click Enter it should now open python in the window,<br>
Now you can run pip directly inside command prompt, `pip install bs4 requests colorama goslate`.**

# Tinydon - Donbot - basic (beta)


- Remove alot of default stuff from Tinychat-Bot
- Added Spam Join Flood Protection
- Added !forgive and !forgiveall
- Added !verified and !rmverified for auto-broadcasting accounts
- Added !lockdown and !lockdownall
- Added in !cam

Bugs
- RTMP craps out on flood, something about 'seek' not being sent
- Spam Join Flood Protection hasn't really been tested

Todo
- Tmp Mod System to allow !kick, !ban !cam, !close
