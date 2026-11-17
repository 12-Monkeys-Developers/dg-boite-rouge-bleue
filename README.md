# Dangerous Gary — Boîtes rouge et bleue pour Foundry VTT

Adaptation de la campagne en deux parties de **Dangerous Gary**, éditées par **Les XII Singes**, pour Foundry Virtual Tabletop.

## Prérequis

- **Foundry VTT version 14**.
- Le système [Dangerous Gary](https://github.com/12-Monkeys-Developers/dangerousgary), **version 1.4.0 minimum**.

Les rencontres utilisent les capacités du système 1.4.0 : effets spéciaux d’attaque, dégâts critiques, effets continus, auras de terreur et régénération. Pour utiliser les classes, les talents et les capacités des artefacts, activer l’option correspondante dans les réglages du système.

## Contenu

Un compendium **« Boites rouge et bleue »** rassemble deux aventures à importer dans un monde Dangerous Gary :

| Aventure | Scènes | Journaux | Fiches Rencontre | Fiches Personnage | Objets et artefacts |
| --- | ---: | ---: | ---: | ---: | ---: |
| Boite rouge | 8 | 8 | 18 | 21 | 15 |
| Boite bleue | 7 | 7 | 26 | 16 | 24 |

- Scènes illustrées et notes donnant accès aux descriptions des lieux.
- Journaux de description des donjons.
- Rencontres avec caractéristiques, attaques et pouvoirs
- 81 profils de créatures et PNJ, vérifiés directement sur les PDF : les protagonistes des donjons, des intersections et du final sont inclus.
- Fiches Personnage pour les PNJ humains, dont Tenser avec ses caractéristiques du livre ; classes et spécialités renseignées lorsqu’elles sont fournies. Les talents ordinaires sont ajoutés comme objets sur les Personnages jusqu’au niveau de chaque classe. Les talents d’Assassin sont créés directement sur les PNJ concernés, sans compendium dédié, et affichés dans le bloc Assassin réservé au MJ. Leur sauvegarde utilise la moyenne des maxima de FOR, DEX et VOL, arrondie à l’inférieur ; ses jets restent privés MJ.
- Valeurs courantes et maximales distinguées pour Baptiste Cavalier et les Amoureux. Chaque fiche indique le livre et la page imprimée de son profil.
- La Guenaude garde une fiche Rencontre pour ses pouvoirs de Monstre ; son statut hybride et ses niveaux Druide 9 et Voleur 9 sont indiqués dans ses pouvoirs.
- Artefacts et équipements associés.

Les effets pris en charge par le système sont renseignés sur les fiches. Les armes des Personnages ne prennent pas en charge les déclencheurs des attaques de Rencontre : leurs effets spéciaux restent en description. La morsure supplémentaire de Rudd dispose de sa propre arme ; sa régénération est conservée sous forme d’effet continu de soin. Les pouvoirs comportant des conditions particulières, des immunités ou des effets narratifs restent décrits pour être gérés par le MJ.

## Installation

1. Installer le système **Dangerous Gary 1.4.0 ou supérieur**.
2. Dans l’écran de configuration de Foundry, ouvrir **Modules complémentaires**, puis **Installer un module** et utiliser cette URL de manifeste :

   ```text
   https://github.com/12-Monkeys-Developers/dg-boite-rouge-bleue/releases/latest/download/module.json
   ```

3. Ouvrir un monde utilisant Dangerous Gary et activer le module **Dangerous Gary : Boites rouge et bleue** dans **Gérer les modules**.
4. Dans les compendiums, ouvrir **Boites rouge et bleue**, puis l’aventure souhaitée et importer son contenu.

L’import crée les acteurs, objets, scènes, journaux et dossiers de l’aventure dans le monde. Aucune macro de génération n’est nécessaire.

## Mise à jour d’une aventure déjà importée

Après mise à jour du module, rouvrir l’aventure depuis le compendium et relancer son import. Pour ne mettre à jour que les acteurs, décocher l’import de tout le contenu et sélectionner **Acteurs** (ainsi que **Objets** pour actualiser les classes autorisées des artefacts), puis confirmer le remplacement.

Les identifiants des acteurs sont conservés. Le réimport remplace leurs données, y compris les modifications personnelles, les PV courants et l’équipement. La sélection **Acteurs** inclut également les PNJ avec fiches Personnage des deux boîtes. Les modifications propres aux tokens non liés ne sont pas directement réécrites par cette opération.

## Crédits et droits

Dangerous Gary © est un jeu de rôle édité par Les XII Singes © 2025.

La marque Les XII Singes est la propriété de ReSpell ©, 5 bis avenue des Clairs-Chênes, 95370 Montigny-lès-Cormeilles. Basé sur le SRD de Mark Of the Odd par Chris McDowall, auteur de Into the Odd : [www.bastionland.com](https://www.bastionland.com/).

Les marques Dungeons & Dragons © et Mordenkainen © sont la propriété de Wizards of the Coast © et sont utilisées au titre des droits de citation, de création transformative et d’hommage sans autre exploitation de leur contenu. Les termes Tenser et Robilar sont la propriété de leurs créateurs et ayants droit et sont utilisés au titre des droits de citation, de création transformative et d’hommage sans autre exploitation de leur contenu.

Les visuels utilisés sur Foundry VTT sont réalisés par [Maxime Plasse](https://www.maxsmaps.com/). Ils sont fournis pour l’utilisation de Foundry VTT. Toute autre utilisation ou reproduction d’image doit obtenir l’accord de ReSpell / Les XII Singes.

Adaptation Foundry VTT : **Kristov** et **l’Alchimiste**.

## Retours et communauté

- [Signaler un problème ou proposer une amélioration](https://github.com/12-Monkeys-Developers/dg-boite-rouge-bleue/issues).
- [Consulter les notes de version](CHANGELOG.md).
- Rejoindre le [Discord francophone dédié à Foundry Virtual Tabletop](https://discord.gg/lafonderie).
