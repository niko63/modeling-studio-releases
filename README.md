# Modeling & Simulation Studio

Plateforme de modélisation d'entreprise et simulation à événements discrets.

**4 éditeurs intégrés :** GRAI · BPMN 2.0 · DEVS · Actigram étendu

---

## 📥 Téléchargement

👉 **[Dernière version — Releases](https://github.com/niko63/modeling-studio-releases/releases/latest)**

Téléchargez le fichier `Modeling & Simulation Studio X.X.X.exe` et double-cliquez dessus pour lancer l'application. **Pas d'installation requise** — c'est un exécutable portable.

---

## ⚙️ Prérequis

**Node.js doit être installé sur votre machine avant de lancer l'application.**

1. Téléchargez Node.js LTS sur **[nodejs.org](https://nodejs.org/en/download)**
2. Choisissez l'installeur Windows (`.msi`) et suivez les étapes
3. Vérifiez l'installation : ouvrez un terminal et tapez `node --version`

> ⚠️ **Important** — Ne pas lancer de serveur Node.js manuellement. L'application démarre son propre serveur automatiquement.

---

## 🚀 Utilisation

1. Téléchargez le fichier `.exe` depuis la section **Releases**
2. Double-cliquez sur l'exe pour lancer l'application directement
3. Créez un compte au premier lancement (le premier compte est automatiquement administrateur)

---

## 📋 Fonctionnalités

- **Éditeur GRAI** — grilles d'analyse décisionnelle, règles A-I, simulation de charge
- **Éditeur BPMN 2.0** — modélisation de processus métier, simulation BPSim
- **Éditeur DEVS** — systèmes à événements discrets, simulation LSIS
- **Éditeur Actigram étendu** — notation fonctionnelle, lien GRAI ↔ Actigram
- **Export PDF** — rapports individuels et rapport unifié multi-modèles
- **Bilingue** — français / anglais

---

## 📁 Données

Vos projets sont sauvegardés localement sur votre machine.
Ils persistent entre les sessions.

---

## ❓ Problèmes connus

**Erreur `ffmpeg.dll introuvable`** — installez Visual C++ Redistributable :
👉 https://aka.ms/vs/17/release/vc_redist.x64.exe

**Page blanche au démarrage** — vérifiez que Node.js est bien installé (`node --version` dans un terminal).
