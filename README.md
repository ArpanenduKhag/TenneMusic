# Discord.js TenneMusic, Music Bot using erela.js
# A Advance Discord Music Bot Like Hydra

[Erela.js docs](https://solaris.codes/projects/erelajs) **Note this Discord Bot Repository is the Same as for the Public Bot [Lava Music](https://lava.milrato.eu) if u want to support me, then please [invite](https://lava.milrato.eu) him!**

## [**DISCORD SUPPORT SERVER INVITE**](https://discord.gg/HsFVamFb4N)

**IF YOU WANNA USE CUSTOM EMOJIS, AND SHARD THEN CHECK OUT THE CUSTOM-EMOJIS TAB(branch)!**

## Installation | How to use the Bot

 **1.** Install [node.js v12+](https://nodejs.org/en/download/) or higher

 **2.** Download this repo and unzip it    |    or git clone it

 **3.** Install all of the packages with **`npm install @discordjs/opus @ksoft/api ascii-table canvacord canvas colors common-tags discord.js enmap erela.js erela.js-deezer erela.js-facebook erela.js-spotify lyrics-finder ms radio-browser `**     |  the important packages are   **`npm install discord.js erela.js`**

 **4** Fill in the parameters, RIGHT in `botconfig/config.json`!

 **5.** [Download Lavalink](https://cdn.discordapp.com/attachments/798196676405755905/827174915714711572/Lavalink.jar) and download Java 15 (Java 13 recommended)

 **5.1** Run the Lavalink file with: **`java -jar Lavalink.jar`**

 **MAKE SURE THAT THERE IS THE `application.yml` FILE OTHERWISE IT WILL NOT WORK!

 **6.** start the bot with **`node index.js`**

#### **NOTE:**

*If you are having errors/problems with starting delete the package.json file and do, before you install the packages `npm init`*



## Windows start Command .bat file
```bat
@ECHO OFF
ECHO ==========================
ECHO Starting Lavalink
ECHO ==========================
start cmd /k java -jar ./Lavalink.jar
ECHO ==========================
@ECHO Taking a 5 Second Break for Lavalink
ECHO ==========================
timeout /T 5 /nobreak
ECHO ==========================
@ECHO Starting BOT
ECHO ==========================
start cmd /k node .
exit /s'
```
Windows `start.bat` file
Which starts Lavalink and the Bot together via one click ;)

Have it in the Same folder as `index.js` and `Lavalink.jar`


