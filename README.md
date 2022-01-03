# Custom/mod version of @madslundt's [keybindings repo](https://github.com/madslundt/keybindings).

Using the caps lock key to remap `{ i, j, k, l }`  to act as arrows and several other keys to act as common shortcuts.

For [Linux](#linux) and [Windows](#windows)

# Linux
## AutoKey
[AutoKey](https://github.com/autokey/autokey) needs to be installed for Linux. This can probably be found on your package manager. The scripts can be found [here](linux/autokey).

Caps lock has to be changed to work as the **hyper** key. This can be done using *Gnome Tweak Tool* or under *System Settings -> Input Devices -> Keyboard -> Advanced -> Caps Lock behavior -> [x] Make Caps Lock an additional Hyper* in KDE.

| Shortcut                                | Output                           |
| --------------------------------------- | -------------------------------- |
| CAPS LOCK + { ; }							  		  	| { Delete }						           |
| CAPS LOCK + CTRL + { ; }								| CTRL + { Delete }						     |
| CAPS LOCK + { p }									   		| { Media play/pause }				     |
| CAPS LOCK + { u, o }              			| { Home, End }            				 |
| CAPS LOCK + CTRL { u, o }        				| CTRL + { Home, End }             |
| CAPS LOCK + SHIFT { u, o }        			| SHIFT + { Home, End }       	   |
| CAPS LOCK + CTRL + SHIFT { u, o }       | CTRL + SHIFT + { Home, End }     |
| CAPS LOCK + { y, h }									  | { PageUp, PageDown }						 |
| CAPS LOCK + CTRL + { y, h }							| CTRL + { PageUp, PageDown }	     |
| CAPS LOCK + { i, j, k, l }        			| { Up, Left, Down, Right }				 |
| CAPS LOCK + ALT + { i, j, k, l }        | ALT + { Up, Left, Down, Right }  |
| CAPS LOCK + SHIFT + { i, j, k, l }      | SHIFT + { Up, Left, Down, Right }|
| CAPS LOCK + CTRL + { i, j, k, l }				| CTRL + { Up, Left, Down, Right } |
| CAPS LOCK + CTRL + SHIFT { i, j, k, l } | CTRL + SHIFT + { Up, Left, Down, Right } |
| CAPS LOCK + CTRL + ALT { i, j, k, l }   | CTRL + ALT + { Up, Left, Down, Right } |
| CAPS LOCK + SHIFT + ALT + { i, j, k, l }| SHIFT + ALT + { Up, Left, Down, Right }  |

Move the scripts to the directory `~/.config/autokey/data/`.

Add `autokey-gtk` or `autokey-qt` to the autostart config to have it running automatically or select the "*Automatically start Autokey at login*" option on the app preferences.

# Windows

## AutoHotkey
[AutoHotkey](https://autohotkey.com) needs to be installed for Windows. The scripts can be found [here](windows/autohotkey).

| Shortcut                                | Output                           |
| --------------------------------------- | -------------------------------- |
| CAPS LOCK + { ; }							  		  	| { Delete }						           |
| CAPS LOCK + CTRL + { ; }								| CTRL + { Delete }						     |
| CAPS LOCK + { p }												| { Media play/pause }				     |
| CAPS LOCK + { u, o }              			| { Home, End }            				 |
| CAPS LOCK + CTRL { u, o }        				| CTRL + { Home, End }             |
| CAPS LOCK + SHIFT { u, o }        			| SHIFT + { Home, End }       	   |
| CAPS LOCK + CTRL + SHIFT { u, o }       | CTRL + SHIFT + { Home, End } |
| CAPS LOCK + { y, h }									  | { PageUp, PageDown }						 |
| CAPS LOCK + CTRL + { y, h }							| CTRL + { PageUp, PageDown }	     |
| CAPS LOCK + { i, j, k, l }        			| { Up, Left, Down, Right }				 |
| CAPS LOCK + ALT + { i, j, k, l }        | ALT + { Up, Left, Down, Right }  |
| CAPS LOCK + SHIFT + { i, j, k, l }      | SHIFT + { Up, Left, Down, Right }|
| CAPS LOCK + CTRL + { i, j, k, l }				| CTRL + { Up, Left, Down, Right } |
| CAPS LOCK + CTRL + SHIFT { i, j, k, l } | CTRL + SHIFT + { Up, Left, Down, Right } |
| CAPS LOCK + CTRL + ALT { i, j, k, l }   | CTRL + ALT + { Up, Left, Down, Right } |
| CAPS LOCK + SHIFT + ALT + { i, j, k, l }| SHIFT + ALT + { Up, Left, Down, Right }  |

### Caps Lock state/behavior
Caps Lock default behavior is `AlwaysOff`. This feature can be enabled by pressing both `Shift` keys at the same time. This will toggle the Caps Lock state until only one `Shift` key is pressed, when the `AlwaysOff` state will be restored.


### Automatically run at start up
 1. Find the script file, select it, and press `Control + C`.
 2. Start **Run** and write `shell:startup`.
 3. Right click and choose **Paste Shortcut**. The shortcut to the script should now be in the Startup folder.

 If you need to run it as administrator, either make sure the script is set up to administrator or start Command Prompt as administrator, and run the script within it.
