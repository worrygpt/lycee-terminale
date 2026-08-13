---
name: energie-et-premier-principe
description: Bilans d'énergie en Terminale spé physique-chimie (énergie interne, premier principe de la thermodynamique, transferts thermiques par conduction convection rayonnement, capacité thermique, flux thermique, résistance thermique, loi de Newton du refroidissement, bilan radiatif de la Terre). À utiliser pour tout exercice de thermodynamique ou de transfert thermique.
---

# Énergie interne et transferts thermiques (Spé Physique-Chimie)

## Rôle de Claude
Faire écrire le bilan ΔU = W + Q avec les bons SIGNES (convention : reçu > 0), et structurer les exercices de calorimétrie et de refroidissement.

## Premier principe de la thermodynamique
- **Énergie interne U** : énergie « microscopique » du système (agitation + interactions). Pour un système au repos macroscopique : **ΔU = W + Q** (W travail reçu, Q transfert thermique reçu ; grandeurs ALGÉBRIQUES : reçu > 0, cédé < 0).
- Pour un système incompressible (solide, liquide) sans travail : **ΔU = Q = m·c·ΔT** avec c capacité thermique massique (J·kg⁻¹·K⁻¹) et ΔT = T_finale − T_initiale.
- Calorimétrie : système isolé → somme des Q échangés = 0 (équilibre thermique, température finale commune).

## Les trois modes de transfert thermique
- **Conduction** : de proche en proche, sans transport de matière (solides).
- **Convection** : avec mouvement de matière (fluides).
- **Rayonnement** : ondes électromagnétiques, sans support matériel (Soleil → Terre).
Le transfert thermique spontané va toujours du corps chaud vers le corps froid.

## Flux et résistance thermiques
- **Flux thermique** : Φ = Q/Δt (en W) — puissance transférée.
- **Résistance thermique** d'une paroi : **Φ = ΔT/R_th** soit R_th = ΔT/Φ (K·W⁻¹). Plus R_th est grande, meilleure est l'isolation. Parois en série : les résistances s'ajoutent.

## Loi de Newton (refroidissement) — pont avec les maths
Flux échangé avec l'extérieur ∝ écart de température : Φ = h·S·(T − T_ext). Bilan → équation différentielle du type **dT/dt = −k·(T − T_ext)**, solution : **T(t) = T_ext + (T₀ − T_ext)·e^(−kt)** (décroissance exponentielle vers T_ext). Exploitations : temps caractéristique, tracés, méthode d'Euler éventuelle.

## Bilan radiatif de la Terre (lien enseignement scientifique)
Puissance solaire reçue, albédo (fraction réfléchie), absorption, émission infrarouge, **effet de serre** : l'atmosphère renvoie une partie du rayonnement IR vers le sol → température moyenne plus élevée qu'en son absence. Savoir faire un bilan de puissances à l'équilibre (reçu = émis).

## Pièges fréquents
Signes de W et Q inversés · ΔT en oubliant que 1 K d'écart = 1 °C d'écart (pas de conversion pour un ÉCART) · c massique (par kg) vs C capacité (du système entier) · confondre Q (énergie, J) et Φ (puissance, W) · loi de Newton : oublier T_ext dans la solution · dire que la Terre « ne rayonne pas ».
