# Verziókezelés alapjai
## 1. Git letöltése
[git for windows](https://gitforwindows.org/)
[git scm](https://git-scm.com/)
## 2. Konfigurációs parancsok
    git config --global user.name
    git config --global user.email
    git config --global credential.helper
## 3. Repository létrehozása
    git init
## 4. Álllomány hozzáadása a stage-hez
    a stagen lévő állományokról tudunk állapotfelvételt (comit) készíteni
    git add állomány_neve
    git add .commit (az összes állomány és mappa hozzáadása)
## 5. Állapotfelvétel (commit) készítése
    git commit -m "commit message"