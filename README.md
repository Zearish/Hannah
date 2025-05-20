<div align=center>
  <img src="https://raw.githubusercontent.com/Zearish/Hannah/refs/heads/main/PinkHannahIcon.png" width="400" />
  <h1>Uopgrade your script using Hannah!</h1>
</div>
<h2>Using Hannah Library in your code</h2>
<pre><code>
if game:GetService("CoreGui").HannahUI ~= nil then
        game:GetService("CoreGui").HannahUI:Destroy()
end

local HannahUI = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Frame_2 = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Frame_3 = Instance.new("Frame")
local Frame_4 = Instance.new("Frame")
local Frame_5 = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local Frame_6 = Instance.new("Frame")
local ImageLabel = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")
local HannahT = Instance.new("Frame")
local ScrollingFrame = Instance.new("ScrollingFrame")
local UIListLayout = Instance.new("UIListLayout")
local Button = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local Toggle = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local ToggleName = Instance.new("TextLabel")


HannahUI.Name = "HannahUI"
HannahUI.Parent = game.CoreGui
HannahUI.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = HannahUI
Frame.Active = true
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BackgroundTransparency = 1.000
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.371761739, -53, 0.341220856, 5)
Frame.Size = UDim2.new(0, 500, 0, 37)
Frame.Draggable = true

game.UserInputService.InputBegan:Connect(function(key, ...)
        if key.KeyCode == Enum.KeyCode.F then
                if game:GetService("CoreGui"):FindFirstChild("Chat") == nil then
                        if Frame.Visible then
                                Frame.Visible = false
                        else
                                Frame.Visible = true
                        end
                end
        end
end)

Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.fromRGB(162, 95, 95)
Frame_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(-0.00137335213, 0, -0.329879016, 0)
Frame_2.Size = UDim2.new(0, 499, 0, 26)

UICorner.Parent = Frame_2

Frame_3.Parent = Frame
Frame_3.BackgroundColor3 = Color3.fromRGB(162, 95, 95)
Frame_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_3.BorderSizePixel = 0
Frame_3.Position = UDim2.new(-0.00137335213, 0, 0.157925859, 0)
Frame_3.Size = UDim2.new(0, 499, 0, 32)

Frame_4.Parent = Frame
Frame_4.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
Frame_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_4.BorderSizePixel = 0
Frame_4.Position = UDim2.new(-0.00137335213, 0, 0.938414037, 0)
Frame_4.Size = UDim2.new(0, 499, 0, 209)

Frame_5.Parent = Frame
Frame_5.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
Frame_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_5.BorderSizePixel = 0
Frame_5.Position = UDim2.new(-0.00137335213, 0, 5.57256031, 0)
Frame_5.Size = UDim2.new(0, 499, 0, 47)

UICorner_2.Parent = Frame_5

Frame_6.Parent = Frame
Frame_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_6.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_6.BorderSizePixel = 0
Frame_6.Position = UDim2.new(-0.00137335213, 0, 0.938414037, 0)
Frame_6.Size = UDim2.new(0, 499, 0, -2)

ImageLabel.Parent = Frame
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(0.0180360731, 0, -0.167715535, 0)
ImageLabel.Size = UDim2.new(0, 38, 0, 38)
ImageLabel.Image = "rbxassetid://75050288385119"

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.0941883773, 0, -0.189189196, 0)
TextLabel.Size = UDim2.new(0, 188, 0, 31)
TextLabel.Font = Enum.Font.TitilliumWeb
TextLabel.Text = "Hannah"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextWrapped = true
TextLabel.TextXAlignment = Enum.TextXAlignment.Left

HannahT.Name = "HannahT"
HannahT.Parent = Frame
HannahT.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
HannahT.BackgroundTransparency = 1.000
HannahT.BorderColor3 = Color3.fromRGB(0, 0, 0)
HannahT.BorderSizePixel = 0
HannahT.Position = UDim2.new(-0.00200400804, 0, 0.864864886, 0)
HannahT.Size = UDim2.new(0, 499, 0, 221)

ScrollingFrame.Parent = HannahT
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScrollingFrame.BackgroundTransparency = 1.000
ScrollingFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScrollingFrame.BorderSizePixel = 0
ScrollingFrame.Position = UDim2.new(0.0360721461, 0, 0.0937616006, 0)
ScrollingFrame.Size = UDim2.new(0, 460, 0, 185)
ScrollingFrame.BottomImage = ""
ScrollingFrame.MidImage = ""
ScrollingFrame.TopImage = ""

UIListLayout.Parent = ScrollingFrame
UIListLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIListLayout.Padding = UDim.new(0, 15)

local function button(name, func)
    local button = Instance.new("TextButton")
    button.Name = name
    button.Parent = ScrollingFrame
    button.BackgroundColor3 = Color3.fromRGB(199, 101, 102)
    button.Size = UDim2.new(0, 414, 0, 42)
    button.Font = Enum.Font.TitilliumWeb
    button.Text = name
    button.TextColor3 = Color3.fromRGB(255, 255, 255)
    button.TextScaled = true

    local UICorner_4_New = Instance.new("UICorner")
    UICorner_4_New.CornerRadius = UDim.new(0, 5)
    UICorner_4_New.Parent = button

    button.MouseButton1Click:Connect(function()
        func()
    end)
end

local function toggle(name, func)
    local toggle = Instance.new("TextButton")
    toggle.Name = name
    toggle.Parent = ScrollingFrame
    toggle.BackgroundColor3 = Color3.fromRGB(85, 49, 50)
    toggle.Size = UDim2.new(0, 52, 0, 50)
    toggle.AutoButtonColor = false
    toggle.Font = Enum.Font.SourceSans
    toggle.Text = ""
    toggle.TextColor3 = Color3.fromRGB(0, 0, 0)

    local UICorner_5_New = Instance.new("UICorner")
    UICorner_5_New.CornerRadius = UDim.new(0, 5)
    UICorner_5_New.Parent = toggle

    local ToggleName = Instance.new("TextLabel")
    ToggleName.TextXAlignment = Enum.TextXAlignment.Left
    ToggleName.Name = "ToggleName"
    ToggleName.Parent = toggle
    ToggleName.BackgroundTransparency = 1.000
    ToggleName.Size = UDim2.new(0, 343, 0, 50)
    ToggleName.Font = Enum.Font.TitilliumWeb
    ToggleName.Text = name
    ToggleName.TextColor3 = Color3.fromRGB(255, 255, 255)
    ToggleName.TextScaled = true
    ToggleName.Position = UDim2.new(0, 60, 0, 0)

    local toggled = false
    toggle.MouseButton1Click:Connect(function()
        toggled = not toggled
        toggle.BackgroundColor3 = toggled and Color3.fromRGB(255, 180, 181) or Color3.fromRGB(85, 49, 50)
        func(toggled)
    end)
end
</code></pre>
<div align=center>
  <h1>Creating Elements</h2>
</div>
<h2>Creating toggles</h2>
<code><pre>
  toggle("Toggle", function(callback)
    if callback then
        print("Toggle on")
    else
        print("Toggle off")
    end
end)
</pre></code>
<h2>Creating buttons</h2>
<pre><code>
  button("Button", function()
    print("Button clicked")
end)
</code></pre>
