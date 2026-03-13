<h1 align="center">
  <span style="color:#00ff88;">tgOsint</span> 🛰️
</h1>

<p align="center">
  <b>Telegram OSINT Tool — Menu interactif</b><br>
  <i>Analyse • Recherche • Groupes • Activité • Rapport</i>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/RebelleMasque/tgOsint/main/assets/banner.png"
       alt="tgOsint banner"
       width="820">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-00ff88?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/OSINT-Telegram-00ff88?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Active-00ff88?style=for-the-badge">
</p>
<p align="center">
  <!-- Communauté -->
  <a href="https://chat.whatsapp.com/F9NbADb7L7v9SALfdBa9zq">
    <img src="https://img.shields.io/badge/WhatsApp-Groupe-00ff88?style=for-the-badge&logo=whatsapp" alt="Groupe WhatsApp">
  </a>

  <a href="https://t.me/+cJv8pOd1Em40ZGFk">
    <img src="https://img.shields.io/badge/Telegram-Cha%C3%AEne-00ff88?style=for-the-badge&logo=telegram" alt="Chaîne Telegram">
  </a>
</p>

<p align="center">
  <!-- Contact développeur -->
  <a href="https://wa.me/2250500581309">
    <img src="https://img.shields.io/badge/Contacter-WhatsApp-00ff88?style=for-the-badge&logo=whatsapp" alt="Contacter le développeur WhatsApp">
  </a>

  <a href="https://t.me/Rebellemasque">
    <img src="https://img.shields.io/badge/Contacter-Telegram-00ff88?style=for-the-badge&logo=telegram" alt="Contacter le développeur Telegram">
  </a>
</p>

---

## 🧠 Description

**tgOsint** est un outil **OSINT Telegram** écrit en Python.  
Il permet de collecter et analyser des informations accessibles publiquement
sur des comptes Telegram à des **fins éducatives et d’analyse**.

### 🔍 Fonctionnalités principales
- Recherche par **username**
- Recherche par **ID**
- Recherche par **numéro de téléphone**
- Liste de **tous les groupes et canaux**
- Analyse de **l’activité récente**
- **Détection de faux comptes** (score indicatif)
- Téléchargement des **photos de profil**
- Génération de **rapport OSINT (.txt)**

---

## ⚠️ Avertissement légal

> Cet outil est fourni **à des fins éducatives et légales uniquement**.  
> Toute utilisation abusive, intrusive ou illégale est **strictement interdite**.  
> L’utilisateur est **seul responsable** de l’usage qu’il en fait.

---

## 🧩 Prérequis

- Python **3.9 ou plus**
- Un compte Telegram
- Un **API ID** et **API Hash** Telegram

---

## 🔑 Obtenir API ID & API Hash

1. Aller sur le site développeur Telegram
 https://my.telegram.org/auth
connecter vous a vautre comptes
3. Créer une application
4. Récupérer :
   - `api_id`
   - `api_hash`

Le script te les demandera automatiquement au lancement.

---

## 📦 Installation (modules & packages)

### 🔹 Installation rapide
```bash
pkg update && pkg upgrade
pkg install python
git clone https://github.com/RebelleMasque/tgOsint.git
cd tgOsint
pip install -r requirements.txt
python tgOsint.py
