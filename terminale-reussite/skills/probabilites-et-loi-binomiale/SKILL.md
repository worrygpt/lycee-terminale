---
name: probabilites-et-loi-binomiale
description: Probabilités de Terminale spé maths - schéma de Bernoulli, loi binomiale, variables aléatoires, espérance et variance, sommes de variables, inégalité de Bienaymé-Tchebychev, loi des grands nombres. À utiliser pour tout exercice de probabilités, calculer P(X=k), une espérance, ou travailler les probabilités conditionnelles et l'indépendance.
---

# Probabilités et loi binomiale (Spé Maths)

## Rôle de Claude
Faire modéliser AVANT de calculer : définir les événements, l'arbre ou la loi, justifier le modèle (c'est là que sont les points de rédaction).

## Rappels indispensables (programme de Première, toujours utilisés)
- **Conditionnelle** : P_A(B) = P(A∩B)/P(A). **Probabilités totales** (avec partition A, Ā) : P(B) = P(A)·P_A(B) + P(Ā)·P_Ā(B). Outil : l'arbre pondéré (produit le long des branches, somme des chemins).
- **Indépendance** : A et B indépendants ⟺ P(A∩B) = P(A)·P(B) ⟺ P_A(B) = P(B).

## Schéma de Bernoulli et loi binomiale
- Épreuve de Bernoulli : deux issues, succès (p) / échec (1−p). Répétition de n épreuves **identiques et indépendantes** : schéma de Bernoulli.
- X = nombre de succès suit la **loi binomiale B(n ; p)** : **P(X = k) = (n k)·pᵏ·(1−p)ⁿ⁻ᵏ**.
- **E(X) = np** · **V(X) = np(1−p)** · σ(X) = √(np(1−p)).
- Calculs types : P(X ≤ k), P(X ≥ k) = 1 − P(X ≤ k−1) (calculatrice ou Python) ; « au moins un succès » : 1 − (1−p)ⁿ ; trouver n minimal tel que 1 − (1−p)ⁿ ≥ 0,99 → inéquation avec ln (attention au sens !).
- **Rédaction attendue** : « On répète n fois de façon identique et indépendante une épreuve de Bernoulli de paramètre p ; X compte les succès donc X suit B(n ; p). »

## Sommes de variables aléatoires
E(X+Y) = E(X) + E(Y) (toujours) · E(aX+b) = aE(X)+b · V(aX+b) = a²V(X) · si X, Y **indépendantes** : V(X+Y) = V(X) + V(Y).
Échantillon de taille n (Sₙ somme, Mₙ = Sₙ/n moyenne) : E(Sₙ) = nμ, V(Sₙ) = nσ² ; **E(Mₙ) = μ, V(Mₙ) = σ²/n** — la moyenne se concentre quand n grandit.

## Concentration et loi des grands nombres
- **Inégalité de Bienaymé-Tchebychev** : P(|X − E(X)| ≥ a) ≤ V(X)/a².
- **Loi des grands nombres** : P(|Mₙ − μ| ≥ a) → 0 quand n → +∞ : la moyenne d'échantillon se rapproche de l'espérance (justifie l'estimation d'une probabilité par une fréquence).

## Pièges fréquents
Oublier de justifier le modèle binomial (identiques + indépendantes) · confondre P(X ≥ k) et 1 − P(X ≤ k) (décalage de 1) · V(X+Y) = V(X)+V(Y) sans l'indépendance · arbre incomplet · probabilité hors de [0 ; 1] non détectée.
