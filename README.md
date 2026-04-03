# InterventionGaz — Application Mobile WinDev

Application mobile développée avec **WinDev** dans le cadre du BTS SIO SLAM (2ème année).  
Le projet simule un outil terrain destiné à la gestion et au suivi des interventions liées au gaz pour une entreprise de service.

---

## 📱 Description

L'application permet à un technicien ou agent de terrain de :

- **Saisir une fiche d'intervention** avec les informations clés (client, adresse, type d'intervention, observations)
- **Consulter la liste des interventions** existantes via une table/zone répétée
- **Naviguer** entre les différents écrans de l'application depuis une interface mobile adaptée

---

## ⚙️ Technologies utilisées

| Technologie | Usage |
|---|---|
| **WinDev Mobile** | Développement de l'application mobile |
| **WinDev (W-Langage)** | Logique applicative et gestion des données |
| **HyperFileSQL** | Base de données intégrée (`.wdd`, `.xdd`) |
| **RAD WinDev** | Génération automatique des fenêtres de saisie |

---

## 🗂️ Structure du projet

```
InterventionGaz/
├── GazService.wdp          # Fichier projet principal WinDev
├── GazService.wdd          # Analyse / modèle de données
├── GazService.xdd          # Description des données HyperFileSQL
├── GazService.env          # Environnement de configuration
├── FI_Fiche_Saisie_Intervention.wdw.cache  # Fenêtre de saisie
├── FI_ZR_Intervention.wdw.cache            # Zone répétée / liste
├── Exe/                    # Exécutables générés
├── GABARITS/               # Gabarits d'interface
├── Themes/                 # Thèmes visuels
└── Sauvegarde/             # Sauvegardes du projet
```

---

## 🚀 Lancer le projet

1. Ouvrir **WinDev** (version compatible avec le projet)
2. Ouvrir le fichier `GazService.wdp`
3. Compiler et lancer depuis l'environnement WinDev ou déployer via le dossier `Exe/`

---

## 👤 Auteur

**Mateo ROCA** — Étudiant BTS SIO SLAM  
[Portfolio](https://mateo.portfoliobtssio66.fr) · [GitHub](https://github.com/Mateo-R13)
