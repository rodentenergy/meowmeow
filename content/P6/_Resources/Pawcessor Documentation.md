---
tags:
  - UI
  - Tools
  - Resources
---
# Download

Can be downloaded here: [Google Drive - Pawcessor](https://drive.google.com/file/d/10fwEzH8T-xvWQvdi47lhQWea5OYjujpz/view?usp=sharing)

<hr>

# How to use - TLDR

- Drag and drop singular or multiple files/folders into field
- Select an output folder or use the Input root folder
- Customize name standard, prefix, and suffix as needed
	- If you don’t want to change the name change this to {name}
	- If you’re processing files and not folder the {folder_name} doesn't actually do anything
- Start processing images :3c
- You will now have a .PNG and .DDS (BC7_SRGB) version of your converted image


<hr>

# What exactly it does
It takes .PNG, .JPG, .JPEG, and .TARGA images and pads them to the nearest power of 2, renames them, and converts them to .DDS (BC7_SRGB) format. 

For example if you wanted to process this folder
- finished
	- HUD
	- Menus
		- buttonBack
		- creditsMenu
		- levelSelect
		- mainMenu
		- pauseMenu
		- settingsMenu
		- skillTree
	- Misc

You would drag the “finished” folder into the field under “Please drag and drop files/folder here:”

Then you could choose your own output folder if you wanted, if you don’t the program will create a new folder in the same folder that “finished” is in. Leaving you with these two folders.

- UI
	- finished
		- HUD
		- Menus
			- buttonBack
			- creditsMenu
			- levelSelect
			- mainMenu
			- pauseMenu
			- settingsMenu
			- skillTree
		- Misc
	- finished_new
		- HUD
		- Menus
			- buttonBack
			- creditsMenu
			- levelSelect
			- mainMenu
			- pauseMenu
			- settingsMenu
			- skillTree
		- Misc

In the finished_new folder you’ll find all the processed images. There will 2 versions of every converted image, one .PNG and one .DDS. You can delete the .PNG version if you want to make it easy to just drag and drop the whole folder into P4V, you’ll have to do this manually for now.

# Walkthrough images
Let’s walkthrough converting a folder called “mainMenu” that has the following images.

![[Pasted image 20241006004302.png]]

First let open the program and drag our folder into the input field. Let’s also use the input folder as the output folder. Lastly, let’s keep the default name standard.

![[Pasted image 20241006015217.png]]

If we press “Start processing images :3c”, we’ll get this folder which contains the following.

![[Pasted image 20241006004558.png]]

![[Pasted image 20241006015127.png]]