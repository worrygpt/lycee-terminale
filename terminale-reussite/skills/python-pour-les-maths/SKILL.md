---
name: python-pour-les-maths
description: Python pour les maths de Terminale (fonctions, boucles, listes, seuils avec while, suites, dichotomie, simulations de probabilités). À utiliser dès qu'un exercice de maths contient un programme Python à compléter, expliquer ou écrire, ou pour s'entraîner à l'algorithmique du bac.
---

# Python pour les maths (Spé Maths)

## Rôle de Claude
Au bac, on demande surtout de **compléter** ou **interpréter** un script court. Entraîner l'élève à lire du code ligne par ligne (tableau d'états des variables) et à connaître les 5 squelettes classiques par cœur.

## Les 5 squelettes à connaître
**1. Calcul des termes d'une suite** (uₙ₊₁ = f(uₙ)) :
```python
def suite(n):
    u = 2                # u0
    for i in range(n):   # n itérations
        u = 3*u - 1      # relation de récurrence
    return u
```
**2. Seuil avec while** (« plus petit n tel que uₙ > A ») :
```python
def seuil(A):
    u, n = 2, 0
    while u <= A:
        u = 3*u - 1
        n = n + 1
    return n
```
**3. Somme / liste de termes** :
```python
S = 0
for k in range(1, n+1):
    S = S + 1/k
```
**4. Dichotomie** (solution de f(x) = 0 sur [a ; b] à eps près) :
```python
def dicho(a, b, eps):
    while b - a > eps:
        m = (a + b) / 2
        if f(a) * f(m) <= 0:
            b = m
        else:
            a = m
    return a, b
```
**5. Simulation / fréquence** (loi binomiale, Monte-Carlo) :
```python
from random import random
def freq(n, p):
    c = 0
    for i in range(n):
        if random() < p:
            c = c + 1
    return c / n
```

## Points de langage à maîtriser
`range(n)` = 0 à n−1 (n valeurs) ; `range(a, b)` = a à b−1 · indentation = structure du programme · `**` puissance, `%` reste, `//` quotient · listes : `L.append(x)`, `L[k]`, `len(L)` · différence for (nombre d'itérations connu) / while (condition d'arrêt) · `def`/`return`.

## Questions types du bac et réflexes
- « Que renvoie ce programme ? » → tableau d'évolution des variables, itération par itération.
- « Compléter les lignes » → identifier le squelette correspondant.
- « Modifier pour que… » → changer condition du while, relation de récurrence ou valeur initiale.
- « Interpréter le résultat dans le contexte » → relier à la suite/limite/probabilité de l'énoncé.

## Pièges fréquents
Décalage d'indices avec range · condition du while inversée (boucle infinie ou arrêt immédiat) · variables non initialisées · confondre u = 3*u − 1 (écrase u) avec une équation · oublier return.
