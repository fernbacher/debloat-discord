# Fast and Easy Method to Debloat Discord

- Browse to your local AppData folder (type in `%LOCALAPPDATA%`) and browse to your Discord installation, then the `modules` folder.
- Keep only `discord_desktop_core-1`, `modules-1`, `utils-1`, `voice-3`. You may want to keep other modules too that you might need.
- Now go up a folder and go into the `locales` folder.
- Keep only the language you use and I advise to keep `en-US.pak` to prevent issues (from personal experience).
- This method should continue to work whatever the Discord version, feel free to fix anything in a pull request though.
- Disabling updates by creating a shortcut to the Discord executable directly should prevent the modules from coming back, but this is not advisable.
- **⚠ Warning: With each Discord update, the modules & locales will come back! This is why it is advisable to use Discord web or a client alternative like [WebCord](https://github.com/SpacingBat3/WebCord).**
