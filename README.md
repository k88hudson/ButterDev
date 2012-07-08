# Sublime Text 2 Utilities for Butter

If you use Sublime Text 2 for working with Butter, make it more awesome:

## Setup instructions
1. Find your packages folder. If you're on a mac, try:
```
cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
```
2. Clone this repository
```
git clone https://github.com/k88hudson/ButterDev
```
3. Try typing `mit` and press TAB in a new file to test.


## Snippets

### Butter License
Shortkey: `mit` + TAB
```
/* This Source Code Form is subject to the terms of the MIT license
 * If a copy of the MIT license was not distributed with this file, you can
 * obtain one at http://www.mozillapopcorn.org/butter-license.txt */
```

### CSS Sections
Shortkey: `---` + TAB in a css/less file
```
/* [Your cursor]
-------------------------------------------------- */
```

### Video
Shortkey: `video` + TAB
```HTML
<video id="[your cursor/video]" preload data-butter="media" controls>
  <source src="http://videos-cdn.mozilla.net/serv/webmademovies/trailer.mp4">
  <source src="http://videos-cdn.mozilla.net/serv/webmademovies/trailer.ogv">
  <source src="http://videos-cdn.mozilla.net/serv/webmademovies/trailer.webm">
</video>
```
