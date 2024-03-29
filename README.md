# Max’s BombParty Bot

> Automatically play acceptable words in the online game BombParty! (www.JKLM.fun) This bot comes preloaded with a dictionary of words, but it also learns new words too! This ensures the words it chooses to answer prompts are as natural as possible. 

(Enabling the Instaplay mode is conspicious and not recommended)


## Installation
1. Ensure you have the latest version of Google Chrome installed on your system
2. Download the repository to a folder on your computer
3. Install the following python packages by navigating to your command line and running
```
pip3 install selenium
pip3 install keyboard
```
4. Launch `Maxs-Bomb-Party-Bot.py` with python3
> If `ModuleNotFoundError: No module name 'example'`, navigate to your command line and run `pip3 install example`!
5. Set up JKLM profile (Optional)
6. Restart the program as necessary, engaging the bot by responding `y` to `Automate?`
> Secondarily, enable Instaplay by responding `y` to `Instaplay?`, although this is unrecommended.
> 
> Or launch "Learn Only" mode by responding `n` to `Automate?`.


## Set Up JKLM Profile (Optional, Est. Time: 3 minutes)

1. Launch `Maxs-Bomb-Party-Bot.py`
2. Wait until www.JKLM.fun loads
3. Configure your profile manually in the top right
4. Once finished, `Right Click` > `Inspect Element`
5. Navigate to `Storage` then `Local Storage`
6. See `JKLM Settings`
7. `Right Click` on the first token (beginning with `{“version”:…}`) > `Edit Value`
8. Highlight and copy the token to your clipboard
9. Navigate to the folder where `Maxs-Bomb-Party-Bot.py` is located on your computer
10. Create a plain text file `profileSettings.txt`
11. Copy the token from `JKLM Settings` into the text file and save. (Ensure the text file only contains the token and no other characters or spaces before/after)

✨ Once you restart the bot, you should see that your profile loads automatically.
