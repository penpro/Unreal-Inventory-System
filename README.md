This is the repo for my CS141 final project.

This is an inventory system that can store items, provides UI elements for interacting and viewing the items in a GUI, allows for drag drop to and from different inventories as well as into the game world itself to spawn items from dropped items.
The system also has save features for saving player inventory, placed container inventories, dropped items, etc.

The inventory system follows the tutorials from Ryan Laley for a large portion but the save system is significantly different because his is broken.
Specifically I'm using several structure arrays instead of the maps because the maps don't support having uniquely identifiable soft objects so the first, second, etc of any given object will overwrite the previous first, second, third, etc. 

https://www.youtube.com/playlist?list=PL4G2bSPE_8umjCYXbq0v5IoV-Wi_WAxC3

This project assumes you already have github desktop, unreal engine 5.5, and github lfh installed and congiured for use.

Basic setup:
Clone this repo to your local machine with unreal engine installed
Open a new third person map in unreal engine: note the project name, for instance "MyProject", you will need to delete this later.
Copy the entirety of the project folder from the git clone
Paste this content into the blank third person project you just created, then delete the .uproject file with the name noted above, for isntance "MyProject.uproject"
To refresh the projects list in the epic games launched you may need to click to another tab (news, samples, fab, etc) and then click back into "Library" and you should see the project "Inventory"

