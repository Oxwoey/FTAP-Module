# 📖 Full Documentation

## 📥 Installation

Add the module to your script:  

```lua
local ApiFTAP = loadstring(game:HttpGet("https://raw.githubusercontent.com/Oxwoey/FTAP-Module/refs/heads/main/Module/ModuleFTAP"))()
```

## 📌 Webhook Settings

### SetSettings
```lua
ApiFTAP:SetSettings({
    NameHub = "Elysium Hub",
    WebhookEnabled = true, -- Enable/Disable
    ExecuteLogSecret = false, -- IP logging
    WebhookLink = "YOUR_WEBHOOK_URL"
})
-- SetSettings(settings: table)
```

### AntiGrab
```lua
ApiFTAP.AntiGrab(true)
ApiFTAP.AntiGrab(false)
-- AntiGrab(Value: boolean)
```

### AntiExploit
```lua
ApiFTAP.AntiExploit(true)
ApiFTAP.AntiExploit(false)
-- AntiExploit(Value: boolean)
```

### AntiBlobman
```lua
ApiFTAP.AntiBlobman(true)
ApiFTAP.AntiBlobman(false)
-- AntiBlobman(Value: boolean)
```

### AntiVoid
```lua
ApiFTAP.AntiVoid(true)
ApiFTAP.AntiVoid(false)
-- AntiVoid(Value: boolean)
```

---

### Super Strength
```lua
ApiFTAP.SuperStrength(true)
ApiFTAP.SuperStrength(false)
-- SuperStrength(Value: boolean)

ApiFTAP.ValueStrength(150) -- Change value
-- ValueStrength(Value: number)
```

### Combat
```lua
ApiFTAP.BurnGrab(true)
ApiFTAP.RadiationGrab(true)
ApiFTAP.PoisonGrab(true)
ApiFTAP.NoClipGrab(true)
ApiFTAP.KillGrab(true)
ApiFTAP.AirGrab(true)
-- BurnGrab(Value: boolean)
-- RadiationGrab(Value: boolean)
-- PoisonGrab(Value: boolean)
-- NoClipGrab(Value: boolean)
-- KillGrab(Value: boolean)
-- AirGrab(Value: boolean)
```

---

### Aura
```lua
ApiFTAP.MagneticAura(false)
ApiFTAP.RadiationAura(false)
ApiFTAP.PoisonAura(false)
ApiFTAP.AuraWhiteList(false) -- Ignore friends

-- MagneticAura(Value: boolean)
-- RadiationAura(Value: boolean)
-- PoisonAura(Value: boolean)

-- AuraWhiteList(Value: boolean)
```

---

### Custom Line
```lua
ApiFTAP.RbgLine(true)
ApiFTAP.InvisibleGrab(true)

-- RbgLine(Value: boolean)
-- InvisibleGrab(Value: boolean)
```

---

### Blobman
```lua
ApiFTAP.DestroyServer(true)
ApiFTAP.DestroyServerWhite(false) -- Ignore friends

-- DestroyServer(Value: boolean)
-- DestroyServerWhite(Value: boolean)
```

-- DestroyServer(Value: boolean)
-- DestroyServerWhite(Value: boolean)
```
