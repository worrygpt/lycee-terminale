---
name: limites-et-continuite
description: Limites de fonctions, asymptotes, continuité et théorème des valeurs intermédiaires (TVI) en spé maths de Terminale. À utiliser pour calculer une limite, lever une forme indéterminée, étudier une asymptote, appliquer le TVI ou son corollaire, ou justifier l'existence et l'unicité d'une solution d'équation.
---

# Limites, continuité et TVI (Spé Maths)

## Rôle de Claude
Guider le calcul pas à pas ; exiger la justification de chaque étape comme au bac (« par somme », « par produit », « par croissances comparées », « d'après le TVI »).

## Calcul de limites — réflexes
1. Remplacer mentalement : si pas de forme indéterminée (FI), conclure par opérations sur les limites.
2. FI classiques : « +∞ − ∞ », « 0 × ∞ », « ∞/∞ », « 0/0 ». Leviers :
   - **Polynômes/quotients en ±∞** : factoriser par le terme de plus haut degré.
   - **Racines** : multiplier par la quantité conjuguée.
   - **Croissances comparées** (à connaître par cœur) : lim(x→+∞) ln(x)/x = 0 ; lim(x→+∞) eˣ/xⁿ = +∞ ; lim(x→+∞) xⁿ/eˣ = 0 ; lim(x→0⁺) x·ln(x) = 0. Retenir : **eˣ ≫ xⁿ ≫ ln x**.
   - **Composée** : poser X = u(x), utiliser lim de u puis lim de f en X.
3. Limites à gauche/droite quand le dénominateur s'annule : étudier le signe du dénominateur.

## Asymptotes
- lim(x→±∞) f(x) = ℓ → asymptote **horizontale** y = ℓ.
- lim(x→a) f(x) = ±∞ → asymptote **verticale** x = a.
- Position relative : signe de f(x) − ℓ.

## Continuité et TVI
- f dérivable ⟹ f continue (réciproque fausse). Les fonctions usuelles sont continues sur leur domaine ; l'affirmer suffit.
- **TVI** : f continue sur [a ; b], k compris entre f(a) et f(b) ⟹ l'équation f(x) = k admet **au moins** une solution dans [a ; b].
- **Corollaire (le plus utilisé au bac)** : f continue et **strictement monotone** sur [a ; b], k entre f(a) et f(b) ⟹ solution **unique**. Rédaction : continuité + stricte monotonie (via tableau de variations) + encadrement de k, puis « d'après le corollaire du TVI… ».
- Extension aux intervalles ouverts/infinis avec les limites aux bornes.
- Encadrement de la solution α : balayage/dichotomie à la calculatrice ou en Python ; donner l'amplitude demandée (ex. 10⁻²).

## Pièges fréquents
Oublier de dire « continue » ou « strictement » · conclure à l'unicité avec le TVI simple · confondre limite en a et valeur f(a) · signe du dénominateur non étudié pour les limites infinies · croissances comparées citées sans les écrire.
