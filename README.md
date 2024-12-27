# Guest Book (add message)

## Project Description
This project is the development of Guest Book Website with Micro Frontend approach using Vue. The remote directory is the components provider and the host directory is the main website. So the remote provides shared components that can then be called and displayed on the page by the host. But the host also shares libraries needed by the remote such as vue-router.

Overall this project implement library such as vuex(state management), vue-router(routing), vue authentication(router auth), axios(API request), form handling, list rendering, indexeddb(store data in browser and offline behavior).

This Website is designed to allow Guests to login, logout, see messages and add message create, in other hand allow Admin to login, logout, see messages and add guests.

## Installation

Clone this repository

```bash
  git clone https://github.com/AsyrafbilalFBJ/Guest-Book-MFE.git
```
    
In /remote directory

```bash
  npm install
  npm run build
  npm run serve
```
    
In /host directory

```bash
  npm install
  npm run build
  npm run preview
```
    
Open http://localhost:8001/ in browser.
