# 🧩 errors — Modern System Error Pages by Tyler

**A sleek, production-ready set of custom error pages (403, 404, 500)**  
Built entirely with **pure HTML, CSS, and JS**, no frameworks or assets required.  
Perfect for any **modern portfolio, SaaS, or full-stack project** that deserves style even in failure.

---

## ✨ Highlights
- ⚙️ 100% standalone (no CDNs, no imports)
- 🧠 Built for modern browsers & static hosts
- 🎨 Three distinct designs, each with a unique tone:
  - **403 Forbidden** → Cyber Access Denied
  - **404 Not Found** → Glitch / Lost Transmission
  - **500 Internal Error** → Matrix-style System Crash
- 🧭 Built-in "Return Home" button linking to a live project dashboard

---

## 🔧 Quick Integration

### 🧱 **Apache Configuration**
Use these for your GitHub Pages-hosted error system:

```apache
ErrorDocument 403 https://reallytyler.github.io/errors/403%20/index.html
ErrorDocument 404 https://reallytyler.github.io/errors/404/index.html
ErrorDocument 500 https://reallytyler.github.io/errors/500/index.html
````

> 💡 You can also host locally using `/errors/403.html`, etc.

### 🌀 **Nginx Example**

```nginx
error_page 403 /errors/403.html;
error_page 404 /errors/404.html;
error_page 500 /errors/500.html;
```

---

## 🏠 Project Dashboard (Return Home) (My versions), you can make it to your main page.

Every page includes a **Return to Home** button leading to your **live dashboard**
with all your Modrinth + GitHub projects:

### 🧱 Modrinth

* [Superly](https://modrinth.com/modpack/superly)
* [Lumera](https://modrinth.com/modpack/lumera)
* [CustomRanks](https://modrinth.com/resourcepack/customranks)
* [DiscordRPC](https://modrinth.com/project/discordrpc)
* [DiscordBot](https://modrinth.com/project/discordbot)

### 💾 GitHub

* [classic-discord-rpc](https://github.com/reallytyler/classic-discord-rpc)
* [errors (this repo)](https://github.com/reallytyler/errors/)
* [LoupClient](https://github.com/reallytyler/LoupClient)
* [DiscordFONTS](https://github.com/reallytyler/DiscordFONTS)
* [customranks](https://github.com/reallytyler/customranks)
* [howtoget](https://github.com/reallytyler/howtoget)
* [discord-say-bot](https://github.com/reallytyler/discord-say-bot)
* [ProjectCloud](https://github.com/reallytyler/ProjectCloud)
* [random-stuff.com](https://github.com/reallytyler/random-stuff.com)
* [Discord-Nuke-Bot](https://github.com/reallytyler/Discord-Nuke-Bot)

### 🌐 Website

* [tyler.ct.ws](https://tyler.ct.ws/)

---

## 📦 Structure

```
errors/
 ├── 403/index.html
 ├── 404/index.html
 ├── 500/index.html
 └── README.md
```

---

## 🧰 Tech Summary

| Feature         | Description                                                                   |
| --------------- | ----------------------------------------------------------------------------- |
| **Language**    | HTML, CSS, JavaScript (inline)                                                |
| **Design Goal** | Modern "system" feel — cyber but clean                                        |
| **Frameworks**  | None                                                                          |
| **Performance** | Sub-20KB total footprint                                                      |
| **Best Use**    | Web server error pages, GitHub Pages fallback pages, or custom static routers |

---

## 🧾 License

Released under the **MIT License** — open, remixable, deploy anywhere.
Attribution is optional but appreciated.

---

### 👤 Author

**Tyler**
💻 Developer • Designer • Creator of digital atmospheres
🔗 [Website](https://tyler.ct.ws/) | [GitHub](https://github.com/reallytyler)

---

> “When systems fail, let them fail beautifully.”

---

```

---

