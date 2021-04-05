-- Made By Ray

local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local title = Instance.new("TextLabel")
local Front = Instance.new("Frame")
local Close = Instance.new("TextButton")
local Gray = Instance.new("Frame")
local NullwareHub = Instance.new("TextButton")
local InfiniteYield = Instance.new("TextButton")
local MiztHub = Instance.new("TextButton")
local RagdollEngine = Instance.new("TextButton")
local FeCar = Instance.new("TextButton")
local Wings = Instance.new("TextButton")
local NetBypasser = Instance.new("TextButton")
local NullwareFix = Instance.new("TextButton")
local SmugDance = Instance.new("TextButton")
local HatFling = Instance.new("TextButton")
local SlapScript = Instance.new("TextButton")
local VrScript = Instance.new("TextButton")
local close = Instance.new("Frame")
local closebutton = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
main.Position = UDim2.new(0.0934716091, 0, 0.314741045, 0)
main.Size = UDim2.new(0, 480, 0, 279)
main.Visible = false
main.Active = true
main.Draggable = true

title.Name = "title"
title.Parent = main
title.BackgroundColor3 = Color3.fromRGB(86, 86, 86)
title.Size = UDim2.new(0, 443, 0, 26)
title.Font = Enum.Font.SpecialElite
title.Text = "Ava's Retardism v2"
title.TextColor3 = Color3.fromRGB(0, 0, 0)
title.TextScaled = true
title.TextSize = 14.000
title.TextWrapped = true

Front.Name = "Front"
Front.Parent = main
Front.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Front.Position = UDim2.new(0, 0, 0.0931899622, 0)
Front.Size = UDim2.new(0, 480, 0, 253)

Close.Name = "Close"
Close.Parent = main
Close.BackgroundColor3 = Color3.fromRGB(255, 170, 0)
Close.Position = UDim2.new(0.922916651, 0, 0, 0)
Close.Size = UDim2.new(0, 37, 0, 26)
Close.Font = Enum.Font.RobotoCondensed
Close.Text = " "
Close.TextColor3 = Color3.fromRGB(255, 0, 0)
Close.TextSize = 14.000

Gray.Name = "Gray"
Gray.Parent = main
Gray.BackgroundColor3 = Color3.fromRGB(83, 83, 83)
Gray.Position = UDim2.new(0.020833334, 0, 0.118279569, 0)
Gray.Size = UDim2.new(0, 456, 0, 237)

NullwareHub.Name = "Nullware Hub"
NullwareHub.Parent = main
NullwareHub.BackgroundColor3 = Color3.fromRGB(86, 86, 86)
NullwareHub.Position = UDim2.new(0.0458333343, 0, 0.146953404, 0)
NullwareHub.Size = UDim2.new(0, 224, 0, 22)
NullwareHub.Font = Enum.Font.SpecialElite
NullwareHub.Text = "Nullware Hub"
NullwareHub.TextColor3 = Color3.fromRGB(0, 0, 0)
NullwareHub.TextScaled = true
NullwareHub.TextSize = 10.000
NullwareHub.TextWrapped = true
NullwareHub.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://gist.githubusercontent.com/M6HqVBcddw2qaN4s/37eef2120d509b37b31fa73944ab2361/raw/kT2fVEFnzDfCRXAP"))()
end)

InfiniteYield.Name = "Infinite Yield"
InfiniteYield.Parent = main
InfiniteYield.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
InfiniteYield.Position = UDim2.new(0.539583325, 0, 0.146953404, 0)
InfiniteYield.Size = UDim2.new(0, 200, 0, 22)
InfiniteYield.Font = Enum.Font.SpecialElite
InfiniteYield.Text = "Infinite Yield"
InfiniteYield.TextColor3 = Color3.fromRGB(0, 0, 0)
InfiniteYield.TextScaled = true
InfiniteYield.TextSize = 14.000
InfiniteYield.TextWrapped = true
InfiniteYield.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)

MiztHub.Name = "Mizt Hub"
MiztHub.Parent = main
MiztHub.BackgroundColor3 = Color3.fromRGB(86, 86, 86)
MiztHub.Position = UDim2.new(0.0458333343, 0, 0.279569894, 0)
MiztHub.Size = UDim2.new(0, 224, 0, 25)
MiztHub.Font = Enum.Font.SpecialElite
MiztHub.Text = "Mizt Hub"
MiztHub.TextColor3 = Color3.fromRGB(0, 0, 0)
MiztHub.TextScaled = true
MiztHub.TextSize = 14.000
MiztHub.TextWrapped = true
MiztHub.MouseButton1Down:connect(function()
	_G.HalfNet = true -- Just make it true
	_G.CustomGui = false -- if you have custom gui turn this on, put the custom gui script below this loadstring
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Sylixe/MiztHub/master/MainFolder/uqXAxyVdQpWTcRCdFXU6Yt2meuDkYcLUDN4SJRekQWZ5wp368zKHreYT4w82AH4U.lua",true))()
end)

RagdollEngine.Name = "Ragdoll Engine"
RagdollEngine.Parent = main
RagdollEngine.BackgroundColor3 = Color3.fromRGB(97, 97, 97)
RagdollEngine.Position = UDim2.new(0.539583325, 0, 0.279569894, 0)
RagdollEngine.Size = UDim2.new(0, 200, 0, 25)
RagdollEngine.Font = Enum.Font.SpecialElite
RagdollEngine.Text = "Ragdoll Engine VYNIXIUS"
RagdollEngine.TextColor3 = Color3.fromRGB(0, 0, 0)
RagdollEngine.TextSize = 14.000
RagdollEngine.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Scripts/master/Vynixius%20Ragdoll%20Engine"))()
end)

FeCar.Name = "Fe Car"
FeCar.Parent = main
FeCar.BackgroundColor3 = Color3.fromRGB(103, 103, 103)
FeCar.Position = UDim2.new(0.0458333343, 0, 0.408602148, 0)
FeCar.Size = UDim2.new(0, 224, 0, 26)
FeCar.Font = Enum.Font.SpecialElite
FeCar.Text = "Fe Car"
FeCar.TextColor3 = Color3.fromRGB(0, 0, 0)
FeCar.TextScaled = true
FeCar.TextSize = 14.000
FeCar.TextWrapped = true
FeCar.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/MonkoTubeYT/carscript/master/!carscript.lua',true))()
end)

Wings.Name = "Wings"
Wings.Parent = main
Wings.BackgroundColor3 = Color3.fromRGB(121, 121, 121)
Wings.Position = UDim2.new(0.539583325, 0, 0.408602148, 0)
Wings.Size = UDim2.new(0, 200, 0, 26)
Wings.Font = Enum.Font.SpecialElite
Wings.Text = "Wings (NotFe)"
Wings.TextColor3 = Color3.fromRGB(0, 0, 0)
Wings.TextScaled = true
Wings.TextSize = 14.000
Wings.TextWrapped = true
Wings.MouseButton1Down:connect(function()
	--[[ To fly jump 2 times -ulti55]]
	--[[ To go down press q ]]

	script.Parent = nil

	function fly()

		for i,v in pairs(script:GetChildren()) do

			pcall(function() v.Value = "" end)

			game:GetService("Debris"):AddItem(v,.1)

		end

		function weld(p0,p1,c0,c1,par)

			local w = Instance.new("Weld",p0 or par)

			w.Part0 = p0

			w.Part1 = p1

			w.C0 = c0 or CFrame.new()

			w.C1 = c1 or CFrame.new()

			return w

		end

		local motors = {}

		function motor(p0,p1,c0,c1,des,vel,par)

			local w = Instance.new("Motor6D",p0 or par)

			w.Part0 = p0

			w.Part1 = p1

			w.C0 = c0 or CFrame.new()

			w.C1 = c1 or CFrame.new()

			w.MaxVelocity = tonumber(vel) or .05

			w.DesiredAngle = tonumber(des) or 0

			return w

		end

		function lerp(a,b,c)

			return a+(b-a)*c

		end

		function clerp(c1,c2,al)

			local com1 = {c1.X,c1.Y,c1.Z,c1:toEulerAnglesXYZ()}

			local com2 = {c2.X,c2.Y,c2.Z,c2:toEulerAnglesXYZ()}

			for i,v in pairs(com1) do

				com1[i] = lerp(v,com2[i],al)

			end

			return CFrame.new(com1[1],com1[2],com1[3]) * CFrame.Angles(select(4,unpack(com1)))

		end

		function ccomplerp(c1,c2,al)

			local com1 = {c1:components()}

			local com2 = {c2:components()}

			for i,v in pairs(com1) do

				com1[i] = lerp(v,com2[i],al)

			end

			return CFrame.new(unpack(com1))

		end

		function tickwave(time,length,offset)

			return (math.abs((tick()+(offset or 0))%time-time/2)*2-time/2)/time/2*length

		end

		function invcol(c)

			c = c.Color

			return BrickColor.new(Color3.new(1-c.b,1-c.g,1-c.r))

		end

		local oc = oc or function(...) return ... end

		local plr = game.Players.LocalPlayer

		local char = plr.Character

		local tor = char.Torso

		local hum = char.Humanoid

		hum.PlatformStand = false

		pcall(function()

			char.Wings:Destroy()

		end)

		pcall(function()

			char.Angel:Destroy() -- hat

		end)

		local mod = Instance.new("Model",char)

		mod.Name = "Wings"

		local special = {

			--antiboomz0r = {"Really black","Institutional white",0,0,false,Color3.new(1,1,.95),Color3.new(1,1,.6)},

			antiboomz0r = {"New Yeller",nil,0.4,0.7,true,Color3.new(1,1,.95),Color3.new(1,1,.6)},

			--antiboomz0r = {"Cyan","Toothpaste",0,0,false,Color3.new(1,0,0),Color3.new(0,0,0)},

			taart = {"Royal purple",nil,.4,.4,true},

			mitta = {"Black",nil,0,0,false},

			penjuin3 = {"White",nil,0,0,false},

			thepc8110 = {"Black","Bright red",.5,0,false,Color3.new(1,0,0),Color3.new(0,0,0)},

			nonspeaker = {"Cyan","Toothpaste",0,0,false,Color3.new(1,0,0),Color3.new(0,0,0)},

			littleau999 = {"Reddish brown",1030,0,0,false},

			unscripter = {"Really black","Really black",.2,0,true,Color3.new(0,0,0),Color3.new(0,0,0)},

			oxcool1 = {"Really black","White",.2,0,false,Color3.new(0,0,0),Color3.new(0,0,0)},

			krodmiss = {"Really black",nil,0,0,false},

		}

		local topcolor = invcol(char.Torso.BrickColor)

		local feacolor = char.Torso.BrickColor

		local ptrans = 0

		local pref = 0

		local fire = false

		local fmcol = Color3.new()

		local fscol = Color3.new()

		local spec = special[plr.Name:lower()]

		if spec then

			topcolor,feacolor,ptrans,pref,fire,fmcol,fscol = spec[1] and BrickColor.new(spec[1]) or topcolor,spec[2] and BrickColor.new(spec[2]) or feacolor,spec[3],spec[4],spec[5],spec[6],spec[7]

		end

		local part = Instance.new("Part")

		part.FormFactor = "Custom"

		part.Size = Vector3.new(.2,.2,.2)

		part.TopSurface,part.BottomSurface = 0,0

		part.CanCollide = false

		part.BrickColor = topcolor

		part.Transparency = ptrans

		part.Reflectance = pref

		local ef = Instance.new("Fire",fire and part or nil)

		ef.Size = .15

		ef.Color = fmcol or Color3.new()

		ef.SecondaryColor = fscol or Color3.new()

		part:BreakJoints()


		function newpart()

			local clone = part:Clone()

			clone.Parent = mod

			clone:BreakJoints()

			return clone

		end

		local feath = newpart()

		feath.BrickColor = feacolor

		feath.Transparency = 0

		Instance.new("SpecialMesh",feath).MeshType = "Sphere"

		function newfeather()

			local clone = feath:Clone()

			clone.Parent = mod

			clone:BreakJoints()

			return clone

		end


		---------- RIGHT WING

		local r1 = newpart()

		r1.Size = Vector3.new(.3,1.5,.3)*1.2

		local rm1 = motor(tor,r1,CFrame.new(.35,.6,.4) * CFrame.Angles(0,0,math.rad(-60)) * CFrame.Angles(math.rad(30),math.rad(-25),0),CFrame.new(0,-.8,0),.1)

		local r2 = newpart()

		r2.Size = Vector3.new(.4,1.8,.4)*1.2

		local rm2 = motor(r1,r2,CFrame.new(0,.75,0) * CFrame.Angles(0,0,math.rad(50)) * CFrame.Angles(math.rad(-30),math.rad(15),0),CFrame.new(0,-.9,0),.1)

		local r3 = newpart()

		r3.Size = Vector3.new(.3,2.2,.3)*1.2

		local rm3 = motor(r2,r3,CFrame.new(.1,.9,0) * CFrame.Angles(0,0,math.rad(-140)) * CFrame.Angles(math.rad(-3),0,0),CFrame.new(0,-1.1,0),.1)

		local r4 = newpart()

		r4.Size = Vector3.new(.25,1.2,.25)*1.2

		local rm4 = motor(r3,r4,CFrame.new(0,1.1,0) * CFrame.Angles(0,0,math.rad(-10)) * CFrame.Angles(math.rad(-3),0,0),CFrame.new(0,-.6,0),.1)

		local feather = newfeather()

		feather.Mesh.Scale = Vector3.new(1,1,1)

		feather.Size = Vector3.new(.4,3,.3)

		weld(r4,feather,CFrame.new(-.1,-.3,0),CFrame.new(0,-1.5,0))

		feather = newfeather()

		feather.Mesh.Scale = Vector3.new(1,1,1)

		feather.Size = Vector3.new(.4,2.3,.3)

		weld(r4,feather,CFrame.new(.1,-.1,0) * CFrame.Angles(0,math.random()*.1,0),CFrame.new(0,-1.1,0))

		feather = newfeather()

		feather.Mesh.Scale = Vector3.new(1,1,1)

		feather.Size = Vector3.new(.35,2.2,.25)

		weld(r4,feather,CFrame.new(.1,-.3,0) * CFrame.Angles(0,math.random()*.1,math.rad(-10)),CFrame.new(0,-1.1,0))

		local rf3 = {}

		for i=0,7 do

			feather = newfeather()

			feather.Mesh.Scale = Vector3.new(1,1,1)

			feather.Size = Vector3.new(.45,2.2,.35)

			table.insert(rf3,motor(r3,feather,CFrame.new(.05,1-i*.285,0) * CFrame.Angles(0,math.random()*.1,math.rad(-25-i*2)),CFrame.new(0,-feather.Size.Y/2,0)))

		end

		local rf2 = {}

		for i=0,6 do

			feather = newfeather()

			feather.Mesh.Scale = Vector3.new(1,1,1)

			feather.Size = Vector3.new(.45,2.2-i*.08,.3)

			table.insert(rf2,motor(r2,feather,CFrame.new(.05,.75-i*.26,0) * CFrame.Angles(0,math.random()*.1,math.rad(-75-i*4)),CFrame.new(0,-feather.Size.Y/2,0)))

		end

		local rf1 = {}

		for i=0,6 do

			feather = newfeather()

			feather.Mesh.Scale = Vector3.new(1,1,1)

			feather.Size = Vector3.new(.37,1.65-i*.06,.25)

			table.insert(rf1,motor(r1,feather,CFrame.new(.05,.63-i*.21,0) * CFrame.Angles(0,math.random()*.05,math.rad(-75)),CFrame.new(0,-feather.Size.Y/2,0)))

		end

		---------- LEFT WING

		local l1 = newpart()

		l1.Size = Vector3.new(.3,1.5,.3)*1.2

		local lm1 = motor(tor,l1,CFrame.new(-.35,.6,.4) * CFrame.Angles(0,0,math.rad(60)) * CFrame.Angles(math.rad(30),math.rad(25),0) * CFrame.Angles(0,-math.pi,0),CFrame.new(0,-.8,0) ,.1)

		local l2 = newpart()

		l2.Size = Vector3.new(.4,1.8,.4)*1.2

		local lm2 = motor(l1,l2,CFrame.new(0,.75,0) * CFrame.Angles(0,0,math.rad(50)) * CFrame.Angles(math.rad(30),math.rad(-15),0),CFrame.new(0,-.9,0),.1)

		local l3 = newpart()

		l3.Size = Vector3.new(.3,2.2,.3)*1.2

		local lm3 = motor(l2,l3,CFrame.new(.1,.9,0) * CFrame.Angles(0,0,math.rad(-140)) * CFrame.Angles(math.rad(3),0,0),CFrame.new(0,-1.1,0),.1)

		local l4 = newpart()

		l4.Size = Vector3.new(.25,1.2,.25)*1.2

		local lm4 = motor(l3,l4,CFrame.new(0,1.1,0) * CFrame.Angles(0,0,math.rad(-10)) * CFrame.Angles(math.rad(3),0,0),CFrame.new(0,-.6,0),.1)

		local feather = newfeather()

		feather.Mesh.Scale = Vector3.new(1,1,1)

		feather.Size = Vector3.new(.4,3,.3)

		weld(l4,feather,CFrame.new(-.1,-.3,0),CFrame.new(0,-1.5,0))

		feather = newfeather()

		feather.Mesh.Scale = Vector3.new(1,1,1)

		feather.Size = Vector3.new(.4,2.3,.3)

		weld(l4,feather,CFrame.new(.1,-.1,0) * CFrame.Angles(0,math.random()*.1,0),CFrame.new(0,-1.1,0))

		feather = newfeather()

		feather.Mesh.Scale = Vector3.new(1,1,1)

		feather.Size = Vector3.new(.35,2.2,.25)

		weld(l4,feather,CFrame.new(.1,-.3,0) * CFrame.Angles(0,math.random()*.1,math.rad(-10)),CFrame.new(0,-1.1,0))

		local lf3 = {}

		for i=0,7 do

			feather = newfeather()

			feather.Mesh.Scale = Vector3.new(1,1,1)

			feather.Size = Vector3.new(.45,2.2,.35)

			table.insert(lf3,motor(l3,feather,CFrame.new(.05,1-i*.285,0) * CFrame.Angles(0,math.random()*.1,math.rad(-25-i*2)),CFrame.new(0,-feather.Size.Y/2,0)))

		end

		local lf2 = {}

		for i=0,6 do

			feather = newfeather()

			feather.Mesh.Scale = Vector3.new(1,1,1)

			feather.Size = Vector3.new(.45,2.2-i*.08,.3)

			table.insert(lf2,motor(l2,feather,CFrame.new(.05,.75-i*.26,0) * CFrame.Angles(0,math.random()*.1,math.rad(-75-i*4)),CFrame.new(0,-feather.Size.Y/2,0)))

		end

		local lf1 = {}

		for i=0,6 do

			feather = newfeather()

			feather.Mesh.Scale = Vector3.new(1,1,1)

			feather.Size = Vector3.new(.37,1.65-i*.06,.25)

			table.insert(lf1,motor(l1,feather,CFrame.new(.05,.63-i*.21,0) * CFrame.Angles(0,math.random()*.05,math.rad(-75)),CFrame.new(0,-feather.Size.Y/2,0)))

		end

		local rwing = {rm1,rm2,rm3,rm4}

		local lwing = {lm1,lm2,lm3,lm4}

		local oc0 = {}

		for i,v in pairs(rwing) do

			oc0[v] = v.C0

		end

		for i,v in pairs(lwing) do

			oc0[v] = v.C0

		end

		function gotResized()

			if lastsize then

				if tor.Size == lastsize then return end -- This shouldn't happen?

				local scaleVec = tor.Size/lastsize

				for i,v in pairs(oc0) do

					oc0[i] = v-v.p+scaleVec*v.p

				end

				lastsize = tor.Size

			end

			lastsize = tor.Size

		end

		tor.Changed:connect(function(p)

			if p == "Size" then

				gotResized()

			end

		end)

		gotResized()

		local idle = {0,0.5,-.2,0; .05,.05,.1,.05; -.6,-1.5,.1,0;}--0,.3,0,0

		local outlow = {-.7,-.2,1.8,0; .3,.05,.1,.05; .2,0,0,0}

		local outhigh = {.5,-.2,1.8,0; .3,.05,.1,.05; .2,0,0,0}

		local veryhigh = {.9,-.3,1.9,0; .3,.05,.1,.05; .2,0,0,0}

		local flap1 = {-.3,.3,1.1,-.2; .3,.05,.1,.05; .2,-.6,0,0}

		local divebomb = {0,.2,.4,-.7; .3,.05,.1,.05; 0,-.5,-.6,0}


		function setwings(tab,time)

			time = time or 10

			for i=1,4 do

				rwing[i].DesiredAngle = tab[i]

				lwing[i].DesiredAngle = tab[i]

				rwing[i].MaxVelocity = math.abs(tab[i]-rwing[i].CurrentAngle)/time

				lwing[i].MaxVelocity = math.abs(tab[i]-lwing[i].CurrentAngle)/time

				local rcf = oc0[rwing[i]] * (tab[12+i] or CFrame.new())

				local lcf = oc0[lwing[i]] * (tab[12+i] or CFrame.new())

			end

			for i,v in pairs(rf1) do

				v.DesiredAngle = tab[9]

				v.MaxVelocity = math.abs(v.DesiredAngle-v.CurrentAngle)/time

			end

			for i,v in pairs(lf1) do

				v.DesiredAngle = tab[9]

				v.MaxVelocity = math.abs(v.DesiredAngle-v.CurrentAngle)/time

			end

			for i,v in pairs(rf2) do

				v.DesiredAngle = tab[10]

				v.MaxVelocity = math.abs(v.DesiredAngle-v.CurrentAngle)/time

			end

			for i,v in pairs(lf2) do

				v.DesiredAngle = tab[10]

				v.MaxVelocity = math.abs(v.DesiredAngle-v.CurrentAngle)/time

			end

			for i,v in pairs(rf3) do

				v.DesiredAngle = tab[11]

				v.MaxVelocity = math.abs(v.DesiredAngle-v.CurrentAngle)/time

			end

			for i,v in pairs(lf3) do

				v.DesiredAngle = tab[11]

				v.MaxVelocity = math.abs(v.DesiredAngle-v.CurrentAngle)/time

			end

		end

		setwings(outhigh,1)

		flying = false

		moving = false

		for i,v in pairs(tor:GetChildren()) do

			if v.ClassName:lower():match("body") then

				v:Destroy()

			end

		end

		local ctor = tor:Clone()

		ctor:ClearAllChildren()

		ctor.Name = "cTorso"

		ctor.Transparency = 1

		ctor.CanCollide = false

		ctor.FormFactor = "Custom"

		ctor.Size = Vector3.new(.2,.2,.2)

		ctor.Parent = mod

		weld(tor,ctor)

		local bg = Instance.new("BodyGyro",ctor)

		bg.maxTorque = Vector3.new()

		bg.P = 15000

		bg.D = 1000

		local bv = Instance.new("BodyVelocity",ctor)

		bv.maxForce = Vector3.new()

		bv.P = 15000

		vel = Vector3.new()

		cf = CFrame.new()

		flspd = 0


		keysdown = {}

		keypressed = {}

		ktime = {}

		descendtimer = 0

		jumptime = tick()

		hum.Jumping:connect(function()

			jumptime = tick()

		end)

		cam = workspace.CurrentCamera

		kd = plr:GetMouse().KeyDown:connect(oc(function(key) 

			keysdown[key] = true 

			keypressed[key] = true 

			if key == "q" then 

				descendtimer = tick() 

			elseif key == " " and not hum.Jump then 

				jumptime = tick()

			elseif (key == "a" or key == "d") and ktime[key] and tick()-ktime[key] < .3 and math.abs(reqrotx) < .3 then

				reqrotx = key == "a" and math.pi*2 or -math.pi*2

			end

			ktime[key] = tick() 

		end))

		ku = plr:GetMouse().KeyUp:connect(function(key) 

			keysdown[key] = false 

			if key == " " then 

				descendtimer = tick() 

			end 

		end)

		function mid(a,b,c)

			return math.max(a,math.min(b,c or -a))

		end

		function bn(a)

			return a and 1 or 0

		end

		function gm(tar)

			local m = 0

			for i,v in pairs(tar:GetChildren()) do

				if v:IsA("BasePart") then

					m = m + v:GetMass()

				end

				m = m + gm(v)

			end

			return m

		end

		reqrotx = 0

		local grav = 196.2

		local con

		con = game:GetService("RunService").Stepped:connect(oc(function()

--[[if not mod:IsDescendantOf(workspace) then

pcall(function() kd:disconnect() end)

pcall(function() ku:disconnect() end)

bg:Destroy()

bv:Destroy()

con:disconnect()

script:Destroy()

return

end]]

			local obvel = tor.CFrame:vectorToObjectSpace(tor.Velocity)

			local sspd, uspd,fspd = obvel.X,obvel.Y,obvel.Z

			if flying then

				local lfldir = fldir

				fldir = cam.CoordinateFrame:vectorToWorldSpace(Vector3.new(bn(keysdown.d)-bn(keysdown.a),0,bn(keysdown.s)-bn(keysdown.w))).unit

				local lmoving = moving

				moving = fldir.magnitude > .1

				if lmoving and not moving then

					idledir = lfldir*Vector3.new(1,0,1)

					descendtimer = tick()

				end

				local dbomb = fldir.Y < -.6 or (moving and keysdown["1"])

				if moving and keysdown["0"] and lmoving then

					fldir = (Vector3.new(lfldir.X,math.min(fldir.Y,lfldir.Y+.01)-.1,lfldir.Z)+(fldir*Vector3.new(1,0,1))*.05).unit

				end

				local down = tor.CFrame:vectorToWorldSpace(Vector3.new(0,-1,0))

				local descending = (not moving and keysdown["q"] and not keysdown[" "])

				cf = ccomplerp(cf,CFrame.new(tor.Position,tor.Position+(not moving and idledir or fldir)),keysdown["0"] and .02 or .07)

				local gdown = not dbomb and cf.lookVector.Y < -.2 and tor.Velocity.unit.Y < .05

				hum.PlatformStand = true

				bg.maxTorque = Vector3.new(1,1,1)*9e5

				local rotvel = CFrame.new(Vector3.new(),tor.Velocity):toObjectSpace(CFrame.new(Vector3.new(),fldir)).lookVector

				bg.cframe = cf * CFrame.Angles(not moving and -.1 or -math.pi/2+.2,moving and mid(-2.5,rotvel.X/1.5) + reqrotx or 0,0)

				reqrotx = reqrotx - reqrotx/10

				bv.maxForce = Vector3.new(1,1,1)*9e4*.5

				local anioff =(bn(keysdown[" "])-bn(keysdown["q"]))/2

				local ani = tickwave(1.5-anioff,1)

				bv.velocity = bv.velocity:Lerp(Vector3.new(0,bn(not moving)*-ani*15+(descending and math.min(20,tick()-descendtimer)*-8 or bn(keysdown[" "])-bn(keysdown["q"]))*15,0)+vel,.6) 

				vel = moving and cf.lookVector*flspd or Vector3.new()

				flspd = math.min(120,lerp(flspd,moving and (fldir.Y<0 and flspd+(-fldir.Y)*grav/60 or math.max(50,flspd-fldir.Y*grav/300)) or 60,.4))

				setwings(moving and (gdown and outlow or dbomb and divebomb) or (descending and veryhigh or flap1),15)

				for i=1,4 do

					--CFrame.Angles(-.5+bn(i==3)*2.4+bn(i==4)*.5,.1+bn(i==2)*.5-bn(i==3)*1.1,bn(i==3)*.1)

					rwing[i].C0 = clerp(rwing[i].C0,oc0[rwing[i]] * (gdown and CFrame.new() or dbomb and CFrame.Angles(-.5+bn(i==3)*.4+bn(i==4)*.5,.1+bn(i==2)*.5-bn(i==3)*1.1,bn(i==3)*.1) or descending and CFrame.Angles(.3,0,0) or CFrame.Angles((i*.1+1.5)*ani,ani*-.5,1*ani)),descending and .8 or .2)

					lwing[i].C0 = clerp(lwing[i].C0,oc0[lwing[i]] * (gdown and CFrame.new() or dbomb and CFrame.Angles(-(-.5+bn(i==3)*.4+bn(i==4)*.5),-(.1+bn(i==2)*.5-bn(i==3)*1.1),bn(i==3)*.1) or descending and CFrame.Angles(-.3,0,0) or CFrame.Angles(-(i*.1+1.5)*ani,ani*.5,1*ani)),descending and .8 or .2)

				end

				local hit,ray = workspace:FindPartOnRayWithIgnoreList(Ray.new(tor.Position,Vector3.new(0,-3.5+math.min(0,bv.velocity.y)/30,0)),{char})

				if hit and down.Y < -.85 and tick()-flystart > 1 then

					flying = false

					hum.PlatformStand = false

					tor.Velocity = Vector3.new()

				end

			else

				bg.maxTorque = Vector3.new()

				bv.maxForce = Vector3.new()

				local ani = tickwave(walking and .8 or 4.5,1)

				setwings(idle,10)

				local x,y,z = fspd/160,uspd/700,sspd/900

				for i=1,4 do

					rwing[i].C0 = clerp(rwing[i].C0,oc0[rwing[i]] * CFrame.Angles(ani*.1 + -mid(-.1,x),0 + -mid(-.1,y) + bn(i==2)*.6,ani*.02 + -mid(-.1,z)),.2)

					lwing[i].C0 = clerp(lwing[i].C0,oc0[lwing[i]] * CFrame.Angles(ani*-.05 + mid(-.1,x),0 + mid(-.1,y) + -bn(i==2)*.6,ani*.02 + mid(-.1,z)),.2)

				end

				if keypressed[" "] and not flying and (tick()-jumptime > .05 and (tick()-jumptime < 3 or hum.Jump)) then

					vel = Vector3.new(0,50,0)

					bv.velocity = vel

					idledir = cam.CoordinateFrame.lookVector*Vector3.new(1,0,1)

					cf = tor.CFrame * CFrame.Angles(-.01,0,0)

					tor.CFrame = cf

					bg.cframe = cf

					flystart = tick()

					flying = true

				end

			end

			keypressed = {}

		end))



	end fly()

	--Bird Wings By Rosemarijohn2
end)

NetBypasser.Name = "Net Bypasser"
NetBypasser.Parent = main
NetBypasser.BackgroundColor3 = Color3.fromRGB(108, 108, 108)
NetBypasser.Position = UDim2.new(0.0458333343, 0, 0.544802845, 0)
NetBypasser.Size = UDim2.new(0, 224, 0, 21)
NetBypasser.Font = Enum.Font.SpecialElite
NetBypasser.Text = "Net Bypasser"
NetBypasser.TextColor3 = Color3.fromRGB(0, 0, 0)
NetBypasser.TextScaled = true
NetBypasser.TextSize = 14.000
NetBypasser.TextWrapped = true
NetBypasser.MouseButton1Down:connect(function()
	print(gethiddenproperty(game:GetService("Players").LocalPlayer, "SimulationRadius"))
end)

NullwareFix.Name = "NullwareFix"
NullwareFix.Parent = main
NullwareFix.BackgroundColor3 = Color3.fromRGB(115, 115, 115)
NullwareFix.Position = UDim2.new(0.539583325, 0, 0.544802845, 0)
NullwareFix.Size = UDim2.new(0, 200, 0, 21)
NullwareFix.Font = Enum.Font.SpecialElite
NullwareFix.Text = "Nullware Reanimation Fix"
NullwareFix.TextColor3 = Color3.fromRGB(0, 0, 0)
NullwareFix.TextSize = 12.000
NullwareFix.MouseButton1Down:connect(function()
	_G.reanimated = false
	_G.ranscript = false
	_G.MSG.Text = ""
end)

SmugDance.Name = "Smug Dance"
SmugDance.Parent = main
SmugDance.BackgroundColor3 = Color3.fromRGB(120, 120, 120)
SmugDance.Position = UDim2.new(0.0458333343, 0, 0.670250893, 0)
SmugDance.Size = UDim2.new(0, 224, 0, 26)
SmugDance.Font = Enum.Font.SpecialElite
SmugDance.Text = "Smug Dance FE"
SmugDance.TextColor3 = Color3.fromRGB(0, 0, 0)
SmugDance.TextScaled = true
SmugDance.TextSize = 14.000
SmugDance.TextWrapped = true
SmugDance.MouseButton1Down:connect(function()
	ArtificialHB = Instance.new("BindableEvent", script)
	ArtificialHB.Name = "Heartbeat"
	script:WaitForChild("Heartbeat")

	Player = game:GetService("Players").LocalPlayer
	PlayerGui = Player.PlayerGui
	Cam = workspace.CurrentCamera
	Backpack = Player.Backpack
	Character = Player.Character
	Humanoid = Character.Humanoid
	Mouse = Player:GetMouse()
	RootPart = Character["HumanoidRootPart"]
	Torso = Character["Torso"]
	Head = Character["Head"]
	RightArm = Character["Right Arm"]
	LeftArm = Character["Left Arm"]
	RightLeg = Character["Right Leg"]
	LeftLeg = Character["Left Leg"]
	RootJoint = RootPart["RootJoint"]
	Neck = Torso["Neck"]
	RightShoulder = Torso["Right Shoulder"]
	LeftShoulder = Torso["Left Shoulder"]
	RightHip = Torso["Right Hip"]
	LeftHip = Torso["Left Hip"]

	Character = Player.Character
	Humanoid = Character.Humanoid

	local BODY = {}
	for _, c in pairs(Character:GetDescendants()) do
		if c:IsA("BasePart") and c.Name ~= "Handle" then
			if c ~= RootPart and c ~= Torso and c ~= Head and c ~= RightArm and c ~= LeftArm and c ~= RightLeg and c ~= LeftLeg then
				c.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0, 0, 0)
			end
			table.insert(BODY,{c,c.Parent,c.Material,c.Color,c.Transparency,c.Size,c.Name})
		elseif c:IsA("JointInstance") then
			table.insert(BODY,{c,c.Parent,nil,nil,nil,nil,nil})
		end
	end

	function refit()
		Character.Parent = workspace
		for e = 1, #BODY do
			if BODY[e] ~= nil then
				local STUFF = BODY[e]
				local PART = STUFF[1]
				local PARENT = STUFF[2]
				local MATERIAL = STUFF[3]
				local COLOR = STUFF[4]
				local TRANSPARENCY = STUFF[5]
				--local SIZE = STUFF[6]
				local NAME = STUFF[7]
				if PART.ClassName == "Part" and PART ~= RootPart then
					PART.Material = MATERIAL
					PART.Transparency = TRANSPARENCY
					PART.Name = NAME
				end
				if PART.Parent ~= PARENT then
					Humanoid:remove()
					PART.Parent = PARENT
					Humanoid = IT("Humanoid",Character)
				end
			end
		end
	end

	Humanoid.Died:connect(function()
		refit()
	end)

	Player = game:GetService("Players").LocalPlayer
	PlayerGui = Player.PlayerGui
	Cam = workspace.CurrentCamera
	Backpack = Player.Backpack
	Character = Player.Character
	Humanoid = Character.Humanoid
	Mouse = Player:GetMouse()
	RootPart = Character["HumanoidRootPart"]
	Torso = Character["Torso"]
	Head = Character["Head"]
	RightArm = Character["Right Arm"]
	LeftArm = Character["Left Arm"]
	RightLeg = Character["Right Leg"]
	LeftLeg = Character["Left Leg"]
	RootJoint = RootPart["RootJoint"]
	Neck = Torso["Neck"]
	RightShoulder = Torso["Right Shoulder"]
	LeftShoulder = Torso["Left Shoulder"]
	RightHip = Torso["Right Hip"]
	LeftHip = Torso["Left Hip"]
	local sick = Instance.new("Sound",Torso)

	IT = Instance.new
	CF = CFrame.new
	VT = Vector3.new
	RAD = math.rad
	C3 = Color3.new
	UD2 = UDim2.new
	BRICKC = BrickColor.new
	ANGLES = CFrame.Angles
	EULER = CFrame.fromEulerAnglesXYZ
	COS = math.cos
	ACOS = math.acos
	SIN = math.sin
	ASIN = math.asin
	ABS = math.abs
	MRANDOM = math.random
	FLOOR = math.floor

	local Speed = 0.1
	AnimationSpeed=.8
	SmoothTime=2

	function swait(num)
		if num==0 or num==nil then
			--if Stagger.Value==false or Stun.Value<=100 then
			--Player.PlayerGui.Pacemaker.Heartbeat.Event:wait()
			script.Heartbeat.Event:wait()
			--end
		else
			for i=0,num do
				--Player.PlayerGui.Pacemaker.Heartbeat.Event:wait()
				script.Heartbeat.Event:wait()
--[[if Stagger.Value==true or Stun.Value>=StunT.Value then
break
end]]
			end
		end
	end
	script:WaitForChild("Heartbeat")

	frame = 1/60
	tf = 0
	allowframeloss = false --if set to true will fire every frame it possibly can. This will result in multiple events happening at the same time whenever delta returns frame2 or greater.
	tossremainder = false --if set to true t will be set to 0 after Fire()-ing.
	lastframe = tick()
	script.Heartbeat:Fire() --ayy lmao

	game:GetService("RunService").Heartbeat:connect(function(s,p) --herp derp
		tf = tf + s
		if tf >= frame then
			if allowframeloss then
				script.Heartbeat:Fire()
				lastframe=tick()
			else
				----print("FIRED "..math.floor(t/frame).." FRAME(S)","REMAINDER "..(t - frame(math.floor(t/frame))))
				for i=1, math.floor(tf/frame) do
					script.Heartbeat:Fire()
				end
				lastframe=tick()
			end
			if tossremainder then
				tf = 0
			else
				tf = tf - frame * math.floor(tf/frame)
			end
		end
	end)

	Anim = {  	Properties = {
		Looping = true,
		Priority = Enum.AnimationPriority.Action
	},
	Keyframes = {
		[0] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.Angles(math.rad(-10.657), 0, 0),
					["Left Leg"] = {
						CFrame = CFrame.Angles(math.rad(-5.214), math.rad(-0.859), math.rad(9.397)),
					},
					["Right Arm"] = {
						CFrame = CFrame.Angles(0, 0, math.rad(169.767)),
					},
					["Left Arm"] = {
						CFrame = CFrame.Angles(0, 0, math.rad(-169.767)),
					},
					["Right Leg"] = {
						CFrame = CFrame.Angles(math.rad(-4.526), math.rad(0.745), math.rad(-9.454)),
					},
				},
			},
		},
		[0.017] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.001, -0.003) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-0.115)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.003, 0.003, 0) * CFrame.Angles(math.rad(-5.271), math.rad(-0.745), math.rad(9.397)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.002, -0.001, -0.001) * CFrame.Angles(math.rad(0.63), math.rad(-0.458), math.rad(169.08)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.003, -0.01, -0.001) * CFrame.Angles(math.rad(-0.573), math.rad(-0.516), math.rad(-169.137)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.001, 0.003, 0.001) * CFrame.Angles(math.rad(-4.526), math.rad(0.516), math.rad(-9.454)),
					},
				},
			},
		},
		[0.033] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.003, -0.014) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-0.516)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.011, 0.012, 0.002) * CFrame.Angles(math.rad(-5.386), math.rad(-0.286), math.rad(9.339)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.008, -0.003, -0.004) * CFrame.Angles(math.rad(2.464), math.rad(-1.948), math.rad(167.132)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.012, -0.039, -0.004) * CFrame.Angles(math.rad(-2.349), math.rad(-2.005), math.rad(-167.189)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.004, 0.013, 0.003) * CFrame.Angles(math.rad(-4.641), math.rad(-0.229), math.rad(-9.454)),
					},
				},
			},
		},
		[0.05] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.006, -0.031) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-1.089)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.024, 0.027, 0.004) * CFrame.Angles(math.rad(-5.615), math.rad(0.458), math.rad(9.225)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.016, -0.005, -0.008) * CFrame.Angles(math.rad(5.386), math.rad(-4.469), math.rad(163.866)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.026, -0.084, -0.006) * CFrame.Angles(math.rad(-5.214), math.rad(-4.641), math.rad(-164.095)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.009, 0.028, 0.006) * CFrame.Angles(math.rad(-4.756), math.rad(-1.432), math.rad(-9.454)),
					},
				},
			},
		},
		[0.067] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.011, -0.056) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-1.948)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.043, 0.047, 0.007) * CFrame.Angles(math.rad(-5.959), math.rad(1.432), math.rad(9.11)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.021, -0.004, -0.011) * CFrame.Angles(math.rad(9.282), math.rad(-8.308), math.rad(159.569)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.044, -0.139, -0.004) * CFrame.Angles(math.rad(-8.938), math.rad(-8.537), math.rad(-159.913)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.016, 0.05, 0.01) * CFrame.Angles(math.rad(-4.927), math.rad(-3.094), math.rad(-9.511)),
					},
				},
			},
		},
		[0.083] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.016, -0.087) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-3.094)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.068, 0.074, 0.01) * CFrame.Angles(math.rad(-6.36), math.rad(2.75), math.rad(8.881)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.018, -0.001, -0.007) * CFrame.Angles(math.rad(13.923), math.rad(-13.694), math.rad(154.355)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.065, -0.196, 0.005) * CFrame.Angles(math.rad(-13.35), math.rad(-13.98), math.rad(-154.928)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.025, 0.078, 0.015) * CFrame.Angles(math.rad(-5.157), math.rad(-5.271), math.rad(-9.568)),
					},
				},
			},
		},
		[0.1] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.024, -0.126) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-4.412)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.098, 0.106, 0.014) * CFrame.Angles(math.rad(-6.875), math.rad(4.354), math.rad(8.709)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.001, 0.007, 0.007) * CFrame.Angles(math.rad(19.022), math.rad(-20.684), math.rad(148.396)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.081, -0.245, 0.024) * CFrame.Angles(math.rad(-18.277), math.rad(-21.028), math.rad(-149.198)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.035, 0.113, 0.019) * CFrame.Angles(math.rad(-5.443), math.rad(-7.964), math.rad(-9.626)),
					},
				},
			},
		},
		[0.117] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.032, -0.171) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-6.016)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.134, 0.144, 0.017) * CFrame.Angles(math.rad(-7.448), math.rad(6.188), math.rad(8.48)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.038, 0.015, 0.042) * CFrame.Angles(math.rad(24.408), math.rad(-29.622), math.rad(141.864)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.083, -0.274, 0.052) * CFrame.Angles(math.rad(-23.377), math.rad(-29.908), math.rad(-142.838)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.048, 0.153, 0.024) * CFrame.Angles(math.rad(-5.787), math.rad(-11.115), math.rad(-9.74)),
					},
				},
			},
		},
		[0.133] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.042, -0.224) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-7.907)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.175, 0.187, 0.02) * CFrame.Angles(math.rad(-8.136), math.rad(8.365), math.rad(8.251)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.105, 0.017, 0.108) * CFrame.Angles(math.rad(29.679), math.rad(-40.451), math.rad(134.702)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.058, -0.272, 0.085) * CFrame.Angles(math.rad(-28.419), math.rad(-40.737), math.rad(-135.963)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.063, 0.2, 0.027) * CFrame.Angles(math.rad(-6.188), math.rad(-14.725), math.rad(-9.912)),
					},
				},
			},
		},
		[0.15] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.052, -0.276) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-9.74)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.217, 0.23, 0.023) * CFrame.Angles(math.rad(-8.824), math.rad(10.542), math.rad(8.021)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.189, 0.002, 0.201) * CFrame.Angles(math.rad(33.919), math.rad(-51.738), math.rad(127.598)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.002, -0.239, 0.108) * CFrame.Angles(math.rad(-32.429), math.rad(-51.967), math.rad(-129.03)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.078, 0.246, 0.028) * CFrame.Angles(math.rad(-6.589), math.rad(-18.335), math.rad(-10.084)),
					},
				},
			},
		},
		[0.167] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.061, -0.321) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-11.345)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.254, 0.267, 0.024) * CFrame.Angles(math.rad(-9.397), math.rad(12.433), math.rad(7.85)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.272, -0.028, 0.302) * CFrame.Angles(math.rad(36.383), math.rad(-61.765), math.rad(120.837)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.086, -0.191, 0.115) * CFrame.Angles(math.rad(-34.721), math.rad(-61.937), math.rad(-122.441)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.091, 0.287, 0.027) * CFrame.Angles(math.rad(-6.99), math.rad(-21.486), math.rad(-10.256)),
					},
				},
			},
		},
		[0.183] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.068, -0.36) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-12.662)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.285, 0.298, 0.024) * CFrame.Angles(math.rad(-9.855), math.rad(14.037), math.rad(7.735)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.344, -0.071, 0.402) * CFrame.Angles(math.rad(36.612), math.rad(-70.359), math.rad(113.618)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.179, -0.141, 0.106) * CFrame.Angles(math.rad(-34.836), math.rad(-70.417), math.rad(-115.279)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.103, 0.321, 0.025) * CFrame.Angles(math.rad(-7.334), math.rad(-24.122), math.rad(-10.485)),
					},
				},
			},
		},
		[0.2] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.074, -0.391) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-13.808)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.311, 0.324, 0.025) * CFrame.Angles(math.rad(-10.256), math.rad(15.355), math.rad(7.678)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.403, -0.117, 0.492) * CFrame.Angles(math.rad(33.289), math.rad(-77.292), math.rad(104.278)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.27, -0.097, 0.086) * CFrame.Angles(math.rad(-31.398), math.rad(-77.292), math.rad(-106.112)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.112, 0.348, 0.023) * CFrame.Angles(math.rad(-7.62), math.rad(-26.299), math.rad(-10.6)),
					},
				},
			},
		},
		[0.217] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.078, -0.416) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-14.668)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.331, 0.343, 0.024) * CFrame.Angles(math.rad(-10.6), math.rad(16.387), math.rad(7.563)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.448, -0.162, 0.566) * CFrame.Angles(math.rad(22.746), math.rad(-82.449), math.rad(89.152)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.35, -0.064, 0.063) * CFrame.Angles(math.rad(-20.97), math.rad(-82.391), math.rad(-91.272)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.12, 0.37, 0.021) * CFrame.Angles(math.rad(-7.85), math.rad(-28.018), math.rad(-10.772)),
					},
				},
			},
		},
		[0.233] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.082, -0.433) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-15.298)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.345, 0.357, 0.024) * CFrame.Angles(math.rad(-10.829), math.rad(17.131), math.rad(7.563)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.479, -0.198, 0.621) * CFrame.Angles(math.rad(-1.833), math.rad(-85.428), math.rad(61.306)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.412, -0.04, 0.042) * CFrame.Angles(math.rad(2.922), math.rad(-85.371), math.rad(-64.229)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.126, 0.385, 0.02) * CFrame.Angles(math.rad(-8.021), math.rad(-29.221), math.rad(-10.886)),
					},
				},
			},
		},
		[0.25] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.084, -0.444) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-15.642)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.354, 0.366, 0.024) * CFrame.Angles(math.rad(-10.943), math.rad(17.533), math.rad(7.506)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.496, -0.221, 0.655) * CFrame.Angles(math.rad(-32.716), math.rad(-86.23), math.rad(28.476)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.451, -0.026, 0.027) * CFrame.Angles(math.rad(32.888), math.rad(-86.173), math.rad(-32.372)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.129, 0.394, 0.018) * CFrame.Angles(math.rad(-8.136), math.rad(-29.908), math.rad(-10.943)),
					},
				},
			},
		},
		[0.267] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.084, -0.447) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-15.756)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.357, 0.368, 0.024) * CFrame.Angles(math.rad(-11.001), math.rad(17.704), math.rad(7.506)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.502, -0.229, 0.666) * CFrame.Angles(math.rad(-44.462), math.rad(-86.173), math.rad(16.1)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.464, -0.022, 0.022) * CFrame.Angles(math.rad(44.462), math.rad(-86.173), math.rad(-20.225)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.13, 0.397, 0.018) * CFrame.Angles(math.rad(-8.193), math.rad(-30.138), math.rad(-10.943)),
					},
				},
			},
		},
		[0.283] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.083, -0.443) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-15.584)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.353, 0.365, 0.024) * CFrame.Angles(math.rad(-10.943), math.rad(17.475), math.rad(7.506)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.495, -0.219, 0.651) * CFrame.Angles(math.rad(-29.164), math.rad(-86.173), math.rad(32.258)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.447, -0.028, 0.029) * CFrame.Angles(math.rad(29.335), math.rad(-86.173), math.rad(-36.096)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.129, 0.393, 0.018) * CFrame.Angles(math.rad(-8.136), math.rad(-29.851), math.rad(-10.943)),
					},
				},
			},
		},
		[0.3] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.081, -0.429) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-15.126)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.342, 0.354, 0.024) * CFrame.Angles(math.rad(-10.772), math.rad(16.902), math.rad(7.563)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.471, -0.189, 0.608) * CFrame.Angles(math.rad(6.875), math.rad(-84.855), math.rad(70.818)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.397, -0.046, 0.048) * CFrame.Angles(math.rad(-5.5), math.rad(-84.74), math.rad(-73.396)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.124, 0.381, 0.02) * CFrame.Angles(math.rad(-7.964), math.rad(-28.877), math.rad(-10.829)),
					},
				},
			},
		},
		[0.317] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.076, -0.406) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-14.324)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.323, 0.336, 0.024) * CFrame.Angles(math.rad(-10.485), math.rad(15.986), math.rad(7.62)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.431, -0.143, 0.537) * CFrame.Angles(math.rad(28.533), math.rad(-80.501), math.rad(96.773)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.318, -0.077, 0.073) * CFrame.Angles(math.rad(-26.643), math.rad(-80.443), math.rad(-98.721)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.117, 0.361, 0.022) * CFrame.Angles(math.rad(-7.735), math.rad(-27.33), math.rad(-10.714)),
					},
				},
			},
		},
		[0.333] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.07, -0.374) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-13.178)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.297, 0.31, 0.025) * CFrame.Angles(math.rad(-10.027), math.rad(14.668), math.rad(7.678)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.371, -0.09, 0.443) * CFrame.Angles(math.rad(35.753), math.rad(-73.51), math.rad(110.008)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.219, -0.121, 0.098) * CFrame.Angles(math.rad(-33.919), math.rad(-73.568), math.rad(-111.784)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.107, 0.333, 0.025) * CFrame.Angles(math.rad(-7.448), math.rad(-25.153), math.rad(-10.542)),
					},
				},
			},
		},
		[0.35] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.063, -0.333) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-11.746)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.263, 0.277, 0.024) * CFrame.Angles(math.rad(-9.511), math.rad(12.949), math.rad(7.85)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.294, -0.039, 0.332) * CFrame.Angles(math.rad(36.669), math.rad(-64.4), math.rad(118.889)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.112, -0.176, 0.113) * CFrame.Angles(math.rad(-35.008), math.rad(-64.515), math.rad(-120.493)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.095, 0.297, 0.027) * CFrame.Angles(math.rad(-7.105), math.rad(-22.288), math.rad(-10.313)),
					},
				},
			},
		},
		[0.367] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.053, -0.283) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-9.969)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.223, 0.236, 0.023) * CFrame.Angles(math.rad(-8.881), math.rad(10.829), math.rad(8.021)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.201, -0.001, 0.215) * CFrame.Angles(math.rad(34.377), math.rad(-53.285), math.rad(126.624)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.013, -0.232, 0.11) * CFrame.Angles(math.rad(-32.888), math.rad(-53.514), math.rad(-128.056)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.08, 0.253, 0.028) * CFrame.Angles(math.rad(-6.646), math.rad(-18.793), math.rad(-10.141)),
					},
				},
			},
		},
		[0.383] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.042, -0.224) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-7.907)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.175, 0.187, 0.02) * CFrame.Angles(math.rad(-8.136), math.rad(8.365), math.rad(8.251)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.105, 0.017, 0.108) * CFrame.Angles(math.rad(29.679), math.rad(-40.451), math.rad(134.702)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.058, -0.272, 0.085) * CFrame.Angles(math.rad(-28.419), math.rad(-40.737), math.rad(-135.963)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.063, 0.2, 0.027) * CFrame.Angles(math.rad(-6.188), math.rad(-14.725), math.rad(-9.912)),
					},
				},
			},
		},
		[0.4] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.031, -0.164) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-5.787)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.128, 0.138, 0.017) * CFrame.Angles(math.rad(-7.391), math.rad(5.901), math.rad(8.537)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.031, 0.014, 0.036) * CFrame.Angles(math.rad(23.606), math.rad(-28.19), math.rad(142.838)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.084, -0.271, 0.048) * CFrame.Angles(math.rad(-22.632), math.rad(-28.533), math.rad(-143.812)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.046, 0.147, 0.023) * CFrame.Angles(math.rad(-5.73), math.rad(-10.6), math.rad(-9.74)),
					},
				},
			},
		},
		[0.417] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.021, -0.114) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-4.011)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.089, 0.096, 0.013) * CFrame.Angles(math.rad(-6.704), math.rad(3.839), math.rad(8.766)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.008, 0.004, 0.001) * CFrame.Angles(math.rad(17.533), math.rad(-18.507), math.rad(150.172)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.077, -0.232, 0.018) * CFrame.Angles(math.rad(-16.845), math.rad(-18.85), math.rad(-150.86)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.032, 0.102, 0.018) * CFrame.Angles(math.rad(-5.329), math.rad(-7.162), math.rad(-9.626)),
					},
				},
			},
		},
		[0.433] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.014, -0.073) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-2.578)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.057, 0.062, 0.009) * CFrame.Angles(math.rad(-6.188), math.rad(2.177), math.rad(8.995)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.021, -0.003, -0.01) * CFrame.Angles(math.rad(11.86), math.rad(-11.173), math.rad(156.704)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.056, -0.172, 0.001) * CFrame.Angles(math.rad(-11.402), math.rad(-11.459), math.rad(-157.162)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.021, 0.066, 0.013) * CFrame.Angles(math.rad(-5.042), math.rad(-4.297), math.rad(-9.511)),
					},
				},
			},
		},
		[0.45] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.008, -0.041) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-1.432)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.032, 0.035, 0.005) * CFrame.Angles(math.rad(-5.73), math.rad(0.802), math.rad(9.167)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.019, -0.005, -0.01) * CFrame.Angles(math.rad(6.933), math.rad(-5.959), math.rad(162.147)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.033, -0.106, -0.005) * CFrame.Angles(math.rad(-6.704), math.rad(-6.131), math.rad(-162.434)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.012, 0.037, 0.008) * CFrame.Angles(math.rad(-4.813), math.rad(-2.063), math.rad(-9.511)),
					},
				},
			},
		},
		[0.467] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.003, -0.018) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-0.63)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.014, 0.016, 0.002) * CFrame.Angles(math.rad(-5.443), math.rad(-0.115), math.rad(9.339)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.01, -0.003, -0.005) * CFrame.Angles(math.rad(3.209), math.rad(-2.521), math.rad(166.33)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.015, -0.05, -0.004) * CFrame.Angles(math.rad(-3.094), math.rad(-2.636), math.rad(-166.444)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.005, 0.016, 0.004) * CFrame.Angles(math.rad(-4.641), math.rad(-0.516), math.rad(-9.454)),
					},
				},
			},
		},
		[0.483] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.001, -0.005) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-0.172)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.004, 0.004, 0.001) * CFrame.Angles(math.rad(-5.271), math.rad(-0.688), math.rad(9.397)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.003, -0.001, -0.002) * CFrame.Angles(math.rad(0.802), math.rad(-0.63), math.rad(168.908)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.004, -0.013, -0.001) * CFrame.Angles(math.rad(-0.802), math.rad(-0.63), math.rad(-168.908)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.001, 0.004, 0.001) * CFrame.Angles(math.rad(-4.526), math.rad(0.458), math.rad(-9.454)),
					},
				},
			},
		},
		[0.5] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.Angles(math.rad(-10.657), 0, 0),
					["Left Leg"] = {
						CFrame = CFrame.Angles(math.rad(-5.214), math.rad(-0.859), math.rad(9.397)),
					},
					["Right Arm"] = {
						CFrame = CFrame.Angles(0, 0, math.rad(169.767)),
					},
					["Left Arm"] = {
						CFrame = CFrame.Angles(0, 0, math.rad(-169.767)),
					},
					["Right Leg"] = {
						CFrame = CFrame.Angles(math.rad(-4.526), math.rad(0.745), math.rad(-9.454)),
					},
				},
			},
		},
		[0.517] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.001, -0.004) * CFrame.Angles(math.rad(-10.657), 0, math.rad(0.115)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.003, 0.004, 0.001) * CFrame.Angles(math.rad(-5.214), math.rad(-0.63), math.rad(9.397)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.004, -0.01, -0.002) * CFrame.Angles(math.rad(-0.573), math.rad(0.573), math.rad(169.137)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.003, -0.001, -0.001) * CFrame.Angles(math.rad(0.63), math.rad(0.516), math.rad(-169.08)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.001, 0.004, 0) * CFrame.Angles(math.rad(-4.584), math.rad(0.63), math.rad(-9.397)),
					},
				},
			},
		},
		[0.533] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.003, -0.017) * CFrame.Angles(math.rad(-10.657), 0, math.rad(0.401)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.011, 0.017, 0.004) * CFrame.Angles(math.rad(-5.329), math.rad(-0.057), math.rad(9.397)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.015, -0.04, -0.005) * CFrame.Angles(math.rad(-2.235), math.rad(2.235), math.rad(167.189)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.01, -0.004, -0.005) * CFrame.Angles(math.rad(2.406), math.rad(2.12), math.rad(-167.017)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.006, 0.017, 0) * CFrame.Angles(math.rad(-4.87), math.rad(0.172), math.rad(-9.397)),
					},
				},
			},
		},
		[0.55] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.007, -0.037) * CFrame.Angles(math.rad(-10.657), 0, math.rad(0.917)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.024, 0.039, 0.009) * CFrame.Angles(math.rad(-5.5), math.rad(1.031), math.rad(9.454)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.034, -0.086, -0.009) * CFrame.Angles(math.rad(-4.927), math.rad(5.157), math.rad(164.095)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.018, -0.008, -0.01) * CFrame.Angles(math.rad(5.271), math.rad(4.927), math.rad(-163.751)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.014, 0.038, 0.001) * CFrame.Angles(math.rad(-5.271), math.rad(-0.573), math.rad(-9.282)),
					},
				},
			},
		},
		[0.567] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.012, -0.066) * CFrame.Angles(math.rad(-10.657), 0, math.rad(1.604)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.042, 0.069, 0.015) * CFrame.Angles(math.rad(-5.73), math.rad(2.464), math.rad(9.454)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.058, -0.142, -0.01) * CFrame.Angles(math.rad(-8.422), math.rad(9.454), math.rad(159.913)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.025, -0.011, -0.014) * CFrame.Angles(math.rad(9.053), math.rad(9.11), math.rad(-159.34)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.024, 0.068, 0.001) * CFrame.Angles(math.rad(-5.901), math.rad(-1.662), math.rad(-9.225)),
					},
				},
			},
		},
		[0.583] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.02, -0.104) * CFrame.Angles(math.rad(-10.657), 0, math.rad(2.521)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.066, 0.108, 0.023) * CFrame.Angles(math.rad(-6.073), math.rad(4.354), math.rad(9.454)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.085, -0.201, -0.003) * CFrame.Angles(math.rad(-12.548), math.rad(15.298), math.rad(154.87)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.024, -0.012, -0.013) * CFrame.Angles(math.rad(13.465), math.rad(14.897), math.rad(-154.011)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.038, 0.106, 0.001) * CFrame.Angles(math.rad(-6.646), math.rad(-3.037), math.rad(-9.11)),
					},
				},
			},
		},
		[0.6] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.028, -0.149) * CFrame.Angles(math.rad(-10.657), 0, math.rad(3.61)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.095, 0.155, 0.032) * CFrame.Angles(math.rad(-6.474), math.rad(6.646), math.rad(9.511)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.107, -0.252, 0.014) * CFrame.Angles(math.rad(-16.96), math.rad(22.918), math.rad(149.084)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.009, -0.011, 0) * CFrame.Angles(math.rad(18.335), math.rad(22.46), math.rad(-147.88)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.055, 0.152, 0.001) * CFrame.Angles(math.rad(-7.62), math.rad(-4.641), math.rad(-8.995)),
					},
				},
			},
		},
		[0.617] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.038, -0.203) * CFrame.Angles(math.rad(-10.657), 0, math.rad(4.927)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.13, 0.211, 0.041) * CFrame.Angles(math.rad(-6.933), math.rad(9.397), math.rad(9.568)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.115, -0.284, 0.041) * CFrame.Angles(math.rad(-21.429), math.rad(32.372), math.rad(142.609)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.028, -0.011, 0.033) * CFrame.Angles(math.rad(23.205), math.rad(31.914), math.rad(-141.12)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.076, 0.206, 0) * CFrame.Angles(math.rad(-8.709), math.rad(-6.646), math.rad(-8.881)),
					},
				},
			},
		},
		[0.633] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.05, -0.265) * CFrame.Angles(math.rad(-10.657), 0, math.rad(6.474)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.17, 0.276, 0.05) * CFrame.Angles(math.rad(-7.448), math.rad(12.49), math.rad(9.683)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.093, -0.285, 0.073) * CFrame.Angles(math.rad(-25.554), math.rad(43.774), math.rad(135.218)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.092, -0.021, 0.096) * CFrame.Angles(math.rad(27.788), math.rad(43.43), math.rad(-133.442)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.101, 0.268, -0.003) * CFrame.Angles(math.rad(-10.027), math.rad(-8.881), math.rad(-8.824)),
					},
				},
			},
		},
		[0.65] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.062, -0.328) * CFrame.Angles(math.rad(-10.657), 0, math.rad(7.964)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.21, 0.34, 0.058) * CFrame.Angles(math.rad(-8.021), math.rad(15.642), math.rad(9.798)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.032, -0.256, 0.097) * CFrame.Angles(math.rad(-28.132), math.rad(55.52), math.rad(127.311)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.173, -0.049, 0.188) * CFrame.Angles(math.rad(30.882), math.rad(55.29), math.rad(-125.363)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.127, 0.329, -0.006) * CFrame.Angles(math.rad(-11.287), math.rad(-11.173), math.rad(-8.824)),
					},
				},
			},
		},
		[0.667] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.072, -0.381) * CFrame.Angles(math.rad(-10.657), 0, math.rad(9.282)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.246, 0.395, 0.064) * CFrame.Angles(math.rad(-8.48), math.rad(18.335), math.rad(9.912)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.054, -0.213, 0.104) * CFrame.Angles(math.rad(-28.075), math.rad(65.776), math.rad(118.717)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.251, -0.092, 0.289) * CFrame.Angles(math.rad(31.341), math.rad(65.718), math.rad(-116.712)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.15, 0.382, -0.01) * CFrame.Angles(math.rad(-12.433), math.rad(-13.121), math.rad(-8.881)),
					},
				},
			},
		},
		[0.683] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.08, -0.427) * CFrame.Angles(math.rad(-10.657), 0, math.rad(10.371)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.276, 0.442, 0.068) * CFrame.Angles(math.rad(-8.938), math.rad(20.626), math.rad(10.084)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.152, -0.168, 0.094) * CFrame.Angles(math.rad(-23.606), math.rad(74.313), math.rad(107.258)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.318, -0.146, 0.388) * CFrame.Angles(math.rad(27.387), math.rad(74.427), math.rad(-105.31)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.17, 0.426, -0.014) * CFrame.Angles(math.rad(-13.407), math.rad(-14.782), math.rad(-8.938)),
					},
				},
			},
		},
		[0.7] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.087, -0.464) * CFrame.Angles(math.rad(-10.657), 0, math.rad(11.287)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.301, 0.48, 0.071) * CFrame.Angles(math.rad(-9.282), math.rad(22.517), math.rad(10.199)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.247, -0.13, 0.074) * CFrame.Angles(math.rad(-9.167), math.rad(80.787), math.rad(87.204)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.371, -0.202, 0.478) * CFrame.Angles(math.rad(13.235), math.rad(81.074), math.rad(-85.199)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.186, 0.462, -0.017) * CFrame.Angles(math.rad(-14.209), math.rad(-16.157), math.rad(-8.995)),
					},
				},
			},
		},
		[0.717] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.093, -0.493) * CFrame.Angles(math.rad(-10.657), 0, math.rad(11.975)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.32, 0.51, 0.072) * CFrame.Angles(math.rad(-9.568), math.rad(24.007), math.rad(10.313)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.331, -0.1, 0.05) * CFrame.Angles(math.rad(25.955), math.rad(84.053), math.rad(47.727)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.411, -0.254, 0.551) * CFrame.Angles(math.rad(-24.064), math.rad(84.397), math.rad(-43.316)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.199, 0.489, -0.02) * CFrame.Angles(math.rad(-14.84), math.rad(-17.189), math.rad(-9.053)),
					},
				},
			},
		},
		[0.733] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.097, -0.514) * CFrame.Angles(math.rad(-10.657), 0, math.rad(12.49)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.335, 0.531, 0.073) * CFrame.Angles(math.rad(-9.798), math.rad(25.038), math.rad(10.428)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.395, -0.08, 0.028) * CFrame.Angles(math.rad(63.312), math.rad(83.652), math.rad(7.277)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.437, -0.296, 0.605) * CFrame.Angles(math.rad(-63.713), math.rad(83.824), math.rad(-0.401)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.209, 0.509, -0.022) * CFrame.Angles(math.rad(-15.241), math.rad(-17.934), math.rad(-9.11)),
					},
				},
			},
		},
		[0.75] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.099, -0.527) * CFrame.Angles(math.rad(-10.657), 0, math.rad(12.777)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.343, 0.544, 0.074) * CFrame.Angles(math.rad(-9.912), math.rad(25.669), math.rad(10.485)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.436, -0.069, 0.013) * CFrame.Angles(math.rad(79.24), math.rad(82.277), math.rad(-10.542)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.452, -0.323, 0.638) * CFrame.Angles(math.rad(-79.469), math.rad(82.334), math.rad(17.303)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.214, 0.521, -0.024) * CFrame.Angles(math.rad(-15.527), math.rad(-18.392), math.rad(-9.167)),
					},
				},
			},
		},
		[0.767] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.1, -0.531) * CFrame.Angles(math.rad(-10.657), 0, math.rad(12.892)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.346, 0.548, 0.074) * CFrame.Angles(math.rad(-9.969), math.rad(25.84), math.rad(10.485)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.449, -0.065, 0.008) * CFrame.Angles(math.rad(83.193), math.rad(81.704), math.rad(-15.126)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.457, -0.332, 0.649) * CFrame.Angles(math.rad(-83.193), math.rad(81.704), math.rad(21.772)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.216, 0.525, -0.024) * CFrame.Angles(math.rad(-15.642), math.rad(-18.564), math.rad(-9.167)),
					},
				},
			},
		},
		[0.783] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.099, -0.525) * CFrame.Angles(math.rad(-10.657), 0, math.rad(12.777)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.342, 0.542, 0.074) * CFrame.Angles(math.rad(-9.912), math.rad(25.554), math.rad(10.485)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.431, -0.07, 0.015) * CFrame.Angles(math.rad(77.922), math.rad(82.449), math.rad(-8.995)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.451, -0.32, 0.635) * CFrame.Angles(math.rad(-78.151), math.rad(82.506), math.rad(15.814)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.214, 0.519, -0.023) * CFrame.Angles(math.rad(-15.527), math.rad(-18.335), math.rad(-9.167)),
					},
				},
			},
		},
		[0.8] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.096, -0.509) * CFrame.Angles(math.rad(-10.657), 0, math.rad(12.376)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.331, 0.526, 0.073) * CFrame.Angles(math.rad(-9.74), math.rad(24.752), math.rad(10.371)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.379, -0.085, 0.034) * CFrame.Angles(math.rad(54.889), math.rad(83.996), math.rad(16.444)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.431, -0.285, 0.592) * CFrame.Angles(math.rad(-55.061), math.rad(84.225), math.rad(-9.798)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.206, 0.504, -0.022) * CFrame.Angles(math.rad(-15.126), math.rad(-17.762), math.rad(-9.11)),
					},
				},
			},
		},
		[0.817] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.091, -0.482) * CFrame.Angles(math.rad(-10.657), 0, math.rad(11.746)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.313, 0.498, 0.072) * CFrame.Angles(math.rad(-9.454), math.rad(23.377), math.rad(10.256)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.297, -0.112, 0.061) * CFrame.Angles(math.rad(8.079), math.rad(83.136), math.rad(67.323)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.396, -0.233, 0.522) * CFrame.Angles(math.rad(-4.756), math.rad(83.48), math.rad(-64.4)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.194, 0.478, -0.019) * CFrame.Angles(math.rad(-14.553), math.rad(-16.788), math.rad(-9.053)),
					},
				},
			},
		},
		[0.833] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.084, -0.444) * CFrame.Angles(math.rad(-10.657), 0, math.rad(10.772)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.287, 0.459, 0.069) * CFrame.Angles(math.rad(-9.11), math.rad(21.486), math.rad(10.141)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.193, -0.151, 0.087) * CFrame.Angles(math.rad(-19.251), math.rad(77.407), math.rad(100.268)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.343, -0.17, 0.428) * CFrame.Angles(math.rad(23.205), math.rad(77.578), math.rad(-98.434)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.177, 0.442, -0.015) * CFrame.Angles(math.rad(-13.751), math.rad(-15.413), math.rad(-8.938)),
					},
				},
			},
		},
		[0.85] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.074, -0.395) * CFrame.Angles(math.rad(-10.657), 0, math.rad(9.626)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.255, 0.41, 0.065) * CFrame.Angles(math.rad(-8.652), math.rad(19.022), math.rad(9.969)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.081, -0.2, 0.102) * CFrame.Angles(math.rad(-27.387), math.rad(68.411), math.rad(115.852)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.271, -0.107, 0.318) * CFrame.Angles(math.rad(30.768), math.rad(68.411), math.rad(-113.847)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.156, 0.395, -0.011) * CFrame.Angles(math.rad(-12.72), math.rad(-13.636), math.rad(-8.881)),
					},
				},
			},
		},
		[0.867] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.063, -0.336) * CFrame.Angles(math.rad(-10.657), 0, math.rad(8.136)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.216, 0.348, 0.059) * CFrame.Angles(math.rad(-8.079), math.rad(16.043), math.rad(9.798)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.021, -0.251, 0.099) * CFrame.Angles(math.rad(-28.304), math.rad(57.067), math.rad(126.165)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.185, -0.054, 0.202) * CFrame.Angles(math.rad(31.112), math.rad(56.837), math.rad(-124.16)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.13, 0.337, -0.007) * CFrame.Angles(math.rad(-11.459), math.rad(-11.459), math.rad(-8.824)),
					},
				},
			},
		},
		[0.883] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.05, -0.265) * CFrame.Angles(math.rad(-10.657), 0, math.rad(6.474)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.17, 0.276, 0.05) * CFrame.Angles(math.rad(-7.448), math.rad(12.49), math.rad(9.683)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.093, -0.285, 0.073) * CFrame.Angles(math.rad(-25.554), math.rad(43.774), math.rad(135.218)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.092, -0.021, 0.096) * CFrame.Angles(math.rad(27.788), math.rad(43.43), math.rad(-133.442)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.101, 0.268, -0.003) * CFrame.Angles(math.rad(-10.027), math.rad(-8.881), math.rad(-8.824)),
					},
				},
			},
		},
		[0.9] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.037, -0.195) * CFrame.Angles(math.rad(-10.657), 0, math.rad(4.756)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.124, 0.203, 0.04) * CFrame.Angles(math.rad(-6.818), math.rad(8.938), math.rad(9.568)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.116, -0.281, 0.036) * CFrame.Angles(math.rad(-20.798), math.rad(30.94), math.rad(143.526)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.021, -0.011, 0.026) * CFrame.Angles(math.rad(22.517), math.rad(30.481), math.rad(-142.094)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.073, 0.198, 0) * CFrame.Angles(math.rad(-8.537), math.rad(-6.303), math.rad(-8.881)),
					},
				},
			},
		},
		[0.917] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.026, -0.135) * CFrame.Angles(math.rad(-10.657), 0, math.rad(3.266)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.086, 0.141, 0.029) * CFrame.Angles(math.rad(-6.36), math.rad(5.959), math.rad(9.454)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.102, -0.239, 0.008) * CFrame.Angles(math.rad(-15.699), math.rad(20.569), math.rad(150.802)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.015, -0.012, -0.005) * CFrame.Angles(math.rad(16.902), math.rad(20.111), math.rad(-149.714)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.05, 0.138, 0.001) * CFrame.Angles(math.rad(-7.334), math.rad(-4.183), math.rad(-8.995)),
					},
				},
			},
		},
		[0.933] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.016, -0.087) * CFrame.Angles(math.rad(-10.657), 0, math.rad(2.12)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.055, 0.09, 0.02) * CFrame.Angles(math.rad(-5.901), math.rad(3.495), math.rad(9.454)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.073, -0.176, -0.007) * CFrame.Angles(math.rad(-10.714), math.rad(12.605), math.rad(157.105)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.026, -0.012, -0.014) * CFrame.Angles(math.rad(11.516), math.rad(12.204), math.rad(-156.417)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.032, 0.089, 0.001) * CFrame.Angles(math.rad(-6.303), math.rad(-2.406), math.rad(-9.167)),
					},
				},
			},
		},
		[0.95] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.009, -0.049) * CFrame.Angles(math.rad(-10.657), 0, math.rad(1.203)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.031, 0.051, 0.011) * CFrame.Angles(math.rad(-5.615), math.rad(1.604), math.rad(9.454)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.044, -0.109, -0.01) * CFrame.Angles(math.rad(-6.36), math.rad(6.818), math.rad(162.434)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.022, -0.01, -0.012) * CFrame.Angles(math.rad(6.818), math.rad(6.532), math.rad(-161.975)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.018, 0.05, 0.001) * CFrame.Angles(math.rad(-5.558), math.rad(-1.031), math.rad(-9.282)),
					},
				},
			},
		},
		[0.967] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.004, -0.022) * CFrame.Angles(math.rad(-10.657), 0, math.rad(0.516)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.014, 0.023, 0.005) * CFrame.Angles(math.rad(-5.386), math.rad(0.229), math.rad(9.397)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.02, -0.052, -0.007) * CFrame.Angles(math.rad(-2.922), math.rad(2.922), math.rad(166.387)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.012, -0.006, -0.007) * CFrame.Angles(math.rad(3.151), math.rad(2.807), math.rad(-166.215)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.008, 0.022, 0.001) * CFrame.Angles(math.rad(-4.985), math.rad(-0.057), math.rad(-9.339)),
					},
				},
			},
		},
		[0.983] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.001, -0.005) * CFrame.Angles(math.rad(-10.657), 0, math.rad(0.115)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.003, 0.006, 0.001) * CFrame.Angles(math.rad(-5.271), math.rad(-0.573), math.rad(9.397)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.005, -0.013, -0.002) * CFrame.Angles(math.rad(-0.745), math.rad(0.688), math.rad(168.908)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.003, -0.002, -0.002) * CFrame.Angles(math.rad(0.802), math.rad(0.688), math.rad(-168.851)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.002, 0.006, 0) * CFrame.Angles(math.rad(-4.641), math.rad(0.573), math.rad(-9.397)),
					},
				},
			},
		},
		[1] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.Angles(math.rad(-10.657), 0, 0),
					["Left Leg"] = {
						CFrame = CFrame.Angles(math.rad(-5.214), math.rad(-0.859), math.rad(9.397)),
					},
					["Right Arm"] = {
						CFrame = CFrame.Angles(0, 0, math.rad(169.767)),
					},
					["Left Arm"] = {
						CFrame = CFrame.Angles(0, 0, math.rad(-169.767)),
					},
					["Right Leg"] = {
						CFrame = CFrame.Angles(math.rad(-4.526), math.rad(0.745), math.rad(-9.454)),
					},
				},
			},
		},
		[1.017] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.001, -0.004) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-0.115)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.003, 0.003, 0.001) * CFrame.Angles(math.rad(-5.271), math.rad(-0.688), math.rad(9.397)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.003, -0.001, -0.001) * CFrame.Angles(math.rad(0.688), math.rad(-0.516), math.rad(169.023)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.003, -0.011, -0.001) * CFrame.Angles(math.rad(-0.688), math.rad(-0.573), math.rad(-169.023)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.001, 0.004, 0.001) * CFrame.Angles(math.rad(-4.526), math.rad(0.458), math.rad(-9.454)),
					},
				},
			},
		},
		[1.033] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.003, -0.016) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-0.573)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.012, 0.014, 0.002) * CFrame.Angles(math.rad(-5.443), math.rad(-0.229), math.rad(9.339)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.009, -0.003, -0.005) * CFrame.Angles(math.rad(2.807), math.rad(-2.177), math.rad(166.731)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.013, -0.044, -0.004) * CFrame.Angles(math.rad(-2.693), math.rad(-2.292), math.rad(-166.845)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.005, 0.014, 0.003) * CFrame.Angles(math.rad(-4.641), math.rad(-0.344), math.rad(-9.454)),
					},
				},
			},
		},
		[1.05] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.007, -0.036) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-1.261)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.028, 0.03, 0.004) * CFrame.Angles(math.rad(-5.672), math.rad(0.63), math.rad(9.225)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.017, -0.005, -0.009) * CFrame.Angles(math.rad(6.131), math.rad(-5.157), math.rad(163.121)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.029, -0.094, -0.006) * CFrame.Angles(math.rad(-5.844), math.rad(-5.271), math.rad(-163.35)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.01, 0.032, 0.007) * CFrame.Angles(math.rad(-4.756), math.rad(-1.719), math.rad(-9.454)),
					},
				},
			},
		},
		[1.067] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.012, -0.064) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-2.235)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.049, 0.054, 0.008) * CFrame.Angles(math.rad(-6.073), math.rad(1.776), math.rad(9.053)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.021, -0.004, -0.011) * CFrame.Angles(math.rad(10.485), math.rad(-9.626), math.rad(158.251)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.05, -0.154, -0.002) * CFrame.Angles(math.rad(-10.027), math.rad(-9.855), math.rad(-158.652)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.018, 0.057, 0.011) * CFrame.Angles(math.rad(-4.985), math.rad(-3.667), math.rad(-9.511)),
					},
				},
			},
		},
		[1.083] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.019, -0.099) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-3.495)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.077, 0.084, 0.011) * CFrame.Angles(math.rad(-6.532), math.rad(3.266), math.rad(8.824)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.014, 0.001, -0.004) * CFrame.Angles(math.rad(15.584), math.rad(-15.814), math.rad(152.464)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.071, -0.213, 0.011) * CFrame.Angles(math.rad(-14.954), math.rad(-16.1), math.rad(-153.094)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.028, 0.089, 0.016) * CFrame.Angles(math.rad(-5.214), math.rad(-6.131), math.rad(-9.568)),
					},
				},
			},
		},
		[1.1] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.027, -0.143) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-5.042)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.112, 0.121, 0.015) * CFrame.Angles(math.rad(-7.105), math.rad(5.042), math.rad(8.594)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.012, 0.01, 0.018) * CFrame.Angles(math.rad(21.142), math.rad(-24.007), math.rad(145.875)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.084, -0.259, 0.034) * CFrame.Angles(math.rad(-20.283), math.rad(-24.351), math.rad(-146.734)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.04, 0.128, 0.021) * CFrame.Angles(math.rad(-5.558), math.rad(-9.167), math.rad(-9.683)),
					},
				},
			},
		},
		[1.117] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.037, -0.195) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-6.875)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.153, 0.164, 0.019) * CFrame.Angles(math.rad(-7.792), math.rad(7.219), math.rad(8.365)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.065, 0.017, 0.068) * CFrame.Angles(math.rad(26.872), math.rad(-34.435), math.rad(138.598)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.076, -0.277, 0.067) * CFrame.Angles(math.rad(-25.783), math.rad(-34.721), math.rad(-139.744)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.055, 0.174, 0.025) * CFrame.Angles(math.rad(-5.959), math.rad(-12.72), math.rad(-9.798)),
					},
				},
			},
		},
		[1.133] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.048, -0.252) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-8.881)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.198, 0.211, 0.022) * CFrame.Angles(math.rad(-8.48), math.rad(9.568), math.rad(8.136)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.149, 0.011, 0.155) * CFrame.Angles(math.rad(32.143), math.rad(-46.639), math.rad(130.806)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.03, -0.257, 0.099) * CFrame.Angles(math.rad(-30.768), math.rad(-46.868), math.rad(-132.181)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.071, 0.226, 0.027) * CFrame.Angles(math.rad(-6.417), math.rad(-16.73), math.rad(-10.027)),
					},
				},
			},
		},
		[1.15] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.057, -0.304) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-10.714)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.24, 0.253, 0.024) * CFrame.Angles(math.rad(-9.167), math.rad(11.746), math.rad(7.907)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.24, -0.014, 0.261) * CFrame.Angles(math.rad(35.581), math.rad(-57.926), math.rad(123.53)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.05, -0.211, 0.114) * CFrame.Angles(math.rad(-34.034), math.rad(-58.098), math.rad(-125.077)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.086, 0.271, 0.027) * CFrame.Angles(math.rad(-6.818), math.rad(-20.283), math.rad(-10.199)),
					},
				},
			},
		},
		[1.167] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.066, -0.348) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-12.261)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.275, 0.289, 0.024) * CFrame.Angles(math.rad(-9.74), math.rad(13.579), math.rad(7.792)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.322, -0.056, 0.37) * CFrame.Angles(math.rad(36.841), math.rad(-67.666), math.rad(116.139)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.147, -0.157, 0.11) * CFrame.Angles(math.rad(-35.065), math.rad(-67.781), math.rad(-117.8)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.099, 0.31, 0.026) * CFrame.Angles(math.rad(-7.219), math.rad(-23.319), math.rad(-10.428)),
					},
				},
			},
		},
		[1.183] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.072, -0.384) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-13.522)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.305, 0.318, 0.025) * CFrame.Angles(math.rad(-10.199), math.rad(15.011), math.rad(7.678)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.389, -0.105, 0.47) * CFrame.Angles(math.rad(34.664), math.rad(-75.63), math.rad(107.143)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.247, -0.108, 0.092) * CFrame.Angles(math.rad(-32.773), math.rad(-75.63), math.rad(-108.919)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.11, 0.341, 0.024) * CFrame.Angles(math.rad(-7.563), math.rad(-25.783), math.rad(-10.6)),
					},
				},
			},
		},
		[1.2] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.077, -0.411) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-14.496)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.327, 0.34, 0.024) * CFrame.Angles(math.rad(-10.542), math.rad(16.215), math.rad(7.62)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.44, -0.153, 0.553) * CFrame.Angles(math.rad(25.726), math.rad(-81.589), math.rad(92.991)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.336, -0.07, 0.068) * CFrame.Angles(math.rad(-23.892), math.rad(-81.532), math.rad(-94.996)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.119, 0.366, 0.022) * CFrame.Angles(math.rad(-7.792), math.rad(-27.674), math.rad(-10.714)),
					},
				},
			},
		},
		[1.217] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.081, -0.431) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-15.183)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.344, 0.356, 0.024) * CFrame.Angles(math.rad(-10.772), math.rad(17.017), math.rad(7.563)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.475, -0.194, 0.615) * CFrame.Angles(math.rad(2.349), math.rad(-85.199), math.rad(65.89)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.405, -0.043, 0.045) * CFrame.Angles(math.rad(-1.146), math.rad(-85.142), math.rad(-68.64)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.125, 0.383, 0.02) * CFrame.Angles(math.rad(-8.021), math.rad(-29.049), math.rad(-10.829)),
					},
				},
			},
		},
		[1.233] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.083, -0.443) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-15.642)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.354, 0.365, 0.024) * CFrame.Angles(math.rad(-10.943), math.rad(17.533), math.rad(7.506)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.496, -0.22, 0.653) * CFrame.Angles(math.rad(-31.112), math.rad(-86.23), math.rad(30.195)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.449, -0.027, 0.028) * CFrame.Angles(math.rad(31.283), math.rad(-86.173), math.rad(-34.091)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.129, 0.394, 0.018) * CFrame.Angles(math.rad(-8.136), math.rad(-29.908), math.rad(-10.943)),
					},
				},
			},
		},
		[1.25] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.084, -0.447) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-15.756)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.357, 0.368, 0.024) * CFrame.Angles(math.rad(-11.001), math.rad(17.704), math.rad(7.506)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.502, -0.229, 0.666) * CFrame.Angles(math.rad(-44.462), math.rad(-86.173), math.rad(16.1)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.464, -0.022, 0.022) * CFrame.Angles(math.rad(44.462), math.rad(-86.173), math.rad(-20.225)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.13, 0.397, 0.018) * CFrame.Angles(math.rad(-8.193), math.rad(-30.138), math.rad(-10.943)),
					},
				},
			},
		},
		[1.267] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.083, -0.443) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-15.584)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.353, 0.365, 0.024) * CFrame.Angles(math.rad(-10.943), math.rad(17.475), math.rad(7.506)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.495, -0.219, 0.651) * CFrame.Angles(math.rad(-29.164), math.rad(-86.173), math.rad(32.258)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.447, -0.028, 0.029) * CFrame.Angles(math.rad(29.335), math.rad(-86.173), math.rad(-36.096)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.129, 0.393, 0.018) * CFrame.Angles(math.rad(-8.136), math.rad(-29.851), math.rad(-10.943)),
					},
				},
			},
		},
		[1.283] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.081, -0.429) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-15.126)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.342, 0.354, 0.024) * CFrame.Angles(math.rad(-10.772), math.rad(16.902), math.rad(7.563)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.471, -0.189, 0.608) * CFrame.Angles(math.rad(6.875), math.rad(-84.855), math.rad(70.818)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.397, -0.046, 0.048) * CFrame.Angles(math.rad(-5.5), math.rad(-84.74), math.rad(-73.396)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.124, 0.381, 0.02) * CFrame.Angles(math.rad(-7.964), math.rad(-28.877), math.rad(-10.829)),
					},
				},
			},
		},
		[1.3] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.076, -0.406) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-14.324)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.323, 0.336, 0.024) * CFrame.Angles(math.rad(-10.485), math.rad(15.986), math.rad(7.62)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.431, -0.143, 0.537) * CFrame.Angles(math.rad(28.533), math.rad(-80.501), math.rad(96.773)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.318, -0.077, 0.073) * CFrame.Angles(math.rad(-26.643), math.rad(-80.443), math.rad(-98.721)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.117, 0.361, 0.022) * CFrame.Angles(math.rad(-7.735), math.rad(-27.33), math.rad(-10.714)),
					},
				},
			},
		},
		[1.317] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.07, -0.374) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-13.178)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.297, 0.31, 0.025) * CFrame.Angles(math.rad(-10.027), math.rad(14.668), math.rad(7.678)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.371, -0.09, 0.443) * CFrame.Angles(math.rad(35.753), math.rad(-73.51), math.rad(110.008)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.219, -0.121, 0.098) * CFrame.Angles(math.rad(-33.919), math.rad(-73.568), math.rad(-111.784)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.107, 0.333, 0.025) * CFrame.Angles(math.rad(-7.448), math.rad(-25.153), math.rad(-10.542)),
					},
				},
			},
		},
		[1.333] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.063, -0.333) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-11.746)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.263, 0.277, 0.024) * CFrame.Angles(math.rad(-9.511), math.rad(12.949), math.rad(7.85)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.294, -0.039, 0.332) * CFrame.Angles(math.rad(36.669), math.rad(-64.4), math.rad(118.889)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.112, -0.176, 0.113) * CFrame.Angles(math.rad(-35.008), math.rad(-64.515), math.rad(-120.493)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.095, 0.297, 0.027) * CFrame.Angles(math.rad(-7.105), math.rad(-22.288), math.rad(-10.313)),
					},
				},
			},
		},
		[1.35] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.053, -0.283) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-9.969)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.223, 0.236, 0.023) * CFrame.Angles(math.rad(-8.881), math.rad(10.829), math.rad(8.021)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.201, -0.001, 0.215) * CFrame.Angles(math.rad(34.377), math.rad(-53.285), math.rad(126.624)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.013, -0.232, 0.11) * CFrame.Angles(math.rad(-32.888), math.rad(-53.514), math.rad(-128.056)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.08, 0.253, 0.028) * CFrame.Angles(math.rad(-6.646), math.rad(-18.793), math.rad(-10.141)),
					},
				},
			},
		},
		[1.367] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.042, -0.224) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-7.907)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.175, 0.187, 0.02) * CFrame.Angles(math.rad(-8.136), math.rad(8.365), math.rad(8.251)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.105, 0.017, 0.108) * CFrame.Angles(math.rad(29.679), math.rad(-40.451), math.rad(134.702)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.058, -0.272, 0.085) * CFrame.Angles(math.rad(-28.419), math.rad(-40.737), math.rad(-135.963)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.063, 0.2, 0.027) * CFrame.Angles(math.rad(-6.188), math.rad(-14.725), math.rad(-9.912)),
					},
				},
			},
		},
		[1.383] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.031, -0.164) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-5.787)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.128, 0.138, 0.017) * CFrame.Angles(math.rad(-7.391), math.rad(5.901), math.rad(8.537)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.031, 0.014, 0.036) * CFrame.Angles(math.rad(23.606), math.rad(-28.19), math.rad(142.838)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.084, -0.271, 0.048) * CFrame.Angles(math.rad(-22.632), math.rad(-28.533), math.rad(-143.812)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.046, 0.147, 0.023) * CFrame.Angles(math.rad(-5.73), math.rad(-10.6), math.rad(-9.74)),
					},
				},
			},
		},
		[1.4] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.021, -0.114) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-4.011)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.089, 0.096, 0.013) * CFrame.Angles(math.rad(-6.704), math.rad(3.839), math.rad(8.766)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.008, 0.004, 0.001) * CFrame.Angles(math.rad(17.533), math.rad(-18.507), math.rad(150.172)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.077, -0.232, 0.018) * CFrame.Angles(math.rad(-16.845), math.rad(-18.85), math.rad(-150.86)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.032, 0.102, 0.018) * CFrame.Angles(math.rad(-5.329), math.rad(-7.162), math.rad(-9.626)),
					},
				},
			},
		},
		[1.417] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.014, -0.073) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-2.578)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.057, 0.062, 0.009) * CFrame.Angles(math.rad(-6.188), math.rad(2.177), math.rad(8.995)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.021, -0.003, -0.01) * CFrame.Angles(math.rad(11.86), math.rad(-11.173), math.rad(156.704)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.056, -0.172, 0.001) * CFrame.Angles(math.rad(-11.402), math.rad(-11.459), math.rad(-157.162)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.021, 0.066, 0.013) * CFrame.Angles(math.rad(-5.042), math.rad(-4.297), math.rad(-9.511)),
					},
				},
			},
		},
		[1.433] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.008, -0.041) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-1.432)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.032, 0.035, 0.005) * CFrame.Angles(math.rad(-5.73), math.rad(0.802), math.rad(9.167)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.019, -0.005, -0.01) * CFrame.Angles(math.rad(6.933), math.rad(-5.959), math.rad(162.147)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.033, -0.106, -0.005) * CFrame.Angles(math.rad(-6.704), math.rad(-6.131), math.rad(-162.434)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.012, 0.037, 0.008) * CFrame.Angles(math.rad(-4.813), math.rad(-2.063), math.rad(-9.511)),
					},
				},
			},
		},
		[1.45] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.003, -0.018) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-0.63)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.014, 0.016, 0.002) * CFrame.Angles(math.rad(-5.443), math.rad(-0.115), math.rad(9.339)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.01, -0.003, -0.005) * CFrame.Angles(math.rad(3.209), math.rad(-2.521), math.rad(166.33)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.015, -0.05, -0.004) * CFrame.Angles(math.rad(-3.094), math.rad(-2.636), math.rad(-166.444)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.005, 0.016, 0.004) * CFrame.Angles(math.rad(-4.641), math.rad(-0.516), math.rad(-9.454)),
					},
				},
			},
		},
		[1.467] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.001, -0.005) * CFrame.Angles(math.rad(-10.657), 0, math.rad(-0.172)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.004, 0.004, 0.001) * CFrame.Angles(math.rad(-5.271), math.rad(-0.688), math.rad(9.397)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.003, -0.001, -0.002) * CFrame.Angles(math.rad(0.802), math.rad(-0.63), math.rad(168.908)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.004, -0.013, -0.001) * CFrame.Angles(math.rad(-0.802), math.rad(-0.63), math.rad(-168.908)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.001, 0.004, 0.001) * CFrame.Angles(math.rad(-4.526), math.rad(0.458), math.rad(-9.454)),
					},
				},
			},
		},
		[1.483] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.Angles(math.rad(-10.657), 0, 0),
					["Left Leg"] = {
						CFrame = CFrame.Angles(math.rad(-5.214), math.rad(-0.859), math.rad(9.397)),
					},
					["Right Arm"] = {
						CFrame = CFrame.Angles(0, 0, math.rad(169.767)),
					},
					["Left Arm"] = {
						CFrame = CFrame.Angles(0, 0, math.rad(-169.767)),
					},
					["Right Leg"] = {
						CFrame = CFrame.Angles(math.rad(-4.526), math.rad(0.745), math.rad(-9.454)),
					},
				},
			},
		},
		[1.5] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.001, -0.004) * CFrame.Angles(math.rad(-10.657), 0, math.rad(0.115)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.003, 0.004, 0.001) * CFrame.Angles(math.rad(-5.214), math.rad(-0.63), math.rad(9.397)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.004, -0.01, -0.002) * CFrame.Angles(math.rad(-0.573), math.rad(0.573), math.rad(169.137)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.003, -0.001, -0.001) * CFrame.Angles(math.rad(0.63), math.rad(0.516), math.rad(-169.08)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.001, 0.004, 0) * CFrame.Angles(math.rad(-4.584), math.rad(0.63), math.rad(-9.397)),
					},
				},
			},
		},
		[1.517] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.003, -0.017) * CFrame.Angles(math.rad(-10.657), 0, math.rad(0.401)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.011, 0.017, 0.004) * CFrame.Angles(math.rad(-5.329), math.rad(-0.057), math.rad(9.397)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.015, -0.04, -0.005) * CFrame.Angles(math.rad(-2.235), math.rad(2.235), math.rad(167.189)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.01, -0.004, -0.005) * CFrame.Angles(math.rad(2.406), math.rad(2.12), math.rad(-167.017)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.006, 0.017, 0) * CFrame.Angles(math.rad(-4.87), math.rad(0.172), math.rad(-9.397)),
					},
				},
			},
		},
		[1.533] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.007, -0.037) * CFrame.Angles(math.rad(-10.657), 0, math.rad(0.917)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.024, 0.039, 0.009) * CFrame.Angles(math.rad(-5.5), math.rad(1.031), math.rad(9.454)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.034, -0.086, -0.009) * CFrame.Angles(math.rad(-4.927), math.rad(5.157), math.rad(164.095)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.018, -0.008, -0.01) * CFrame.Angles(math.rad(5.271), math.rad(4.927), math.rad(-163.751)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.014, 0.038, 0.001) * CFrame.Angles(math.rad(-5.271), math.rad(-0.573), math.rad(-9.282)),
					},
				},
			},
		},
		[1.55] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.012, -0.066) * CFrame.Angles(math.rad(-10.657), 0, math.rad(1.604)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.042, 0.069, 0.015) * CFrame.Angles(math.rad(-5.73), math.rad(2.464), math.rad(9.454)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.058, -0.142, -0.01) * CFrame.Angles(math.rad(-8.422), math.rad(9.454), math.rad(159.913)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.025, -0.011, -0.014) * CFrame.Angles(math.rad(9.053), math.rad(9.11), math.rad(-159.34)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.024, 0.068, 0.001) * CFrame.Angles(math.rad(-5.901), math.rad(-1.662), math.rad(-9.225)),
					},
				},
			},
		},
		[1.567] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.02, -0.104) * CFrame.Angles(math.rad(-10.657), 0, math.rad(2.521)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.066, 0.108, 0.023) * CFrame.Angles(math.rad(-6.073), math.rad(4.354), math.rad(9.454)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.085, -0.201, -0.003) * CFrame.Angles(math.rad(-12.548), math.rad(15.298), math.rad(154.87)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.024, -0.012, -0.013) * CFrame.Angles(math.rad(13.465), math.rad(14.897), math.rad(-154.011)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.038, 0.106, 0.001) * CFrame.Angles(math.rad(-6.646), math.rad(-3.037), math.rad(-9.11)),
					},
				},
			},
		},
		[1.583] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.028, -0.149) * CFrame.Angles(math.rad(-10.657), 0, math.rad(3.61)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.095, 0.155, 0.032) * CFrame.Angles(math.rad(-6.474), math.rad(6.646), math.rad(9.511)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.107, -0.252, 0.014) * CFrame.Angles(math.rad(-16.96), math.rad(22.918), math.rad(149.084)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.009, -0.011, 0) * CFrame.Angles(math.rad(18.335), math.rad(22.46), math.rad(-147.88)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.055, 0.152, 0.001) * CFrame.Angles(math.rad(-7.62), math.rad(-4.641), math.rad(-8.995)),
					},
				},
			},
		},
		[1.6] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.038, -0.203) * CFrame.Angles(math.rad(-10.657), 0, math.rad(4.927)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.13, 0.211, 0.041) * CFrame.Angles(math.rad(-6.933), math.rad(9.397), math.rad(9.568)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.115, -0.284, 0.041) * CFrame.Angles(math.rad(-21.429), math.rad(32.372), math.rad(142.609)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.028, -0.011, 0.033) * CFrame.Angles(math.rad(23.205), math.rad(31.914), math.rad(-141.12)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.076, 0.206, 0) * CFrame.Angles(math.rad(-8.709), math.rad(-6.646), math.rad(-8.881)),
					},
				},
			},
		},
		[1.617] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.05, -0.265) * CFrame.Angles(math.rad(-10.657), 0, math.rad(6.474)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.17, 0.276, 0.05) * CFrame.Angles(math.rad(-7.448), math.rad(12.49), math.rad(9.683)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.093, -0.285, 0.073) * CFrame.Angles(math.rad(-25.554), math.rad(43.774), math.rad(135.218)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.092, -0.021, 0.096) * CFrame.Angles(math.rad(27.788), math.rad(43.43), math.rad(-133.442)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.101, 0.268, -0.003) * CFrame.Angles(math.rad(-10.027), math.rad(-8.881), math.rad(-8.824)),
					},
				},
			},
		},
		[1.633] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.062, -0.328) * CFrame.Angles(math.rad(-10.657), 0, math.rad(7.964)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.21, 0.34, 0.058) * CFrame.Angles(math.rad(-8.021), math.rad(15.642), math.rad(9.798)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.032, -0.256, 0.097) * CFrame.Angles(math.rad(-28.132), math.rad(55.52), math.rad(127.311)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.173, -0.049, 0.188) * CFrame.Angles(math.rad(30.882), math.rad(55.29), math.rad(-125.363)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.127, 0.329, -0.006) * CFrame.Angles(math.rad(-11.287), math.rad(-11.173), math.rad(-8.824)),
					},
				},
			},
		},
		[1.65] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.072, -0.381) * CFrame.Angles(math.rad(-10.657), 0, math.rad(9.282)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.246, 0.395, 0.064) * CFrame.Angles(math.rad(-8.48), math.rad(18.335), math.rad(9.912)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.054, -0.213, 0.104) * CFrame.Angles(math.rad(-28.075), math.rad(65.776), math.rad(118.717)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.251, -0.092, 0.289) * CFrame.Angles(math.rad(31.341), math.rad(65.718), math.rad(-116.712)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.15, 0.382, -0.01) * CFrame.Angles(math.rad(-12.433), math.rad(-13.121), math.rad(-8.881)),
					},
				},
			},
		},
		[1.667] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.08, -0.427) * CFrame.Angles(math.rad(-10.657), 0, math.rad(10.371)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.276, 0.442, 0.068) * CFrame.Angles(math.rad(-8.938), math.rad(20.626), math.rad(10.084)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.152, -0.168, 0.094) * CFrame.Angles(math.rad(-23.606), math.rad(74.313), math.rad(107.258)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.318, -0.146, 0.388) * CFrame.Angles(math.rad(27.387), math.rad(74.427), math.rad(-105.31)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.17, 0.426, -0.014) * CFrame.Angles(math.rad(-13.407), math.rad(-14.782), math.rad(-8.938)),
					},
				},
			},
		},
		[1.683] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.087, -0.464) * CFrame.Angles(math.rad(-10.657), 0, math.rad(11.287)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.301, 0.48, 0.071) * CFrame.Angles(math.rad(-9.282), math.rad(22.517), math.rad(10.199)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.247, -0.13, 0.074) * CFrame.Angles(math.rad(-9.167), math.rad(80.787), math.rad(87.204)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.371, -0.202, 0.478) * CFrame.Angles(math.rad(13.235), math.rad(81.074), math.rad(-85.199)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.186, 0.462, -0.017) * CFrame.Angles(math.rad(-14.209), math.rad(-16.157), math.rad(-8.995)),
					},
				},
			},
		},
		[1.7] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.093, -0.493) * CFrame.Angles(math.rad(-10.657), 0, math.rad(11.975)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.32, 0.51, 0.072) * CFrame.Angles(math.rad(-9.568), math.rad(24.007), math.rad(10.313)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.331, -0.1, 0.05) * CFrame.Angles(math.rad(25.955), math.rad(84.053), math.rad(47.727)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.411, -0.254, 0.551) * CFrame.Angles(math.rad(-24.064), math.rad(84.397), math.rad(-43.316)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.199, 0.489, -0.02) * CFrame.Angles(math.rad(-14.84), math.rad(-17.189), math.rad(-9.053)),
					},
				},
			},
		},
		[1.717] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.097, -0.514) * CFrame.Angles(math.rad(-10.657), 0, math.rad(12.49)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.335, 0.531, 0.073) * CFrame.Angles(math.rad(-9.798), math.rad(25.038), math.rad(10.428)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.395, -0.08, 0.028) * CFrame.Angles(math.rad(63.312), math.rad(83.652), math.rad(7.277)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.437, -0.296, 0.605) * CFrame.Angles(math.rad(-63.713), math.rad(83.824), math.rad(-0.401)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.209, 0.509, -0.022) * CFrame.Angles(math.rad(-15.241), math.rad(-17.934), math.rad(-9.11)),
					},
				},
			},
		},
		[1.733] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.099, -0.527) * CFrame.Angles(math.rad(-10.657), 0, math.rad(12.777)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.343, 0.544, 0.074) * CFrame.Angles(math.rad(-9.912), math.rad(25.669), math.rad(10.485)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.436, -0.069, 0.013) * CFrame.Angles(math.rad(79.24), math.rad(82.277), math.rad(-10.542)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.452, -0.323, 0.638) * CFrame.Angles(math.rad(-79.469), math.rad(82.334), math.rad(17.303)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.214, 0.521, -0.024) * CFrame.Angles(math.rad(-15.527), math.rad(-18.392), math.rad(-9.167)),
					},
				},
			},
		},
		[1.75] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.1, -0.531) * CFrame.Angles(math.rad(-10.657), 0, math.rad(12.892)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.346, 0.548, 0.074) * CFrame.Angles(math.rad(-9.969), math.rad(25.84), math.rad(10.485)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.449, -0.065, 0.008) * CFrame.Angles(math.rad(83.193), math.rad(81.704), math.rad(-15.126)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.457, -0.332, 0.649) * CFrame.Angles(math.rad(-83.193), math.rad(81.704), math.rad(21.772)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.216, 0.525, -0.024) * CFrame.Angles(math.rad(-15.642), math.rad(-18.564), math.rad(-9.167)),
					},
				},
			},
		},
		[1.767] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.099, -0.526) * CFrame.Angles(math.rad(-10.657), 0, math.rad(12.777)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.343, 0.543, 0.074) * CFrame.Angles(math.rad(-9.912), math.rad(25.611), math.rad(10.485)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.434, -0.069, 0.014) * CFrame.Angles(math.rad(78.667), math.rad(82.334), math.rad(-9.855)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.452, -0.321, 0.637) * CFrame.Angles(math.rad(-78.896), math.rad(82.391), math.rad(16.673)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.214, 0.52, -0.024) * CFrame.Angles(math.rad(-15.527), math.rad(-18.392), math.rad(-9.167)),
					},
				},
			},
		},
		[1.783] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.096, -0.512) * CFrame.Angles(math.rad(-10.657), 0, math.rad(12.433)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.333, 0.529, 0.073) * CFrame.Angles(math.rad(-9.74), math.rad(24.924), math.rad(10.428)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.388, -0.082, 0.031) * CFrame.Angles(math.rad(59.645), math.rad(83.824), math.rad(11.287)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.435, -0.291, 0.599) * CFrame.Angles(math.rad(-59.989), math.rad(84.053), math.rad(-4.469)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.208, 0.507, -0.022) * CFrame.Angles(math.rad(-15.241), math.rad(-17.876), math.rad(-9.11)),
					},
				},
			},
		},
		[1.8] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.092, -0.488) * CFrame.Angles(math.rad(-10.657), 0, math.rad(11.86)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.317, 0.505, 0.072) * CFrame.Angles(math.rad(-9.511), math.rad(23.72), math.rad(10.313)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.315, -0.105, 0.055) * CFrame.Angles(math.rad(17.246), math.rad(83.709), math.rad(57.181)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.404, -0.245, 0.538) * CFrame.Angles(math.rad(-14.61), math.rad(84.11), math.rad(-53.572)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.197, 0.484, -0.02) * CFrame.Angles(math.rad(-14.725), math.rad(-17.017), math.rad(-9.053)),
					},
				},
			},
		},
		[1.817] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.086, -0.455) * CFrame.Angles(math.rad(-10.657), 0, math.rad(11.058)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.295, 0.471, 0.07) * CFrame.Angles(math.rad(-9.225), math.rad(22.059), math.rad(10.199)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.222, -0.139, 0.08) * CFrame.Angles(math.rad(-14.61), math.rad(79.297), math.rad(93.965)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.359, -0.187, 0.455) * CFrame.Angles(math.rad(18.678), math.rad(79.527), math.rad(-92.074)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.182, 0.453, -0.016) * CFrame.Angles(math.rad(-13.98), math.rad(-15.814), math.rad(-8.995)),
					},
				},
			},
		},
		[1.833] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.078, -0.413) * CFrame.Angles(math.rad(-10.657), 0, math.rad(10.027)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.266, 0.427, 0.067) * CFrame.Angles(math.rad(-8.766), math.rad(19.939), math.rad(10.027)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.119, -0.183, 0.099) * CFrame.Angles(math.rad(-25.84), math.rad(71.677), math.rad(111.612)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.297, -0.127, 0.356) * CFrame.Angles(math.rad(29.393), math.rad(71.734), math.rad(-109.664)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.163, 0.412, -0.013) * CFrame.Angles(math.rad(-13.121), math.rad(-14.267), math.rad(-8.938)),
					},
				},
			},
		},
		[1.85] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.068, -0.361) * CFrame.Angles(math.rad(-10.657), 0, math.rad(8.766)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.232, 0.374, 0.062) * CFrame.Angles(math.rad(-8.308), math.rad(17.303), math.rad(9.855)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(0.017, -0.231, 0.103) * CFrame.Angles(math.rad(-28.476), math.rad(61.879), math.rad(122.326)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.221, -0.073, 0.248) * CFrame.Angles(math.rad(31.513), math.rad(61.708), math.rad(-120.321)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.141, 0.362, -0.009) * CFrame.Angles(math.rad(-11.975), math.rad(-12.376), math.rad(-8.824)),
					},
				},
			},
		},
		[1.867] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.056, -0.3) * CFrame.Angles(math.rad(-10.657), 0, math.rad(7.277)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.192, 0.311, 0.055) * CFrame.Angles(math.rad(-7.735), math.rad(14.209), math.rad(9.74)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.065, -0.273, 0.088) * CFrame.Angles(math.rad(-27.215), math.rad(50.191), math.rad(130.978)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.135, -0.034, 0.143) * CFrame.Angles(math.rad(29.679), math.rad(49.905), math.rad(-129.087)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.115, 0.302, -0.005) * CFrame.Angles(math.rad(-10.714), math.rad(-10.141), math.rad(-8.824)),
					},
				},
			},
		},
		[1.883] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.044, -0.231) * CFrame.Angles(math.rad(-10.657), 0, math.rad(5.615)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.148, 0.24, 0.046) * CFrame.Angles(math.rad(-7.162), math.rad(10.772), math.rad(9.568)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.11, -0.289, 0.056) * CFrame.Angles(math.rad(-23.434), math.rad(37.471), math.rad(139.286)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.055, -0.014, 0.058) * CFrame.Angles(math.rad(25.439), math.rad(37.07), math.rad(-137.682)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.088, 0.234, -0.001) * CFrame.Angles(math.rad(-9.282), math.rad(-7.678), math.rad(-8.881)),
					},
				},
			},
		},
		[1.9] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.032, -0.17) * CFrame.Angles(math.rad(-10.657), 0, math.rad(4.125)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.108, 0.177, 0.035) * CFrame.Angles(math.rad(-6.646), math.rad(7.678), math.rad(9.511)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.113, -0.268, 0.024) * CFrame.Angles(math.rad(-18.793), math.rad(26.471), math.rad(146.563)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(-0.003, -0.011, 0.01) * CFrame.Angles(math.rad(20.283), math.rad(26.012), math.rad(-145.245)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.063, 0.173, 0) * CFrame.Angles(math.rad(-8.021), math.rad(-5.443), math.rad(-8.938)),
					},
				},
			},
		},
		[1.917] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.022, -0.118) * CFrame.Angles(math.rad(-10.657), 0, math.rad(2.865)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.075, 0.123, 0.026) * CFrame.Angles(math.rad(-6.188), math.rad(5.099), math.rad(9.454)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.093, -0.22, 0.001) * CFrame.Angles(math.rad(-13.98), math.rad(17.647), math.rad(152.98)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.021, -0.012, -0.01) * CFrame.Angles(math.rad(15.069), math.rad(17.189), math.rad(-152.063)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.044, 0.12, 0.001) * CFrame.Angles(math.rad(-6.99), math.rad(-3.552), math.rad(-9.053)),
					},
				},
			},
		},
		[1.933] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.014, -0.075) * CFrame.Angles(math.rad(-10.657), 0, math.rad(1.833)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.048, 0.079, 0.017) * CFrame.Angles(math.rad(-5.844), math.rad(2.922), math.rad(9.454)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.065, -0.158, -0.009) * CFrame.Angles(math.rad(-9.454), math.rad(10.829), math.rad(158.652)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.026, -0.012, -0.014) * CFrame.Angles(math.rad(10.199), math.rad(10.485), math.rad(-158.022)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.028, 0.077, 0.001) * CFrame.Angles(math.rad(-6.073), math.rad(-2.005), math.rad(-9.167)),
					},
				},
			},
		},
		[1.95] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.008, -0.042) * CFrame.Angles(math.rad(-10.657), 0, math.rad(1.031)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.027, 0.044, 0.01) * CFrame.Angles(math.rad(-5.558), math.rad(1.261), math.rad(9.454)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.038, -0.097, -0.01) * CFrame.Angles(math.rad(-5.558), math.rad(5.901), math.rad(163.293)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.02, -0.009, -0.011) * CFrame.Angles(math.rad(5.959), math.rad(5.672), math.rad(-162.949)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.015, 0.044, 0.001) * CFrame.Angles(math.rad(-5.386), math.rad(-0.802), math.rad(-9.282)),
					},
				},
			},
		},
		[1.967] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.004, -0.019) * CFrame.Angles(math.rad(-10.657), 0, math.rad(0.458)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.012, 0.02, 0.005) * CFrame.Angles(math.rad(-5.386), math.rad(0.057), math.rad(9.397)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.017, -0.045, -0.006) * CFrame.Angles(math.rad(-2.578), math.rad(2.521), math.rad(166.845)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.011, -0.005, -0.006) * CFrame.Angles(math.rad(2.75), math.rad(2.406), math.rad(-166.673)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.007, 0.019, 0) * CFrame.Angles(math.rad(-4.927), math.rad(0.057), math.rad(-9.339)),
					},
				},
			},
		},
		[1.983] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.new(0, -0.001, -0.005) * CFrame.Angles(math.rad(-10.657), 0, math.rad(0.115)),
					["Left Leg"] = {
						CFrame = CFrame.new(-0.003, 0.005, 0.001) * CFrame.Angles(math.rad(-5.214), math.rad(-0.63), math.rad(9.397)),
					},
					["Right Arm"] = {
						CFrame = CFrame.new(-0.004, -0.012, -0.002) * CFrame.Angles(math.rad(-0.63), math.rad(0.63), math.rad(169.023)),
					},
					["Left Arm"] = {
						CFrame = CFrame.new(0.003, -0.001, -0.002) * CFrame.Angles(math.rad(0.688), math.rad(0.573), math.rad(-168.965)),
					},
					["Right Leg"] = {
						CFrame = CFrame.new(0.002, 0.005, 0) * CFrame.Angles(math.rad(-4.641), math.rad(0.573), math.rad(-9.397)),
					},
				},
			},
		},
		[2] = {
			["HumanoidRootPart"] = {
				["Torso"] = {
					CFrame = CFrame.Angles(math.rad(-10.657), 0, 0),
					["Left Leg"] = {
						CFrame = CFrame.Angles(math.rad(-5.214), math.rad(-0.859), math.rad(9.397)),
					},
					["Right Arm"] = {
						CFrame = CFrame.Angles(0, 0, math.rad(169.767)),
					},
					["Left Arm"] = {
						CFrame = CFrame.Angles(0, 0, math.rad(-169.767)),
					},
					["Right Leg"] = {
						CFrame = CFrame.Angles(math.rad(-4.526), math.rad(0.745), math.rad(-9.454)),
					},
				},
			},
		},
	}
	}

	local number=0

	LastTimeSetTotal=0
	local savec0 = {}


	GetAnimCF = function(limb,Time)

		local GA = nil
		coroutine.resume(coroutine.create(function()

			if limb == "Torso" then
				GA = Anim.Keyframes[Time]["HumanoidRootPart"]["Torso"].CFrame
			else
				GA = Anim.Keyframes[Time]["HumanoidRootPart"]["Torso"][""..limb].CFrame

			end
		end))
		return GA
	end



	local model = nil
	if owner ~= nil then 
		model = owner.Character
	else
		model = game:GetService("Players").localPlayer.Character
	end
	function GatherAllInstances(Parent)
		local Instances = {}
		local function GatherInstances(Parent)
			for i, v in pairs(Parent:GetChildren()) do
				GatherInstances(v)
				table.insert(Instances, v)
			end
		end
		GatherInstances(Parent)
		return Instances
	end




	for i, v in pairs(GatherAllInstances(model)) do
		if v:IsA("BasePart") then 
			for i, v2 in pairs(GatherAllInstances(model)) do
				if v2:IsA("Motor6D") and  v2.Part1.Name == v.Name then 

					local saveCF = v2.C0
					table.insert(savec0,{v2.Name,saveCF})

				end
			end
		end end




	RunAnim = function(Time)






		local speed = Time-LastTimeSetTotal

		speed = speed*AnimationSpeed
		LastTimeSetTotal = Time	



		local doing = true

		coroutine.resume(coroutine.create(function()
			for i, v in pairs(GatherAllInstances(model)) do
				if v:IsA("BasePart") then 
					for i, v2 in pairs(GatherAllInstances(model)) do
						if v2:IsA("Motor6D") and  v2.Part1.Name == v.Name then 

							local GotAnim = GetAnimCF(v.Name,Time)
							local saveCF = nil
							for i,v3 in pairs(savec0) do 
								if v2.name == v3[1] then
									saveCF = v3[2]
								end
							end


							if GotAnim ~= nil and saveCF ~= nil then


								coroutine.resume(coroutine.create(function()
									while doing == true do
										swait()
										v2.C0 = v2.C0:lerp(saveCF*GotAnim,SmoothTime *speed)
									end

								end))


							end

						end

					end
				end end


		end))
		wait(speed)
		doing = false
	end
	while true do
		RunAnim(0)	
		RunAnim(0.1)	
		RunAnim(0.2)
		RunAnim(0.3)
		RunAnim(0.4)
		RunAnim(0.5)
		RunAnim(0.6)
		RunAnim(0.7)
		RunAnim(0.8)
		RunAnim(0.9)
		RunAnim(1)

		LastTimeSetTotal = .1
		Humanoid.MaxHealth = "inf"
		Humanoid.Health = "inf"
		sick.SoundId = "rbxassetid://"
		sick.Looped = true
		sick.Pitch = 1
		sick.Volume = 10
		sick:Resume()
		sick.Parent = Torso
		refit()
	end
end)

HatFling.Name = "HatFling"
HatFling.Parent = main
HatFling.BackgroundColor3 = Color3.fromRGB(117, 117, 117)
HatFling.Position = UDim2.new(0.539583325, 0, 0.670250893, 0)
HatFling.Size = UDim2.new(0, 200, 0, 26)
HatFling.Font = Enum.Font.SpecialElite
HatFling.Text = "Hat Fling"
HatFling.TextColor3 = Color3.fromRGB(0, 0, 0)
HatFling.TextScaled = true
HatFling.TextSize = 14.000
HatFling.TextWrapped = true
HatFling.MouseButton1Down:connect(function()
	hats first to drop----------------
	for _,v in pairs(game:GetService("Players").LocalPlayer.Character:GetChildren()) do
		if v:IsA("Accessory") then
			v.Parent = workspace
		end
	end
	------------------------------------------------------------------------------------------------------------------------
	script its self:

	------------------------------------------------------------------------------------------------------------------------
	spawn(function()
		while true do game:GetService("RunService").Heartbeat:wait()
			for i,v in pairs(game.Players:GetPlayers()) do
				if v == game.Players.LocalPlayer == false then
					game.Players.LocalPlayer.MaximumSimulationRadius = math.pow(math.huge,math.huge)math.huge
					game.Players.LocalPlayer.SimulationRadius = math.pow(math.huge,math.huge)math.huge
					v.MaximumSimulationRadius = 0
					v.SimulationRadius = 0
					game:GetService("RunService").Stepped:wait()
				end
			end
		end
	end)

	local Player = game:GetService("Players").LocalPlayer
	local Players = game:GetService("Players")
	local HatList = {}
	local i = 0
	for ,l in pairs(Player.Character:GetChildren()) do
		if l:IsA("Accessory") then if i>0 then l.Parent = workspace  end i = i + 1 end;
	end
	wait(.1)



	for ,v in pairs(workspace:GetDescendants()) do
		if v.Name == "Handle" and v:IsA("BasePart") and v.Parent:IsA("Accessory") and v:IsDescendantOf(Player.Character)==false and Players:GetPlayerFromCharacter(v.Parent.Parent)==nil then
			table.insert(HatList,v)
		end
	end

	for _,hat in pairs(HatList) do
		hat.Parent = workspace
		hat.Position = Player.Character.HumanoidRootPart.Position + Player.Character.HumanoidRootPart.CFrame.lookVector * 5
		local BodyPos = Instance.new("BodyPosition",hat)
		local BodyAng = Instance.new("BodyAngularVelocity",hat)
		BodyAng.AngularVelocity = Vector3.new(0,9e12,0)
		BodyAng.P = 9e12
		BodyPos.MaxForce = Vector3.new(9e9,9e9,9e9)
		BodyPos.P = 9e8
		spawn(function()
			while wait() do
				if pcall(function()
						hat.CanCollide = false
						BodyPos.Position = Player.Character.HumanoidRootPart.Position + Vector3.new(math.random(-2,2),math.random(-2,2),math.random(-2,2))
					end) then
				else
					BodyPos:Destroy()
					hat.CanCollide = true
				end
			end
		end)

	end
end)

SlapScript.Name = "Slap Script"
SlapScript.Parent = main
SlapScript.BackgroundColor3 = Color3.fromRGB(104, 104, 104)
SlapScript.Position = UDim2.new(0.0458333343, 0, 0.792114675, 0)
SlapScript.Size = UDim2.new(0, 224, 0, 32)
SlapScript.Font = Enum.Font.SpecialElite
SlapScript.Text = "Fe Slap Script"
SlapScript.TextColor3 = Color3.fromRGB(0, 0, 0)
SlapScript.TextScaled = true
SlapScript.TextSize = 14.000
SlapScript.TextWrapped = true
SlapScript.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/YPZ0wNaw'),true))()
end)

VrScript.Name = "Vr Script"
VrScript.Parent = main
VrScript.BackgroundColor3 = Color3.fromRGB(102, 102, 102)
VrScript.Position = UDim2.new(0.539583325, 0, 0.788530469, 0)
VrScript.Size = UDim2.new(0, 200, 0, 33)
VrScript.Font = Enum.Font.SpecialElite
VrScript.Text = "Vr Script"
VrScript.TextColor3 = Color3.fromRGB(0, 0, 0)
VrScript.TextScaled = true
VrScript.TextSize = 14.000
VrScript.TextWrapped = true
VrScript.MouseButton1Down:connect(function()
	-- CLOVR - FE FULL-BODY VR SCRIPT

	-- April 21st Update - TOOL HOLDING ADDED

	-- | made by 0866 and Abacaxl
	-- | tysm unverified
	-- | Fixed By Gabriellogin#7714

	--RagDollEnabled is set to true, DON'T set it to false or CLOVR won't work. Feel free to change the other settings though.
	spawn(function()
		while wait() do
			sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
			sethiddenproperty(game.Players.LocalPlayer, "MaximumSimulationRadius", math.huge)
		end
	end)

	--|| Settings:
	local StudsOffset = 0 -- Character height (negative if you're too high)
	local Smoothness = .5 -- Character interpolation (0.1 - 1 = smooth - rigid)
	local AnchorCharacter = true -- Prevent physics from causing inconsistencies
	local HideCharacter = false -- Hide character on a platform
	local NoCollision = true -- Disable player collision
	local ChatEnabled = true -- See chat on your left hand in-game
	local ChatLocalRange = 75 -- Local chat range
	local ViewportEnabled = true -- View nearby players in a frame
	local ViewportRange = 30 -- Maximum distance players are updated
	local RagdollEnabled = true -- Use your character instead of hats (NetworkOwner vulnerability)
	local RagdollHeadMovement = true -- Move your head separately from your body (+9 second wait)
	local AutoRun = false -- Run script on respawn
	local AutoRespawn = true -- Kill your real body when your virtual body dies
	local WearAllAccessories = false -- Use all leftover hats for the head
	local AccurateHandPosition = true -- Move your Roblox hands according to your real hands
	local AccessorySettings = {
		LeftArm = "";
		RightArm = "";
		LeftLeg = "";
		RightLeg = "";
		Torso = "";
		Head = true;
		BlockArms = true;
		BlockLegs = true;
		BlockTorso = true;
		LimbOffset = CFrame.Angles(math.rad(90), 0, 0);
	}
	local FootPlacementSettings = {
		RightOffset = Vector3.new(.5, 0, 0),
		LeftOffset = Vector3.new(-.5, 0, 0),
	}
	--|| Script:
	local Script = nil;
	Script = function()
--[[
 Variables
--]]
		local Players = game:GetService("Players")
		local Client = Players.LocalPlayer
		local Character = Client.Character or Client.CharacterAdded:Wait()
		local WeldBase = Character:WaitForChild("HumanoidRootPart")
		local ArmBase = Character:FindFirstChild("RightHand") or Character:FindFirstChild("Right Arm") or WeldBase
		local Backpack = Client:WaitForChild("Backpack")
		local Mouse = Client:GetMouse()
		local Camera = workspace.CurrentCamera
		local VRService = game:GetService("VRService")
		local VRReady = VRService.VREnabled
		local UserInputService = game:GetService("UserInputService")
		local RunService = game:GetService("RunService")
		local HttpService = game:GetService("HttpService")
		local StarterGui = game:GetService("StarterGui")
		local HeadAccessories = {};
		local UsedAccessories = {};
		local Pointer = false;
		local Point1 = false;
		local Point2 = false;
		local VirtualRig = game:GetObjects("rbxassetid://4468539481")[1]
		local VirtualBody = game:GetObjects("rbxassetid://4464983829")[1]
		local Anchor = Instance.new("Part")
		Anchor.Anchored = true
		Anchor.Transparency = 1
		Anchor.CanCollide = false
		Anchor.Parent = workspace
		if RagdollEnabled then
			print("RagdollEnabled, thank you for using CLOVR!")
			local NetworkAccess = coroutine.create(function()
				settings().Physics.AllowSleep = false
				while true do game:GetService("RunService").RenderStepped:Wait()
					for _,Players in next, game:GetService("Players"):GetChildren() do
						if Players ~= game:GetService("Players").LocalPlayer then
							Players.MaximumSimulationRadius = 0.1 Players.SimulationRadius = 0 end end
					sethiddenproperty(game.Players.LocalPlayer, "MaximumSimulationRadius", math.huge)
					game:GetService("Players").LocalPlayer.SimulationRadius = math.huge*math.huge end end)
			coroutine.resume(NetworkAccess)
		end
--[[
 Character Protection
--]]
		local CharacterCFrame = WeldBase.CFrame
		if not RagdollEnabled then
			Character.Humanoid.AnimationPlayed:Connect(function(Animation)
				Animation:Stop()
			end)
			for _, Track in next, Character.Humanoid:GetPlayingAnimationTracks() do
				Track:Stop()
			end
			if HideCharacter then
				local Platform = Instance.new("Part")
				Platform.Anchored = true
				Platform.Size = Vector3.new(100, 5, 100)
				Platform.CFrame = CFrame.new(0, 10000, 0)
				Platform.Transparency = 1
				Platform.Parent = workspace
				Character:MoveTo(Platform.Position + Vector3.new(0, 5, 0))
				wait(.5)
			end
			if AnchorCharacter then
				for _, Part in pairs(Character:GetChildren()) do
					if Part:IsA("BasePart") then
						Part.Anchored = true
					end
				end
			end
		end
--[[
 Functions
--]]
		function Tween(Object, Style, Direction, Time, Goal)
			local tweenInfo = TweenInfo.new(Time, Enum.EasingStyle[Style], Enum.EasingDirection[Direction])
			local tween = game:GetService("TweenService"):Create(Object, tweenInfo, Goal)
			tween.Completed:Connect(function()
				tween:Destroy()
			end)
			tween:Play()
			return tween
		end
		local function GetMotorForLimb(Limb)
			for _, Motor in next, Character:GetDescendants() do
				if Motor:IsA("Motor6D") and Motor.Part1 == Limb then
					return Motor
				end
			end
		end
		local function CreateAlignment(Limb, Part0)
			local Attachment0 = Instance.new("Attachment", Part0 or Anchor)
			local Attachment1 = Instance.new("Attachment", Limb)
			local Orientation = Instance.new("AlignOrientation")
			local Position = Instance.new("AlignPosition")
			Orientation.Attachment0 = Attachment1
			Orientation.Attachment1 = Attachment0
			Orientation.RigidityEnabled = false
			Orientation.MaxTorque = 20000
			Orientation.Responsiveness = 40
			Orientation.Parent = Character.HumanoidRootPart
			Position.Attachment0 = Attachment1
			Position.Attachment1 = Attachment0
			Position.RigidityEnabled = false
			Position.MaxForce = 40000
			Position.Responsiveness = 40
			Position.Parent = Character.HumanoidRootPart
			Limb.Massless = false
			local Motor = GetMotorForLimb(Limb)
			if Motor then
				Motor:Destroy()
			end
			return function(CF, Local)
				if Local then
					Attachment0.CFrame = CF
				else
					Attachment0.WorldCFrame = CF
				end
			end;
		end
		local function GetExtraTool()
			for _, Tool in next, Character:GetChildren() do
				if Tool:IsA("Tool") and not Tool.Name:match("LIMB_TOOL") then
					return Tool
				end
			end
		end
		local function GetGripForHandle(Handle)
			for _, Weld in next, Character:GetDescendants() do
				if Weld:IsA("Weld") and (Weld.Part0 == Handle or Weld.Part1 == Handle) then
					return Weld
				end
			end
			wait(.2)
			for _, Weld in next, Character:GetDescendants() do
				if Weld:IsA("Weld") and (Weld.Part0 == Handle or Weld.Part1 == Handle) then
					return Weld
				end
			end
		end
		local function CreateRightGrip(Handle)
			local RightGrip = Instance.new("Weld")
			RightGrip.Name = "RightGrip"
			RightGrip.Part1 = Handle
			RightGrip.Part0 = WeldBase
			RightGrip.Parent = WeldBase
			return RightGrip
		end
		local function CreateAccessory(Accessory, DeleteMeshes)
			if not Accessory then
				return
			end
			local HatAttachment = Accessory.Handle:FindFirstChildWhichIsA("Attachment")
			local HeadAttachment = VirtualRig:FindFirstChild(HatAttachment.Name, true)
			local BasePart = HeadAttachment.Parent
			local HatAtt = HatAttachment.CFrame
			local HeadAtt = HeadAttachment.CFrame
			if DeleteMeshes then
				if Accessory.Handle:FindFirstChild("Mesh") then
					Accessory.Handle.Mesh:Destroy()
				end
			end
			wait()
			local Handle = Accessory:WaitForChild("Handle")
			if Handle:FindFirstChildWhichIsA("Weld", true) then
				Handle:FindFirstChildWhichIsA("Weld", true):Destroy()
				Handle:BreakJoints()
			else
				Handle:BreakJoints()
			end
			Handle.Massless = true
			Handle.Transparency = 0.5
			UsedAccessories[Accessory] = true
			local RightGrip = CreateRightGrip(Handle)
			wait()
			for _, Object in pairs(Handle:GetDescendants()) do
				if not Object:IsA("BasePart") then
					pcall(function()
						Object.Transparency = 1
					end)
					pcall(function()
						Object.Enabled = false
					end)
				end
			end
			return Handle, RightGrip, HatAtt, HeadAtt, BasePart;
		end
		local function GetHeadAccessories()
			for _, Accessory in next, Character:GetChildren() do
				if Accessory:IsA("Accessory") and not UsedAccessories[Accessory] then
					local Handle, RightGrip, HatAtt, HeadAtt, BasePart = CreateAccessory(Accessory)
					table.insert(HeadAccessories, {Handle, RightGrip, HatAtt, HeadAtt, BasePart})
					do
						Handle.Transparency = 1
					end
					if not WearAllAccessories then
						break
					end
				end
			end
		end
--[[
 VR Replication Setup
--]]
		if not RagdollEnabled then
			LeftHandle, LeftHandGrip = CreateAccessory(Character:FindFirstChild(AccessorySettings.LeftArm), AccessorySettings.BlockArms)
			RightHandle, RightHandGrip = CreateAccessory(Character:FindFirstChild(AccessorySettings.RightArm), AccessorySettings.BlockArms)
			LeftHipHandle, LeftLegGrip = CreateAccessory(Character:FindFirstChild(AccessorySettings.LeftLeg), AccessorySettings.BlockLegs)
			RightHipHandle, RightLegGrip = CreateAccessory(Character:FindFirstChild(AccessorySettings.RightLeg), AccessorySettings.BlockLegs)
			TorsoHandle, TorsoGrip = CreateAccessory(Character:FindFirstChild(AccessorySettings.Torso), AccessorySettings.BlockTorso)
			GetHeadAccessories()
		elseif RagdollEnabled then
			if RagdollHeadMovement then
				Permadeath()
				MoveHead = CreateAlignment(Character["Head"])
			end
			MoveRightArm = CreateAlignment(Character["Right Arm"])
			MoveLeftArm = CreateAlignment(Character["Left Arm"])
			MoveRightLeg = CreateAlignment(Character["Right Leg"])
			MoveLeftLeg = CreateAlignment(Character["Left Leg"])
			MoveTorso = CreateAlignment(Character["Torso"])
			MoveRoot = CreateAlignment(Character.HumanoidRootPart)
			if RagdollHeadMovement then
				for _, Accessory in next, Character:GetChildren() do
					if Accessory:IsA("Accessory") and Accessory:FindFirstChild("Handle") then
						local Attachment1 = Accessory.Handle:FindFirstChildWhichIsA("Attachment")
						local Attachment0 = Character:FindFirstChild(tostring(Attachment1), true)
						local Orientation = Instance.new("AlignOrientation")
						local Position = Instance.new("AlignPosition")
						print(Attachment1, Attachment0, Accessory)
						Orientation.Attachment0 = Attachment1
						Orientation.Attachment1 = Attachment0
						Orientation.RigidityEnabled = false
						Orientation.ReactionTorqueEnabled = true
						Orientation.MaxTorque = 20000
						Orientation.Responsiveness = 40
						Orientation.Parent = Character.Head
						Position.Attachment0 = Attachment1
						Position.Attachment1 = Attachment0
						Position.RigidityEnabled = false
						Position.ReactionForceEnabled = true
						Position.MaxForce = 40000
						Position.Responsiveness = 40
						Position.Parent = Character.Head
					end
				end
			end
		end
--[[
 Movement
--]]
		VirtualRig.Name = "VirtualRig"
		VirtualRig.RightFoot.BodyPosition.Position = CharacterCFrame.p
		VirtualRig.LeftFoot.BodyPosition.Position = CharacterCFrame.p
		VirtualRig.Parent = workspace
		VirtualRig:SetPrimaryPartCFrame(CharacterCFrame)
		VirtualRig.Humanoid.Health = 0
		VirtualRig:BreakJoints()
		--
		VirtualBody.Parent = workspace
		VirtualBody.Name = "VirtualBody"
		VirtualBody.Humanoid.WalkSpeed = 24
		VirtualBody.Humanoid.CameraOffset = Vector3.new(0, StudsOffset, 0)
		VirtualBody:SetPrimaryPartCFrame(CharacterCFrame)
		VirtualBody.Humanoid.Died:Connect(function()
			print("Virtual death")
			if AutoRespawn then
				Character:BreakJoints()
				if RagdollHeadMovement and RagdollEnabled then
					Network:Unclaim()
					Respawn()
				end
			end
		end)
		--
		Camera.CameraSubject = VirtualBody.Humanoid
		Character.Humanoid.WalkSpeed = 0
		Character.Humanoid.JumpPower = 1
		for _, Part in next, VirtualBody:GetChildren() do
			if Part:IsA("BasePart") then
				Part.Transparency = 1
			end
		end
		for _, Part in next, VirtualRig:GetChildren() do
			if Part:IsA("BasePart") then
				Part.Transparency = 1
			end
		end
		if not VRReady then
			VirtualRig.RightUpperArm.ShoulderConstraint.RigidityEnabled = true
			VirtualRig.LeftUpperArm.ShoulderConstraint.RigidityEnabled = true
		end
		local OnMoving = RunService.Stepped:Connect(function()
			local Direction = Character.Humanoid.MoveDirection
			local Start = VirtualBody.HumanoidRootPart.Position
			local Point = Start + Direction * 6
			VirtualBody.Humanoid:MoveTo(Point)
		end)
		Character.Humanoid.Jumping:Connect(function()
			VirtualBody.Humanoid.Jump = true
		end)
		UserInputService.JumpRequest:Connect(function()
			VirtualBody.Humanoid.Jump = true
		end)
--[[
 VR Replication
--]]
		if RagdollEnabled then
			for _, Part in pairs(Character:GetDescendants()) do
				if Part:IsA("BasePart") and Part.Name == "Handle" and Part.Parent:IsA("Accessory") then
					Part.LocalTransparencyModifier = 1
				elseif Part:IsA("BasePart") and Part.Transparency < 0.5 and Part.Name ~= "Head" then
					Part.LocalTransparencyModifier = 0.5
				elseif Part:IsA("BasePart") and Part.Name == "Head" then
					Part.LocalTransparencyModifier = 1
				end
				if not Part:IsA("BasePart") and not Part:IsA("AlignPosition") and not Part:IsA("AlignOrientation") then
					pcall(function()
						Part.Transparency = 1
					end)
					pcall(function()
						Part.Enabled = false
					end)
				end
			end
		end
		local FootUpdateDebounce = tick()
		local function FloorRay(Part, Distance)
			local Position = Part.CFrame.p
			local Target = Position - Vector3.new(0, Distance, 0)
			local Line = Ray.new(Position, (Target - Position).Unit * Distance)
			local FloorPart, FloorPosition, FloorNormal = workspace:FindPartOnRayWithIgnoreList(Line, {VirtualRig, VirtualBody, Character})
			if FloorPart then
				return FloorPart, FloorPosition, FloorNormal, (FloorPosition - Position).Magnitude
			else
				return nil, Target, Vector3.new(), Distance
			end
		end
		local function Flatten(CF)
			local X,Y,Z = CF.X,CF.Y,CF.Z
			local LX,LZ = CF.lookVector.X,CF.lookVector.Z
			return CFrame.new(X,Y,Z) * CFrame.Angles(0,math.atan2(LX,LZ),0)
		end
		local FootTurn = 1
		local function FootReady(Foot, Target)
			local MaxDist
			if Character.Humanoid.MoveDirection.Magnitude > 0 then
				MaxDist = .5
			else
				MaxDist = 1
			end
			local PastThreshold = (Foot.Position - Target.Position).Magnitude > MaxDist
			local PastTick = tick() - FootUpdateDebounce >= 2
			if PastThreshold or PastTick then
				FootUpdateDebounce = tick()
			end
			return
				PastThreshold
				or
				PastTick
		end
		local function FootYield()
			local RightFooting = VirtualRig.RightFoot.BodyPosition
			local LeftFooting = VirtualRig.LeftFoot.BodyPosition
			local LowerTorso = VirtualRig.LowerTorso
			local Yield = tick()
			repeat
				RunService.Stepped:Wait()
				if
					(LowerTorso.Position - RightFooting.Position).Y > 4
						or
						(LowerTorso.Position - LeftFooting.Position).Y > 4
						or
						((LowerTorso.Position - RightFooting.Position) * Vector3.new(1, 0, 1)).Magnitude > 4
						or
						((LowerTorso.Position - LeftFooting.Position) * Vector3.new(1, 0, 1)).Magnitude > 4
				then
					break
				end
			until tick() - Yield >= .17
		end
		local function UpdateFooting()
			if not VirtualRig:FindFirstChild("LowerTorso") then
				wait()
				return
			end
			local Floor, FloorPosition, FloorNormal, Dist = FloorRay(VirtualRig.LowerTorso, 3)
			Dist = math.clamp(Dist, 0, 5)
			local FootTarget =
				VirtualRig.LowerTorso.CFrame *
				CFrame.new(FootPlacementSettings.RightOffset) -
				Vector3.new(0, Dist, 0) +
				Character.Humanoid.MoveDirection * (VirtualBody.Humanoid.WalkSpeed / 8) * 2
			if FootReady(VirtualRig.RightFoot, FootTarget) then
				VirtualRig.RightFoot.BodyPosition.Position = FootTarget.p
				VirtualRig.RightFoot.BodyGyro.CFrame = Flatten(VirtualRig.LowerTorso.CFrame)
			end
			FootYield()
			local FootTarget =
				VirtualRig.LowerTorso.CFrame *
				CFrame.new(FootPlacementSettings.LeftOffset) -
				Vector3.new(0, Dist, 0) +
				Character.Humanoid.MoveDirection * (VirtualBody.Humanoid.WalkSpeed / 8) * 2
			if FootReady(VirtualRig.LeftFoot, FootTarget) then
				VirtualRig.LeftFoot.BodyPosition.Position = FootTarget.p
				VirtualRig.LeftFoot.BodyGyro.CFrame = Flatten(VirtualRig.LowerTorso.CFrame)
			end
		end
		local function UpdateTorsoPosition()
			if not RagdollEnabled then
				if TorsoHandle then
					local Positioning = VirtualRig.UpperTorso.CFrame
					if not TorsoGrip or not TorsoGrip.Parent then
						TorsoGrip = CreateRightGrip(TorsoHandle)
					end
					local Parent = TorsoGrip.Parent
					TorsoGrip.C1 = CFrame.new()
					TorsoGrip.C0 = TorsoGrip.C0:Lerp(WeldBase.CFrame:ToObjectSpace(Positioning * CFrame.new(0, -0.25, 0) * AccessorySettings.LimbOffset), Smoothness)
					TorsoGrip.Parent = nil
					TorsoGrip.Parent = Parent
				end
			else
				local Positioning = VirtualRig.UpperTorso.CFrame
				MoveTorso(Positioning * CFrame.new(0, -0.25, 0))
				MoveRoot(Positioning * CFrame.new(0, -0.25, 0))
			end
		end
		local function UpdateLegPosition()
			if not RagdollEnabled then
				if RightHipHandle then
					local Positioning =
						VirtualRig.RightLowerLeg.CFrame
					: Lerp(VirtualRig.RightFoot.CFrame, 0.5)
						+ Vector3.new(0, 0.5, 0)
					if not RightHipHandle or not RightHipHandle.Parent then
						RightLegGrip = CreateRightGrip(RightHipHandle)
					end
					local Parent = RightLegGrip.Parent
					RightLegGrip.C1 = CFrame.new()
					RightLegGrip.C0 = RightLegGrip.C0:Lerp(WeldBase.CFrame:ToObjectSpace(Positioning * AccessorySettings.LimbOffset), Smoothness)
					RightLegGrip.Parent = nil
					RightLegGrip.Parent = Parent
				end
				if LeftHipHandle then
					local Positioning =
						VirtualRig.LeftLowerLeg.CFrame
					: Lerp(VirtualRig.LeftFoot.CFrame, 0.5)
						+ Vector3.new(0, 0.5, 0)
					if not LeftLegGrip or not LeftLegGrip.Parent then
						LeftLegGrip = CreateRightGrip(LeftHipHandle)
					end
					local Parent = LeftLegGrip.Parent
					LeftLegGrip.C1 = CFrame.new()
					LeftLegGrip.C0 = LeftLegGrip.C0:Lerp(WeldBase.CFrame:ToObjectSpace(Positioning * AccessorySettings.LimbOffset), Smoothness)
					LeftLegGrip.Parent = nil
					LeftLegGrip.Parent = Parent
				end
			else
				do
					local Positioning =
						VirtualRig.RightLowerLeg.CFrame
					: Lerp(VirtualRig.RightFoot.CFrame, 0.5)
						* CFrame.Angles(0, math.rad(180), 0)
						+ Vector3.new(0, 0.5, 0)
					MoveRightLeg(Positioning)
				end
				do
					local Positioning =
						VirtualRig.LeftLowerLeg.CFrame
					: Lerp(VirtualRig.LeftFoot.CFrame, 0.5)
						* CFrame.Angles(0, math.rad(180), 0)
						+ Vector3.new(0, 0.5, 0)
					MoveLeftLeg(Positioning)
				end
			end
		end
		warn("VRReady is", VRReady)
		local function OnUserCFrameChanged(UserCFrame, Positioning, IgnoreTorso)
			local Positioning = Camera.CFrame * Positioning
			if not IgnoreTorso then
				UpdateTorsoPosition()
				UpdateLegPosition()
			end
			if not RagdollEnabled then
				if UserCFrame == Enum.UserCFrame.Head and AccessorySettings.Head then
					for _, Table in next, HeadAccessories do
						local Handle, RightGrip, HatAtt, HeadAtt, BasePart = unpack(Table)
						local LocalPositioning = Positioning
						if not RightGrip or not RightGrip.Parent then
							RightGrip = CreateRightGrip(Handle)
							Table[2] = RightGrip
						end
						local Parent = RightGrip.Parent
						if BasePart then
							LocalPositioning = BasePart.CFrame * HeadAtt
						end
						RightGrip.C1 = HatAtt
						RightGrip.C0 = RightGrip.C0:Lerp(WeldBase.CFrame:ToObjectSpace(LocalPositioning), Smoothness)
						RightGrip.Parent = nil
						RightGrip.Parent = Parent
					end
				elseif RightHandle and UserCFrame == Enum.UserCFrame.RightHand and AccessorySettings.RightArm then
					local HandPosition = Positioning
					local LocalPositioning = Positioning
					if not RightHandGrip or not RightHandGrip.Parent then
						RightHandGrip = CreateRightGrip(RightHandle)
					end
					if AccurateHandPosition then
						HandPosition = HandPosition * CFrame.new(0, 0, 1)
					end
					if not VRReady then
						local HeadRotation = Camera.CFrame - Camera.CFrame.p
						HandPosition = VirtualRig.RightUpperArm.CFrame:Lerp(VirtualRig.RightLowerArm.CFrame, 0.5) * AccessorySettings.LimbOffset
						--LocalPositioning = (HeadRotation + (HandPosition * CFrame.new(0, 0, 1)).p) * CFrame.Angles(math.rad(-45), 0, 0)
						LocalPositioning = HandPosition * CFrame.new(0, 0, 1) * CFrame.Angles(math.rad(-180), 0, 0)
						if Point2 then
							VirtualRig.RightUpperArm.Aim.MaxTorque = Vector3.new(math.huge, math.huge, math.huge)
							VirtualRig.RightUpperArm.Aim.CFrame = Camera.CFrame * AccessorySettings.LimbOffset
						elseif VirtualRig.RightUpperArm.Aim.MaxTorque ~= Vector3.new(0, 0, 0) then
							VirtualRig.RightUpperArm.Aim.MaxTorque = Vector3.new(0, 0, 0)
						end
					elseif AccurateHandPosition then
						LocalPositioning = HandPosition
					end
					local Parent = RightHandGrip.Parent
					RightHandGrip.C1 = CFrame.new()
					RightHandGrip.C0 = RightHandGrip.C0:Lerp(WeldBase.CFrame:ToObjectSpace(HandPosition), Smoothness)
					RightHandGrip.Parent = nil
					RightHandGrip.Parent = Parent
					--
					local EquippedTool = GetExtraTool()
					if EquippedTool and EquippedTool:FindFirstChild("Handle") then
						local EquippedGrip = GetGripForHandle(EquippedTool.Handle)
						local Parent = EquippedGrip.Parent
						local ArmBaseCFrame = ArmBase.CFrame
						if ArmBase.Name == "Right Arm" then
							ArmBaseCFrame = ArmBaseCFrame
						end
						EquippedGrip.C1 = EquippedTool.Grip
						EquippedGrip.C0 = EquippedGrip.C0:Lerp(ArmBaseCFrame:ToObjectSpace(LocalPositioning), Smoothness)
						EquippedGrip.Parent = nil
						EquippedGrip.Parent = Parent
					end
				elseif LeftHandle and UserCFrame == Enum.UserCFrame.LeftHand and AccessorySettings.LeftArm then
					local HandPosition = Positioning
					if not LeftHandGrip or not LeftHandGrip.Parent then
						LeftHandGrip = CreateRightGrip(LeftHandle)
					end
					if AccurateHandPosition then
						HandPosition = HandPosition * CFrame.new(0, 0, 1)
					end
					if not VRReady then
						HandPosition = VirtualRig.LeftUpperArm.CFrame:Lerp(VirtualRig.LeftLowerArm.CFrame, 0.5) * AccessorySettings.LimbOffset
						--warn("Setting HandPosition to hands")
						if Point1 then
							VirtualRig.LeftUpperArm.Aim.MaxTorque = Vector3.new(math.huge, math.huge, math.huge)
							VirtualRig.LeftUpperArm.Aim.CFrame = Camera.CFrame * AccessorySettings.LimbOffset
						elseif VirtualRig.LeftUpperArm.Aim.MaxTorque ~= Vector3.new(0, 0, 0) then
							VirtualRig.LeftUpperArm.Aim.MaxTorque = Vector3.new(0, 0, 0)
						end
					end
					local Parent = LeftHandGrip.Parent
					LeftHandGrip.C1 = CFrame.new()
					LeftHandGrip.C0 = LeftHandGrip.C0:Lerp(WeldBase.CFrame:ToObjectSpace(HandPosition), Smoothness)
					LeftHandGrip.Parent = nil
					LeftHandGrip.Parent = Parent
				end
			end
			if RagdollEnabled then
				if UserCFrame == Enum.UserCFrame.Head and RagdollHeadMovement then
					MoveHead(Positioning)
				elseif UserCFrame == Enum.UserCFrame.RightHand then
					local Positioning = Positioning
					if not VRReady then
						Positioning = VirtualRig.RightUpperArm.CFrame:Lerp(VirtualRig.RightLowerArm.CFrame, 0.5)
					elseif AccurateHandPosition then
						Positioning = Positioning * CFrame.new(0, 0, 1)
					end
					if VRReady then
						Positioning = Positioning * AccessorySettings.LimbOffset
					end
					MoveRightArm(Positioning)
					if Point2 then
						VirtualRig.RightUpperArm.Aim.MaxTorque = Vector3.new(math.huge, math.huge, math.huge)
						VirtualRig.RightUpperArm.Aim.CFrame = Camera.CFrame * AccessorySettings.LimbOffset
					elseif VirtualRig.RightUpperArm.Aim.MaxTorque ~= Vector3.new(0, 0, 0) then
						VirtualRig.RightUpperArm.Aim.MaxTorque = Vector3.new(0, 0, 0)
					end
				elseif UserCFrame == Enum.UserCFrame.LeftHand then
					local Positioning = Positioning
					if not VRReady then
						Positioning = VirtualRig.LeftUpperArm.CFrame:Lerp(VirtualRig.LeftLowerArm.CFrame, 0.5)
					elseif AccurateHandPosition then
						Positioning = Positioning * CFrame.new(0, 0, 1)
					end
					if VRReady then
						Positioning = Positioning * AccessorySettings.LimbOffset
					end
					MoveLeftArm(Positioning)
					if Point1 then
						VirtualRig.LeftUpperArm.Aim.MaxTorque = Vector3.new(math.huge, math.huge, math.huge)
						VirtualRig.LeftUpperArm.Aim.CFrame = Camera.CFrame * AccessorySettings.LimbOffset
					elseif VirtualRig.LeftUpperArm.Aim.MaxTorque ~= Vector3.new(0, 0, 0) then
						VirtualRig.LeftUpperArm.Aim.MaxTorque = Vector3.new(0, 0, 0)
					end
				end
			end
			if UserCFrame == Enum.UserCFrame.Head then
				VirtualRig.Head.CFrame = Positioning
			elseif UserCFrame == Enum.UserCFrame.RightHand and VRReady then
				VirtualRig.RightHand.CFrame = Positioning
			elseif UserCFrame == Enum.UserCFrame.LeftHand and VRReady then
				VirtualRig.LeftHand.CFrame = Positioning
			end
			if not VRReady and VirtualRig.LeftHand.Anchored then
				VirtualRig.RightHand.Anchored = false
				VirtualRig.LeftHand.Anchored = false
			elseif VRReady and not VirtualRig.LeftHand.Anchored then
				VirtualRig.RightHand.Anchored = true
				VirtualRig.LeftHand.Anchored = true
			end
		end
		local CFrameChanged = VRService.UserCFrameChanged:Connect(OnUserCFrameChanged)
		local OnStepped = RunService.Stepped:Connect(function()
			for _, Part in pairs(VirtualRig:GetChildren()) do
				if Part:IsA("BasePart") then
					Part.CanCollide = false
				end
			end
			if RagdollEnabled then
				for _, Part in pairs(Character:GetChildren()) do
					if Part:IsA("BasePart") then
						Part.CanCollide = false
					end
				end
			end
			if NoCollision then
				for _, Player in pairs(Players:GetPlayers()) do
					if Player ~= Client and Player.Character then
						local Descendants = Player.Character:GetDescendants()
						for i = 1, #Descendants do
							local Part = Descendants[i]
							if Part:IsA("BasePart") then
								Part.CanCollide = false
								Part.Velocity = Vector3.new()
								Part.RotVelocity = Vector3.new()
							end
						end
					end
				end
			end
		end)
		local OnRenderStepped = RunService.Stepped:Connect(function()
			Camera.CameraSubject = VirtualBody.Humanoid
			if RagdollEnabled then
				Character.HumanoidRootPart.CFrame = VirtualRig.UpperTorso.CFrame
				Character.HumanoidRootPart.Velocity = Vector3.new(0, 0, 0)
			end
			if not VRReady then
				OnUserCFrameChanged(Enum.UserCFrame.Head, CFrame.new(0, 0, 0))
				OnUserCFrameChanged(Enum.UserCFrame.RightHand, CFrame.new(0, 0, 0), true)
				OnUserCFrameChanged(Enum.UserCFrame.LeftHand, CFrame.new(0, 0, 0), true)
			end
		end)
		spawn(function()
			while Character and Character.Parent do
				FootYield()
				UpdateFooting()
			end
		end)
--[[
 Non-VR Support + VR Mechanics
--]]
		local OnInput = UserInputService.InputBegan:Connect(function(Input, Processed)
			if not Processed then
				if Input.KeyCode == Enum.KeyCode.LeftControl or Input.KeyCode == Enum.KeyCode.ButtonL2 then
					Tween(VirtualBody.Humanoid, "Elastic", "Out", 1, {
						CameraOffset = Vector3.new(0, StudsOffset - 1.5, 0)
					})
				end
				if Input.KeyCode == Enum.KeyCode.X then
					if RagdollEnabled and RagdollHeadMovement then
						Network:Unclaim()
						Respawn()
					end
				end
				if Input.KeyCode == Enum.KeyCode.C then
					VirtualBody:MoveTo(Mouse.Hit.p)
					VirtualRig:MoveTo(Mouse.Hit.p)
				end
			end
			if Input.KeyCode == Enum.KeyCode.LeftShift or Input.KeyCode == Enum.KeyCode.ButtonR2 then
				Tween(VirtualBody.Humanoid, "Sine", "Out", 1, {
					WalkSpeed = 24
				})
			end
			if not VRReady and Input.UserInputType == Enum.UserInputType.MouseButton1 then
				Point1 = true
			end
			if not VRReady and Input.UserInputType == Enum.UserInputType.MouseButton2 then
				Point2 = true
			end
			if VRReady and Input.KeyCode == Enum.KeyCode.ButtonY then
				Character:BreakJoints()
				if RagdollEnabled and RagdollHeadMovement then
					Network:Unclaim()
					Respawn()
				end
			end
		end)
		local OnInputEnded = UserInputService.InputEnded:Connect(function(Input, Processed)
			if not Processed then
				if Input.KeyCode == Enum.KeyCode.LeftControl or Input.KeyCode == Enum.KeyCode.ButtonL2 then
					Tween(VirtualBody.Humanoid, "Elastic", "Out", 1, {
						CameraOffset = Vector3.new(0, StudsOffset, 0)
					})
				end
			end
			if Input.KeyCode == Enum.KeyCode.LeftShift or Input.KeyCode == Enum.KeyCode.ButtonR2 then
				Tween(VirtualBody.Humanoid, "Sine", "Out", 1, {
					WalkSpeed = 8
				})
			end
			if not VRReady and Input.UserInputType == Enum.UserInputType.MouseButton1 then
				Point1 = false
			end
			if not VRReady and Input.UserInputType == Enum.UserInputType.MouseButton2 then
				Point2 = false
			end
		end)
--[[
 Proper Cleanup
--]]
		local OnReset
		OnReset = Client.CharacterAdded:Connect(function()
			OnReset:Disconnect();
			CFrameChanged:Disconnect();
			OnStepped:Disconnect();
			OnRenderStepped:Disconnect();
			OnMoving:Disconnect();
			OnInput:Disconnect();
			OnInputEnded:Disconnect();
			VirtualRig:Destroy();
			VirtualBody:Destroy();
			if RagdollEnabled then
				Network:Unclaim();
			end
			if AutoRun then
				delay(2, function()
					Script()
				end)
			end
		end)
		if ChatEnabled then
			spawn(ChatHUDFunc)
		end
		if ViewportEnabled then
			spawn(ViewHUDFunc)
		end
		do
--[[
 Functions
 --]]
			local Players = game:GetService("Players")
			local Client = Players.LocalPlayer
			local VRService = game:GetService("VRService")
			local VRReady = VRService.VREnabled
			local UserInputService = game:GetService("UserInputService")
			local RunService = game:GetService("RunService")
			local Camera = workspace.CurrentCamera
--[[
 Code
 --]]
			if VRReady then
				local Pointer = game:GetObjects("rbxassetid://4476173280")[1]
				Pointer.Parent = workspace
				Pointer.Beam.Enabled = false
				Pointer.Target.ParticleEmitter.Enabled = false
				local RenderStepped = RunService.RenderStepped:Connect(function()
					if Pointer.Beam.Enabled then
						local RightHand = Camera.CFrame * VRService:GetUserCFrame(Enum.UserCFrame.RightHand)
						local Target = RightHand * CFrame.new(0, 0, -10)
						local Line = Ray.new(RightHand.p, (Target.p - RightHand.p).Unit * 128)
						local Part, Position = workspace:FindPartOnRayWithIgnoreList(Line, {VirtualRig, VirtualBody, Character, Pointer})
						local Distance = (Position - RightHand.p).Magnitude
						Pointer.Target.Position = Vector3.new(0, 0, -Distance)
						Pointer.CFrame = RightHand
					end
				end)
				local Input = UserInputService.InputBegan:Connect(function(Input)
					if Input.KeyCode == Enum.KeyCode.ButtonB then
						Pointer.Beam.Enabled = not Pointer.Beam.Enabled
						Pointer.Target.ParticleEmitter.Enabled = not Pointer.Target.ParticleEmitter.Enabled
					end
				end)
				--
				local CharacterAdded
				CharacterAdded = Client.CharacterAdded:Connect(function()
					RenderStepped:Disconnect()
					Input:Disconnect()
					CharacterAdded:Disconnect()
					Pointer:Destroy()
					Pointer = nil
				end)
			else
				return
			end
		end
	end;
	Permadeath = function()
		local ch = game.Players.LocalPlayer.Character
		local prt=Instance.new("Model", workspace)
		local z1 = Instance.new("Part", prt)
		z1.Name="Torso"
		z1.CanCollide = false
		z1.Anchored = true
		local z2 =Instance.new("Part", prt)
		z2.Name="Head"
		z2.Anchored = true
		z2.CanCollide = false
		local z3 =Instance.new("Humanoid", prt)
		z3.Name="Humanoid"
		z1.Position = Vector3.new(0,9999,0)
		z2.Position = Vector3.new(0,9991,0)
		game.Players.LocalPlayer.Character=prt
		wait(5)
		warn("50%")
		game.Players.LocalPlayer.Character=ch
		wait(6)
		warn("100%")
	end;
	Respawn = function()
		local ch = game.Players.LocalPlayer.Character
		local prt=Instance.new("Model", workspace)
		local z1 = Instance.new("Part", prt)
		z1.Name="Torso"
		z1.CanCollide = false
		z1.Anchored = true
		local z2 =Instance.new("Part", prt)
		z2.Name="Head"
		z2.Anchored = true
		z2.CanCollide = false
		local z3 =Instance.new("Humanoid", prt)
		z3.Name="Humanoid"
		z1.Position = Vector3.new(0,9999,0)
		z2.Position = Vector3.new(0,9991,0)
		game.Players.LocalPlayer.Character=prt
		wait(5)
		game.Players.LocalPlayer.Character=ch
	end;
	ChatHUDFunc = function()
--[[
 Variables
 --]]
		local UserInputService = game:GetService("UserInputService")
		local RunService = game:GetService("RunService")
		local VRService = game:GetService("VRService")
		local VRReady = VRService.VREnabled
		local Players = game:GetService("Players")
		local Client = Players.LocalPlayer
		local ChatHUD = game:GetObjects("rbxassetid://4476067885")[1]
		local GlobalFrame = ChatHUD.GlobalFrame
		local Template = GlobalFrame.Template
		local LocalFrame = ChatHUD.LocalFrame
		local Global = ChatHUD.Global
		local Local = ChatHUD.Local
		local Camera = workspace.CurrentCamera
		Template.Parent = nil
		ChatHUD.Parent = game:GetService("CoreGui")
--[[
 Code
 --]]
		local Highlight = Global.Frame.BackgroundColor3
		local Deselected = Local.Frame.BackgroundColor3
		local OpenGlobalTab = function()
			Global.Frame.BackgroundColor3 = Highlight
			Local.Frame.BackgroundColor3 = Deselected
			Global.Font = Enum.Font.SourceSansBold
			Local.Font = Enum.Font.SourceSans
			GlobalFrame.Visible = true
			LocalFrame.Visible = false
		end
		local OpenLocalTab = function()
			Global.Frame.BackgroundColor3 = Deselected
			Local.Frame.BackgroundColor3 = Highlight
			Global.Font = Enum.Font.SourceSans
			Local.Font = Enum.Font.SourceSansBold
			GlobalFrame.Visible = false
			LocalFrame.Visible = true
		end
		Global.MouseButton1Down:Connect(OpenGlobalTab)
		Local.MouseButton1Down:Connect(OpenLocalTab)
		Global.MouseButton1Click:Connect(OpenGlobalTab)
		Local.MouseButton1Click:Connect(OpenLocalTab)
		OpenLocalTab()
		--
		local function GetPlayerDistance(Sender)
			if Sender.Character and Sender.Character:FindFirstChild("Head") then
				return math.floor((Sender.Character.Head.Position - Camera:GetRenderCFrame().p).Magnitude + 0.5)
			end
		end
		local function NewGlobal(Message, Sender, Color)
			local Frame = Template:Clone()
			Frame.Text = ("[%s]: %s"):format(Sender.Name, Message)
			Frame.User.Text = ("[%s]:"):format(Sender.Name)
			Frame.User.TextColor3 = Color
			Frame.BackgroundColor3 = Color
			Frame.Parent = GlobalFrame
			delay(60, function()
				Frame:Destroy()
			end)
		end
		local function NewLocal(Message, Sender, Color, Dist)
			local Frame = Template:Clone()
			Frame.Text = ("(%s) [%s]: %s"):format(tostring(Dist), Sender.Name, Message)
			Frame.User.Text = ("(%s) [%s]:"):format(tostring(Dist), Sender.Name)
			Frame.User.TextColor3 = Color
			Frame.BackgroundColor3 = Color
			Frame.Parent = LocalFrame
			delay(60, function()
				Frame:Destroy()
			end)
		end
		local function OnNewChat(Message, Sender, Color)
			if not ChatHUD or not ChatHUD.Parent then return end
			NewGlobal(Message, Sender, Color)
			local Distance = GetPlayerDistance(Sender)
			if Distance and Distance <= ChatLocalRange then
				NewLocal(Message, Sender, Color, Distance)
			end
		end
		local function OnPlayerAdded(Player)
			if not ChatHUD or not ChatHUD.Parent then return end
			local Color = BrickColor.Random().Color
			Player.Chatted:Connect(function(Message)
				OnNewChat(Message, Player, Color)
			end)
		end
		Players.PlayerAdded:Connect(OnPlayerAdded)
		for _, Player in pairs(Players:GetPlayers()) do
			OnPlayerAdded(Player)
		end
		--
		local ChatPart = ChatHUD.Part
		ChatHUD.Adornee = ChatPart
		if VRReady then
			ChatHUD.Parent = game:GetService("CoreGui")
			ChatHUD.Enabled = true
			ChatHUD.AlwaysOnTop = true
			local OnInput = UserInputService.InputBegan:Connect(function(Input, Processed)
				if not Processed then
					if Input.KeyCode == Enum.KeyCode.ButtonX then
						ChatHUD.Enabled = not ChatHUD.Enabled
					end
				end
			end)
			local RenderStepped = RunService.RenderStepped:Connect(function()
				local LeftHand = VRService:GetUserCFrame(Enum.UserCFrame.LeftHand)
				ChatPart.CFrame = Camera.CFrame * LeftHand
			end)
			local CharacterAdded
			CharacterAdded = Client.CharacterAdded:Connect(function()
				OnInput:Disconnect()
				RenderStepped:Disconnect()
				CharacterAdded:Disconnect()
				ChatHUD:Destroy()
				ChatHUD = nil
			end)
		end
		wait(9e9)
	end;
	ViewHUDFunc = function()
--[[
 Variables
 --]]
		local ViewportRange = ViewportRange or 32
		local UserInputService = game:GetService("UserInputService")
		local RunService = game:GetService("RunService")
		local VRService = game:GetService("VRService")
		local VRReady = VRService.VREnabled
		local Players = game:GetService("Players")
		local Client = Players.LocalPlayer
		local Mouse = Client:GetMouse()
		local Camera = workspace.CurrentCamera
		local CameraPort = Camera.CFrame
		local ViewHUD = script:FindFirstChild("ViewHUD") or game:GetObjects("rbxassetid://4480405425")[1]
		local Viewport = ViewHUD.Viewport
		local Viewcam = Instance.new("Camera")
		local ViewPart = ViewHUD.Part
		ViewHUD.Parent = game:GetService("CoreGui")
		Viewcam.Parent = Viewport
		Viewcam.CameraType = Enum.CameraType.Scriptable
		Viewport.CurrentCamera = Viewcam
		Viewport.BackgroundTransparency = 1
--[[
 Code
 --]]
		local function Clone(Character)
			local Arc = Character.Archivable
			local Clone;
			Character.Archivable = true
			Clone = Character:Clone()
			Character.Archivable = Arc
			return Clone
		end
		local function GetPart(Name, Parent, Descendants)
			for i = 1, #Descendants do
				local Part = Descendants[i]
				if Part.Name == Name and Part.Parent.Name == Parent then
					return Part
				end
			end
		end
		local function OnPlayerAdded(Player)
			if not ViewHUD or not ViewHUD.Parent then return end
			local function CharacterAdded(Character)
				if not ViewHUD or not ViewHUD.Parent then return end
				Character:WaitForChild("Head")
				Character:WaitForChild("Humanoid")
				wait(3)
				local FakeChar = Clone(Character)
				local Root = FakeChar:FindFirstChild("HumanoidRootPart") or FakeChar:FindFirstChild("Head")
				local RenderConnection;
				local Descendants = FakeChar:GetDescendants()
				local RealDescendants = Character:GetDescendants()
				local Correspondents = {};
				FakeChar.Humanoid.DisplayDistanceType = "None"
				for i = 1, #Descendants do
					local Part = Descendants[i]
					local Real = Part:IsA("BasePart") and GetPart(Part.Name, Part.Parent.Name, RealDescendants)
					if Part:IsA("BasePart") and Real then
						Part.Anchored = true
						Part:BreakJoints()
						if Part.Parent:IsA("Accessory") then
							Part.Transparency = 0
						end
						table.insert(Correspondents, {Part, Real})
					end
				end
				RenderConnection = RunService.RenderStepped:Connect(function()
					if not Character or not Character.Parent then
						RenderConnection:Disconnect()
						FakeChar:Destroy()
						return
					end
					if (Root and (Root.Position - Camera.CFrame.p).Magnitude <= ViewportRange) or Player == Client or not Root then
						for i = 1, #Correspondents do
							local Part, Real = unpack(Correspondents[i])
							if Part and Real and Part.Parent and Real.Parent then
								Part.CFrame = Real.CFrame
							elseif Part.Parent and not Real.Parent then
								Part:Destroy()
							end
						end
					end
				end)
				FakeChar.Parent = Viewcam
			end
			Player.CharacterAdded:Connect(CharacterAdded)
			if Player.Character then
				spawn(function()
					CharacterAdded(Player.Character)
				end)
			end
		end
		local PlayerAdded = Players.PlayerAdded:Connect(OnPlayerAdded)
		for _, Player in pairs(Players:GetPlayers()) do
			OnPlayerAdded(Player)
		end
		ViewPart.Size = Vector3.new()
		if VRReady then
			Viewport.Position = UDim2.new(.62, 0, .89, 0)
			Viewport.Size = UDim2.new(.3, 0, .3, 0)
			Viewport.AnchorPoint = Vector2.new(.5, 1)
		else
			Viewport.Size = UDim2.new(0.3, 0, 0.3, 0)
		end
		local RenderStepped = RunService.RenderStepped:Connect(function()
			local Render = Camera.CFrame
			local Scale = Camera.ViewportSize
			if VRReady then
				Render = Render * VRService:GetUserCFrame(Enum.UserCFrame.Head)
			end
			CameraPort = CFrame.new(Render.p + Vector3.new(5, 2, 0), Render.p)
			Viewport.Camera.CFrame = CameraPort
			ViewPart.CFrame = Render * CFrame.new(0, 0, -16)
			ViewHUD.Size = UDim2.new(0, Scale.X - 6, 0, Scale.Y - 6)
		end)
		--
		local CharacterAdded
		CharacterAdded = Client.CharacterAdded:Connect(function()
			RenderStepped:Disconnect()
			CharacterAdded:Disconnect()
			PlayerAdded:Disconnect()
			ViewHUD:Destroy()
			ViewHUD = nil
		end)
		wait(9e9)
	end;
	Script()
	wait(2)
	local Players = game:GetService("Players")
	local lp = Players.LocalPlayer
	local character = lp.Character
	local A0LL = Instance.new("Attachment", character["Left Leg"])
	A0LL.Position = Vector3.new(0, 1, 0)
	local A1LL = Instance.new("Attachment", character["Torso"])
	A1LL.Position = Vector3.new(-0.5, -1, 0)
	local socket1 = Instance.new("BallSocketConstraint", character["Left Leg"])
	socket1.Attachment0 = A0LL
	socket1.Attachment1 = A1LL
	local A0RL = Instance.new("Attachment", character["Right Leg"])
	A0RL.Position = Vector3.new(0, 1, 0)
	local A1RL = Instance.new("Attachment", character["Torso"])
	A1RL.Position = Vector3.new(0.5, -1, 0)
	local socket2 = Instance.new("BallSocketConstraint", character["Right Leg"])
	socket2.Attachment0 = A0RL
	socket2.Attachment1 = A1RL
	local A0H = Instance.new("Attachment", character["Head"])
	A0H.Position = Vector3.new(0, -0.5, 0)
	local A1H = Instance.new("Attachment", character["Torso"])
	A1H.Position = Vector3.new(0, 1, 0)
	local socket5 = Instance.new("BallSocketConstraint", character["Head"])
	socket5.Attachment0 = A0H
	socket5.Attachment1 = A1H
	loadstring(game:HttpGet("https://ghostbin.co/paste/krmyf/raw",true))()
	-----------------------------------------------------------
	wait(9e9)
end)

close.Name = "close"
close.Parent = ScreenGui
close.BackgroundColor3 = Color3.fromRGB(107, 107, 107)
close.Position = UDim2.new(0.0932203382, 0, 0.314741045, 0)
close.Size = UDim2.new(0, 443, 0, 26)
close.MouseButton1Down:connect(function()
	main.Visible = false
	closebutton.Visible = true
end)

closebutton.Name = "closebutton"
closebutton.Parent = close
closebutton.BackgroundColor3 = Color3.fromRGB(255, 170, 0)
closebutton.Position = UDim2.new(1, 0, 0, 0)
closebutton.Size = UDim2.new(0, 37, 0, 26)
closebutton.Font = Enum.Font.SourceSans
closebutton.Text = ""
closebutton.TextColor3 = Color3.fromRGB(0, 0, 0)
closebutton.TextSize = 14.000
closebutton.MouseButton1Down:connect(function()
	closebutton.Visible = false
	main.Visible = true
end)
