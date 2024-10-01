# crosshairs lie here
hurray
```lua
local crosshair = `{blob}/threeline?raw=true'
local location = 'threeline.png'
if not isfile(location) then 
  writefile('threeline.png', crosshair)
end
```
# now u got it lets insert it!!!
```lua
local asset = getcustomasset('threeline.png')
print(asset) -- 'rbxasset://threeline.png'
```
yaaayy
