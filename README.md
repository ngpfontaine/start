# Start Page

> Select a base colour palette, change your search pages, drop in your favourite sites & icons

- Cursor is hidden, everything can be done w/ a keyboard (can be changed at top of ``` main.css ```)

- Auto focus is on search input.

![img preview](https://nicfontaine.com/startp/startp_01.png)


### Usage

1. Use L & R Arrow keys to change search sites.
2. Up Arrow to pull previous searches
3. Down Arrow (to leave search focus), then any Arrow keys to navigate tiles.
4. That's it.

---

### About
- Tile nav isn't grid based, so you can add or remove any and change their size, or container width and arrow navigation will stay intact. (NOTE) may get a little weird with odd numbers that leave like 1 tile on a row or something.

- I just threw in [Font Awesome Icons](http://fontawesome.io/get-started/). Use whatever icons you prefer (you'll have to style them), or flip through there and grab whatever works.

- Add or remove an search sites; just match up placeholder and url slug at the same index in the two array vars below. The little 'slide number dots' below will read the length of the array & increase or decrease accordingly.


### Customize Options
- A few vars in ``` main.js ```:
```
// BASE HUE VALUE (0-360)
var cpbh = 264;

// SEARCH PLACEHOLDERS (use whatever string you want to display)
var searchPl = ['> duckduckgo', '> google'];

// SEARCH SITE URLS (run a search & grab the url minus query string [if it uses one..])
var searchUrlArray = ['https://duckduckgo.com/?q=', 'https://google.com/#q='];
```

### To-Do
- weather updates

### More
Check out my website at [nicfontaine.com](https://nicfontaine.com)  
Twitter: [@ngpfontaine](https://twitter.com/ngpfontaine)

### License
Use it, break it, complain, wtvr.
