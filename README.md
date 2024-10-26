local walkspeed = 20
local jumppower = 50
local health = 100

local player = game.Players.LocalPlayer
local character = player.Character:WaitForChild("Humanoid")
character.WalkSpeed = walkspeed
character.UseJumpPower = true
character.JumpPower = jumppower
character.MaxHealth = health
player.Character:WaitForChild("Humanoid").Health = character.MaxHealth
