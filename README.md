# CSN-150 FINAL
#Final project for CSN150
#Name of the project
StormBreaker
#Purpose
The purpose of this tool is to gain unauthorized access to the audio, video and gps capabilities of devices, potentially for surveillance or eavesdropping purposes. It's important to note that the use of such tools for unauthorized access or malicious activities is illegal and unethical.
#Equiment
Laptop and charing cable. (this tool is software based and it does not require any external components)
#Documentation i followed 
https://www.youtube.com/watch?v=UkoPCbp_vBk
https://github.com/ultrasecurity/Storm-Breaker
https://www.geeksforgeeks.org/storm-breaker-social-engineering-tool-in-linux/
#Steps I followed
$Step 1:
I first went to this github repository "https://github.com/ultrasecurity/Storm-Breaker"
#Step 2:
I downloaded the repository as a zip and i unziped it in my desktop.
#Step 3:
I downloaded virtual box to be able to run linux
#Step 4:
I needed to make sure that i had all de dependencies installed
php
python3
git
Ngrok
#Step 5:
I had to open my terminal and navigate to my desktop where i unziped the folder.
#Step 6:
inside the folder was everything i needed to install except Ngrok so i had to run the necessary commands to install everything
$ cd Storm-Breaker
$ sudo bash install.sh
$ sudo python3 -m pip install -r requirements.txt
$ sudo python3 st.py
#Step 7:
after everything is installed you will be able to open another window in terminal and run 
$ngrok http 2897
this will allow you to use StormBreaker online.
#Problems
Some of the problems i encounter were
1. I was not able to run the software properly on my computer (MAC OS) so i downloaded a virtual machine.
2. When i installed the virtual machine i did it without a GUI because i didnt have enough memory but i had to end up installing a desktop because i needed to use an internet browser
3. when i had to link my Ngrok token to the StormBreaker i had an issue because the key was too long and i had to input it multiple times
#Conclusion
In conclusion this was a very fun project and now i have a tool that i can keep working on and i will make sure to use it ethically and responsably.
