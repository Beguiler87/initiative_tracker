# initiative_tracker
A Python-based, simple initiative tracker for TTRPGs.
---------------------------------------------------------------------------------------------------------------------------------
Overview:
This tool is intended to keep track of combat initiative for GMs running TTRPGs.
Once a list of combatants is entered, the system will display those combatants in initiative order, from highest to lowest.
Keyboard commands will enable the user to advance the initiative as participants complete their turns, and remove participants
who are no longer part of the initiative (ie, They're dead, Jim.).
---------------------------------------------------------------------------------------------------------------------------------
Cloning Instructions (ie, How do I get this on my own machine?):
Open the terminal you intend to use to run this program. It was created using VS Code, but that shouldn't make a difference as
far as users are concerned. Open the directory where you would like to clone to. Once you have done so, in your terminal, type
git clone https://github.com/Beguiler87/initiative_tracker, and press enter. If you run into issues, I suggest reviewing GitHub's 
cloning instructions at https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository.
Depending on your machine, you may need to install Colorama. Visit https://pypi.org/project/colorama/ for more information.
Once installed on your machine, please refrain from pushing any commits to the original git repository. If you wish to make your 
own changes to the program, feel free to do so. However, you may not distribute, sell, or otherwise reproduce the original 
program or its original code without the author's express permission.
---------------------------------------------------------------------------------------------------------------------------------
Entering Combatants in the Initiative Order:
An initiative tracker is useless if you can't put your players and their opponents into it for actual use. To do so, go into the 
initiative_tracker.py file and find the main() function. You will see a number of lines that begin with tracker.add_warrior.
These are the combatants and the relevant information that the system needs to function. Each combatant needs to be entered in the
format "Name", Initiative Score, "ally/enemy". The name can be whatever is appropriate for the character (as you will see from the
examples already entered). The initiative score is a simple number (integers only). However, please remember to enter the side in 
only lower-case letters as the system is currently set to seek an exact match.
---------------------------------------------------------------------------------------------------------------------------------
Using the Tracker:
The initiative tracker has been designed to be as simple as possible. Once you have entered the combatants, simply run the 
program. You can do so by typing "python basicinit.py" in the command line of your termainal. Remember to add the number of the 
version of python you are running to the end of "python" (ie "python3"). This initative tracker was built using Python 3 and may 
not work with earlier versions.
Alternatively, if you are using a program like VisualStudio Code, you may have a "Run File" option when you have 
initiative.py open. Both ways work, simply use the one you are more comfortable with.
Once you have initiated the program, it will print some information to the console and provide a few basic prompts. If at any 
point you are unsure of what to do, you can type in "commands" and press ENTER to see a list of options.
Combat continues on your prompts until one side or the other is defeated. At that point, a message will appear stating which
side is victorious and halt the program.
Enjoy your games! I hope that this tool is useful at your gaming table, or inspires you in some way to create your own tool.
-Beguiler87
---------------------------------------------------------------------------------------------------------------------------------