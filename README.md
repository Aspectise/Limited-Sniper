# Limited Sniper
### Next update at 50 ⭐
Limited Sniper let you add limited ids in config.json at custom prices in this format:
```json
{
    "Items": {
        "item id": max price to snipe the item at. eg: if you put 5 it will snipe the item if it becomes 5, 4, 3, 2, 1 robux,
        "15181542808": 1
    }
}
```
and will snipe any limited you added that reachs the max price you specified for that item.

*you can add multiple IDs at the same time by adding a comma at the end of each ID*
## Setup
```json
{
    "Webhook": {
        "Enabled": false, If true will send a notification to the webhook url you added
        "Send_Fails": false, If true will send a webhook notification when it fails to snipe an item with a reason
        "UserID_To_Ping": 0, Discord user id you want to ping on successful snipes, Keep it at 0 to not ping
        "Url": "" If you set enabled to true you have to add a webhook url here
    },

    "Cookies": {
        "Buy_cookie": "", Your roblox account cookie that will buy the limiteds (main account cookie)
        "Check_cookie": "", Your roblox alt account cookie that will check the limiteds (can be the same as buy cookie)
        "Bypass_cookies": false Bypass roblox's region lock
    },

    "Items": {
        "15181542808": 1, Limited ids with max price
        "13335138883": 1
    },

    "Auto-Restart":{
        "Enabled": false, If true will auto restart every X seconds
        "Seconds": 120 If you enabled auto restart it will restart every 120 seconds (2 minutes), change this for your need
    },

    "Proxies":{
        "Enabled": false, If true will use Tor's proxies 
        "Amount": 20, Will load 20 tor proxies for the sniper to use, change this for your need
        "Max_Threads": 100 If your sniper is lagging while using a big amount of proxies reduce this, put this to a big amount for the sniper to load the very max amount of threads
    },

    "Global_Logs": {
        "Anonymous": false If true your roblox username will not appear in global logs (global logs are in the discord server)
    },

    "Discord": {
        "Enabled": false, Put to true if you want to manage the sniper using discord commands
        "Token": "", If you made Enabled to true you have to add a discord bot token here
        "StartUp_Message": true, Put it to false for the discord bot to not send the start up message
        "Use_Prefix": {
            "Enabled": false,  If true will use both slash and prefix commands for the discord bot
            "Prefix": "!" Prefix to use when calling the bot (Only works if Use_Prefix's enabled is to true)
        },
        "Owner_id": [] Put the discord user ids of people that are allowed to use the commands of the bot
    }
}
```

<details>
<summary><strong>How to get discord token! (Click to expand) </strong></summary>

    
#### Create a new [application](https://discord.com/developers/applications)

![image](https://github.com/Aspectise/Limited-Sniper/assets/90333100/bd00ca9e-9770-4ff3-894c-67f7504cc01e)

#### Enable these 3 intents

![image](https://github.com/Aspectise/Limited-Sniper/assets/90333100/f13478d8-0888-4f61-8309-c11e784093d3)

#### Get the token by clicking copy

![image](https://github.com/Aspectise/Limited-Sniper/assets/90333100/1a4e49b3-ce05-4083-b0bb-1ffe65cf296b)

#### To invite the bot: Click copy and paste the url in your browser

![image](https://github.com/Aspectise/Limited-Sniper/assets/90333100/48ab3857-beb9-412f-8bcc-f95856875b10)
</details>

# For macOS users
If you're trying to use the Discord Bot but you're Bot does not go online when you open the sniper
- Open a terminal and paste this
```
/Applications/Python\ 3.11/Install\ Certificates.command
```

### Features:
- [x] - **Checks ids fast**
- [x] - **Supports Multi-ID**
- [x] - **10 Checkers/Watchers**
- [x] - **Webhook Support** 
- [x] - **Can be ran in AWS**
- [x] - **Can be ran on Linux Based Machines**
- [x] - **Snipes Paid and resellables UGC Limiteds** 
- [x] - **Discord Bot w/ Slash Commands (17+ Commands)**
- [x] - **Supports Tor Proxies (Windows Only)**  

## Preview:
![image](https://github.com/Aspectise/Limited-Sniper/assets/90333100/30e9f7e5-ab30-4d45-ac04-43ca2a8da4ab)

## IMPORTANT!
- If you don't trust it don't use it. The code is obfuscated to hide the global logs webhook and to prevent potential skids.
- If you don't want to use tor proxies and dont trust the tor-proxies.exe, delete the folder.
- **If main.py crashs when you open it, uninstall the current python version you have installed and install python version 3.11.x**
## Help
If you need help setting up the bot join the [Discord](https://discord.gg/deathsniper)
