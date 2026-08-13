---
name: ece-et-mesures
description: Préparation aux ECE (épreuves de compétences expérimentales) de physique-chimie et maîtrise des mesures et incertitudes (protocole, verrerie, incertitude-type, écart normalisé z-score, chiffres significatifs, notation scientifique). À utiliser pour préparer l'ECE, rédiger un protocole, exploiter des mesures ou évaluer des incertitudes.
---

# ECE et mesures/incertitudes (Spé Physique-Chimie)

## Rôle de Claude
Simuler des situations d'ECE (proposer un protocole, l'exécuter mentalement, exploiter) et entraîner le réflexe incertitudes + chiffres significatifs sur chaque résultat.

## L'épreuve ECE
- **1 heure**, en fin d'année, compte dans la note de spécialité (barème sur 20 ramené dans la note finale). Tirage d'une situation ; évaluation par compétences : S'approprier, Analyser/Raisonner, Réaliser, Valider, Communiquer.
- Déroulé type : analyser un problème → **proposer ou compléter un protocole** → réaliser (mesures, montage, tableur/Python) → exploiter → **valider** (incertitudes, comparaison à une référence) → conclure.
- Réflexes gagnants : lire TOUT l'énoncé d'abord · appeler l'examinateur si bloqué (prévu, pénalité limitée) · gérer le temps (ne pas rester 30 min sur le montage) · noter unités et incertitudes au fil de l'eau.

## Rédiger un protocole (structure attendue)
1. Matériel et produits (verrerie PRÉCISE : pipette jaugée ≠ éprouvette — la pipette jaugée est bien plus précise). 2. Étapes numérotées, verbes d'action. 3. Grandeurs mesurées et comment. 4. Sécurité (lunettes, gants, hotte selon produits). 5. Schéma si montage.
Verrerie de précision : fiole jaugée (préparer un volume précis), pipette jaugée (prélever), burette graduée (verser en mesurant) ; bécher et erlenmeyer = approximatifs.

## Incertitudes
- **Incertitude-type u(X)** : évaluation type A (statistique : u = s/√n sur n mesures répétées, s écart-type) ou type B (une mesure : notice, graduations).
- Écriture du résultat : **X = (valeur ± u) unité**, avec l'incertitude à 1 ou 2 chiffres significatifs et la valeur arrondie en cohérence. Ex. : C = (2,45 ± 0,03)×10⁻² mol·L⁻¹.
- Incertitude composée : formules fournies (savoir les appliquer, souvent en quadrature).
- **Comparaison à une valeur de référence — écart normalisé (z-score)** : **z = |x − x_réf| / u(x)** (ou u combinée). **Si z ≤ 2 : compatible** avec la référence ; si z > 2 : incompatible → chercher les sources d'erreur. C'est LA conclusion attendue en validation.

## Chiffres significatifs
Le résultat d'un calcul a autant de CS que la donnée qui en a le MOINS (produits/quotients). Zéros de tête non significatifs ; notation scientifique pour lever les ambiguïtés. Ne pas confondre précision d'affichage calculatrice et précision réelle.

## Pièges fréquents
Protocole sans volumes ni verrerie précise · résultat sans unité ni incertitude · z-score conclu à l'envers · confondre incertitude et erreur · arrondir en cascade au fil des calculs (garder les valeurs exactes, arrondir À LA FIN) · schéma sans légende.
