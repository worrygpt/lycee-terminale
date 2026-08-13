---
name: dipole-rc
description: Dynamique du dipôle RC en Terminale spé physique-chimie (condensateur, capacité, charge et décharge, équation différentielle, constante de temps tau=RC, détermination graphique, intensité et tension). À utiliser pour tout exercice sur le circuit RC, les condensateurs, ou les équations différentielles en électricité.
---

# Dipôle RC (Spé Physique-Chimie)

## Rôle de Claude
C'est le chapitre-pont avec les maths (équations différentielles) : faire établir l'équation par les lois de l'électricité, la résoudre proprement, puis exploiter les courbes.

## Le condensateur
- Deux armatures en regard ; charge q sur l'armature positive : **q = C·u_C** (C = capacité en farads F ; ordres de grandeur μF, nF).
- **Intensité** : i = dq/dt = **C·du_C/dt**. Convention récepteur (flèches de u et i opposées).
- Le condensateur stocke de l'énergie : E = ½·C·u_C².

## Charge d'un condensateur (circuit E, R, C)
Loi des mailles : E = u_R + u_C = R·i + u_C → **équation différentielle** :
**du_C/dt + u_C/(RC) = E/(RC)**
- Solution avec u_C(0) = 0 : **u_C(t) = E·(1 − e^(−t/τ))** avec **τ = R·C** (constante de temps, en secondes — vérifier l'homogénéité : Ω × F = s).
- Intensité : i(t) = (E/R)·e^(−t/τ) (maximale au début, tend vers 0).
- Régime transitoire → régime permanent (u_C → E, i → 0 : le condensateur se comporte comme un interrupteur ouvert).

## Décharge (condensateur chargé dans R)
Équation : du_C/dt + u_C/(RC) = 0 → **u_C(t) = E·e^(−t/τ)**.

## Déterminer τ graphiquement (3 méthodes à connaître)
1. **63 %** : à t = τ, u_C = 0,63·E (charge) ou 0,37·E (décharge).
2. **Tangente à l'origine** : elle coupe l'asymptote à t = τ.
3. À t = 5τ, on considère le régime permanent atteint (~99 %) : durée de charge ≈ 5τ.

## Méthode type au bac
1. Schéma, flécher tensions et courant. 2. Loi des mailles + q = Cu_C. 3. Mettre l'équation sous la forme canonique demandée. 4. **Vérifier** qu'une solution proposée convient (la dériver, l'injecter, vérifier la condition initiale) OU résoudre directement (cours de maths). 5. Exploiter : τ, valeurs à un instant, influence de R et C (τ augmente avec les deux).

## Pièges fréquents
Oublier la condition initiale · confondre charge (1 − e) et décharge (e) · τ = R + C ou R/C (faux : produit) · tangente mal tracée · i = C·du/dt oublié quand on demande i(t) · unités : ms sur le graphique et s dans les calculs · dire que u_C est discontinu (u_C est TOUJOURS continue).
