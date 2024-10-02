# To do today
- ~~Take a look at [Welcome to Quartz 4](https://quartz.jzhao.xyz)~~
- ~~Finish python program for fixing UI files~~
- https://github.com/antipalindrome/Photoshop-Export-Layers-to-Files-Fast/blob/main/README.md
# UI thoughts
- Something painted for the main menu? A cut out of some sort? Sort of like these? 
	![[Pasted image 20241001125629.png|300]]
- Same vibe as this in general? 
	![[Pasted image 20241001125726.png|300]] ![[Pasted image 20241001130150.png|300]]
- Colors sort of like these? 
	![[Pasted image 20241001125751.png|300]] ![[Pasted image 20241001125813.png|300]] 
	![[Pasted image 20241001125828.png|150]] ![[Pasted image 20241001125839.png|112]]
# UI feedback
- Vilka mockups folk gillade:

| Mockup | Hur många? |
| ------ | ---------- |
| 1      | 2          |
| 2      | 3          |
| 3      | 2          |
| 4      | -          |
| 5      | 3          |
| 6      | -          |
- 
# Standup (för imorgon)
- Friday I did some planning and had some meetings
- After Friday I made a python script that automatically pads my files to the nearest power of 2, adds the correct suffix and prefix and also makes a .dds version
- Made it so there’s an option to do individual files and folders, if they’re in folders the finished .dds also gets the folder name put after the prefix and before it’s name. So a png or targa called Background in a folder called pauseMenu would become power of 2, a .dds and be named T_pauseMenuBackground_C if you choose to do a folder the folder structure also gets copied over to the output folder.
- Tested the python script in the model viewer compared to images that I converted manually to make sure they turn out correctly and they do :thumbsup:
- Decided to make it a program instead, it can convert single files, multiple files, a folder (including subfolders), and multiple folders. You can also choose an output path, a custom suffix and prefix and change the name standard. I’m not completely done with it but I’m about 95% done, but since it isn’t necessary or useful to anyone else I’ll finish it after school.
- Prepared questions for a UI meeting.
- Did rough blockouts of all UI menus + HUD to illustrate how I’m imagining the layout of everything right now.
- Did some first draft mockups to explore the look of the UI.
# Google calendar tasks
```dataviewjs
const {getEvents} = this.app.plugins.plugins["google-calendar"].api; 
const events = await getEvents({ 
  startDate: window.moment(DateTime.now().toJSDate()),
  endDate: window.moment(DateTime.now().toJSDate())
  });

var eventsString = await events.reduce((text, event) => text + ` - ${moment(event.start.dateTime).format("**hh:mm A**")} - ${event.summary.replace(/\//g, "-").replace(/\|/g, "-")}\n`, "");

dv.el("string", eventsString)
```