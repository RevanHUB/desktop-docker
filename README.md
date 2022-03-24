# desktop-docker
An Electron App to add instant access to applications and websites! 🎆

# 🌌 Use:

``` git clone https://github.com/RevanHUB/desktop-docker ```

``` cd electron-quick-start ```

``` npm run dev ```

# 🕋 How to: 

You can change the shortcuts in controls.js, I added support for 10 shortcuts support for now, interface have space for 20 on X-Axis and if user expands interface, unlimited:

``` let count = new dock("https://google.es", "https://david-martin-webdev.com",  "https://github.com/RevanHUB", "https://twitch.tv", NEW_URL); ``` 

To add the image, use relative paths, store the img inside src folder and add a new line:

``` create__docker(count.element(), URL_IMG); ``` 

# 🎆 Roadmap:

- Dark theme / Light Theme.
- Dinamic way to change the shortcuts with beginner friendly design.
- Optimization of app to consume less. (in this moment performance is good but memory charge have values between 12Mbs and 43,4Mbs, beWidget actually uses 60Mbs of ram).


# 🎆 License:

``` Free for use but I don't allow to change the code without my permission. ``` 
