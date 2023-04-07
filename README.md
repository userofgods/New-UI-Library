VisualLib

# Making the Library 

local VisualLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/userofgods/New-UI-Library/main/Souce"))()

Making a Window local Window = VisualLib:MakeWindow({Name = "My Library"})

# Adding Tab
local Tab = Window:CreateTab({
    Name = "Tab"
})

# Adding a Button 
Tab:AddButton({
    Name = "Button",
    Callback = function ()
        print("Working")
    end
})

# Adding a Toggle
Tab:AddToggle({
    Name = "Toggle",
    Callback = function ()
        print("Working")
    end
})

# Adding a Slider
Tab:AddSlider({
    Name = "Slider",
    Min = 0, Max = 100,
    Callback = function ()
        print("Wokring")
    end
})
