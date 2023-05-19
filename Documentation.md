# Dark Hub Library
## Documentation
This documentation is for the stable release of Dark Library.
### Booting the Library
```lua

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Dialz2/Dark-Lib/main/Dark%20Library%20Source"))()

```
### Creating a Window
```lua
local Window = Library:CreateWindow("Title")
```
### Creating a Tab
```lua
local Tab = Window:CreateTab("Text")
```
### Creating a Section
```lua
local Section = Tab:CreateSection("Text")
```
### Creating a Button
```lua
Section:CreateButton("Text",function()
       print("Script")
end)
```
### Creating a Toggle
```lua
Section:CreateToggle("Text",function()
       print("Script")
end)
```
### Creating a TextBox
```lua
Section:CreateBox("Text",function()
       print("Script")
end)
```
### Creating a Label
```lua
Section:CreateLabel("Text")
```
### Creating a Notification
```lua
game:GetService("StarterGui"):SetCore("SendNotification",{

	Title = "Title",

	Text = "Text"

})
```
