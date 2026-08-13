---
name: geometrie-dans-l-espace
description: Géométrie dans l'espace en Terminale spé maths (vecteurs, produit scalaire, orthogonalité, vecteur normal, équations cartésiennes de plans, représentations paramétriques de droites, intersections, distances, projeté orthogonal). À utiliser pour tout exercice de géométrie dans l'espace, souvent avec un cube ou un tétraèdre.
---

# Géométrie dans l'espace (Spé Maths)

## Rôle de Claude
Exercice le plus « méthodique » du bac : presque tout se résout avec une boîte à outils fixe. La faire appliquer dans l'ordre, coordonnées à l'appui, et faire dessiner/situer les points sur la figure.

## Boîte à outils (repère orthonormé)
- Vecteur AB = (x_B−x_A ; y_B−y_A ; z_B−z_A) · norme ‖u‖ = √(x²+y²+z²) · AB = ‖vecteur AB‖.
- **Produit scalaire** : u·v = xx' + yy' + zz' = ‖u‖·‖v‖·cos(u,v). **u ⊥ v ⟺ u·v = 0**.
- **Colinéarité** : u et v colinéaires ⟺ coordonnées proportionnelles → alignement, parallélisme.
- Points coplanaires / vecteurs coplanaires : w = a·u + b·v (résoudre le système).

## Droites et plans
- **Droite** passant par A de vecteur directeur u : représentation **paramétrique** x = x_A + t·x_u ; y = … ; z = … (t ∈ ℝ).
- **Plan** de vecteur normal n(a ; b ; c) : équation **cartésienne ax + by + cz + d = 0** (d avec un point du plan).
- Trouver un vecteur normal à (ABC) : n·AB = 0 et n·AC = 0 → système (fixer une coordonnée).
- **Droite ⊥ plan** ⟺ vecteur directeur colinéaire au normal. **Droite ∥ plan** ⟺ directeur ⊥ normal. **Plans ∥** ⟺ normaux colinéaires.
- **Intersections** : droite ∩ plan → injecter la paramétrique dans l'équation du plan, résoudre en t. Deux plans sécants → droite (résoudre le système en paramétrant).

## Projeté orthogonal et distances
- **Projeté orthogonal H de M sur un plan P** : droite passant par M dirigée par n, intersection avec P. Alors MH = distance de M à P.
- Distance de M(x₀;y₀;z₀) au plan ax+by+cz+d = 0 : **|ax₀+by₀+cz₀+d| / √(a²+b²+c²)** (utile à connaître ou à savoir retrouver via le projeté).
- Projeté sur une droite : H sur la droite avec MH·u = 0 (résoudre en t). Applications : volumes (V = ⅓ × B × h pour tétraèdre/pyramide), aires, angles via cos.

## Pièges fréquents
Confondre vecteur normal (plan) et vecteur directeur (droite) · vérifier qu'un point appartient à la droite en oubliant que t doit être LE MÊME pour x, y, z · signe de d dans l'équation du plan · dire « orthogonales » pour deux droites non coplanaires sans produit scalaire nul · calculs non posés (tout écrire, les erreurs viennent du calcul mental).
