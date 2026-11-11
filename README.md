# COU-87 — Site de suivi ciblé

Site statique francophone, sans backend ni communication réseau. Ouvrir `index.html` dans un navigateur.

## Limites
- Les chiffres 147, 101, 5050 et 73→45 sont ceux du cadrage fourni ; les 147 états, 101 classes et 45 colonnes ne sont pas fabriqués.
- Le registre contient un noyau de 7 objets de provenance. Importer les données complètes par JSON pour effectuer des contrôles sur de vrais vecteurs.
- Le comparateur travaille localement sur un jeu de vecteurs binaires distincts de largeur 1–16, sans prouver une borne inférieure.
- Aucun lancement expérimental, publication, modification GitHub, création de ticket ni synchronisation automatique.
- Aucun stockage durable côté navigateur : exporter le registre JSON, qui contient les ajouts locaux.
- Le verrou de prépublication exige un statut `certifié` et une référence de certificat, sans vérifier cryptographiquement cette référence : ce n'est qu'un contrôle d'interface ; la certification réelle demeure externe.

## Provenance
PR547 : https://github.com/alexcour/couret-multi-ia-lab/pull/547
Commit consulté : 27dc21ea668c61a414329507d5131653110e007b
Fichier : research/fibre-separation-20261109/minimal_separator.py
La description de la PR rapporte trois méthodes de test local et précise que la CI n'est pas encore vérifiée.