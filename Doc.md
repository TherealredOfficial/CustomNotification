# Custom Notification Script

This script provides a customizable notification system for developers in Roblox.

## Installation

1. **Load the Script:**
   Load the script using `loadstring` from the GitHub URL. Place this in your script or command bar:

   ```lua
   loadstring(game:HttpGet("https://raw.githubusercontent.com/YourUsername/YourRepository/main/Main"))()

## Customization

### Change Default Settings

You can customize the default appearance of notifications by modifying the script. Open the script and find the `showCustomNotification` function. Within this function, you can adjust various parameters such as colors, fonts, and sizes.

### Example Customization

Here's an example of how you might modify the script to change the default colors:

```lua
-- Update the default colors
local defaultBackgroundColor = Color3.fromRGB(0, 0, 0) -- Change to your preferred color
local defaultIconColor = Color3.fromRGB(255, 255, 255) -- Change to your preferred color
local defaultStrokeColor = Color3.fromRGB(138, 43, 226) -- Change to your preferred color
