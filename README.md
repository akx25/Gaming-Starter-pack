# Gaming-Starter-pack
Install all the gaming thing you need using WinGet or Linux terminal!

Included software

- Steam
- Discord
- AMD Software: Adrenalin Edition
- NVIDIA GeForce Experience
- Intel Driver & Support Assistant
- EA Launcher
- Ubisoft Connect
- Epic Games Launcher

1. Open PowerShell
2. Copy & Paste one of these (Depending on your GPU!)


AMD "Valve.Steam","Discord.Discord","AdvancedMicroDevices.AMDSoftwareAdrenalinEdition","EpicGames.EpicGamesLauncher","ElectronicArts.EADesktop","Ubisoft.Connect","RockstarGames.Launcher" | ForEach-Object { winget install --id $_ -e }

NVIDIA "Valve.Steam","Discord.Discord","Nvidia.GeForceExperience","ElectronicArts.EADesktop","Ubisoft.Connect","EpicGames.EpicGamesLauncher","RockstarGames.Launcher" | ForEach-Object { winget install --id $_ -e }

INTEL "Valve.Steam","Discord.Discord","ElectronicArts.EADesktop","Ubisoft.Connect","Intel.IntelDriverAndSupportAssistant","EpicGames.EpicGamesLauncher","RockstarGames.Launcher" | ForEach-Object { winget install --id $_ -e }


3. ENJOY :)
