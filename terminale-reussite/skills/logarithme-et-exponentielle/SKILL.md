---
name: logarithme-et-exponentielle
description: Fonctions exponentielle et logarithme népérien en Terminale (propriétés algébriques, équations et inéquations avec exp et ln, limites, croissances comparées, dérivées de exp(u) et ln(u)). À utiliser pour tout exercice avec e^x ou ln, résoudre des équations du type e^x=k ou ln(x)=k, ou des inéquations avec q^n.
---

# Logarithme et exponentielle (Spé Maths)

## Rôle de Claude
Ces deux fonctions sont partout au bac (suites, probas, équations différentielles, études de fonctions). Automatiser les propriétés algébriques par des gammes, puis travailler les équations/inéquations types.

## Propriétés à connaître par cœur
**Exponentielle** (définie sur ℝ, à valeurs dans ]0 ; +∞[, strictement croissante) :
e⁰ = 1 · e^(a+b) = eᵃ·eᵇ · e^(a−b) = eᵃ/eᵇ · e^(−a) = 1/eᵃ · (eᵃ)ⁿ = e^(na) · eˣ > 0 toujours.
**Logarithme népérien** (défini sur ]0 ; +∞[, strictement croissant, réciproque de exp) :
ln 1 = 0 · ln e = 1 · ln(ab) = ln a + ln b · ln(a/b) = ln a − ln b · ln(aⁿ) = n·ln a · ln(1/a) = −ln a · ln(√a) = ½·ln a.
**Liens** : e^(ln x) = x (x > 0) · ln(eˣ) = x · eˣ = y ⟺ x = ln y (y > 0).

## Équations et inéquations — méthodes
- eˣ = k : si k > 0, x = ln k ; si k ≤ 0, pas de solution. ln x = k ⟺ x = eᵏ (avec x > 0 !).
- e^(u(x)) = e^(v(x)) ⟺ u(x) = v(x) · ln u = ln v ⟺ u = v (avec u, v > 0).
- Croissance stricte : eᵃ < eᵇ ⟺ a < b ; ln a < ln b ⟺ a < b (a, b > 0). **Toujours vérifier le domaine avant d'appliquer ln.**
- Type qⁿ ≤ k (suites géométriques) : appliquer ln ; ⚠ si 0 < q < 1 alors ln q < 0 et l'inégalité **change de sens** en divisant.
- Équations « polynomiales en eˣ » : poser X = eˣ (avec X > 0), résoudre, revenir à x.

## Limites et croissances comparées
lim(x→+∞) eˣ = +∞ · lim(x→−∞) eˣ = 0 · lim(x→0⁺) ln x = −∞ · lim(x→+∞) ln x = +∞
lim(x→+∞) eˣ/x = +∞ · lim(x→−∞) x·eˣ = 0 · lim(x→+∞) ln(x)/x = 0 · lim(x→0⁺) x·ln x = 0
Hiérarchie : **exp écrase les puissances, qui écrasent ln**.

## Dérivées
(eˣ)' = eˣ · (eᵘ)' = u'·eᵘ · (ln x)' = 1/x · (ln u)' = u'/u (u > 0). Courbes : tangente de exp en 0 : y = x + 1 ; inégalité classique eˣ ≥ x + 1 ; ln x ≤ x − 1.

## Pièges fréquents
ln(a + b) ≠ ln a + ln b (aucune formule pour la somme !) · appliquer ln à un nombre négatif ou nul · oublier X > 0 après le changement de variable · oublier l'inversion du sens avec ln q < 0 · confondre (ln x)² et ln(x²).
