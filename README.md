# vue-vite-electron
fast start to using vue 3,vite 3, vuetify 3, electron.js.

## Scripts 
- yarn dev - launch dev version on browser
- yarn electron:dev - launch dev version on windows app 
- yarn electron - launch windows app 
- yarn build - build web project
- yarn build:docs - build web project for github pages
- yarn app:build - compile windows app

## sass, post.css and other

## Structure
```
dist - compiled version for the browser
dist_electron - compiled version for windows
docs - compiled version for github pages
github - files for readme.md
public - static files
src - vue folder
| assets 
| components
| plugins
| styles
| App.vue - launch component for vue
| main.js - launch js for cite
index.html - launch html
main.js - settings for electron.js
preload.js - preload script for electron.js
vie.config.js - vite config file
```
## Roadmap
- [x] add vuetify
- [x] add sass support
- [ ] add ts support
- [ ] add vuex
- [ ] add vue router
- [ ] add vue devtools for electron
- [ ] try to add vue native
## Technologies used 
- vue 3
- vite
- vuetify 3
- electron.js
- sass