---
name: suites-et-recurrence
description: Suites numériques et raisonnement par récurrence en spé maths de Terminale (limites de suites, théorèmes de convergence, suites géométriques et arithmético-géométriques, rédaction de la récurrence). À utiliser pour tout exercice ou révision sur les suites, une démonstration par récurrence, la convergence, ou les suites auxiliaires.
---

# Suites et récurrence (Spé Maths)

## Rôle de Claude
Faire chercher avant d'aider : demander ce que l'élève a tenté, donner un indice, puis la méthode, puis seulement la solution complète — toujours avec la rédaction modèle exigée au bac.

## Le raisonnement par récurrence (rédaction type à respecter mot pour mot)
Pour montrer que P(n) est vraie pour tout n ≥ n₀ :
1. **Initialisation** : vérifier P(n₀).
2. **Hérédité** : « Soit n ≥ n₀. Supposons P(n) vraie (hypothèse de récurrence). Montrons P(n+1). » … calcul qui UTILISE l'hypothèse …
3. **Conclusion** : « P est initialisée et héréditaire, donc par récurrence, P(n) est vraie pour tout n ≥ n₀. »
Pièges : oublier l'initialisation ; « supposer P(n) pour tout n » (faux : pour UN n fixé) ; ne pas utiliser l'hypothèse de récurrence.

## Limites de suites — l'essentiel
- **q^n** : si −1 < q < 1, lim = 0 ; si q > 1, lim = +∞ ; si q ≤ −1, pas de limite ; si q = 1, lim = 1.
- **Opérations** sur les limites + formes indéterminées : « ∞ − ∞ », « 0 × ∞ », « ∞/∞ », « 0/0 » → factoriser par le terme dominant, ou utiliser le conjugué.
- **Comparaison** : si uₙ ≥ vₙ et vₙ → +∞ alors uₙ → +∞. **Gendarmes** : si vₙ ≤ uₙ ≤ wₙ et vₙ, wₙ → ℓ alors uₙ → ℓ.
- **Théorème de la limite monotone** : toute suite croissante et majorée converge (décroissante minorée aussi). Croissante non majorée → +∞.
- Montrer la monotonie : signe de uₙ₊₁ − uₙ, ou uₙ₊₁/uₙ vs 1 (termes > 0), ou récurrence.

## Suites arithmético-géométriques (grand classique du bac)
uₙ₊₁ = a·uₙ + b (a ≠ 1) : l'énoncé fait poser vₙ = uₙ − ℓ où ℓ = b/(1−a) (point fixe, solution de ℓ = aℓ + b).
Montrer que (vₙ) est géométrique de raison a → vₙ = v₀·aⁿ → uₙ = (u₀ − ℓ)·aⁿ + ℓ → limite selon a.

## Méthodes types du bac
- Étudier f telle que uₙ₊₁ = f(uₙ) : récurrence pour l'encadrement/monotonie, limite = solution de f(ℓ) = ℓ (si f continue et uₙ → ℓ).
- Seuil : « plus petit n tel que uₙ > A » → boucle while en Python (voir python-pour-les-maths).
- Sommes géométriques : 1 + q + … + qⁿ = (1 − qⁿ⁺¹)/(1 − q) pour q ≠ 1.

## Pièges fréquents
Confondre « majorée » et « convergente » · conclure ℓ = f(ℓ) sans avoir prouvé la convergence · erreurs de signe dans uₙ₊₁ − uₙ · oublier de justifier vₙ ≠ 0 quand on divise.
