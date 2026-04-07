# 🚗 FiveM Lore Friendly Vehicle Pack

Pack de véhicules **lore-friendly** pour FiveM, prêt à être utilisé sur tout type de serveur (ESX, QBCore, Standalone).

📦 Le pack est fourni sous forme d’un fichier principal :

```id="yrjs8b"
Lore Friendly.rar
```

Ce fichier contient **tous les véhicules sous forme de `.rar` individuels**.

---

## 📸 Aperçu des véhicules

| Véhicule                       | Aperçu                               |
| ------------------------------ | ------------------------------------ |
| Benefactor Imperial            | ![](https://i.imgur.com/q4E2A3w.png) |
| Benefactor XLS ED-BlackSupremo | ![](https://i.imgur.com/o0qJCJS.png) |
| Cheval Picador EXR             | ![](https://i.imgur.com/3HGmkST.png) |
| Declasse Vigero                | ![](https://i.imgur.com/LZopgPS.png) |
| DLVanillaEMS                   | ![](https://i.imgur.com/itQ9lZW.png) |
| Dominator GTX 1.0              | ![](https://i.imgur.com/MqrSafd.png) |
| Gauntlet Hellfire              | ![](https://i.imgur.com/vc0NRJm.png) |
| Grotti Verano GT               | ![](https://i.imgur.com/80RZb9f.png) |
| Improved Penetrator            | ![](https://i.imgur.com/86ZWrwQ.png) |
| Karin Everon (Stock)           | ![](https://i.imgur.com/L1nzFIG.png) |
| Lampadati Komoda GTA           | ![](https://i.imgur.com/bFBkLAF.png) |
| Maibatsu Sunrise R             | ![](https://i.imgur.com/AHWZICV.png) |
| Escalade Sport                 | ![](https://i.imgur.com/aeCr9w1.png) |
| Pegassi Infernus X             | ![](https://i.imgur.com/wEYgZi5.png) |
| Vapid Caracara 4x4 (Bagged)    | ![](https://i.imgur.com/UqOqRPA.png) |
| Vapid Caracara                 | ![](https://i.imgur.com/PSEhXux.png) |
| Vapid Dominator Classic        | ![](https://i.imgur.com/LrHiOhG.png) |
| Vapid Sandstorm                | ![](https://i.imgur.com/esXaTnt.png) |
| Vapid Speedo Express           | ![](https://i.imgur.com/9sM9Gc1.png) |
| Vapid Police Cruiser           | ![](https://i.imgur.com/XW6nXFr.png) |

---

## 📦 Contenu

* 1 archive principale : `Lore Friendly.rar`
* Plusieurs archives `.rar` :

  * 1 véhicule = 1 archive
* Chaque archive contient :

  * Modèle du véhicule
  * Fichiers de streaming
  * `fxmanifest.lua` (selon véhicule)

---

## ⚙️ Installation

### 1. Extraire le pack principal

```id="ns0fzn"
Lore Friendly.rar
```

---

### 2. Extraire chaque véhicule

Chaque véhicule est fourni en `.rar` :

* Extraire chaque archive
* Récupérer le dossier du véhicule

---

### 3. Installer sur le serveur

Placer les dossiers dans :

```id="vaj8yg"
resources/[vehicles]/
```

---

### 4. Ajouter au `server.cfg`

Option classique :

```id="js72t1"
ensure nom_du_vehicle
```

Option optimisée :

```id="gaij6c"
ensure [vehicles]
```

---

## 🔧 Compatibilité

* ✅ ESX (Legacy / Final)
* ✅ QBCore
* ✅ Standalone
* ✅ OneSync

---

## ⚠️ Important

* ❌ Ne pas mettre les `.rar` dans `resources`
* ❌ Toujours extraire chaque véhicule
* ❌ Ne pas renommer les dossiers sans adapter les fichiers internes
* ✔️ Vérifier les conflits de spawnname
* ✔️ Tester en local avant mise en production

---

## 📁 Structure recommandée

```id="k60u9y"
resources/
└── [vehicles]/
    ├── vehicle1/
    ├── vehicle2/
    └── ...
```

---

## 🔐 Bonnes pratiques

* Backup complet avant installation
* Éviter les doublons de véhicules
* Limiter le nombre de véhicules actifs (performance)
* Vérifier les erreurs console (`F8` / logs serveur)

---

## 👤 Auteur

* **InconnueOnTop**

---

## 📜 Licence

Usage autorisé pour serveurs FiveM
Revente interdite sans autorisation

---

## 🤝 Support

Aucun support garanti.
Le pack est fourni **tel quel**, fonctionnel et prêt à l’emploi.

---
