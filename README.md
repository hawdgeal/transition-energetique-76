# transition-energetique-76

![Project Logo](donnees/DPE76.png)

# Tableau de bord interactif - Transition énergétique en Seine-Maritime

Bienvenue dans le projet visant à créer un tableau de bord interactif pour analyser les données énergétiques et les diagnostics de performance énergétique (DPE) en Seine-Maritime.

## Objectif du projet

Ce projet a pour but de :

1. **Analyser et visualiser les données énergétiques** : Identifier les tendances et les indicateurs clés liés à la consommation énergétique des habitations et aux diagnostics de performance énergétique.
2. **Positionnement comparatif** : Comparer les performances énergétiques locales à celles des autres départements français.
3. **Faciliter la prise de décision** : Fournir des visualisations claires et interactives pour permettre aux décideurs de comprendre rapidement les informations pertinentes.

## Fonctionnalités principales

- Visualisation des données de consommation énergétique.
- Répartition des diagnostics de performance énergétique (DPE).
- Carte interactive illustrant les performances énergétiques par territoire.
- Comparaison avec d'autres départements français à l'aide de graphiques clairs et percutants.

## Sources des données

Les données utilisées dans ce projet proviennent de :

- [Consommation annuelle d'électricité et de gaz par département](https://www.data.gouv.fr/)
- [DPE logements existants (API ADEME)](https://data.ademe.fr/)

## Structure du projet

├── docs/
│   ├── index.html              # Page web principale
│   └── autres fichiers HTML
├── donnees/
│   ├── consommation-annuelle-d-electricite-et-gaz-par-departement.csv
│   ├── dpe_data.csv            # Données extraites de l'API DPE
│   └── autres fichiers de données
├── exploration/
│   ├── [analyse_dpe.ipynb](https://github.com/hawdgeal/transition-energetique-76/blob/main/exploration/analyse_dpe.ipynb)       # Analyse des diagnostics de performance énergétique (DPE)
│   ├── [analyse_finale.ipynb](https://github.com/hawdgeal/transition-energetique-76/blob/main/exploration/analyse_finale.ipynb)    # Synthèse des analyses et visualisations finales
│   ├── [conso_nrj.ipynb](https://github.com/hawdgeal/transition-energetique-76/blob/main/exploration/conso_nrj.ipynb)         # Étude de la consommation énergétique par département
│   ├── [requete_api.ipynb](https://github.com/username/transition-energetique-76/blob/main/exploration/requete_api.ipynb)       # Scripts pour extraire les données depuis l'API
├── .gitignore                  # Fichiers à exclure du dépôt
└── README.md                   # Description du projet

## Technologies utilisées

- **Langage de programmation** : Python, HTML
- **Bibliothèques Python principales** : pandas, requests

## Installation

Pour utiliser ou contribuer à ce projet :

1. Clonez ce dépôt GitHub :

   ```bash
   git clone <URL_du_dépôt>
   ```
2. Installez les dépendances nécessaires :

   ```bash
   pip install -r requirements.txt
   ```
3. Configurez les accès API si nécessaire (voir la documentation).

## Utilisation

1. Exécutez le script principal pour extraire les données via l'API et les traiter.
2. Générez des visualisations à partir des données nettoyées.
3. Explorez les visualisations interactives dans le tableau de bord.

## Contribution

Les contributions sont les bienvenues ! Si vous souhaitez contribuer :

1. Forkez ce dépôt.
2. Créez une branche pour votre fonctionnalité ou correction :
   ```bash
   git checkout -b ma-nouvelle-fonctionnalite
   ```
3. Effectuez vos modifications et validez-les :
   ```bash
   git commit -m "Ajout d'une nouvelle fonctionnalité"
   ```
4. Poussez vos modifications :
   ```bash
   git push origin ma-nouvelle-fonctionnalite
   ```
5. Créez une Pull Request.

## Licence

Ce projet est sous licence [MIT](LICENSE).

## Contact

Pour toute question ou suggestion, veuillez contactez Rodrigo ou Cynthia
