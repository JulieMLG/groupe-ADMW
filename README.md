Le lien public de l'application est le suivant : https://jmlg.shinyapps.io/impact_gel_vigne/

Ce dashboard s'appuie sur les 3 sources de données publiques suivante :

Données météo, nous avons choisit de regarder les données des 5 années 2019 à 2023
https://public.opendatasoft.com/explore/dataset/donnees-synop-essentielles-omm/table/?flg=fr-fr&sort=date

Données des exploitations/vignobles français :
https://www.data.gouv.fr/fr/datasets/delimitation-parcellaire-des-aoc-viticoles-de-linao/

Données pour lier les 2 data précédentes : correspondance entre les code INSEE et les codes Postaux
https://public.opendatasoft.com/explore/dataset/correspondance-code-insee-code-postal/table/?flg=fr-fr

Pour ce projet, nous avons dans un premier temps travaillé les données publiques et obtenu 4 sous fichiers excel.
Ceci permet au dashboard de se charger plus rapidement.

La prépration des données a ajouté la notion "type de vin" (Rouge, Blanc, Rosé, Autre) à nos exploitations.
"Autre" est utilisé pour les vins qui ne rentrent dans aucune des catégories précédentes.
Mais également lorsqu'une exploitation comporte plusieurs types, nous avons gardé l'information du type majoritaire, sans majorité, le type est classé dans "Autre".
