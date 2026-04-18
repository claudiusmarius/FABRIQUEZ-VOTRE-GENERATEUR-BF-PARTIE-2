# FABRIQUEZ-VOTRE-GENERATEUR-BF-PARTIE-2

# DFTA266 - Partie 2 : Traitement du signal analogique

## 📌 Présentation

Cette partie du projet DFTA266 concerne le traitement analogique du signal issu du générateur DDS basé sur AD9833 et Seeeduino XIAO.

Le DDS fournit des signaux utiles, mais bruts :

- sinus et triangle ≈ 0,6 Vcc
- carré ≈ 5 Vcc
- signaux référencés au 0V
- amplitude non homogène selon le mode

L’objectif est donc de convertir ces signaux en une vraie sortie laboratoire, réglable et exploitable.

---

## 🔧 Fonctions réalisées

### ✔ Centrage du signal

Transformation du signal DDS unipolaire en signal centré autour de 0V.

### ✔ Réglage amplitude / gain

Double action :

- atténuation réglable
- amplification variable

### ✔ Offset de sortie

Ajout d’un décalage positif ou négatif ajustable.

### ✔ Adaptation du signal carré

Réduction automatique de l’amplitude du mode carré afin d’uniformiser les niveaux.

### ✔ Étage de sortie push-pull

Buffer de courant robuste permettant :

- meilleure tenue en charge
- protection partielle contre court-circuit
- sortie plus stable

---

## 🧪 Validation

Le montage a été validé :

- sous LTspice
- sur breadboard
- à l’oscilloscope

---

## 📂 Contenu du dépôt

- Schémas
- Fichiers LTspice
- Photos breadboard
- Notes techniques
- Vidéo YouTube associée

---

## 🎬 Série DFTA266

1. Générateur DDS AD9833 + Seeeduino XIAO  
2. Traitement analogique du signal  ← vous êtes ici  
3. Alimentation symétrique ±12V  
4. Mise en boîtier finale

---

## 📜 Licence

Projet personnel open hardware / open source à but pédagogique.
