# Homebridge-Rooba-STV-passwordgrab
A small applescript to automate grabbing your BILD and Robot Password for Homebridge-Roomba-STV


This is a small AppleScript that can help in automating the process for Homebridge-Roomba-stv (https://github.com/esteban-mallen/homebridge-roomba-stv#readme credit to esteban-mallen for creating the plugin) for macOS users.

set up is VERY simple. save the AppleScript application, and open it in Script Editor on macOS. From there, change the ServerAddress, ServerUserName, and ServerPassword to fit your SSH credentials

```
tell application "Terminal"
	set ServerAddress to "SERVER IP HERE"
	set ServerUserName to "SSH LOGIN USERNAME HERE"
	set ServerPassword to "PASSWORD HERE"
end tell
```

next, save the app.

Finally, run the application you just made. Accept any permissions that are required by macOS for accessiblity. This Script requires Keyboard, and Terminal access.

follow the prompts, and you can now configure your Roomba for Homebridge!

this applescript is set to work with default install locations on a macOS based server, it has not been modified to work with a Raspberry Pi just yet, and i would love some help on that!
