# To do (put (most) into google calendar ok pls)
- Buy new shower head
- Look at shower drain
- Get rid of milk next time I take out the trash
- Get rid of some of my piles of cardboard
- Do dishes
- Change sheets
- Take more pictures of myself that aren’t at home
- Figure out how to best use daily notes
- Check out google calendar plugin for Obsidian

# Things to do tomorrow before 9am
- Test .py script on school computer 
- **Download unreal on school computer!!!**
- Install UVpacker add-on on school computer
- Make personal youtrack for IND work
- <u>BOOK A DENTIST APPOINTMENT AT 7AM!!!</u>

```dataviewjs
const {getEvents} = this.app.plugins.plugins["google-calendar"].api; 
const events = await getEvents({ 
  startDate: window.moment(DateTime.now().toJSDate()),
  endDate: window.moment(DateTime.now().toJSDate())
  });

var eventsString = await events.reduce((text, event) => text + ` - ${moment(event.start.dateTime).format("**hh:mm A**")} - ${event.summary.replace(/\//g, "-").replace(/\|/g, "-")}\n`, "");

dv.el("string", eventsString)
```