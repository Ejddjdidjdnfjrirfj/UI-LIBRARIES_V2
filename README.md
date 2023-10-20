Library = {}

function Library.CreateLib(Title)
    local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Frame2 = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local UIListLayout = Instance.new("UIListLayout")
local Lable = Instance.new("TextLabel")

ScreenGui.Parent = game.CoreGui

Frame.Name = "Frame"
Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.Position = UDim2.new(0,267,0,65)
Frame.Size = UDim2.new(0,589,0,486)
Frame.BackgroundTransparency = 0.35

UICorner.Parent = Frame

Frame2.Name = "Frame"
Frame2.Parent = Frame
Frame2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame2.Position = UDim2.new(0, 0, 0, 0)
Frame2.Size = UDim2.new(1, 0, 0, 42)
Frame2.BackgroundTransparency = 0.35

UICorner_2.Parent = Frame2

UIListLayout.Parent = Frame2

Label.Name = "TextLabel"
Label.Parent = Frame2
Label.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Label.Position = UDim2.new(0, 0, 0,   0)
Label.Size = UDim2.new(0, 0, 1, 0)
Label.BackgroundTransparency = 1
Lable.Text = Title


end
