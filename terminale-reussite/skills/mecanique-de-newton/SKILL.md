---
name: mecanique-de-newton
description: Mécanique de Newton en Terminale spé physique-chimie (vecteurs position, vitesse, accélération, deuxième loi de Newton, chute libre, mouvement dans un champ uniforme, projectile, équations horaires, trajectoire). À utiliser pour tout exercice de mécanique - projectile, chute, mouvement dans un champ électrique, plans inclinés.
---

# Mécanique de Newton (Spé Physique-Chimie)

## Rôle de Claude
Imposer LA méthode en 5 étapes (système, référentiel, forces, Newton, projection) à chaque exercice, jusqu'à l'automatisme. Vérifier l'homogénéité et les cas limites à la fin.

## Cinématique
- Vecteur position OM(t) → **vitesse** v = dOM/dt → **accélération** a = dv/dt (dérivées coordonnée par coordonnée ; sens inverse par primitives + conditions initiales).
- Vocabulaire : mouvement rectiligne uniforme (v constant), uniformément accéléré (a constant), circulaire uniforme (a centripète, v change de direction).

## La méthode en 5 étapes (toujours dans cet ordre)
1. **Système** : {l'objet étudié}, masse m.
2. **Référentiel** : terrestre supposé galiléen.
3. **Bilan des forces** : poids P = mg (vertical, vers le bas), réaction du support, frottements, poussée d'Archimède, force électrique F = qE… (schéma !). Préciser si certaines sont négligées (énoncé).
4. **Deuxième loi de Newton** : **ΣF = m·a** (les autres lois : principe d'inertie ΣF = 0 ⟺ v constant ; action-réaction).
5. **Projection** sur les axes du repère choisi → coordonnées de a.

## Le grand classique : projectile dans le champ de pesanteur uniforme
Chute libre (seul le poids) : a = g soit ax = 0, az = −g (axe z vertical ascendant).
Conditions initiales : v₀ incliné d'un angle α → v₀x = v₀cos α, v₀z = v₀sin α.
- **Équations horaires** : x(t) = v₀cos α·t ; z(t) = −½gt² + v₀sin α·t + z₀.
- **Trajectoire** (éliminer t) : z = −g·x²/(2v₀²cos²α) + tan α·x + z₀ → parabole.
- Exploitations types : **flèche** (sommet : vz = 0), **portée** (z = 0), vitesse en un point, durée de vol. Le mouvement horizontal est uniforme, le vertical uniformément varié.

## Champ électrique uniforme (condensateur plan)
Force F = qE (attention au signe de q : sens de F opposé à E si q < 0) ; poids souvent négligeable devant F (à justifier par un rapport d'ordres de grandeur). Même démarche → trajectoire parabolique. Applications : accélération ou déviation de particules.

## Pièges fréquents
Oublier une force au bilan (réaction du support !) · projeter avec les mauvais signes (bien définir l'orientation des axes AVANT) · conditions initiales oubliées dans les primitives · confondre vitesse et accélération nulles (au sommet : vz = 0 mais az = −g) · unités (g ≈ 9,81 m·s⁻² ; angles en degrés vs radians selon la calculatrice) · « ΣF = ma » écrit sans vecteurs.
