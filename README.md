<center><img src="https://i.postimg.cc/MKPVVR1s/dplogo-512.png" alt="logo"></center>
<center><img src="https://i.postimg.cc/RZ9dqPFx/introduce.png" alt="introduce"></center>

Example Video : *Coming soon!*

This plugin introduces two special currencies (**Cash** and **Mileage**) for your Minecraft server. Players can earn these currencies through gameplay or events and spend them on items or perks in an in-game shop.  
Enhance your server’s economy with a fun secondary currency system where players can earn rewards beyond the standard money, all without complicated setup!

---

<center><img src="https://i.postimg.cc/RZ9dqP08/description.png" alt="description"></center>

- Add two custom player currencies, **Cash** and **Mileage**, separate from the default economy  
- Create custom **shops** where players can buy or sell items using Cash or Mileage  
- **Automatically track and save** each player’s currency balances and transaction statistics  
- Easily configure **shop items and prices** through an intuitive in-game GUI  
- Real-time **currency balance display** via PlaceholderAPI integration  

---

<center><img src="https://i.postimg.cc/rwcjzhpH/depend-plugin.png" alt="depend-plugin"></center>

- All DP-Plugins require the **`DPP-Core`** plugin  
- The plugin will not work if **`DPP-Core`** is not installed  
- You can download **`DPP-Core`** here: <a href="https://github.com/DP-Plugins/DPP-Core/releases" target="_blank">Click me!</a>  
- This plugin integrates with **PlaceholderAPI**  
- If PlaceholderAPI is not installed, placeholder features will not be available  

---

<center><img src="https://i.postimg.cc/dV01RxJB/installation.png" alt="installation"></center>

1️⃣ Place the **`DPP-Core`** plugin and this plugin file (**`DP-Cash-*.jar`**) into your server’s **`plugins`** folder  

2️⃣ Restart the server, and the plugin will be automatically enabled  

3️⃣ If needed, you can open and modify **`config.yml`** and **`plugin.yml`** to customize settings  

---

<center><img src="https://i.postimg.cc/jSKcC85K/settings.png" alt="settings"></center>

- **`config.yml`**: Manages basic plugin settings and message options  

---

<center><img src="https://i.postimg.cc/SxqdjZKw/command.png" alt="command"></center>

❗ Some commands require admin permission (`dpcash.admin`)

**Command List and Examples**

| Command | Permission | Description | Example |
|------|------------|-------------|---------|
| `/cash give <username/UUID> <amount>` | dpcash.admin | Give cash to a player | `/cash give Steve 100` |
| `/cash take <username/UUID> <amount>` | dpcash.admin | Take cash from a player | `/cash take Steve 50` |
| `/cash set <username/UUID> <amount>` | dpcash.admin | Set a player’s cash balance | `/cash set Steve 1000` |
| `/cash info <username/UUID>` | dpcash.admin | Check a player’s cash balance | `/cash info Steve` |
| `/cash my` | dpcash.user | Check your own cash balance | `/cash my` |
| `/cash reset <username/UUID>` | dpcash.admin | Reset a player’s cash balance | `/cash reset Steve` |
| `/mileage give <username/UUID> <amount>` | dpcash.admin | Give mileage to a player | `/mileage give Steve 100` |
| `/mileage take <username/UUID> <amount>` | dpcash.admin | Take mileage from a player | `/mileage take Steve 50` |
| `/mileage set <username/UUID> <amount>` | dpcash.admin | Set a player’s mileage balance | `/mileage set Steve 500` |
| `/mileage info <username/UUID>` | dpcash.admin | Check a player’s mileage balance | `/mileage info Steve` |
| `/mileage my` | dpcash.user | Check your own mileage balance | `/mileage my` |
| `/mileage reset <username/UUID>` | dpcash.admin | Reset a player’s mileage balance | `/mileage reset Steve` |
| `/cashshop create <name> <row> <shopType>` | dpcash.admin | Create a new shop | `/cashshop create VIPShop 5 CASH` |
| `/cashshop items <shopName>` | dpcash.admin | Edit shop items via GUI | `/cashshop items VIPShop` |
| `/cashshop price <shopName>` | dpcash.admin | Set shop item prices | `/cashshop price VIPShop` |
| `/cashshop maxpage <shopName> <maxPage>` | dpcash.admin | Set maximum pages for a shop | `/cashshop maxpage VIPShop 3` |
| `/cashshop delete <shopName>` | dpcash.admin | Delete a shop | `/cashshop delete VIPShop` |
| `/cashshop reload` | dpcash.admin | Reload plugin configuration | `/cashshop reload` |
| `/cashshop open <shopName>` | dpcash.user | Open a shop | `/cashshop open VIPShop` |

**❗Notes when using commands**

- Shop names support Korean and English, but **spaces are not allowed**  
- Invalid inputs will display an error message  
- Shop items and prices are edited via GUI and saved automatically  
- Admin commands require **OP** status or the `dpcash.admin` permission  

---

<center><img src="https://i.postimg.cc/Z5ZH0fqL/api-integration.png" alt="api-integration"></center>

Display a player’s currency data in real-time using PlaceholderAPI

- **`%dpcash_cash%`**: Player’s current cash balance  
- **`%dpcash_mileage%`**: Player’s current mileage balance  
- **`%dpcash_total_cash_earned%`**: Total cash earned  
- **`%dpcash_total_cash_spent%`**: Total cash spent  
- **`%dpcash_total_mileage_earned%`**: Total mileage earned  
- **`%dpcash_total_mileage_spent%`**: Total mileage spent  

---

<center><a href="https://discord.gg/JnMCqkn2FX"><img src="https://i.postimg.cc/4xZPn8dC/discord.png" alt="discord"></a></center>

- https://discord.gg/JnMCqkn2FX  
- If you have any questions or issues, please contact your server administrator  
- Suggestions for new features or improvements are always welcome  

---
