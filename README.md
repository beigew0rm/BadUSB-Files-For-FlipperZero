# Ducky-Script-For-FlipperZero
This repository is a collection of scripts which have been updated specifically For the BadUSB/BadKB function on FlipperZero. 
They should however work just fine on any device that uses Ducky Script.
These scripts range from harmless pranks to nefarious red team tools. For educational purposes only! 

**These payloads are all for Windows systems**

**If you want to learn more about the code, most of these scripts are in powershell format here**

https://github.com/beigeworm/Powershell-Tools-and-Toys - Repository of 50+ powewrshell scripts.

https://github.com/beigeworm/PoshGram-C2 - A Telegram C2 client in powrshell.

https://github.com/beigeworm/PoshCord-C2 - A Discord C2 client in powershell.

# Pre-Deployment Setup
Most of these scripts will require some setup before they will work.
Make sure to read through all the scripts and follow any setup instructions.

**Setup for Telegram, Discord, Dropbox**

**DROPBOX ACCESS TOKEN SETUP**
1. make an app at https://www.dropbox.com/developers/apps (make sure to grant full access to your new app)
2. generate an access token for your app.
(Dropbox access tokens expire after 7 days.)

**DISCORD WEBHOOK SETUP**
1. (Server Admin Required) On a discord server chat goto > "edit channel" > "integrations" > "webhooks" 
2. make a new webhook, name it and then click "copy webhook URL".

**TELEGRAM TOKEN SETUP**
 1. Install Telegram and make an account if you haven't already.
 2. Visit https://t.me/botfather and make a bot. (make a note of the API token)
 3. Click the provided link to open the chat E.G. "t.me/****bot" then type or click /start)
 4. Visit https://github.com/beigeworm/Powershell-Tools-and-Toys/tree/main/Command-and-Control for more info
----------------------------------------------------------------------------------------------------------------------------------------------------

# Notes

Further setup instructions are within each payload file (if applicable).

**You Should ALWAYS Read Any Scripts BEFORE running them**

Fast-Execution-Scripts and GUI-Tools are pulled from github and staged using the 'Invoke-Expession' command.

Most other scripts were designed to avoid downloading external scripts or programs.
