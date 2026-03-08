# DogApple-- UI LIBRARY
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wall%20v3"))()

local Window = Library:CreateWindow("Apple Dog Hub 🍎🐶 | Blox Fruits")

-- MAIN
local Main = Window:CreateTab("Main")

Main:CreateButton("Speed Boost", function()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 80
end)

Main:CreateButton("High Jump", function()
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = 120
end)

Main:CreateButton("Reset Player", function()
    game.Players.LocalPlayer.Character.Humanoid.Health = 0
end)

-- FARM
local Farm = Window:CreateTab("Auto Farm")

Farm:CreateButton("Auto Farm Level", function()
    print("Auto Farm Level iniciado")
end)

Farm:CreateButton("Auto Quest", function()
    print("Auto Quest iniciado")
end)

Farm:CreateButton("Auto Boss", function()
    print("Auto Boss iniciado")
end)

Farm:CreateButton("Fast Attack", function()
    print("Fast Attack ativado")
end)

-- RACE
local Race = Window:CreateTab("Race")

Race:CreateButton("Auto Trial", function()
    print("Auto Trial iniciado")
end)

Race:CreateButton("Auto Gear", function()
    print("Pegando engrenagem")
end)

Race:CreateButton("Auto Race V2", function()
    print("Race V2")
end)

Race:CreateButton("Auto Race V3", function()
    print("Race V3")
end)

-- SEA EVENTS
local Sea = Window:CreateTab("Sea Events")

Sea:CreateButton("Auto Leviathan", function()
    print("Procurando Leviathan")
end)

Sea:CreateButton("Auto Sea Beast", function()
    print("Caçando Sea Beast")
end)

Sea:CreateButton("Auto Rumbling Waters", function()
    print("Evento Rumbling Waters")
end)

Sea:CreateButton("Auto Ship Raid", function()
    print("Ship Raid iniciado")
end)

Sea:CreateButton("Auto Terror Shark", function()
    print("Terror Shark detectado")
end)

Sea:CreateButton("Auto Piranha", function()
    print("Piranhas detectadas")
end)

-- FRUITS
local Fruits = Window:CreateTab("Fruits")

Fruits:CreateButton("ESP Fruits", function()
    print("ESP Fruits ativado")
end)

Fruits:CreateButton("Auto Store Fruits", function()
    print("Guardando frutas")
end)

Fruits:CreateButton("Fruit Sniper", function()
    print("Detectando frutas")
end)

-- PLAYER
local Player = Window:CreateTab("Player")

Player:CreateButton("Fly", function()
    print("Fly ativado")
end)

Player:CreateButton("No Clip", function()
    print("No Clip ativado")
end)

Player:CreateButton("Infinite Energy", function()
    print("Energia infinita")
end)

-- TELEPORT
local Teleport = Window:CreateTab("Teleport")

Teleport:CreateButton("Teleport Jungle", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1600,36,150)
end)

Teleport:CreateButton("Teleport Desert", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(900,50,4300)
end)

-- MISC
local Misc = Window:CreateTab("Misc")

Misc:CreateButton("Server Hop", function()
    print("Mudando de servidor")
end)

Misc:CreateButton("Rejoin Server", function()
    game:GetService("TeleportService"):Teleport(game.PlaceId, game.Players.LocalPlayer)
end)
