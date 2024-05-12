local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Silkroad.onion", HidePremium = false, IntroText = "Silkroad.onion", SaveConfig = true, ConfigFolder = "Silk"})

local ADT = Window:MakeTab({
	Name = "a dusty trip",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

ADT:AddButton({
	Name = "ALL IN ONE (⭐)",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/artemy133563/Utilities/main/ADustyTrip",true))()
  	end    
})

ADT:AddButton({
	Name = "BEST AUTOFARM",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/artemy133563/Utilities/main/MiniFarm",true))()
  	end    
})

local OTHER = Window:MakeTab({
	Name = "Other Scripts",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

OTHER:AddButton({
	Name = "Infyield",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
  	end    
})

local Setings = Window:MakeTab({
	Name = "Setings",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Setings:AddButton({
	Name = "Destroy GUI",
	Callback = function()
        OrionLib:Destroy()
  	end    
})

OrionLib:Init()
