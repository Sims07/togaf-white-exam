# 🎓 TOGAF EA® Foundation - Simulateur d'Examen Part 1 (OGEA-F101)

Une application web interactive (https://sims07.github.io/togaf-white-exam/), légère et moderne conçue pour vous entraîner efficacement à la certification **TOGAF® Enterprise Architecture Part 1 (OGEA-F101)** en français.

L'application est entièrement développée dans un unique fichier HTML autonome (`togaf_exam_ogea_f101.html`) s'appuyant sur **Tailwind CSS**, ce qui la rend extrêmement facile à héberger ou à utiliser localement sans aucune configuration de serveur lourde.

---

## ⚠️ Avertissement de Non-Affiliation / Disclaimer

> **Important :** Ce projet est un outil d'apprentissage communautaire indépendant.
>
> * **Non-officiel :** Ce simulateur n'est pas affilié, associé, autorisé, approuvé ou officiellement lié à *The Open Group* (propriétaire de la marque déposée TOGAF®).
> * **Génération par IA :** Les questions de l'examen blanc "Difficile" pré-embarqué, ainsi que la structure des explications, ont été générées et affinées à l'aide de l'intelligence artificielle **Google Gemini**. Elles s'inspirent fidèlement de la documentation et du style de l'examen d'origine, mais n'en constituent pas des questions réelles d'examens officiels divulguées.
> * **Usage :** Utilisez cet outil comme un complément d'entraînement pratique et ludique, et non comme l'unique moyen de révision ou comme une garantie absolue de réussite à l'examen officiel.

---

## ✨ Fonctionnalités clés

### 🧩 3 Niveaux de Difficulté
* **Facile (Vert) :** Axé sur les définitions indispensables, les acronymes clés et la structure globale de l'ADM. Charge automatiquement le fichier `./examen_blanc_togaf_ea_niveau_facile.json`.
* **Moyen (Jaune) :** Traite des relations entre phases, de l'alignement stratégique et de la gouvernance. Charge automatiquement le fichier `./examen_blanc_togaf_ea_niveau_moyen.json`.
* **Difficile (Rouge) :** Scénarios d'architecture d'entreprise complexes et études de cas issus du modèle officiel (questions pré-embarquées).

### ⚡ 2 Modes d'Entraînement
* **Mode Examen Classique :** 40 questions minutées. Votre score et le rapport d'erreurs ne sont dévoilés qu'à la toute fin.
* **Mode Interactif :** Validation immédiate de votre choix, correction visuelle en vert/rouge et affichage instantané de l'explication d'architecture associée.

### 💾 Persistance de Session (Pause & Reprise)
Vous devez interrompre vos révisions ? Revenez au menu principal à tout moment. Votre progression, votre score temporaire et le chronomètre restant sont sauvegardés pour reprendre exactement là où vous vous étiez arrêté.

### 🖼️ Schémas d'Architecture Dynamiques
Les questions faisant référence à des figures clés du standard intègrent de magnifiques schémas vectoriels SVG interactifs dessines à la volée (*Roue ADM*, *Cadre de Contenu*, *Capacités d'AE*).

### ⚙️ Panneau de Configuration Avancé
Modifiez les URLs locales ou distantes pour injecter vos propres fichiers d'examens au format JSON via un menu de paramétrage dédié (accessible via l'icône engrenage).
