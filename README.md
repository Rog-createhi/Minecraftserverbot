# Minecraft Server Bot with Web UI

A customizable Minecraft Java Edition bot with a built-in Web UI, powered by [Mineflayer](https://github.com/PrismarineJS/mineflayer).

---

## ✨ Features

- ✅ Connect to **any Java Minecraft server**
- 👤 Custom bot username support
- 🖱️ Web UI to control:
  - Jump
  - Crouch
  - Move (basic)
  - Use item
- 🔄 Auto-equips the first inventory item
- 🛡️ Totem support
- 🧭 Logs activity to browser console
- ⚠️ **Inventory display is placeholder-only** (work in progress)

---

## 🛠 Requirements

- [Node.js](https://nodejs.org/) (v16+ recommended)
- Git (optional if you download ZIP)
- Web browser (Chrome/Firefox/etc.)

---

## 🚀 Installation (one after another) (broken recommended to use the noob way)

wget https://github.com/Rog-createhi/Minecraftserverbot/releases/download/1.0.0/MinecraftServerBot.zip

unzip MinecraftServerBot.zip

cd MinecraftServerBot

npm install

---

▶️ Usage

# Start the server and bot backend
node server.js (this is the problem I don't know how to solve it)

Then, open your browser and go to:

http://localhost:3000

From the Web UI, you can:

1. Enter the bot username (any name).


2. Enter a server IP (e.g., play.example.com).


3. Enter the port (e.g., 25565).


4.  drink coffee


5. Click Connect.



Once connected, you can control the bot via buttons on the page.


---
---

⚙️ Current Limitations

Inventory tab may show incorrect or missing items.

No advanced pathfinding.

Only basic movement.

Respawn logic is not implemented.

No SSL — this is local dev only (unless self-hosted securely).



---

💡 Tips

Run in screen/tmux if hosting on a VPS.

Use a VPS or port forwarding if you want others to access the web UI.

Use firewall rules to restrict unauthorized web access.



---

📜 License

MIT License © 2025 Rog-createhi

funfact: this readme is by chatgpt (yes ik it may not be right)
for noobs: https://replit.com/@rjki59166/MinecraftServerBot
