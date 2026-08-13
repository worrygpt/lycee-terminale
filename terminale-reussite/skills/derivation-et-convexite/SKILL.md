---
name: derivation-et-convexite
description: Dérivation, étude de fonctions et convexité en spé maths de Terminale (dérivées usuelles et composées, tableaux de variations, tangentes, convexité, points d'inflexion). À utiliser pour dériver une fonction, étudier ses variations, une tangente, la convexité, ou toute étude de fonction complète.
---

# Dérivation et convexité (Spé Maths)

## Rôle de Claude
Vérifier les calculs de dérivées de l'élève avant tout (source n°1 d'erreurs), puis structurer l'étude de fonction dans l'ordre canonique.

## Dérivées à connaître par cœur
xⁿ → n·xⁿ⁻¹ · 1/x → −1/x² · √x → 1/(2√x) · eˣ → eˣ · ln x → 1/x · cos x → −sin x · sin x → cos x
**Opérations** : (u+v)' = u'+v' · (ku)' = k·u' · (uv)' = u'v + uv' · (u/v)' = (u'v − uv')/v² · (1/v)' = −v'/v²
**Composées (essentielles en Terminale)** : (eᵘ)' = u'·eᵘ · (ln u)' = u'/u · (uⁿ)' = n·u'·uⁿ⁻¹ · (√u)' = u'/(2√u) · plus généralement (f∘u)' = u' × f'(u), en particulier x ↦ f(ax+b) a pour dérivée a·f'(ax+b).

## Étude de fonction — plan canonique
1. Domaine de définition (et de dérivabilité).
2. Limites aux bornes → asymptotes éventuelles.
3. Calcul de f'(x), **factorisation** pour étudier son signe.
4. Signe de f' → tableau de variations complet (flèches + limites + extremums, valeurs exactes).
5. Questions annexes : équation f(x) = k (corollaire du TVI), tangentes, position/courbe.

## Tangente
Équation de la tangente en a : **y = f'(a)(x − a) + f(a)**. Position courbe/tangente : signe de f(x) − [f'(a)(x−a) + f(a)] — ou argument de convexité (plus rapide, voir ci-dessous).

## Convexité (chapitre de Terminale)
- f **convexe** sur I ⟺ la courbe est au-dessus de toutes ses tangentes ⟺ f' croissante sur I ⟺ f''(x) ≥ 0 sur I. (Concave : tout s'inverse.)
- **Point d'inflexion** : point où la courbe traverse sa tangente ⟺ f'' s'annule EN CHANGEANT DE SIGNE.
- Applications bac : signe de f'' → tableau de convexité ; inégalités du type eˣ ≥ x + 1 (courbe au-dessus de la tangente en 0) ; lecture graphique (convexe = « tournée vers le haut »).

## Pièges fréquents
(uv)' ≠ u'v' · oublier le u' dans (eᵘ)' et (ln u)' · signe de f' non factorisé donc faux · confondre f' qui s'annule et point d'inflexion (c'est f'') · tableau de variations sans limites ni valeurs · « f'' = 0 donc inflexion » sans vérifier le changement de signe.

## Entraînement
Dictée de dérivées (10 fonctions en 5 min) · étude complète guidée puis en autonomie · exercices de convexité avec inégalités classiques.
