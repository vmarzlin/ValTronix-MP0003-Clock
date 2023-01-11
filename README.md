# MP0003 Clock
Mini-plaquette permettant de générer un signal d'horloge débrayable.
La fréquence est variable entre environ 1Hz et 44Hz mais conserve un ratio de 50%.
Le signal d'horloge est disponible simultanément en logique positive et négative.
Ce signal d'horloge peut être mis en pause et repris de façon propre sans introduire d'impulsions parasites.
Lorsqu'il est en pause (hold) il est possible d'envoyer des impulsions manuellement sans rebond (mode pas-à-pas).

Parallèlement à l'horloge, un signal RESET (et son complément) est disponible.
Il est activé par défaut à la mise sous tension et à chaque appui sur le bouton RESET.
Une durée minimale d'impulsion est garantie.

Le RESET, les tops d'horloge et le mode "run" (horloge active) sont affichés via des LED.

Les sorties sont protégées contre les courts-circuits.
