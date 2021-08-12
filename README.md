# Custom/mod version of @madslundt's [keybindings repo](https://github.com/madslundt/keybindings).

Make use of caps lock, remap arrow keys to `{ i, j, k, l }` and extra stuff.

For [Linux](#linux) and for [Windows](#windows)

# Linux
## AutoKey
[AutoKey](https://github.com/autokey/autokey) needs to be installed for Linux. This can be downloaded within Ubuntu package manager. The scripts can be found [here](linux/autokey).

At first caps lock has to be changed to function as the **hyper** key. This can be done with **Gnome Tweak Tool**.

| Shortcut                         | Output                           |
| -------------------------------- | -------------------------------- |
| CAPSLOCK + { i, j, k, l }        | { Up, Left, Down, Right }        |
| CAPSLOCK + CTRL + { i, j, k, l } | ALT + { Up, Left, Down, Right }  |
| CAPSLOCK + ALT + { i, j, k, l }  | CTRL + { Up, Left, Down, Right } |
| CAPSLOCK + { u, o }              | { Home, End }                    |
| ALT + { i, k }                   | { PageUp, PageDown }             |

Move the scripts to the directory `~/.config/autokey/data/`.

# Windows

## AutoHotkey
[AutoHotkey](https://autohotkey.com) needs to be installed for Windows. The scripts can be found [here](windows/autohotkey).

| Shortcut                                | Output                           |
| --------------------------------------- | -------------------------------- |
| CAPSLOCK + { ; }							  		  	| { Delete }						           |
| CAPSLOCK + CTRL + { ; }									| CTRL + { Delete }						     |
| CAPSLOCK + { p }												| { Media play/pause }				     |
| CAPSLOCK + { u, o }              				| { Home, End }            				 |
| CAPSLOCK + CTRL { u, o }        				| CTRL + { Home, End }             |
| CAPSLOCK + CTRL + SHIFT { u, o }        | CTRL + SHIFT + { Home, End } |
| CAPSLOCK + { y, h }									  	| { PageUp, PageDown }						 |
| CAPSLOCK + CTRL + { y, h }							| CTRL + { PageUp, PageDown }	     |
| CAPSLOCK + { i, j, k, l }        				| { Up, Left, Down, Right }				 |
| CAPSLOCK + ALT + { i, j, k, l }         | ALT + { Up, Left, Down, Right }  |
| CAPSLOCK + CTRL + { i, j, k, l }				| CTRL + { Up, Left, Down, Right } |
| CAPSLOCK + CTRL + SHIFT { i, j, k, l }  | CTRL + SHIFT + { Up, Left, Down, Right } |
| CAPSLOCK + SHIFT + ALT + { i, j, k, l } | SHIFT + ALT + { Up, Left, Down, Right }  |

### Automatically start up
 1. Find the script file, select it, and press Control-C.
 2. Start **Run** and write `shell:startup`.
 3. Right click and choose **Paste Shortcut**. The shortcut to the script should now be in the Startup folder.

 If you need to run it as administrator either make sure the scripts is set up to administrator or start Command Prompt as administrator and run the scripts within.
