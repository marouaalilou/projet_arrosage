# Projet d'arrosage automatique
Un système qui arrose automatiquement une plante en pot selon ses besoins réels en eau.
Projet personnel d'étudiante en ingénierie des systèmes d'information.

## Objectif
Aider à prendre soin des plantes en pot, même quand on est absent ou qu'on oublie d'arroser.

## Matériel (version 1)
- Carte ESP32 ou Arduino
- Capteur d'humidité du sol (capacitif)
- Mini pompe à eau + relais 5 V
- Petit réservoir d'eau, tuyau, câbles, plaque d'essai
- Alimentation basse tension (jamais le courant 220 V)

## Fonctionnement
1. Le capteur mesure l'humidité du sol.
2. Si l'humidité est sous le seuil bas de la plante, la pompe arrose par petites séquences.
3. Après chaque séquence, le système attend, puis mesure de nouveau.
4. L'arrosage s'arrête quand le seuil haut est atteint.
5. Des sécurités limitent la durée et la fréquence des arrosages.

## Avancement
- [x] Idée et dépôt GitHub créés
- [ ] Schéma du montage
- [ ] Lecture du capteur d'humidité
- [ ] Arrosage automatique avec la pompe
- [ ] Photos et code

## Feuille de route
- V1 : arrosage automatique avec seuils réglés à la main
- V2 : application mobile avec alertes
- V3 : base de données de plantes avec seuils par espèce
- V4 : ajout d'une caméra et identification de la plante par photo
- V5 : détection des problèmes de la plante (maladies, manque d'eau, feuilles abîmées) avec l'IA
- V6 : réglage automatique des seuils et conseils personnalisés selon la plante
  
## Auteure
Maroua Alilou, étudiante en ingénierie des systèmes d'information
