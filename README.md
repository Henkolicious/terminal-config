# terminal-config

<pre>
// To view the default settings, hold "alt" while clicking on the "Settings" button.
// For documentation on these settings, see: https://aka.ms/terminal-documentation
{
    "$schema": "https://aka.ms/terminal-profiles-schema",
    "defaultProfile": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
    "profiles": [
        {
            // Make changes here to the powershell.exe profile
            "guid": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
            "name": "Windows PowerShell",
            "commandline": "powershell.exe",
            "hidden": false        
        },
        {
            // Make changes here to the cmd.exe profile
            "guid": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
            "name": "cmd",
            "commandline": "cmd.exe",
            "hidden": false,
            "colorScheme": "HenkoliciousCMD",
            // img url: https://res.cloudinary.com/practicaldev/image/fetch/s--kTsDcTzl--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_66%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/s8ysw6hfoj1a61ovz0us.gif
            "backgroundImage": "C:\\maigchorse.gif",
            "backgroundImageAlignment": "topRight",
            "backgroundImageStretchMode":"none",
            "acrylicOpacity": 0.1,
            "useAcrylic": true
        },
        {
            "guid": "{2c4de342-38b7-51cf-b940-2309a097f518}",
            "hidden": false,
            "name": "Ubuntu",
            "source": "Windows.Terminal.Wsl"
        },
        {
            "guid": "{b453ae62-4e3d-5e58-b989-0a998ec441b8}",
            "hidden": false,
            "name": "Azure Cloud Shell",
            "source": "Windows.Terminal.Azure"
        }     
    ],
    "schemes": [
        {
            "name": "HenkoliciousCMD",
            "background" : "#282A36",
            "black" : "#21222C",
            "blue" : "#BD93F9",
            "brightBlack" : "#6272A4",
            "brightBlue" : "#D6ACFF",
            "brightCyan" : "#A4FFFF",
            "brightGreen" : "#69FF94",
            "brightPurple" : "#FF92DF",
            "brightRed" : "#FF6E6E",
            "brightWhite" : "#FFFFFF",
            "brightYellow" : "#FFFFA5",
            "cyan" : "#8BE9FD",
            "foreground" : "#F8F8F2",
            "green" : "#50FA7B",
            "purple" : "#FF79C6",
            "red" : "#FF5555",
            "white" : "#F8F8F2",
            "yellow" : "#F1FA8C"
        }
    ],
    "keybindings": [
        {
            "command": "copy",
            "keys": [
                "ctrl+shift+c"
            ]
        },
        {
            "command": "paste",
            "keys": [
                "ctrl+shift+v"
            ]
        },
        {
            "command": "closeTab",
            "keys": [
                "ctrl+w"
            ]
        },
        {
            "command": "openNewTabDropdown",
            "keys": [
                "ctrl+t"
            ]
        },
        {
            "command": "switchToTab0",
            "keys": ["ctrl+1"]
        },
        {
            "command": "switchToTab1",
            "keys": ["ctrl+2"]
        },
        {
            "command": "switchToTab2",
            "keys": ["ctrl+3"]
        },
        {
            "command": "switchToTab3",
            "keys": ["ctrl+4"]
        },
        {
            "command": "switchToTab4",
            "keys": ["ctrl+5"]
        },
        {
            "command": "nextTab",
            "keys": ["ctrl+pgup"]
        }
        ,
        {
            "command": "prevTab",
            "keys": ["ctrl+pgdn"]
        }
    ]
}
</pre>
