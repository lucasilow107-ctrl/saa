-- Tạo một ScreenGui
local screenGui = Instance.new("ScreenGui")
screenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

-- Tạo một Frame
local frame = Instance.new("Frame")
frame.Size = UDim2.new(0, 200, 0, 100)
frame.Position = UDim2.new(0.5, -100, 0.5, -50)
frame.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
frame.Parent = screenGui

-- Tạo một TextLabel
local label = Instance.new("TextLabel")
label.Size = UDim2.new(1, 0, 1, 0)
label.Text = "Xin chào Roblox!"
label.Parent = frame
