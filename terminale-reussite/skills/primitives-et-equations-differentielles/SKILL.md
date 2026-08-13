---
name: primitives-et-equations-differentielles
description: Primitives et équations différentielles en Terminale spé maths (primitives usuelles et composées, équations y'=ay et y'=ay+b, problème de Cauchy, condition initiale). À utiliser pour chercher une primitive, vérifier qu'une fonction est solution, ou résoudre une équation différentielle avec condition initiale.
---

# Primitives et équations différentielles (Spé Maths)

## Rôle de Claude
Faire vérifier chaque primitive en la re-dérivant (réflexe absolu), et faire rédiger la résolution des équations différentielles dans les formes exactes du cours.

## Primitives — définition et usuelles
F est une primitive de f sur I si F' = f. Deux primitives diffèrent d'une constante : F(x) + C.
xⁿ → xⁿ⁺¹/(n+1) · 1/x² → −1/x · 1/√x → 2√x · 1/x → ln x (sur ]0;+∞[) · eˣ → eˣ · cos x → sin x · sin x → −cos x · cos(ax+b) → (1/a)sin(ax+b) · sin(ax+b) → −(1/a)cos(ax+b).

## Primitives de formes composées (à reconnaître)
u'·eᵘ → eᵘ · u'/u → ln(u) (u > 0) · u'·uⁿ → uⁿ⁺¹/(n+1) · u'/u² → −1/u · u'/√u → 2√u.
**Méthode** : repérer u, calculer u', ajuster la constante multiplicative. Ex. : x·e^(x²) = ½·(2x·e^(x²)) → primitive ½·e^(x²).
Trouver LA primitive vérifiant F(x₀) = y₀ : forme générale + C, puis déterminer C avec la condition.

## Équations différentielles au programme
- **y' = a·y** : solutions y(x) = C·e^(ax), C ∈ ℝ.
- **y' = a·y + b** (a ≠ 0) : solution particulière constante y₀ = −b/a ; solutions générales **y(x) = C·e^(ax) − b/a**.
- **Problème de Cauchy** : condition initiale y(x₀) = y₀ → déterminer C. Il y a alors une unique solution.
- Vérifier qu'une fonction est solution : calculer y' et remplacer dans l'équation (question fréquente et facile — ne pas la rater).
- Habillage bac : équations se ramenant à ces formes par changement de fonction (z = y − ℓ), modèles concrets (refroidissement, populations, charge électrique) — bien traduire l'énoncé en équation.

## Rédaction type
« L'équation y' = −2y + 6 a pour solutions les fonctions x ↦ C·e^(−2x) + 3, C ∈ ℝ. La condition y(0) = 5 donne C + 3 = 5 donc C = 2. Ainsi y(x) = 2e^(−2x) + 3. »

## Pièges fréquents
Oublier « + C » (ou l'oublier au moment de la condition initiale) · signe de −b/a · confondre dériver et primitiver · primitive de 1/x écrite −1/x² (c'est la dérivée !) · oublier le facteur 1/a pour cos(ax+b) · ne pas re-dériver pour vérifier.
