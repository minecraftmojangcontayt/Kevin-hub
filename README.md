local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "Kevin Hub",
   Icon = 0, -- Icon in Topbar. Can use Lucide Icons (string) or Roblox Image (number). 0 to use no icon (default).
   LoadingTitle = "Kevin Hub",
   LoadingSubtitle = "Showcase",
   Theme = "Default", -- Check https://docs.sirius.menu/rayfield/configuration/themes

   DisableRayfieldPrompts = false,
   DisableBuildWarnings = false, -- Prevents Rayfield from warning when the script has a version mismatch with the interface

   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Big Hub"
   },

   Discord = {
      Enabled = false, -- Prompt the user to join your Discord server if their executor supports it
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },

   KeySystem = false -- Sistema de key desativado; bloco KeySettings removido
})

local Tab = Window:CreateTab("Blox Fruits", 4483362458) -- Title, Image

local Section = Tab:CreateSection("Blox Fruits")

local Button = Tab:CreateButton({
   Name = "QuantumOnyx Hub",
   Callback = function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/flazhy/QuantumOnyx/refs/heads/main/QuantumOnyx.lua"))()

   end,
})

local Button = Tab:CreateButton({
   Name = "Redz Hub",
   Callback = function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/huy384/redzHub/refs/heads/main/redz⁶Hub.lua"))()

   end,
})

local Button = Tab:CreateButton({
   Name = "8x Luck Buffer",
   Callback = function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/Ytzeno99/bufflucky/refs/heads/main/LucKyRadomFruit.lua"))()

   end,
})

local Button = Tab:CreateButton({
   Name = "Teddy Hub",
   Callback = function()
 
loadstring(game:HttpGet("https://raw.githubusercontent.com/Teddyseetink/Haidepzai/refs/heads/main/TeddyHub.lua"))()

   end,
})

local Button = Tab:CreateButton({
   Name = "Zyre Hub",
   Callback = function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/GoblinKun009/Script/refs/heads/main/ZyreHub", true))()

   end,
})

local Button = Tab:CreateButton({
   Name = "Xeter Hub V4",
   Callback = function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/TlDinhKhoi/Xeter/refs/heads/main/Main.lua"))()

   end,
})

local Button = Tab:CreateButton({
   Name = "Blue x Hub",
   Callback = function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/Dev-BlueX/BlueX-Hub/refs/heads/main/Main.lua"))()

   end,
})

local Button = Tab:CreateButton({
   Name = "Tdt Hub",
   Callback = function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/ThinhNek343/tdthub/refs/heads/main/maintdt.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Hoho Hub",
   Callback = function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI"))()

   end,
})

local Button = Tab:CreateButton({
   Name = "Zee Hub VIP",
   Callback = function()
 loadstring(game:HttpGet("https://link.trwxz.com/LS-Zee-Hub-VIP"))()
   end,
})

local Tab = Window:CreateTab("The Forge", 4483362458) -- Title, Image

local Section = Tab:CreateSection("The forge")

local Button = Tab:CreateButton({
   Name = "Ajjan Hub",
   Callback = function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/onliengamerop/Roblox-scripthsiaoioaka/refs/heads/main/Ajjans%20forge%20script"))()

   end,
})

local Button = Tab:CreateButton({
   Name = "Lunor Hub",
   Callback = function()
 loadstring(game:HttpGet("https://lunor.dev/loader"))()

   end,
})

local Button = Tab:CreateButton({
   Name = "VoidWorld Hub",
   Callback = function()
 loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/280c3c5ae0ed18010fea0d86c424fdb5.lua"))()

   end,
})

local Button = Tab:CreateButton({
   Name = "Lunaris X Hub",
   Callback = function()
 loadstring(game:HttpGet("https://api.junkie-development.de/api/v1/luascripts/public/4bb9adb87bb661b1352d17bed46bae126c1fb4977d40806d88c586804d857515/download"))()

   end,
})

local Button = Tab:CreateButton({
   Name = "Alchemy Hub",
   Callback = function()
 loadstring(game:HttpGet("https://scripts.alchemyhub.xyz"))()

   end,
})

local Button = Tab:CreateButton({
   Name = "Vex Hub",
   Callback = function()
 loadstring(game:HttpGet("https://ry-zen.studio/raw/VexHub/Hub.lua?key=U2VjdXJlQXV0aEtleQ"))()

   end,
})

local Button = Tab:CreateButton({
   Name = "Speed Hub X",
   Callback = function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua", true))()

   end,
})

local Button = Tab:CreateButton({
   Name = "Chiyo Hub",
   Callback = function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/kaisenlmao/loader/refs/heads/main/chiyo.lua"))()

   end,
})

local Button = Tab:CreateButton({
   Name = "Nics Hub",
   Callback = function()
 loadstring(game:HttpGet("https://api.junkie-development.de/api/v1/luascripts/public/4a149ec7015ec262afc48f0cb6e88f6fd242b9fcccc21c7747f6385888a9ebac/download"))()

   end,
})

local Button = Tab:CreateButton({
   Name = "Rift Hub",
   Callback = function()
 loadstring(game:HttpGet("https://rifton.top/loader.lua"))()

   end,
})

local Tab = Window:CreateTab("99 Nights In The Florest", 4483362458) -- Title, Image

local Section = Tab:CreateSection("99 Nights In The Florest")

local Button = Tab:CreateButton({
   Name = "Voidware Hub",
   Callback = function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/VapeVoidware/VWExtra/main/NightsInTheForest.lua", true))()

   end,
})

local Button = Tab:CreateButton({
   Name = "Vector Hub",
   Callback = function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/AAwful/Vector_Hub/0/v2"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Foxname Diamond Hub",
   Callback = function()
 loadstring(game:HttpGet('https://raw.githubusercontent.com/caomod2077/Script/refs/heads/main/FNDayFarm.lua'))()

   end,
})

local Button = Tab:CreateButton({
   Name = "Lunor Hub",
   Callback = function()
 loadstring(game:HttpGet('https://lunor.dev/loader'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Kenniel Hub",
   Callback = function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/Kenniel123/99-Nights-in-the-Forest/refs/heads/main/99%20Nights%20in%20the%20Forest"))()

   end,
})

local Tab = Window:CreateTab("Dandy's world", 4483362458) -- Title, Image

local Section = Tab:CreateSection("Dandy's world")

local Button = Tab:CreateButton({
   Name = "Noxious Hub",
   Callback = function()
 loadstring(game:HttpGet("https://rawscripts.net/raw/Dandy's-World-ALPHA-DW-Noxious-Hub-l-Not-Mine-39261"))()

   end,
})

local Button = Tab:CreateButton({
   Name = "Riddance Hub",
   Callback = function()
 
loadstring(game:HttpGet("https://raw.githubusercontent.com/riddance-club/script/refs/heads/main/loader.lua"))()

   end,
})
Rayfield:LoadConfiguration()
