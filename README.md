# New-UI-Library
New release the name of Visual Library or VisualLib

## Making The Library
```lua
local VisualLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/userofgods/New-UI-Library/main/Souce")()
```

## Creating A Window
```lua
local Window = VisualLib:MakeWindow({Name = "Visual Library"})
```
Creates Window

## Creating A Tab
```lua
local Tab = Window:CreateTab({
    Name = "Tab"
})
```
Creates Tab

## Elements

## Adding A Button
```lua
Tab:AddButton({
    Name = "Button",
    Callback = function ()
        print("Working")
    end
})
```

## Adding A Toggle
```lua
Tab:AddToggle({
    Name = "Toggle",
    Callback = function ()
    print("Working")
    end
})
```

## Adding A Slider
```lua
Tab:AddSlider({
    Name = "Slider",
    Min = 0,
    Max = 100,
    Callback = function ()
        print("Working")
    end
})
```

# Destorying The UI
```lua
VisualLib:Destory()
```

Thats all
