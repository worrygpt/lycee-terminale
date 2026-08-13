---
name: nombres-complexes
description: Nombres complexes en Maths Expertes (forme algébrique, module et argument, forme exponentielle, formules de Moivre et d'Euler, racines n-ièmes, équations du second degré, applications géométriques). À utiliser pour tout exercice de maths expertes sur les complexes, calculs, équations ou géométrie avec affixes.
---

# Nombres complexes (Maths Expertes)

## Rôle de Claude
Faire jongler entre les trois écritures (algébrique, trigonométrique, exponentielle) : le bon choix de forme fait 80 % de la solution. Somme/équation → algébrique ; produit/quotient/puissance → exponentielle.

## Formes et conversions
- **Algébrique** : z = a + ib, a = Re(z), b = Im(z), i² = −1. **Conjugué** : z̄ = a − ib ; z·z̄ = a² + b² ; règles : conjugué d'une somme/produit/quotient = somme/produit/quotient des conjugués.
- **Module** : |z| = √(a² + b²) ; |z·z'| = |z||z'| ; |z/z'| = |z|/|z'| ; |zⁿ| = |z|ⁿ.
- **Argument** (z ≠ 0) : θ tel que cos θ = a/|z| et sin θ = b/|z| (repérer les valeurs remarquables). arg(zz') = arg z + arg z' [2π] ; arg(z/z') = arg z − arg z' [2π] ; arg(z̄) = −arg z.
- **Trigonométrique / exponentielle** : z = r(cos θ + i sin θ) = r·e^(iθ) avec r = |z|. e^(iθ)·e^(iθ') = e^(i(θ+θ')).
- Quotient en algébrique : multiplier haut et bas par le conjugué du dénominateur.

## Formules clés
- **Moivre** : (cos θ + i sin θ)ⁿ = cos(nθ) + i sin(nθ) — soit (e^(iθ))ⁿ = e^(inθ).
- **Euler** : cos θ = (e^(iθ) + e^(−iθ))/2 · sin θ = (e^(iθ) − e^(−iθ))/(2i). Applications : linéariser cos²θ, cos³θ… ; retrouver les formules d'addition.

## Équations
- **Second degré à coefficients réels** az² + bz + c = 0 : Δ < 0 → deux racines complexes conjuguées z = (−b ± i√(−Δ))/(2a).
- **zⁿ = a** : passer en exponentielle. Racines n-ièmes de l'unité : e^(2ikπ/n), k = 0, …, n−1 (n racines, sommets d'un polygone régulier, somme nulle pour n ≥ 2).
- Factorisation : si z₀ racine d'un polynôme, factoriser par (z − z₀).

## Géométrie avec les affixes
M(z) point d'affixe z. **AB = |z_B − z_A|** · vecteur AB d'affixe z_B − z_A · milieu : (z_A + z_B)/2 · angle (AB, AC) = arg((z_C − z_A)/(z_B − z_A)) [2π] → alignement (argument 0 ou π, quotient réel), orthogonalité (± π/2, quotient imaginaire pur), triangles particuliers · |z − z_A| = r : cercle de centre A rayon r · multiplication par e^(iθ) : rotation d'angle θ autour de O.

## Pièges fréquents
Écrire |z|² = z² (faux : |z|² = z·z̄) · argument défini pour z = 0 · oublier [2π] · racine carrée d'un nombre négatif écrite √(−4) au lieu de 2i · comparer des complexes avec < (interdit) · oublier des racines dans zⁿ = a (il y en a n).
