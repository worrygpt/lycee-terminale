---
name: calcul-integral
description: Calcul intégral en Terminale spé maths (intégrale et aire, primitive, propriétés, valeur moyenne, intégration par parties, aire entre deux courbes). À utiliser pour calculer une intégrale, une aire sous une courbe, une valeur moyenne, faire une intégration par parties ou encadrer une intégrale.
---

# Calcul intégral (Spé Maths)

## Rôle de Claude
Relier systématiquement l'intégrale à son sens (aire, valeur moyenne) et faire vérifier les calculs de primitives par dérivation.

## Définition et calcul
Pour f continue sur [a ; b] et F une primitive de f : **∫ₐᵇ f(x)dx = F(b) − F(a)** (noté [F(x)]ₐᵇ).
Si f ≥ 0 sur [a ; b], l'intégrale est l'**aire** (en unités d'aire) du domaine entre la courbe, l'axe des abscisses et les droites x = a, x = b. Si f ≤ 0, l'aire vaut −∫ₐᵇ f.

## Propriétés
- Linéarité : ∫(αf + βg) = α∫f + β∫g.
- **Relation de Chasles** : ∫ₐᵇ + ∫ᵇᶜ = ∫ₐᶜ.
- ∫ₐᵃ f = 0 ; ∫ᵇₐ f = −∫ₐᵇ f.
- **Positivité** : si f ≥ 0 sur [a;b] (a ≤ b), ∫ₐᵇ f ≥ 0. **Croissance** : f ≤ g ⟹ ∫f ≤ ∫g → encadrements d'intégrales (méthode : encadrer f sur [a;b] puis intégrer l'encadrement).
- **Valeur moyenne** de f sur [a ; b] : μ = 1/(b−a) · ∫ₐᵇ f(x)dx.
- **Aire entre deux courbes** : si f ≥ g sur [a;b], aire = ∫ₐᵇ (f(x) − g(x))dx. Étudier d'abord la position relative (signe de f − g).

## Intégration par parties (IPP)
Pour u, v dérivables à dérivées continues : **∫ₐᵇ u'(x)v(x)dx = [u(x)v(x)]ₐᵇ − ∫ₐᵇ u(x)v'(x)dx**.
Choix : dériver ce qui se simplifie (polynôme, ln), primitiver ce qui reste stable (eˣ, cos, sin). Classiques : ∫x·eˣdx (dériver x) · ∫ln(x)dx = ∫1·ln(x)dx (dériver ln, primitiver 1) · ∫x·cos(x)dx.

## Suites d'intégrales (grand classique du bac)
Iₙ = ∫ₐᵇ fₙ(x)dx : monotonie via le signe de Iₙ₊₁ − Iₙ = ∫(fₙ₊₁ − fₙ) ; encadrement de fₙ → encadrement de Iₙ → limite par gendarmes ; parfois relation de récurrence par IPP.

## Pièges fréquents
Oublier que « aire » exige f ≥ 0 (sinon découper selon le signe) · aire entre courbes sans vérifier qui est au-dessus · erreurs de signe dans [F(x)]ₐᵇ · IPP avec mauvais choix de u et v (si ça se complique, inverser) · oublier les unités d'aire quand l'énoncé donne un repère avec échelle.
