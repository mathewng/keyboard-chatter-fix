# keyboard-chatter-fix
I have a logitech G810 keyboard experiencing severe keyboard chatter.
The fix will limit the rate of the keyboard and is not suitable for gamers.

## Windows
Registry patch for Windows.
The patch applies the fix to the current user and the default "user" (the user for Windows login screen).

The fix introduces a 40ms debounce period and a minimum of 10ms period to hold down a key to accept the keypress. This might break some macro functionality that sends keystrokes without delay between keystrokes or a hold down delay (KEY DOWN followed immediately by a KEY UP without delay).

The patch has only been tested on Windows 10.

Download the registry patch @ https://github.com/mathewng/keyboard-chatter-fix/releases/latest
