---
name: combinatoire-et-denombrement
description: Combinatoire et dénombrement en Terminale spé maths (principes additif et multiplicatif, k-uplets, arrangements, permutations, combinaisons, triangle de Pascal). À utiliser pour compter des possibilités, choisir entre arrangement et combinaison, calculer des coefficients binomiaux ou résoudre un problème de dénombrement.
---

# Combinatoire et dénombrement (Spé Maths)

## Rôle de Claude
Le nerf de la guerre : choisir le BON modèle de comptage. Toujours poser les deux questions décisives avec l'élève : **l'ordre compte-t-il ?** et **peut-on répéter un élément ?**

## Les principes de base
- **Multiplicatif** : une situation en étapes indépendantes → on multiplie les nombres de choix.
- **Additif** : des cas disjoints → on additionne. (Cas non disjoints : ajouter puis retrancher l'intersection.)
- **Passage au complémentaire** : « au moins un… » se compte souvent par Total − « aucun ».

## Les 4 modèles à connaître (E ensemble à n éléments)
| Situation | Ordre | Répétition | Nombre |
|---|---|---|---|
| **k-uplets** de E (tirages successifs avec remise, codes) | oui | oui | nᵏ |
| **Arrangements** (tirages successifs sans remise, podiums) | oui | non | n × (n−1) × … × (n−k+1) = n!/(n−k)! |
| **Permutations** (ranger tous les éléments) | oui | non | n! |
| **Combinaisons** (choisir une partie, une main, un comité) | non | non | (n k) = n!/(k!(n−k)!) |
Nombre de parties d'un ensemble à n éléments : 2ⁿ.

## Coefficients binomiaux — propriétés
(n 0) = (n n) = 1 · (n 1) = n · **symétrie** : (n k) = (n n−k) · **relation de Pascal** : (n k) + (n k+1) = (n+1 k+1) → triangle de Pascal pour calculer de proche en proche · Σₖ (n k) = 2ⁿ.

## Démarche type sur un problème
1. Reformuler : qu'est-ce qu'« un cas » exactement ?
2. Ordre ? Répétition ? → choisir le modèle (ou découper en étapes mixtes : ex. choisir 2 filles parmi 12 ET 3 garçons parmi 15 → (12 2) × (15 3)).
3. Vérifier avec un petit exemple (n = 3) si le doute persiste.
4. Rédiger : justifier le modèle en une phrase avant le calcul.

## Pièges fréquents
Utiliser un arrangement pour une main de cartes (l'ordre ne compte pas !) · oublier de multiplier les étapes · compter deux fois des cas non disjoints · confondre « au moins un » et « exactement un » · (n k) avec k > n (ça vaut 0).
