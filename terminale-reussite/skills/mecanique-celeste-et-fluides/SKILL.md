---
name: mecanique-celeste-et-fluides
description: Mouvement des satellites et planètes, lois de Kepler, et statique des fluides en Terminale spé physique-chimie (gravitation, orbite circulaire, période de révolution, satellite géostationnaire, loi fondamentale de la statique des fluides, loi de Mariotte, poussée d'Archimède). À utiliser pour tout exercice sur les satellites, les planètes ou les fluides au repos.
---

# Mécanique céleste et fluides (Spé Physique-Chimie)

## Rôle de Claude
Deux blocs distincts du programme. Pour les satellites : dérouler la démonstration classique (v puis T) jusqu'à la maîtrise. Pour les fluides : soigner les unités (Pa, m, K).

## Gravitation et lois de Kepler
- **Force gravitationnelle** : F = G·m·M/r² (G ≈ 6,67×10⁻¹¹ SI), attractive, portée par la droite reliant les centres.
- **Lois de Kepler** : (1) orbites elliptiques, le Soleil à un foyer ; (2) loi des aires : le rayon balaie des aires égales en des durées égales (la planète va plus vite près du Soleil) ; (3) **T²/a³ = constante** pour tous les corps orbitant autour du même astre (a = demi-grand axe).

## Satellite en orbite circulaire (LA démonstration à savoir refaire)
Système {satellite}, référentiel géocentrique, seule force : gravitation.
1. Newton : a = G·M/r² dirigée vers le centre → mouvement circulaire **uniforme** (a centripète, a = v²/r).
2. Égaliser : v²/r = GM/r² → **v = √(GM/r)** (indépendant de la masse du satellite !).
3. Période : T = 2πr/v → **T = 2π√(r³/GM)** — et on retrouve la 3e loi de Kepler : T²/r³ = 4π²/(GM).
- **Géostationnaire** : immobile au-dessus d'un point de l'équateur → T = 23 h 56 min (jour sidéral), orbite équatoriale, r ≈ 42 000 km (altitude ≈ 36 000 km). Attention : r = R_Terre + h (h = altitude).

## Statique des fluides
- **Pression** : P = F/S (Pa = N·m⁻²) ; 1 bar = 10⁵ Pa ; pression atmosphérique ≈ 1013 hPa.
- **Loi fondamentale de la statique des fluides** (fluide incompressible au repos) : **P₂ − P₁ = ρ·g·(z₁ − z₂)** — la pression augmente avec la profondeur : P(profondeur h) = P_surface + ρgh. Application : plongée (+1 bar tous les 10 m d'eau environ).
- **Loi de Mariotte** (gaz, T constante) : **P·V = constante** (P₁V₁ = P₂V₂).
- **Poussée d'Archimède** : force verticale ascendante, norme = poids du fluide déplacé : F_A = ρ_fluide·V_immergé·g. Flotte si ρ_objet < ρ_fluide.

## Pièges fréquents
Confondre r (rayon d'orbite) et h (altitude) · masse M dans les formules = masse de l'ASTRE central, pas du satellite · calculer T en oubliant de convertir r en mètres · appliquer Mariotte avec T qui varie · ρgh avec h en cm · oublier que la statique des fluides suppose le fluide incompressible (liquides oui, gaz non).
