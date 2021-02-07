# New Unity
A Unity like Layout for Latte Dock

![New Unity as it is in use on my Desktop](assets/images/Screenshot_001.png)
New Unity as it is in use on my Desktop

---
## How to use
### <u>Prerequisites:</u>
- [Latte Dock](https://invent.kde.org/plasma/latte-dock) (You need a version compiled from the latest commits)  
***This does not work with the stable build of Latte Dock as of February 2021***
  - Arch Linux AUR: [latte-dock-git](https://aur.archlinux.org/packages/latte-dock-git/)
  - Ubuntu and derivatives PPA: [latte-dock](https://launchpad.net/~rikmills/+archive/ubuntu/latte-dock)
- Third Party Plasmoids:
  - [Window Buttons](https://store.kde.org/p/1272871/)
  - [Window Title](https://store.kde.org/p/1274218/)
  - [Window AppMenu](https://store.kde.org/p/1274975/)
    - This is replaceable with the default Plasmoid "Global Menu"
  - [Media Player +](https://store.kde.org/p/1317639/)
  - [Netspeed Widget](https://store.kde.org/p/998895)
  - [USwitcher](https://store.kde.org/p/1194339)
  - [Present Windows Button](https://store.kde.org/p/1181039)
- [My layout file](New-Unity.layout.latte)

### <u>"Installing":</u> 
0. Install Latte Dock and the Third Party Plasmoids
1. Start Latte Dock
2. Remove all plasma panels
3. Right Click onto your Latte Dock and click on "Configure Latte..." 
4. Click on "Import..." and choose my layout file
5. the switch to the "Preferences" tab and enable 
   "Support borderless maximized windows in different layouts"
6. Click on "Apply"
7. Clock on the layout "New Unity" and then on the button "Switch"

### <u>Verifying that everything works™:</u>
You should now check if everything is correctly loaded
1. Open a new Dolphin window and maximize it
2. Now check if the top bar has all plasmoids (from left to right):
   - Window Buttons (Close, Maxmimize/Restore, Minimize buttons)
   - Window Title (It should show the application title; in this case "Dolphin")
   - Window AppMenu (The menu bar of the application)
   - Media Player + (most likely "No media" followed by a play button)
   - Netspeed Widget (Plasmoid which shows how big your network traffic is)
   - System Load Viewer (Two bars which show CPU and RAM Usage)
   - System Tray
   - Notifications
   - KDE Connect
   - Night Color Control
   - Removable Devices
   - Bluetooth
   - Network
   - Audio
   - Clock
   - USwitcher (Shutdown Symbol)
3. Now check if the side bar has all plasmoids (from top to bottom):
   - Application Launcher
   - Latte Tasks (The many application icons)
   - Present Windows Button
   - Trash

Is everything loaded?
- Yes! — Good!
- No!
  - Try to add the missing plasmoids via: Right Click -> Add Widget  
    If the plasmoid isn't shown in the list make sure the plasmoid is correctly installed  
    Instructions should be available if needed at the plasmoid page linked above

### <u>Editing the layout to better suit you:</u>
You can edit the layout by right clicking onto the panels and choosing either "Add Widgets" to add Plasmoids or "Edit Panel" to edit the current panel.

---
## More Stuff (from the screenshot):
- GTK,Qt5, Plasma: [Sweet Mars](https://store.kde.org/p/1393507/) by [EliverLara](https://github.com/EliverLara) 
- Icons: [McMojave-Circle](https://store.kde.org/p/1305429)
- Cursors: [Capitaine Cursors](https://store.kde.org/p/1148692)
- Wallpaper: Taken from the song [スピークイージー by wotaku](https://www.youtube.com/watch?v=P8aUNilN7JQ)
- 