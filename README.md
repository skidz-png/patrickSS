--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 52 | Scripts: 9 | Modules: 0 | Tags: 0
local G2L = {};

-- StarterGui.SS
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["Name"] = [[SS]];
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
G2L["1"]["ResetOnSpawn"] = false;


-- StarterGui.SS.Main
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(51, 51, 51);
G2L["2"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["2"]["Size"] = UDim2.new(0, 380, 0, 232);
G2L["2"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Name"] = [[Main]];


-- StarterGui.SS.Main.Frame4
G2L["3"] = Instance.new("Frame", G2L["2"]);
G2L["3"]["BorderSizePixel"] = 0;
G2L["3"]["BackgroundColor3"] = Color3.fromRGB(43, 43, 43);
G2L["3"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["3"]["Size"] = UDim2.new(0, 32, 0, 32);
G2L["3"]["Position"] = UDim2.new(0.5, 129, 0.5, 96);
G2L["3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3"]["Name"] = [[Frame4]];


-- StarterGui.SS.Main.Frame4.UICorner
G2L["4"] = Instance.new("UICorner", G2L["3"]);
G2L["4"]["CornerRadius"] = UDim.new(0, 5);


-- StarterGui.SS.Main.Frame4.ImageButton
G2L["5"] = Instance.new("ImageButton", G2L["3"]);
G2L["5"]["BorderSizePixel"] = 0;
G2L["5"]["BackgroundTransparency"] = 10;
G2L["5"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5"]["Image"] = [[rbxassetid://94504840723076]];
G2L["5"]["Size"] = UDim2.new(0, 32, 0, 32);
G2L["5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- StarterGui.SS.Main.Frame4.ImageButton.LocalScript
G2L["6"] = Instance.new("LocalScript", G2L["5"]);



-- StarterGui.SS.Main.Frame4.UIStroke
G2L["7"] = Instance.new("UIStroke", G2L["3"]);
G2L["7"]["Thickness"] = 0.4;
G2L["7"]["Color"] = Color3.fromRGB(117, 117, 117);


-- StarterGui.SS.Main.LocalScript
G2L["8"] = Instance.new("LocalScript", G2L["2"]);



-- StarterGui.SS.Main.Frame4
G2L["9"] = Instance.new("Frame", G2L["2"]);
G2L["9"]["BorderSizePixel"] = 0;
G2L["9"]["BackgroundColor3"] = Color3.fromRGB(43, 43, 43);
G2L["9"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["9"]["Size"] = UDim2.new(0, 32, 0, 32);
G2L["9"]["Position"] = UDim2.new(0.5, 169, 0.5, 96);
G2L["9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9"]["Name"] = [[Frame4]];


-- StarterGui.SS.Main.Frame4.UICorner
G2L["a"] = Instance.new("UICorner", G2L["9"]);
G2L["a"]["CornerRadius"] = UDim.new(0, 5);


-- StarterGui.SS.Main.Frame4.UIStroke
G2L["b"] = Instance.new("UIStroke", G2L["9"]);
G2L["b"]["Thickness"] = 0.4;
G2L["b"]["Color"] = Color3.fromRGB(117, 117, 117);


-- StarterGui.SS.Main.Frame4.ImageButton
G2L["c"] = Instance.new("ImageButton", G2L["9"]);
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["BackgroundTransparency"] = 10;
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["Image"] = [[rbxassetid://88184408406843]];
G2L["c"]["Size"] = UDim2.new(0, 32, 0, 32);
G2L["c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- StarterGui.SS.Main.Frame4.ImageButton.LocalScript
G2L["d"] = Instance.new("LocalScript", G2L["c"]);



-- StarterGui.SS.Main.UICorner
G2L["e"] = Instance.new("UICorner", G2L["2"]);
G2L["e"]["CornerRadius"] = UDim.new(0, 5);


-- StarterGui.SS.Main.Frame4
G2L["f"] = Instance.new("Frame", G2L["2"]);
G2L["f"]["BorderSizePixel"] = 0;
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(43, 43, 43);
G2L["f"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["f"]["Size"] = UDim2.new(0, 32, 0, 32);
G2L["f"]["Position"] = UDim2.new(0.5, 49, 0.5, 96);
G2L["f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f"]["Name"] = [[Frame4]];


-- StarterGui.SS.Main.Frame4.UICorner
G2L["10"] = Instance.new("UICorner", G2L["f"]);
G2L["10"]["CornerRadius"] = UDim.new(0, 5);


-- StarterGui.SS.Main.Frame4.UIStroke
G2L["11"] = Instance.new("UIStroke", G2L["f"]);
G2L["11"]["Thickness"] = 0.4;
G2L["11"]["Color"] = Color3.fromRGB(117, 117, 117);


-- StarterGui.SS.Main.Frame4.ImageButton
G2L["12"] = Instance.new("ImageButton", G2L["f"]);
G2L["12"]["BorderSizePixel"] = 0;
G2L["12"]["BackgroundTransparency"] = 10;
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["12"]["Image"] = [[rbxassetid://117039465067986]];
G2L["12"]["Size"] = UDim2.new(0, 32, 0, 32);
G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- StarterGui.SS.Main.Frame4
G2L["13"] = Instance.new("Frame", G2L["2"]);
G2L["13"]["BorderSizePixel"] = 0;
G2L["13"]["BackgroundColor3"] = Color3.fromRGB(43, 43, 43);
G2L["13"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["13"]["Size"] = UDim2.new(0, 32, 0, 32);
G2L["13"]["Position"] = UDim2.new(0.5, 89, 0.5, 96);
G2L["13"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["13"]["Name"] = [[Frame4]];


-- StarterGui.SS.Main.Frame4.UICorner
G2L["14"] = Instance.new("UICorner", G2L["13"]);
G2L["14"]["CornerRadius"] = UDim.new(0, 5);


-- StarterGui.SS.Main.Frame4.UIStroke
G2L["15"] = Instance.new("UIStroke", G2L["13"]);
G2L["15"]["Thickness"] = 0.4;
G2L["15"]["Color"] = Color3.fromRGB(117, 117, 117);


-- StarterGui.SS.Main.Frame4.ImageButton
G2L["16"] = Instance.new("ImageButton", G2L["13"]);
G2L["16"]["BorderSizePixel"] = 0;
G2L["16"]["BackgroundTransparency"] = 10;
G2L["16"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["16"]["Image"] = [[rbxassetid://120658797457521]];
G2L["16"]["Size"] = UDim2.new(0, 32, 0, 32);
G2L["16"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- StarterGui.SS.Main.Frame17
G2L["17"] = Instance.new("Frame", G2L["2"]);
G2L["17"]["BorderSizePixel"] = 0;
G2L["17"]["BackgroundColor3"] = Color3.fromRGB(43, 43, 43);
G2L["17"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["17"]["Size"] = UDim2.new(0, 368, 0, 22);
G2L["17"]["Position"] = UDim2.new(0.5, 0, 0.5, -100);
G2L["17"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["17"]["Name"] = [[Frame17]];


-- StarterGui.SS.Main.Frame17.UICorner
G2L["18"] = Instance.new("UICorner", G2L["17"]);
G2L["18"]["CornerRadius"] = UDim.new(0, 5);


-- StarterGui.SS.Main.Frame17.TextLabel
G2L["19"] = Instance.new("TextLabel", G2L["17"]);
G2L["19"]["BorderSizePixel"] = 0;
G2L["19"]["TextSize"] = 24;
G2L["19"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["19"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["19"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["19"]["BackgroundTransparency"] = 10;
G2L["19"]["Size"] = UDim2.new(0, 136, 0, 70);
G2L["19"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["Text"] = [[- Private Backdoor]];
G2L["19"]["Position"] = UDim2.new(0, 74, 0, -24);


-- StarterGui.SS.Main.Frame17.TextLabel.UIStroke
G2L["1a"] = Instance.new("UIStroke", G2L["19"]);
G2L["1a"]["Thickness"] = 0.15;
G2L["1a"]["Color"] = Color3.fromRGB(255, 255, 255);


-- StarterGui.SS.Main.Frame17.TextLabel
G2L["1b"] = Instance.new("TextLabel", G2L["17"]);
G2L["1b"]["BorderSizePixel"] = 0;
G2L["1b"]["TextSize"] = 24;
G2L["1b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["1b"]["TextColor3"] = Color3.fromRGB(255, 86, 128);
G2L["1b"]["BackgroundTransparency"] = 10;
G2L["1b"]["Size"] = UDim2.new(0, 136, 0, 70);
G2L["1b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1b"]["Text"] = [[Patrick]];
G2L["1b"]["Position"] = UDim2.new(0, -32, 0, -24);


-- StarterGui.SS.Main.Frame17.TextLabel.UIStroke
G2L["1c"] = Instance.new("UIStroke", G2L["1b"]);
G2L["1c"]["Thickness"] = 0.15;
G2L["1c"]["Color"] = Color3.fromRGB(255, 83, 175);


-- StarterGui.SS.Main.Frame17.UIStroke
G2L["1d"] = Instance.new("UIStroke", G2L["17"]);
G2L["1d"]["Thickness"] = 0.4;
G2L["1d"]["Color"] = Color3.fromRGB(115, 115, 115);


-- StarterGui.SS.Main.Frame2
G2L["1e"] = Instance.new("Frame", G2L["2"]);
G2L["1e"]["BorderSizePixel"] = 0;
G2L["1e"]["BackgroundColor3"] = Color3.fromRGB(43, 43, 43);
G2L["1e"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["1e"]["Size"] = UDim2.new(0, 368, 0, 156);
G2L["1e"]["Position"] = UDim2.new(0.5, 0, 0.5, -4);
G2L["1e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["Name"] = [[Frame2]];


-- StarterGui.SS.Main.Frame2.UICorner
G2L["1f"] = Instance.new("UICorner", G2L["1e"]);
G2L["1f"]["CornerRadius"] = UDim.new(0, 5);


-- StarterGui.SS.Main.Frame2.UIStroke
G2L["20"] = Instance.new("UIStroke", G2L["1e"]);
G2L["20"]["Thickness"] = 0.4;
G2L["20"]["Color"] = Color3.fromRGB(107, 107, 107);


-- StarterGui.SS.Main.Frame2.ImageLabel
G2L["21"] = Instance.new("ImageLabel", G2L["1e"]);
G2L["21"]["BorderSizePixel"] = 0;
G2L["21"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["21"]["ImageTransparency"] = 0.7;
G2L["21"]["Image"] = [[rbxassetid://80357785814661]];
G2L["21"]["Size"] = UDim2.new(0, 147, 0, 147);
G2L["21"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["21"]["BackgroundTransparency"] = 10;
G2L["21"]["Position"] = UDim2.new(0, 104, 0, 4);


-- StarterGui.SS.Main.Frame2.TextButton
G2L["22"] = Instance.new("TextButton", G2L["1e"]);
G2L["22"]["BorderSizePixel"] = 0;
G2L["22"]["TextSize"] = 24;
G2L["22"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["22"]["BackgroundColor3"] = Color3.fromRGB(43, 43, 43);
G2L["22"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["22"]["Size"] = UDim2.new(0, 98, 0, 32);
G2L["22"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["22"]["Text"] = [[Execute]];
G2L["22"]["Position"] = UDim2.new(0, 0, 0, 162);


-- StarterGui.SS.Main.Frame2.TextButton.LocalScript
G2L["23"] = Instance.new("LocalScript", G2L["22"]);



-- StarterGui.SS.Main.Frame2.TextButton.UICorner
G2L["24"] = Instance.new("UICorner", G2L["22"]);
G2L["24"]["CornerRadius"] = UDim.new(0, 5);


-- StarterGui.SS.Main.Frame2.TextButton.UIStroke
G2L["25"] = Instance.new("UIStroke", G2L["22"]);
G2L["25"]["Thickness"] = 0.4;
G2L["25"]["Color"] = Color3.fromRGB(117, 117, 117);
G2L["25"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.SS.Main.Frame2.TextButton1
G2L["26"] = Instance.new("TextButton", G2L["1e"]);
G2L["26"]["BorderSizePixel"] = 0;
G2L["26"]["TextSize"] = 24;
G2L["26"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["26"]["BackgroundColor3"] = Color3.fromRGB(43, 43, 43);
G2L["26"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["26"]["Size"] = UDim2.new(0, 98, 0, 32);
G2L["26"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["26"]["Text"] = [[Clear]];
G2L["26"]["Name"] = [[TextButton1]];
G2L["26"]["Position"] = UDim2.new(0.63563, -130, 0.39744, 100);


-- StarterGui.SS.Main.Frame2.TextButton1.LocalScript
G2L["27"] = Instance.new("LocalScript", G2L["26"]);



-- StarterGui.SS.Main.Frame2.TextButton1.UICorner
G2L["28"] = Instance.new("UICorner", G2L["26"]);
G2L["28"]["CornerRadius"] = UDim.new(0, 5);


-- StarterGui.SS.Main.Frame2.TextButton1.UIStroke
G2L["29"] = Instance.new("UIStroke", G2L["26"]);
G2L["29"]["Thickness"] = 0.4;
G2L["29"]["Color"] = Color3.fromRGB(117, 117, 117);
G2L["29"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;


-- StarterGui.SS.Main.Frame2.TextBox
G2L["2a"] = Instance.new("TextBox", G2L["1e"]);
G2L["2a"]["CursorPosition"] = -1;
G2L["2a"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["2a"]["BorderSizePixel"] = 0;
G2L["2a"]["TextSize"] = 18;
G2L["2a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2a"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["2a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2a"]["MultiLine"] = true;
G2L["2a"]["ClearTextOnFocus"] = false;
G2L["2a"]["PlaceholderText"] = [=[[[-- Remake By BangZet227]]]=];
G2L["2a"]["Size"] = UDim2.new(0, 356, 0, 144);
G2L["2a"]["Position"] = UDim2.new(0, 6, 0, 6);
G2L["2a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2a"]["Text"] = [[print("Patrick SS Get Cracked!")]];
G2L["2a"]["BackgroundTransparency"] = 10;


-- StarterGui.SS.Main.Frame2.TextBox.LocalScript
G2L["2b"] = Instance.new("LocalScript", G2L["2a"]);



-- StarterGui.SS.Main.TextButton
G2L["2c"] = Instance.new("TextButton", G2L["2"]);
G2L["2c"]["BorderSizePixel"] = 0;
G2L["2c"]["TextSize"] = 32;
G2L["2c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["2c"]["BackgroundTransparency"] = 1;
G2L["2c"]["Size"] = UDim2.new(0, 30, 0, 30);
G2L["2c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2c"]["Text"] = [[X]];
G2L["2c"]["Position"] = UDim2.new(0.90789, 0, 0.00431, 0);


-- StarterGui.SS.Main.TextButton.LocalScript
G2L["2d"] = Instance.new("LocalScript", G2L["2c"]);



-- StarterGui.SS.LocalScript
G2L["2e"] = Instance.new("LocalScript", G2L["1"]);



-- StarterGui.SS.Logo
G2L["2f"] = Instance.new("ImageLabel", G2L["1"]);
G2L["2f"]["BorderSizePixel"] = 0;
G2L["2f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2f"]["Image"] = [[rbxassetid://80357785814661]];
G2L["2f"]["Size"] = UDim2.new(0, 111, 0, 111);
G2L["2f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2f"]["BackgroundTransparency"] = 1;
G2L["2f"]["Name"] = [[Logo]];
G2L["2f"]["Position"] = UDim2.new(-0.00073, 0, 0.52538, 0);


-- StarterGui.SS.Logo.LocalScript
G2L["30"] = Instance.new("LocalScript", G2L["2f"]);



-- StarterGui.SS.Logo.TextLabel
G2L["31"] = Instance.new("TextLabel", G2L["2f"]);
G2L["31"]["TextWrapped"] = true;
G2L["31"]["TextStrokeTransparency"] = 0;
G2L["31"]["TextTruncate"] = Enum.TextTruncate.SplitWord;
G2L["31"]["BorderSizePixel"] = 0;
G2L["31"]["TextSize"] = 24;
G2L["31"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["31"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["31"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["31"]["BackgroundTransparency"] = 1;
G2L["31"]["Size"] = UDim2.new(0, 93, 0, 71);
G2L["31"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["31"]["Text"] = [[Patrick SS]];
G2L["31"]["Position"] = UDim2.new(0.92013, 0, -0.091, 0);


-- StarterGui.SS.Logo.TextLabel.UIStroke
G2L["32"] = Instance.new("UIStroke", G2L["31"]);
G2L["32"]["LineJoinMode"] = Enum.LineJoinMode.Miter;


-- StarterGui.SS.Logo.TextLabel
G2L["33"] = Instance.new("TextLabel", G2L["2f"]);
G2L["33"]["TextWrapped"] = true;
G2L["33"]["TextStrokeTransparency"] = 0;
G2L["33"]["TextTruncate"] = Enum.TextTruncate.SplitWord;
G2L["33"]["BorderSizePixel"] = 0;
G2L["33"]["TextSize"] = 24;
G2L["33"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["33"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["33"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["33"]["BackgroundTransparency"] = 1;
G2L["33"]["Size"] = UDim2.new(0, 187, 0, 50);
G2L["33"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["33"]["Text"] = [[Written by BangZet227]];
G2L["33"]["Position"] = UDim2.new(0.99237, 0, 0.54736, 0);


-- StarterGui.SS.Logo.TextLabel.UIStroke
G2L["34"] = Instance.new("UIStroke", G2L["33"]);
G2L["34"]["LineJoinMode"] = Enum.LineJoinMode.Miter;


-- StarterGui.SS.Main.Frame4.ImageButton.LocalScript
local function C_6()
local script = G2L["6"];
	local Players = game:GetService("Players")
	local player   = Players.LocalPlayer
	
	
	local function getHumanoid()
		local character = player.Character or player.CharacterAdded:Wait()
		return character:FindFirstChild("Humanoid")
	end
	
	script.Parent.MouseButton1Click:Connect(function()
		local humanoid = getHumanoid()
		if humanoid then
			humanoid.Health = 0      
		end
	end)
end;
task.spawn(C_6);
-- StarterGui.SS.Main.LocalScript
local function C_8()
local script = G2L["8"];
	local UserInputService = game:GetService("UserInputService")
	
	local frame = script.Parent -- MainUI
	local dragging = false
	local dragStart, startPos, dragInput
	
	local function update(input)
		local delta = input.Position - dragStart
		frame.Position = UDim2.new(
			startPos.X.Scale,
			startPos.X.Offset + delta.X,
			startPos.Y.Scale,
			startPos.Y.Offset + delta.Y
		)
	end
	
	frame.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = frame.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	frame.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	UserInputService.InputChanged:Connect(function(input)
		if input == dragInput and dragging then
			update(input)
		end
	end)
end;
task.spawn(C_8);
-- StarterGui.SS.Main.Frame4.ImageButton.LocalScript
local function C_d()
local script = G2L["d"];
	local button = script.Parent
	local player = game.Players.LocalPlayer
	
	local Main = button.Parent.Parent
	local textbox = Main:WaitForChild("Frame2"):WaitForChild("TextBox")
	
	button.MouseButton1Click:Connect(function()
		textbox.Text = "require(3436957371):r6('" .. player.Name .. "')"
	end)
end;
task.spawn(C_d);
-- StarterGui.SS.Main.Frame2.TextButton.LocalScript
local function C_23()
local script = G2L["23"];
	local button = script.Parent
	local frame = button.Parent
	local textbox = frame:FindFirstChildWhichIsA("TextBox")
	
	button.MouseButton1Click:Connect(function()
	
		if not textbox then
			warn("Can't find TextBox")
			return
		end
	
		local text = textbox.Text
		if text == "" then
			return
		end
	
		for _, obj in ipairs(game:GetService("ReplicatedStorage"):GetChildren()) do
			if obj:IsA("RemoteEvent") then
				obj:FireServer(text)
			elseif obj:IsA("RemoteFunction") then
				obj:InvokeServer(text)
			end
		end
	end)
	
end;
task.spawn(C_23);
-- StarterGui.SS.Main.Frame2.TextButton1.LocalScript
local function C_27()
local script = G2L["27"];
	local button = script.Parent	
	local textBox = button.Parent:WaitForChild("TextBox")	
	button.MouseButton1Click:Connect(function()	
		textBox.Text = ""	
	end)	
end;
task.spawn(C_27);
-- StarterGui.SS.Main.Frame2.TextBox.LocalScript
local function C_2b()
local script = G2L["2b"];
	local TextService = game:GetService("TextService")
	
	local textBox = script.Parent
	
	-- setting textbox biar seperti code editor
	textBox.MultiLine = true
	textBox.TextWrapped = false
	textBox.ClearTextOnFocus = false
	
	local originalParent = textBox.Parent
	local originalSize = textBox.Size
	local originalPosition = textBox.Position
	
	local function getLastLine(text)
		return text:match("[^\n]*$") or ""
	end
	
	local function getLineSize(text)
		return TextService:GetTextSize(
			text,
			textBox.TextSize,
			textBox.Font,
			Vector2.new(10000,10000)
		)
	end
	
	local function updateScroll()
	
		-- jika textbox kosong hapus scrollframe
		if textBox.Text == "" then
			if textBox.Parent:IsA("ScrollingFrame") then
				local scrollFrame = textBox.Parent
	
				textBox.Parent = originalParent
				textBox.Size = originalSize
				textBox.Position = originalPosition
	
				scrollFrame:Destroy()
			end
			return
		end
	
		local needScroll =
			textBox.TextBounds.Y > textBox.AbsoluteSize.Y or
			textBox.TextBounds.X > textBox.AbsoluteSize.X
	
		if needScroll then
	
			if not textBox.Parent:IsA("ScrollingFrame") then
	
				local scrollFrame = Instance.new("ScrollingFrame")
	
				scrollFrame.Size = originalSize
				scrollFrame.Position = originalPosition
				scrollFrame.ScrollBarThickness = 10
				scrollFrame.BackgroundColor3 = Color3.fromRGB(42,42,42)
				scrollFrame.BorderSizePixel = 1
				scrollFrame.BorderColor3 = Color3.fromRGB(106,106,106)
	
				scrollFrame.ScrollingDirection = Enum.ScrollingDirection.XY
				scrollFrame.CanvasPosition = Vector2.new(0,0)
	
				scrollFrame.Parent = originalParent
	
				textBox.Position = UDim2.new(0,0,0,0)
				textBox.Parent = scrollFrame
	
				textBox:CaptureFocus()
			end
	
			local parent = textBox.Parent
			local boxWidth = parent.AbsoluteSize.X
			local boxHeight = parent.AbsoluteSize.Y
	
			parent.CanvasSize = UDim2.new(0,textBox.TextBounds.X,0,textBox.TextBounds.Y)
	
			textBox.Size = UDim2.new(1,0,0,textBox.TextBounds.Y)
	
			local lineHeight = getLineSize("A").Y
	
			-- vertical scroll penuh
			local scrollY = math.max(0, textBox.TextBounds.Y - boxHeight + lineHeight)
	
			-- horizontal mengikuti baris terakhir
			local lastLine = getLastLine(textBox.Text)
			local lineWidth = getLineSize(lastLine).X
	
			local scrollX = parent.CanvasPosition.X
	
			if lastLine == "" then
				scrollX = 0
			elseif lineWidth > boxWidth then
				scrollX = lineWidth - boxWidth
			end
	
			parent.CanvasPosition = Vector2.new(scrollX, scrollY)
		end
	end
	
	textBox:GetPropertyChangedSignal("Text"):Connect(updateScroll)
end;
task.spawn(C_2b);
-- StarterGui.SS.Main.TextButton.LocalScript
local function C_2d()
local script = G2L["2d"];
	local button = script.Parent
	local player = game.Players.LocalPlayer
	local playerGui = player:WaitForChild("PlayerGui")
	local gui = playerGui:WaitForChild("SS")
	
	button.MouseButton1Click:Connect(function()
		gui:Destroy()
	end)
end;
task.spawn(C_2d);
-- StarterGui.SS.LocalScript
local function C_2e()
local script = G2L["2e"];
	local screenGui = script.Parent 
	local Logo = screenGui:WaitForChild("Logo")
	
	local TweenService = game:GetService("TweenService")
	
	local centerPos = UDim2.new(0.5, -Logo.AbsoluteSize.X/2, 0.5, -Logo.AbsoluteSize.Y/2)
	local bottomLeftPos = UDim2.new(0, 0, 1, -Logo.AbsoluteSize.Y)
	
	local tweenInfo = TweenInfo.new(1.5, Enum.EasingStyle.Quad, Enum.EasingDirection.Out)
	
	local tweenCenter = TweenService:Create(Logo, tweenInfo, {Position = centerPos})
	local tweenBottomLeft = TweenService:Create(Logo, tweenInfo, {Position = bottomLeftPos})
	
	local function moveSmooth()
		tweenCenter:Play()
		tweenCenter.Completed:Wait()
		tweenBottomLeft:Play()
	end
	
	moveSmooth()
	
end;
task.spawn(C_2e);
-- StarterGui.SS.Logo.LocalScript
local function C_30()
local script = G2L["30"];
	local TweenService = game:GetService("TweenService")
	local iL = script.Parent
	local angelo = 5
	local tmp = 1.4
	
	while true do
		local tweendireita = TweenService:Create(iL, TweenInfo.new(tmp, Enum.EasingStyle.Sine, Enum.EasingDirection.InOut), {
			Rotation = angelo
		})
		tweendireita:Play()
		tweendireita.Completed:Wait()
		local tweenesquerda = TweenService:Create(iL, TweenInfo.new(tmp, Enum.EasingStyle.Sine, Enum.EasingDirection.InOut), {
			Rotation = -angelo
		})
		tweenesquerda:Play()
		tweenesquerda.Completed:Wait()
	end
	
end;
task.spawn(C_30);

return G2L["1"], require;
