# <img src="logo-1.png" alt="ChatGPT Direction Toggle Logo" width="25px" style="border-radius:8px; vertical-align:middle;"> **ChatGPT Direction Toggle**

A lightweight **Google Chrome Extension** that lets you instantly switch ChatGPT between **LTR ↔ RTL**.  
Perfect for **Persian, Arabic, Hebrew** users who need proper right-to-left support.

<details>
<summary><h2>🖥 Demo</h2></summary>

<img width="600" alt="Demo Screenshot - ChatGPT Direction Toggle" src="https://github.com/user-attachments/assets/b1b641db-7af6-455a-b49d-ef19b5691355" />
<img width="678" height="277" alt="RTL" src="https://github.com/user-attachments/assets/ec7e7a0d-ff81-4656-a5ad-9b5314df6ff8" />
<img width="683" height="291" alt="LTR" src="https://github.com/user-attachments/assets/333adace-f64c-48db-bdd8-35ddc4707a41" />

<details>
  <summary><h3>Explained</h3></summary>
This extension adds a simple toggle via the **browser toolbar icon**:  

* **Click once** → Switch to **RTL** (Right-to-Left).  
* **Click again** → Switch back to **LTR** (Left-to-Right).  
* Shows a **green ON badge** when RTL mode is active.  

**In short:** read and write in the direction you prefer with a single click.  
</details>
</details>

<details>
<summary><h2>💡 Why & Benefits</h2></summary>

- Makes ChatGPT much more usable for **RTL languages** (Persian, Arabic, Hebrew).  
- One-click toggle directly from the browser toolbar.  
- Works seamlessly with **messages, input box, and editor**.  
- No external dependencies, no layout breaking.  

</details>

<details>
<summary><h2>✨ Features</h2></summary>

- Toggle via **extension icon click**.  
- Badge indicator → shows **ON** when RTL is active.  
- Persistent setting (remembers last mode).  
- Compatible with ChatGPT dynamic DOM updates.  
- Lightweight – no frameworks or extra libraries.  

</details>

<details>
<summary><h2>⚙️ Installation</h2></summary>

This is a **local Chrome Extension** (not yet in the Chrome Web Store).  

1. Clone or download this repository.  
2. Open Chrome → go to `chrome://extensions/`.  
3. Enable **Developer mode** (top-right).  
4. Click **Load unpacked** and select the project folder.  
5. A new icon appears in your toolbar.  
6. **Click the icon** to toggle RTL/LTR in ChatGPT.  

</details>

<details>
<summary><h2>❓ FAQ</h2></summary>

<details>
<summary><h3>🔹 Does it affect only ChatGPT?</h3></summary>
Yes. The extension only runs on <b>chat.openai.com</b> and <b>chatgpt.com</b>.
</details>

<details>
<summary><h3>🔹 Does it break the layout?</h3></summary>
No. It only modifies <b>text direction</b> and <b>alignment</b>.
</details>

<details>
<summary><h3>🔹 How can I see if RTL is enabled?</h3></summary>
When RTL mode is ON, the extension icon shows a **green ON badge**.  
</details>

<details>
<summary><h3>🔹 Does it save my last choice?</h3></summary>
Yes. It uses <b>chrome.storage</b> to persist your last setting.  
</details>

</details>

<details>
<summary><h2>📌 Changelog</h2></summary>

- **v2.0.0** – Migrated from Tampermonkey userscript to full Chrome Extension (Manifest V3).  
- **v1.1.0** – Improved toggle logic, persistence.  
- **v1.0.0** – Initial userscript release with button + Alt+R shortcut.  

</details>

<details>
<summary><h2>🔑 SEO Keywords</h2></summary>

chatgpt rtl, chatgpt chrome extension, chatgpt rtl extension, rtl support chatgpt, persian arabic hebrew chatgpt, chatgpt direction toggle extension, chatgpt ltr rtl switch  

</details>

<details>
<summary><h3>⚠️ Disclaimer</h3></summary>

This project is created **for educational and personal use only**.  
It is not affiliated with, endorsed by, or connected to **OpenAI** or **ChatGPT**.  
Use at your own risk. The author assumes no responsibility for any consequences arising from its use.  

</details>

### 🤝 Contributing

Contributions, bug reports, and feature ideas are welcome!  

[![Sasha](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/127698692?v=4&w=35&h=35&mask=circle)](https://github.com/reza-nzri)
