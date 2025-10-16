# Pterodactyl Free Theme

Install Free pterodactyl themee using simple commands.

---

## 📥 Install Panel Assetss
```bash
bash <(curl -s https://raw.githubusercontent.com/rredefined/ptero/main/assets.sh)
apt update
apt install unzip -y 
```

---

## 📌 Setup files Using These Commands:
Click on the copy button to copy each command! ⬇️

```bash
git clone https://github.com/rredefined/free-theme.git
cd free-theme
mv theme.zip /var/www/
cd /var/www && unzip theme.zip
```

## 🚀 Final Step

### ▶️ Install the theme
```
cd /var/www/pterodactyl
export NODE_OPTIONS=--openssl-legacy-provider
yarn build:production
```

---

## ⭐ Contribute
- Star ⭐ the repo  
- Fork 🍴 the project  
- Contribute 🔧 via pull requests  

---

## 📞 Discord: 
[![Nightt.jss](https://discord.com/users/969258536557244537)
