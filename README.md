# Plutonium
Welcome to Plutonium | V ~ B.1.0.0

# Supported Games
 [Blox Hunt] 
+ Tazer Anyone
+ Energy Fill
+ Health Fill
+ Walkspeed

 [Universal] 
+ Esp
+ Aimbot

## <a href="https://github.com/nrv-ous/Hydroxide/blob/master/main.lua"><b>Main.lua</b></a>

```lua
--[[
                       ▄█▄
                       █████████████▄
                       ███        ███
                       ███        ███
                       ███        ███   ██▄       ▄██
                       █████████████▀   ███       ███
                       ███              ███       ███
                       ███              ███       ███
                       ███              ███       ███
                       ███              ▀██▄     ▄██▀
                       ▀█▀                ▀███████▀


                     All import code is from Hydroxide                
       thanks to the hydroxide team for letting anyone use there code 
       Welcome to Plutonium, a free script hub that was in development
         sense 3/1/20. Feel free to use any of the code you see and 
        make any changes or copys of the code as you wish all we want 
          in return is that you give use credits sorry if you dont
               understand the code feel free to contact use at

     Any things else you want to know check out our website and discord
         Discord:    https://discord.gg/5rtFxpv
         Website:    

                And a great thanks from the Plutonium Team <3
]]--
local import = function(toimport)
    if type(toimport) == "string" then
        return loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/Masterzz-Developer/Plutonium/master/" .. toimport))()
    else 
        return game:GetObjects("rbxassetid://" .. toimport)[1]
    end
end

local gamessupported = game.workspace.Name
if gamessupported == 'BloxHuntnamehere' then
    import("BloxHunt.lua")
end
```
# First Time
If it is your first time please use 
```lua
_G.FirstTime = true
```
and if it is not your first time please use
```lua
_G.FirstTime = false
```
