-- Nhat Anh Script

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local label = Instance.new("TextLabel")
local SpeedButton = Instance.new("TextButton")
local AmateurHUB = Instance.new("TextButton")
local VEPSCRIPT = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui

Main.Name = "Main"
Main.Parent = ScreenGui
Main.BackgroundColor3 = Color3.fromRGB(9, 9, 9)
Main.Position = UDim2.new(0.492082834, 0, 0.243816242, 0)
Main.Size = UDim2.new(0, 403, 0, 211)
main.Active = true
main.Draggable = true

label.Name = "label"
label.Parent = Main
label.BackgroundColor3 = Color3.fromRGB(255, 85, 0)
label.Size = UDim2.new(0, 403, 0, 35)
label.Font = Enum.Font.SourceSans
label.Text = "NAHub | Made By NhatAnh (Orb#5041)"
label.TextColor3 = Color3.fromRGB(16, 32, 255)
label.TextSize = 34.000
label.TextWrapped = true

SpeedButton.Name = "SpeedButton"
SpeedButton.Parent = Main
SpeedButton.BackgroundColor3 = Color3.fromRGB(255, 255, 0)
SpeedButton.Position = UDim2.new(0, 0, 0.271728158, 0)
SpeedButton.Size = UDim2.new(0, 134, 0, 32)
SpeedButton.Font = Enum.Font.SourceSans
SpeedButton.Text = "Speed"
SpeedButton.TextColor3 = Color3.fromRGB(0, 0, 0)
SpeedButton.TextSize = 14.000
SpeedButton.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/pq80JhpJ"))()
end)

AmateurHUB.Name = "AmateurHUB"
AmateurHUB.Parent = Main
AmateurHUB.BackgroundColor3 = Color3.fromRGB(255, 85, 0)
AmateurHUB.Position = UDim2.new(0.66749382, 0, 0.366514891, 0)
AmateurHUB.Size = UDim2.new(0, 134, 0, 32)
AmateurHUB.Font = Enum.Font.SourceSans
AmateurHUB.Text = "AmateurHub"
AmateurHUB.TextColor3 = Color3.fromRGB(0, 0, 0)
AmateurHUB.TextSize = 14.000
AmateurHUB.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/JOSHYEXPLOITS/AmateurHub/main/Amateur%20Hub"))()
end)

VEPSCRIPT.Name = "VEPSCRIPT"
VEPSCRIPT.Parent = Main
VEPSCRIPT.BackgroundColor3 = Color3.fromRGB(255, 85, 0)
VEPSCRIPT.BorderColor3 = Color3.fromRGB(255, 85, 0)
VEPSCRIPT.Position = UDim2.new(0.66749382, 0, 0.60189569, 0)
VEPSCRIPT.Size = UDim2.new(0, 134, 0, 32)
VEPSCRIPT.Font = Enum.Font.SourceSans
VEPSCRIPT.Text = "Vep"
VEPSCRIPT.TextColor3 = Color3.fromRGB(0, 0, 0)
VEPSCRIPT.TextSize = 14.000
VEPSCRIPT.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/vep1032/VepStuff/main/Demon%20Fall%20TOMAN"))()
end)