local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Player = game.Players.LocalPlayer
local Window = OrionLib:MakeWindow({Name = "Key system", HidePremium = false, SaveConfig = true, IntroEnabled = false })

OrionLib:MakeNotification({
	Name = "Login!",
	Content = "you are logged in as"..Player.Name..".",
	Image = "rbxassetid://4483345998",
	Time = 5
})

_G.Key = "T00ls6 HUB paid Ufldyteqd"
_G.KeyInput = "string"

function MakeScriptHub()
    local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("T00ls6 HUB PAID VERSION", "Sentinel")

--MAIN
local Main = Window:NewTab("Main")
local LockAimSection = Main:NewSection("LockAim")


LockAimSection:NewButton("Lock aim", "Avoir le lock aim", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/YoyoSoloExe/AIM-LOCK/main/aim%20lock'))()
end)

LockAimSection:NewToggle("Super-Humain", "Go fast and jump high", function(state)
    if state then
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 200
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 120
    else
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 50
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
    end
end)

LockAimSection:NewButton("Infinit yield", "Avoir les command admin", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)


--ESP
local ESP = Window:NewTab("ESP")
local ESPSection = ESP:NewSection("ESP")

ESPSection:NewButton("ESP", "Avoir le esp", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/YoyoSoloExe/UNHAMED-ESP/main/ESP'))()
end)

--LOCAL PLAYER
local Player = Window:NewTab("Player")
local PlayerSection = Player:NewSection("Player")

PlayerSection:NewSlider("WalkSpeed", "Courir plus vite !!", 500, 16, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

PlayerSection:NewSlider("Super Saut", "Sauter plus haut", 1000, 50, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
end)

PlayerSection:NewButton("Reset WS/JP", "Reset WS/JP", function()
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
end)

--All Games
local AllGames = Window:NewTab("All games")
local AllGamesSection = AllGames:NewSection("All games script")

AllGamesSection:NewButton("Brookhaven rp", "Avoir le script brookhaven", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/IceMael7/NewIceHub/main/Brookhaven'))()
end)

AllGamesSection:NewButton("Blox Fruit", "Avoir le script Blox fruit", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ThunderZ-HUB/HUB/main/Script"))() 
end)

AllGamesSection:NewButton("murder mystery 2", "Avoir le script mm2", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/VEZ2/NEVAHUB/main/2'))()
end)

--invisible
local invisible = Window:NewTab("Invisible")
local invisibleSection = invisible:NewSection("invisible script")

invisibleSection:NewButton("invisible", "etre invisible", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/kLF5E3tf'))() 
end)


--Btool
local Btool = Window:NewTab("Btool")
local BtoolSection = Btool:NewSection("Btool")

BtoolSection:NewButton("Btool", "avoir Btool", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/FBKJTUyw'))()
end)

--fly
local Fly = Window:NewTab("Fly")
local FlySection = Fly:NewSection("Fly")

FlySection:NewButton("Fly (X)", "pouvoir voler", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/fPtT2Q1F'))()
end)

--CONCTACT
local CONCTACT = Window:NewTab("CONCTACT")
local CONCTACTSection = CONCTACT:NewSection("CONCTACT")

CONCTACTSection:NewLabel("T00ls6")
end

function CorrectKeyNotification()
    OrionLib:MakeNotification({
        Name = "Correct Key",
        Content = "Vous avez saisi la bonne clé",
        Image = "rbxassetid://4483345998",
        Time = 5
    })
end

function IncorrectKeyNotification()
    OrionLib:MakeNotification({
        Name = "Incorrect Key",
        Content = "Vous avez saisi la mauvaise clé",
        Image = "rbxassetid://4483345998",
        Time = 5
    })
end

local Tab = Window:MakeTab({
	Name = "Key",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddTextbox({
	Name = "Enter Key: ",
	Default = "Enter key: ",
	TextDisappear = true,
	Callback = function(Value)
		_G.KeyInput = Value
        
	end	  
})

Tab:AddButton({
	Name = "Check Key!",
	Callback = function()
      		if _G.KeyInput == _G.Key then
            MakeScriptHub()
            CorrectKeyNotification()
            else
                IncorrectKeyNotification()
            end
  	end    
})

Tab:AddButton({
	Name = "Get key",
	Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/YoyoSoloExe/Get-key-bypass/main/dont%20opened'))()
  	end    
})
