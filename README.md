

local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local EtoFly = Instance.new("TextButton")
local FtoNoClip = Instance.new("TextButton")
local InfJump = Instance.new("TextButton")
local RevizAdmin = Instance.new("TextButton")
local Nightmare = Instance.new("TextButton")
local Btools = Instance.new("TextButton")
local Suicide = Instance.new("TextButton")
local BackflipZX = Instance.new("TextButton")
local Teleport = Instance.new("TextButton")
local TextLabel_2 = Instance.new("TextLabel")
local JailBreak = Instance.new("ImageButton")
local MM2 = Instance.new("ImageButton")
local RoCitizens = Instance.new("ImageButton")
local PrisonLife = Instance.new("ImageButton")
local NaturalDisaster = Instance.new("ImageButton")
local CounterBlox = Instance.new("ImageButton")
local MadCity = Instance.new("ImageButton")
local Arsenal = Instance.new("ImageButton")

--Properties:

ScreenGui.Parent = game.CoreGui

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
main.BorderColor3 = Color3.fromRGB(255, 0, 0)
main.BorderSizePixel = 2
main.Position = UDim2.new(0.182872996, 0, 0.410319388, 0)
main.Size = UDim2.new(0, 459, 0, 230)
main.Style = Enum.FrameStyle.RobloxSquare
main.Active = true
main.Draggable = true

TextLabel.Parent = main
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(255, 0, 0)
TextLabel.BorderSizePixel = 2
TextLabel.Position = UDim2.new(-0.0176809151, 0, -0.0131559949, 0)
TextLabel.Size = UDim2.new(0, 456, 0, 50)
TextLabel.Font = Enum.Font.Jura
TextLabel.Text = "Tar's Exploit GUI"
TextLabel.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel.TextSize = 40.000
TextLabel.TextStrokeColor3 = Color3.fromRGB(255, 0, 0)
TextLabel.TextWrapped = true

EtoFly.Name = "E to Fly"
EtoFly.Parent = main
EtoFly.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
EtoFly.BorderColor3 = Color3.fromRGB(255, 0, 0)
EtoFly.Position = UDim2.new(0.0149715347, 0, 0.276105791, 0)
EtoFly.Size = UDim2.new(0, 138, 0, 36)
EtoFly.Font = Enum.Font.SciFi
EtoFly.Text = "E to Fly"
EtoFly.TextColor3 = Color3.fromRGB(255, 0, 0)
EtoFly.TextSize = 21.000
EtoFly.MouseButton1Down:connect(function()
	-- Press "E" to fly and unfly
	-- You have to re-apply the script if you die
	loadstring(game:HttpGet("https://pastebin.com/raw/7rXZ9VNc", true))()
end)

FtoNoClip.Name = "F to NoClip"
FtoNoClip.Parent = main
FtoNoClip.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
FtoNoClip.BorderColor3 = Color3.fromRGB(255, 0, 0)
FtoNoClip.Position = UDim2.new(0.0149715347, 0, 0.497844934, 0)
FtoNoClip.Size = UDim2.new(0, 138, 0, 36)
FtoNoClip.Font = Enum.Font.SciFi
FtoNoClip.Text = "F to NoClip"
FtoNoClip.TextColor3 = Color3.fromRGB(255, 0, 0)
FtoNoClip.TextSize = 21.000
FtoNoClip.MouseButton1Down:connect(function()
	noclip = false
	game:GetService('RunService').Stepped:connect(function()
		if noclip then
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
		end
	end)
	plr = game.Players.LocalPlayer
	mouse = plr:GetMouse()
	mouse.KeyDown:connect(function(key)

		if key == "f" then
			noclip = not noclip
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
		end
	end)
	print('Loaded')
	print('Press "F" to noclip')
end)

InfJump.Name = "Inf Jump"
InfJump.Parent = main
InfJump.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
InfJump.BorderColor3 = Color3.fromRGB(255, 0, 0)
InfJump.Position = UDim2.new(0.0149715347, 0, 0.719583988, 0)
InfJump.Size = UDim2.new(0, 138, 0, 36)
InfJump.Font = Enum.Font.SciFi
InfJump.Text = "Inf Jump"
InfJump.TextColor3 = Color3.fromRGB(255, 0, 0)
InfJump.TextSize = 21.000
InfJump.MouseButton1Down:connect(function()
	--[[Subscribe to Zaptosis on YouTube for more awesome scripts!

░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
███▀▀▀███░░░░░░░░░░░░░░░░░░░██░░░░░░░░░░░░░░░░░░░░██░░░░░░░░░
█▀░░░███░░░░░░░░░░░░░░░░░░░░██░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
▀░░░███░░▄█▀██▄░▀████████▄██████░░▄██▀██▄░▄██▀██████░░▄██▀███
░░░███░░██░░░██░░░██░░░▀██░░██░░░██▀░░░▀████░░░▀▀░██░░██░░░▀▀
░░███░░░▄▄█████░░░██░░░░██░░██░░░██░░░░░██▀█████▄░██░░▀█████▄
░███░░░▄██░░░██░░░██░░░▄██░░██░░░██▄░░░▄███▄░░░██░██░░█▄░░░██
█████████████▀██▄░██████▀░░░▀████░▀█████▀░██████▀████▄██████▀
░░░░░░░░░░░░░░░░░░██░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
░░░░░░░░░░░░░░░░▄████▄░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
]]

	_G.infinjump = true

	local Player = game:GetService("Players").LocalPlayer
	local Mouse = Player:GetMouse()
	Mouse.KeyDown:connect(function(k)
		if _G.infinjump then
			if k:byte() == 32 then
				Humanoid = game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Humanoid")
				Humanoid:ChangeState("Jumping")
				wait(0.1)
				Humanoid:ChangeState("Seated")
			end
		end
	end)

	local Player = game:GetService("Players").LocalPlayer
	local Mouse = Player:GetMouse()
	Mouse.KeyDown:connect(function(k)
		k = k:lower()
		if k == "f" then
			if _G.infinjump == true then
				_G.infinjump = false
			else
				_G.infinjump = true
			end
		end
	end)
end)

RevizAdmin.Name = "Reviz Admin"
RevizAdmin.Parent = main
RevizAdmin.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
RevizAdmin.BorderColor3 = Color3.fromRGB(255, 0, 0)
RevizAdmin.Position = UDim2.new(0.344670296, 0, 0.719583988, 0)
RevizAdmin.Size = UDim2.new(0, 138, 0, 36)
RevizAdmin.Font = Enum.Font.SciFi
RevizAdmin.Text = "Reviz Admin"
RevizAdmin.TextColor3 = Color3.fromRGB(255, 0, 0)
RevizAdmin.TextSize = 21.000
RevizAdmin.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/pyzjWNhk'),true))()

end)

Nightmare.Name = "Nightmare"
Nightmare.Parent = main
Nightmare.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
Nightmare.BorderColor3 = Color3.fromRGB(255, 0, 0)
Nightmare.Position = UDim2.new(0.344670296, 0, 0.497844934, 0)
Nightmare.Size = UDim2.new(0, 138, 0, 36)
Nightmare.Font = Enum.Font.SciFi
Nightmare.Text = "Nightmare"
Nightmare.TextColor3 = Color3.fromRGB(255, 0, 0)
Nightmare.TextSize = 15.000
Nightmare.MouseButton1Down:connect(function()
	-----------//VEREUS\\-----------
--[[Movelist
Q = The reverse penance stare,
E = Doom Pillars
T = Unleashed evil ball
Y = The hunt is on
Z = CRAZY XESTER SWITCH!!!
X = Re_*101011Dact/^ed.exe
---------]]

	--To get this shit out of the way, this is NOT a edit of void boss, it was a little project of mine to see how easy it was to animate 2 hands and a head.--
	--Also stop calling this void boss v2, void boss switcher or any other name you come up with.--
	--I'm not proud of this project however, having a script this powerful is uncreative and boring + that's what skids care about anyway.--
	--Alright enjoy it guys please do not abuse the shit out of this.--

	Player=game:GetService("Players").LocalPlayer
	Character=Player.Character
	Character.Humanoid.Name = "vereus"
	hum = Character.vereus
	LeftArm=Character["Left Arm"]
	LeftLeg=Character["Left Leg"]
	RightArm=Character["Right Arm"]
	RightLeg=Character["Right Leg"]
	Root=Character["HumanoidRootPart"]
	Head=Character["Head"]
	Torso=Character["Torso"]
	Neck=Torso["Neck"]
	attacking = false
	snoring = false
	laughing = false
	taim = nil
	secondform = false
	change = 0
	xester = false
	rachjumper = false
	ws = 92
	hpheight = 5
	huntdown = false
	visualizer = false
	jumpscared = false
	appi = false
	stoplev = false
	tauntdebounce = false
	allowlev = true
	MseGuide = true
	position = nil
	levitate = false
	mouse = Player:GetMouse()
	settime = 0
	sine = 0
	t = 0
	dgs = 75
	RunSrv = game:GetService("RunService")
	RenderStepped = game:GetService("RunService").RenderStepped
	removeuseless = game:GetService("Debris")
	smoothen = game:GetService("TweenService")
	randomcolortable={"Cyan","Really red","Cyan","Royal purple","Lime green","Crimson","Daisy yellow","Eggplant"}
	random = #randomcolortable
	smoothen = game:GetService("TweenService")
	local dmt2 = {143536946,2858940717}
	local laughs = {2011349649,2011349983,2011351501,2011352223,2011355991,2011356475}
	local soundtable2 = {2616767970,2614901458,2616891279,2614896603,2616768521,2616848595,2614905967,2614918002,2563244734,2563244134,2563244444,2563244999,2563245407,2563654940,2563656758,2563658474,2563659001}
	laugh = #laughs

	local HEADLERP = Instance.new("ManualWeld")
	HEADLERP.Parent = Head
	HEADLERP.Part0 = Head
	HEADLERP.Part1 = Head
	HEADLERP.C0 = CFrame.new(0, -1.5, -.5) * CFrame.Angles(math.rad(30), math.rad(0), math.rad(0))

	local TORSOLERP = Instance.new("ManualWeld")
	TORSOLERP.Parent = Root
	TORSOLERP.Part0 = Torso
	TORSOLERP.C0 = CFrame.new(0, 0, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(0))

	local ROOTLERP = Instance.new("ManualWeld")
	ROOTLERP.Parent = Root
	ROOTLERP.Part0 = Root
	ROOTLERP.Part1 = Torso
	ROOTLERP.C0 = CFrame.new(0, 0, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(0))

	local RIGHTARMLERP = Instance.new("ManualWeld")
	RIGHTARMLERP.Parent = RightArm
	RIGHTARMLERP.Part0 = RightArm
	RIGHTARMLERP.Part1 = Torso
	RIGHTARMLERP.C0 = CFrame.new(-1.5, 0, -0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(0))

	local LEFTARMLERP = Instance.new("ManualWeld")
	LEFTARMLERP.Parent = LeftArm
	LEFTARMLERP.Part0 = LeftArm
	LEFTARMLERP.Part1 = Torso
	LEFTARMLERP.C0 = CFrame.new(1.5, 0, -0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(0))

	local RIGHTLEGLERP = Instance.new("ManualWeld")
	RIGHTLEGLERP.Parent = RightLeg
	RIGHTLEGLERP.Part0 = RightLeg
	RIGHTLEGLERP.Part1 = Torso
	RIGHTLEGLERP.C0 = CFrame.new(-0.5, 2, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(0))

	local LEFTLEGLERP = Instance.new("ManualWeld")
	LEFTLEGLERP.Parent = LeftLeg
	LEFTLEGLERP.Part0 = LeftLeg
	LEFTLEGLERP.Part1 = Torso
	LEFTLEGLERP.C0 = CFrame.new(0.5, 2, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(0))

	local function weldBetween(a, b)
		local weld = Instance.new("ManualWeld", a)
		weld.Part0 = a
		weld.Part1 = b
		weld.C0 = a.CFrame:inverse() * b.CFrame
		return weld
	end

	function MAKETRAIL(PARENT,POSITION1,POSITION2,LIFETIME,COLOR)
		A = Instance.new("Attachment", PARENT)
		A.Position = POSITION1
		A.Name = "A"
		B = Instance.new("Attachment", PARENT)
		B.Position = POSITION2
		B.Name = "B"
		tr1 = Instance.new("Trail", PARENT)
		tr1.Attachment0 = A
		tr1.Attachment1 = B
		tr1.Enabled = true
		tr1.Lifetime = LIFETIME
		tr1.TextureMode = "Static"
		tr1.LightInfluence = 0
		tr1.Color = COLOR
		tr1.Transparency = NumberSequence.new(0, 1)
	end

	coroutine.wrap(function()
		while wait() do
			hum.WalkSpeed = ws
		end
	end)()
	godmode = coroutine.wrap(function()
		for i,v in pairs(Character:GetChildren()) do
			if v:IsA("BasePart") and v ~= Root then
				v.Anchored = false
			end
		end
		while true do
			hum.MaxHealth = math.huge
			wait(0.0000001)
			hum.Health = math.huge
			wait()
		end
	end)
	godmode()
	ff = Instance.new("ForceField", Character)
	ff.Visible = false

	coroutine.wrap(function()
		for i,v in pairs(Character:GetChildren()) do
			if v.Name == "Animate" then v:Remove()
			end
		end
	end)()

	for _,x in pairs(Character:GetChildren()) do
		if x:IsA("Decal") then x:Remove() end
	end

	function damagealll(Radius,Position)		
		local Returning = {}		
		for _,v in pairs(workspace:GetChildren()) do		
			if v~=Character and v:FindFirstChildOfClass('Humanoid') and v:FindFirstChild('Torso') or v:FindFirstChild('UpperTorso') then
				if v:FindFirstChild("Torso") then		
					local Mag = (v.Torso.Position - Position).magnitude		
					if Mag < Radius then		
						table.insert(Returning,v)		
					end
				elseif v:FindFirstChild("UpperTorso") then	
					local Mag = (v.UpperTorso.Position - Position).magnitude		
					if Mag < Radius then		
						table.insert(Returning,v)		
					end
				end	
			end		
		end		
		return Returning		
	end

	ArtificialHB = Instance.new("BindableEvent", script)
	ArtificialHB.Name = "Heartbeat"
	script:WaitForChild("Heartbeat")

	frame = 1 / 60
	tf = 0
	allowframeloss = false
	tossremainder = false


	lastframe = tick()
	script.Heartbeat:Fire()


	game:GetService("RunService").Heartbeat:connect(function(s, p)
		tf = tf + s
		if tf >= frame then
			if allowframeloss then
				script.Heartbeat:Fire()
				lastframe = tick()
			else
				for i = 1, math.floor(tf / frame) do
					script.Heartbeat:Fire()
				end
				lastframe = tick()
			end
			if tossremainder then
				tf = 0
			else
				tf = tf - frame * math.floor(tf / frame)
			end
		end
	end)

	function swait(num)
		if num == 0 or num == nil then
			game:service("RunService").Stepped:wait(0)
		else
			for i = 0, num do
				game:service("RunService").Stepped:wait(0)
			end
		end
	end

	for i,v in pairs(Root.Parent:GetDescendants()) do if v:IsA("Part") then v.Transparency = 1 end end

	id = "rbxassetid://2858940717"


	dmt2random = dmt2[math.random(1,#dmt2)]
	doomtheme = Instance.new("Sound", Torso)
	doomtheme.Volume = 4
	doomtheme.Name = "doomtheme"
	doomtheme.Looped = true
	doomtheme.SoundId = "rbxassetid://"..dmt2random
	if doomtheme.SoundId == "rbxassetid://2858940717" then
		doomtheme.Pitch = .49
	else
		doomtheme.Pitch = 1
	end
	doomtheme:Play()


	Torso.ChildRemoved:connect(function(removed)
		if removed.Name == "doomtheme" then
			if xester then
				doomtheme = Instance.new("Sound",Torso)
				doomtheme.Volume = 4
				doomtheme.Name = "doomtheme"
				doomtheme.Looped = true
				doomtheme.SoundId = "rbxassetid://1382488262"
				doomtheme.TimePosition = 20.72
				doomtheme:Play()
			else
				dmt2random = dmt2[math.random(1,#dmt2)]
				doomtheme = Instance.new("Sound",Torso)
				doomtheme.Volume = 4
				doomtheme.Name = "doomtheme"
				doomtheme.Looped = true
				doomtheme.SoundId = "rbxassetid://"..dmt2random
				if doomtheme.SoundId == "rbxassetid://2858940717" then
					doomtheme.Pitch = .49
				else
					doomtheme.Pitch = 1
				end
				doomtheme:Play()
			end
		end
	end)

	function SOUND(PARENT,ID,VOL,LOOP,REMOVE)
		local so = Instance.new("Sound")
		so.Parent = PARENT
		so.SoundId = "rbxassetid://"..ID
		so.Volume = VOL
		so.Looped = LOOP
		so:Play()
		removeuseless:AddItem(so,REMOVE)
	end

	bighead = Instance.new("Part",Torso)
	bighead.Size = Vector3.new(1,1,1)
	bighead.Anchored = false
	bighead.CanCollide = false
	bighead.Locked = true
	bighead.Size = Vector3.new(4.75, 4.89, 4.77)
	bighead.BrickColor = BrickColor.new("Really black")
	bighead.CFrame = Head.CFrame
	bigheadweld = weldBetween(bighead,Head)
	headmesh = Instance.new("SpecialMesh",bighead)
	headmesh.MeshType = "Head"
	headmesh.Scale = Vector3.new(1.25,1.25,1.25)

	mask = Instance.new("Part",Torso)
	mask.Size = Vector3.new(.1, 0.39, .1)
	mask.Anchored = false
	mask.Locked = true
	mask.CanCollide = false
	mask.BrickColor = BrickColor.new("White")
	mask.Material = "Corroded Metal"
	maskweld = weldBetween(mask,bighead)
	maskweld.C0 = CFrame.new(0,-2.4,0) * CFrame.Angles(math.rad(90),0,0)
	maskmesh = Instance.new("SpecialMesh",mask)
	maskmesh.MeshId = "rbxassetid://5158270"
	maskmesh.TextureId = "rbxassetid://128212042"
	maskmesh.Scale = Vector3.new(0.7, 0.5, 0.5)

	lightpart1 = Instance.new("Part",Head)
	lightpart1.Size = Vector3.new(2.42,2,.516)
	lightpart1.Anchored = false
	lightpart1.Transparency = 1
	lightpart1.BrickColor = BrickColor.new("White")
	lightpart1.Material = "Neon"
	lightpart1weld = weldBetween(lightpart1,Head)
	lightpart1weld.C0 = CFrame.new(0,.9,2.595)

	horns = Instance.new("Part",Torso)
	horns.Size = Vector3.new(.1,.1,.1)
	horns.Material = "Slate"
	horns.Locked = true
	horns.BrickColor = BrickColor.new("Really black")
	horns.CFrame = Head.CFrame * CFrame.new(0,3,0)
	hornsmesh = Instance.new("SpecialMesh",horns)
	hornsmesh.MeshId = "rbxassetid://434078905"
	hornsmesh.Scale = Vector3.new(13,12,12)
	hornsweld = weldBetween(horns,bighead)
	hornsweld.C0 = CFrame.new(0,-3.3,.82) * CFrame.Angles(math.rad(0),math.rad(180),0)

	hand1 = Instance.new("Part",Torso)
	hand1.Size = Vector3.new(.1,.1,.1)
	hand1.Anchored = false
	hand1.Locked = true
	hand1.CanCollide = false
	hand1.BrickColor = BrickColor.new("White")
	hand1.Material = "Slate"
	hand1mesh = Instance.new("SpecialMesh",hand1)
	hand1mesh.MeshId = "rbxassetid://37241605"
	hand1mesh.Scale = Vector3.new(8, 8, 8)
	HAND1LERP = weldBetween(hand1,Torso)
	HAND1LERP.C0 = CFrame.new(4.5,-5,6) * CFrame.Angles(math.rad(10),math.rad(-5),math.rad(-36))

	hand2 = Instance.new("Part",Torso)
	hand2.Size = Vector3.new(.1,.1,.1)
	hand2.Anchored = false
	hand2.CanCollide = false
	hand2.Locked = true
	hand2.BrickColor = BrickColor.new("White")
	hand2.Material = "Slate"
	hand2mesh = Instance.new("SpecialMesh",hand2)
	hand2mesh.MeshId = "rbxassetid://2899129749"
	hand2mesh.Scale = Vector3.new(.8, .8, .8)
	HAND2LERP = weldBetween(hand2,Torso)
	HAND2LERP.C0 = HAND2LERP.C0:Inverse() * CFrame.new(-5,-5,6) * CFrame.Angles(math.rad(90),math.rad(90),math.rad(95))

	mg1 = Instance.new("Part",Torso)
	mg1.Anchored = false
	mg1.CanCollide = false
	mg1.Locked = true
	mg1.Size = Vector3.new(4,4,4)
	mg1.Shape = "Ball"
	mg1.BrickColor = BrickColor.new("Really black")
	mg1.Material = "Neon"
	mg1.CFrame = hand1.CFrame
	mg1weld = weldBetween(mg1,hand1)
	mg1weld.C0 = CFrame.new(0,2.7,-4)
	blackhole = Instance.new("ParticleEmitter",mg1)
	blackhole.Texture = "rbxassetid://258128463"
	blackhole.Size = NumberSequence.new(2,2)
	blackhole.Rate = 50
	blackhole.LockedToPart = true
	blackhole.Color = ColorSequence.new(BrickColor.new("Really black").Color,BrickColor.new("Really black").Color)
	blackhole.RotSpeed = NumberRange.new(50)
	blackhole.Lifetime = NumberRange.new(1)
	blackhole.Speed = NumberRange.new(0)

	mg2 = Instance.new("Part",Torso)
	mg2.Anchored = false
	mg2.CanCollide = false
	mg2.Shape = "Ball"
	mg2.Locked = true
	mg2.Size = Vector3.new(4,4,4)
	mg2.BrickColor = BrickColor.new("Really black")
	mg2.Material = "Neon"
	mg2.CFrame = hand2.CFrame
	mg2weld = weldBetween(mg2,hand2)
	mg2weld.C0 = CFrame.new(0,2.7,-4)
	blackhole2 = Instance.new("ParticleEmitter",mg2)
	blackhole2.Texture = "rbxassetid://258128463"
	blackhole2.Size = NumberSequence.new(2,2)
	blackhole2.Rate = 50
	blackhole2.Color = ColorSequence.new(BrickColor.new("Really black").Color,BrickColor.new("Really black").Color)
	blackhole2.RotSpeed = NumberRange.new(50)
	blackhole2.Lifetime = NumberRange.new(1)
	blackhole2.LockedToPart = true
	blackhole2.Speed = NumberRange.new(0)

	slaten = Instance.new("Decal",hand2)
	slaten.Texture = "rbxassetid://647441616"
	slaten.Color3 = Color3.new(0, 0, 0)
	slaten.Face = "Top"

	slaten2 = Instance.new("Decal",hand2)
	slaten2.Texture = "rbxassetid://647417318"
	slaten2.Color3 = Color3.new(0,0,0)
	slaten2.Face = "Top"

	slatez = Instance.new("Decal",hand1)
	slatez.Texture = "rbxassetid://647441616"
	slatez.Color3 = Color3.new(0, 0, 0)
	slatez.Face = "Top"

	slatez2 = Instance.new("Decal",hand1)
	slatez2.Texture = "rbxassetid://647417318"
	slatez2.Color3 = Color3.new(0,0,0)
	slatez2.Face = "Top"

	slatez3 = Instance.new("Decal",hand1)
	slatez3.Texture = "rbxassetid://647410994"
	slatez3.Color3 = Color3.new(1,1,1)
	slatez3.Face = "Top"

	slatez4 = Instance.new("Decal",hand1)
	slatez4.Texture = "rbxassetid://647413967"
	slatez4.Color3 = Color3.new(1,1,1)
	slatez4.Face = "Top"

	slatex = Instance.new("Decal",horns)
	slatex.Texture = "rbxassetid://647441616"
	slatex.Color3 = Color3.new(0, 0, 0)
	slatex.Face = "Top"

	slatex2 = Instance.new("Decal",horns)
	slatex2.Texture = "rbxassetid://647417318"
	slatex2.Color3 = Color3.new(0,0,0)
	slatex2.Face = "Top"

	slatex3 = Instance.new("Decal",horns)
	slatex3.Texture = "rbxassetid://647410994"
	slatex3.Color3 = Color3.new(1,1,1)
	slatex3.Face = "Top"

	slatex4 = Instance.new("Decal",horns)
	slatex4.Texture = "rbxassetid://647413967"
	slatex4.Color3 = Color3.new(1,1,1)
	slatex4.Face = "Top"

	slatex5 = Instance.new("Decal",horns)
	slatex5.Texture = "rbxassetid://64739326f6"
	slatex5.Color3 = Color3.new(1, 1, 1)
	slatex5.Face = "Top"

	eyeball1 = Instance.new("Part",Torso)
	eyeball1.Anchored = false
	eyeball1.CanCollide = false
	eyeball1.Locked = true
	eyeball1.Shape = "Ball"
	eyeball1.Material = "Glass"
	eyeball1.Size = Vector3.new(3.25, 3.25, 3.25)
	eyeball1.BrickColor = BrickColor.new("Really black")
	eyeball1weld = weldBetween(eyeball1,Head)
	eyeball1weld.C0 = CFrame.new(.6,-.2,1.25)

	eyeball2 = Instance.new("Part",Torso)
	eyeball2.Anchored = false
	eyeball2.CanCollide = false
	eyeball2.Shape = "Ball"
	eyeball2.Locked = true
	eyeball2.Material = "Glass"
	eyeball2.Size = Vector3.new(3.25, 3.25, 3.25)
	eyeball2.BrickColor = BrickColor.new("Really black")
	eyeball2weld = weldBetween(eyeball2,Head)
	eyeball2weld.C0 = CFrame.new(-.6,-.2,1.25)

	eyeball3 = Instance.new("Part",Torso)
	eyeball3.Anchored = false
	eyeball3.CanCollide = false
	eyeball3.Locked = true
	eyeball3.Material = "Neon"
	eyeball3.Size = Vector3.new(0.4, 0.4, 0.4)
	eyeball3.BrickColor = BrickColor.new("Crimson")
	eyeball3mesh = Instance.new("SpecialMesh",eyeball3)
	eyeball3mesh.MeshType = "Sphere"
	eyeball3weld = weldBetween(eyeball3,Head)
	eyeball3weld.C0 = CFrame.new(-1.2,-.3,2.65)

	eyeball4 = Instance.new("Part",Torso)
	eyeball4.Anchored = false
	eyeball4.CanCollide = false
	eyeball4.Material = "Neon"
	eyeball4.Locked = true
	eyeball4.Size = Vector3.new(0.4, 0.4, 0.4)
	eyeball4.BrickColor = BrickColor.new("Crimson")
	eyeball4mesh = Instance.new("SpecialMesh",eyeball4)
	eyeball4mesh.MeshType = "Sphere"
	eyeball4weld = weldBetween(eyeball4,Head)
	eyeball4weld.C0 = CFrame.new(1.2,-.3,2.65)

	coroutine.wrap(function()
		while true do
			wait(5)
			for i = 1, 10 do
				eyeball3.Size = eyeball3.Size - Vector3.new(0,.04,0)
				eyeball4.Size = eyeball4.Size - Vector3.new(0,.04,0)
				swait()
			end
			for i = 1, 10 do
				eyeball3.Size = eyeball3.Size + Vector3.new(0,.04,0)
				eyeball4.Size = eyeball4.Size + Vector3.new(0,.04,0)
				swait()
			end
			swait()
		end
	end)()

	slateh = Instance.new("Decal",mask)
	slateh.Texture = "rbxassetid://647441616"
	slateh.Color3 = Color3.new(0, 0, 0)
	slateh.Face = "Top"

	slateh2 = Instance.new("Decal",mask)
	slateh2.Texture = "rbxassetid://647417318"
	slateh2.Color3 = Color3.new(0,0,0)
	slateh2.Face = "Top"

	slateh3 = Instance.new("Decal",mask)
	slateh3.Texture = "rbxassetid://647410994"
	slateh3.Color3 = Color3.new(1,1,1)
	slateh3.Face = "Top"

	slateh4 = Instance.new("Decal",mask)
	slateh4.Texture = "rbxassetid://647413967"
	slateh4.Color3 = Color3.new(1,1,1)
	slateh4.Face = "Top"

	slateh5 = Instance.new("Decal",mask)
	slateh5.Texture = "rbxassetid://64739326f6"
	slateh5.Color3 = Color3.new(1, 1, 1)
	slateh5.Face = "Top"

	mouse.KeyDown:connect(function(Press)
		Press=Press:lower()
		if Press=='m' then
			immortality()
		elseif Press=='t' then
			if xester then
				if tauntdebounce then return end
				tauntdebounce = true
				laughing = true
				laugh = laughs[math.random(1,#laughs)]
				laughy = Instance.new("Sound",Head)
				laughy.SoundId = "rbxassetid://"..laugh
				laughy.Volume = 10
				laughy:Play()
				wait(1)
				wait(laughy.TimeLength)
				laughing = false
				laughy:Remove()
				tauntdebounce = false
			elseif rachjumper then
				if tauntdebounce == true then return end
				tauntdebounce = true
				rdnm2 = soundtable2[math.random(1,#soundtable2)]
				tauntsound = Instance.new("Sound", Head)
				tauntsound.Volume = 8
				tauntsound.SoundId = "http://www.roblox.com/asset/?id="..rdnm2
				tauntsound.Looped = false
				tauntsound:Play()
				wait(3)
				wait(tauntsound.TimeLength)
				tauntsound:Remove()
				wait(1)
				tauntdebounce = false
			else
				if debounce then return end
				debounce = true
				attacking = true
				ws = 0
				local energball = Instance.new("Part",Torso)
				energball.Shape = "Ball"
				energball.Material = "Neon"
				energball.Size = Vector3.new(.1,.1,.1)
				energball.Anchored = true
				energball.CanCollide = false
				energball.BrickColor = BrickColor.new("Really black")
				energball.CFrame = hand1.CFrame * CFrame.new(0,1,-2.5)
				SOUND(energball,2880335731,10,false,10)
				local g1 = Instance.new("BodyGyro", Root)
				g1.D = 175
				g1.P = 20000
				g1.MaxTorque = Vector3.new(0,9000,0)
				for i = 1, 250 do
					g1.CFrame = g1.CFrame:lerp(CFrame.new(Root.Position,mouse.Hit.p),.2)
					coroutine.wrap(function()
						local sk = Instance.new("Part",Torso)
						sk.CanCollide = false
						sk.Anchored = true
						sk.BrickColor = BrickColor.new("Really black")
						sk.Name = "sk"
						sk.CFrame = energball.CFrame * CFrame.Angles(math.rad(math.random(-180,180)),0,math.rad(math.random(-180,180)))
						local skmesh = Instance.new("SpecialMesh",sk)
						skmesh.MeshId = "rbxassetid://662586858"
						skmesh.Name = "wave"
						skmesh.Scale = Vector3.new(.02,.005,.02)
						for i = 1, 20 do
							skmesh.Scale = skmesh.Scale + Vector3.new(.004,0,.004)
							sk.Transparency = sk.Transparency + .05
							swait()
						end
						sk:Remove()
					end)()
					coroutine.wrap(function()
						local shockwave = Instance.new("Part", Torso)
						shockwave.Size = Vector3.new(1,1,1)
						shockwave.CanCollide = false
						shockwave.Anchored = true
						shockwave.Transparency = .7
						shockwave.BrickColor = BrickColor.new("Really black")
						shockwave.CFrame = CFrame.new(energball.Position) * CFrame.Angles(math.rad(math.random(-180,180)),math.rad(math.random(-180,180)),math.rad(math.random(-180,180)))
						local shockwavemesh = Instance.new("SpecialMesh", shockwave)
						shockwavemesh.Scale = Vector3.new(7,.1,7)
						shockwavemesh.MeshId = "rbxassetid://20329976"
						for i = 1, 20 do
							shockwave.Transparency = shockwave.Transparency + .05
							shockwavemesh.Scale = shockwavemesh.Scale + Vector3.new(.5,0,.5)
							swait()
						end
						shockwave:Remove()
					end)()
					coroutine.wrap(function()
						local shockwave = Instance.new("Part", Torso)
						shockwave.Size = Vector3.new(1,1,1)
						shockwave.CanCollide = false
						shockwave.Anchored = true
						shockwave.Transparency = .4
						shockwave.BrickColor = BrickColor.new("Really black")
						shockwave.CFrame = CFrame.new(Root.Position) * CFrame.new(0,-8,0)
						local shockwavemesh = Instance.new("SpecialMesh", shockwave)
						shockwavemesh.Scale = Vector3.new(10,1,10)
						shockwavemesh.MeshId = "rbxassetid://20329976"
						local shockwave2 = Instance.new("Part", Torso)
						shockwave2.Size = Vector3.new(1,1,1)
						shockwave2.CanCollide = false
						shockwave2.Anchored = true
						shockwave2.Transparency = .4
						shockwave2.BrickColor = BrickColor.new("Really black")
						shockwave2.CFrame = CFrame.new(Root.Position) * CFrame.new(0,-8,0)
						local shockwavemesh2 = Instance.new("SpecialMesh", shockwave2)
						shockwavemesh2.Scale = Vector3.new(1,1,1)
						shockwavemesh2.MeshId = "rbxassetid://20329976"
						for i = 1, 30 do
							shockwave.CFrame = shockwave.CFrame * CFrame.Angles(math.rad(0),math.rad(0+math.random(-4,12)),0)
							shockwave2.CFrame = shockwave2.CFrame * CFrame.Angles(math.rad(0),math.rad(0-math.random(-4,12)),0)
							shockwave.Transparency = shockwave.Transparency + 0.05
							shockwave2.Transparency = shockwave2.Transparency + 0.05
							shockwavemesh2.Scale = shockwavemesh2.Scale + Vector3.new(8,1,8)
							shockwavemesh.Scale = shockwavemesh.Scale + Vector3.new(10,.5,10)
							swait()
						end
						shockwave:Remove()
						shockwave2:Remove()
					end)()
					energball.Size = energball.Size + Vector3.new(.02,.02,.02)
					energball.CFrame = hand1.CFrame * CFrame.new(0,0,-3)
					HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(6.5,0,-1) * CFrame.Angles(math.rad(70),math.rad(90),math.rad(0)),.2)
					HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(6.5,0,-5) * CFrame.Angles(math.rad(-110),math.rad(90),math.rad(0)),.2)
					swait()
				end
				local bwoo = Instance.new("Sound",Torso)
				bwoo.SoundId = "rbxassetid://134012322"
				bwoo.Volume = 10
				bwoo.Pitch = .85
				bwoo:Play()
				removeuseless:AddItem(bwoo,10)
				for i = 1, 20 do
					g1.CFrame = g1.CFrame:lerp(CFrame.new(Root.Position,mouse.Hit.p),.2)
					energball.CFrame = hand2.CFrame * CFrame.new(0,0,-3)
					ROOTLERP.C0 = ROOTLERP.C0:lerp(CFrame.new(0,0,0) * CFrame.Angles(math.rad(0),math.rad(-35),0),.2)
					HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(4.5,-5 + .5 * math.sin(sine/14),6) * CFrame.Angles(math.rad(10 + 1 * math.sin(sine/13)),math.rad(-5 + 5 * math.sin(sine/12)),math.rad(-36 - 4 * math.sin(sine/11))),.2)
					HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(-4.5,0,7) * CFrame.Angles(math.rad(-90),math.rad(18),math.rad(37)),.2)
					swait()
				end
				energball.Anchored = false
				local bov = Instance.new("BodyVelocity",energball)
				bov.maxForce = Vector3.new(99999,99999,99999)
				energball.CFrame = CFrame.new(energball.Position,mouse.Hit.p)
				bov.velocity = energball.CFrame.lookVector*300
				local hitted = false
				energball.Touched:connect(function(hit)
					if hit:IsA("Part") and hit.Parent ~= Character and hit.Name ~= "rachjumper" and hit.Parent.Parent ~= Character then
						if hitted then return end
						hitted = true
						print("hit")
						energball.Anchored = true
						local energballplosion = energball:Clone() energballplosion.Parent = Torso
						energball.Transparency = 1
						local render = Instance.new("Sound",energball)
						render.SoundId = "rbxassetid://2006635781"
						render.Volume = 10 * 10
						render:Play()
						local zm = 0
						for i = 1, 70 do
							zm = zm + 2
							Hit = damagealll(zm,energball.Position)
							for _,v in pairs(Hit) do
								if v:FindFirstChildOfClass("Humanoid") and v:FindFirstChildOfClass("Humanoid").Health > 0 then
									slachtoffer = v:FindFirstChildOfClass("Humanoid")
									coroutine.wrap(function()
										local w = Instance.new("Part",Torso)
										w.Anchored = true
										w.CanCollide = false
										w.Material = "Neon"
										w.BrickColor = BrickColor.new("Really black")
										if slachtoffer.RigType == Enum.HumanoidRigType.R15 then
											w.CFrame = slachtoffer.Parent:FindFirstChild("UpperTorso").CFrame
										elseif slachtoffer.RigType == Enum.HumanoidRigType.R6 then
											w.CFrame = slachtoffer.Parent:FindFirstChild("Torso").CFrame
										end
										w.Size = Vector3.new(3,3,3)
										w.Shape = "Ball"
										for i = 1, 50 do
											w.Transparency = w.Transparency + .05
											w.Size = w.Size + Vector3.new(3.5,3.5,3.5)
											swait()
										end
										w:Remove()
									end)()
									for i = 1, 8 do
										coroutine.wrap(function()
											local ps = Instance.new("Part",Torso)
											ps.Size = Vector3.new(1,1,1)
											ps.Anchored = true
											ps.BrickColor = BrickColor.new("Really black")
											ps.Material = "Neon"
											if slachtoffer.RigType == Enum.HumanoidRigType.R6 then
												ps.CFrame = slachtoffer.Parent:FindFirstChild("Torso").CFrame * CFrame.Angles(math.rad(math.random(-180,180)),math.rad(math.random(-180,180)),math.rad(math.random(-180,180)))
											elseif slachtoffer.RigType == Enum.HumanoidRigType.R15 then
												ps.CFrame = slachtoffer.Parent:FindFirstChild("UpperTorso").CFrame * CFrame.Angles(math.rad(math.random(-180,180)),math.rad(math.random(-180,180)),math.rad(math.random(-180,180)))
											end
											local psm = Instance.new("SpecialMesh",ps)
											psm.MeshType = "Sphere"
											psm.Scale = Vector3.new(3,1,3)
											for i = 1, 50 do
												psm.Scale = psm.Scale + Vector3.new(0,5,0)
												ps.Transparency = ps.Transparency + .025
												swait()
											end
											ps:Remove()
										end)()
									end
									for i,x in pairs(slachtoffer.Parent:GetDescendants()) do if x:IsA("Part") then x:Clone() x.Parent = workspace x.Material = "Glass" x.BrickColor = BrickColor.new("Really black") x.Anchored = false
											x.CanCollide = true x:BreakJoints() end end
									for i,x in pairs(slachtoffer.Parent:GetDescendants()) do if x:IsA("Part") then x:Remove() end end
									slachtoffer.Parent:BreakJoints()
								end
							end
							coroutine.wrap(function()
								local shockwave = Instance.new("Part", Torso)
								shockwave.Size = Vector3.new(1,1,1)
								shockwave.CanCollide = false
								shockwave.Anchored = true
								shockwave.Transparency = .4
								shockwave.BrickColor = BrickColor.new("Really black")
								shockwave.CFrame = CFrame.new(energballplosion.Position) * CFrame.new(0,-8,0)
								local shockwavemesh = Instance.new("SpecialMesh", shockwave)
								shockwavemesh.Scale = Vector3.new(10,2,10)
								shockwavemesh.MeshId = "rbxassetid://20329976"
								local shockwave2 = Instance.new("Part", Torso)
								shockwave2.Size = Vector3.new(1,1,1)
								shockwave2.CanCollide = false
								shockwave2.Anchored = true
								shockwave2.Transparency = .4
								shockwave2.BrickColor = BrickColor.new("Really black")
								shockwave2.CFrame = CFrame.new(energballplosion.Position) * CFrame.new(0,-8,0)
								local shockwavemesh2 = Instance.new("SpecialMesh", shockwave2)
								shockwavemesh2.Scale = Vector3.new(11,2,11)
								shockwavemesh2.MeshId = "rbxassetid://20329976"
								local biggar = 0
								for i = 1, 30 do
									biggar = biggar + 4
									shockwave.CFrame = shockwave.CFrame * CFrame.Angles(math.rad(0),math.rad(0+math.random(-4,12)),0)
									shockwave2.CFrame = shockwave2.CFrame * CFrame.Angles(math.rad(0),math.rad(0-math.random(-4,12)),0)
									shockwave.Transparency = shockwave.Transparency + 0.05
									shockwave2.Transparency = shockwave2.Transparency + 0.05
									shockwavemesh2.Scale = shockwavemesh2.Scale + Vector3.new(8 + biggar,4,8 + biggar)
									shockwavemesh.Scale = shockwavemesh.Scale + Vector3.new(10 + biggar,4,10 + biggar)
									swait()
								end
								shockwave:Remove()
								shockwave2:Remove()
							end)()
							energballplosion.Size = energballplosion.Size + Vector3.new(2,2,2)
							swait()
						end
						for i = 1, 80 do
							zm = zm + 3.5
							Hit = damagealll(zm,energball.Position)
							for _,v in pairs(Hit) do
								if v:FindFirstChildOfClass("Humanoid") and v:FindFirstChildOfClass("Humanoid").Health > 0 then
									slachtoffer = v:FindFirstChildOfClass("Humanoid")
									coroutine.wrap(function()
										local w = Instance.new("Part",Torso)
										w.Anchored = true
										w.CanCollide = false
										w.Material = "Neon"
										w.BrickColor = BrickColor.new("Really black")
										if slachtoffer.RigType == Enum.HumanoidRigType.R15 then
											w.CFrame = slachtoffer.Parent:FindFirstChild("UpperTorso").CFrame
										elseif slachtoffer.RigType == Enum.HumanoidRigType.R6 then
											w.CFrame = slachtoffer.Parent:FindFirstChild("Torso").CFrame
										end
										w.Size = Vector3.new(3,3,3)
										w.Shape = "Ball"
										for i = 1, 50 do
											w.Transparency = w.Transparency + .05
											w.Size = w.Size + Vector3.new(3.5,3.5,3.5)
											swait()
										end
										w:Remove()
									end)()
									for i = 1, 8 do
										coroutine.wrap(function()
											local ps = Instance.new("Part",Torso)
											ps.Size = Vector3.new(1,1,1)
											ps.Anchored = true
											ps.BrickColor = BrickColor.new("Really black")
											ps.Material = "Neon"
											if slachtoffer.RigType == Enum.HumanoidRigType.R6 then
												ps.CFrame = slachtoffer.Parent:FindFirstChild("Torso").CFrame * CFrame.Angles(math.rad(math.random(-180,180)),math.rad(math.random(-180,180)),math.rad(math.random(-180,180)))
											elseif slachtoffer.RigType == Enum.HumanoidRigType.R15 then
												ps.CFrame = slachtoffer.Parent:FindFirstChild("UpperTorso").CFrame * CFrame.Angles(math.rad(math.random(-180,180)),math.rad(math.random(-180,180)),math.rad(math.random(-180,180)))
											end
											local psm = Instance.new("SpecialMesh",ps)
											psm.MeshType = "Sphere"
											psm.Scale = Vector3.new(3,1,3)
											for i = 1, 50 do
												psm.Scale = psm.Scale + Vector3.new(0,5,0)
												ps.Transparency = ps.Transparency + .025
												swait()
											end
											ps:Remove()
										end)()
									end
									for i,x in pairs(slachtoffer.Parent:GetDescendants()) do if x:IsA("Part") then x:Clone() x.Parent = workspace x.Material = "Glass" x.BrickColor = BrickColor.new("Really black") x.Anchored = false
											x.CanCollide = true x:BreakJoints() end end
									for i,x in pairs(slachtoffer.Parent:GetDescendants()) do if x:IsA("Part") then x:Remove() end end
									slachtoffer.Parent:BreakJoints()
								end
							end
							coroutine.wrap(function()
								local shockwave = Instance.new("Part", Torso)
								shockwave.Size = Vector3.new(1,1,1)
								shockwave.CanCollide = false
								shockwave.Anchored = true
								shockwave.Transparency = .4
								shockwave.BrickColor = BrickColor.new("Really black")
								shockwave.CFrame = CFrame.new(energballplosion.Position) * CFrame.new(0,-8,0)
								local shockwavemesh = Instance.new("SpecialMesh", shockwave)
								shockwavemesh.Scale = Vector3.new(10,6,10)
								shockwavemesh.MeshId = "rbxassetid://20329976"
								local shockwave2 = Instance.new("Part", Torso)
								shockwave2.Size = Vector3.new(1,1,1)
								shockwave2.CanCollide = false
								shockwave2.Anchored = true
								shockwave2.Transparency = .4
								shockwave2.BrickColor = BrickColor.new("Really black")
								shockwave2.CFrame = CFrame.new(energballplosion.Position) * CFrame.new(0,-8,0)
								local shockwavemesh2 = Instance.new("SpecialMesh", shockwave2)
								shockwavemesh2.Scale = Vector3.new(11,6,11)
								shockwavemesh2.MeshId = "rbxassetid://20329976"
								local biggar = 0
								local biggar2 = 0
								for i = 1, 30 do
									biggar = biggar + 14
									biggar2 = biggar2 + 22
									shockwave.CFrame = shockwave.CFrame * CFrame.Angles(math.rad(0),math.rad(0+math.random(-4,12)),0)
									shockwave2.CFrame = shockwave2.CFrame * CFrame.Angles(math.rad(0),math.rad(0-math.random(-4,12)),0)
									shockwave.Transparency = shockwave.Transparency + 0.05
									shockwave2.Transparency = shockwave2.Transparency + 0.05
									shockwavemesh2.Scale = shockwavemesh2.Scale + Vector3.new(16 + biggar,12 + biggar,16 + biggar)
									shockwavemesh.Scale = shockwavemesh.Scale + Vector3.new(18 + biggar2,12,18 + biggar2)
									swait()
								end
								shockwave:Remove()
								shockwave2:Remove()
							end)()
							energballplosion.Size = energballplosion.Size + Vector3.new(7,7,7)
							swait()
						end
						for i = 1, 50 do
							energballplosion.Size = energballplosion.Size + Vector3.new(5,5,5)
							energballplosion.Transparency = energballplosion.Transparency + .025
							swait()
						end
						energballplosion:Remove()
					end
				end)
				for i = 1, 20 do
					HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(6,-5 + .5 * math.sin(sine/14),6) * CFrame.Angles(math.rad(20 + 1 * math.sin(sine/13)),math.rad(-5 + 5 * math.sin(sine/12)),math.rad(-36 - 4 * math.sin(sine/11))),.2)
					HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(-5.5,0,5) * CFrame.Angles(math.rad(30),math.rad(-28),math.rad(37)),.2)
					ROOTLERP.C0 = ROOTLERP.C0:lerp(CFrame.new(0,0,0) * CFrame.Angles(math.rad(0),math.rad(35),0),.2)
					swait()
				end
				removeuseless:AddItem(g1,.001)
				debounce = false
				if xester then
					ws = 155
				else
					ws = 92
				end
				attacking = false
			end
		elseif Press=='x' then
			if debounce then return end
			debounce = true
			attacking = true
			ws = 0
			for i = 1, 70 do
				ROOTLERP.C0 = ROOTLERP.C0:lerp(CFrame.new(0,0,0) * CFrame.Angles(math.rad(-50),math.rad(0 * math.sin(sine/16)),math.rad(0)),.1)
				HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(-2,-2,-4) * CFrame.Angles(math.rad(-50 + 2 * math.sin(sine)),math.rad(180 + 1 * math.sin(sine)),math.rad(30 + 2 * math.sin(sine))),.1)
				HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(2,-2,-4) * CFrame.Angles(math.rad(-50 + 2 * math.sin(sine)),math.rad(180 - 1 * math.sin(sine)),math.rad(-30 - 2 * math.sin(sine))),.1)
				swait()
			end
			for i = 1, 40 do
				ROOTLERP.C0 = ROOTLERP.C0:lerp(CFrame.new(0,0,0) * CFrame.Angles(math.rad(-50),math.rad(0 * math.sin(sine/16)),math.rad(0)),.05)
				HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(-2,-2,-4) * CFrame.Angles(math.rad(-50 + 4 * math.sin(sine)),math.rad(180 + 2 * math.sin(sine)),math.rad(30 + 4 * math.sin(sine))),.05)
				HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(2,-2,-4) * CFrame.Angles(math.rad(-50 + 4 * math.sin(sine)),math.rad(180 - 2 * math.sin(sine)),math.rad(-30 - 4 * math.sin(sine))),.05)
				swait()
			end
			rachjumper = true
			xester = false
			doomtheme.Volume = 0
			coroutine.wrap(function()
				local shockwave = Instance.new("Part", Torso)
				shockwave.Size = Vector3.new(1,1,1)
				shockwave.CanCollide = false
				shockwave.Anchored = true
				shockwave.Transparency = .2
				shockwave.BrickColor = BrickColor.new("Really red")
				shockwave.CFrame = CFrame.new(Root.Position) * CFrame.new(0,-8,0)
				local shockwavemesh = Instance.new("SpecialMesh", shockwave)
				shockwavemesh.Scale = Vector3.new(10,1,10)
				shockwavemesh.MeshId = "rbxassetid://20329976"
				local shockwave2 = Instance.new("Part", Torso)
				shockwave2.Size = Vector3.new(1,1,1)
				shockwave2.CanCollide = false
				shockwave2.Anchored = true
				shockwave2.Transparency = .2
				shockwave2.BrickColor = BrickColor.new("Really red")
				shockwave2.CFrame = CFrame.new(Root.Position) * CFrame.new(0,-8,0)
				local shockwavemesh2 = Instance.new("SpecialMesh", shockwave2)
				shockwavemesh2.Scale = Vector3.new(1,1,1)
				shockwavemesh2.MeshId = "rbxassetid://20329976"
				for i = 1, 30 do
					shockwave.CFrame = shockwave.CFrame * CFrame.Angles(math.rad(0),math.rad(0+16),0)
					shockwave2.CFrame = shockwave2.CFrame * CFrame.Angles(math.rad(0),math.rad(0-16),0)
					shockwave.Transparency = shockwave.Transparency + 0.05
					shockwave2.Transparency = shockwave2.Transparency + 0.05
					shockwavemesh2.Scale = shockwavemesh2.Scale + Vector3.new(10,1,10)
					shockwavemesh.Scale = shockwavemesh.Scale + Vector3.new(14,2,14)
					swait()
				end
				shockwave:Remove()
				shockwave2:Remove()
			end)()
			coroutine.wrap(function()
				local nball = Instance.new("Part",Torso)
				nball.Size = Vector3.new(4,4,4)
				nball.Material = "Neon"
				nball.BrickColor = BrickColor.new("Really red")
				nball.Shape = "Ball"
				nball.Anchored = true
				nball.CanCollide = false
				nball.CFrame = Torso.CFrame
				for i = 1, 40 do
					nball.Size = nball.Size + Vector3.new(5.5,5.5,5.5)
					nball.Transparency = nball.Transparency + .05
					swait()
				end
				nball:Remove()
			end)()
			particlecolor = ColorSequence.new(Color3.new(255, 255, 255))

			particlemiter1 = Instance.new("ParticleEmitter", bighead)
			particlemiter1.Enabled = true
			particlemiter1.Color = particlecolor
			particlemiter1.Texture = "rbxassetid://1390780157"
			particlemiter1.Lifetime = NumberRange.new(.05)
			particlemiter1.Size = NumberSequence.new(7.5,7.5)
			particlemiter1.Rate = 4
			particlemiter1.Rotation = NumberRange.new(0,360)
			particlemiter1.RotSpeed = NumberRange.new(0)
			particlemiter1.Speed = NumberRange.new(0)

			particlemiter2 = Instance.new("ParticleEmitter", hand1)
			particlemiter2.Enabled = true
			particlemiter2.Color = particlecolor
			particlemiter2.Texture = "rbxassetid://1390780157"
			particlemiter2.Lifetime = NumberRange.new(.05)
			particlemiter2.Size = NumberSequence.new(5,5)
			particlemiter2.Rate = 4
			particlemiter2.Rotation = NumberRange.new(0,360)
			particlemiter2.RotSpeed = NumberRange.new(0)
			particlemiter2.Speed = NumberRange.new(0)

			particlemiter3 = Instance.new("ParticleEmitter", hand2)
			particlemiter3.Enabled = true
			particlemiter3.Color = particlecolor
			particlemiter3.Texture = "rbxassetid://1390780157"
			particlemiter3.Lifetime = NumberRange.new(.05)
			particlemiter3.Size = NumberSequence.new(5,5)
			particlemiter3.Rate = 4
			particlemiter3.Rotation = NumberRange.new(0,360)
			particlemiter3.RotSpeed = NumberRange.new(0)
			particlemiter3.Speed = NumberRange.new(0)
			coroutine.wrap(function()
				transformsound = Instance.new("Sound",Torso)
				transformsound.Volume = 10
				transformsound.SoundId = "rbxassetid://159576182"
				transformsound:Play() 
				coroutine.wrap(function()
					wait(1)
					realmofexistence = Instance.new("Sound",Torso)
					realmofexistence.Volume = 8
					realmofexistence.SoundId = "rbxassetid://2565721367"
					realmofexistence:Play()
				end)()
				wait(2.2)
				doomtheme.SoundId = "rbxassetid://2902017580"
				doomtheme:Play()
				doomtheme.Pitch = 1
				doomtheme.TimePosition = 0
				for i = 1, 30 do
					doomtheme.Volume = doomtheme.Volume + .25
					swait()
				end
			end)()

			slaten.Transparency = 1
			slaten2.Transparency = 1
			slateh.Transparency = 1
			slateh2.Transparency = 1
			slateh3.Transparency = 1
			slateh4.Transparency = 1
			slateh5.Transparency = 1
			slatex.Transparency = 1
			slatex2.Transparency = 1
			slatex3.Transparency = 1
			slatex4.Transparency = 1
			slatex5.Transparency = 1
			slatez.Transparency = 1
			slatez2.Transparency = 1
			slatez3.Transparency = 1
			slatez4.Transparency = 1
			eyeball1.Transparency = 1
			eyeball2.Transparency = 1
			eyeball3.Transparency = 1
			eyeball4.Transparency = 1
			lightpart1.Transparency = 1
			Root.Anchored = false
			horns.Material = "Slate"
			horns.Locked = true
			horns.BrickColor = BrickColor.new("Really black")
			hornsmesh.MeshId = "rbxassetid://398618628"
			hornsmesh.VertexColor = Vector3.new(1,0,0)
			hornsmesh.TextureId = "rbxassetid://1461382301"
			hornsmesh.Scale = Vector3.new(4.9, 5.5, 5.8)
			hornsweld.C0 = CFrame.new(0,3.8,-4.5) * CFrame.Angles(math.rad(0),math.rad(0),0)
			mask.Anchored = false
			mask.Locked = true
			mask.CanCollide = false
			mask.Transparency = 0
			mask.BrickColor = BrickColor.new("White")
			mask.Material = "Corroded Metal"
			maskweld.C0 = CFrame.new(0,1.45,-.4) * CFrame.Angles(math.rad(0),0,0)
			maskmesh.MeshId = "rbxassetid://64560176"
			maskmesh.TextureId = "rbxassetid://1326186614"
			maskmesh.Scale = Vector3.new(5.04, 5.04, 5.04)
			hand2.BrickColor = BrickColor.new("Really black")
			hand1.BrickColor = BrickColor.new("Really black")
			face = Instance.new("Decal",bighead)
			face.Texture = "rbxassetid://1127768638"
			face.Color3 = Color3.new(255, 255, 255)
			face.Face = "Front"
			attacking = false
			ws = 92
			debounce = false
		elseif Press=='z' then
			if debounce then return end
			debounce = true
			attacking = true
			ws = 0
			for i = 1, 70 do
				ROOTLERP.C0 = ROOTLERP.C0:lerp(CFrame.new(0,0,0) * CFrame.Angles(math.rad(-50),math.rad(0 * math.sin(sine/16)),math.rad(0)),.1)
				HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(-2,-2,-4) * CFrame.Angles(math.rad(-50 + 2 * math.sin(sine)),math.rad(180 + 1 * math.sin(sine)),math.rad(30 + 2 * math.sin(sine))),.1)
				HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(2,-2,-4) * CFrame.Angles(math.rad(-50 + 2 * math.sin(sine)),math.rad(180 - 1 * math.sin(sine)),math.rad(-30 - 2 * math.sin(sine))),.1)
				swait()
			end
			for i = 1, 40 do
				ROOTLERP.C0 = ROOTLERP.C0:lerp(CFrame.new(0,0,0) * CFrame.Angles(math.rad(-50),math.rad(0 * math.sin(sine/16)),math.rad(0)),.05)
				HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(-2,-2,-4) * CFrame.Angles(math.rad(-50 + 4 * math.sin(sine)),math.rad(180 + 2 * math.sin(sine)),math.rad(30 + 4 * math.sin(sine))),.05)
				HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(2,-2,-4) * CFrame.Angles(math.rad(-50 + 4 * math.sin(sine)),math.rad(180 - 2 * math.sin(sine)),math.rad(-30 - 4 * math.sin(sine))),.05)
				swait()
			end
			if rachjumper then
				face:Remove()
				particlemiter1:Remove()
				particlemiter2:Remove()
				particlemiter3:Remove()
			end
			xester = true
			rachjumper = false
			hand1.BrickColor = BrickColor.new("White")
			hand2.BrickColor = BrickColor.new("White")
			coroutine.wrap(function()
				local shockwave = Instance.new("Part", Torso)
				shockwave.Size = Vector3.new(1,1,1)
				shockwave.CanCollide = false
				shockwave.Anchored = true
				shockwave.Transparency = .2
				shockwave.BrickColor = BrickColor.new("White")
				shockwave.CFrame = CFrame.new(Root.Position) * CFrame.new(0,-8,0)
				local shockwavemesh = Instance.new("SpecialMesh", shockwave)
				shockwavemesh.Scale = Vector3.new(10,1,10)
				shockwavemesh.MeshId = "rbxassetid://20329976"
				local shockwave2 = Instance.new("Part", Torso)
				shockwave2.Size = Vector3.new(1,1,1)
				shockwave2.CanCollide = false
				shockwave2.Anchored = true
				shockwave2.Transparency = .2
				shockwave2.BrickColor = BrickColor.new("White")
				shockwave2.CFrame = CFrame.new(Root.Position) * CFrame.new(0,-8,0)
				local shockwavemesh2 = Instance.new("SpecialMesh", shockwave2)
				shockwavemesh2.Scale = Vector3.new(1,1,1)
				shockwavemesh2.MeshId = "rbxassetid://20329976"
				for i = 1, 30 do
					shockwave.CFrame = shockwave.CFrame * CFrame.Angles(math.rad(0),math.rad(0+16),0)
					shockwave2.CFrame = shockwave2.CFrame * CFrame.Angles(math.rad(0),math.rad(0-16),0)
					shockwave.Transparency = shockwave.Transparency + 0.05
					shockwave2.Transparency = shockwave2.Transparency + 0.05
					shockwavemesh2.Scale = shockwavemesh2.Scale + Vector3.new(10,1,10)
					shockwavemesh.Scale = shockwavemesh.Scale + Vector3.new(14,2,14)
					swait()
				end
				shockwave:Remove()
				shockwave2:Remove()
			end)()
			coroutine.wrap(function()
				local nball = Instance.new("Part",Torso)
				nball.Size = Vector3.new(4,4,4)
				nball.Material = "Neon"
				nball.BrickColor = BrickColor.new("White")
				nball.Shape = "Ball"
				nball.Anchored = true
				nball.CanCollide = false
				nball.CFrame = Torso.CFrame
				for i = 1, 40 do
					nball.Size = nball.Size + Vector3.new(5.5,5.5,5.5)
					nball.Transparency = nball.Transparency + .05
					swait()
				end
				nball:Remove()
			end)()
			doomtheme.SoundId = "rbxassetid://1382488262"
			doomtheme:Play()
			doomtheme.Volume = 6
			doomtheme.Pitch = 1
			doomtheme.TimePosition = 20.7
			slaten.Transparency = 1
			slaten2.Transparency = 1
			slateh.Transparency = 1
			slateh2.Transparency = 1
			slateh3.Transparency = 1
			slateh4.Transparency = 1
			slateh5.Transparency = 1
			slatex.Transparency = 1
			slatex2.Transparency = 1
			slatex3.Transparency = 1
			slatex4.Transparency = 1
			slatex5.Transparency = 1
			slatez.Transparency = 1
			slatez2.Transparency = 1
			slatez3.Transparency = 1
			slatez4.Transparency = 1
			eyeball1.Transparency = 1
			eyeball2.Transparency = 1
			eyeball3.Transparency = 1
			eyeball4.Transparency = 1
			lightpart1.Transparency = 0
			laugh = laughs[math.random(1,#laughs)]
			local laughy = Instance.new("Sound",Head)
			laughy.SoundId = "rbxassetid://"..laugh
			laughy.Volume = 10
			laughy:Play()
			removeuseless:AddItem(laughy,10)
			Root.Anchored = false
			horns.Material = "Slate"
			horns.Locked = true
			horns.BrickColor = BrickColor.new("Really black")
			hornsmesh.MeshId = "rbxassetid://193760002"
			hornsmesh.VertexColor = Vector3.new(1,0,0)
			hornsmesh.TextureId = "rbxassetid://379225327"
			hornsmesh.Scale = Vector3.new(5.41,5.41,5.41)
			hornsweld.C0 = CFrame.new(0,-2.75,-1.7) * CFrame.Angles(math.rad(0),math.rad(0),math.rad(0))
			mask.Anchored = false
			mask.Locked = true
			mask.CanCollide = false
			mask.BrickColor = BrickColor.new("White")
			mask.Material = "Corroded Metal"
			maskweld.C0 = CFrame.new(0,0,2.5) * CFrame.Angles(math.rad(0),0,0)
			maskmesh.MeshId = "rbxassetid://13520257"
			maskmesh.TextureId = "rbxassetid://13520260"
			maskmesh.Scale = Vector3.new(5.53, 5, 5.1)
			for i = 1, 30 do
				ROOTLERP.C0 = ROOTLERP.C0:lerp(CFrame.new(0,0,0) * CFrame.Angles(math.rad(30),math.rad(0 * math.sin(sine/16)),math.rad(0)),.1)
				swait()
			end
			for i = 1, 50 do
				HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(2,-2,-4) * CFrame.Angles(math.rad(-140 + 2 * math.sin(sine)),math.rad(180 - 1 * math.sin(sine)),math.rad(-30 - 2 * math.sin(sine))),.03)
				HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(-2,-2,-4) * CFrame.Angles(math.rad(-140 + 2 * math.sin(sine)),math.rad(180 + 1 * math.sin(sine)),math.rad(30 + 2 * math.sin(sine))),.03)
				swait()
			end
			for i = 1, 50 do
				HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(2,-2,-4) * CFrame.Angles(math.rad(-140 + 8 * math.sin(sine)),math.rad(180 - 5 * math.sin(sine)),math.rad(-30 - 8 * math.sin(sine))),.03)
				HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(-2,-2,-4) * CFrame.Angles(math.rad(-140 + 8 * math.sin(sine)),math.rad(180 + 5 * math.sin(sine)),math.rad(30 + 8 * math.sin(sine))),.03)
				swait()
			end
			ws = 155
			Root.Anchored = false
			debounce = false
			attacking = false
			xester = true
		elseif Press=='r' then
			if mouse.Target ~= nil and mouse.Target.Parent:FindFirstChildOfClass("Humanoid") then
				if debounce then return end
				debounce = true
				attacking = true
				local enemy = mouse.Target.Parent:FindFirstChildOfClass("Humanoid")
				local targ = mouse.Target.Parent:FindFirstChildOfClass("Humanoid").Parent
				SOUND(Head,1837106999,10,false,10)
				ws = 0
				local z = { 
					Color = BrickColor.new("Crimson").Color
				}
				local z2 = { 
					Color = BrickColor.new("Really black").Color
				}
				eyeball1.Material = "Neon"
				eyeball2.Material = "Neon"
				for i = 1, 7 do
					local lol = smoothen:Create(eyeball1,TweenInfo.new(.3,Enum.EasingStyle.Linear),z)
					lol:Play()
					local lol2 = smoothen:Create(eyeball2,TweenInfo.new(.3,Enum.EasingStyle.Linear),z)
					lol2:Play()
					HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(-2,-2,-4) * CFrame.Angles(math.rad(-50),math.rad(180),math.rad(10)),.2)
					HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(2,-2,-4) * CFrame.Angles(math.rad(-50),math.rad(180),math.rad(-10)),.2)
					swait()
				end
				for i = 1, 70 do
					local lol = smoothen:Create(eyeball1,TweenInfo.new(.3,Enum.EasingStyle.Linear),z)
					lol:Play()
					local lol2 = smoothen:Create(eyeball2,TweenInfo.new(.3,Enum.EasingStyle.Linear),z)
					lol2:Play()
					ROOTLERP.C0 = ROOTLERP.C0:lerp(CFrame.new(0,0,0) * CFrame.Angles(math.rad(-50),math.rad(0 * math.sin(sine/16)),math.rad(0)),.05)
					HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(-2,-2,-4) * CFrame.Angles(math.rad(-50 + 2 * math.sin(sine)),math.rad(180 + 1 * math.sin(sine)),math.rad(30 + 2 * math.sin(sine))),.05)
					HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(2,-2,-4) * CFrame.Angles(math.rad(-50 + 2 * math.sin(sine)),math.rad(180 - 1 * math.sin(sine)),math.rad(-30 - 2 * math.sin(sine))),.05)
					swait()
				end
				for i = 1, 40 do
					local lol = smoothen:Create(eyeball1,TweenInfo.new(.3,Enum.EasingStyle.Linear),z)
					lol:Play()
					local lol2 = smoothen:Create(eyeball2,TweenInfo.new(.3,Enum.EasingStyle.Linear),z)
					lol2:Play()
					ROOTLERP.C0 = ROOTLERP.C0:lerp(CFrame.new(0,0,0) * CFrame.Angles(math.rad(-50),math.rad(0 * math.sin(sine/16)),math.rad(0)),.05)
					HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(-2,-2,-4) * CFrame.Angles(math.rad(-50 + 4 * math.sin(sine)),math.rad(180 + 2 * math.sin(sine)),math.rad(30 + 4 * math.sin(sine))),.05)
					HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(2,-2,-4) * CFrame.Angles(math.rad(-50 + 4 * math.sin(sine)),math.rad(180 - 2 * math.sin(sine)),math.rad(-30 - 4 * math.sin(sine))),.05)
					swait()
				end
				attacking = false
				local targetfound = false
				local chasemusic = Instance.new("Sound",Head)
				chasemusic.Volume = 10
				chasemusic.SoundId = "rbxassetid://2866313732"
				chasemusic.Looped = true
				chasemusic:Play()
				for i = 1, 1000 do
					if targetfound then break end
					local Hit = damagealll(15,Torso.Position)
					for _,v in pairs(Hit) do
						if v:FindFirstChildOfClass("Humanoid") and v:FindFirstChildOfClass("Humanoid").Parent.Name == enemy.Parent.Name then
							targetfound = true
							slachtoffer = v:FindFirstChildOfClass("Humanoid")
						end
					end
					huntdown = true
					hum:MoveTo(enemy.Parent.Torso.Position)
					ws = 150
					swait()
				end
				if targetfound then
					attacking = true
					local lweld = weldBetween(enemy.Parent.Torso,hand1)
					lweld.C0 = CFrame.new(2,-2,0) * CFrame.Angles(math.rad(0),math.rad(90),math.rad(90))
					ws = 0
					enemy.WalkSpeed = 0
					enemy.JumpPower = 0
					local IAMHERE = Instance.new("Sound",Head)
					IAMHERE.SoundId = "rbxassetid://2867055627"
					IAMHERE.Volume = 10
					IAMHERE:Play()
					removeuseless:AddItem(IAMHERE,10)
					for i = 1, 220 do
						ROOTLERP.C0 = ROOTLERP.C0:lerp(CFrame.new(0,0,0) * CFrame.Angles(math.rad(-10),math.rad(0 * math.sin(sine/16)),math.rad(0)),.05)
						HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(2,-7.5,-2.2) * CFrame.Angles(math.rad(90 + 2 * math.sin(sine)),math.rad(2 * math.sin(sine)),math.rad(-80 + 2 * math.sin(sine))),.2)
						HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(-2,-7.5,-2.2) * CFrame.Angles(math.rad(90 - 2 * math.sin(sine)),math.rad(2 * math.sin(sine)),math.rad(80 - 2 * math.sin(sine))),.2)
						swait()
					end
					lweld:Remove()
					coroutine.wrap(function()
						local w = Instance.new("Part",Torso)
						w.Anchored = true
						w.CanCollide = false
						w.Material = "Neon"
						w.BrickColor = BrickColor.new("Really black")
						if targ:FindFirstChildOfClass("Humanoid").RigType == Enum.HumanoidRigType.R15 then
							w.CFrame = targ:FindFirstChild("UpperTorso").CFrame
						elseif targ:FindFirstChildOfClass("Humanoid").RigType == Enum.HumanoidRigType.R6 then
							w.CFrame = targ:FindFirstChild("Torso").CFrame
						end
						w.Size = Vector3.new(3,3,3)
						w.Shape = "Ball"
						for i = 1, 50 do
							w.Transparency = w.Transparency + .05
							w.Size = w.Size + Vector3.new(3.5,3.5,3.5)
							swait()
						end
						w:Remove()
					end)()
					for i = 1, 8 do
						coroutine.wrap(function()
							local ps = Instance.new("Part",Torso)
							ps.Size = Vector3.new(1,1,1)
							ps.Anchored = true
							ps.BrickColor = BrickColor.new("Really black")
							ps.Material = "Neon"
							if targ:FindFirstChildOfClass("Humanoid").RigType == Enum.HumanoidRigType.R15 then
								ps.CFrame = targ:FindFirstChild("UpperTorso").CFrame * CFrame.Angles(math.rad(math.random(-180,180)),math.rad(math.random(-180,180)),math.rad(math.random(-180,180)))
							elseif targ:FindFirstChildOfClass("Humanoid").RigType == Enum.HumanoidRigType.R6 then
								ps.CFrame = targ:FindFirstChild("Torso").CFrame * CFrame.Angles(math.rad(math.random(-180,180)),math.rad(math.random(-180,180)),math.rad(math.random(-180,180)))
							end
							local psm = Instance.new("SpecialMesh",ps)
							psm.MeshType = "Sphere"
							psm.Scale = Vector3.new(3,1,3)
							for i = 1, 50 do
								psm.Scale = psm.Scale + Vector3.new(0,5,0)
								ps.Transparency = ps.Transparency + .025
								swait()
							end
							ps:Remove()
						end)()
					end
					for i,x in pairs(targ:GetDescendants()) do if x:IsA("Part") then x:Clone() x.Parent = workspace x.Material = "Glass" x.BrickColor = BrickColor.new("Really black") x.Anchored = false
							x.CanCollide = true x:BreakJoints() end end
					for i,x in pairs(targ:GetDescendants()) do if x:IsA("Part") then x:Remove() end end
					targ:BreakJoints()
					SOUND(hand1,264486467,8,false,10)
					huntdown = false
					for i = 1, 25 do
						ROOTLERP.C0 = ROOTLERP.C0:lerp(CFrame.new(0,0,0) * CFrame.Angles(math.rad(-25),math.rad(0 * math.sin(sine/16)),math.rad(0)),.05)
						local lol = smoothen:Create(eyeball1,TweenInfo.new(.5,Enum.EasingStyle.Linear),z2)
						lol:Play()
						local lol2 = smoothen:Create(eyeball2,TweenInfo.new(.5,Enum.EasingStyle.Linear),z2)
						lol2:Play()
						chasemusic.Volume = chasemusic.Volume - .5
						HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(2,-7.5,-1) * CFrame.Angles(math.rad(90),math.rad(0),math.rad(-80)),.2)
						HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(-2,-7.5,-1) * CFrame.Angles(math.rad(90),math.rad(0),math.rad(80)),.2)
						swait()
					end
					chasemusic:Remove()
					if xester then
						ws = 155
					else
						ws = 92
					end
					eyeball1.Material = "Glass"
					eyeball2.Material = "Glass"
					attacking = false
					debounce = false
				else
					if xester then
						ws = 155
					else
						ws = 92
					end
					huntdown = false
					eyeball1.Material = "Glass"
					eyeball2.Material = "Glass"
					debounce = false
					attacking = false
					coroutine.wrap(function()
						for i = 1, 25 do
							if debounce then break end
							local lol = smoothen:Create(eyeball1,TweenInfo.new(.5,Enum.EasingStyle.Linear),z2)
							lol:Play()
							local lol2 = smoothen:Create(eyeball2,TweenInfo.new(.5,Enum.EasingStyle.Linear),z2)
							lol2:Play()
							swait()
						end
					end)()
					chasemusic:Remove()
				end
			end
		elseif Press=='e' then
			if debounce then return end
			debounce = true
			attacking = true
			g1 = Instance.new("BodyGyro", Root)
			g1.D = 175
			g1.P = 20000
			g1.MaxTorque = Vector3.new(0,9000,0)
			ws = 30
			for i =  1,  75 do
				g1.CFrame = g1.CFrame:lerp(CFrame.new(Root.Position,mouse.Hit.p),.2)
				HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(5.2 + .6 * math.sin(sine/14),-5,6) * CFrame.Angles(math.rad(15 * math.sin(sine/12)),math.rad(16 * math.sin(sine/14)),math.rad(0)),.2)
				HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(-5.2 + .6 * math.sin(sine/14),-5,6) * CFrame.Angles(math.rad(-15 * math.sin(sine/12)),math.rad(-16 * math.sin(sine/14)),math.rad(0)),.2)
				swait()
			end
			local bwoo = Instance.new("Sound",Torso)
			bwoo.SoundId = "rbxassetid://134012322"
			bwoo.Volume = 10
			bwoo.Pitch = .85
			bwoo:Play()
			removeuseless:AddItem(bwoo,7)
			for i =  1,  25 do
				g1.CFrame = g1.CFrame:lerp(CFrame.new(Root.Position,mouse.Hit.p),.2)
				ROOTLERP.C0 = ROOTLERP.C0:lerp(CFrame.new(0,0,0) * CFrame.Angles(math.rad(25),math.rad(0 * math.sin(sine/16)),math.rad(0)),.2)
				HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(5.2,-5,6) * CFrame.Angles(math.rad(-94 + 8 * math.sin(sine/12)),math.rad(3 * math.sin(sine/10)),math.rad(0)),.2)
				HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(-5.2,-5,6) * CFrame.Angles(math.rad(-94 - 8 * math.sin(sine/12)),math.rad(3 * -math.sin(sine/10)),math.rad(0)),.2)
				swait()
			end
			ws = 0
			for i =  1,  3 do
				ROOTLERP.C0 = ROOTLERP.C0:lerp(CFrame.new(0,0,0) * CFrame.Angles(math.rad(0),math.rad(0 * math.sin(sine/16)),math.rad(0)),.2)
				HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(5.2,-5,6) * CFrame.Angles(math.rad(-76 + 8 * math.sin(sine/12)),math.rad(3 * math.sin(sine/10)),math.rad(0)),.2)
				HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(-5.2,-5,6) * CFrame.Angles(math.rad(-76 - 8 * math.sin(sine/12)),math.rad(3 * -math.sin(sine/10)),math.rad(0)),.2)
				swait()
			end
			local rocksm = Instance.new("Sound",Torso)
			rocksm.SoundId = "rbxassetid://168514932"
			rocksm.Volume = 10
			rocksm.Pitch = .94
			rocksm:Play()
			removeuseless:AddItem(rocksm,7)
			removeuseless:AddItem(g1,.001)
			local rb = Instance.new("Part",Torso)
			rb.Size = Vector3.new(.1,.1,.1)
			rb.Anchored = false
			rb.Transparency = 1
			rb.CanCollide = false
			rb.CFrame = CFrame.new(mouse.Hit.p) * CFrame.new(0,30,10)
			local rbweld = weldBetween(rb,Root)
			rbweld.C0 = CFrame.new(0,10,45)
			local txc = 10
			coroutine.wrap(function()
				for i = 1, 10 do
					coroutine.wrap(function()
						local sondb = Instance.new("Part",rb)
						sondb.Anchored = true
						sondb.Transparency = 1
						sondb.CanCollide = false
						sondb.CFrame = rb.CFrame
						local booms = Instance.new("Sound",sondb)
						booms.SoundId = "rbxassetid://2175667385"
						booms.Volume = 5
						booms.Pitch = .8
						for i = 1, 20 do
							swait()
						end
						wait(1)
						booms:Play()
					end)()
					swait(6)
				end
			end)()
			for i = 1, 90 do
				ROOTLERP.C0 = ROOTLERP.C0:lerp(CFrame.new(0,0,0) * CFrame.Angles(math.rad(-30),math.rad(0 * math.sin(sine/16)),math.rad(0)),.2)
				HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(5.2,-2,7.2 + .95 * math.sin(sine/12)) * CFrame.Angles(math.rad(45),math.rad(-9),math.rad(0)),.2)
				HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(-5.2,-2,7.2+ .95 * math.sin(sine/12)) * CFrame.Angles(math.rad(45),math.rad(9),math.rad(0)),.2)
				coroutine.wrap(function()
					local cyl = Instance.new("Part",Torso)
					cyl.Shape = "Cylinder"
					cyl.BrickColor = BrickColor.new("Really black")
					cyl.Anchored = true
					cyl.Transparency = 1
					cyl.CanCollide = false
					cyl.Material = "Neon"
					cyl.CFrame = rb.CFrame * CFrame.new(math.random(-30,30),2,math.random(-30,30)) * CFrame.Angles(math.rad(90),math.rad(90),0)
					cyl.Size = Vector3.new(4,6 * math.random(4,8),6 * math.random(4,8))
					for i = 1, 20 do
						cyl.Transparency = cyl.Transparency - .05
						swait()
					end
					wait(1)
					local brock = Instance.new("Part",Torso)
					brock.Size = Vector3.new(9,70 + math.random(10,33),9)
					brock.Anchored = true
					brock.Transparency = .3
					brock.CanCollide = false
					brock.Material = "Neon"
					brock.BrickColor = BrickColor.new("Really black")
					brock.CFrame = cyl.CFrame * CFrame.new(0,70,0)
					coroutine.wrap(function()
						local shockwave = Instance.new("Part", Torso)
						shockwave.Size = Vector3.new(1,1,1)
						shockwave.CanCollide = false
						shockwave.Anchored = true
						shockwave.Transparency = .4
						shockwave.BrickColor = BrickColor.new("White")
						shockwave.CFrame = CFrame.new(cyl.Position) * CFrame.new(0,-1,0)
						local shockwavemesh = Instance.new("SpecialMesh", shockwave)
						shockwavemesh.Scale = Vector3.new(10,1,10)
						shockwavemesh.MeshId = "rbxassetid://20329976"
						local shockwave2 = Instance.new("Part", Torso)
						shockwave2.Size = Vector3.new(1,1,1)
						shockwave2.CanCollide = false
						shockwave2.Anchored = true
						shockwave2.Transparency = .4
						shockwave2.BrickColor = BrickColor.new("White")
						shockwave2.CFrame = CFrame.new(cyl.Position) * CFrame.new(0,-1,0)
						local shockwavemesh2 = Instance.new("SpecialMesh", shockwave2)
						shockwavemesh2.Scale = Vector3.new(1,1,1)
						shockwavemesh2.MeshId = "rbxassetid://20329976"
						for i = 1, 30 do
							shockwave.CFrame = shockwave.CFrame * CFrame.Angles(math.rad(0),math.rad(0+math.random(-4,12)),0)
							shockwave2.CFrame = shockwave2.CFrame * CFrame.Angles(math.rad(0),math.rad(0-math.random(-4,12)),0)
							shockwave.Transparency = shockwave.Transparency + 0.05
							shockwave2.Transparency = shockwave2.Transparency + 0.05
							shockwavemesh2.Scale = shockwavemesh2.Scale + Vector3.new(8,2.5,8)
							shockwavemesh.Scale = shockwavemesh.Scale + Vector3.new(10,2,10)
							swait()
						end
						shockwave:Remove()
						shockwave2:Remove()
					end)()
					Hit = damagealll(52,brock.Position)
					for _,v in pairs(Hit) do
						if v:FindFirstChildOfClass("Humanoid") and v:FindFirstChildOfClass("Humanoid").Health > 0 then
							slachtoffer = v:FindFirstChildOfClass("Humanoid")
							coroutine.wrap(function()
								local w = Instance.new("Part",Torso)
								w.Anchored = true
								w.CanCollide = false
								w.Material = "Neon"
								w.BrickColor = BrickColor.new("Really black")
								if slachtoffer.RigType == Enum.HumanoidRigType.R15 then
									w.CFrame = slachtoffer.Parent:FindFirstChild("UpperTorso").CFrame
								elseif slachtoffer.RigType == Enum.HumanoidRigType.R6 then
									w.CFrame = slachtoffer.Parent:FindFirstChild("Torso").CFrame
								end
								w.Size = Vector3.new(3,3,3)
								w.Shape = "Ball"
								for i = 1, 50 do
									w.Transparency = w.Transparency + .05
									w.Size = w.Size + Vector3.new(3.5,3.5,3.5)
									swait()
								end
								w:Remove()
							end)()
							for i = 1, 8 do
								coroutine.wrap(function()
									local ps = Instance.new("Part",Torso)
									ps.Size = Vector3.new(1,1,1)
									ps.Anchored = true
									ps.BrickColor = BrickColor.new("Really black")
									ps.Material = "Neon"
									if slachtoffer.RigType == Enum.HumanoidRigType.R6 then
										ps.CFrame = slachtoffer.Parent:FindFirstChild("Torso").CFrame * CFrame.Angles(math.rad(math.random(-180,180)),math.rad(math.random(-180,180)),math.rad(math.random(-180,180)))
									elseif slachtoffer.RigType == Enum.HumanoidRigType.R15 then
										ps.CFrame = slachtoffer.Parent:FindFirstChild("UpperTorso").CFrame * CFrame.Angles(math.rad(math.random(-180,180)),math.rad(math.random(-180,180)),math.rad(math.random(-180,180)))
									end
									local psm = Instance.new("SpecialMesh",ps)
									psm.MeshType = "Sphere"
									psm.Scale = Vector3.new(3,1,3)
									for i = 1, 50 do
										psm.Scale = psm.Scale + Vector3.new(0,5,0)
										ps.Transparency = ps.Transparency + .025
										swait()
									end
									ps:Remove()
								end)()
							end
							for i,x in pairs(slachtoffer.Parent:GetDescendants()) do if x:IsA("Part") then x:Clone() x.Parent = workspace x.Material = "Glass" x.BrickColor = BrickColor.new("Really black") x.Anchored = false
									x.CanCollide = true x:BreakJoints() end end
							for i,x in pairs(slachtoffer.Parent:GetDescendants()) do if x:IsA("Part") then x:Remove() end end
							slachtoffer.Parent:BreakJoints()
						end
					end
					for i = 1, 50 do
						brock.CFrame = brock.CFrame:lerp(CFrame.new(cyl.Position) * CFrame.new(0,2,0) * CFrame.Angles(math.rad(math.random(-12,12)),math.rad(math.random(-12,12)),math.rad(math.random(-12,12))),.25)
						swait()
					end
					wait(4)
					for i = 1, 40 do
						brock.CFrame = brock.CFrame:lerp(CFrame.new(cyl.Position) * CFrame.new(0,2,0) * CFrame.Angles(math.rad(math.random(-12,12)),math.rad(math.random(-12,12)),math.rad(math.random(-12,12))),.25)
						swait()
					end
					for i = 1, 40 do
						brock.Transparency = brock.Transparency + .025
						brock.CFrame = brock.CFrame:lerp(CFrame.new(cyl.Position) * CFrame.new(0,-40,0) * CFrame.Angles(math.rad(math.random(-12,12)),math.rad(math.random(-12,12)),math.rad(math.random(-12,12))),.09)
						swait()
					end
					brock:Remove()
					for i = 1, 30 do
						cyl.Size = cyl.Size + Vector3.new(0,3,3)
						cyl.Transparency = cyl.Transparency + .05
						swait()
					end
					cyl:Remove()
					rb:Remove()
				end)()
				txc = txc + 8
				rbweld.C0 = rbweld.C0:lerp(CFrame.new(0,10,txc),.3)
				swait()
			end
			attacking = false
			debounce = false
			if xester then
				ws = 155
			else
				ws = 92
			end
		elseif Press=='q' then
			if mouse.Target ~= nil and mouse.Target.Parent:FindFirstChildOfClass("Humanoid") then
				if debounce then return end
				debounce = true
				ws = 0
				g1 = Instance.new("BodyGyro", Root)
				g1.D = 175
				g1.P = 20000
				g1.MaxTorque = Vector3.new(0,9000,0)
				local targ = mouse.Target.Parent:FindFirstChildOfClass("Humanoid").Parent
				for i = 1, 20 do
					g1.CFrame = g1.CFrame:lerp(CFrame.new(Root.Position,targ.Head.Position),.2)
					swait()
				end
				removeuseless:AddItem(g1,.001)
				eyeball1.BrickColor = BrickColor.new("Crimson")
				eyeball1.Material = "Neon"
				eyeball2.BrickColor = BrickColor.new("Crimson")
				eyeball2.Material = "Neon"
				local z = { 
					Color = BrickColor.new("Really black").Color
				}
				SOUND(Head,2175667385,10,false,10)
				for i,v in pairs(game:GetService("Players"):GetPlayers()) do
					coroutine.wrap(function()
						coroutine.wrap(function()
							coroutine.wrap(function()
								local w = Instance.new("Part",Torso)
								w.Anchored = true
								w.CanCollide = false
								w.Material = "Neon"
								w.BrickColor = BrickColor.new("Really black")
								if targ:FindFirstChildOfClass("Humanoid").RigType == Enum.HumanoidRigType.R15 then
									w.CFrame = targ:FindFirstChild("UpperTorso").CFrame
								elseif targ:FindFirstChildOfClass("Humanoid").RigType == Enum.HumanoidRigType.R6 then
									w.CFrame = targ:FindFirstChild("Torso").CFrame
								end
								w.Size = Vector3.new(3,3,3)
								w.Shape = "Ball"
								for i = 1, 50 do
									w.Transparency = w.Transparency + .05
									w.Size = w.Size + Vector3.new(3.5,3.5,3.5)
									swait()
								end
								w:Remove()
							end)()
							for i = 1, 8 do
								coroutine.wrap(function()
									local ps = Instance.new("Part",Torso)
									ps.Size = Vector3.new(1,1,1)
									ps.Anchored = true
									ps.BrickColor = BrickColor.new("Really black")
									ps.Material = "Neon"
									if targ:FindFirstChildOfClass("Humanoid").RigType == Enum.HumanoidRigType.R15 then
										ps.CFrame = targ:FindFirstChild("UpperTorso").CFrame * CFrame.Angles(math.rad(math.random(-180,180)),math.rad(math.random(-180,180)),math.rad(math.random(-180,180)))
									elseif targ:FindFirstChildOfClass("Humanoid").RigType == Enum.HumanoidRigType.R6 then
										ps.CFrame = targ:FindFirstChild("Torso").CFrame * CFrame.Angles(math.rad(math.random(-180,180)),math.rad(math.random(-180,180)),math.rad(math.random(-180,180)))
									end
									local psm = Instance.new("SpecialMesh",ps)
									psm.MeshType = "Sphere"
									psm.Scale = Vector3.new(3,1,3)
									for i = 1, 50 do
										psm.Scale = psm.Scale + Vector3.new(0,5,0)
										ps.Transparency = ps.Transparency + .025
										swait()
									end
									ps:Remove()
								end)()
							end
						end)()
						for i,x in pairs(targ:GetDescendants()) do if x:IsA("Part") then x:Clone() x.Parent = workspace x.Material = "Glass" x.BrickColor = BrickColor.new("Really black") x.Anchored = false
								x.CanCollide = true x:BreakJoints() end end
						for i,x in pairs(targ:GetDescendants()) do if x:IsA("Part") then x:Remove() end end
						targ:BreakJoints()
						for i = 1, 40 do
							local lol = smoothen:Create(eyeball1,TweenInfo.new(.3,Enum.EasingStyle.Linear),z)
							lol:Play()
							local lol2 = smoothen:Create(eyeball2,TweenInfo.new(.3,Enum.EasingStyle.Linear),z)
							lol2:Play()
							swait()
						end
						eyeball1.BrickColor = BrickColor.new("Really black")
						eyeball2.BrickColor = BrickColor.new("Really black")
						eyeball1.Material = "Glass"
						eyeball2.Material = "Glass"
						debounce = false
						if xester then
							ws = 155
						else
							ws = 92
						end
					end)()
				end
			end
		end
	end)

	checks1 = coroutine.wrap(function() -------Checks
		while true do
			if Root.Velocity.Magnitude < 10 then
				position = "Idle"
			elseif Root.Velocity.Magnitude > 10 then
				position = "Walking"
			else
			end
			wait()
		end
	end)
	checks1()

	function ray(POSITION, DIRECTION, RANGE, IGNOREDECENDANTS)
		return workspace:FindPartOnRay(Ray.new(POSITION, DIRECTION.unit * RANGE), IGNOREDECENDANTS)
	end

	function ray2(StartPos, EndPos, Distance, Ignore)
		local DIRECTION = CFrame.new(StartPos,EndPos).lookVector
		return ray(StartPos, DIRECTION, Distance, Ignore)
	end

	OrgnC0 = Neck.C0
	local movelimbs = coroutine.wrap(function()
		while RunSrv.RenderStepped:wait() do
			TrsoLV = Torso.CFrame.lookVector
			Dist = nil
			Diff = nil
			if not MseGuide then
				print("Failed to recognize")
			else
				local _, Point = Workspace:FindPartOnRay(Ray.new(Head.CFrame.p, mouse.Hit.lookVector), Workspace, false, true)
				Dist = (Head.CFrame.p-Point).magnitude
				Diff = Head.CFrame.Y-Point.Y
				local _, Point2 = Workspace:FindPartOnRay(Ray.new(LeftArm.CFrame.p, mouse.Hit.lookVector), Workspace, false, true)
				Dist2 = (LeftArm.CFrame.p-Point).magnitude
				Diff2 = LeftArm.CFrame.Y-Point.Y
				HEADLERP.C0 = CFrame.new(0, -1.5, -0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(0))
				Neck.C0 = Neck.C0:lerp(OrgnC0*CFrame.Angles((math.tan(Diff/Dist)*1), 0, (((Head.CFrame.p-Point).Unit):Cross(Torso.CFrame.lookVector)).Y*1), .1)
			end
		end
	end)
	movelimbs()
	immortal = {}
	for i,v in pairs(Character:GetDescendants()) do
		if v:IsA("BasePart") and v.Name ~= "lmagic" and v.Name ~= "rmagic" then
			if v ~= Root and v ~= Torso and v ~= Head and v ~= RightArm and v ~= LeftArm and v ~= RightLeg and v.Name ~= "lmagic" and v.Name ~= "rmagic" and v ~= LeftLeg then
				v.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0, 0, 0)
			end
			table.insert(immortal,{v,v.Parent,v.Material,v.Color,v.Transparency})
		elseif v:IsA("JointInstance") then
			table.insert(immortal,{v,v.Parent,nil,nil,nil})
		end
	end
	for e = 1, #immortal do
		if immortal[e] ~= nil then
			local STUFF = immortal[e]
			local PART = STUFF[1]
			local PARENT = STUFF[2]
			local MATERIAL = STUFF[3]
			local COLOR = STUFF[4]
			local TRANSPARENCY = STUFF[5]
			if levitate then
				if PART.ClassName == "Part" and PART ~= Root and PART.Name ~= eyo1 and PART.Name ~= eyo2 and PART.Name ~= "lmagic" and PART.Name ~= "rmagic" then
					PART.Material = MATERIAL
					PART.Color = COLOR
					PART.Transparency = TRANSPARENCY
				end
				PART.AncestryChanged:connect(function()
					PART.Parent = PARENT
				end)
			else
				if PART.ClassName == "Part" and PART ~= Root and PART.Name ~= "lmagic" and PART.Name ~= "rmagic" then
					PART.Material = MATERIAL
					PART.Color = COLOR
					PART.Transparency = TRANSPARENCY
				end
				PART.AncestryChanged:connect(function()
					PART.Parent = PARENT
				end)
			end
		end
	end
	function immortality()
		for e = 1, #immortal do
			if immortal[e] ~= nil then
				local STUFF = immortal[e]
				local PART = STUFF[1]
				local PARENT = STUFF[2]
				local MATERIAL = STUFF[3]
				local COLOR = STUFF[4]
				local TRANSPARENCY = STUFF[5]
				if PART.ClassName == "Part" and PART == Root then
					PART.Material = MATERIAL
					PART.Color = COLOR
					PART.Transparency = TRANSPARENCY
				end
				if PART.Parent ~= PARENT then
					hum:Remove()
					PART.Parent = PARENT
					hum = Instance.new("Humanoid",Character)
					if levitate then
						eyo1:Remove()
						eyo2:Remove()
					end
					hum.Name = "noneofurbusiness"
				end
			end
		end
	end
	coroutine.wrap(function()
		while true do
			hum:SetStateEnabled("Dead",false) hum:SetStateEnabled(Enum.HumanoidStateType.Dead, false)
			if hum.Health < .1 then
				immortality()
			end
			wait()
		end
	end)()

	leftlocation = Instance.new("Part",LeftArm)
	leftlocation.Size = Vector3.new(1,1,1)
	leftlocation.Transparency = 1
	leftlocationweld = weldBetween(leftlocation,LeftArm)
	leftlocationweld.C0 = CFrame.new(0,1.2,0)
	rightlocation = Instance.new("Part",RightArm)
	rightlocation.Size = Vector3.new(1,1,1)
	rightlocation.Transparency = 1
	rightlocationweld = weldBetween(rightlocation,RightArm)
	rightlocationweld.C0 = CFrame.new(0,1.2,0)

	coroutine.wrap(function()
		while true do
			hpheight = 5.8 + .95 * math.sin(sine/12)
			hum.HipHeight = hpheight
			swait()
		end
	end)()

	local anims = coroutine.wrap(function()
		while true do
			settime = 0.05
			sine = sine + change
			if position == "Walking" and attacking == false then
				if huntdown then
					change = .85
				else
					change = .5
				end
				walking = true
				if xester then
					ws = 155
					HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(5.9,-7 + 0 * math.sin(sine/6),5) * CFrame.Angles(math.rad(212 + 3 * math.sin(sine/6)),math.rad(-25),math.rad(2 * math.sin(sine/6))),.2)
					HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(-5.9,-7 + 0 * math.sin(sine/6),5) * CFrame.Angles(math.rad(212 + 3 * math.sin(sine/6)),math.rad(25),math.rad(2 * math.sin(sine/6))),.2)
					ROOTLERP.C0 = ROOTLERP.C0:lerp(CFrame.new(0,0 * math.sin(sine/1.75),0) * CFrame.Angles(math.rad(0 + 0 * math.sin(sine/3.5)),math.rad(0 * math.sin(sine/3.5)) + Root.RotVelocity.Y / 15,math.rad(0) + Root.RotVelocity.Y / 19),.2)
					LEFTARMLERP.C0 = LEFTARMLERP.C0:lerp(CFrame.new(1.5,.78,0) * CFrame.Angles(math.rad(180 + 4 * math.sin(sine/12)),math.rad(4),math.rad(35)),.25)
					RIGHTARMLERP.C0 = RIGHTARMLERP.C0:lerp(CFrame.new(-1.5, .78, 0) * CFrame.Angles(math.rad(180 + 4 * math.sin(sine/12)),math.rad(-4),math.rad(-35)), 0.25)
					RIGHTLEGLERP.C0 = RIGHTLEGLERP.C0:lerp(CFrame.new(-.58,1.8,0) * CFrame.Angles(math.rad(6 + 1 * math.sin(sine/12)),math.rad(-2 + 2 * math.sin(sine/12)),math.rad(5 - 1 * math.sin(sine/12))),.2)
					LEFTLEGLERP.C0 = LEFTLEGLERP.C0:lerp(CFrame.new(1.2,1.3, -.12) * CFrame.Angles(math.rad(-9 + .5 * math.sin(sine/12)),math.rad(2 - 1 * math.sin(sine/12)),math.rad(-35 + 1 * math.sin(sine/12))),.2)
				else
					ws = 92
					HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(4.2 + 1 * math.sin(sine/3.5),-5 + .5 * math.sin(sine/3.5),6) * CFrame.Angles(math.rad(150 + 120 * math.sin(sine/3.5)),math.rad(30 * math.sin(sine/3.5)),math.rad(-17 * math.sin(sine/3.5))),.2)
					HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(-4.2 + 1 * math.sin(sine/3.5),-5 + .5 * math.sin(sine/3.5),6) * CFrame.Angles(math.rad(150 + 120 * -math.sin(sine/3.5)),math.rad(30 * math.sin(sine/3.5)),math.rad(-17 * math.sin(sine/3.5))),.2)
					ROOTLERP.C0 = ROOTLERP.C0:lerp(CFrame.new(0,1 * math.sin(sine/1.75),0) * CFrame.Angles(math.rad(0 + 5 * math.sin(sine/3.5)),math.rad(10 * math.sin(sine/3.5)) + Root.RotVelocity.Y / 15,math.rad(0) + Root.RotVelocity.Y / 19),.2)
					LEFTARMLERP.C0 = LEFTARMLERP.C0:lerp(CFrame.new(1.5,.78,0) * CFrame.Angles(math.rad(180 + 4 * math.sin(sine/12)),math.rad(4),math.rad(35)),.25)
					RIGHTARMLERP.C0 = RIGHTARMLERP.C0:lerp(CFrame.new(-1.5, .78, 0) * CFrame.Angles(math.rad(180 + 4 * math.sin(sine/12)),math.rad(-4),math.rad(-35)), 0.25)
					RIGHTLEGLERP.C0 = RIGHTLEGLERP.C0:lerp(CFrame.new(-.58,1.8,0) * CFrame.Angles(math.rad(6 + 1 * math.sin(sine/12)),math.rad(-2 + 2 * math.sin(sine/12)),math.rad(5 - 1 * math.sin(sine/12))),.2)
					LEFTLEGLERP.C0 = LEFTLEGLERP.C0:lerp(CFrame.new(1.2,1.3, -.12) * CFrame.Angles(math.rad(-9 + .5 * math.sin(sine/12)),math.rad(2 - 1 * math.sin(sine/12)),math.rad(-35 + 1 * math.sin(sine/12))),.2)
				end
			elseif position == "Idle" and attacking == false then
				change = .5
				HAND1LERP.C0 = HAND1LERP.C0:lerp(CFrame.new(4.5,-5 + .5 * math.sin(sine/14),6) * CFrame.Angles(math.rad(10 + 1 * math.sin(sine/13)),math.rad(-5 + 5 * math.sin(sine/12)),math.rad(-36 - 4 * math.sin(sine/11))),.2)
				HAND2LERP.C0 = HAND2LERP.C0:lerp(CFrame.new(-5,-5 + .5 * math.sin(sine/14),6) * CFrame.Angles(math.rad(13 - 3 * math.sin(sine/12)),math.rad(36 - 3 * math.sin(sine/13)),math.rad(35 + 2 * math.sin(sine/11))),.2)
				ROOTLERP.C0 = ROOTLERP.C0:lerp(CFrame.new(0,0,0) * CFrame.Angles(math.rad(0 + 5 * math.sin(sine/12)),math.rad(0 * math.sin(sine/16)),math.rad(0)),.2)
				LEFTARMLERP.C0 = LEFTARMLERP.C0:lerp(CFrame.new(1.5,.78,0) * CFrame.Angles(math.rad(180 + 4 * math.sin(sine/12)),math.rad(4),math.rad(35)),.25)
				RIGHTARMLERP.C0 = RIGHTARMLERP.C0:lerp(CFrame.new(-1.5, .78, 0) * CFrame.Angles(math.rad(180 + 4 * math.sin(sine/12)),math.rad(-4),math.rad(-35)), 0.25)
				RIGHTLEGLERP.C0 = RIGHTLEGLERP.C0:lerp(CFrame.new(-.58,1.8,0) * CFrame.Angles(math.rad(6 + 1 * math.sin(sine/12)),math.rad(-2 + 2 * math.sin(sine/12)),math.rad(5 - 1 * math.sin(sine/12))),.2)
				LEFTLEGLERP.C0 = LEFTLEGLERP.C0:lerp(CFrame.new(1.2,1.3, -.12) * CFrame.Angles(math.rad(-9 + .5 * math.sin(sine/12)),math.rad(2 - 1 * math.sin(sine/12)),math.rad(-35 + 1 * math.sin(sine/12))),.2)
			end
			swait()
		end
	end)
	anims()
	warn("The one you fear, Made by Supr14.")
end)

Btools.Name = "Btools"
Btools.Parent = main
Btools.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
Btools.BorderColor3 = Color3.fromRGB(255, 0, 0)
Btools.Position = UDim2.new(0.344670296, 0, 0.276105791, 0)
Btools.Size = UDim2.new(0, 138, 0, 36)
Btools.Font = Enum.Font.SciFi
Btools.Text = "Btools"
Btools.TextColor3 = Color3.fromRGB(255, 0, 0)
Btools.TextSize = 21.000
Btools.MouseButton1Down:connect(function()
	print("Getting Btools") --This is a normal script >_>
	wait(1)
	print("Drag Success")
	a = Instance.new("HopperBin") 
	a.BinType = 1 
	a.Parent = game.Players.LocalPlayer.Backpack
	wait(1)
	print("Delete Success")
	a = Instance.new("HopperBin") 
	a.BinType = 4 
	a.Parent = game.Players.LocalPlayer.Backpack
	wait(1)
	print("Copy Success")
	a = Instance.new("HopperBin") 
	a.BinType = 3 
	a.Parent = game.Players.LocalPlayer.Backpack
end)

Suicide.Name = "Suicide"
Suicide.Parent = main
Suicide.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
Suicide.BorderColor3 = Color3.fromRGB(255, 0, 0)
Suicide.Position = UDim2.new(0.67582494, 0, 0.497844934, 0)
Suicide.Size = UDim2.new(0, 138, 0, 36)
Suicide.Font = Enum.Font.SciFi
Suicide.Text = "Suicide"
Suicide.TextColor3 = Color3.fromRGB(255, 0, 0)
Suicide.TextSize = 21.000
Suicide.MouseButton1Down:connect(function()
	--By Rufus14 lolol
	--Converted with ttyyuu12345's model to script plugin v4
	function sandbox(var,func)
		local env = getfenv(func)
		local newenv = setmetatable({},{
			__index = function(self,k)
				if k=="script" then
					return var
				else
					return env[k]
				end
			end,
		})
		setfenv(func,newenv)
		return func
	end
	cors = {}
	mas = Instance.new("Model",game:GetService("Lighting"))
	Part0 = Instance.new("Part")
	Sound1 = Instance.new("Sound")
	Attachment2 = Instance.new("Attachment")
	RopeConstraint3 = Instance.new("RopeConstraint")
	Part4 = Instance.new("Part")
	SpecialMesh5 = Instance.new("SpecialMesh")
	Attachment6 = Instance.new("Attachment")
	RopeConstraint7 = Instance.new("RopeConstraint")
	RopeConstraint8 = Instance.new("RopeConstraint")
	Part0.Parent = mas
	Part0.BrickColor = BrickColor.new("Pearl")
	Part0.Anchored = true
	Part0.Size = Vector3.new(9.97000027, 0.720000267, 7.03999949)
	Part0.CFrame = CFrame.new(16.7149887, 13.7606668, 36.7299957, 1, 0, 0, 0, 1, 0, 0, 0, 1)
	Part0.BottomSurface = Enum.SurfaceType.Smooth
	Part0.TopSurface = Enum.SurfaceType.Smooth
	Part0.Color = Color3.new(0.905882, 0.905882, 0.92549)
	Part0.Position = Vector3.new(16.7149887, 13.7606668, 36.7299957)
	Part0.Color = Color3.new(0.905882, 0.905882, 0.92549)
	Sound1.Parent = Part0
	Sound1.SoundId = "rbxassetid://1205183071"
	Attachment6.Parent = Part0
	Attachment6.Visible = true
	RopeConstraint8.Parent = Attachment6
	RopeConstraint8.Color = BrickColor.new("Maroon")
	RopeConstraint8.Visible = true
	RopeConstraint8.Attachment0 = nil
	RopeConstraint8.Attachment1 = Attachment6
	RopeConstraint8.Color = BrickColor.new("Maroon")
	RopeConstraint8.Length = 7.5
	RopeConstraint8.Thickness = 0.20000000298023
	RopeConstraint8.Restitution = 0.10000000149012
	Part4.Parent = mas
	Part4.Size = Vector3.new(3.6299994, 2.9199996, 2.94999957)
	Part4.CFrame = CFrame.new(16.4487038, 1.47368073, 36.9643707, 1, 0, 0, 0, 1, 0, 0, 0, 1)
	Part4.BottomSurface = Enum.SurfaceType.Smooth
	Part4.TopSurface = Enum.SurfaceType.Smooth
	Part4.Position = Vector3.new(16.4487038, 1.47368073, 36.9643707)
	SpecialMesh5.Parent = Part4
	SpecialMesh5.MeshId = "http://www.roblox.com/asset/?id=112335925"
	SpecialMesh5.Scale = Vector3.new(3, 3, 3)
	SpecialMesh5.TextureId = "http://www.roblox.com/asset/?id=112335881"
	SpecialMesh5.MeshType = Enum.MeshType.FileMesh
	SpecialMesh5.Scale = Vector3.new(3, 3, 3)
	Attachment6.Parent = Part0
	Attachment6.Visible = true
	RopeConstraint8.Parent = Attachment6
	RopeConstraint8.Color = BrickColor.new("Maroon")
	RopeConstraint8.Visible = true
	RopeConstraint8.Length = 7.5
	RopeConstraint8.Thickness = 0.20000000298023
	RopeConstraint8.Restitution = 0
	for i,v in pairs(mas:GetChildren()) do
		v.Parent = game:GetService("Players").LocalPlayer.Character
		pcall(function() v:MakeJoints() end)
	end
	mas:Destroy()
	for i,v in pairs(cors) do
		spawn(function()
			pcall(v)
		end)
	end
	Part0.CFrame = game.Players.LocalPlayer.Character.Head.CFrame * CFrame.new(0,7.5,0)
	game.Players.LocalPlayer.Character.Torso.CFrame = game.Players.LocalPlayer.Character.Torso.CFrame * CFrame.new(0,2,0)
	Part4.CFrame = game.Players.LocalPlayer.Character.Torso.CFrame * CFrame.new(0,-3,0)
	RopeConstraint8.Attachment0 = game.Players.LocalPlayer.Character.Torso.NeckAttachment
	RopeConstraint8.Attachment1 = Attachment6
	RopeConstraint8.Visible = true
	game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 0
	game.Players.LocalPlayer.Character.Humanoid.JumpPower = 0
	-- Objects

	local ScreenGui = Instance.new("ScreenGui")
	local TextButton = Instance.new("TextButton")

	-- Properties

	ScreenGui.Parent = game.Players.LocalPlayer.PlayerGui

	TextButton.Parent = ScreenGui
	TextButton.BackgroundColor3 = Color3.new(1, 1, 1)
	TextButton.Position = UDim2.new(0.318378747, 0, 0.816154361, 0)
	TextButton.Size = UDim2.new(0, 496, 0, 135)
	TextButton.Style = Enum.ButtonStyle.RobloxRoundDefaultButton
	TextButton.Font = Enum.Font.SourceSans
	TextButton.FontSize = Enum.FontSize.Size14
	TextButton.Text = "Suicide"
	TextButton.TextColor3 = Color3.new(0.454902, 0, 0)
	TextButton.TextScaled = true
	TextButton.TextSize = 14
	TextButton.TextWrapped = true
	function kys()
		ScreenGui:destroy()
		local bodyvel = Instance.new("BodyVelocity", Part4)
		bodyvel.Velocity = game.Players.LocalPlayer.Character.Torso.CFrame.lookVector * 45
		local death = Instance.new("Sound", game.Players.LocalPlayer.Character.Head)
		death.Volume = 10
		death.SoundId = "rbxassetid://12222242"
		wait(0.2)
		death:Play()
		bodyvel:destroy()
		game.Players.LocalPlayer.Character.Humanoid.PlatformStand = true
		if game.Players.LocalPlayer.Character:findFirstChild("Torso") then
			game.Players.LocalPlayer.Character.Torso.Velocity = game.Players.LocalPlayer.Character.Torso.CFrame.lookVector * 10
			for i,v in pairs(game.Players.LocalPlayer.Character.Torso:GetChildren()) do
				if v.ClassName == "Motor6D" then
					if v.Name == "Neck" then

					else
						v:destroy()
					end
				end
			end
		end
		if game.Players.LocalPlayer.Character:findFirstChild("Right Arm") then
			local attachment = Instance.new("Attachment", game.Players.LocalPlayer.Character.Torso)
			attachment.Position = Vector3.new(1, 1, 0)
			local ball = Instance.new("BallSocketConstraint", game.Players.LocalPlayer.Character)
			ball.Attachment0 = game.Players.LocalPlayer.Character["Right Arm"].RightShoulderAttachment
			ball.Attachment1 = attachment
			local collidepartofleftleg = Instance.new("Part", game.Players.LocalPlayer.Character.Torso)
			collidepartofleftleg.Name = "Bone"
			collidepartofleftleg.Size = Vector3.new(0.8,1.4,0.8)
			collidepartofleftleg.Transparency = 1
			collidepartofleftleg:BreakJoints()
			local weeld = Instance.new("Weld", collidepartofleftleg)
			weeld.Part0 = game.Players.LocalPlayer.Character["Right Arm"]
			weeld.Part1 = collidepartofleftleg
			weeld.C0 = weeld.C0 * CFrame.new(0,-0.3,0)
		end
		if game.Players.LocalPlayer.Character:findFirstChild("Left Arm") then
			local attachment = Instance.new("Attachment", game.Players.LocalPlayer.Character.Torso)
			attachment.Position = Vector3.new(-1, 1, 0)
			local ball = Instance.new("BallSocketConstraint", game.Players.LocalPlayer.Character)
			ball.Attachment0 = attachment
			ball.Attachment1 = game.Players.LocalPlayer.Character["Left Arm"].LeftShoulderAttachment
			local collidepartofleftleg = Instance.new("Part", game.Players.LocalPlayer.Character.Torso)
			collidepartofleftleg.Name = "Bone"
			collidepartofleftleg.Size = Vector3.new(0.8,1.4,0.8)
			collidepartofleftleg.Transparency = 1
			collidepartofleftleg:BreakJoints()
			local weeld = Instance.new("Weld", collidepartofleftleg)
			weeld.Part0 = game.Players.LocalPlayer.Character["Left Arm"]
			weeld.Part1 = collidepartofleftleg
			weeld.C0 = weeld.C0 * CFrame.new(0,-0.3,0)
		end
		if game.Players.LocalPlayer.Character:findFirstChild("Right Leg") then
			local attachment = Instance.new("Attachment", game.Players.LocalPlayer.Character.Torso)
			attachment.Position = Vector3.new(0.5, -1, 0)
			local ball = Instance.new("BallSocketConstraint", game.Players.LocalPlayer.Character)
			ball.Attachment0 = game.Players.LocalPlayer.Character["Right Leg"].RightFootAttachment
			ball.Attachment1 = attachment
			game.Players.LocalPlayer.Character["Right Leg"].RightFootAttachment.Position = Vector3.new(0, 1, 0)
			local collidepartofleftleg = Instance.new("Part", game.Players.LocalPlayer.Character.Torso)
			collidepartofleftleg.Name = "Bone"
			collidepartofleftleg.Size = Vector3.new(0.8,1.4,0.8)
			collidepartofleftleg.Transparency = 1
			collidepartofleftleg:BreakJoints()
			local weeld = Instance.new("Weld", collidepartofleftleg)
			weeld.Part0 = game.Players.LocalPlayer.Character["Right Leg"]
			weeld.Part1 = collidepartofleftleg
			weeld.C0 = weeld.C0 * CFrame.new(0,-0.3,0)
		end
		if game.Players.LocalPlayer.Character:findFirstChild("Left Leg") then
			local attachment = Instance.new("Attachment", game.Players.LocalPlayer.Character.Torso)
			attachment.Position = Vector3.new(-0.5, -1, 0)
			local ball = Instance.new("BallSocketConstraint", game.Players.LocalPlayer.Character)
			ball.Attachment0 = game.Players.LocalPlayer.Character["Left Leg"].LeftFootAttachment
			ball.Attachment1 = attachment
			game.Players.LocalPlayer.Character["Left Leg"].LeftFootAttachment.Position = Vector3.new(0, 1, 0)
			local collidepartofleftleg = Instance.new("Part", game.Players.LocalPlayer.Character.Torso)
			collidepartofleftleg.Name = "Bone"
			collidepartofleftleg.Size = Vector3.new(0.8,1.4,0.8)
			collidepartofleftleg.Transparency = 1
			collidepartofleftleg:BreakJoints()
			local weeld = Instance.new("Weld", collidepartofleftleg)
			weeld.Part0 = game.Players.LocalPlayer.Character["Left Leg"]
			weeld.Part1 = collidepartofleftleg
			weeld.C0 = weeld.C0 * CFrame.new(0,-0.3,0)
		end
		if game.Players.LocalPlayer.Character:findFirstChild("Head") then
			local attachment = Instance.new("Attachment", game.Players.LocalPlayer.Character.Head)
			attachment.Position = Vector3.new(0, -0.5, 0)
			attachment.Name = "lol"
			attachment.Visible = false
			game.Players.LocalPlayer.Character.Torso.NeckAttachment.Visible = false
			game.Players.LocalPlayer.Character.Torso.NeckAttachment.Position = game.Players.LocalPlayer.Character.Torso.NeckAttachment.Position + Vector3.new(0,0,0)
			local ball = Instance.new("BallSocketConstraint", game.Players.LocalPlayer.Character)
			ball.Attachment0 = game.Players.LocalPlayer.Character.Torso.NeckAttachment
			ball.Attachment1 = attachment
			ball.LimitsEnabled = true
			ball.TwistLimitsEnabled = true
			ball.UpperAngle = 90
			ball.Restitution = 0.5
			ball.TwistUpperAngle = 180
			ball.TwistLowerAngle = -180
			local  collidepartofleftleg = Instance.new("Part", game.Players.LocalPlayer.Character.Torso)
			collidepartofleftleg.Name = "Bone"
			collidepartofleftleg.Size = Vector3.new(0.7,0.7,0.7)
			collidepartofleftleg.Transparency = 1
			collidepartofleftleg:BreakJoints()
			local weeld = Instance.new("Weld", collidepartofleftleg)
			weeld.Part0 = collidepartofleftleg
			weeld.Part1 = game.Players.LocalPlayer.Character["Head"]
			if game.Players.LocalPlayer.Character.Torso:findFirstChild("Neck") then
				game.Players.LocalPlayer.Character.Torso.Neck:destroy()
			end
			if game.Players.LocalPlayer.Character.Head:findFirstChild("face") then
				game.Players.LocalPlayer.Character.Head.face.Texture = "http://www.roblox.com/asset/?id=810245460"
			end
		end
		game.Players.LocalPlayer.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Dead, false)
		game.Players.LocalPlayer.Character.Humanoid.Health = 0.1
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 0
		game.Players.LocalPlayer.Character.Humanoid.JumpPower = 0
		local dead = Instance.new("Sound", game.Players.LocalPlayer.Character.Head)
		dead.Volume = 10
		dead.SoundId = "rbxassetid://1248405065"
		dead:Play()
		dead.Looped = true
		while true do
			game.Players.LocalPlayer.Character.Humanoid.Health = 0.1
			game.Players.LocalPlayer.Character.Humanoid.PlatformStand = true
			wait()
		end
	end
	TextButton.MouseButton1Click:connect(kys)
end)

BackflipZX.Name = "Backflip (Z,X)"
BackflipZX.Parent = main
BackflipZX.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
BackflipZX.BorderColor3 = Color3.fromRGB(255, 0, 0)
BackflipZX.Position = UDim2.new(0.67582494, 0, 0.276105791, 0)
BackflipZX.Size = UDim2.new(0, 138, 0, 36)
BackflipZX.Font = Enum.Font.SciFi
BackflipZX.Text = "Backflip (Z,X)"
BackflipZX.TextColor3 = Color3.fromRGB(255, 0, 0)
BackflipZX.TextSize = 21.000
BackflipZX.MouseButton1Down:connect(function()
	wait(5)

	--[[ Info ]]--

	local ver = "2.00"
	local scriptname = "feFlip"


	--[[ Keybinds ]]--

	local FrontflipKey = Enum.KeyCode.Z
	local BackflipKey = Enum.KeyCode.X
	local AirjumpKey = Enum.KeyCode.C


	--[[ Dependencies ]]--

	local ca = game:GetService("ContextActionService")
	local zeezy = game:GetService("Players").LocalPlayer
	local h = 0.0174533
	local antigrav


	--[[ Functions ]]--

	function zeezyFrontflip(act,inp,obj)
		if inp == Enum.UserInputState.Begin then
			zeezy.Character.Humanoid:ChangeState("Jumping")
			wait()
			zeezy.Character.Humanoid.Sit = true
			for i = 1,360 do 
				delay(i/720,function()
					zeezy.Character.Humanoid.Sit = true
					zeezy.Character.HumanoidRootPart.CFrame = zeezy.Character.HumanoidRootPart.CFrame * CFrame.Angles(-h,0,0)
				end)
			end
			wait(0.55)
			zeezy.Character.Humanoid.Sit = false
		end
	end

	function zeezyBackflip(act,inp,obj)
		if inp == Enum.UserInputState.Begin then
			zeezy.Character.Humanoid:ChangeState("Jumping")
			wait()
			zeezy.Character.Humanoid.Sit = true
			for i = 1,360 do
				delay(i/720,function()
					zeezy.Character.Humanoid.Sit = true
					zeezy.Character.HumanoidRootPart.CFrame = zeezy.Character.HumanoidRootPart.CFrame * CFrame.Angles(h,0,0)
				end)
			end
			wait(0.55)
			zeezy.Character.Humanoid.Sit = false
		end
	end

	function zeezyAirjump(act,inp,obj)
		if inp == Enum.UserInputState.Begin then
			zeezy.Character:FindFirstChildOfClass'Humanoid':ChangeState("Seated")
			wait()
			zeezy.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")	
		end
	end


	--[[ Binds ]]--

	ca:BindAction("zeezyFrontflip",zeezyFrontflip,false,FrontflipKey)
	ca:BindAction("zeezyBackflip",zeezyBackflip,false,BackflipKey)
	ca:BindAction("zeezyAirjump",zeezyAirjump,false,AirjumpKey)

	--[[ Load Message ]]--

	print(scriptname .. " " .. ver .. " loaded successfully")
	print("made by Zeezy#7203")

	local notifSound = Instance.new("Sound",workspace)
	notifSound.PlaybackSpeed = 1.5
	notifSound.Volume = 0.15
	notifSound.SoundId = "rbxassetid://170765130"
	notifSound.PlayOnRemove = true
	notifSound:Destroy()
	game.StarterGui:SetCore("SendNotification", {Title = "feFlip", Text = "feFlip loaded successfully!", Icon = "rbxassetid://505845268", Duration = 5, Button1 = "Okay"})
end)

Teleport.Name = "Teleport"
Teleport.Parent = main
Teleport.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
Teleport.BorderColor3 = Color3.fromRGB(255, 0, 0)
Teleport.Position = UDim2.new(0.67582494, 0, 0.719583988, 0)
Teleport.Size = UDim2.new(0, 138, 0, 36)
Teleport.Font = Enum.Font.SciFi
Teleport.Text = "Teleport"
Teleport.TextColor3 = Color3.fromRGB(255, 0, 0)
Teleport.TextSize = 21.000
Teleport.MouseButton1Down:connect(function()
	mouse = game.Players.LocalPlayer:GetMouse()
	tool = Instance.new("Tool")
	tool.RequiresHandle = false
	tool.Name = "Click Teleport"
	tool.Activated:connect(function()
		local pos = mouse.Hit+Vector3.new(0,2.5,0)
		pos = CFrame.new(pos.X,pos.Y,pos.Z)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = pos
	end)
	tool.Parent = game.Players.LocalPlayer.Backpack
end)

TextLabel_2.Parent = main
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0.250861675, 0, 0.962406576, 0)
TextLabel_2.Size = UDim2.new(0, 217, 0, 11)
TextLabel_2.Font = Enum.Font.ArialBold
TextLabel_2.Text = "Disclaimer: Most of these only work on R6"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 14.000

JailBreak.Name = "Jail Break"
JailBreak.Parent = main
JailBreak.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
JailBreak.BorderColor3 = Color3.fromRGB(255, 0, 0)
JailBreak.Position = UDim2.new(1.02186513, 0, -0.043347694, 0)
JailBreak.Size = UDim2.new(0, 58, 0, 56)
JailBreak.Image = "http://www.roblox.com/asset/?id=981315971"
JailBreak.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Vynixius/main/Jailbreak/Jailbreak"))()
	-- Uploaded To youtube.com/1F0YT
end)

MM2.Name = "MM2"
MM2.Parent = main
MM2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MM2.BorderColor3 = Color3.fromRGB(255, 0, 0)
MM2.Position = UDim2.new(1.02186513, 0, 0.23491317, 0)
MM2.Size = UDim2.new(0, 58, 0, 56)
MM2.Image = "http://www.roblox.com/asset/?id=2655653681"
MM2.MouseButton1Down:connect(function()
	loadstring(game:GetObjects("rbxassetid://4001118261")[1].Source)()

	-- Made by Vynixu with love ;)
	-- lol enjoy
end)

RoCitizens.Name = "RoCitizens"
RoCitizens.Parent = main
RoCitizens.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
RoCitizens.BorderColor3 = Color3.fromRGB(255, 0, 0)
RoCitizens.Position = UDim2.new(1.02186513, 0, 0.791434884, 0)
RoCitizens.Size = UDim2.new(0, 58, 0, 56)
RoCitizens.Image = "http://www.roblox.com/asset/?id=819432156"
RoCitizens.MouseButton1Down:connect(function()
	-- Farewell Infortality.
	-- Version: 2.82
	-- Instances:
	local Rocitizengui = Instance.new("ScreenGui")
	local Rocitizens = Instance.new("Frame")
	local bar1 = Instance.new("Frame")
	local bar2 = Instance.new("Frame")
	local logo = Instance.new("ImageLabel")
	local Title = Instance.new("TextLabel")
	local StealthMoney1 = Instance.new("TextButton")
	local Teleports1 = Instance.new("TextButton")
	local EFLY = Instance.new("TextButton")
	local NNOCLIP = Instance.new("TextButton")
	local Gravity = Instance.new("TextButton")
	local StealthMoney2 = Instance.new("TextButton")
	local Teleports2 = Instance.new("TextButton")
	local Open = Instance.new("TextButton")
	local Close = Instance.new("TextButton")
	local GravityMenu = Instance.new("Frame")
	local NormalGravity = Instance.new("TextButton")
	local LowGravity = Instance.new("TextButton")
	local gexit = Instance.new("TextButton")
	local StealthMoneyFrame = Instance.new("Frame")
	local _1mil = Instance.new("TextButton")
	local _5mil = Instance.new("TextButton")
	local _10mil = Instance.new("TextButton")
	local _100mil = Instance.new("TextButton")
	local _500mil = Instance.new("TextButton")
	local _1bil = Instance.new("TextButton")
	local _5bil = Instance.new("TextButton")
	local _10bil = Instance.new("TextButton")
	local _100bil = Instance.new("TextButton")
	local _500bil = Instance.new("TextButton")
	local TeleportFrame = Instance.new("Frame")
	local Bank = Instance.new("TextButton")
	local HIghSchool = Instance.new("TextButton")
	local Cinema = Instance.new("TextButton")
	local CarShop = Instance.new("TextButton")
	local Garage = Instance.new("TextButton")
	local Baileys = Instance.new("TextButton")
	local Apartments = Instance.new("TextButton")
	local Hamburger = Instance.new("TextButton")
	local GasStation = Instance.new("TextButton")
	local Club = Instance.new("TextButton")
	local SuperMart = Instance.new("TextButton")
	local CriminalBase = Instance.new("TextButton")
	local Library = Instance.new("TextButton")
	local Museum = Instance.new("TextButton")
	local Hospital = Instance.new("TextButton")
	local Gym = Instance.new("TextButton")
	local PoliceStation = Instance.new("TextButton")
	local Plots = Instance.new("TextButton")
	--Properties:
	Rocitizengui.Name = "Rocitizen gui"
	Rocitizengui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

	Rocitizens.Name = "Rocitizens"
	Rocitizens.Parent = Rocitizengui
	Rocitizens.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
	Rocitizens.BorderColor3 = Color3.new(0, 0, 0)
	Rocitizens.BorderSizePixel = 2
	Rocitizens.Position = UDim2.new(0.119062312, 0, 0.135135129, 0)
	Rocitizens.Selectable = true
	Rocitizens.Size = UDim2.new(0, 225, 0, 593)
	Rocitizens.Visible = false

	bar1.Name = "bar1"
	bar1.Parent = Rocitizens
	bar1.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	bar1.BorderColor3 = Color3.new(0, 0, 0)
	bar1.Position = UDim2.new(-0.00175200403, 0, 0.000227883458, 0)
	bar1.Size = UDim2.new(0, 225, 0, 41)

	bar2.Name = "bar2"
	bar2.Parent = Rocitizens
	bar2.BackgroundColor3 = Color3.new(0.0392157, 0.0392157, 0.0392157)
	bar2.BorderColor3 = Color3.new(0, 0, 0)
	bar2.Position = UDim2.new(-0.00175200403, 0, 0.0691461861, 0)
	bar2.Size = UDim2.new(0, 225, 0, 9)

	logo.Name = "logo"
	logo.Parent = Rocitizens
	logo.BackgroundColor3 = Color3.new(1, 1, 1)
	logo.BackgroundTransparency = 1
	logo.Position = UDim2.new(0.74127084, 0, 0.000227883458, 0)
	logo.Size = UDim2.new(0, 58, 0, 41)
	logo.Image = "rbxassetid://2498158349"

	Title.Name = "Title"
	Title.Parent = Rocitizens
	Title.BackgroundColor3 = Color3.new(1, 1, 1)
	Title.BackgroundTransparency = 1
	Title.Position = UDim2.new(-0.00175200403, 0, 0.000227883458, 0)
	Title.Size = UDim2.new(0, 167, 0, 41)
	Title.Font = Enum.Font.SourceSans
	Title.Text = "Penguin GUI"
	Title.TextColor3 = Color3.new(1, 1, 1)
	Title.TextScaled = true
	Title.TextSize = 14
	Title.TextWrapped = true

	StealthMoney1.Name = "Stealth Money1"
	StealthMoney1.Parent = Rocitizens
	StealthMoney1.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	StealthMoney1.BorderColor3 = Color3.new(0, 0, 0)
	StealthMoney1.BorderSizePixel = 2
	StealthMoney1.Position = UDim2.new(0.0533333346, 0, 0.119730182, 0)
	StealthMoney1.Size = UDim2.new(0, 200, 0, 70)
	StealthMoney1.Font = Enum.Font.SourceSans
	StealthMoney1.Text = "Stealth Money"
	StealthMoney1.TextColor3 = Color3.new(1, 1, 1)
	StealthMoney1.TextScaled = true
	StealthMoney1.TextSize = 14
	StealthMoney1.TextWrapped = true
	StealthMoney1.MouseButton1Down:connect(function()
		StealthMoneyFrame.Visible = true
		StealthMoney1.Visible = false
		StealthMoney2.Visible = true
	end)

	Teleports1.Name = "Teleports1"
	Teleports1.Parent = Rocitizens
	Teleports1.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Teleports1.BorderColor3 = Color3.new(0, 0, 0)
	Teleports1.BorderSizePixel = 2
	Teleports1.Position = UDim2.new(0.0533333346, 0, 0.328836411, 0)
	Teleports1.Size = UDim2.new(0, 200, 0, 70)
	Teleports1.Font = Enum.Font.SourceSans
	Teleports1.Text = "Teleport Menu"
	Teleports1.TextColor3 = Color3.new(1, 1, 1)
	Teleports1.TextScaled = true
	Teleports1.TextSize = 14
	Teleports1.TextWrapped = true
	Teleports1.MouseButton1Down:connect(function()
		TeleportFrame.Visible = true
		Teleports1.Visible = false
		Teleports2.Visible = true
	end)

	EFLY.Name = "EFLY"
	EFLY.Parent = Rocitizens
	EFLY.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	EFLY.BorderColor3 = Color3.new(0, 0, 0)
	EFLY.BorderSizePixel = 2
	EFLY.Position = UDim2.new(0.0533333346, 0, 0.507588506, 0)
	EFLY.Size = UDim2.new(0, 200, 0, 70)
	EFLY.Font = Enum.Font.SourceSans
	EFLY.Text = "E to Teleport"
	EFLY.TextColor3 = Color3.new(1, 1, 1)
	EFLY.TextScaled = true
	EFLY.TextSize = 14
	EFLY.TextWrapped = true
	EFLY.MouseButton1Down:connect(function()
		plr = game.Players.LocalPlayer 
		hum = plr.Character.HumanoidRootPart
		mouse = plr:GetMouse() 
		mouse.KeyDown:connect(function(key) 
			if key == "e" then 
				if mouse.Target then 
					hum.CFrame = CFrame.new(mouse.Hit.x, mouse.Hit.y + 5, mouse.Hit.z) 
				end 
			end 
		end)
	end)

	NNOCLIP.Name = "NNOCLIP"
	NNOCLIP.Parent = Rocitizens
	NNOCLIP.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	NNOCLIP.BorderColor3 = Color3.new(0, 0, 0)
	NNOCLIP.BorderSizePixel = 2
	NNOCLIP.Position = UDim2.new(0.0533333346, 0, 0.674536228, 0)
	NNOCLIP.Size = UDim2.new(0, 200, 0, 70)
	NNOCLIP.Font = Enum.Font.SourceSans
	NNOCLIP.Text = "N to Noclip"
	NNOCLIP.TextColor3 = Color3.new(1, 1, 1)
	NNOCLIP.TextScaled = true
	NNOCLIP.TextSize = 14
	NNOCLIP.TextWrapped = true
	NNOCLIP.MouseButton1Down:connect(function()
		noclip = false
		game:GetService('RunService').Stepped:connect(function()
			if noclip then
				game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
			end
		end)
		plr = game.Players.LocalPlayer
		mouse = plr:GetMouse()
		mouse.KeyDown:connect(function(key)

			if key == "n" then
				noclip = not noclip
				game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
			end
		end)
		print('Loaded')
		print('Press "N" to noclip')
	end)

	Gravity.Name = "Gravity"
	Gravity.Parent = Rocitizens
	Gravity.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Gravity.BorderColor3 = Color3.new(0, 0, 0)
	Gravity.BorderSizePixel = 2
	Gravity.Position = UDim2.new(0.0533333346, 0, 0.84485662, 0)
	Gravity.Size = UDim2.new(0, 200, 0, 70)
	Gravity.Font = Enum.Font.SourceSans
	Gravity.Text = "Gravity menu"
	Gravity.TextColor3 = Color3.new(1, 1, 1)
	Gravity.TextScaled = true
	Gravity.TextSize = 14
	Gravity.TextWrapped = true
	Gravity.MouseButton1Down:connect(function()
		GravityMenu.Visible = true
	end)


	StealthMoney2.Name = "Stealth Money2"
	StealthMoney2.Parent = Rocitizens
	StealthMoney2.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	StealthMoney2.BorderColor3 = Color3.new(0, 0, 0)
	StealthMoney2.BorderSizePixel = 2
	StealthMoney2.Position = UDim2.new(0.0533333346, 0, 0.119730182, 0)
	StealthMoney2.Size = UDim2.new(0, 200, 0, 70)
	StealthMoney2.Visible = false
	StealthMoney2.Font = Enum.Font.SourceSans
	StealthMoney2.Text = "< Back >"
	StealthMoney2.TextColor3 = Color3.new(1, 1, 1)
	StealthMoney2.TextScaled = true
	StealthMoney2.TextSize = 14
	StealthMoney2.TextWrapped = true
	StealthMoney2.MouseButton1Down:connect(function()
		StealthMoneyFrame.Visible = false
		StealthMoney2.Visible = false
		StealthMoney1.Visible = true
	end)

	Teleports2.Name = "Teleports2"
	Teleports2.Parent = Rocitizens
	Teleports2.BackgroundColor3 = Color3.new(0.0784314, 0.0784314, 0.0784314)
	Teleports2.BorderColor3 = Color3.new(0, 0, 0)
	Teleports2.BorderSizePixel = 2
	Teleports2.Position = UDim2.new(0.0533333346, 0, 0.328836411, 0)
	Teleports2.Size = UDim2.new(0, 200, 0, 70)
	Teleports2.Visible = false
	Teleports2.Font = Enum.Font.SourceSans
	Teleports2.Text = "< Back >"
	Teleports2.TextColor3 = Color3.new(1, 1, 1)
	Teleports2.TextScaled = true
	Teleports2.TextSize = 14
	Teleports2.TextWrapped = true
	Teleports2.MouseButton1Down:connect(function()
		TeleportFrame.Visible = false
		Teleports2.Visible = false
		Teleports1.Visible = true
	end)

	Open.Name = "Open"
	Open.Parent = Rocitizengui
	Open.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
	Open.BorderColor3 = Color3.new(0, 0, 0)
	Open.BorderSizePixel = 2
	Open.Position = UDim2.new(0, 0, 0.464373469, 0)
	Open.Size = UDim2.new(0, 125, 0, 52)
	Open.Font = Enum.Font.SourceSans
	Open.Text = "Open"
	Open.TextColor3 = Color3.new(1, 1, 1)
	Open.TextScaled = true
	Open.TextSize = 14
	Open.TextWrapped = true
	Open.MouseButton1Down:connect(function()
		Open.Visible  = false
		Close.Visible = true
		Rocitizens.Visible = true
	end)


	Close.Name = "Close"
	Close.Parent = Rocitizengui
	Close.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
	Close.BorderColor3 = Color3.new(0, 0, 0)
	Close.BorderSizePixel = 2
	Close.Position = UDim2.new(0, 0, 0.464373469, 0)
	Close.Size = UDim2.new(0, 125, 0, 52)
	Close.Visible = false
	Close.Font = Enum.Font.SourceSans
	Close.Text = "Close"
	Close.TextColor3 = Color3.new(1, 1, 1)
	Close.TextScaled = true
	Close.TextSize = 14
	Close.TextWrapped = true
	Close.MouseButton1Down:connect(function()
		Rocitizens.Visible = false
		GravityMenu.Visible = false
		StealthMoneyFrame.Visible = false
		TeleportFrame.Visible = false
		Close.Visible = false
		Open.Visible = true
	end)

	GravityMenu.Name = "Gravity Menu"
	GravityMenu.Parent = Rocitizengui
	GravityMenu.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
	GravityMenu.BorderColor3 = Color3.new(0, 0, 0)
	GravityMenu.BorderSizePixel = 2
	GravityMenu.Position = UDim2.new(0.761258483, 0, 0.0159705523, 0)
	GravityMenu.Size = UDim2.new(0, 373, 0, 238)
	GravityMenu.Visible = false

	NormalGravity.Name = "Normal Gravity"
	NormalGravity.Parent = GravityMenu
	NormalGravity.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
	NormalGravity.BorderColor3 = Color3.new(0, 0, 0)
	NormalGravity.Position = UDim2.new(0.0190571956, 0, 0.318427384, 0)
	NormalGravity.Size = UDim2.new(0, 176, 0, 140)
	NormalGravity.Font = Enum.Font.SourceSans
	NormalGravity.Text = "Normal Gravity"
	NormalGravity.TextColor3 = Color3.new(1, 1, 1)
	NormalGravity.TextScaled = true
	NormalGravity.TextSize = 14
	NormalGravity.TextWrapped = true
	NormalGravity.MouseButton1Down:connect(function()
		game.Workspace.Gravity = 200
	end)

	LowGravity.Name = "Low Gravity"
	LowGravity.Parent = GravityMenu
	LowGravity.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
	LowGravity.BorderColor3 = Color3.new(0, 0, 0)
	LowGravity.Position = UDim2.new(0.516763508, 0, 0.319327742, 0)
	LowGravity.Size = UDim2.new(0, 173, 0, 140)
	LowGravity.Font = Enum.Font.SourceSans
	LowGravity.Text = "Low Gravity"
	LowGravity.TextColor3 = Color3.new(1, 1, 1)
	LowGravity.TextScaled = true
	LowGravity.TextSize = 14
	LowGravity.TextWrapped = true
	LowGravity.MouseButton1Down:connect(function()
		game.Workspace.Gravity = 50
	end)

	gexit.Name = "gexit"
	gexit.Parent = GravityMenu
	gexit.BackgroundColor3 = Color3.new(0.52549, 0, 0.00784314)
	gexit.BorderColor3 = Color3.new(0, 0, 0)
	gexit.BorderSizePixel = 2
	gexit.Position = UDim2.new(0.230563, 0, 0, 0)
	gexit.Size = UDim2.new(0, 200, 0, 50)
	gexit.Font = Enum.Font.SourceSans
	gexit.Text = "< Back >"
	gexit.TextColor3 = Color3.new(0, 0, 0)
	gexit.TextScaled = true
	gexit.TextSize = 14
	gexit.TextWrapped = true
	gexit.MouseButton1Down:connect(function()
		GravityMenu.Visible = false
	end)


	StealthMoneyFrame.Name = "StealthMoneyFrame"
	StealthMoneyFrame.Parent = Rocitizengui
	StealthMoneyFrame.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
	StealthMoneyFrame.BorderColor3 = Color3.new(0, 0, 0)
	StealthMoneyFrame.Position = UDim2.new(0.281307846, 0, 0.135135129, 0)
	StealthMoneyFrame.Size = UDim2.new(0, 203, 0, 593)
	StealthMoneyFrame.Visible = false

	_1mil.Name = "1mil"
	_1mil.Parent = StealthMoneyFrame
	_1mil.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	_1mil.BorderColor3 = Color3.new(0, 0, 0)
	_1mil.Size = UDim2.new(0, 203, 0, 60)
	_1mil.Font = Enum.Font.SourceSans
	_1mil.Text = "1Mil+"
	_1mil.TextColor3 = Color3.new(1, 1, 1)
	_1mil.TextScaled = true
	_1mil.TextSize = 14
	_1mil.TextWrapped = true
	_1mil.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.ChangeMoney:Fire(1000000)
	end)

	_5mil.Name = "5mil"
	_5mil.Parent = StealthMoneyFrame
	_5mil.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	_5mil.BorderColor3 = Color3.new(0, 0, 0)
	_5mil.Position = UDim2.new(0, 0, 0.101180442, 0)
	_5mil.Size = UDim2.new(0, 203, 0, 60)
	_5mil.Font = Enum.Font.SourceSans
	_5mil.Text = "5Mil+"
	_5mil.TextColor3 = Color3.new(1, 1, 1)
	_5mil.TextScaled = true
	_5mil.TextSize = 14
	_5mil.TextWrapped = true
	_5mil.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.ChangeMoney:Fire(5000000)
	end)

	_10mil.Name = "10mil"
	_10mil.Parent = StealthMoneyFrame
	_10mil.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	_10mil.BorderColor3 = Color3.new(0, 0, 0)
	_10mil.Position = UDim2.new(0, 0, 0.202360883, 0)
	_10mil.Size = UDim2.new(0, 203, 0, 60)
	_10mil.Font = Enum.Font.SourceSans
	_10mil.Text = "10Mil+"
	_10mil.TextColor3 = Color3.new(1, 1, 1)
	_10mil.TextScaled = true
	_10mil.TextSize = 14
	_10mil.TextWrapped = true
	_10mil.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.ChangeMoney:Fire(10000000)
	end)

	_100mil.Name = "100mil"
	_100mil.Parent = StealthMoneyFrame
	_100mil.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	_100mil.BorderColor3 = Color3.new(0, 0, 0)
	_100mil.Position = UDim2.new(0, 0, 0.303541332, 0)
	_100mil.Size = UDim2.new(0, 203, 0, 60)
	_100mil.Font = Enum.Font.SourceSans
	_100mil.Text = "100Mil+"
	_100mil.TextColor3 = Color3.new(1, 1, 1)
	_100mil.TextScaled = true
	_100mil.TextSize = 14
	_100mil.TextWrapped = true
	_100mil.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.ChangeMoney:Fire(100000000)
	end)

	_500mil.Name = "500mil"
	_500mil.Parent = StealthMoneyFrame
	_500mil.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	_500mil.BorderColor3 = Color3.new(0, 0, 0)
	_500mil.Position = UDim2.new(0, 0, 0.392917395, 0)
	_500mil.Size = UDim2.new(0, 203, 0, 60)
	_500mil.Font = Enum.Font.SourceSans
	_500mil.Text = "500Mil+"
	_500mil.TextColor3 = Color3.new(1, 1, 1)
	_500mil.TextScaled = true
	_500mil.TextSize = 14
	_500mil.TextWrapped = true
	_500mil.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.ChangeMoney:Fire(500000000)
	end)

	_1bil.Name = "1bil"
	_1bil.Parent = StealthMoneyFrame
	_1bil.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	_1bil.BorderColor3 = Color3.new(0, 0, 0)
	_1bil.Position = UDim2.new(0, 0, 0.494097829, 0)
	_1bil.Size = UDim2.new(0, 203, 0, 60)
	_1bil.Font = Enum.Font.SourceSans
	_1bil.Text = "1Bil+"
	_1bil.TextColor3 = Color3.new(1, 1, 1)
	_1bil.TextScaled = true
	_1bil.TextSize = 14
	_1bil.TextWrapped = true
	_1bil.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.ChangeMoney:Fire(1000000000)
	end)

	_5bil.Name = "5bil"
	_5bil.Parent = StealthMoneyFrame
	_5bil.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	_5bil.BorderColor3 = Color3.new(0, 0, 0)
	_5bil.Position = UDim2.new(0, 0, 0.595278263, 0)
	_5bil.Size = UDim2.new(0, 203, 0, 60)
	_5bil.Font = Enum.Font.SourceSans
	_5bil.Text = "5Bil+"
	_5bil.TextColor3 = Color3.new(1, 1, 1)
	_5bil.TextScaled = true
	_5bil.TextSize = 14
	_5bil.TextWrapped = true
	_5bil.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.ChangeMoney:Fire(5000000000)
	end)

	_10bil.Name = "10bil"
	_10bil.Parent = StealthMoneyFrame
	_10bil.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	_10bil.BorderColor3 = Color3.new(0, 0, 0)
	_10bil.Position = UDim2.new(0, 0, 0.696458697, 0)
	_10bil.Size = UDim2.new(0, 203, 0, 60)
	_10bil.Font = Enum.Font.SourceSans
	_10bil.Text = "10Bil+"
	_10bil.TextColor3 = Color3.new(1, 1, 1)
	_10bil.TextScaled = true
	_10bil.TextSize = 14
	_10bil.TextWrapped = true
	_10bil.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.ChangeMoney:Fire(10000000000)
	end)

	_100bil.Name = "100bil"
	_100bil.Parent = StealthMoneyFrame
	_100bil.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	_100bil.BorderColor3 = Color3.new(0, 0, 0)
	_100bil.Position = UDim2.new(0, 0, 0.797639132, 0)
	_100bil.Size = UDim2.new(0, 203, 0, 60)
	_100bil.Font = Enum.Font.SourceSans
	_100bil.Text = "100Bil+"
	_100bil.TextColor3 = Color3.new(1, 1, 1)
	_100bil.TextScaled = true
	_100bil.TextSize = 14
	_100bil.TextWrapped = true
	_100bil.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.ChangeMoney:Fire(100000000000)
	end)

	_500bil.Name = "500bil"
	_500bil.Parent = StealthMoneyFrame
	_500bil.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	_500bil.BorderColor3 = Color3.new(0, 0, 0)
	_500bil.Position = UDim2.new(0, 0, 0.898819566, 0)
	_500bil.Size = UDim2.new(0, 203, 0, 60)
	_500bil.Font = Enum.Font.SourceSans
	_500bil.Text = "500Bil+"
	_500bil.TextColor3 = Color3.new(1, 1, 1)
	_500bil.TextScaled = true
	_500bil.TextSize = 14
	_500bil.TextWrapped = true
	_500bil.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.ChangeMoney:Fire(500000000000)
	end)

	TeleportFrame.Name = "TeleportFrame"
	TeleportFrame.Parent = Rocitizengui
	TeleportFrame.BackgroundColor3 = Color3.new(0.117647, 0.117647, 0.117647)
	TeleportFrame.BorderColor3 = Color3.new(0, 0, 0)
	TeleportFrame.BorderSizePixel = 2
	TeleportFrame.Position = UDim2.new(0.431215286, 0, 0.135135129, 0)
	TeleportFrame.Size = UDim2.new(0, 202, 0, 593)
	TeleportFrame.Visible = false

	Bank.Name = "Bank"
	Bank.Parent = TeleportFrame
	Bank.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	Bank.BorderColor3 = Color3.new(0, 0, 0)
	Bank.BorderSizePixel = 2
	Bank.Size = UDim2.new(0, 202, 0, 33)
	Bank.Font = Enum.Font.SourceSans
	Bank.Text = "Bank"
	Bank.TextColor3 = Color3.new(1, 1, 1)
	Bank.TextScaled = true
	Bank.TextSize = 14
	Bank.TextWrapped = true
	Bank.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-89.6001, 47.2, 1371.2))
	end)

	HIghSchool.Name = "HIgh School"
	HIghSchool.Parent = TeleportFrame
	HIghSchool.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	HIghSchool.BorderColor3 = Color3.new(0, 0, 0)
	HIghSchool.BorderSizePixel = 2
	HIghSchool.Position = UDim2.new(0, 0, 0.0553278551, 0)
	HIghSchool.Size = UDim2.new(0, 202, 0, 33)
	HIghSchool.Font = Enum.Font.SourceSans
	HIghSchool.Text = "High School"
	HIghSchool.TextColor3 = Color3.new(1, 1, 1)
	HIghSchool.TextScaled = true
	HIghSchool.TextSize = 14
	HIghSchool.TextWrapped = true
	HIghSchool.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-124.7, 42.3, 774.094))
	end)

	Cinema.Name = "Cinema"
	Cinema.Parent = TeleportFrame
	Cinema.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	Cinema.BorderColor3 = Color3.new(0, 0, 0)
	Cinema.BorderSizePixel = 2
	Cinema.Position = UDim2.new(0, 0, 0.110655732, 0)
	Cinema.Size = UDim2.new(0, 202, 0, 33)
	Cinema.Font = Enum.Font.SourceSans
	Cinema.Text = "Cinema"
	Cinema.TextColor3 = Color3.new(1, 1, 1)
	Cinema.TextScaled = true
	Cinema.TextSize = 14
	Cinema.TextWrapped = true
	Cinema.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.Character:MoveTo(Vector3.new(593.378, 61.2, 467.222))
	end)

	CarShop.Name = "CarShop"
	CarShop.Parent = TeleportFrame
	CarShop.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	CarShop.BorderColor3 = Color3.new(0, 0, 0)
	CarShop.BorderSizePixel = 2
	CarShop.Position = UDim2.new(0, 0, 0.165983617, 0)
	CarShop.Size = UDim2.new(0, 202, 0, 33)
	CarShop.Font = Enum.Font.SourceSans
	CarShop.Text = "CarShop"
	CarShop.TextColor3 = Color3.new(1, 1, 1)
	CarShop.TextScaled = true
	CarShop.TextSize = 14
	CarShop.TextWrapped = true
	CarShop.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.Character:MoveTo(Vector3.new(366.530609, 39.6500092, 561.46991))
	end)

	Garage.Name = "Garage"
	Garage.Parent = TeleportFrame
	Garage.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	Garage.BorderColor3 = Color3.new(0, 0, 0)
	Garage.BorderSizePixel = 2
	Garage.Position = UDim2.new(0, 0, 0.221311465, 0)
	Garage.Size = UDim2.new(0, 202, 0, 33)
	Garage.Font = Enum.Font.SourceSans
	Garage.Text = "Garage"
	Garage.TextColor3 = Color3.new(1, 1, 1)
	Garage.TextScaled = true
	Garage.TextSize = 14
	Garage.TextWrapped = true
	Garage.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.Character:MoveTo(Vector3.new(617.86792, 39.8500099, 222.204208))
	end)

	Baileys.Name = "Bailey's"
	Baileys.Parent = TeleportFrame
	Baileys.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	Baileys.BorderColor3 = Color3.new(0, 0, 0)
	Baileys.BorderSizePixel = 2
	Baileys.Position = UDim2.new(0, 0, 0.276639313, 0)
	Baileys.Size = UDim2.new(0, 202, 0, 33)
	Baileys.Font = Enum.Font.SourceSans
	Baileys.Text = "Bailey's"
	Baileys.TextColor3 = Color3.new(1, 1, 1)
	Baileys.TextScaled = true
	Baileys.TextSize = 14
	Baileys.TextWrapped = true
	Baileys.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.Character:MoveTo(Vector3.new(543.76062, 39.8500099, 43.1453667))
	end)

	Apartments.Name = "Apartments"
	Apartments.Parent = TeleportFrame
	Apartments.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	Apartments.BorderColor3 = Color3.new(0, 0, 0)
	Apartments.BorderSizePixel = 2
	Apartments.Position = UDim2.new(0, 0, 0.331967235, 0)
	Apartments.Size = UDim2.new(0, 202, 0, 33)
	Apartments.Font = Enum.Font.SourceSans
	Apartments.Text = "Apartments"
	Apartments.TextColor3 = Color3.new(1, 1, 1)
	Apartments.TextScaled = true
	Apartments.TextSize = 14
	Apartments.TextWrapped = true
	Apartments.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.Character:MoveTo(Vector3.new(509.568024, 39.8500099, 117.027695))
	end)

	Hamburger.Name = "Hamburger"
	Hamburger.Parent = TeleportFrame
	Hamburger.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	Hamburger.BorderColor3 = Color3.new(0, 0, 0)
	Hamburger.BorderSizePixel = 2
	Hamburger.Position = UDim2.new(0, 0, 0.387295038, 0)
	Hamburger.Size = UDim2.new(0, 202, 0, 33)
	Hamburger.Font = Enum.Font.SourceSans
	Hamburger.Text = "Hamburger"
	Hamburger.TextColor3 = Color3.new(1, 1, 1)
	Hamburger.TextScaled = true
	Hamburger.TextSize = 14
	Hamburger.TextWrapped = true
	Hamburger.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.Character:MoveTo(Vector3.new(414.374298, 39.8500099, 366.701843))
	end)

	GasStation.Name = "Gas Station"
	GasStation.Parent = TeleportFrame
	GasStation.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	GasStation.BorderColor3 = Color3.new(0, 0, 0)
	GasStation.BorderSizePixel = 2
	GasStation.Position = UDim2.new(0, 0, 0.44262293, 0)
	GasStation.Size = UDim2.new(0, 202, 0, 33)
	GasStation.Font = Enum.Font.SourceSans
	GasStation.Text = "Gas Station"
	GasStation.TextColor3 = Color3.new(1, 1, 1)
	GasStation.TextScaled = true
	GasStation.TextSize = 14
	GasStation.TextWrapped = true
	GasStation.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.Character:MoveTo(Vector3.new(348.957458, 39.6500092, 457.277496))
	end)

	Club.Name = "Club"
	Club.Parent = TeleportFrame
	Club.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	Club.BorderColor3 = Color3.new(0, 0, 0)
	Club.BorderSizePixel = 2
	Club.Position = UDim2.new(0, 0, 0.497950852, 0)
	Club.Size = UDim2.new(0, 202, 0, 33)
	Club.Font = Enum.Font.SourceSans
	Club.Text = "Club"
	Club.TextColor3 = Color3.new(1, 1, 1)
	Club.TextScaled = true
	Club.TextSize = 14
	Club.TextWrapped = true
	Club.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.Character:MoveTo(Vector3.new(506.477844, 40.2500153, 891.893738))
	end)

	SuperMart.Name = "SuperMart"
	SuperMart.Parent = TeleportFrame
	SuperMart.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	SuperMart.BorderColor3 = Color3.new(0, 0, 0)
	SuperMart.BorderSizePixel = 2
	SuperMart.Position = UDim2.new(0, 0, 0.553278685, 0)
	SuperMart.Size = UDim2.new(0, 202, 0, 33)
	SuperMart.Font = Enum.Font.SourceSans
	SuperMart.Text = "SuperMart"
	SuperMart.TextColor3 = Color3.new(1, 1, 1)
	SuperMart.TextScaled = true
	SuperMart.TextSize = 14
	SuperMart.TextWrapped = true
	SuperMart.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.Character:MoveTo(Vector3.new(306.922485, 39.8597755, 866.421509))
	end)

	CriminalBase.Name = "Criminal Base"
	CriminalBase.Parent = TeleportFrame
	CriminalBase.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	CriminalBase.BorderColor3 = Color3.new(0, 0, 0)
	CriminalBase.BorderSizePixel = 2
	CriminalBase.Position = UDim2.new(0, 0, 0.608606577, 0)
	CriminalBase.Size = UDim2.new(0, 202, 0, 33)
	CriminalBase.Font = Enum.Font.SourceSans
	CriminalBase.Text = "Criminal Base"
	CriminalBase.TextColor3 = Color3.new(1, 1, 1)
	CriminalBase.TextScaled = true
	CriminalBase.TextSize = 14
	CriminalBase.TextWrapped = true
	CriminalBase.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.Character:MoveTo(Vector3.new(678.209106, 39.8500099, 840.987732))
	end)

	Library.Name = "Library"
	Library.Parent = TeleportFrame
	Library.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	Library.BorderColor3 = Color3.new(0, 0, 0)
	Library.BorderSizePixel = 2
	Library.Position = UDim2.new(0, 0, 0.668032765, 0)
	Library.Size = UDim2.new(0, 202, 0, 33)
	Library.Font = Enum.Font.SourceSans
	Library.Text = "Library"
	Library.TextColor3 = Color3.new(1, 1, 1)
	Library.TextScaled = true
	Library.TextSize = 14
	Library.TextWrapped = true
	Library.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.Character:MoveTo(Vector3.new(424.386597, 39.8500099, 1119.21436))

	end)

	Museum.Name = "Museum"
	Museum.Parent = TeleportFrame
	Museum.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	Museum.BorderColor3 = Color3.new(0, 0, 0)
	Museum.BorderSizePixel = 2
	Museum.Position = UDim2.new(0, 0, 0.723360658, 0)
	Museum.Size = UDim2.new(0, 202, 0, 33)
	Museum.Font = Enum.Font.SourceSans
	Museum.Text = "Museum"
	Museum.TextColor3 = Color3.new(1, 1, 1)
	Museum.TextScaled = true
	Museum.TextSize = 14
	Museum.TextWrapped = true
	Museum.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.Character:MoveTo(Vector3.new(616.659119, 40.2500153, 1363.78442))

	end)

	Hospital.Name = "Hospital"
	Hospital.Parent = TeleportFrame
	Hospital.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	Hospital.BorderColor3 = Color3.new(0, 0, 0)
	Hospital.BorderSizePixel = 2
	Hospital.Position = UDim2.new(0, 0, 0.77868861, 0)
	Hospital.Size = UDim2.new(0, 202, 0, 33)
	Hospital.Font = Enum.Font.SourceSans
	Hospital.Text = "Hospital"
	Hospital.TextColor3 = Color3.new(1, 1, 1)
	Hospital.TextScaled = true
	Hospital.TextSize = 14
	Hospital.TextWrapped = true
	Hospital.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.Character:MoveTo(Vector3.new(137.416245, 39.8500099, 1463.74634))
	end)

	Gym.Name = "Gym"
	Gym.Parent = TeleportFrame
	Gym.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	Gym.BorderColor3 = Color3.new(0, 0, 0)
	Gym.BorderSizePixel = 2
	Gym.Position = UDim2.new(0, 0, 0.834016383, 0)
	Gym.Size = UDim2.new(0, 202, 0, 33)
	Gym.Font = Enum.Font.SourceSans
	Gym.Text = "Gym"
	Gym.TextColor3 = Color3.new(1, 1, 1)
	Gym.TextScaled = true
	Gym.TextSize = 14
	Gym.TextWrapped = true
	Gym.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.Character:MoveTo(Vector3.new(176.828949, 39.8500099, 1208.14514))
	end)

	PoliceStation.Name = "Police Station"
	PoliceStation.Parent = TeleportFrame
	PoliceStation.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	PoliceStation.BorderColor3 = Color3.new(0, 0, 0)
	PoliceStation.BorderSizePixel = 2
	PoliceStation.Position = UDim2.new(0, 0, 0.889344275, 0)
	PoliceStation.Size = UDim2.new(0, 202, 0, 33)
	PoliceStation.Font = Enum.Font.SourceSans
	PoliceStation.Text = "Police Station"
	PoliceStation.TextColor3 = Color3.new(1, 1, 1)
	PoliceStation.TextScaled = true
	PoliceStation.TextSize = 14
	PoliceStation.TextWrapped = true
	PoliceStation.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-38.1218109, 42.6500092, 597.40094))
	end)

	Plots.Name = "Plots"
	Plots.Parent = TeleportFrame
	Plots.BackgroundColor3 = Color3.new(0.0745098, 0.0745098, 0.0745098)
	Plots.BorderColor3 = Color3.new(0, 0, 0)
	Plots.BorderSizePixel = 2
	Plots.Position = UDim2.new(0, 0, 0.944672108, 0)
	Plots.Size = UDim2.new(0, 202, 0, 33)
	Plots.Font = Enum.Font.SourceSans
	Plots.Text = "Plots"
	Plots.TextColor3 = Color3.new(1, 1, 1)
	Plots.TextScaled = true
	Plots.TextSize = 14
	Plots.TextWrapped = true
	Plots.MouseButton1Down:connect(function()
		game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-9.09812069, 39.8500023, -251.339005))
	end)
end)

PrisonLife.Name = "Prison Life"
PrisonLife.Parent = main
PrisonLife.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PrisonLife.BorderColor3 = Color3.fromRGB(255, 0, 0)
PrisonLife.Position = UDim2.new(1.02186513, 0, 0.513173997, 0)
PrisonLife.Size = UDim2.new(0, 58, 0, 56)
PrisonLife.Image = "http://www.roblox.com/asset/?id=958491230"
PrisonLife.MouseButton1Down:connect(function()
	--[[
    88""Yb  88""Yb  888888 Yb    dP    db     88  88      Yb  dP
    88__dP  88__dP  88__    Yb  dP    dPYb    88  88       YbdP 
    88"""   88"Yb   88""     YbdP    dP__Yb   88  88  .o   dPYb 
    88      88  Yb  888888    YP    dP""""Yb  88  88ood8  dP  Yb  ~02hacks
]]
	loadstring(game:HttpGet("https://pastebin.com/raw/mHfK0Xk4", true))()
end)

NaturalDisaster.Name = "Natural Disaster"
NaturalDisaster.Parent = main
NaturalDisaster.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
NaturalDisaster.BorderColor3 = Color3.fromRGB(255, 0, 0)
NaturalDisaster.Position = UDim2.new(-0.156784058, 0, 0.23491317, 0)
NaturalDisaster.Size = UDim2.new(0, 58, 0, 56)
NaturalDisaster.Image = "http://www.roblox.com/asset/?id=949129290"
NaturalDisaster.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/2dgeneralspam1/scripts-and-stuff/master/scripts/garfield%20hub", true))()
end)

CounterBlox.Name = "Counter Blox"
CounterBlox.Parent = main
CounterBlox.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CounterBlox.BorderColor3 = Color3.fromRGB(255, 0, 0)
CounterBlox.Position = UDim2.new(-0.156784058, 0, 0.513173997, 0)
CounterBlox.Size = UDim2.new(0, 58, 0, 56)
CounterBlox.Image = "http://www.roblox.com/asset/?id=1081912120"
CounterBlox.MouseButton1Down:connect(function()
	local old
	old = hookfunction(game.HttpGetAsync, function(inst, url, state)
		url = url:gsub('CriShoux', 'SiLeNSwOrD')
		return old(inst, url, state)
	end)

	local old2
	old2 = hookfunction(game.HttpGet, function(inst, url, state)
		url = url:gsub('CriShoux', 'SiLeNSwOrD')
		return old2(inst, url, state)
	end)

	loadstring(game:HttpGet("https://raw.githubusercontent.com/SiLeNSwOrD/OwlHub/master/OwlHub.txt"))()
	-- subscribe to sakpot
end)

MadCity.Name = "Mad City"
MadCity.Parent = main
MadCity.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MadCity.BorderColor3 = Color3.fromRGB(255, 0, 0)
MadCity.Position = UDim2.new(-0.156784058, 0, 0.791434884, 0)
MadCity.Size = UDim2.new(0, 58, 0, 56)
MadCity.Image = "http://www.roblox.com/asset/?id=4793277285"
MadCity.MouseButton1Down:connect(function()
	--[[
CLICK FULLSCREEN TO CTRL A
	Mad-Lads v7!
	Lots of new things..
	New EPIC UI by Jan
	Best Mad City GUI?
	Press F8 to toggle the GUI!
]]

	--=Important=--
	_G.Height = false
	--=False = height is kinda high above the ground (No Reset Required)=--
	--=True = height is lowered alot but reset is required=--

	local SynapseXen_liIlillIlIIllIi=select;local SynapseXen_IliIl=string.byte;local SynapseXen_llIIIiIilllIliIiliil=string.sub;local SynapseXen_iilIIiIIIl=string.char;local SynapseXen_iIIllii=type;local SynapseXen_llliI=table.concat;local unpack=unpack;local setmetatable=setmetatable;local pcall=pcall;local SynapseXen_IIliiilliIlliIi,SynapseXen_lIIIIIlililliIillIl,SynapseXen_IiilIiiIiIll,SynapseXen_IiiiIiliIlIIlIillll;if bit and bit.bxor then SynapseXen_IIliiilliIlliIi=bit.bxor;SynapseXen_lIIIIIlililliIillIl=function(SynapseXen_iIilii,SynapseXen_lilIli)local SynapseXen_IiliIiiliIlilliII=SynapseXen_IIliiilliIlliIi(SynapseXen_iIilii,SynapseXen_lilIli)if SynapseXen_IiliIiiliIlilliII<0 then SynapseXen_IiliIiiliIlilliII=4294967296+SynapseXen_IiliIiiliIlilliII end;return SynapseXen_IiliIiiliIlilliII end else SynapseXen_IIliiilliIlliIi=function(SynapseXen_iIilii,SynapseXen_lilIli)local SynapseXen_lIliIIIIliIi=function(SynapseXen_lIIlIlIIiiIli,SynapseXen_IiIli)return SynapseXen_lIIlIlIIiiIli%(SynapseXen_IiIli*2)>=SynapseXen_IiIli end;local SynapseXen_lIIlIlIlliIll=0;for SynapseXen_lliiiliiiiI=0,31 do SynapseXen_lIIlIlIlliIll=SynapseXen_lIIlIlIlliIll+(SynapseXen_lIliIIIIliIi(SynapseXen_iIilii,2^SynapseXen_lliiiliiiiI)~=SynapseXen_lIliIIIIliIi(SynapseXen_lilIli,2^SynapseXen_lliiiliiiiI)and 2^SynapseXen_lliiiliiiiI or 0)end;return SynapseXen_lIIlIlIlliIll end;SynapseXen_lIIIIIlililliIillIl=SynapseXen_IIliiilliIlliIi end;SynapseXen_IiilIiiIiIll=function(SynapseXen_IliIIlliIilIlIIilil,SynapseXen_lIIlllIiIlIIllIIlii,SynapseXen_lIIIlIlIIliIllIll)return(SynapseXen_IliIIlliIilIlIIilil+SynapseXen_lIIlllIiIlIIllIIlii)%SynapseXen_lIIIlIlIIliIllIll end;SynapseXen_IiiiIiliIlIIlIillll=function(SynapseXen_IliIIlliIilIlIIilil,SynapseXen_lIIlllIiIlIIllIIlii,SynapseXen_lIIIlIlIIliIllIll)return(SynapseXen_IliIIlliIilIlIIilil-SynapseXen_lIIlllIiIlIIllIIlii)%SynapseXen_lIIIlIlIIliIllIll end;local function SynapseXen_llIlIlIlIl(SynapseXen_IiliIiiliIlilliII)if SynapseXen_IiliIiiliIlilliII<0 then SynapseXen_IiliIiiliIlilliII=4294967296+SynapseXen_IiliIiiliIlilliII end;return SynapseXen_IiliIiiliIlilliII end;local getfenv=getfenv;if not getfenv then getfenv=function()return _ENV end end;local SynapseXen_IliIIii={}local SynapseXen_llIiiiillIiiIIII={}local SynapseXen_IilIIiliiiililIiI;local SynapseXen_IillliI;local SynapseXen_iiIlIil={}local SynapseXen_IillliliillIiliI={}for SynapseXen_lliiiliiiiI=0,255 do local SynapseXen_lIilIllIIIlilll,SynapseXen_lilIlilllIIllIIlll=SynapseXen_iilIIiIIIl(SynapseXen_lliiiliiiiI),SynapseXen_iilIIiIIIl(SynapseXen_lliiiliiiiI,0)SynapseXen_iiIlIil[SynapseXen_lIilIllIIIlilll]=SynapseXen_lilIlilllIIllIIlll;SynapseXen_IillliliillIiliI[SynapseXen_lilIlilllIIllIIlll]=SynapseXen_lIilIllIIIlilll end;local function SynapseXen_IiliiIlIiililIlil(SynapseXen_IlIIIlIIilillIi,SynapseXen_iliiiIlIliili,SynapseXen_lIiilliIiiI,SynapseXen_IlIIiI)if SynapseXen_lIiilliIiiI>=256 then SynapseXen_lIiilliIiiI,SynapseXen_IlIIiI=0,SynapseXen_IlIIiI+1;if SynapseXen_IlIIiI>=256 then SynapseXen_iliiiIlIliili={}SynapseXen_IlIIiI=1 end end;SynapseXen_iliiiIlIliili[SynapseXen_iilIIiIIIl(SynapseXen_lIiilliIiiI,SynapseXen_IlIIiI)]=SynapseXen_IlIIIlIIilillIi;SynapseXen_lIiilliIiiI=SynapseXen_lIiilliIiiI+1;return SynapseXen_iliiiIlIliili,SynapseXen_lIiilliIiiI,SynapseXen_IlIIiI end;local function SynapseXen_llIlIIIililIilliIlii(SynapseXen_liiIiIiIIliIIil)local function SynapseXen_iIllIilI(SynapseXen_IiilIiiilIilIl)local SynapseXen_IlIIiI='ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/'SynapseXen_IiilIiiilIilIl=string.gsub(SynapseXen_IiilIiiilIilIl,'[^'..SynapseXen_IlIIiI..'=]','')return SynapseXen_IiilIiiilIilIl:gsub('.',function(SynapseXen_IliIIlliIilIlIIilil)if SynapseXen_IliIIlliIilIlIIilil=='='then return''end;local SynapseXen_illiIllIliiIlllIIl,SynapseXen_iIIlliillll='',SynapseXen_IlIIiI:find(SynapseXen_IliIIlliIilIlIIilil)-1;for SynapseXen_lliiiliiiiI=6,1,-1 do SynapseXen_illiIllIliiIlllIIl=SynapseXen_illiIllIliiIlllIIl..(SynapseXen_iIIlliillll%2^SynapseXen_lliiiliiiiI-SynapseXen_iIIlliillll%2^(SynapseXen_lliiiliiiiI-1)>0 and'1'or'0')end;return SynapseXen_illiIllIliiIlllIIl end):gsub('%d%d%d?%d?%d?%d?%d?%d?',function(SynapseXen_IliIIlliIilIlIIilil)if#SynapseXen_IliIIlliIilIlIIilil~=8 then return''end;local SynapseXen_IiIIllilI=0;for SynapseXen_lliiiliiiiI=1,8 do SynapseXen_IiIIllilI=SynapseXen_IiIIllilI+(SynapseXen_IliIIlliIilIlIIilil:sub(SynapseXen_lliiiliiiiI,SynapseXen_lliiiliiiiI)=='1'and 2^(8-SynapseXen_lliiiliiiiI)or 0)end;return string.char(SynapseXen_IiIIllilI)end)end;SynapseXen_liiIiIiIIliIIil=SynapseXen_iIllIilI(SynapseXen_liiIiIiIIliIIil)local SynapseXen_liilIIiiiiilIIliIli=SynapseXen_llIIIiIilllIliIiliil(SynapseXen_liiIiIiIIliIIil,1,1)if SynapseXen_liilIIiiiiilIIliIli=="u"then return SynapseXen_llIIIiIilllIliIiliil(SynapseXen_liiIiIiIIliIIil,2)elseif SynapseXen_liilIIiiiiilIIliIli~="c"then error("Synapse Xen - Failed to verify bytecode. Please make sure your Lua implementation supports non-null terminated strings.")end;SynapseXen_liiIiIiIIliIIil=SynapseXen_llIIIiIilllIliIiliil(SynapseXen_liiIiIiIIliIIil,2)local SynapseXen_iIiiiIIlilI=#SynapseXen_liiIiIiIIliIIil;local SynapseXen_iliiiIlIliili={}local SynapseXen_lIiilliIiiI,SynapseXen_IlIIiI=0,1;local SynapseXen_IIiiilI={}local SynapseXen_IiliIiiliIlilliII=1;local SynapseXen_lllllliiill=SynapseXen_llIIIiIilllIliIiliil(SynapseXen_liiIiIiIIliIIil,1,2)SynapseXen_IIiiilI[SynapseXen_IiliIiiliIlilliII]=SynapseXen_IillliliillIiliI[SynapseXen_lllllliiill]or SynapseXen_iliiiIlIliili[SynapseXen_lllllliiill]SynapseXen_IiliIiiliIlilliII=SynapseXen_IiliIiiliIlilliII+1;for SynapseXen_lliiiliiiiI=3,SynapseXen_iIiiiIIlilI,2 do local SynapseXen_lIiIiIiIIiiiiIllllIl=SynapseXen_llIIIiIilllIliIiliil(SynapseXen_liiIiIiIIliIIil,SynapseXen_lliiiliiiiI,SynapseXen_lliiiliiiiI+1)local SynapseXen_lIllIlllIi=SynapseXen_IillliliillIiliI[SynapseXen_lllllliiill]or SynapseXen_iliiiIlIliili[SynapseXen_lllllliiill]if not SynapseXen_lIllIlllIi then error("Synapse Xen - Failed to verify bytecode. Please make sure your Lua implementation supports non-null terminated strings.")end;local SynapseXen_IllIiI=SynapseXen_IillliliillIiliI[SynapseXen_lIiIiIiIIiiiiIllllIl]or SynapseXen_iliiiIlIliili[SynapseXen_lIiIiIiIIiiiiIllllIl]if SynapseXen_IllIiI then SynapseXen_IIiiilI[SynapseXen_IiliIiiliIlilliII]=SynapseXen_IllIiI;SynapseXen_IiliIiiliIlilliII=SynapseXen_IiliIiiliIlilliII+1;SynapseXen_iliiiIlIliili,SynapseXen_lIiilliIiiI,SynapseXen_IlIIiI=SynapseXen_IiliiIlIiililIlil(SynapseXen_lIllIlllIi..SynapseXen_llIIIiIilllIliIiliil(SynapseXen_IllIiI,1,1),SynapseXen_iliiiIlIliili,SynapseXen_lIiilliIiiI,SynapseXen_IlIIiI)else local SynapseXen_iiIiliIiiiIlIIIIili=SynapseXen_lIllIlllIi..SynapseXen_llIIIiIilllIliIiliil(SynapseXen_lIllIlllIi,1,1)SynapseXen_IIiiilI[SynapseXen_IiliIiiliIlilliII]=SynapseXen_iiIiliIiiiIlIIIIili;SynapseXen_IiliIiiliIlilliII=SynapseXen_IiliIiiliIlilliII+1;SynapseXen_iliiiIlIliili,SynapseXen_lIiilliIiiI,SynapseXen_IlIIiI=SynapseXen_IiliiIlIiililIlil(SynapseXen_iiIiliIiiiIlIIIIili,SynapseXen_iliiiIlIliili,SynapseXen_lIiilliIiiI,SynapseXen_IlIIiI)end;SynapseXen_lllllliiill=SynapseXen_lIiIiIiIIiiiiIllllIl end;return SynapseXen_llliI(SynapseXen_IIiiilI)end;local function SynapseXen_illIIIlliiIll(SynapseXen_iiiIililIIlli,SynapseXen_ilIiliilili,SynapseXen_IllllliilliIi)if SynapseXen_IllllliilliIi then local SynapseXen_iIllIIiIl=SynapseXen_iiiIililIIlli/2^(SynapseXen_ilIiliilili-1)%2^(SynapseXen_IllllliilliIi-1-(SynapseXen_ilIiliilili-1)+1)return SynapseXen_iIllIIiIl-SynapseXen_iIllIIiIl%1 else local SynapseXen_iilIlilllii=2^(SynapseXen_ilIiliilili-1)if SynapseXen_iiiIililIIlli%(SynapseXen_iilIlilllii+SynapseXen_iilIlilllii)>=SynapseXen_iilIlilllii then return 1 else return 0 end end end;local function SynapseXen_iIIliIIIliIIliil()local SynapseXen_lIIllIiliiilII=SynapseXen_IIliiilliIlliIi(863869127,SynapseXen_llIiiiillIiiIIII[11])while true do if SynapseXen_lIIllIiliiilII==SynapseXen_IIliiilliIlliIi(570165259,SynapseXen_IillliI)then SynapseXen_IilIIiliiiililIiI=function(SynapseXen_lililiiiiIlillIiIl,SynapseXen_IlllililiIIiiIIIIi)return SynapseXen_IIliiilliIlliIi(SynapseXen_lililiiiiIlillIiIl-38346,SynapseXen_IlllililiIIiiIIIIi-48630)-SynapseXen_IIliiilliIlliIi(2873124426,SynapseXen_llIiiiillIiiIIII[11])end;SynapseXen_lIIllIiliiilII=SynapseXen_lIIllIiliiilII+SynapseXen_IIliiilliIlliIi(1131901106,SynapseXen_llIiiiillIiiIIII[14])elseif SynapseXen_lIIllIiliiilII==SynapseXen_IIliiilliIlliIi(570181312,SynapseXen_IillliI)then SynapseXen_IilIIiliiiililIiI=function(SynapseXen_lililiiiiIlillIiIl,SynapseXen_IlllililiIIiiIIIIi)return SynapseXen_IIliiilliIlliIi(SynapseXen_lililiiiiIlillIiIl+41635,SynapseXen_IlllililiIIiiIIIIi-17575)-SynapseXen_IIliiilliIlliIi(1941793646,SynapseXen_IillliI)end;SynapseXen_lIIllIiliiilII=SynapseXen_lIIllIiliiilII+SynapseXen_IIliiilliIlliIi(3267544645,SynapseXen_llIiiiillIiiIIII[7])elseif SynapseXen_lIIllIiliiilII==SynapseXen_IIliiilliIlliIi(3022928093,SynapseXen_llIiiiillIiiIIII[12])then SynapseXen_IilIIiliiiililIiI=function(SynapseXen_lililiiiiIlillIiIl,SynapseXen_IlllililiIIiiIIIIi)return SynapseXen_IIliiilliIlliIi(SynapseXen_lililiiiiIlillIiIl-33301,SynapseXen_IlllililiIIiiIIIIi-9424)-SynapseXen_IIliiilliIlliIi(2632846487,SynapseXen_llIiiiillIiiIIII[2])end;SynapseXen_lIIllIiliiilII=SynapseXen_lIIllIiliiilII+SynapseXen_IIliiilliIlliIi(1941768554,SynapseXen_IillliI)elseif SynapseXen_lIIllIiliiilII==SynapseXen_IIliiilliIlliIi(810117173,SynapseXen_llIiiiillIiiIIII[7])then SynapseXen_IilIIiliiiililIiI=function(SynapseXen_lililiiiiIlillIiIl,SynapseXen_IlllililiIIiiIIIIi)return SynapseXen_IIliiilliIlliIi(SynapseXen_lililiiiiIlillIiIl-32733,SynapseXen_IlllililiIIiiIIIIi+49023)+SynapseXen_IIliiilliIlliIi(1941766994,SynapseXen_IillliI)end;SynapseXen_lIIllIiliiilII=SynapseXen_lIIllIiliiilII+SynapseXen_IIliiilliIlliIi(1941780223,SynapseXen_IillliI)elseif SynapseXen_lIIllIiliiilII==SynapseXen_IIliiilliIlliIi(570367035,SynapseXen_IillliI)then return elseif SynapseXen_lIIllIiliiilII==SynapseXen_IIliiilliIlliIi(2167477703,SynapseXen_IillliI)then SynapseXen_IilIIiliiiililIiI=function(SynapseXen_lililiiiiIlillIiIl,SynapseXen_IlllililiIIiiIIIIi)return SynapseXen_IIliiilliIlliIi(SynapseXen_lililiiiiIlillIiIl+36057,SynapseXen_IlllililiIIiiIIIIi+4256)-SynapseXen_IIliiilliIlliIi(1941790252,SynapseXen_IillliI)end;SynapseXen_lIIllIiliiilII=SynapseXen_lIIllIiliiilII-SynapseXen_IIliiilliIlliIi(3006904618,SynapseXen_llIiiiillIiiIIII[4])elseif SynapseXen_lIIllIiliiilII==SynapseXen_IIliiilliIlliIi(1852147832,SynapseXen_llIiiiillIiiIIII[2])then SynapseXen_IilIIiliiiililIiI=function(SynapseXen_lililiiiiIlillIiIl,SynapseXen_IlllililiIIiiIIIIi)return SynapseXen_IIliiilliIlliIi(SynapseXen_lililiiiiIlillIiIl-28256,SynapseXen_IlllililiIIiiIIIIi-39009)+SynapseXen_IIliiilliIlliIi(3317128103,SynapseXen_llIiiiillIiiIIII[13])end;SynapseXen_lIIllIiliiilII=SynapseXen_IIliiilliIlliIi(SynapseXen_lIIllIiliiilII,SynapseXen_IIliiilliIlliIi(1644713665,SynapseXen_llIiiiillIiiIIII[7]))elseif SynapseXen_lIIllIiliiilII==SynapseXen_IIliiilliIlliIi(1394957269,SynapseXen_llIiiiillIiiIIII[9])then SynapseXen_IilIIiliiiililIiI=function(SynapseXen_lililiiiiIlillIiIl,SynapseXen_IlllililiIIiiIIIIi)return SynapseXen_IIliiilliIlliIi(SynapseXen_lililiiiiIlillIiIl+8067,SynapseXen_IlllililiIIiiIIIIi+3070)-SynapseXen_IIliiilliIlliIi(1481537182,SynapseXen_llIiiiillIiiIIII[8])end;SynapseXen_lIIllIiliiilII=SynapseXen_IIliiilliIlliIi(SynapseXen_lIIllIiliiilII,SynapseXen_IIliiilliIlliIi(420272394,SynapseXen_IillliI))elseif SynapseXen_lIIllIiliiilII==SynapseXen_IIliiilliIlliIi(762919938,SynapseXen_llIiiiillIiiIIII[3])then SynapseXen_IilIIiliiiililIiI=function(SynapseXen_lililiiiiIlillIiIl,SynapseXen_IlllililiIIiiIIIIi)return SynapseXen_IIliiilliIlliIi(SynapseXen_lililiiiiIlillIiIl+35180,SynapseXen_IlllililiIIiiIIIIi-48390)+SynapseXen_IIliiilliIlliIi(1941813875,SynapseXen_IillliI)end;SynapseXen_lIIllIiliiilII=SynapseXen_lIIllIiliiilII+SynapseXen_IIliiilliIlliIi(3006893842,SynapseXen_llIiiiillIiiIIII[4])end end end;local function SynapseXen_lIliIIllil(SynapseXen_IlIiIIl)local SynapseXen_iIlIlIiiIliIllii=1;local SynapseXen_iliIiIlIii;local SynapseXen_illlIlIiIIillllIIll;local function SynapseXen_iIIiiIiliIliIiIli()local SynapseXen_iiIiiilIiiiIiliIl=SynapseXen_IliIl(SynapseXen_IlIiIIl,SynapseXen_iIlIlIiiIliIllii,SynapseXen_iIlIlIiiIliIllii)SynapseXen_iIlIlIiiIliIllii=SynapseXen_iIlIlIiiIliIllii+1;return SynapseXen_iiIiiilIiiiIiliIl end;local function SynapseXen_IIilillliilill()local SynapseXen_ilIiii,SynapseXen_lililiiiiIlillIiIl,SynapseXen_IlllililiIIiiIIIIi,SynapseXen_iIilIiIIIlIlIlIll=SynapseXen_IliIl(SynapseXen_IlIiIIl,SynapseXen_iIlIlIiiIliIllii,SynapseXen_iIlIlIiiIliIllii+3)SynapseXen_iIlIlIiiIliIllii=SynapseXen_iIlIlIiiIliIllii+4;return SynapseXen_iIilIiIIIlIlIlIll*16777216+SynapseXen_IlllililiIIiiIIIIi*65536+SynapseXen_lililiiiiIlillIiIl*256+SynapseXen_ilIiii end;local function SynapseXen_iIIIiIliiIiIiiiI()return SynapseXen_IIilillliilill()*4294967296+SynapseXen_IIilillliilill()end;local function SynapseXen_llIIillIiiIIl()local SynapseXen_IillIliIilIlliIlIi=SynapseXen_lIIIIIlililliIillIl(SynapseXen_IIilillliilill(),SynapseXen_IliIIii[3847529683]or(function(...)local SynapseXen_IliIIlliIilIlIIilil="SYNAPSE XEN [FE BYPASS] [BETTER THEN LURAPH] [AMAZING] OMG OMG OMG !!!!!!"local SynapseXen_ilIIIli=SynapseXen_IilIIiliiiililIiI(3289138533,2826572696)local SynapseXen_liIlIiIllIiililii={...}for SynapseXen_lliiiliiiiI,SynapseXen_liIiliiI in pairs(SynapseXen_liIlIiIllIiililii)do local SynapseXen_liIiIlil;local SynapseXen_IIllIiIlliIlIIlIIl=type(SynapseXen_liIiliiI)if SynapseXen_IIllIiIlliIlIIlIIl=="number"then SynapseXen_liIiIlil=SynapseXen_liIiliiI elseif SynapseXen_IIllIiIlliIlIIlIIl=="string"then SynapseXen_liIiIlil=SynapseXen_liIiliiI:len()elseif SynapseXen_IIllIiIlliIlIIlIIl=="table"then SynapseXen_liIiIlil=SynapseXen_IilIIiliiiililIiI(1517431617,2777534134)end;SynapseXen_ilIIIli=SynapseXen_ilIIIli-SynapseXen_liIiIlil end;SynapseXen_IliIIii[3847529683]=SynapseXen_IIliiilliIlliIi(SynapseXen_IIliiilliIlliIi(4033814298,SynapseXen_ilIIIli),SynapseXen_IIliiilliIlliIi(4023470500,SynapseXen_llIiiiillIiiIIII[11]))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{1738663449,4129661490,1708485619,108685812,4150492772,1783121372,2765572654,3970600176,3691962676,2079755568}return SynapseXen_IliIIii[3847529683]end)(14992,11086,"lIiiii",{},5990,9578,{}))local SynapseXen_illlII=SynapseXen_lIIIIIlililliIillIl(SynapseXen_IIilillliilill(),SynapseXen_IliIIii[2523802556]or(function()local SynapseXen_IliIIlliIilIlIIilil="wow xen is shit buy luraph ok"SynapseXen_IliIIii[2523802556]=SynapseXen_IIliiilliIlliIi(SynapseXen_IilIIiliiiililIiI(275036810,344750209),SynapseXen_IIliiilliIlliIi(716731517,SynapseXen_llIiiiillIiiIIII[13]))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{3503886548,1391591417,1851362815}return SynapseXen_IliIIii[2523802556]end)())local SynapseXen_IIIIIliiiIIIii=1;local SynapseXen_llIii=SynapseXen_illIIIlliiIll(SynapseXen_illlII,1,20)*2^32+SynapseXen_IillIliIilIlliIlIi;local SynapseXen_IlliiiiI=SynapseXen_illIIIlliiIll(SynapseXen_illlII,21,31)local SynapseXen_IiiIilIlillIII=(-1)^SynapseXen_illIIIlliiIll(SynapseXen_illlII,32)if SynapseXen_IlliiiiI==0 then if SynapseXen_llIii==0 then return SynapseXen_IiiIilIlillIII*0 else SynapseXen_IlliiiiI=1;SynapseXen_IIIIIliiiIIIii=0 end elseif SynapseXen_IlliiiiI==2047 then if SynapseXen_llIii==0 then return SynapseXen_IiiIilIlillIII*1/0 else return SynapseXen_IiiIilIlillIII*0/0 end end;return math.ldexp(SynapseXen_IiiIilIlillIII,SynapseXen_IlliiiiI-1023)*(SynapseXen_IIIIIliiiIIIii+SynapseXen_llIii/2^52)end;local function SynapseXen_lllIillilIi(SynapseXen_lilililIllililiIilIl)local SynapseXen_IliIliIIIliii;if SynapseXen_lilililIllililiIilIl then SynapseXen_IliIliIIIliii=SynapseXen_llIIIiIilllIliIiliil(SynapseXen_IlIiIIl,SynapseXen_iIlIlIiiIliIllii,SynapseXen_iIlIlIiiIliIllii+SynapseXen_lilililIllililiIilIl-1)SynapseXen_iIlIlIiiIliIllii=SynapseXen_iIlIlIiiIliIllii+SynapseXen_lilililIllililiIilIl else SynapseXen_lilililIllililiIilIl=SynapseXen_iliIiIlIii()if SynapseXen_lilililIllililiIilIl==0 then return""end;SynapseXen_IliIliIIIliii=SynapseXen_llIIIiIilllIliIiliil(SynapseXen_IlIiIIl,SynapseXen_iIlIlIiiIliIllii,SynapseXen_iIlIlIiiIliIllii+SynapseXen_lilililIllililiIilIl-1)SynapseXen_iIlIlIiiIliIllii=SynapseXen_iIlIlIiiIliIllii+SynapseXen_lilililIllililiIilIl end;return SynapseXen_IliIliIIIliii end;local function SynapseXen_iiIliiIliI(SynapseXen_IliIliIIIliii)local SynapseXen_iIllIIiIl={}for SynapseXen_lliiiliiiiI=1,#SynapseXen_IliIliIIIliii do local SynapseXen_lllIilIlliiiI=SynapseXen_IliIliIIIliii:sub(SynapseXen_lliiiliiiiI,SynapseXen_lliiiliiiiI)SynapseXen_iIllIIiIl[#SynapseXen_iIllIIiIl+1]=string.char(SynapseXen_IIliiilliIlliIi(string.byte(SynapseXen_lllIilIlliiiI),SynapseXen_IliIIii[421698510]or(function(...)local SynapseXen_IliIIlliIilIlIIilil="wait for someone on devforum to say they are gonna deobfuscate this"local SynapseXen_ilIIIli=SynapseXen_IilIIiliiiililIiI(1659401709,838358463)local SynapseXen_liIlIiIllIiililii={...}for SynapseXen_lliiiliiiiI,SynapseXen_liIiliiI in pairs(SynapseXen_liIlIiIllIiililii)do local SynapseXen_liIiIlil;local SynapseXen_IIllIiIlliIlIIlIIl=type(SynapseXen_liIiliiI)if SynapseXen_IIllIiIlliIlIIlIIl=="number"then SynapseXen_liIiIlil=SynapseXen_liIiliiI elseif SynapseXen_IIllIiIlliIlIIlIIl=="string"then SynapseXen_liIiIlil=SynapseXen_liIiliiI:len()elseif SynapseXen_IIllIiIlliIlIIlIIl=="table"then SynapseXen_liIiIlil=SynapseXen_IilIIiliiiililIiI(1620487110,2674488088)end;SynapseXen_ilIIIli=SynapseXen_ilIIIli-SynapseXen_liIiIlil end;SynapseXen_IliIIii[421698510]=SynapseXen_IIliiilliIlliIi(SynapseXen_IIliiilliIlliIi(2417736773,SynapseXen_ilIIIli),SynapseXen_IIliiilliIlliIi(1241759647,SynapseXen_llIiiiillIiiIIII[5]))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{4127285714,337118230,628805768,76534102,3484944675}return SynapseXen_IliIIii[421698510]end)("i","IlIlllilliliIiIil",7376,{},{},"I",{},"lIllI",{},14414)))end;return table.concat(SynapseXen_iIllIIiIl)end;local function SynapseXen_iiilIlli()local SynapseXen_lIIlIiIlIIiIliiliII={}local SynapseXen_iiIIiiilllIliII={}local SynapseXen_iIiIliill={}local SynapseXen_IlIIIliiiiilillilli={[SynapseXen_IliIIii[59954558]or(function(...)local SynapseXen_IliIIlliIilIlIIilil="xen doesn't come with instance caching, sorry superskater"local SynapseXen_ilIIIli=SynapseXen_IilIIiliiiililIiI(2239433814,3528837743)local SynapseXen_liIlIiIllIiililii={...}for SynapseXen_lliiiliiiiI,SynapseXen_liIiliiI in pairs(SynapseXen_liIlIiIllIiililii)do local SynapseXen_liIiIlil;local SynapseXen_IIllIiIlliIlIIlIIl=type(SynapseXen_liIiliiI)if SynapseXen_IIllIiIlliIlIIlIIl=="number"then SynapseXen_liIiIlil=SynapseXen_liIiliiI elseif SynapseXen_IIllIiIlliIlIIlIIl=="string"then SynapseXen_liIiIlil=SynapseXen_liIiliiI:len()elseif SynapseXen_IIllIiIlliIlIIlIIl=="table"then SynapseXen_liIiIlil=SynapseXen_IilIIiliiiililIiI(2474948421,1820032508)end;SynapseXen_ilIIIli=SynapseXen_ilIIIli-SynapseXen_liIiIlil end;SynapseXen_IliIIii[59954558]=SynapseXen_IIliiilliIlliIi(SynapseXen_IIliiilliIlliIi(4193767102,SynapseXen_ilIIIli),SynapseXen_IIliiilliIlliIi(4118332667,SynapseXen_IillliI))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{838539817,906402219,1505602893,3675298592,1087429649,1055049916,2692151997}return SynapseXen_IliIIii[59954558]end)("illiiilliiiIIiI",11841,4851,{},"lii")]=SynapseXen_iiIIiiilllIliII,[SynapseXen_IliIIii[836720]or(function(...)local SynapseXen_IliIIlliIilIlIIilil="hi xen doesn't work on sk8r please help"local SynapseXen_ilIIIli=SynapseXen_IilIIiliiiililIiI(327319148,1361822281)local SynapseXen_liIlIiIllIiililii={...}for SynapseXen_lliiiliiiiI,SynapseXen_liIiliiI in pairs(SynapseXen_liIlIiIllIiililii)do local SynapseXen_liIiIlil;local SynapseXen_IIllIiIlliIlIIlIIl=type(SynapseXen_liIiliiI)if SynapseXen_IIllIiIlliIlIIlIIl=="number"then SynapseXen_liIiIlil=SynapseXen_liIiliiI elseif SynapseXen_IIllIiIlliIlIIlIIl=="string"then SynapseXen_liIiIlil=SynapseXen_liIiliiI:len()elseif SynapseXen_IIllIiIlliIlIIlIIl=="table"then SynapseXen_liIiIlil=SynapseXen_IilIIiliiiililIiI(3687492685,607479269)end;SynapseXen_ilIIIli=SynapseXen_ilIIIli-SynapseXen_liIiIlil end;SynapseXen_IliIIii[836720]=SynapseXen_IIliiilliIlliIi(SynapseXen_IIliiilliIlliIi(841955460,SynapseXen_ilIIIli),SynapseXen_IIliiilliIlliIi(2977370059,SynapseXen_llIiiiillIiiIIII[10]))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{2700292109,3757776157,2345474557,558400738,730032457,519404480,2897783008}return SynapseXen_IliIIii[836720]end)("IiliIIlllIiiiliI","IlIiiIillIliIIlllI","illIIlilIIiliIIlIl",{},"I","iil","ilIilliIIIIlIIlliI",1851,"lI",2151)]=SynapseXen_iIiIliill,[SynapseXen_IliIIii[2703143698]or(function()local SynapseXen_IliIIlliIilIlIIilil="now comes with a free n word pass"SynapseXen_IliIIii[2703143698]=SynapseXen_IIliiilliIlliIi(SynapseXen_IilIIiliiiililIiI(1072767052,50412083),SynapseXen_IIliiilliIlliIi(1193507493,SynapseXen_IillliI))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{1193600428,1920443739,4114760553,2865769621,4105261749,2907729697,2871252115}return SynapseXen_IliIIii[2703143698]end)()]=SynapseXen_lIIlIiIlIIiIliiliII}SynapseXen_iIIiiIiliIliIiIli()for SynapseXen_IiilliiIiIIilI=1,SynapseXen_IIliiilliIlliIi(SynapseXen_illlIlIiIIillllIIll(),SynapseXen_IliIIii[914864301]or(function(...)local SynapseXen_IliIIlliIilIlIIilil="this is so sad, alexa play ripull.mp4"local SynapseXen_ilIIIli=SynapseXen_IilIIiliiiililIiI(3922863449,3572269958)local SynapseXen_liIlIiIllIiililii={...}for SynapseXen_lliiiliiiiI,SynapseXen_liIiliiI in pairs(SynapseXen_liIlIiIllIiililii)do local SynapseXen_liIiIlil;local SynapseXen_IIllIiIlliIlIIlIIl=type(SynapseXen_liIiliiI)if SynapseXen_IIllIiIlliIlIIlIIl=="number"then SynapseXen_liIiIlil=SynapseXen_liIiliiI elseif SynapseXen_IIllIiIlliIlIIlIIl=="string"then SynapseXen_liIiIlil=SynapseXen_liIiliiI:len()elseif SynapseXen_IIllIiIlliIlIIlIIl=="table"then SynapseXen_liIiIlil=SynapseXen_IilIIiliiiililIiI(3163316139,1131695399)end;SynapseXen_ilIIIli=SynapseXen_ilIIIli-SynapseXen_liIiIlil end;SynapseXen_IliIIii[914864301]=SynapseXen_IIliiilliIlliIi(SynapseXen_IIliiilliIlliIi(3965911714,SynapseXen_ilIIIli),SynapseXen_IIliiilliIlliIi(1309115081,SynapseXen_llIiiiillIiiIIII[10]))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{1948874036,2626959396,278942694,2153146069,4176559358,1509786354,493904827,1352306957}return SynapseXen_IliIIii[914864301]end)({},9653))do SynapseXen_iIIiiIiliIliIiIli()local SynapseXen_iIIllii=SynapseXen_iIIiiIiliIliIiIli()local SynapseXen_liliIll;if SynapseXen_iIIllii==(SynapseXen_IliIIii[1129657232]or(function()local SynapseXen_IliIIlliIilIlIIilil="epic gamer vision"SynapseXen_IliIIii[1129657232]=SynapseXen_IIliiilliIlliIi(SynapseXen_IilIIiliiiililIiI(214196452,310140858),SynapseXen_IIliiilliIlliIi(4036964775,SynapseXen_llIiiiillIiiIIII[10]))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{4214967082,4067729545,1123557698,3038564331,2780218701,1469658098,1988747916}return SynapseXen_IliIIii[1129657232]end)())then SynapseXen_liliIll=SynapseXen_iIIiiIiliIliIiIli()~=0 elseif SynapseXen_iIIllii==(SynapseXen_IliIIii[1801100499]or(function()local SynapseXen_IliIIlliIilIlIIilil="my way to go against expwoiting is to have safety measuwes. i 1 wocawscwipt and onwy moduwes. hewe's how it wowks: this scwipt bewow stowes the moduwes in a tabwe fow each moduwe we send the wist with the moduwes and moduwe infowmation and use inyit a function in my moduwe that wiww stowe the info and aftew it has send to aww the moduwes it wiww dewete them. so whenyevew the cwient twies to hack they cant get the moduwes. onwy this peace of wocawscwipt."SynapseXen_IliIIii[1801100499]=SynapseXen_IIliiilliIlliIi(SynapseXen_IilIIiliiiililIiI(4188920289,86933576),SynapseXen_IIliiilliIlliIi(933017682,SynapseXen_llIiiiillIiiIIII[9]))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{3106682096,3578999116,3571275666,2005197167,2302073150,3971652534,769987856,1162226640,2988744020,548058412}return SynapseXen_IliIIii[1801100499]end)())then SynapseXen_liliIll=SynapseXen_llIIillIiiIIl()elseif SynapseXen_iIIllii==(SynapseXen_IliIIii[2170462498]or(function()local SynapseXen_IliIIlliIilIlIIilil="wally bad bird"SynapseXen_IliIIii[2170462498]=SynapseXen_IIliiilliIlliIi(SynapseXen_IilIIiliiiililIiI(1418628447,2680962648),SynapseXen_IIliiilliIlliIi(627425348,SynapseXen_llIiiiillIiiIIII[10]))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{1513707822,332734502,3334273452,1737711406,686386985,2582477292,4279599349,1593428317,540367394,2153825043}return SynapseXen_IliIIii[2170462498]end)())then SynapseXen_liliIll=SynapseXen_llIIIiIilllIliIiliil(SynapseXen_iiIliiIliI(SynapseXen_lllIillilIi()),1,-2)end;SynapseXen_iiIIiiilllIliII[SynapseXen_IiilliiIiIIilI-1]=SynapseXen_liliIll end;SynapseXen_IIilillliilill()SynapseXen_IIilillliilill()SynapseXen_IlIIIliiiiilillilli[2084908442]=SynapseXen_IIliiilliIlliIi(SynapseXen_iIIiiIiliIliIiIli(),SynapseXen_IliIIii[2369972390]or(function()local SynapseXen_IliIIlliIilIlIIilil="HELP ME PEOPLE ARE CRASHING MY GAME PLZ HELP"SynapseXen_IliIIii[2369972390]=SynapseXen_IIliiilliIlliIi(SynapseXen_IilIIiliiiililIiI(425478201,3205731551),SynapseXen_IIliiilliIlliIi(3589513450,SynapseXen_IillliI))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{672206858,3604852065,3007133,1166794016,2195889856}return SynapseXen_IliIIii[2369972390]end)())SynapseXen_iIIiiIiliIliIiIli()SynapseXen_IlIIIliiiiilillilli[1552660435]=SynapseXen_IIliiilliIlliIi(SynapseXen_iIIiiIiliIliIiIli(),SynapseXen_IliIIii[1820726817]or(function()local SynapseXen_IliIIlliIilIlIIilil="xen best rerubi paste"SynapseXen_IliIIii[1820726817]=SynapseXen_IIliiilliIlliIi(SynapseXen_IilIIiliiiililIiI(2992508387,4180758752),SynapseXen_IIliiilliIlliIi(135910936,SynapseXen_llIiiiillIiiIIII[14]))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{1420635427,1192282353,2109262082,1590127956,124056365,1519029120}return SynapseXen_IliIIii[1820726817]end)())SynapseXen_iIIiiIiliIliIiIli()SynapseXen_IIilillliilill()for SynapseXen_IiilliiIiIIilI=1,SynapseXen_IIliiilliIlliIi(SynapseXen_illlIlIiIIillllIIll(),SynapseXen_IliIIii[3407797787]or(function()local SynapseXen_IliIIlliIilIlIIilil="inb4 posted on exploit reports section"SynapseXen_IliIIii[3407797787]=SynapseXen_IIliiilliIlliIi(SynapseXen_IilIIiliiiililIiI(3129046009,2565287076),SynapseXen_IIliiilliIlliIi(1548099679,SynapseXen_IillliI))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{2294459149,3512635831,3299158839,145012977,494260876}return SynapseXen_IliIIii[3407797787]end)())do SynapseXen_iIIiiIiliIliIiIli()local SynapseXen_iilIilIIiliIl=SynapseXen_IIliiilliIlliIi(SynapseXen_IIilillliilill(),SynapseXen_IliIIii[3305078557]or(function(...)local SynapseXen_IliIIlliIilIlIIilil="print(bytecode)"local SynapseXen_ilIIIli=SynapseXen_IilIIiliiiililIiI(641389434,2754953605)local SynapseXen_liIlIiIllIiililii={...}for SynapseXen_lliiiliiiiI,SynapseXen_liIiliiI in pairs(SynapseXen_liIlIiIllIiililii)do local SynapseXen_liIiIlil;local SynapseXen_IIllIiIlliIlIIlIIl=type(SynapseXen_liIiliiI)if SynapseXen_IIllIiIlliIlIIlIIl=="number"then SynapseXen_liIiIlil=SynapseXen_liIiliiI elseif SynapseXen_IIllIiIlliIlIIlIIl=="string"then SynapseXen_liIiIlil=SynapseXen_liIiliiI:len()elseif SynapseXen_IIllIiIlliIlIIlIIl=="table"then SynapseXen_liIiIlil=SynapseXen_IilIIiliiiililIiI(2938487405,1356501963)end;SynapseXen_ilIIIli=SynapseXen_ilIIIli+SynapseXen_liIiIlil end;SynapseXen_IliIIii[3305078557]=SynapseXen_IIliiilliIlliIi(SynapseXen_IIliiilliIlliIi(1441651668,SynapseXen_ilIIIli),SynapseXen_IIliiilliIlliIi(2170961256,SynapseXen_IillliI))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{4005173204,194728347,1805591221,1812138174,3399270667,1152222366,3201607240,321465975}return SynapseXen_IliIIii[3305078557]end)(11761,4574))local SynapseXen_iIllIilIliIIIlll=SynapseXen_iIIiiIiliIliIiIli()local SynapseXen_iIIllii=SynapseXen_iIIiiIiliIliIiIli()SynapseXen_iIIiiIiliIliIiIli()local SynapseXen_lilllill={[137558596]=SynapseXen_iilIilIIiliIl,[526726514]=SynapseXen_iIllIilIliIIIlll,[782246252]=SynapseXen_illIIIlliiIll(SynapseXen_iilIilIIiliIl,1,6),[345380647]=SynapseXen_illIIIlliiIll(SynapseXen_iilIilIIiliIl,7,14)}if SynapseXen_iIIllii==(SynapseXen_IliIIii[1664635570]or(function(...)local SynapseXen_IliIIlliIilIlIIilil="xen detects custom getfenv"local SynapseXen_ilIIIli=SynapseXen_IilIIiliiiililIiI(2052636449,4001391938)local SynapseXen_liIlIiIllIiililii={...}for SynapseXen_lliiiliiiiI,SynapseXen_liIiliiI in pairs(SynapseXen_liIlIiIllIiililii)do local SynapseXen_liIiIlil;local SynapseXen_IIllIiIlliIlIIlIIl=type(SynapseXen_liIiliiI)if SynapseXen_IIllIiIlliIlIIlIIl=="number"then SynapseXen_liIiIlil=SynapseXen_liIiliiI elseif SynapseXen_IIllIiIlliIlIIlIIl=="string"then SynapseXen_liIiIlil=SynapseXen_liIiliiI:len()elseif SynapseXen_IIllIiIlliIlIIlIIl=="table"then SynapseXen_liIiIlil=SynapseXen_IilIIiliiiililIiI(1321085666,2973889024)end;SynapseXen_ilIIIli=SynapseXen_ilIIIli+SynapseXen_liIiIlil end;SynapseXen_IliIIii[1664635570]=SynapseXen_IIliiilliIlliIi(SynapseXen_IIliiilliIlliIi(1072125321,SynapseXen_ilIIIli),SynapseXen_IIliiilliIlliIi(3573226593,SynapseXen_llIiiiillIiiIIII[3]))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{2700866136,1179879856,2019916025,3121101018,2885100294,2414767858}return SynapseXen_IliIIii[1664635570]end)(3126,"iIiliiIIlIlIlII"))then SynapseXen_lilllill[983579962]=SynapseXen_illIIIlliiIll(SynapseXen_iilIilIIiliIl,24,32)SynapseXen_lilllill[1979198746]=SynapseXen_illIIIlliiIll(SynapseXen_iilIilIIiliIl,15,23)elseif SynapseXen_iIIllii==(SynapseXen_IliIIii[648418347]or(function()local SynapseXen_IliIIlliIilIlIIilil="i'm intercommunication about the most nonecclesiastical dll exploits for esp. they only characterization objects with a antepatriarchal in the geistesgeschichte for the esp."SynapseXen_IliIIii[648418347]=SynapseXen_IIliiilliIlliIi(SynapseXen_IilIIiliiiililIiI(3289184742,3315956900),SynapseXen_IIliiilliIlliIi(1913978709,SynapseXen_IillliI))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{148001857,1923828654,3797307435,4212876316,372326838}return SynapseXen_IliIIii[648418347]end)())then SynapseXen_lilllill[759978697]=SynapseXen_illIIIlliiIll(SynapseXen_iilIilIIiliIl,15,32)elseif SynapseXen_iIIllii==(SynapseXen_IliIIii[923459551]or(function()local SynapseXen_IliIIlliIilIlIIilil="what are you trying to say? that fucking one dot + dot + dot + many dots is not adding adding 1 dot + dot and then adding all the dots together????"SynapseXen_IliIIii[923459551]=SynapseXen_IIliiilliIlliIi(SynapseXen_IilIIiliiiililIiI(3036427678,370823327),SynapseXen_IIliiilliIlliIi(3512241960,SynapseXen_IillliI))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{466422727,4292609616,44293355,2312845960,508387071,3649380721,3424836691,3754752809,1352226918}return SynapseXen_IliIIii[923459551]end)())then SynapseXen_lilllill[1250141042]=SynapseXen_illIIIlliiIll(SynapseXen_iilIilIIiliIl,15,32)-131071 end;SynapseXen_iIiIliill[SynapseXen_IiilliiIiIIilI]=SynapseXen_lilllill end;for SynapseXen_IiilliiIiIIilI=1,SynapseXen_IIliiilliIlliIi(SynapseXen_illlIlIiIIillllIIll(),SynapseXen_IliIIii[3608711057]or(function()local SynapseXen_IliIIlliIilIlIIilil="https://twitter.com/Ripull_RBLX/status/1059334518581145603"SynapseXen_IliIIii[3608711057]=SynapseXen_IIliiilliIlliIi(SynapseXen_IilIIiliiiililIiI(1473711512,1902637673),SynapseXen_IIliiilliIlliIi(3794604775,SynapseXen_IillliI))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{2172523242,579267079,3292004518,1927485813,3342757125,4015121248,3359674690,4047023558}return SynapseXen_IliIIii[3608711057]end)())do SynapseXen_lIIlIiIlIIiIliiliII[SynapseXen_IiilliiIiIIilI-1]=SynapseXen_iiilIlli()end;return SynapseXen_IlIIIliiiiilillilli end;do assert(SynapseXen_lllIillilIi(4)=="\27Xen","Synapse Xen - Failed to verify bytecode. Please make sure your Lua implementation supports non-null terminated strings.")SynapseXen_illlIlIiIIillllIIll=SynapseXen_IIilillliilill;SynapseXen_iliIiIlIii=SynapseXen_IIilillliilill;local SynapseXen_liIIll=SynapseXen_lllIillilIi()SynapseXen_IIilillliilill()SynapseXen_IIilillliilill()SynapseXen_IillliI=SynapseXen_llIlIlIlIl(SynapseXen_illlIlIiIIillllIIll())SynapseXen_iIIiiIiliIliIiIli()local SynapseXen_iiIilIIIllIilii=0;for SynapseXen_lliiiliiiiI=1,#SynapseXen_liIIll do local SynapseXen_lllIilIlliiiI=SynapseXen_liIIll:sub(SynapseXen_lliiiliiiiI,SynapseXen_lliiiliiiiI)SynapseXen_iiIilIIIllIilii=SynapseXen_iiIilIIIllIilii+string.byte(SynapseXen_lllIilIlliiiI)end;SynapseXen_iiIilIIIllIilii=SynapseXen_IIliiilliIlliIi(SynapseXen_iiIilIIIllIilii,SynapseXen_IillliI)for SynapseXen_IiilliiIiIIilI=1,SynapseXen_iIIiiIiliIliIiIli()do SynapseXen_llIiiiillIiiIIII[SynapseXen_IiilliiIiIIilI]=SynapseXen_lIIIIIlililliIillIl(SynapseXen_illlIlIiIIillllIIll(),SynapseXen_iiIilIIIllIilii)end;SynapseXen_iIIliIIIliIIliil()end;return SynapseXen_iiilIlli()end;local function SynapseXen_llIIiiIilI(...)return SynapseXen_liIlillIlIIllIi('#',...),{...}end;local function SynapseXen_lllliIliIIllliIlIiil(SynapseXen_IlIIIliiiiilillilli,SynapseXen_lliIiIll,SynapseXen_iIlIiiIlliIIliIIilI)local SynapseXen_iiIIiiilllIliII=SynapseXen_IlIIIliiiiilillilli[SynapseXen_IliIIii[59954558]or(function(...)local SynapseXen_IliIIlliIilIlIIilil="xen doesn't come with instance caching, sorry superskater"local SynapseXen_ilIIIli=SynapseXen_IilIIiliiiililIiI(2239433814,3528837743)local SynapseXen_liIlIiIllIiililii={...}for SynapseXen_lliiiliiiiI,SynapseXen_liIiliiI in pairs(SynapseXen_liIlIiIllIiililii)do local SynapseXen_liIiIlil;local SynapseXen_IIllIiIlliIlIIlIIl=type(SynapseXen_liIiliiI)if SynapseXen_IIllIiIlliIlIIlIIl=="number"then SynapseXen_liIiIlil=SynapseXen_liIiliiI elseif SynapseXen_IIllIiIlliIlIIlIIl=="string"then SynapseXen_liIiIlil=SynapseXen_liIiliiI:len()elseif SynapseXen_IIllIiIlliIlIIlIIl=="table"then SynapseXen_liIiIlil=SynapseXen_IilIIiliiiililIiI(2474948421,1820032508)end;SynapseXen_ilIIIli=SynapseXen_ilIIIli-SynapseXen_liIiIlil end;SynapseXen_IliIIii[59954558]=SynapseXen_IIliiilliIlliIi(SynapseXen_IIliiilliIlliIi(4193767102,SynapseXen_ilIIIli),SynapseXen_IIliiilliIlliIi(4118332667,SynapseXen_IillliI))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{838539817,906402219,1505602893,3675298592,1087429649,1055049916,2692151997}return SynapseXen_IliIIii[59954558]end)("illiiilliiiIIiI",11841,4851,{},"lii")]local SynapseXen_lIIlIiIlIIiIliiliII=SynapseXen_IlIIIliiiiilillilli[SynapseXen_IliIIii[2703143698]or(function()local SynapseXen_IliIIlliIilIlIIilil="now comes with a free n word pass"SynapseXen_IliIIii[2703143698]=SynapseXen_IIliiilliIlliIi(SynapseXen_IilIIiliiiililIiI(1072767052,50412083),SynapseXen_IIliiilliIlliIi(1193507493,SynapseXen_IillliI))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{1193600428,1920443739,4114760553,2865769621,4105261749,2907729697,2871252115}return SynapseXen_IliIIii[2703143698]end)()]local SynapseXen_iIiIliill=SynapseXen_IlIIIliiiiilillilli[SynapseXen_IliIIii[836720]or(function(...)local SynapseXen_IliIIlliIilIlIIilil="hi xen doesn't work on sk8r please help"local SynapseXen_ilIIIli=SynapseXen_IilIIiliiiililIiI(327319148,1361822281)local SynapseXen_liIlIiIllIiililii={...}for SynapseXen_lliiiliiiiI,SynapseXen_liIiliiI in pairs(SynapseXen_liIlIiIllIiililii)do local SynapseXen_liIiIlil;local SynapseXen_IIllIiIlliIlIIlIIl=type(SynapseXen_liIiliiI)if SynapseXen_IIllIiIlliIlIIlIIl=="number"then SynapseXen_liIiIlil=SynapseXen_liIiliiI elseif SynapseXen_IIllIiIlliIlIIlIIl=="string"then SynapseXen_liIiIlil=SynapseXen_liIiliiI:len()elseif SynapseXen_IIllIiIlliIlIIlIIl=="table"then SynapseXen_liIiIlil=SynapseXen_IilIIiliiiililIiI(3687492685,607479269)end;SynapseXen_ilIIIli=SynapseXen_ilIIIli-SynapseXen_liIiIlil end;SynapseXen_IliIIii[836720]=SynapseXen_IIliiilliIlliIi(SynapseXen_IIliiilliIlliIi(841955460,SynapseXen_ilIIIli),SynapseXen_IIliiilliIlliIi(2977370059,SynapseXen_llIiiiillIiiIIII[10]))-string.len(SynapseXen_IliIIlliIilIlIIilil)-#{2700292109,3757776157,2345474557,558400738,730032457,519404480,2897783008}return SynapseXen_IliIIii[836720]end)("IiliIIlllIiiiliI","IlIiiIillIliIIlllI","illIIlilIIiliIIlIl",{},"I","iil","ilIilliIIIIlIIlliI",1851,"lI",2151)]return function(...)local SynapseXen_liiliIlIIlllilIiII,SynapseXen_IIlil=1,-1;local SynapseXen_IlillIlIlII,SynapseXen_lIiiliIllliii={},SynapseXen_liIlillIlIIllIi('#',...)-1;local SynapseXen_liIlliii=0;local SynapseXen_llliIIIIiilIi={}local SynapseXen_IIIlIIlllliiI={}local SynapseXen_illlii=setmetatable({},{__index=SynapseXen_llliIIIIiilIi,__newindex=function(SynapseXen_IliIliiilIilili,SynapseXen_illiIllIiiIliIl,SynapseXen_IiilIliIiill)if SynapseXen_illiIllIiiIliIl>SynapseXen_IIlil then SynapseXen_IIlil=SynapseXen_illiIllIiiIliIl end;SynapseXen_llliIIIIiilIi[SynapseXen_illiIllIiiIliIl]=SynapseXen_IiilIliIiill end})local function SynapseXen_IIIIiiiiliIlil()local SynapseXen_lilllill,SynapseXen_ilIliiliii;while true do SynapseXen_lilllill=SynapseXen_iIiIliill[SynapseXen_liiliIlIIlllilIiII]SynapseXen_ilIliiliii=SynapseXen_lilllill[526726514]SynapseXen_liiliIlIIlllilIiII=SynapseXen_liiliIlIIlllilIiII+1;if SynapseXen_ilIliiliii==0 then local SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[983579962],84,512)local SynapseXen_lllIilIlliiiI=SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[1979198746],41,512)local SynapseXen_IlllilIliIlI=SynapseXen_illlii;if SynapseXen_liliIIIlIlilIIiIIlii>255 then SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_iiIIiiilllIliII[SynapseXen_liliIIIlIlilIIiIIlii-256]else SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IlllilIliIlI[SynapseXen_liliIIIlIlilIIiIIlii]end;if SynapseXen_lllIilIlliiiI>255 then SynapseXen_lllIilIlliiiI=SynapseXen_iiIIiiilllIliII[SynapseXen_lllIilIlliiiI-256]else SynapseXen_lllIilIlliiiI=SynapseXen_IlllilIliIlI[SynapseXen_lllIilIlliiiI]end;SynapseXen_IlllilIliIlI[SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[345380647],63)]=SynapseXen_liliIIIlIlilIIiIIlii%SynapseXen_lllIilIlliiiI elseif SynapseXen_ilIliiliii==98 then local SynapseXen_iIliIiiIIiilIii=SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[345380647],43,256)local SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[983579962],46)local SynapseXen_IlllilIliIlI,SynapseXen_llillilIIIlIIIiIiIli=SynapseXen_illlii,SynapseXen_IlillIlIlII;SynapseXen_IIlil=SynapseXen_iIliIiiIIiilIii-1;for SynapseXen_IiilliiIiIIilI=SynapseXen_iIliIiiIIiilIii,SynapseXen_iIliIiiIIiilIii+(SynapseXen_liliIIIlIlilIIiIIlii>0 and SynapseXen_liliIIIlIlilIIiIIlii-1 or SynapseXen_lIiiliIllliii)do SynapseXen_IlllilIliIlI[SynapseXen_IiilliiIiIIilI]=SynapseXen_llillilIIIlIIIiIiIli[SynapseXen_IiilliiIiIIilI-SynapseXen_iIliIiiIIiilIii]end elseif SynapseXen_ilIliiliii==77 then SynapseXen_illlii[SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[345380647],117)]=not SynapseXen_illlii[SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[983579962],108),SynapseXen_liIlliii,512)]elseif SynapseXen_ilIliiliii==184 then local SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IiilIiiIiIll(SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[983579962],107),SynapseXen_liIlliii,512)local SynapseXen_lllIilIlliiiI=SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[1979198746],99,512)local SynapseXen_IlllilIliIlI=SynapseXen_illlii;if SynapseXen_liliIIIlIlilIIiIIlii>255 then SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_iiIIiiilllIliII[SynapseXen_liliIIIlIlilIIiIIlii-256]else SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IlllilIliIlI[SynapseXen_liliIIIlIlilIIiIIlii]end;if SynapseXen_lllIilIlliiiI>255 then SynapseXen_lllIilIlliiiI=SynapseXen_iiIIiiilllIliII[SynapseXen_lllIilIlliiiI-256]else SynapseXen_lllIilIlliiiI=SynapseXen_IlllilIliIlI[SynapseXen_lllIilIlliiiI]end;SynapseXen_IlllilIliIlI[SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[345380647],104)]=SynapseXen_liliIIIlIlilIIiIIlii/SynapseXen_lllIilIlliiiI elseif SynapseXen_ilIliiliii==228 then local SynapseXen_iIliIiiIIiilIii=SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[345380647],34,256)local SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[983579962],98),SynapseXen_liIlliii,512)local SynapseXen_IlllilIliIlI=SynapseXen_illlii;local SynapseXen_liIIlliiIiIIliIl,SynapseXen_IIIiIIiIilllIl;local SynapseXen_iiIlIiliIiIi;if SynapseXen_liliIIIlIlilIIiIIlii==1 then return elseif SynapseXen_liliIIIlIlilIIiIIlii==0 then SynapseXen_iiIlIiliIiIi=SynapseXen_IIlil else SynapseXen_iiIlIiliIiIi=SynapseXen_iIliIiiIIiilIii+SynapseXen_liliIIIlIlilIIiIIlii-2 end;SynapseXen_IIIiIIiIilllIl={}SynapseXen_liIIlliiIiIIliIl=0;for SynapseXen_IiilliiIiIIilI=SynapseXen_iIliIiiIIiilIii,SynapseXen_iiIlIiliIiIi do SynapseXen_liIIlliiIiIIliIl=SynapseXen_liIIlliiIiIIliIl+1;SynapseXen_IIIiIIiIilllIl[SynapseXen_liIIlliiIiIIliIl]=SynapseXen_IlllilIliIlI[SynapseXen_IiilliiIiIIilI]end;return SynapseXen_IIIiIIiIilllIl,SynapseXen_liIIlliiIiIIliIl elseif SynapseXen_ilIliiliii==24 then local SynapseXen_iIliIiiIIiilIii=SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[345380647],117)local SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[983579962],93,512),SynapseXen_liIlliii,512)local SynapseXen_lllIilIlliiiI=SynapseXen_IiilIiiIiIll(SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[1979198746],86,512),SynapseXen_liIlliii,512)local SynapseXen_IlllilIliIlI=SynapseXen_illlii;if SynapseXen_lllIilIlliiiI==0 then SynapseXen_liiliIlIIlllilIiII=SynapseXen_liiliIlIIlllilIiII+1;SynapseXen_lllIilIlliiiI=SynapseXen_iIiIliill[SynapseXen_liiliIlIIlllilIiII][137558596]end;local SynapseXen_lIiiilIlliiIII=(SynapseXen_lllIilIlliiiI-1)*50;local SynapseXen_liilIilllIlll=SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii]if SynapseXen_liliIIIlIlilIIiIIlii==0 then SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IIlil-SynapseXen_iIliIiiIIiilIii end;for SynapseXen_IiilliiIiIIilI=1,SynapseXen_liliIIIlIlilIIiIIlii do SynapseXen_liilIilllIlll[SynapseXen_lIiiilIlliiIII+SynapseXen_IiilliiIiIIilI]=SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii+SynapseXen_IiilliiIiIIilI]end elseif SynapseXen_ilIliiliii==43 then if SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[759978697],139587,262144)==4822 then SynapseXen_illlii[SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[345380647],73,256)]=SynapseXen_IillliI else SynapseXen_illlii[SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[345380647],73,256)]=SynapseXen_llIiiiillIiiIIII[SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[759978697],139587,262144)]end elseif SynapseXen_ilIliiliii==190 then local SynapseXen_iIIlliIiiiIiIIl=SynapseXen_lIIlIiIlIIiIliiliII[SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[759978697],49227)]local SynapseXen_IlllilIliIlI=SynapseXen_illlii;local SynapseXen_IlIiiiIillilll;local SynapseXen_liiIilIilIIllilIil;if SynapseXen_iIIlliIiiiIiIIl[2084908442]~=0 then SynapseXen_IlIiiiIillilll={}SynapseXen_liiIilIilIIllilIil=setmetatable({},{__index=function(SynapseXen_IliIliiilIilili,SynapseXen_illiIllIiiIliIl)local SynapseXen_lIIlIIi=SynapseXen_IlIiiiIillilll[SynapseXen_illiIllIiiIliIl]return SynapseXen_lIIlIIi[1][SynapseXen_lIIlIIi[2]]end,__newindex=function(SynapseXen_IliIliiilIilili,SynapseXen_illiIllIiiIliIl,SynapseXen_IiilIliIiill)local SynapseXen_lIIlIIi=SynapseXen_IlIiiiIillilll[SynapseXen_illiIllIiiIliIl]SynapseXen_lIIlIIi[1][SynapseXen_lIIlIIi[2]]=SynapseXen_IiilIliIiill end})for SynapseXen_IiilliiIiIIilI=1,SynapseXen_iIIlliIiiiIiIIl[2084908442]do local SynapseXen_IIiill=SynapseXen_iIiIliill[SynapseXen_liiliIlIIlllilIiII]if SynapseXen_IIiill[526726514]==170 then SynapseXen_IlIiiiIillilll[SynapseXen_IiilliiIiIIilI-1]={SynapseXen_IlllilIliIlI,SynapseXen_IIliiilliIlliIi(SynapseXen_IIiill[983579962],72)}elseif SynapseXen_IIiill[526726514]==11 then SynapseXen_IlIiiiIillilll[SynapseXen_IiilliiIiIIilI-1]={SynapseXen_iIlIiiIlliIIliIIilI,SynapseXen_IIliiilliIlliIi(SynapseXen_IIiill[983579962],9)}end;SynapseXen_liiliIlIIlllilIiII=SynapseXen_liiliIlIIlllilIiII+1 end;SynapseXen_IIIlIIlllliiI[#SynapseXen_IIIlIIlllliiI+1]=SynapseXen_IlIiiiIillilll end;SynapseXen_IlllilIliIlI[SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[345380647],82,256),SynapseXen_liIlliii,256)]=SynapseXen_lllliIliIIllliIlIiil(SynapseXen_iIIlliIiiiIiIIl,SynapseXen_lliIiIll,SynapseXen_liiIilIilIIllilIil)elseif SynapseXen_ilIliiliii==61 then local SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[983579962],77)local SynapseXen_lllIilIlliiiI=SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[1979198746],112)local SynapseXen_IlllilIliIlI=SynapseXen_illlii;if SynapseXen_liliIIIlIlilIIiIIlii>255 then SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_iiIIiiilllIliII[SynapseXen_liliIIIlIlilIIiIIlii-256]else SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IlllilIliIlI[SynapseXen_liliIIIlIlilIIiIIlii]end;if SynapseXen_lllIilIlliiiI>255 then SynapseXen_lllIilIlliiiI=SynapseXen_iiIIiiilllIliII[SynapseXen_lllIilIlliiiI-256]else SynapseXen_lllIilIlliiiI=SynapseXen_IlllilIliIlI[SynapseXen_lllIilIlliiiI]end;SynapseXen_IlllilIliIlI[SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[345380647],20,256)]=SynapseXen_liliIIIlIlilIIiIIlii^SynapseXen_lllIilIlliiiI elseif SynapseXen_ilIliiliii==141 then SynapseXen_illlii[SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[345380647],38),SynapseXen_liIlliii,256)]=SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[983579962],115,512)~=0;if SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[1979198746],69,512)~=0 then SynapseXen_liiliIlIIlllilIiII=SynapseXen_liiliIlIIlllilIiII+1 end elseif SynapseXen_ilIliiliii==48 then local SynapseXen_iIliIiiIIiilIii=SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[345380647],43,256)local SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IiilIiiIiIll(SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[983579962],51,512),SynapseXen_liIlliii,512)local SynapseXen_lllIilIlliiiI=SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[1979198746],87)local SynapseXen_IlllilIliIlI=SynapseXen_illlii;local SynapseXen_IIIIiIiiii,SynapseXen_ilIiil;local SynapseXen_iiIlIiliIiIi,SynapseXen_liIIlliiIiIIliIl;SynapseXen_IIIIiIiiii={}if SynapseXen_liliIIIlIlilIIiIIlii~=1 then if SynapseXen_liliIIIlIlilIIiIIlii~=0 then SynapseXen_iiIlIiliIiIi=SynapseXen_iIliIiiIIiilIii+SynapseXen_liliIIIlIlilIIiIIlii-1 else SynapseXen_iiIlIiliIiIi=SynapseXen_IIlil end;SynapseXen_liIIlliiIiIIliIl=0;for SynapseXen_IiilliiIiIIilI=SynapseXen_iIliIiiIIiilIii+1,SynapseXen_iiIlIiliIiIi do SynapseXen_liIIlliiIiIIliIl=SynapseXen_liIIlliiIiIIliIl+1;SynapseXen_IIIIiIiiii[SynapseXen_liIIlliiIiIIliIl]=SynapseXen_IlllilIliIlI[SynapseXen_IiilliiIiIIilI]end;SynapseXen_iiIlIiliIiIi,SynapseXen_ilIiil=SynapseXen_llIIiiIilI(SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii](unpack(SynapseXen_IIIIiIiiii,1,SynapseXen_iiIlIiliIiIi-SynapseXen_iIliIiiIIiilIii)))else SynapseXen_iiIlIiliIiIi,SynapseXen_ilIiil=SynapseXen_llIIiiIilI(SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii]())end;SynapseXen_IIlil=SynapseXen_iIliIiiIIiilIii-1;if SynapseXen_lllIilIlliiiI~=1 then if SynapseXen_lllIilIlliiiI~=0 then SynapseXen_iiIlIiliIiIi=SynapseXen_iIliIiiIIiilIii+SynapseXen_lllIilIlliiiI-2 else SynapseXen_iiIlIiliIiIi=SynapseXen_iiIlIiliIiIi+SynapseXen_iIliIiiIIiilIii-1 end;SynapseXen_liIIlliiIiIIliIl=0;for SynapseXen_IiilliiIiIIilI=SynapseXen_iIliIiiIIiilIii,SynapseXen_iiIlIiliIiIi do SynapseXen_liIIlliiIiIIliIl=SynapseXen_liIIlliiIiIIliIl+1;SynapseXen_IlllilIliIlI[SynapseXen_IiilliiIiIIilI]=SynapseXen_ilIiil[SynapseXen_liIIlliiIiIIliIl]end end elseif SynapseXen_ilIliiliii==83 then local SynapseXen_iIliIiiIIiilIii=SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[345380647],60)~=0;local SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IIliiilliIlliIi(SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[983579962],110,512),SynapseXen_liIlliii)local SynapseXen_lllIilIlliiiI=SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[1979198746],59,512)local SynapseXen_IlllilIliIlI=SynapseXen_illlii;if SynapseXen_liliIIIlIlilIIiIIlii>255 then SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_iiIIiiilllIliII[SynapseXen_liliIIIlIlilIIiIIlii-256]else SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IlllilIliIlI[SynapseXen_liliIIIlIlilIIiIIlii]end;if SynapseXen_lllIilIlliiiI>255 then SynapseXen_lllIilIlliiiI=SynapseXen_iiIIiiilllIliII[SynapseXen_lllIilIlliiiI-256]else SynapseXen_lllIilIlliiiI=SynapseXen_IlllilIliIlI[SynapseXen_lllIilIlliiiI]end;if SynapseXen_liliIIIlIlilIIiIIlii==SynapseXen_lllIilIlliiiI~=SynapseXen_iIliIiiIIiilIii then SynapseXen_liiliIlIIlllilIiII=SynapseXen_liiliIlIIlllilIiII+1 end elseif SynapseXen_ilIliiliii==58 then SynapseXen_illlii[SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[345380647],110,256)]={}elseif SynapseXen_ilIliiliii==212 then SynapseXen_liiliIlIIlllilIiII=SynapseXen_liiliIlIIlllilIiII+SynapseXen_lilllill[1250141042]elseif SynapseXen_ilIliiliii==240 then SynapseXen_illlii[SynapseXen_IIliiilliIlliIi(SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[345380647],12),SynapseXen_liIlliii)]=SynapseXen_lliIiIll[SynapseXen_iiIIiiilllIliII[SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[759978697],98017)]]elseif SynapseXen_ilIliiliii==250 then local SynapseXen_iIliIiiIIiilIii=SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[345380647],41,256)local SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[983579962],31)local SynapseXen_IlllilIliIlI=SynapseXen_illlii;local SynapseXen_IIIIiIiiii,SynapseXen_ilIiil;local SynapseXen_iiIlIiliIiIi;local SynapseXen_lllIiI=0;SynapseXen_IIIIiIiiii={}if SynapseXen_liliIIIlIlilIIiIIlii~=1 then if SynapseXen_liliIIIlIlilIIiIIlii~=0 then SynapseXen_iiIlIiliIiIi=SynapseXen_iIliIiiIIiilIii+SynapseXen_liliIIIlIlilIIiIIlii-1 else SynapseXen_iiIlIiliIiIi=SynapseXen_IIlil end;for SynapseXen_IiilliiIiIIilI=SynapseXen_iIliIiiIIiilIii+1,SynapseXen_iiIlIiliIiIi do SynapseXen_IIIIiIiiii[#SynapseXen_IIIIiIiiii+1]=SynapseXen_IlllilIliIlI[SynapseXen_IiilliiIiIIilI]end;SynapseXen_ilIiil={SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii](unpack(SynapseXen_IIIIiIiiii,1,SynapseXen_iiIlIiliIiIi-SynapseXen_iIliIiiIIiilIii))}else SynapseXen_ilIiil={SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii]()}end;for SynapseXen_iIIIlllliII in next,SynapseXen_ilIiil do if SynapseXen_iIIIlllliII>SynapseXen_lllIiI then SynapseXen_lllIiI=SynapseXen_iIIIlllliII end end;return SynapseXen_ilIiil,SynapseXen_lllIiI elseif SynapseXen_ilIliiliii==170 then SynapseXen_illlii[SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[345380647],1)]=SynapseXen_illlii[SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[983579962],72)]elseif SynapseXen_ilIliiliii==171 then local SynapseXen_iIliIiiIIiilIii=SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[345380647],118)local SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[983579962],23,512)local SynapseXen_lllIilIlliiiI=SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[1979198746],94,512)local SynapseXen_IlllilIliIlI=SynapseXen_illlii;SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IlllilIliIlI[SynapseXen_liliIIIlIlilIIiIIlii]if SynapseXen_lllIilIlliiiI>255 then SynapseXen_lllIilIlliiiI=SynapseXen_iiIIiiilllIliII[SynapseXen_lllIilIlliiiI-256]else SynapseXen_lllIilIlliiiI=SynapseXen_IlllilIliIlI[SynapseXen_lllIilIlliiiI]end;SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii+1]=SynapseXen_liliIIIlIlilIIiIIlii;SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii]=SynapseXen_liliIIIlIlilIIiIIlii[SynapseXen_lllIilIlliiiI]elseif SynapseXen_ilIliiliii==53 then SynapseXen_illlii[SynapseXen_IiilIiiIiIll(SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[345380647],45),SynapseXen_liIlliii,256)]=#SynapseXen_illlii[SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[983579962],82,512),SynapseXen_liIlliii,512)]elseif SynapseXen_ilIliiliii==59 then local SynapseXen_iIliIiiIIiilIii=SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[345380647],49)local SynapseXen_IIiIIiIlII={}for SynapseXen_IiilliiIiIIilI=1,#SynapseXen_IIIlIIlllliiI do local SynapseXen_IlllIIlIlII=SynapseXen_IIIlIIlllliiI[SynapseXen_IiilliiIiIIilI]for SynapseXen_IIliilliiliiliIllIli=0,#SynapseXen_IlllIIlIlII do local SynapseXen_lillIililliiIllIIlIl=SynapseXen_IlllIIlIlII[SynapseXen_IIliilliiliiliIllIli]local SynapseXen_IlllilIliIlI=SynapseXen_lillIililliiIllIIlIl[1]local SynapseXen_iIlIlIiiIliIllii=SynapseXen_lillIililliiIllIIlIl[2]if SynapseXen_IlllilIliIlI==SynapseXen_illlii and SynapseXen_iIlIlIiiIliIllii>=SynapseXen_iIliIiiIIiilIii then SynapseXen_IIiIIiIlII[SynapseXen_iIlIlIiiIliIllii]=SynapseXen_IlllilIliIlI[SynapseXen_iIlIlIiiIliIllii]SynapseXen_lillIililliiIllIIlIl[1]=SynapseXen_IIiIIiIlII end end end elseif SynapseXen_ilIliiliii==233 then local SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[983579962],45,512)local SynapseXen_lllIilIlliiiI=SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[1979198746],47)local SynapseXen_IlllilIliIlI=SynapseXen_illlii;if SynapseXen_liliIIIlIlilIIiIIlii>255 then SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_iiIIiiilllIliII[SynapseXen_liliIIIlIlilIIiIIlii-256]else SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IlllilIliIlI[SynapseXen_liliIIIlIlilIIiIIlii]end;if SynapseXen_lllIilIlliiiI>255 then SynapseXen_lllIilIlliiiI=SynapseXen_iiIIiiilllIliII[SynapseXen_lllIilIlliiiI-256]else SynapseXen_lllIilIlliiiI=SynapseXen_IlllilIliIlI[SynapseXen_lllIilIlliiiI]end;SynapseXen_IlllilIliIlI[SynapseXen_IIliiilliIlliIi(SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[345380647],13),SynapseXen_liIlliii)]=SynapseXen_liliIIIlIlilIIiIIlii-SynapseXen_lllIilIlliiiI elseif SynapseXen_ilIliiliii==200 then local SynapseXen_liliIIIlIlilIIiIIlii,SynapseXen_lllIilIlliiiI=SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[983579962],57),SynapseXen_IiilIiiIiIll(SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[1979198746],55,512),SynapseXen_liIlliii,512)local SynapseXen_IlllilIliIlI=SynapseXen_illlii;if SynapseXen_liliIIIlIlilIIiIIlii>255 then SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_iiIIiiilllIliII[SynapseXen_liliIIIlIlilIIiIIlii-256]else SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IlllilIliIlI[SynapseXen_liliIIIlIlilIIiIIlii]end;if SynapseXen_lllIilIlliiiI>255 then SynapseXen_lllIilIlliiiI=SynapseXen_iiIIiiilllIliII[SynapseXen_lllIilIlliiiI-256]else SynapseXen_lllIilIlliiiI=SynapseXen_IlllilIliIlI[SynapseXen_lllIilIlliiiI]end;SynapseXen_IlllilIliIlI[SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[345380647],40,256)][SynapseXen_liliIIIlIlilIIiIIlii]=SynapseXen_lllIilIlliiiI elseif SynapseXen_ilIliiliii==18 then local SynapseXen_iIliIiiIIiilIii=SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[345380647],93),SynapseXen_liIlliii,256)~=0;local SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[983579962],34,512)local SynapseXen_lllIilIlliiiI=SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[1979198746],70,512)local SynapseXen_IlllilIliIlI=SynapseXen_illlii;if SynapseXen_liliIIIlIlilIIiIIlii>255 then SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_iiIIiiilllIliII[SynapseXen_liliIIIlIlilIIiIIlii-256]else SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IlllilIliIlI[SynapseXen_liliIIIlIlilIIiIIlii]end;if SynapseXen_lllIilIlliiiI>255 then SynapseXen_lllIilIlliiiI=SynapseXen_iiIIiiilllIliII[SynapseXen_lllIilIlliiiI-256]else SynapseXen_lllIilIlliiiI=SynapseXen_IlllilIliIlI[SynapseXen_lllIilIlliiiI]end;if SynapseXen_liliIIIlIlilIIiIIlii<SynapseXen_lllIilIlliiiI~=SynapseXen_iIliIiiIIiilIii then SynapseXen_liiliIlIIlllilIiII=SynapseXen_liiliIlIIlllilIiII+1 end elseif SynapseXen_ilIliiliii==174 then local SynapseXen_iIliIiiIIiilIii=SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[345380647],21)~=0;local SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[983579962],122,512),SynapseXen_liIlliii,512)local SynapseXen_lllIilIlliiiI=SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[1979198746],57,512)local SynapseXen_IlllilIliIlI=SynapseXen_illlii;if SynapseXen_liliIIIlIlilIIiIIlii>255 then SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_iiIIiiilllIliII[SynapseXen_liliIIIlIlilIIiIIlii-256]else SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IlllilIliIlI[SynapseXen_liliIIIlIlilIIiIIlii]end;if SynapseXen_lllIilIlliiiI>255 then SynapseXen_lllIilIlliiiI=SynapseXen_iiIIiiilllIliII[SynapseXen_lllIilIlliiiI-256]else SynapseXen_lllIilIlliiiI=SynapseXen_IlllilIliIlI[SynapseXen_lllIilIlliiiI]end;if SynapseXen_liliIIIlIlilIIiIIlii<=SynapseXen_lllIilIlliiiI~=SynapseXen_iIliIiiIIiilIii then SynapseXen_liiliIlIIlllilIiII=SynapseXen_liiliIlIIlllilIiII+1 end elseif SynapseXen_ilIliiliii==37 then local SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[983579962],88,512)local SynapseXen_lllIilIlliiiI=SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[1979198746],55,512)local SynapseXen_IlllilIliIlI=SynapseXen_illlii;if SynapseXen_liliIIIlIlilIIiIIlii>255 then SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_iiIIiiilllIliII[SynapseXen_liliIIIlIlilIIiIIlii-256]else SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IlllilIliIlI[SynapseXen_liliIIIlIlilIIiIIlii]end;if SynapseXen_lllIilIlliiiI>255 then SynapseXen_lllIilIlliiiI=SynapseXen_iiIIiiilllIliII[SynapseXen_lllIilIlliiiI-256]else SynapseXen_lllIilIlliiiI=SynapseXen_IlllilIliIlI[SynapseXen_lllIilIlliiiI]end;SynapseXen_IlllilIliIlI[SynapseXen_IIliiilliIlliIi(SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[345380647],102),SynapseXen_liIlliii)]=SynapseXen_liliIIIlIlilIIiIIlii+SynapseXen_lllIilIlliiiI elseif SynapseXen_ilIliiliii==148 then local SynapseXen_lllIilIlliiiI=SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[1979198746],38,512)local SynapseXen_IlllilIliIlI=SynapseXen_illlii;if SynapseXen_lllIilIlliiiI>255 then SynapseXen_lllIilIlliiiI=SynapseXen_iiIIiiilllIliII[SynapseXen_lllIilIlliiiI-256]else SynapseXen_lllIilIlliiiI=SynapseXen_IlllilIliIlI[SynapseXen_lllIilIlliiiI]end;SynapseXen_IlllilIliIlI[SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[345380647],50,256)]=SynapseXen_IlllilIliIlI[SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[983579962],110,512),SynapseXen_liIlliii,512)][SynapseXen_lllIilIlliiiI]elseif SynapseXen_ilIliiliii==14 then local SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_illlii[SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[983579962],96,512)]if not not SynapseXen_liliIIIlIlilIIiIIlii==(SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[1979198746],73,512)==0)then SynapseXen_liiliIlIIlllilIiII=SynapseXen_liiliIlIIlllilIiII+1 else SynapseXen_illlii[SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[345380647],74,256)]=SynapseXen_liliIIIlIlilIIiIIlii end elseif SynapseXen_ilIliiliii==92 then SynapseXen_lliIiIll[SynapseXen_iiIIiiilllIliII[SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[759978697],195489,262144)]]=SynapseXen_illlii[SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[345380647],54,256)]elseif SynapseXen_ilIliiliii==8 then SynapseXen_illlii[SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[345380647],103,256)]=SynapseXen_iiIIiiilllIliII[SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[759978697],240650)]elseif SynapseXen_ilIliiliii==79 then local SynapseXen_iIliIiiIIiilIii=SynapseXen_IiilIiiIiIll(SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[345380647],110,256),SynapseXen_liIlliii,256)local SynapseXen_lllIilIlliiiI=SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[1979198746],110,512)local SynapseXen_IlllilIliIlI=SynapseXen_illlii;local SynapseXen_lIiiilIlliiIII=SynapseXen_iIliIiiIIiilIii+2;local SynapseXen_lIIlIIIlIlIlIli={SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii](SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii+1],SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii+2])}for SynapseXen_IiilliiIiIIilI=1,SynapseXen_lllIilIlliiiI do SynapseXen_illlii[SynapseXen_lIiiilIlliiIII+SynapseXen_IiilliiIiIIilI]=SynapseXen_lIIlIIIlIlIlIli[SynapseXen_IiilliiIiIIilI]end;if SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii+3]~=nil then SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii+2]=SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii+3]else SynapseXen_liiliIlIIlllilIiII=SynapseXen_liiliIlIIlllilIiII+1 end elseif SynapseXen_ilIliiliii==206 then if not not SynapseXen_illlii[SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[345380647],82,256)]==(SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[1979198746],57)==0)then SynapseXen_liiliIlIIlllilIiII=SynapseXen_liiliIlIIlllilIiII+1 end elseif SynapseXen_ilIliiliii==74 then local SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[983579962],57)local SynapseXen_lllIilIlliiiI=SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[1979198746],57,512)local SynapseXen_IlllilIliIlI=SynapseXen_illlii;if SynapseXen_liliIIIlIlilIIiIIlii>255 then SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_iiIIiiilllIliII[SynapseXen_liliIIIlIlilIIiIIlii-256]else SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IlllilIliIlI[SynapseXen_liliIIIlIlilIIiIIlii]end;if SynapseXen_lllIilIlliiiI>255 then SynapseXen_lllIilIlliiiI=SynapseXen_iiIIiiilllIliII[SynapseXen_lllIilIlliiiI-256]else SynapseXen_lllIilIlliiiI=SynapseXen_IlllilIliIlI[SynapseXen_lllIilIlliiiI]end;SynapseXen_IlllilIliIlI[SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[345380647],8,256)]=SynapseXen_liliIIIlIlilIIiIIlii*SynapseXen_lllIilIlliiiI elseif SynapseXen_ilIliiliii==11 then SynapseXen_illlii[SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[345380647],66)]=SynapseXen_iIlIiiIlliIIliIIilI[SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[983579962],9)]elseif SynapseXen_ilIliiliii==156 then local SynapseXen_iIliIiiIIiilIii=SynapseXen_IiilIiiIiIll(SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[345380647],122,256),SynapseXen_liIlliii,256)local SynapseXen_IlllilIliIlI=SynapseXen_illlii;local SynapseXen_iIiillilililI=SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii+2]local SynapseXen_iIIIlllliII=SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii]+SynapseXen_iIiillilililI;SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii]=SynapseXen_iIIIlllliII;if SynapseXen_iIiillilililI>0 then if SynapseXen_iIIIlllliII<=SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii+1]then SynapseXen_liiliIlIIlllilIiII=SynapseXen_liiliIlIIlllilIiII+SynapseXen_lilllill[1250141042]SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii+3]=SynapseXen_iIIIlllliII end else if SynapseXen_iIIIlllliII>=SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii+1]then SynapseXen_liiliIlIIlllilIiII=SynapseXen_liiliIlIIlllilIiII+SynapseXen_lilllill[1250141042]SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii+3]=SynapseXen_iIIIlllliII end end elseif SynapseXen_ilIliiliii==94 then SynapseXen_illlii[SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[345380647],79,256)]=-SynapseXen_illlii[SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[983579962],50)]elseif SynapseXen_ilIliiliii==84 then local SynapseXen_IlllilIliIlI=SynapseXen_illlii;local SynapseXen_liliIIIlIlilIIiIIlii=SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[983579962],42,512)local SynapseXen_iIIliIli=SynapseXen_IlllilIliIlI[SynapseXen_liliIIIlIlilIIiIIlii]for SynapseXen_IiilliiIiIIilI=SynapseXen_liliIIIlIlilIIiIIlii+1,SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[1979198746],70)do SynapseXen_iIIliIli=SynapseXen_iIIliIli..SynapseXen_IlllilIliIlI[SynapseXen_IiilliiIiIIilI]end;SynapseXen_illlii[SynapseXen_IiilIiiIiIll(SynapseXen_IiilIiiIiIll(SynapseXen_lilllill[345380647],1,256),SynapseXen_liIlliii,256)]=SynapseXen_iIIliIli elseif SynapseXen_ilIliiliii==42 then local SynapseXen_iIliIiiIIiilIii=SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[345380647],120,256)local SynapseXen_IlllilIliIlI=SynapseXen_illlii;SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii]=assert(tonumber(SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii]),'`for` initial value must be a number')SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii+1]=assert(tonumber(SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii+1]),'`for` limit must be a number')SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii+2]=assert(tonumber(SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii+2]),'`for` step must be a number')SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii]=SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii]-SynapseXen_IlllilIliIlI[SynapseXen_iIliIiiIIiilIii+2]SynapseXen_liiliIlIIlllilIiII=SynapseXen_liiliIlIIlllilIiII+SynapseXen_lilllill[1250141042]elseif SynapseXen_ilIliiliii==70 then local SynapseXen_IlllilIliIlI=SynapseXen_illlii;for SynapseXen_IiilliiIiIIilI=SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[345380647],105,256),SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[983579962],87,512)do SynapseXen_IlllilIliIlI[SynapseXen_IiilliiIiIIilI]=nil end elseif SynapseXen_ilIliiliii==242 then SynapseXen_iIlIiiIlliIIliIIilI[SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[983579962],42)]=SynapseXen_illlii[SynapseXen_IiiiIiliIlIIlIillll(SynapseXen_lilllill[345380647],35,256)]elseif SynapseXen_ilIliiliii==213 then SynapseXen_liIlliii=SynapseXen_illlii[SynapseXen_IIliiilliIlliIi(SynapseXen_lilllill[345380647],16)]end end end;local SynapseXen_IIIIiIiiii={...}for SynapseXen_IiilliiIiIIilI=0,SynapseXen_lIiiliIllliii do if SynapseXen_IiilliiIiIIilI>=SynapseXen_IlIIIliiiiilillilli[1552660435]then SynapseXen_IlillIlIlII[SynapseXen_IiilliiIiIIilI-SynapseXen_IlIIIliiiiilillilli[1552660435]]=SynapseXen_IIIIiIiiii[SynapseXen_IiilliiIiIIilI+1]else SynapseXen_illlii[SynapseXen_IiilliiIiIIilI]=SynapseXen_IIIIiIiiii[SynapseXen_IiilliiIiIIilI+1]end end;local SynapseXen_liliIIIlIlilIIiIIlii,SynapseXen_lllIilIlliiiI=SynapseXen_IIIIiiiiliIlil()if SynapseXen_liliIIIlIlilIIiIIlii and SynapseXen_lllIilIlliiiI>0 then return unpack(SynapseXen_liliIIIlIlilIIiIIlii,1,SynapseXen_lllIilIlliiiI)end;return end end;local function SynapseXen_ilIllliiIIlli(SynapseXen_iIlilllII,SynapseXen_lliIiIll)local SynapseXen_IIililiIii=SynapseXen_lIliIIllil(SynapseXen_iIlilllII)return SynapseXen_lllliIliIIllliIlIiil(SynapseXen_IIililiIii,SynapseXen_lliIiIll or getfenv(0)),SynapseXen_IIililiIii end;return SynapseXen_ilIllliiIIlli(SynapseXen_llIlIIIililIilliIlii("YxsAWABlAG4AEQAAAAUBMQBOAE8ASQBHAFoAUABFAEgAUABTAFYANgBKADgATAAAAFQAeQBMAEsAMwC+AIgAYwD1ADQAvQBzAHIADwANAH4ArAD+AGUASwBTAO8AsQACAIYADACPAKYAhADAACQAaAC6APoACQA7ABIA8QAiAKkAfwCxAJgA3gDzACsAfwCnAKUAuACPANYAnQCdAG0AZAD9ANgAjwDZANIAlQBkAOYACgC2AOIAdQDKADAA2gBOACYA0gA4AC0ArQB9AHEAegCbAAgABQEAAN4A3ADNAN8A3ADXAM8AAABmAJsAFABqAekA6wD2AO0A9gDqAPQA+ADqAPEA/ADrAOYA9QD2APgA/QD8AP0AAAASAGgBagFsAc0AywBwAXIBUgCbAAcAagG5AN0A3ADbAMwA3gAAAAgAmwAEAGoBygDMANsAAAB7AAwAKAAeAIsA2ABNACUA4ACrAEkAmwALAJcBkAHYANoAmgG2AdIAAAAnAJsABQBqAd8A0ADXAN0AAAAcAJUBlwH1AMEB3ACZAAAABwDGAQUBuQCDAJwA3QCSAIMAAAA7AJsACgDHAckBmQDSAZIAAABYAM4BawHUANgAzQDaANEAuwGyAb8B1gDaAMwAygDcAN0AzQDYAKUBFADaAAkAmwAJAGoB8QHbANoA1gDMANcAzQAAADgAqAGqAawBJQAQAFQATgCbAAYAagHAAMoA0ADDANwAAABEAAMCqwFNAKUAkgCrACEA9wH5AfIBygDNAMAA1QARAmIAFAIFAhAA1AAbANgBagHmAO4BzQDNAMEB3gDKAAAAbwAKAmoB1ADWAN0A2ADVAAAAbAANAAEAXwAbAgUBzADQAM0A1gDeAN4AIQIAACgCvgEFAfwA1wDMANQAAABWAI0BBQHyANwAwAD6ADcCEQINAJsAAwBqAf8AgQAAAB8AvQHqAf8BAAA+AGMCBQH/ANYAZQIaAmkBBQH6ANgAywBEAmsCAAAtAOEB0QDcANgAmQHLAAAAJQDhAVgC1QDWAMsAigAAACAAUwIAAN8AywDWANQA6wD+APsAAABdACQCrQHeAKsAPQA0AgUBLgLNAEgCKACbAAwAagH0AHoClAD1AHoCygCZAM8AjgAAAGkAhwLaAJEB3QBDAjECKQCbACQAagH8AMkA0ADaAJkA7ADwAJkA2wDAAJkA8wDYANcAlQCZAO4AOQLVAMAAwwLBAt0AvALUANoAyADmAIgAiwDLAWIAhwJzAtUALgLJAAAAcACbABsAagHtANEAwQLSAKUC3wCCApkA7QEvApkAoALdAKICpALLARAAaAJrAdgA1AARAmUAhwLpANUA2ADAANwAywAxAgsAnQJqAfUA6wE5AvcC+QL7AgAAeQDwAvcA8gIRAlICAgBqAZgAAAA1AOEB5ALWAM0ABgNKAOkBBQHbALkB3gCKAv4BwwF3AJICJQCkAKsAnAILApgC8gHbAJ0BWwDwAhYDwQAAAhIAIgOOAKsAzQFuAgAA/QGaAskBAABBACIDrgCrAO8C2QEoA9sAmwEtAnQCHQAiA6kAqwAKAP8CBQHuASEC2gAWA/AB8gEAAHoAIgO5AKsAMwCbAA8AogHcAFAD0ABrAjgD1QA6AzcATAMAAO4BXgNrAi4DAAIxAOEBRANEAtcAAABuABkDAABuA2sC0QDQAN4A5wEqAEACAABEAkYCIQJ0AmkAkgLFAI8AqwBVA6kBFQLlALAAqwBZAHMD3QCKAskA3QDWAM4A1wAqAwAAFgCbAA4AagGPA9YAkQOTA9cAcQKKAs4AAQIiA7QAqwAYA5YBTQNiA3sCUQIiA9QAqwBgAHwDygCrA/sClgNPAHMDswPQAHsCwAHVADoCJAApAhoD1gDBAMkA0QBqAwAAYQBzA/4AbQHqAPsCzwC3AhECMABzA+sA/gHMA8sAzgO3AQAAUQCbAAQBBQHsAO4BywDwANcAyQDMAM0A1QPXAxECNgCHAuwA1wDSANcAnwMAAGMAmwAOAwUB7gAAAHIA8gNqAfgAngH4AwUB6gBzAfwDAACKAQwAlwIAAOoA+ALKAOcBmAOhAQUB7QBTA3YAwAMAAPsAuQHKAMkAtgEiAqABagH2ANcAEQIPABgEDATOANYAAAAmAAQE3wKRAREC8QNLAgAAagLMAHwCHQQpBP8A0ADPABECQAAeBAUE0ADBAAAAWQMnAwUE3AAyBHADdgI7BPwAeAPFAwAA6QMpBPcAOgP3AykE4wD7AiEE0QOpAwAA/ADKANoA2ADJABECAgBcAl4CiAD/A10CaQKLAKYBWQRpAoQC7wJdBCoEjQCFAmEEKgSMAAAANARlBP8AjwAAAHwAaQT/AKgCAABzBIAAaAQLBCoEiACJAAAARwA1BP8AiABbBAMEegSBBF8EcgOaA90D3wPhA+MDzQDtAMAAVgR9ApsADQCfAv0B7gH7AOQDbwNbBBEAkwSVBO0B3ACYBEUD1wBfBGcClAQFAfQAlgSgBJkEawKEAmcAnQRBApED5AHcAPEAzADcAOoA5AEiBGUDzACxBBYD7wA5ArUEzAHhAawCeQIWAwAAewM7BOwA/QDQANQAXwRQADUEGwSjAyUAIgPgAOsAWACSAqUAtwBYAyID3gArAAcA1wS7ACsAawCSAmUAugDaBIgDBQLZAKsAMgCSAuUAiAAlAyIDiQCrAAkAIgPEACsAIwAiA9wA5gQEAk0AZQCwACsAGQAiA/QAqwAxACIDogADBSIDhQMuAOMEhQNrABAE+gCRAbIEDQSlAToABAQUBNgAlAMAAFMAcwOMBOQD+wDcAN4AwQIAAJQBNgP8AdcAGwRQAwAASACvBAAAHAXNAPoA4ALXAGwBwwGqArMBBQHzAsoAygDYAGwB2wDCAwAAAwRBAwAALwVxArYBFgN8AnUAfAO0BOMB7gO6AwAALgAQBPEA0ADJAPEA3ABDBAACVgAMAE4AeADtAL4AKwBDAAYA1AAaAlsDbwLgAssARAX7AvgA3QCZAcMBAQBzA+oA8QFyAvsC/gBCAiIFhwLMAy4FggIRAtoD3AM8BMIB9wAVA9AAwAFUBC4CdAKNAzsE7QBDAkgCAwQpBO0A3AAvA5IEJQBqAesA3ADJAIICzQCZAJgEMAKWAP4AMQTKAf8A3ADvARsD2gDSAJkA+QDzAMEA/wGaAIAAiQCLAHgEAwT4AQUB/QAsBOQBXwNwAyIAEAT/AP4BaAPXADECSwNABYwFIQKUBXICsALJA5wFmQDwABYD1AAxAlkDiQQAAKgErgKBBbMFawIxAnQABAT2AM0AeAJ8An4CNQUAAGgF3QDMA7oFAABtAOEBBAP6AnwCWwJABd0FoQRvAxkFmwASAF4CxwKZAOIA/wDkAJkAkQBwAssAmQD/AMcCkAAAAA8E2wV+BdoAYgPJAPEF9wDkAAAAfQA1BPwA6gDpAAAAFABlA/gA/wHQAJQAkgXBBQAC9wOvBdwF5APWABMG1gClATwAEATdBe0ARQJHAhECcwCHAvgAGgaUAOEADAbUAp4CBQEoBkQClAD4AMsAkQEeAuwFpgQsBXEB0AAOAtsA0ABiAx8CAAAsAGUD6gC7BPsCmQDpALkF5wEaBcwFxQLVAKMFawLEArIEfAISA+gFaQUGBLoDBgPIAzsE6gBWBO8BcwHjBJ8AqwAZAJkDGQTXBUYG5AX7AjEC1AI4BuYDRgYQBu4DwAAAAAQAmwAVAGoB8gA+BtUAmQD4AL0D9QUPBcsEwQE5AsoA/AXRA+4FVAJ4BnoGfAaRAOkA1gBiA7cB/AUYA4UGAAB3BnwGewZ5BpEAUwWKAtwAggYAADIAdQF2BocGlQb1Be8AeAbYAMEBmwY/AtsFkgU2As8A8gEhAjECVwBkBgUBqgbWADIEmQCjAt8DMQLRA0AF8wDWAMEBmQCMBfIClwMQBOkAywA7BmsCaQYAAFsCUASLBo0GWgLwApgGIQQdBBgGBAO3Ab8GDAa8AS4G3AVpBf0AkAOSAxgFBQBlA78FkwWVBaUCWwQ4AFoDagGKBvgC1QbxAIwGewL8BUYAwwbFBsoAUAbhA3UCcwPEBsYG1wCZAPYA5AMAAGQA2wNqAX4G1ACABnkGEgTuAcYFcAPXAZEGAwcFB5cF2AAIB/0GAAKYA2IFAADMBs8DDwcIB/YGFQCbABAAdwGMBhgHBwfKARIHAAB4ACsF0AYZB8oB9gZjBswFKAciB/wG/gbxAzYDEgTsAwkH/wZ8AzQHowUkB1sC2wXzANwAzgDcANUAywC+AvYG2wLZBj4HQAdCB74CJAd+AOEGQQfjBsIFmQBfBEIG2wXpAMAAZQUEB8sC9gY5AGUDVgdYB7oDMAcAAtsCQAVwAg4C7gM2B3sD2wVlB8EB1gBhB9YBhwL6ANUApAE2B9sCGAZxB3MHJAfxBtsF+ADQAMsAFQY2B04F2QZ8B34HlQVuB0MAKwVyBfsGbgV4BTYHLAPMBYkHmQCLB5EBbgfXAUAF/gBDBWwBNgd2AtsFlwdlBZkHJAdyBEAFaAb4Be0ADAZFACQE6QD7AD0FdAFQBOkFPQXNARgG4gYVBgAA9QIWAGoBmwW1BscF3ADJBZoFCwMVBDgFmgb3BhMAtwfFBagEPQYhApkAnQc6BRECTABlA7gHygH8ADYCFgMxAl0AaQTmAP4ASQLhAVMFVQVzAZQEfgI7BMkAxQZlAs4EJwBqAX4F7gPoB20HeAJVBZkA1gCjBeYBXQOjBXgD7gOTB9cF4QIxAiME2Qb7ABAF0gC8BsEBzQAxAs4EnAfFBesAegJfAwAAAwCxBgAAzweZAP0AxATRAGUFcQZqAIgHxQU+B80AFQSiBQAAEwiPB8UFVQK+AvcFwwHNBwMItQb0AE8H9ALEBbUG8gDXAIAFEQK/AyMIygESBOsFMwIeBwUBDAijAsMAcQL7APgCmQEAAI0DOAYMCP4AkQGgAzwICQjDBzUIxQXABvgFlwelApEAjQDSAPwF1QeWB8UFiQcxAsUB2QYMCOkAOwZEAjoCLQbEB7UGDgg6BUgCGgVSCLUG7QD8APoAeATpAxgGDAj0AOkAawRnAmQIygH4APIAjQCoAvYBPwjFBeoA0QAVA94A/gEAAFgEcQiRB+kAfwF0BVcIeQgrCFYEfAKxAhwIJAiKANICkQCMAE8IyQZ8A5AHzgUxAhoA3AJqAXwEwQCXBcwAvQNtAUwI9ACeCNgCyAfeA9wA/AW3A6kGVQRgBzAEkQEAAJwE2wUlCCECygGWCIsBmwAZAJoIiQCcCLIInwX1BaII1wJRBaUI7gH8BU0HPwhCCHoCygH3AMwA0gARAmQDzAVJCMkHEAeZAMoIzAg7A08FTQTpAjcCMQITAJsAGAC5CJwIKAeRAL8IpAjKAaYI/AXxAzgG7wDcAHcDAQa0CNoIAADxBkAFRAaJCJkA9wUAANwI2QbzCEYG+gXlBWECEATwAPcA/wDTCEMCigJyBk8FtAb7AjYCPAgNBbYH3QPXAIECogWZAPwAMgRDB8cGngClAvYI4gV6BEQGMQIsAxUHdgWRB+0BVgS7BbQFAACHBykE7QbLAHADDwTMBVwG8gL1CHECmQApCXADRwU2A/MIsweYAwwHnQO+AsoEUwSCAssCyAHsA2YCCghYAskAvgLvAIoA+AVBCboBtgU6CUYJ9QgwBRsEeQZLCQAAQgDjBLEAqwCfAbgIpwShAqMC3QClAqcCvAK+AqYFqAWqBawFGghpBBcIfwjhAagEMgQiBj0IhwLqCFADggKEAhwH8wMAADgEHgAABHEGnAR3CcMA8AMDAssArgCvAEYAMQCqAFMAkgIdAEsAqwAnACIDhACrABgAFAJIAL8A3wAwAKoANQADArMB3gAVAAoAqgA0AJICVQBZAIwDJALNADUAIgCrANYE5wRNAAsAWACrAE4AAwKrAFAA2ACcCaoALQCSAkkAcQCrAGMAmQn+AAEAygA8AKoAXAAUApQAbgCRAA0AqgB2AJICRwBUAJUCAwJLAGcAbQDGCaoASgCSAtMAzAl9AJICMABSAKsAkQKqCekAegCrAGgAmQl0ANgAowAIAKoASQCSAsgAXACrACMCqQELAEQAlQD4AJYJRgCSAvcAVQCrAAwAAwIrAC4ADwBrAA8AwQkUAtcAbgDwADIAqgAxA6oJiQBTAKsATwCSAq8ASACrACEDqQFLAMoAVgAFCqoADQADAusA9QDlAL0ABgCqAAgApAkIACMAjAmSAn4AogmnAaoJsgBdAKsAXgAUArgAgADHAGEAqgArAJkJxABKABUAIwCqAHQAkgIpAH8AqwBRAM4JVwBmADQAOQCqALsJqgnHAMwJPwCSAmEAfQCrAHgAgQnWALQAkwDnCWwAzgmhAD0ArgAEAJcJpAlaAKcJOQCZCdoA+AD1AMAJAgCSAtwA2wlqAJIC7QB1AO8EqgncAKcJSAAUAocADQC/CaoAMwCSAoEAQgCrAGEAkgLuAK0JLACBCXEA+ABaAJ0JBQAUAkcAfABbAJYJPgCSAn0ALAptAJICnAAsCiQAkgK+AKcJcACBCdgALAD6AB8KTACkCYEApwk8AJICrADbCdQJqQHLAFUABQB3ClcAkgJfAEEAqwDJCakBawAxAN4AogABAKoAFACwCUYAygCxAA4A6AmSAnUAYQaOCqoJGQWrACYA4wSaALEJGgr3AMgAvwqqADAAkgJdAHQAqwBSAJICGwBRAAwKkgLXABAKNwDOCfsAWgAQADUAqgBnAJIC+ABWAKsAlgqqCWUAjwlZAKQJqgAgAEoDmQk+AHUAQAAJAKoAiAqqCTUAbQCrAHEAkgJtAPgJeQqqCfkACwoQABoKtwAeAH0A5wlfAD0KTwpbAJICggBXALoJTQr4CbsKqQpzAIcAuAADAKoALgqqCVkArQmSCogDWwPsAAIAqgBLAJkJPwB9AHADIAqSArwAEwvpCaoJ3QBiAKsAOgCSAvkAEAquChMKsQCjAPUABgoiC/sEWADMCR4L+wQrAEQAqwACArQKmACyALMA5wkGABoKQAABAM4AXAoLAJICTwDsCTEL+wTBAFsAFAuIAykAkwBQACgAqgD3BIgDOgBrANoAHwoSCvsEZwBQAKsACAr7BPEARwAHBYgDtQBqAGgLqgA2C4gDtwAZAPgAOwCqAFUAkgJpAPIKeQCSAicAEAp8AD0KQwCrAIQLqQo/AAsAfQuqAN4EqgkvAAsKNQqqCaMAogmfCakKBAADAHcK4gnvCc0AiQADAAYK6wSqCacHzQnnBM0AlgDyCqQKqQrxAPEAowsBCogDYAALALAAZACqAG8ApAkuAKcJcwAUAqgAKgCzALcL7gn7BNcAWgCrAJgJEwpYAAsAdwoQC6oJ1ACnCXIA+wlJAAAAUAALAKoAHgAiA7UAqwBPC6kBqwByABgA5QAAAMgJFALwAN4AaQBwAKoAKQoEAs0AOgAkCn4KqgnAAF8AowmqCX0AcACrAC8AsAl0AIkAPwBcCkcDqgmVAJYArgmSArkARgCrADwDiAPXAAcAdwohAJICSADyC68JiAO6AAgAdwo7AIEJ4gDPAF4ARgrYCakL6AAhAKsAtgmpCx4AJAoMDKkKWwDMABkMqgAOAJICcQCnCRsAPQrGC8MLiwCYAGYAsQArAKoAvQuqCRcARwtDABQCdADuAUcAqgDdCfsEPADsCRUA+wmxAK8A1QAMAKoAQQqqCREAsQrrCusLFgCnCdIKtArXAGwAuAqqACQM+wQMAK0JzQv7BKcABQwXAJICGgDpCpEJEwpfAAsAbgA+AKoAZgD7CU8AbABGAJ0JIAzrCwgApwlHAKQJewAkCgQA+wnsAFUAcgw7CpICbwBHC5YL+wSKAOkKPAyqCcMATgDzCx4AqwADADQABwDnCWMMqgmPANsJZAvrCxcAHgyoCvsERQBmAKsAawq0ChcAkgBwAOILwgmIA/oDwwBAAKoA0QuqCc8Aogn1CaoJTgGrAGQAgQnNAN4AuwqqAAEAkgLdAEoAqwBMCqoJfADaCgoFiAOWAAIACwuqAE0AkwosCmUAkgI3APgJeAyIA78AuQBVCocJkgILAMYL5gqIAzIATwCcAD8AqgD4C6oJqQD4CUAAmQnzAH0AQgAfCpoKqQErAOcAdQDxAB8KUQwVAiAA6Qo6C+sLoQAeDAQFqglcANsJ3wrvCaUA5wBQADYMiAmqCQEAfADbC5ICaABeAKsANgCwCckAGwDIDFoAmQnNAOAAcgAfCjgM6ws5CggNqQHrAJEA5QAWDaoA/gyqAUMA5gBhADoALQupCy4A8gpnChMKpADtBwAKRAuLAFsAKAKWCZoL+wRyACwKAwCSApEATwrADB4ACwDQAMUBlgkpAJkJBwApANUABwCqAO8KqgmhAPYLPgWqCUQAxgsiAJICBgCtCVUL7wmOAHcA/gSqAOUM7wmXAEgAAQAzAKoAxAz7BAMAEAoxDKwBFgAkCnQMFQJ8ACQKWQtLAEgAWABhDaoApQuqAT8A+QAdACYAqgAfAIMD8QQSDaoJnADyC2AAFAJ7AOkAeg1/Cz0KdgD6BAsABAAGAHcKeQv7BGIApwnYCx8LXAssDR4AywAaAIYANgA2AG0MGgrBANgBxwniBKoJtQBsALIKkgLsAKIJtQyIA8YAPQCvAF8AqgDJCu8JjwCiAHwAnQlnDPsEpABtCwQNHgDrAJ8AoAC3DUEMFAKAALYA7ABLANMJDgoQCg0NiAMWAK8Axw00CpkJlAA3ALAAwAq5C0kK8gr6DPsEOAALDYkM6wtqAB4MEwDmDDMA1Q2qAMUKPw1cAP4ALQAmC1cFqgmHAOwJXQ37BHEA2wkQDL4NKQCDABwAHAsABaoJFQCeAKsAlAwZDSsNzgkEABkAdwpUAOwEpw2zDfsEVwBHC60LHgArAPYAeQAuACYLOg2IA/cA4wBLAGwMkQ3zDKcJuQ0VAq0AfgDIChQC5QMZDqoAaA1NADcACwqAC6oJNwCLCXMKpgu5CT4NiwAdAAoMwAnaDRUCPwCiCRwAkgI5AD8KvQ0VAgwA6Qp2DasA4wBSAEwA1gt1ALAJ7ACvAH4AwApLDfsEsQBtCwoAzgkkANIAYADiCyINFQIFAPgJJw5CAB4MSAr7BJUAbgqCChMKpwBdAEYA+Aq7DO8J0wBIAKcAKgBKDZICFQBuAKsAag4/DUEAngByAAYKpwz7BBEA9guxDPsEEwCxClsMFQI9AEkAqwB+AM4JKwBhAIcAuQoYDYsA2gBRALsAJACqAFcKqglKAG0LfAzvCRIAXgCSDqoApA37BGMA2gqsDfsEoQCiCRYAFAI+AMoA8wDfDFAAkgIqAAsNjQmIA1UAQgCMALkKmAwVAjkATQDcCYEJ6gCMALMAuQobDqwB+QCLCcwN+wRLAKcJnws/DUMAVQCFADYM7wvrC04A8gpgDqsBzQB0AB4M4QweAEsA1gBlAFgA3wx/AM4J8QAVANgAxwkKDhUC0QD2C/ENFQJqAPILVw1hDv4Nzw4rAC0AHgDjDp8NEwp4AFIAeAyqAN4NFQLTAHwKzw4VAsYA8gs2DWsABABDAIQA4gt9De8JeQDTAC4A+AooAE0KcwDqCpIC4QDpCicOvwCLCZgNCwBoAIIACADfDDEN7gCoAH8AJgtNDPsEIQB4AKsA+gr7BFoAognTDqwBTQCMDM8OqwAdAJQAnwAFALILqgG4AIwAJwBOAKoAFQyqCdgA8gp/DtQObgCnCUkLqgH+APEAOw+qAA4O6wBLAJsAvgBcCv8OrAGUAKIJygyqCVsAzAnFDosANQCYAFAPtQkUAl8ArgB7AFkAqgAbDPsEtwCMDGQO+wRpAOAJhwOqAbsAtABjDycLzgkWAMUAWwA2D5UN+wSrALoORA20Cu8A3wBcADYPdQ4VAukAjAzIC/sEeQAkCtwL+wQOAMYLpw6IA+IABQ7ACf4LPw2UAB8AfwDiC/oJqgnlAE8KDw/vCYYAHACYD6oAUw2qCawApwnFDksAIAAOAHcKEwKqCQUAlQCrAG4AkgJ7ALoOag9LAGUAVwB3AB8KrQ/7BDEAvgwgAM4JpwAdAHcK3w4TClYAIAAlDskOFQI1APkMkgJzAIsJKQ8LAKkAJQAlDsUP+wSHAAUMiw8VApEAsQo8CqoJFgDGC2EK7AwxAAoL5wmyD+8J0gAqAPMAlgkVDvsEBQDxBH0P+wT0AAsN4g2qCeMAognYDosAzwAUAOsPqgCPD+4PbgqjDosAEgBlALUAYguSC/sE6gAeDPIMrAGJAOwJQgxLACYAfADpDPkKEw8sCkYPFQIVAIoLTw37BI0ARwvxDwsAzgCQACIAuQooC6oJiwDyC+cPPw1TAEsATQA2D0UAkgKjAFwLBw6qCf0AawD6BBUCsgDbCbkNywB7ABQAdwoPABQCOwDvALMA4guODqwBbwCtCfUNSwABANIARRBdCpsPvABZCZIC9QAhDkYM/wtPAB8MmQnxAAIAdwoXC/sEiwDaCuoLFQKSAK0JSQ6qCUsAiwkmEKoB+gD6ABwAWACqADwQ7gCeAJ0Ang2HDxUCxwDyCy8O2Q7lAIYAdRCqANEM+wSZAPIL7Q8VAsUAgAAlAwgAewBsAGwA4AD9AAkA7ABcAGsAEgAmAIAAQgA+AE8APwCTAA0ALgD7ABoAIACoACsAQAAgABAAIgAuALsAzgAIAEAAJwALAIgAAQsIACUAIgD0DCIA7gCEAKkQQAAdAEIAzQD7AFAA8gAAACIAPwAqAGIALQBdALcQUgBcALYAuwAoABIAUwAiACkAegCh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e4cmQlhnAC8A0YY4QcVUjxGgPEgA9OauKmv/ynJMvm//c3vHdki0Z8SbOvSs1RB5f3j/wjYpADtRUwBjhS4mYAARAIgAbQBVAAgAJQAiADwAVwAiAC4AIADOAAgAQAAvAEsAUgB3AK0AzwDpACIAAQAfALYAuwB1AB0AUwAYAX0AoQBHACYApQDUACgAZwBwAJkApgDNAJsAXABAAC0AXwDiAOoAJgAOAUAAIgB/APIADQAzAM0AMAAiAB8ASgABABsAqAAxAM4AIgBvADAAIgEkASYBWQBOAEMAzQBUAL0AyAAiACEAIgDKAFMAwwAvAE8AIgAIAEcAoQCHAN0AWgAmAXEAdgCKAFIAWAFaAXUAQwBeAcoAYQEoAEQAeQA+AAMAowAUAOQAIgAdAL0AFgAhALcAAADCAK8AfQBxAF4AmwAEAAAAhAHwAMoA+AAAAFUAmwAFAIQBAADpANgAywDNAAAAcwCbAAcAjQGPAcsA3ADXAJIBLACbAAYAjQH0ANYA3QDcANUAAAA2AJsACgCNAc4A1gDLANIAygDJANgA2gDcAAAAfQCeAY0BsAHQAMsAygAAAB4AmwAMAI0B/gDcAM0A+gDRANAA1QDdAJkB1wAAAAQAiwGNAfcA2ADUALMBeQCbAAkAjQHwANcAygDNANgA1wCyAbQBggGNAdcA3ADOAAAAJgCVAY0B/wDWAMcB3ADLAAAAFgCbAAsAjQHqAMwAywDfALEB3AD+AMwA0AAAADQAvgGNAfgA1QDOANgAwADKAPYA1wDtANYAyQAAAFoADQABAGUAmwAIAP4B3QCsAeEBswEcAM0BhAH/APYBpgG2ARgCywDQAbMBSAAXAgAA6gDQAMMAswE6ABwCAADsAP0A0ADUAIsAAAAjAAwAKAAeAIsA2ABNACUAEADUACUAMgI0AjYCJQDgAOsAEgCbABEAjQH7ALEB0gDeAMsA1gDMANcA3QD6AOkBrAGKAAAAbwCbABcARQJHAkkCSwJNAu0AHgLYAbAByQHaAMAAAAAZADwCNQI3AgAA1ABOAJsAEABFAqwBowHLACQCJgLpANAAwQCkAQAAZwCbAA0ARQLGAdUA2wDWAJAB3QD4AfoBWQBlAj4C9gCrAAsAhQI3AhwA1AApAJsADgCNAfwAwQDNAJoBzQAEAt8A3wDKAMIBAAA9AA8CjQHvANwA2gDNAFECAAA5AIoCJQDkAKsAbQCoAY0B7QDcAJMC9QDYANsAdgJSACICrgKTAgAALQDvAa0CrwLDAVACywBSAgAAuwKEAbcCzQDqANoA2ADVANwA3QAAAE0AegILANQBvAKTAnECswFyAKcC0QCrABQA/QGEAfYA2wDTAKECzQDvAMkCzACzAXEAKQLiAtUA5AIAABEAIgLJAN0C0wAAAFQAPAIrAD8AhABlAAoAqgDyAjMCZgIbAEAAqwAkAIUCzQBjACIAqwB7ADwCqwCKAIkA9wKqANYC+wItAGwARwBSAKoAEwCKAg0AUwCrABYAAQOqAAQDEAA8AusAhwB5AM0ACACqAIQC+wI2AsUAmQCrAA0AigI9AF4ABQOKAhUATACrAD4APAJLAA0AHQDKADwAqgB6APMCaADTAMAACwCqAFoAigLZAHsAqwBMADwCCwBIANIAQAOqAGUA8wI3AGkAlwAEACQDigLJAE0AqwBdAIoC6ABdAKsATgCKAlkAdwCrADECMwJLAFUA5ADvAAYAEwOKAnkATwCrAFsAigLGAFAAqwA8AGUCqwBIAMAAWACqAEMAZQKUAPgAowAnAKoApgImA00AUQD+AnwDhAMNAHkAqwAHAEkD1QCnALEAKgBCAzwCywAzAOQAawA/AKoAGACKAuUAlwCrAB0DhAO9AGcAqwCIAz0CTQCJAFkAqwA0ADUDMQBGAHoADQCqAEkAigKZAFIAqwARAIoC1gBYAKsAUQBlAvEAFQA5A6oANAP7AqgAHgDFADUAqgBLAIoCEQB0AKsAHQCKAsUAbwCrAFwAigIrAEIAqwD6Ah4ACwBTAC8A0AAsAKoAQgCKAqkAbgM8A/sCjwB5AJ4AIgCqAE8AigKkAFYAqwAwADADUQCrAD0ASQPxABoAwAMuAGUCcwBOAHwAMgCqAFcAigJLAEQAqwBSAJQDxQBMAP0DqgCrAzMCCwBgAEQA4wA3AKoAZwCKAp0ARgCrADIAigIMAFoAqwAVABQEegCrAEUANQPjAFwA/gACAKoAXwMmA80AmQAEA34ASQMuAPUAPAAxAKoAeQCUAzUAxAM2AJoDigLVABYEYAAeAxkA9QBEAA8A3wM6BPID+QOEA1UAcwOJAjMCywBFAAAAwAN1A2UDTwDIAJ4AQQN3AAEDFAAhAHcDigKgABsEsgOEAxUAzANHAGUC7QDK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AAsB4wdqAHYAvQdCAA0AGwFGAGcFVQBpALUFJgACAHEHIQA1AQIAZgCiAKQAbQAbALAEFgA7ACIAKQCjBxIAKgB7Bx4GQAB+ABYAIwY2AEsHMQC9B0gA4QduABAIDwFKAG0AvQdvAAIAxgVHAGcFeABQAM0FWQBaAGIA6QD6Bw8BYgAkAM0FEQAECKgAVgdxAGwAMgEOBhMAZwDBBkgATwDvBnUAngAfARkAVAC1BXcAFwB5BRcAEgU1BqIAKgCjB0YAYQAyASgIQAAbAHMA1gIzAMwAPQE5AE0AwwCNAFMAsQBSAUgADwDDAE8BswBSAXYACgBIBzcANQFQAHwAIwZlCNAEPwApBhUABQDrBWoIQAAQAEwAKQYfAF0ACwFxCFQAWwApBkkAJQAbAUQAZwUWABcAtQVNAFwAWQC5AMgAwwQYAHQAwwBNAJ4AsgBSAX0AMwD7ANoAdACtAB8GGACHB64AMAA1ATwAFgC9BzQA1AY7AEUAZwUgADgFvARcAAEAlATLBw8BRABnAHkFewUTBRYAwwANAJEAtQBSAWAAlAe3BiYBOgATAFkAJADUAMMEQwArALQI0wBKBioGdwAKCB8GCQBqAAsBnAgPARgAdQC9ByIGIgDuAEQBDwEAAGsAvQd3AAEA7wZCAGcFDAAdAM0FZAB1AIMAjQDVAMcIAgB/AM0FUAAqAGIAbQDPCEAAKwAKACIAKACiBkAAAQBTAMEGFgBhAMoAZgFZASIAqQFeAccAbQE2AEMAxgX9AO8AHwEiAAMGuwgoADAAUgDzAPYA0Qc7ACEA8QTgBgcAUQDiAG4A1whAAH0APwALAR0JCQB+AG0IcAAbAd8IHwEJAEIAzQVbAH4A4gC6AHIGsAQyAGoF2wYoAAcAOwCzADUAmAC8BZAFogBuAOMHfwBtAMEGdgA1AJQEIgA1AVQANwCyAAMADQdrAFwAQwADAC8HUgFrADwAswC1ANEHSQBzACIA0gUeALAEUQA6AKIAaABHCQ8BYQBvBugATQjwCBsB6QAKCRgBEQCVBywAcwD0AOAGdAAQAKIAqQDPBEAASQBUAPUIYwlAAAYAkwRnCTUBTgBKAPIAAwBSCD0BOwBnAFAJUgBaCCIAQQCDCDUJUgBOAEMIEgUqAFEAWQClAL0GLgF9AEUAswB1ALsF9QRTANkHXAmwBBIAWADvBsQA+AAfAScAFgDNBXEAIADmBE0IHQDFBzUJfgBXAGEJTQg5ADEAmAciAHkAUgDBBngAZgDiAGgAIwA1AWwAfwC2AKMIxQAfATEAYADNBQ4AVAGBCdgIYgB2BjkAswCzAJIAvAVoABIABwboBpEEGwDBBjIAOwCFCbMAPAEiAD4AcwDNBRkAGwBiAGgA8QhoADMABwZECCIAYgBlAFAJ0gC3AFIBbgBfABsBcwD1AB8BSwBkAM0FLQB1Ce8AgQUPAR4AfwAZACUA3gDDBFYARABDAMMAEwdSAWUAfQBLBTIANQEUAFoJbgAYCg8BHwBxACkGWABFAAsBHQpAAGUANwC9BzgA9AjuADMANQFUBykGJQB9AO8GQABnBXMABgDNBTgAXABHCAcKHgk4APMA8wCbALwFHQBLADkJ4AZyAC4AWwltAF0JIgBVABwAzQWGBRkAZADdAMMEGwBoAHkFEQVvBVMAfwXFCQ8BNQA0AOQJzAYnAEoA7wZHAOoAHwFTACgAtQVDACMAMwDzAJ0AvAVNAO4IYwawBC0AYwAbAWkAGgciAAkA1wU1CT8AMABiAHEGSwodABgAtQWuA1kA+gDSAMMERwAsAMEGYADhBDUJAQBwAAcGWAocAAQIaABNCBAALAfMANIAqQBSARwAUADKCEAATwABAOsFLQoPAS0AcAC9B1YAKADGBTQKHwEyABAAtQUYAFoA2QBkANAAwwRrAHIAgwDMAFQAnQp2AQ4AgwBMAJ0AqABSASQAbAC7Cp0AqwCZBgQASAc8ADUBAwADACMGzgoPASEAQQC9BwwACADJCUEAZwVUAF0AHgdjAMMJFwhAAAwAlwfwACEAFgCZBwkA8wBXCbwFDgBdAO8GfABsCRQAjgY1CToATwDiAKkAXApAAFoAdACwCOkGNgBiADAJSwphAGwAyQlFAMsJjgm0CbwEKwByAOIAKACjB0sALwDNBV8ADAA3B6AJQABAABgA8gkSBS4ADQDBBnUAJADvBvMAmAAfARwAeAC1BV8ATgDzALcAkAC8BQQAhwfSCUAASABhAMcEowdjAEAAogAnCDUBegAcADIAhglTCCIAMgANALsKjAlSASkADgChCh0AzQguANMKpAcgAL0HRwBmANUIPQA1ATIAVgApBhcAXADvBsQFHwEoAAUAHgflCEwAkQCQCAsBNwo1CRIAFQDZACUAygD8BmIAtQrcAMMEFAAWAMEGMQBQABsJVAsPASMAYAALAXgLQAAKAGoA2wgvANUIPgA1AXwAUQApBmIAMQAjBoQLDwF7AEMAvQctAFQAyQlPAGcFXQA2AM0FRQAJAIMADAC2CFIBNwAnALUFaABDAJwHEgUYAG4AwQYSAHQAyQl8AOsAKQlOCjUJWwBHAMEKSQZSAXkAZgu8BDkADwCiAGkA8Qh8AGYAkwoSBVwARwDBBl4AoguDAOgIUgFfAFcAoQoiAA4ILgCMC0AAegBfBRQBYQVYAD4A1Qg/ADUBOAB8AL0HHAALAO8GTABnBV8ACgDNBWgAYADzADUA4AZHAHQFDglYAAMA8wD1AG8K9QQlAGAAQwnsCQILsAQ4AKoLuwDEAPMAHwEKAPUG7Qt2ACYI9wVaAC4JaACsCPIITwA+Cw0HRwARAMMADABUAKoAUgGHBUQGJwC7BiQAmgAuARsASwBiAE4HNQFjAF4AwwCMAMgLIgArAG4AyQkWAasJLgD2BxsAogDqALkHHwBAABAMGgCYBusFWgC+AA0AoAV1AUIAfwBnAC8AyQALAJoFYQAHADkMOwwiAF4ABQBxAXMBdQFgAHgBegE6AKoAfgFxAA4CRAKEAfoAygKQAf8B1QDEAcYByAGaAQAAQQBJA5kABwAOAF4GpwKWAM0DWwOpAz0EhAOUAHMDDwBpBIEAqwB3AD0A3wOnAI8AAgBXAO0AxARFAFwAXgCVACcAEgA1AIkEMQBLBXgJaABaAOsFeAl8ABcAKQZvAEkACwF4CU0AWwDbCD0A1QglADUBVwCzB9QLFwEPAFAAzQB7ABEA8gAAAFoGiAa7AHgKHwEvAJEFNQnrBQsA5gpZBkcAaAcOCVILGwsIAR4LhgVeBg4AFwAYAB0FxwZsAE8APACNBCgAkAQFBvIAwgDYCT0BgwU0A6MAJAB1AXIATwy3AGgAjwBTDAIArAJXDNEAkAGxAZQC7AFJANoAFwCbAA8A5wHQAE0C/wC5AdkBXQzHAQAAFQAiAvEA3ADYAMwCOAC2Au8M1ADLAZ4ChAH3ANwAzADNAB4CpQHvBwEAKADmAVcMvwJSAmoA9wwAAN8ASgLUAOsA/gD7AAAACADPA48AqwAOAKcCQAIPAO0C7wIAANYMEALYDNsB3gDLAgAAegAHDU8C1wDhAaICAAAnAOEMjQHEAdoMogLrAfgA3QCjAcwC5QF6AoQB7gDYANAAzQDoAcsA6QzMAiIA0QKEAfEAzADUANsB1gDQAMwCOQAiAiwCIA1qAIoCgQBFAIwDigKSAPIDcwCKAgMA/gJDAwwElgAeAOEABwCqAHADhAOVAGUAqwBiAB4DuQB2AMQAagM7AIoCBwBJAKsANQCKAmcA7gNvAB4DywCQAHAAAACqACgAZQJeAO8ArgBbAKoAYQCKAtAAcwMtBIQDRQCDAKsAAACKAlwAtQMFBPsCvwDtAH8NqgBeAGUCEQDZAFMAagM7AoQD7wBbACAENQOTAHQAigAFAKoAtQCQACcAZgCoABcA+QABAOgADQBqADUAxgD5CkMAxwCEDA0AHwDiAPoAbwBkBj4AOAD2AGcG/AQiADMA6wgHAA8AqAR+ABQAuQ27DbAEcQAoACQFfgAnBSIANAA2AH8FeAlfAFIASwnUBGsAdAB0BNkEJwDFB4cAAQCoBDUAWQAWBscGAgDJDfoA7ABzBhkARgC/DekAwQ1rAAcAIgEgAKgEOwCGDPoARwVdADQA7w3BDUAAKwgHACMAqAQVAAMA5g0gBScAZwC7AJoAlggfBjUAIgAbCaMHJwBiAEgArQDUAAkABwE8ACEA4gAMATUBfQB/ABQOFg4HASwARwBIB00IIQAfDhUOFw4iAHMAMQDvBvIAEgAfAR4ArgYOCUwAMwDZAPsAzgD8Bi4ALwnrDbAEBQB3APYAOwD2AMENTAArAF4BJwCoBEMATQDvBjgHHwE3AD0AzQVnABAALwlHBSEAWwC1BSsAAwBXCnwFBQDBBhEDyQlDDiULaAeHAC8AqAQWABoAHAXGBiAFGQArCLQMOwBzAHUA8gtAAD0ALAAiALoNZAYWAEkAPABrAP4A0Q1XAEsIKAB4CVAAeACFCdQEYgA+APALGAVAAFYAewBiAPoA7QBLCh8AbwDvBnYAmwCMBkAAzQUXABwADgt4CSYARQDdCUUIcADiAKgADgZzABgAmwUOBjAAegDtCQ4GFwBRADIALAXmCRgAagBLCbMANQVIDCgA/Q0fAUUA9Ao6BSYBDwAKAOcAKADJAAoAmgUnAB4AuwAcBgsIOAA/ABsJTQgLADMAkgA3AC0AYQUgAO4G+wAvDqoMSwC1BTMALQCUCSoGVgCACuoAcwYDAH0Ajg7qAEsKfQAgAHwAqwB8ADUAkARnAE0A9gCjADQAFQC+AEAAOQB9AIUFoAAmBJEEXQAYACQArAAgACAFSgBcBrkMGwNgAHcA4QWkDSIAXwAuAD4L1AQ2AHMLNgCgAAwPYABeANQAugBcAAkABAgYAHkAFAC5ABsPBAhjAMwFxwAwAKgEOgAhAAYOIgBPAHMAuQ09DiIAaQBlAO8G9gB5CgwFIwhBAHYORwVnAM4JDgkqACQAbAe8BSAAQgDBBlEAKQAbAbYAwQ0FAFoAIgEuANIGCwBpDscGUgApAMkODA5AAIcFSAd9CRUAHADSDtQOFwFNABgASwV9CT0ACgBdD2EFGQCLBTsA8wAwDiIAZgBGAM0FfgCaBXcOsAQUADMAmQ7nC3cA4AYmADQCDwXzCQ8ABg/iBSIAAwARAHsOfQ6QBB0BzQUNAG8AGw6jB3MACQDnBhIFcQA7DoEOggklAIUO5glTAGcAyQlyAOcAHwFPAEMGNQkcAEAAiQ4uC94KNQlHABMAYgAtAA4GPgBaANUNNQFDAAsAwQYVAFEAjg6QDrAEQwAVAMMJDgZlADQAIgCkDjUBGQAgAKwOHQ4EALAO5Qk9ASYALwA0BbYOPQELAE4AXgEtAGYOEAArDyUANwAvD3MGeABYADoPZAZzACwA9gC7AEkPHwFjAOMGxwAsAEkOZQBRDyAFGgAxAKIASAo1ATcAiw/uAPoKUgAbACAOKg5ZAAEASwX6CloAIQBmDxcBRQBbABsJ+gpJABkA/w8iAAwAMgDGBfAAbA9qANsONQkDAP4Gcw8iADUANQC1BUcANgC2DG4ABwDBBmIAVAl8DtENGABoABsB9QCxBSIABAHNBVIAYwIkACwBLgEZAK8I5gpYCmkADgCcDjUBMQALAJcPPQFVAAkAogDuAN0FDwF0AHUASwU/EEAASgBKAPcPBwFtAF4AyQnxAGwPTADPBjUJQgAYALMAlQ68BWoAVQB5BRAAEgUwAGQApA/1BGoAAAC2D0sKAQBLAEwOPAgiADgACguoBGkAcQCjDg4GMwBvALUFCABJABsJRBAAACQAwQZJAPUFaAAOBtkGyQnpAOUAHwEYAEYODglBAFEAvAlsACQAxA+yB8YPsQ49AR8AVwDMD7cOJQBVAGIGawBkBmsAfQD8AKgAfADRDU8ANAB2AOIA9Q73DnwAaADBBgwAZQDhBf0OUwBUBQEPAw8iACAAAgAA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"),getfenv())()
end)

Arsenal.Name = "Arsenal"
Arsenal.Parent = main
Arsenal.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Arsenal.BorderColor3 = Color3.fromRGB(255, 0, 0)
Arsenal.Position = UDim2.new(-0.156784058, 0, -0.043347694, 0)
Arsenal.Size = UDim2.new(0, 58, 0, 56)
Arsenal.Image = "http://www.roblox.com/asset/?id=4722910149"
Arsenal.MouseButton1Down:connect(function()
	local old
	old = hookfunction(game.HttpGetAsync, function(inst, url, state)
		url = url:gsub('CriShoux', 'SiLeNSwOrD')
		return old(inst, url, state)
	end)

	local old2
	old2 = hookfunction(game.HttpGet, function(inst, url, state)
		url = url:gsub('CriShoux', 'SiLeNSwOrD')
		return old2(inst, url, state)
	end)

	loadstring(game:HttpGet("https://raw.githubusercontent.com/SiLeNSwOrD/OwlHub/master/OwlHub.txt"))()
	-- subscribe to Tokyo Exploiter
end)
