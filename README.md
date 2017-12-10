# Automatic Webpage Scroller

This Linux bash script will press keyboard navigation shortcuts to scroll through web-pages.
It's designed for users who want to set up an old computer next to their main one as a news feed. I run mine on my server, since its GUI isn't doing anything otherwise, and the script doesn't take many resources away from the server services.

Features:
- Very simple.
- Should work with any browser. (Tested in Firefox & Chrome)
- Scrolls through multiple tabs if open.
- Annotated code is easy to adjust for faster or slower scroll speeds.

PLEASE NOTE:
- You will not be able to use your computer while running this script. It pretends to be the user pressing hotkeys. It will keep scrolling until you close the terminal window.
- This script depends on xdotool. You will need to install this dependency before running script.

To install xdotool, run:
sudo apt-get install xdotool
sudo apt-get update

To install:
1. Clone this repository to your machine.
2. In terminal, navigate to the file and run this command:
sudo chmod u+x AutomaticPageScroller

To run:
1. Open your browser and get your tabs ready. (I like to keep mine bookmarked with the Home button.)
2. In terminal, run the script with the command:
./AutomaticPageScroller
3. Press any key on the keyboard and switch back to your browser.
4. After 10 seconds, the browser will enter full-screen mode (F11) and press the down button twice every 2 seconds.
