# Implémentation de Modèles de Diffusion (DDPM & CDM)

Ce repository contient plusieurs implémentations de modèles de diffusion, en commençant par un Denoising Diffusion Probabilistic Model (DDPM) jusqu'à une version conditionnelle (CDM). Ces exercices permettent d'explorer la génération d'images en utilisant un processus de diffusion et de débruitage.

## Contenu du repository

### 1. Implémentation de DDPM et du Processus d'échantillonnage
**Objectif :**
- Comprendre le fonctionnement des modèles de diffusion probabilistes (DDPM).
- Apprendre comment les images sont générées en inversant un processus de diffusion de bruit.
- Implémenter le processus de sampling pour débruiter progressivement une image à partir du bruit pur.

### 2. Implémentation de DDPM et Processus d'Entraîment
**Objectif :**
- Entraîner un modèle DDPM à partir de données d'images.
- Implémenter la fonction de perte et l'apprentissage du réseau de débruitage.
- Observer l'évolution de la qualité des images générées à mesure que le modèle s'améliore.

### 3. Entraînement d'un Modèle de Diffusion Conditionnel (CDM)
**Objectif :**
- Étendre l'approche DDPM pour permettre la génération conditionnelle d'images.
- Conditionner le modèle sur des informations additionnelles (ex: labels de classe, descriptions textuelles, attributs structurés).
- Expérimenter avec un Conditional Denoising Diffusion Model (CDDM) pour un contrôle plus précis des images générées.

Les modèles entraînés sont enregistrés dans le fichier `models`.
