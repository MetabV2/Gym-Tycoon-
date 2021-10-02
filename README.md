
local InsertedObjects = Instance.new("ScreenGui")
local ImageLabel = Instance.new("ImageLabel")
local ScrollingFrame = Instance.new("ScrollingFrame")
local Button3 = Instance.new("ImageButton")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
local BtnText = Instance.new("TextLabel")
local UIGradient = Instance.new("UIGradient")
local Button3_2 = Instance.new("ImageButton")
local UIAspectRatioConstraint_2 = Instance.new("UIAspectRatioConstraint")
local BtnText_2 = Instance.new("TextLabel")
local UIGradient_2 = Instance.new("UIGradient")
local Button3_3 = Instance.new("ImageButton")
local UIAspectRatioConstraint_3 = Instance.new("UIAspectRatioConstraint")
local BtnText_3 = Instance.new("TextLabel")
local UIGradient_3 = Instance.new("UIGradient")
local Button3_4 = Instance.new("ImageButton")
local UIAspectRatioConstraint_4 = Instance.new("UIAspectRatioConstraint")
local BtnText_4 = Instance.new("TextLabel")
local UIGradient_4 = Instance.new("UIGradient")
local Button3_5 = Instance.new("ImageButton")
local UIAspectRatioConstraint_5 = Instance.new("UIAspectRatioConstraint")
local BtnText_5 = Instance.new("TextLabel")
local UIGradient_5 = Instance.new("UIGradient")
local CloseButton = Instance.new("ImageButton")
local UIGradient_6 = Instance.new("UIGradient")
local UIAspectRatioConstraint_6 = Instance.new("UIAspectRatioConstraint")
local ImageButton = Instance.new("ImageButton")

--Properties:

InsertedObjects.Name = "InsertedObjects"
InsertedObjects.Parent = game.CoreGui
InsertedObjects.ResetOnSpawn = false

ImageLabel.Parent = InsertedObjects
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.Position = UDim2.new(0.0394712277, 0, 0.104501605, 0)
ImageLabel.Size = UDim2.new(0, 755, 0, 492)
ImageLabel.Image = "http://www.roblox.com/asset/?id=7402946493"

ScrollingFrame.Parent = ImageLabel
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScrollingFrame.BackgroundTransparency = 1.000
ScrollingFrame.BorderSizePixel = 0
ScrollingFrame.Position = UDim2.new(0.36953643, 0, 0.380081296, 0)
ScrollingFrame.Size = UDim2.new(0, 195, 0, 243)
ScrollingFrame.CanvasPosition = Vector2.new(0, 150)

Button3.Name = "Button 3"
Button3.Parent = ScrollingFrame
Button3.AnchorPoint = Vector2.new(1, 1)
Button3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button3.BackgroundTransparency = 1.000
Button3.Position = UDim2.new(0.945403278, 0, 0.0651222095, 0)
Button3.Size = UDim2.new(0.882225692, 0, 0.0763209537, 0)
Button3.Image = "rbxassetid://2790382281"
Button3.ImageColor3 = Color3.fromRGB(26, 190, 190)
Button3.ScaleType = Enum.ScaleType.Slice
Button3.SliceCenter = Rect.new(4, 4, 252, 252)

UIAspectRatioConstraint.Parent = Button3
UIAspectRatioConstraint.AspectRatio = 3.042

BtnText.Name = "BtnText"
BtnText.Parent = Button3
BtnText.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText.BackgroundTransparency = 1.000
BtnText.BorderSizePixel = 0
BtnText.Position = UDim2.new(0.498592883, 0, 0.488144726, 0)
BtnText.Size = UDim2.new(0.891457498, -5, 0.468874484, -5)
BtnText.Font = Enum.Font.GothamBlack
BtnText.Text = "AUTO NPC CHECKER"
BtnText.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText.TextScaled = true
BtnText.TextSize = 14.000
BtnText.TextWrapped = true

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(0.98, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient.Offset = Vector2.new(-0.349999994, 0)
UIGradient.Rotation = -135
UIGradient.Parent = Button3

Button3_2.Name = "Button 3"
Button3_2.Parent = ScrollingFrame
Button3_2.AnchorPoint = Vector2.new(1, 1)
Button3_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button3_2.BackgroundTransparency = 1.000
Button3_2.Position = UDim2.new(0.945403278, 0, 0.129146606, 0)
Button3_2.Size = UDim2.new(0.882225692, 0, 0.0763209537, 0)
Button3_2.Image = "rbxassetid://2790382281"
Button3_2.ImageColor3 = Color3.fromRGB(26, 190, 190)
Button3_2.ScaleType = Enum.ScaleType.Slice
Button3_2.SliceCenter = Rect.new(4, 4, 252, 252)

UIAspectRatioConstraint_2.Parent = Button3_2
UIAspectRatioConstraint_2.AspectRatio = 3.042

BtnText_2.Name = "BtnText"
BtnText_2.Parent = Button3_2
BtnText_2.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_2.BackgroundTransparency = 1.000
BtnText_2.BorderSizePixel = 0
BtnText_2.Position = UDim2.new(0.498592883, 0, 0.488144726, 0)
BtnText_2.Size = UDim2.new(0.891457498, -5, 0.468874484, -5)
BtnText_2.Font = Enum.Font.GothamBlack
BtnText_2.Text = "AUTO COLLECT CASH"
BtnText_2.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_2.TextScaled = true
BtnText_2.TextSize = 14.000
BtnText_2.TextWrapped = true

UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(0.98, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient_2.Offset = Vector2.new(-0.349999994, 0)
UIGradient_2.Rotation = -135
UIGradient_2.Parent = Button3_2

Button3_3.Name = "Button 3"
Button3_3.Parent = ScrollingFrame
Button3_3.AnchorPoint = Vector2.new(1, 1)
Button3_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button3_3.BackgroundTransparency = 1.000
Button3_3.Position = UDim2.new(0.940275073, 0, 0.193170995, 0)
Button3_3.Size = UDim2.new(0.882225692, 0, 0.0763209537, 0)
Button3_3.Image = "rbxassetid://2790382281"
Button3_3.ImageColor3 = Color3.fromRGB(26, 190, 190)
Button3_3.ScaleType = Enum.ScaleType.Slice
Button3_3.SliceCenter = Rect.new(4, 4, 252, 252)

UIAspectRatioConstraint_3.Parent = Button3_3
UIAspectRatioConstraint_3.AspectRatio = 3.042

BtnText_3.Name = "BtnText"
BtnText_3.Parent = Button3_3
BtnText_3.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_3.BackgroundTransparency = 1.000
BtnText_3.BorderSizePixel = 0
BtnText_3.Position = UDim2.new(0.498592883, 0, 0.488144726, 0)
BtnText_3.Size = UDim2.new(0.891457498, -5, 0.468874484, -5)
BtnText_3.Font = Enum.Font.GothamBlack
BtnText_3.Text = "AUTO SPAWN BULK"
BtnText_3.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_3.TextScaled = true
BtnText_3.TextSize = 14.000
BtnText_3.TextWrapped = true

UIGradient_3.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(0.98, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient_3.Offset = Vector2.new(-0.349999994, 0)
UIGradient_3.Rotation = -135
UIGradient_3.Parent = Button3_3

Button3_4.Name = "Button 3"
Button3_4.Parent = ScrollingFrame
Button3_4.AnchorPoint = Vector2.new(1, 1)
Button3_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button3_4.BackgroundTransparency = 1.000
Button3_4.Position = UDim2.new(0.935146868, 0, 0.321219772, 0)
Button3_4.Size = UDim2.new(0.882225692, 0, 0.0763209537, 0)
Button3_4.Image = "rbxassetid://2790382281"
Button3_4.ImageColor3 = Color3.fromRGB(26, 190, 190)
Button3_4.ScaleType = Enum.ScaleType.Slice
Button3_4.SliceCenter = Rect.new(4, 4, 252, 252)

UIAspectRatioConstraint_4.Parent = Button3_4
UIAspectRatioConstraint_4.AspectRatio = 3.042

BtnText_4.Name = "BtnText"
BtnText_4.Parent = Button3_4
BtnText_4.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_4.BackgroundTransparency = 1.000
BtnText_4.BorderSizePixel = 0
BtnText_4.Position = UDim2.new(0.510218441, 0, 0.489505291, 0)
BtnText_4.Size = UDim2.new(0.810078204, -5, 0.678369999, -5)
BtnText_4.Font = Enum.Font.GothamBlack
BtnText_4.Text = "INFINITE MONEY "
BtnText_4.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_4.TextScaled = true
BtnText_4.TextSize = 14.000
BtnText_4.TextWrapped = true

UIGradient_4.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(0.98, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient_4.Offset = Vector2.new(-0.349999994, 0)
UIGradient_4.Rotation = -135
UIGradient_4.Parent = Button3_4

Button3_5.Name = "Button 3"
Button3_5.Parent = ScrollingFrame
Button3_5.AnchorPoint = Vector2.new(1, 1)
Button3_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button3_5.BackgroundTransparency = 1.000
Button3_5.Position = UDim2.new(0.940275073, 0, 0.257195383, 0)
Button3_5.Size = UDim2.new(0.882225692, 0, 0.0763209537, 0)
Button3_5.Image = "rbxassetid://2790382281"
Button3_5.ImageColor3 = Color3.fromRGB(26, 190, 190)
Button3_5.ScaleType = Enum.ScaleType.Slice
Button3_5.SliceCenter = Rect.new(4, 4, 252, 252)

UIAspectRatioConstraint_5.Parent = Button3_5
UIAspectRatioConstraint_5.AspectRatio = 3.042

BtnText_5.Name = "BtnText"
BtnText_5.Parent = Button3_5
BtnText_5.AnchorPoint = Vector2.new(0.5, 0.5)
BtnText_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BtnText_5.BackgroundTransparency = 1.000
BtnText_5.BorderSizePixel = 0
BtnText_5.Position = UDim2.new(0.498592883, 0, 0.488144726, 0)
BtnText_5.Size = UDim2.new(0.891457498, -5, 0.468874484, -5)
BtnText_5.Font = Enum.Font.GothamBlack
BtnText_5.Text = "AUTO BUY GYM"
BtnText_5.TextColor3 = Color3.fromRGB(255, 255, 255)
BtnText_5.TextScaled = true
BtnText_5.TextSize = 14.000
BtnText_5.TextWrapped = true

UIGradient_5.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(0.98, Color3.fromRGB(19, 143, 143)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient_5.Offset = Vector2.new(-0.349999994, 0)
UIGradient_5.Rotation = -135
UIGradient_5.Parent = Button3_5

CloseButton.Name = "CloseButton"
CloseButton.Parent = ImageLabel
CloseButton.AnchorPoint = Vector2.new(0.5, 0.5)
CloseButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CloseButton.BackgroundTransparency = 1.000
CloseButton.BorderSizePixel = 0
CloseButton.Position = UDim2.new(0.628071308, 0, 0.122769609, 0)
CloseButton.Size = UDim2.new(0.0927402824, 0, 0.0778043792, 0)
CloseButton.Image = "http://www.roblox.com/asset/?id=7400386959"

UIGradient_6.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 136, 255))}
UIGradient_6.Offset = Vector2.new(-0.349999994, 0)
UIGradient_6.Rotation = -135
UIGradient_6.Parent = CloseButton

UIAspectRatioConstraint_6.Parent = CloseButton
UIAspectRatioConstraint_6.AspectRatio = 2.000

ImageButton.Parent = InsertedObjects
ImageButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageButton.BackgroundTransparency = 1.000
ImageButton.Position = UDim2.new(0.416326493, 0, 0, 0)
ImageButton.Size = UDim2.new(0, 123, 0, 60)
ImageButton.Image = "http://www.roblox.com/asset/?id=7529900564"

-- Scripts:

local function ERQEM_fake_script() -- ImageLabel.LocalScript 
	local script = Instance.new('LocalScript', ImageLabel)

	
	local UIS = game:GetService('UserInputService')
	
	local frame = script.Parent
	
	
	
	local dragToggle = nil
	
	local dragSpeed = 0.25
	
	local dragStart = nil
	
	local startPos = nil
	
	
	
	local function updateInput(input)
	
		local delta = input.Position - dragStart
	
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
	
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	
	end
	
	
	
	frame.InputBegan:Connect(function(input)
	
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
	
			dragToggle = true
	
			dragStart = input.Position
	
			startPos = frame.Position
	
			input.Changed:Connect(function()
	
				if input.UserInputState == Enum.UserInputState.End then
	
					dragToggle = false
	
				end
	
			end)
	
		end
	
	end)
	
	
	
	UIS.InputChanged:Connect(function(input)
	
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
	
			if dragToggle then
	
				updateInput(input)
	
			end
	
		end
	
	end)
	
	
	
	
end
coroutine.wrap(ERQEM_fake_script)()
local function IHXBWMW_fake_script() -- ImageLabel.LocalScript 
	local script = Instance.new('LocalScript', ImageLabel)

	while true do
		script.Parent.BackgroundColor3 = Color3.new (255, 176, 0)
		wait(.7)
		script.Parent.BackgroundColor3 = Color3.new (0, 255, 0)
		wait(.7)
		script.Parent.BackgroundColor3 = Color3.new (255, 0, 0)
		wait(.7)
		script.Parent.BackgroundColor3 = Color3.new (170, 85, 0)
		wait(.7)
		script.Parent.BackgroundColor3 = Color3.new (106, 57, 9)
		wait(.7)
		script.Parent.BackgroundColor3 = Color3.new (0, 16, 176)
		wait(.7)
	end
end
coroutine.wrap(IHXBWMW_fake_script)()
local function GAGCUS_fake_script() -- Button3.ANIME 
	local script = Instance.new('LocalScript', Button3)

	local btn = script.Parent
	local uiGradient = btn:WaitForChild("UIGradient")
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.4, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local gradientRestoreTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(-0.35, 0)})
	local gradientAddTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(1, 0)})
	
	
	btn.MouseEnter:Connect(function()
		
		isHovering = true
		
		gradientAddTween:Play()
	end)
	
	btn.MouseLeave:Connect(function()
		
		isHovering = false
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Down:Connect(function()
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Up:Connect(function()
		
		if not isHovering then
			gradientRestoreTween:Play()
		else
			gradientAddTween:Play()
		end
	end)
end
coroutine.wrap(GAGCUS_fake_script)()
local function PJIHJVA_fake_script() -- Button3.METAB SCRIPT 
	local script = Instance.new('LocalScript', Button3)

	
	script.Parent.MouseButton1Down:connect(function()
	
		while true do 
			wait(1)
			game:GetService("ReplicatedStorage").RemoteObjects.NPCCheckedIn:FireServer(game:GetService("Players").LocalPlayer,1)
		end
		end)
	
	
	
	
	
	
end
coroutine.wrap(PJIHJVA_fake_script)()
local function SQWTVLK_fake_script() -- Button3_2.ANIME 
	local script = Instance.new('LocalScript', Button3_2)

	local btn = script.Parent
	local uiGradient = btn:WaitForChild("UIGradient")
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.4, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local gradientRestoreTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(-0.35, 0)})
	local gradientAddTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(1, 0)})
	
	
	btn.MouseEnter:Connect(function()
		
		isHovering = true
		
		gradientAddTween:Play()
	end)
	
	btn.MouseLeave:Connect(function()
		
		isHovering = false
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Down:Connect(function()
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Up:Connect(function()
		
		if not isHovering then
			gradientRestoreTween:Play()
		else
			gradientAddTween:Play()
		end
	end)
end
coroutine.wrap(SQWTVLK_fake_script)()
local function NCXXY_fake_script() -- Button3_2.METAB SCRIPT 
	local script = Instance.new('LocalScript', Button3_2)

	
	script.Parent.MouseButton1Down:connect(function()
	
		while true do 
			wait()
				game:GetService("ReplicatedStorage").RemoteObjects.ClaimRushCash:FireServer()
		end
		end)
	
	
	
	
	
	
end
coroutine.wrap(NCXXY_fake_script)()
local function BJXQ_fake_script() -- Button3_3.ANIME 
	local script = Instance.new('LocalScript', Button3_3)

	local btn = script.Parent
	local uiGradient = btn:WaitForChild("UIGradient")
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.4, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local gradientRestoreTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(-0.35, 0)})
	local gradientAddTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(1, 0)})
	
	
	btn.MouseEnter:Connect(function()
		
		isHovering = true
		
		gradientAddTween:Play()
	end)
	
	btn.MouseLeave:Connect(function()
		
		isHovering = false
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Down:Connect(function()
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Up:Connect(function()
		
		if not isHovering then
			gradientRestoreTween:Play()
		else
			gradientAddTween:Play()
		end
	end)
end
coroutine.wrap(BJXQ_fake_script)()
local function JRQL_fake_script() -- Button3_3.METAB SCRIPT 
	local script = Instance.new('LocalScript', Button3_3)

	
	script.Parent.MouseButton1Down:connect(function()
	
		while true do 
			wait()
			game:GetService("ReplicatedStorage").RemoteObjects.ActiveBulkSpawner:FireServer(508184690)
		end
	end)
	
	
	
	
	
	
end
coroutine.wrap(JRQL_fake_script)()
local function JUUY_fake_script() -- Button3_4.ANIME 
	local script = Instance.new('LocalScript', Button3_4)

	local btn = script.Parent
	local uiGradient = btn:WaitForChild("UIGradient")
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.4, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local gradientRestoreTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(-0.35, 0)})
	local gradientAddTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(1, 0)})
	
	
	btn.MouseEnter:Connect(function()
		
		isHovering = true
		
		gradientAddTween:Play()
	end)
	
	btn.MouseLeave:Connect(function()
		
		isHovering = false
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Down:Connect(function()
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Up:Connect(function()
		
		if not isHovering then
			gradientRestoreTween:Play()
		else
			gradientAddTween:Play()
		end
	end)
end
coroutine.wrap(JUUY_fake_script)()
local function PHYRP_fake_script() -- Button3_4.METAB SCRIPT 
	local script = Instance.new('LocalScript', Button3_4)

	
	script.Parent.MouseButton1Down:connect(function()
	
		while wait() do
			game:GetService("ReplicatedStorage").RemoteObjects.DismissedAlphaMessage:FireServer()
		end
			end)
	
				
									
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
end
coroutine.wrap(PHYRP_fake_script)()
local function WJNHECC_fake_script() -- Button3_5.ANIME 
	local script = Instance.new('LocalScript', Button3_5)

	local btn = script.Parent
	local uiGradient = btn:WaitForChild("UIGradient")
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.4, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local gradientRestoreTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(-0.35, 0)})
	local gradientAddTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(1, 0)})
	
	
	btn.MouseEnter:Connect(function()
		
		isHovering = true
		
		gradientAddTween:Play()
	end)
	
	btn.MouseLeave:Connect(function()
		
		isHovering = false
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Down:Connect(function()
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Up:Connect(function()
		
		if not isHovering then
			gradientRestoreTween:Play()
		else
			gradientAddTween:Play()
		end
	end)
end
coroutine.wrap(WJNHECC_fake_script)()
local function VRRRBF_fake_script() -- Button3_5.METAB SCRIPT 
	local script = Instance.new('LocalScript', Button3_5)

	
	script.Parent.MouseButton1Down:connect(function()
	
		while true do
			wait()
			game:GetService("ReplicatedStorage").RemoteObjects.RequestBuildUpgrade:InvokeServer()
		end
	end)
	
	
	
	
	
	
end
coroutine.wrap(VRRRBF_fake_script)()
local function GNDEB_fake_script() -- CloseButton.LocalScript 
	local script = Instance.new('LocalScript', CloseButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(GNDEB_fake_script)()
local function RATH_fake_script() -- CloseButton.ANIME 
	local script = Instance.new('LocalScript', CloseButton)

	local btn = script.Parent
	local uiGradient = btn:WaitForChild("UIGradient")
	
	local isHovering = false
	
	local tweenService = game:GetService("TweenService")
	local tweenInfo = TweenInfo.new(0.4, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
	
	local gradientRestoreTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(-0.35, 0)})
	local gradientAddTween = tweenService:Create(uiGradient, tweenInfo, {Offset = Vector2.new(1, 0)})
	
	
	btn.MouseEnter:Connect(function()
		
		isHovering = true
		
		gradientAddTween:Play()
	end)
	
	btn.MouseLeave:Connect(function()
		
		isHovering = false
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Down:Connect(function()
		
		gradientRestoreTween:Play()
	end)
	
	btn.MouseButton1Up:Connect(function()
		
		if not isHovering then
			gradientRestoreTween:Play()
		else
			gradientAddTween:Play()
		end
	end)
end
coroutine.wrap(RATH_fake_script)()
local function FBINJ_fake_script() -- ImageButton.LocalScript 
	local script = Instance.new('LocalScript', ImageButton)

	script.Parent.MouseButton1Click:connect(function()
		script.Parent.Parent.ImageLabel.Visible = not script.Parent.Parent.ImageLabel.Visible
	end)
	
end
coroutine.wrap(FBINJ_fake_script)()
