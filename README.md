# 🤖 MILON BOT V4

![Milon BOT Logo](https://raw.githubusercontent.com/MR-IMRAN-60/ImranBypass/refs/heads/main/imranbotlogo.png)

**🌟 Fully Customizable Facebook Messenger Bot**  
**Premium Features • Easy to Use • Built with ❤️ by Imran Ahmed**

## 👤 ABOUT ME

- Name: ```Milon hasan```</br> 
- Age: ```20```</br>  
- Facebook: [Milon hasan](https://www.facebook.com/Imran.Ahmed099).</br>

## 🚀 STARTUP

```bash
npm install
```
```txt
node main/catalogs/IMRANA.js
```
## 🛠️ CREDITS

Original Base: BotPack by YanMaglinte

Modified By: ```Milon & Ryuko```</br>

Facebook Client: fca-ws3 by Kenneth Aceberos

## ✨ FEATURES

✅ Email notifications for box approval (configurable via Config.json)

🔧 Custom console logging (see configs/console.js)

🚫 Spam prevention in ban system

💎 Premium-only commands (enable with premium: true in command config)


## ⚙️ CONFIGURATION

File	Description

Milon.js	```Auto restart and pending message handler```</br>
Config.json	```Bot name, prefix, admins, operators, etc.```</br>
appstate.json ```Facebook login/session state```</br>


## 🔐 BOX APPROVAL SYSTEM

Enable in Config.json:

```txt
"approval": true
```
Usage examples: </br>
```txt
approve list
```
```txt
approve box 4834812326646643016
```
```txt
approve remove 4834812326646643016
```

## 📥 HOW TO GET appstate.json

Use the FBState Exporter extension to export your Facebook login session:

Steps:

1. Download fbstate exporter [here](https://drive.google.com/file/d/1peKwJz_QNrTIj7LY5V2h000rZtjSHiA8/view?usp=drivesdk)</br>


2. Open with Kiwi Browser


3. Load as ``extension``</br>


4. Login to Facebook


5. Open the extension and click “Copy fbstate”


6. Paste the copied data into a file named appstate.json



## 🧠 ADDING A COMMAND

Example command template:
```
module.exports.config = {
  name: "example",
  version: "1.0.0",
  permission: 0,
  credits: "IMRAN",
  description: "An example command",
  prefix: true,
  category: "utility",
  usages: "example [args]",
  cooldowns: 5,
  premium: false,
  dependencies: {}
};

module.exports.run = async ({ api, event, args }) => {
  api.sendMessage("Hello from example command!", event.threadID);
};
```
## 🧩 UPCOMING FEATURES

⏩ Command aliases

🔒 Encrypted state manager

📊 Dashboard system for logs and analytics


📁 RESOURCES

GitHub Repository: [Milon-BOTV4](https://github.com/MR-IMRAN-60/IMRAN-BOTV4)


> 💬 Developed with care by Imran Ahmed & Ryuko



Let me know if you want me to help with anything else!

