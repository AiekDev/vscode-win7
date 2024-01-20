# Visual Studio Code - Windows 7, 8 & 8.1 backport
This isn't really a fancy readme but I don't give a shit

## How to remake this yourself:

### 1. Compile VSCode or get it from the official site
Doesn't matter really, all that matters is you get VSCode from somewhere

### 2. Get supermium-electron (shoutout to win32)
Supermium-electron is backported electron 28, you can find it here >>> https://github.com/win32ss/supermium-electron/releases/tag/v28-testing

## Now that you have everything you need, you can porting!

### 3. Now, do what I did in that screenshot


<p align="center">
  <img alt="a" src="https://media.discordapp.net/attachments/721626533290180730/1198310033952350339/image.png">
</p>

### 4. Replacing @vscode folder

in VSCode version 1.85.2, the @vscode folder inside of node_modules.asar.unpacked just decided to refuse working with windows 7 & 8 for some reason, to revert this you will have to download VSCode 1.85.1 and use its @vscode folder OR you can just get it off this github page (i uploaded it here for convenience). Just follow what I do in the image:

<p align="center">
  <img alt="a" src="https://cdn.discordapp.com/attachments/721626533290180730/1198316041336533012/image.png">
</p>

### 5. That's it!

You're done, this is what the finished product should look like

<p align="center">
  <img alt="a" src="https://media.discordapp.net/attachments/721626533290180730/1198295120869605396/image.png">
</p>

if this documentation is too shitty for you to understand just dm me on discord and ill help you (discord tag: aiek.)
