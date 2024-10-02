# Things to do today
- ~~Test .py script on school computer~~ 
- ~~**Download unreal on school computer!!!**~~
- ~~Install UVpacker add-on on school computer~~
- ~~Install obsidian on school computer~~
- ~~Install RenderDocs~~
- [x] Take a look at [Welcome to Quartz 4](https://quartz.jzhao.xyz)
- ~~Fina upp UI .py script och skriv dokumentation så den kan delas~~
- ~~^ Lägg till ett alternativ för att konvertera individuella filer~~
- ~~[Photoshop-Export-Layers-to-Files-Fast/README.md at main · antipalindrome/Photoshop-Export-Layers-to-Files-Fast · GitHub](https://github.com/antipalindrome/Photoshop-Export-Layers-to-Files-Fast/blob/main/README.md)~~
# To put into google calendar
- ~~Buy new shower head~~
- ~~Look at shower drain~~
- ~~Get rid of milk next time I take out the trash~~
- ~~Get rid of some of my piles of cardboard~~
- ~~Do dishes~~
- ~~Change sheets~~
- ~~BOOK A DENTIST APPOINTMENT!~~
- ~~Set up kanban board that can be reached from home and school with estimation and time tracking features, preferably something like swim lanes also but anything is fine as long as it can group stuff together~~

```dataviewjs
const {getEvents} = this.app.plugins.plugins["google-calendar"].api; 
const events = await getEvents({ 
  startDate: window.moment(DateTime.now().toJSDate()),
  endDate: window.moment(DateTime.now().toJSDate())
  });

var eventsString = await events.reduce((text, event) => text + ` - ${moment(event.start.dateTime).format("**hh:mm A**")} - ${event.summary.replace(/\//g, "-").replace(/\|/g, "-")}\n`, "");

dv.el("string", eventsString)
```
# Blockout assets
- ~~Crate~~
- ~~Couch~~
- ~~Doorway~~
- ~~Plaza stairs~~
- ~~Tree~~
- ~~Pile of logs~~
- ~~Fix stairs~~
- ~~Make materials~~
- ~~1 screenshot of all assets with player ref~~
- ~~1 screenshot with collision rendering on~~
- ~~1-3 screenshots of close ups~~
- ~~1 video of player traversing the level and demoing the collisions~~

# Standup tomorrow
- Friday I did some planning and had some meetings
- After Friday I made a python script that automatically pads my files to the nearest power of 2, adds the correct suffix and prefix and also makes a .dds version
- Made it so there’s an option to do individual files and folders, if they’re in folders the finished .dds also gets the folder name put after the prefix and before it’s name. So a png or targa called Background in a folder called pauseMenu would become power of 2, a .dds and be named T_pauseMenuBackground_C if you choose to do a folder the folder structure also gets copied over to the output folder.
- Tested the python script in the model viewer compared to images that I converted manually to make sure they turn out correctly and they do :thumbsup:
- Decided to make it a program instead, it can convert single files, multiple files, a folder (including subfolders), and multiple folders. You can also choose an output path, a custom suffix and prefix and change the name standard. I’m not completely done with it but I’m about 95% done, but since it isn’t necessary or useful to anyone else I’ll finish it after school.
- Prepared questions for a UI meeting.
- Did rough blockouts of all UI menus + HUD to illustrate how I’m imagining the layout of everything right now.