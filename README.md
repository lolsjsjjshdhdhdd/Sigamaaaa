local Library = loadstring(Game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wizard"))()
 
local popittWindow = Library:NewWindow("Pop it")
 
local popitcheats = popittWindow:NewSection("Main")
 
popitcheats:CreateButton("grab all", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Nadiehp/UI-/refs/heads/main/Collect All ¿(Scam)%3F"))()
end)

popitcheats:CreateButton("Xray", function()
game.Players.LocalPlayer.XRay.Value=true
end)

local tpcheats = popittWindow:NewSection("tp")

tpcheats:CreateButton("spawn", function()
local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
local location = CFrame.new(69, 18, -266)
local humanoid = game.Players.LocalPlayer.Character.Humanoid
humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
wait(0.1)
pl.CFrame = location
end)

tpcheats:CreateButton("glass trade", function()
local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
local location = CFrame.new(140, 20, 210)
local humanoid = game.Players.LocalPlayer.Character.Humanoid
humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
wait(0.1)
pl.CFrame = location
end)

popitcheats:CreateButton("FAKE JUMP", function()
local humanoid = game.Players.LocalPlayer.Character.Humanoid
humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
wait(0.1)
end)

local  Buycheats = popittWindow:NewSection("Buy stuff")

Buycheats:CreateButton("Dart", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Nadiehp/Pop-it-trading-buy/main/Buy%20Dart"))()
end)

Buycheats:CreateButton("Demorgan", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Nadiehp/Buy-Demorgan/refs/heads/main/Buy-Demorgan"))()()
end)

Buycheats:CreateButton("F", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Nadiehp/Buy-F/main/Buy-F"))()
end)

Buycheats:CreateButton("Retro bike", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Nadiehp/Retro-Bike/refs/heads/main/Retro-Bike"))()
end)

Buycheats:CreateButton("Squid", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Nadiehp/Buy-Squid/main/Buy-Squid"))()
end)

Buycheats:CreateButton("Box Harambe", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Nadiehp/Box-Toy-Harambe/refs/heads/main/Box-Toy-Harambe"))()()
end)

Buycheats:CreateButton("Rainbow hand", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Nadiehp/Buy-hand-rainbow/refs/heads/main/Hand%20rainbow"))()()
end)

Buycheats:CreateButton("Rainbow star", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Nadiehp/Rainbow-Star/refs/heads/main/Rainbow%20Star"))()()
end)

Buycheats:CreateButton("Rainbow flower", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Nadiehp/Buy-Flower-Rainbow/main/Buy-Flower-Rainbow"))()
end)

local Misccheats = popittWindow:NewSection("Misc")

Misccheats:CreateButton("anti afk", function()
loadstring(game:HttpGet("https://pastebin.com/raw/rs8GM0HT"))()
end)
