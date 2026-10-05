<!-- ELUCENIA technical documentation · escala-lanss · fr · no clinical/professional/rights approval -->

# Échelle de douleur LANSS

[conditions, sources et autorisations](https://elucenia.org/fr/outils/escala-lanss)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### La douleur ressemble-t-elle à une sensation étrange et désagréable dans la peau (piqûres, fourmillements, décharges électriques) ?

`a1`

### La douleur donne-t-elle à la peau de la zone douloureuse un aspect différent de la normale (taches, rougeur, coloration rose) ?

`a2`

### La douleur rend-elle la peau anormalement sensible au toucher (gêne lors d’un léger effleurement ou avec des vêtements serrés) ?

`a3`

### La douleur apparaît-elle soudainement, par crises sans raison apparente au repos (décharges électriques, élancements) ?

`a4`

### La douleur donne-t-elle l’impression que la température de la peau a changé (chaleur, brûlure) ?

`a5`

### Examen : allodynie (douleur ou gêne lors d’un effleurement au coton dans la zone douloureuse, comparée à une zone normale)

`b6`

### Examen : seuil modifié à la piqûre (une piqûre avec une aiguille 23G est perçue différemment dans la zone douloureuse : plus ou moins intense)

`b7`

## Édition de la méthode

LANSS/Bennett 2001 : 5 symptômes+2 signes, total 0–24, seuil ≥12 ; portugais brésilien Schestatsky 2011

## Formule documentée

Partie A (questionnaire) : items de 5, 5, 3, 2 et 1 point. Partie B (examen sensitif) : allodynie 5 ; seuil de piqûre altéré 3. Total 0 à 24 ; seuil ≥12.

## Limites et population

La LANSS combine symptômes et signes obtenus par un examen sensitif pour rechercher la prédominance d’un mécanisme neuropathique dans la douleur chronique. Les items d’examen ne doivent pas être traités comme de simples autoévaluations. La validation brésilienne citée ne certifie ni l’implémentation ni de nouvelles traductions.

## Références

- [Bennett M. The LANSS Pain Scale: the Leeds assessment of neuropathic symptoms and signs. Pain, 2001.](https://doi.org/10.1016/S0304-3959(00)00482-6)

- [Schestatsky P et al. Brazilian Portuguese validation of the Leeds Assessment of Neuropathic Symptoms and Signs for patients with chronic pain. Pain Med, 2011.](https://doi.org/10.1111/j.1526-4637.2011.01221.x)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
