<p align="center">
  <img src="https://raw.githubusercontent.com/jrushengodas/ytm-godas/main/ytm-godas/assets/logo.jpg" width="230">
</p>

<h1 align="center">🎵 YTM Song Request - Godas DEV</h1>

<p align="center">
  Système complet de Song Request YouTube Music pour Streamer.bot
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-stable-green">
  <img src="https://img.shields.io/badge/version-1.0-blue">
  <img src="https://img.shields.io/badge/Streamer.bot-compatible-purple">
  <img src="https://img.shields.io/github/downloads/jrushengodas/ytm-godas/total?style=flat">
</p>

---

## 📥 Download

<p align="center">
  <a href="https://github.com/jrushengodas/ytm-godas/releases">
    <img src="https://img.shields.io/badge/Télécharger-YTM%20Godas%20DEV-blue?style=for-the-badge">
  </a>
</p>

## 🚀 Fonctionnalités

- 🎶 Song Request via `!sr` ou reward Twitch  
- 📋 Ajout automatique dans une playlist YouTube  
- 🔄 OAuth Google avec refresh token automatique  
- 🎧 `!song` → musique en cours  
- ⏭️ `!next` → prochaine musique  
- 📜 `!playlist` → voir la playlist  
- 🧹 `!clearplaylist` → vider la playlist  
- 🔐 Setup OAuth avec `!godasytm`  

---

## 💡 Pourquoi ce projet ?

Ce système permet de connecter facilement **Twitch + Streamer.bot + YouTube Music**  
afin d’automatiser entièrement les Song Requests.

👉 Objectif : simplicité, rapidité et zéro prise de tête.

---

## ⚡ Installation rapide

1. Télécharger le setup (bouton ci-dessus)  
2. Installer YouTube Music Desktop  
3. Importer le fichier `.sb` dans Streamer.bot  
4. Configurer Google Cloud  
5. Remplir les Set Arguments dans `godasytm`  
6. Lancer dans le chat :

```text
!godasytm
````

7. Tester :

```text
!sr nom musique + artiste
!song
!next
!playlist
```

---

## ⚙️ Documentation

* 📄 [Installation](INSTALLATION.md)
* 📄 [Google Cloud](GOOGLE_CLOUD.md)
* 📄 [YTM Desktop](YTM_DESKTOP.md)
* 📄 [Commandes](COMMANDS.md)
* 📄 [Crédits](CREDITS.md)

---

## 🎮 Commandes

```text
!godasytm       → Setup OAuth Google
!sr musique     → Ajouter une musique
!song           → Musique en cours
!next           → Prochaine musique
!playlist       → Voir la playlist
!clearplaylist  → Vider la playlist
```

---

## 📦 Version

```text
v1.0 → Release initiale
```
## ❤️ Crédits

**Développement :**

* Godas DEV

**Technologies utilisées :**

* Streamer.bot
* YouTube Data API v3
* YouTube Music Desktop

---

## 🛠 Support

En cas de problème :

* Vérifier que **YouTube Data API v3** est activée
* Vérifier les URI OAuth :

  * [http://127.0.0.1:5000/](http://127.0.0.1:5000/)
  * [http://localhost:5000/](http://localhost:5000/)
* Vérifier que l’API Beta de YouTube Music Desktop est activée
* Relancer `!godasytm`

---

<p align="center">
  ⚡ YTM Song Request System  
  <br>
  Developed with ❤️ by <strong>Godas DEV</strong>
</p>
