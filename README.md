# 🇲🇦 PMSS - La Plate-forme Marocaine de Simulation en Santé

**« La simulation est une technique, pas une technologie. »**

Bienvenue sur le dépôt officiel de PMSS. Nous proposons des applications web de simulation en santé gratuites, légères et entièrement hors ligne, conçues pour démocratiser l'enseignement médical. Ce projet a débuté dans le cadre d'un module de doctorat intitulé « innovation pédagogique », mais nous avons pensé qu'il serait utile de partager ces applications avec le monde entier.

## 🌟 Notre philosophie

La simulation haute fidélité ne devrait pas nécessiter un budget important ni un accès constant à Internet. Chaque application de ce dépôt est :

- **100 % hors ligne :** Fonctionne parfaitement sans connexion Internet.
- **Légère :** Chaque application est un fichier HTML autonome, généralement sous 2 Mo.
- **Universelle :** Fonctionne sur tout appareil doté d'un navigateur moderne — PC, tablette, smartphone.
- **Gratuite :** Sous licence CC BY 4.0, y compris pour un usage commercial (avec attribution).

## 📱 Simulations disponibles

| Nom de l'application | Description | Lien |
| :--- | :--- | :--- |
| **Simulateur ECG normal** | Simulez et comprenez les tracés ECG normaux. | [Ouvrir l'application](normal-ecg-simulateur.html) |
| **Axe cardiaque (version animée)** | Outil interactif pour déterminer l'axe électrique du cœur. Tracés ECG animés (balayage continu). | [Ouvrir l'application](axe-cardiaque.html) |
| **Axe cardiaque (version statique)** | Même outil, mais avec des tracés ECG statiques qui se redessinent instantanément lors du changement d'axe. Idéal pour comparer les morphologies sans la distraction du mouvement. | [Ouvrir l'application](axe-cardiaque-statique.html) |
| **Cartographie des électrodes** | Visualisez le placement des dérivations ECG et la cartographie des électrodes. | [Ouvrir l'application](carto-electrode.html) |
| **Étiqueteur d'ondes** | Entraînez-vous à identifier les ondes P, QRS et T sur les tracés ECG. | [Ouvrir l'application](etiqueteur-ondes.html) |
| **Trouver l'erreur** | Entraînement diagnostique pour repérer les anomalies dans les tracés ECG. | [Ouvrir l'application](trouver-erreur.html) |

*D'autres simulations (respirateurs artificiels, moniteurs, pousse-seringues) arriveront bientôt !*

### Différence entre les deux versions de l'axe cardiaque

- **Version animée** (`axe-cardiaque.html`) : les tracés ECG défilent de droite à gauche en continu, comme sur un moniteur de chevet. La trace se met à jour progressivement à mesure que les nouveaux échantillons remplacent les anciens.
- **Version statique** (`axe-cardiaque-statique.html`) : trois battements fixes sont affichés par dérivation. Les tracés ne défilent pas — ils sont entièrement redessinés à chaque changement d'axe. Cette version économise la batterie sur mobile et facilite la comparaison visuelle des morphologies.

## 💻 Utilisation hors ligne

1. Ouvrez le fichier que vous souhaitez utiliser (par exemple, `normal-ecg-simulateur.html`).
2. Cliquez sur le bouton **« Raw »** ou faites un clic droit et sélectionnez **« Enregistrer la cible sous... »** pour télécharger le fichier `.html` sur votre ordinateur.
3. Double-cliquez sur le fichier téléchargé. Il s'ouvrira dans votre navigateur web par défaut et fonctionnera parfaitement hors ligne.

## Demander une simulation

Vous avez une demande pour une machine médicale spécifique ou un scénario clinique ? Ouvrez une *issue* GitHub et faites-le nous savoir !

## 📝 Citation et usage académique

Ces outils sont sous licence CC BY 4.0, qui autorise l'usage non commercial et commercial, l'adaptation et la redistribution — à condition de fournir une attribution appropriée.

**Si vous utilisez les applications PMSS dans vos recherches, votre enseignement ou vos publications scientifiques, vous devez référencer ce travail.**

Veuillez nous citer comme suit :

> Razzok, O. (2026). *PMSS - La Plate-forme Marocaine de Simulation en Santé* [Applications web de simulation en santé]. Récupéré de https://github.com/oualid-razzok/PMSS-Simulations

*Vous pouvez également utiliser le bouton « Cite this repository » dans la barre latérale droite de la page GitHub pour générer une citation BibTeX ou APA.*

## 📜 Licence

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Ce projet est sous licence **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

- ✅ Vous pouvez **partager** et **adapter** le matériel pour **tout usage, y compris commercial**.
- ✅ Vous pouvez distribuer les œuvres dérivées sous n'importe quelle licence.
- ⚠️ Vous **devez** accorder un crédit approprié, fournir un lien vers la licence et indiquer si des modifications ont été effectuées.

Consultez le fichier [LICENCE](LICENCE) pour le texte complet de la licence, ou lisez le [résumé en langue courante](https://creativecommons.org/licenses/by/4.0/).
