# 🚗 Noveks TÜV Vehicle Inspection Script

**Version:** 1.5.0  
**Developer:** Novek  
**Discord:** [Join Support Discord](https://discord.gg/8q8BnmgXq2)  
**Tebex Store:** [Buy Here](https://noveks-workspace.tebex.io/package/6499193)
**Script Preview:** [Youtube](https://youtu.be/wxJ4aIq-Lmg)

---

## 📄 Overview

Bring a new level of realism to your roleplay server with the **Noveks TÜV Vehicle Inspection Script**. This script allows players to register their vehicles at a TÜV station for an inspection. Vehicles that pass the inspection receive a TÜV certificate, while faulty vehicles can have their certificates revoked by admins. Ideal for adding more depth to police, mechanic, and vehicle-related roleplay.

---

## 🔧 **Features:**

- 🔧 **TÜV Inspection:**  
  Players can bring their vehicles to a TÜV station to undergo an inspection.

- 🏷️ **TÜV Certificate:**  
  If the vehicle passes the inspection, players receive a valid TÜV certificate for their vehicle.

- ❌ **Certificate Revocation:**  
  Admins can revoke the certificate for vehicles that have issues or are deemed unsafe.

- 🛠️ **Realistic Interactions:**  
  The script adds more realism to your server by integrating the vehicle inspection process. Great for mechanics, police, and other roleplay jobs!

- 🚀 **Easy Customization:**  
  Easily configurable for your server’s specific needs. Modify station locations, inspection requirements, and more.

Here’s an updated section of the README for the **Noveks TÜV Vehicle Inspection Script**, including the configuration details you provided:

---

## 🛠️ **Installation:**

1. **Download the Script:**  
   Place the script files into your **`resources`** folder.

2. **Add to `server.cfg`:**  
   Add the following line to your `server.cfg`:
   ```lua
   ensure cfx_tuv
   ```

3. **Configure the Script:**  
   Edit the configuration file to set inspection stations, certificate details, and any other customizable options.

---

## 🛠️ **Configuration**

The script configuration is done through the `Noveks_CFG` table. Here you can customize several aspects of the TÜV Vehicle Inspection system to suit your server needs.

### Example Configuration:
```lua
Noveks_CFG = {}

-- ================================================ =========================
-- Job Restriction for Inspection Station Viewing
-- Set to `false` to allow all players to see the inspection stations
-- Set to `true` and specify a job to restrict access
Noveks_CFG.JobRestrictedView = false

-- ================================================ =========================
-- Allowed Job to use the inspection features
-- Specify the job (e.g., police, mechanic, etc.) that can use the script features
Noveks_CFG.AllowedJob = "police"

-- ================================================ =========================
-- Key Binding for TÜV Inspection Search
-- This is the key code that triggers the inspection search interaction
Noveks_CFG.TUVSearchKey = 288 -- Default: `F2`

-- ================================================ =========================
-- Admin Group for Certificate Revocation
-- Specify the admin group that is allowed to revoke certificates
Noveks_CFG.AdminGroup = "admin"

-- ================================================ =========================
-- Language Settings
-- Set to 'en' for English or 'de' for German
Noveks_CFG.locale = 'en'  -- [en] for English, [de] for German
```

## 📝 **Notes:**

- The **`JobRestrictedView`** setting allows you to control which jobs can view the TÜV inspection stations. Set it to `false` to allow any player to see and use the stations, or set it to `true` to restrict access to players with specific jobs like **police** or **mechanic**.

- The **`AllowedJob`** setting defines the job that can interact with the inspection system. You can set this to any of your server's roles (e.g., "police", "mechanic", etc.) to make the script job-specific.

- **Admin group functionality** allows admins to revoke a vehicle's TÜV certificate using the **`AdminGroup`** setting. Customize the group name as necessary for your server's admin structure.

---

## 📑 **Requirements:**

- **ESX 1.2** or **ESX Legacy**  
- **ox_lib**
- **ox_target**

---

## 💬 **Support:**

If you have any questions or face any issues, feel free to open a ticket on our **Discord**:  
[Noveks Support Discord](https://discord.gg/8q8BnmgXq2)

---

### 📑 **License:**

This script is **not open-source** and is subject to the following terms:  
- **Usage:** Licensed for use only on your own server. Redistribution or resale is prohibited.  
- **Modifications:** You may not modify or distribute the script unless explicitly permitted.  
- **Escrow Protection:** Usage terms follow the escrow platform rules (Tebex).  
