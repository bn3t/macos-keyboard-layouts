# macos-keyboard-layouts

MacOS keyboard layouts I might need

# Install

I have found that it works best when installed for all users. If not some Apple apps refuse to use this keyboard and revert to the default one.

    sudo cp Belgian\ \(Microsoft\ Keyboard\).keylayout /Library/Keyboard\ Layouts

Logout / login again.

# Setup

Go in System Preferences > keyboard.

* Choose Text Input > [Edit], Click the [+] icon at the bottom left of the dialog to add a new keyboard layout. The Belgian (Microsoft Keyboard) should appear in the Other section.
* Click [Add] to add this keyboard.
* Optional: Change modifier keys: Also in System Preferences > keyboard, click [Keyboard Shortcuts...], Choose in the left menu, Modifier Keys, choose the name of the keyboard, at the top right of the screen. Reverse the assignement of the Alt and Cmd keys. Command key should have the Option key selected, Option key should have command.

# To edit

Maybe best to use Ukulele tool. http://software.sil.org/ukelele/

## Belgian (Microsoft Keyboard).keylayout

Belgian Keyboard with specifics for the Microsoft Keyboard. It is customised to keep '{' and '}' available with Option + 5 and Option + ) as it is working this way when on the MacBook Pro keyboard.
