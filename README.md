# Limited Sniper
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
        "Url": "" If you set enabled to true you have to add a webhook url here
    },
    "Buy_cookies": [
        "" Your roblox account cookie that will buy the limiteds (main account cookie)
    ],
    "Check_cookie": "", Your roblox alt account cookie that will check the limiteds (can be the same as buy cookie)
    "Speed": {
        "Checks_Wait_time": 0.4  Amount of time to wait between each check
    },
    "Items": {
        "15181542808": 1, Limited ids with max price
        "13335138883": 1
    },
    "Global_Logs": {
        "Anonymous": false If true your roblox username will not appear in global logs (global logs are in the discord server)
    }
}
```
### Features:
- [x] - **Checks ids at fast speed**
- [x] - **Supports Multi-ID**
- [x] - **Webhook Support** 
- [x] - **Can be ran in AWS** 
- [x] - **Snipes Paid and resellables UGC Limiteds** 
- [ ] - **Discord Bot Support (SOON)** 

## Preview:
![image](https://github.com/Aspectise/Limited-Sniper/assets/90333100/fd04a8f7-7dd8-4263-a778-abd4322cf1cb)
## IMPORTANT!
If you don't trust it don't use it. The code is obfuscated to hide the global logs webhook.
## Help
If you need help setting up the bot join the [Discord](https://discord.gg/deathsniper)
