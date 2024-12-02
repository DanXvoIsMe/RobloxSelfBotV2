# Selfbot-Luau-roblox

# Example script
```lua
local Bot = loadstring(game:HttpGet("https://raw.githubusercontent.com/skbiditoiletrizz327/Selfbot-Luau-roblox/refs/heads/main/src/main.lua"))()

Bot:addCommand("!output",function(info) --> !output hello eg
    Bot:Output(`[~] {info.username} with userid {info.userId} said: {info.content}`,194, 120, 17) --> content: hello
end)

Bot:Websocket({
    ["token"] = "",
})
```


### Example output of how it would look like when someone does "!output Hello World!" in a discord chat
![Alt text](https://raw.githubusercontent.com/skbiditoiletrizz327/Selfbot-Luau-roblox/refs/heads/main/src/console.png)

Now you can do a whole lot of more with this when forking it and modifying it yourself. Im just giving you the base.

However I will probaly not continue updating this repository due to me working on a discord bot framework which will also be fully writen in luau with embed & components support.
