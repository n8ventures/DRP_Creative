# Discord Rich Presence for Creative Apps
### Show your friends what you're working on, be it in Adobe Suite, Autodesk Suite, Cinema 4D or many more!
This app runs in the background and looks for processes, then parses the windows title and turns it into a project name to display with Discords Rich Presence.

Examples:
![example1](https://i.imgur.com/yFzQh6O.png)
![example2](https://i.imgur.com/fziotzt.png)
![example3](https://i.imgur.com/9SEXuQr.png)

## how to install:
1. Grab the latest version from the [Releases](https://github.com/n8ventures/DRP_Creative/releases) page, then make a folder in `C:/Program Files/` and call it whatever, for example `DRP Creative`. 
3. Do `[WindowsButton] + R`, type `Shell:StartUp`, hit enter. A folder will open.
4. Put the exe file inside this folder(Now the app will start on pc start)
5. If you want to run it now, double click it
6. Enjoy!

## How to use:

-   When it's running, you'll notice a new icon appear on your Taskbar. If you want to exclude the **currently open project** from showing up, click on the icon and click on `Don't show current project`.
![icon showcase](https://i.imgur.com/nADffGB.png)

-   To change the portfolio website or remove excluded projects and words from the program, run the program at least once, and a `.drp_config` file will appear. You can open this with any text editor and rewrite the lines there. be gentle though, program expects a certain format for the file ^^'

### Currently supported programs:
**Full support:**
-   Cinema 4D
-   Adobe After Effects
-   Adobe Illustrator
-   Adobe Photoshop
-   Adobe Premiere Pro
-   Autodesk Maya
-   Autodesk 3Ds Max
-   Davinci Resolve
-   Isotropix Clarisse
-   Calvary
-   Ableton
-   FL Studio
-   Blender

**Partial support:** *(meaning it shows up on Discord, but doesn't display the project name)*
-   Marvelous Designer ¹*
-   Substance Designer ¹*
-   Substance Painter  ¹*
-   Adobe Audition ¹*

¹*sadly not doable, project name not in proces window title. They will show up though, just with default project name*
