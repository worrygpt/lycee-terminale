---
name: matrices-et-graphes
description: Matrices et graphes en Maths Expertes (calcul matriciel, inverse, puissances de matrices, suites de matrices U(n+1)=AU(n)+B, matrice d'adjacence, chaînes de longueur n, chaînes de Markov). À utiliser pour tout exercice de maths expertes sur les matrices, les graphes ou les évolutions d'états.
---

# Matrices et graphes (Maths Expertes)

## Rôle de Claude
Faire poser les calculs proprement (les erreurs viennent à 90 % du produit matriciel) et relier systématiquement matrices ↔ situations concrètes (évolutions, graphes).

## Calcul matriciel
- Matrice n×p, coefficient a_ij (ligne i, colonne j). Somme et produit par un réel : terme à terme.
- **Produit** A×B : possible si (colonnes de A) = (lignes de B) ; coefficient (i,j) = ligne i de A « scalaire » colonne j de B. **Non commutatif** : AB ≠ BA en général — ne jamais échanger !
- **Identité** I (des 1 sur la diagonale) : AI = IA = A.
- **Inverse** : A⁻¹ telle que AA⁻¹ = I. Pour A = (a b ; c d) : inversible ⟺ ad − bc ≠ 0, et A⁻¹ = 1/(ad−bc) × (d −b ; −c a). Résolution de systèmes : AX = B ⟺ X = A⁻¹B.
- **Puissances** Aⁿ : conjecture sur A², A³ puis **récurrence** ; ou formule donnée par l'énoncé (souvent via P·Dⁿ·P⁻¹ avec D diagonale — les étapes sont guidées).

## Suites de matrices (grand classique)
Uₙ₊₁ = A·Uₙ : alors Uₙ = Aⁿ·U₀ (récurrence rapide à rédiger).
Uₙ₊₁ = A·Uₙ + B : chercher l'état stable C = AC + B, poser Vₙ = Uₙ − C, montrer Vₙ₊₁ = A·Vₙ, d'où Uₙ = Aⁿ(U₀ − C) + C. Étude de la limite terme à terme.

## Graphes
- Sommets, arêtes, orienté ou non, degré d'un sommet ; somme des degrés = 2 × nombre d'arêtes.
- **Matrice d'adjacence** M : m_ij = nombre d'arêtes de i vers j.
- **Théorème clé** : le coefficient (i, j) de **Mⁿ** = nombre de **chaînes de longueur n** de i à j.
- Graphes pondérés par des probabilités (chaînes de Markov, selon le programme suivi) : matrice de transition (somme de chaque ligne = 1), état Pₙ₊₁ = Pₙ·M, état stable P = P·M.

## Pièges fréquents
Commuter un produit · dimensions incompatibles non vérifiées · développer (A+B)² = A² + 2AB + B² (FAUX : c'est A² + AB + BA + B²) · diviser par une matrice (on multiplie par l'inverse, du bon côté) · oublier de vérifier ad − bc ≠ 0 · récurrence de Uₙ = AⁿU₀ non rédigée.

## Entraînement
Gammes de produits 2×2 et 3×3 · un exercice type « évolution de populations sur 2 états » complet · lecture de graphe → matrice → nombre de chemins.
