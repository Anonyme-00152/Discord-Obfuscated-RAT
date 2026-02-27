# 🤖 Bot Setup Guide

## 🇫🇷 Instructions (Français)

### 1. Lancer l’installation initiale
```bash
setup.bat
```
- Une fois l’installation terminée, appuie sur **Entrée** → la fenêtre se fermera automatiquement.

---

### 2. Configurer la persistance
```bash
setup_persist.bat
```
- Choisis l’option **1** et attends la fin de l’installation.  
- Vérifie que le fichier `../dist/bot.exe` a bien été créé.

---

### 3. Lancer le bot compilé
```bash
../dist/bot.exe
```
- Double-clique pour démarrer le bot.

---

### 4. Encoder et insérer le token du bot
1. Accède au dossier :
```bash
admin_file
```
2. Lance le script :
```bash
run_encode.bat
```
3. Choisis **l’option 1**, entre ton **token de bot Discord** puis copie la version encodée.  
4. Ouvre ton fichier :
```bash
bot.py
```
5. Colle le token encodé à la ligne **12** :
```python
TOKEN_B64 = "ENTER_YOUR_BOT_TOKEN_HERE"
```
6. Sauvegarde et ferme le fichier.

---

### 5. Exécuter le bot via script
```bash
run_bot.bat
```
- Une fois lancé, tu peux fermer la fenêtre de commande.

---

⚠️ **Attention :**  
Cette version utilise **ton propre token encodé** → toi seul auras accès à la machine qui exécute `../dist/bot.exe`.

---

## 🇬🇧 Instructions (English)

### 1. Run initial setup
```bash
setup.bat
```
- When installation is complete, press **Enter** → the window will close automatically.

---

### 2. Configure persistence
```bash
setup_persist.bat
```
- Select option **1** and wait for the installation to finish.  
- Check that the file `../dist/bot.exe` has been generated.

---

### 3. Start the compiled bot
```bash
../dist/bot.exe
```
- Double-click to run the compiled bot.

---

### 4. Encode and insert the bot token
1. Go to the folder:
```bash
admin_file
```
2. Run the script:
```bash
run_encode.bat
```
3. Select **option 1**, enter your **Discord bot token**, then copy the encoded version.  
4. Open your file:
```bash
bot.py
```
5. Paste the encoded token at **line 12**:
```python
TOKEN_B64 = "ENTER_YOUR_BOT_TOKEN_HERE"
```
6. Save and close the file.

---

### 5. Run the bot via script
```bash
run_bot.bat
```
- Once the bot is running, you can safely close the command window.

---

⚠️ **Warning:**  
This version uses **your own encoded token** → only **YOU** will have access to the machine running `../dist/bot.exe`.
