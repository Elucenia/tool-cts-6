<!-- ELUCENIA technical documentation · cts-6 · fr · no clinical/professional/rights approval -->

# CTS-6 (syndrome du canal carpien)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/cts-6)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Engourdissement principalement ou exclusivement dans le territoire du nerf médian

`dorm`

### Engourdissement nocturne

`noturna`

### Atrophie et/ou faiblesse des muscles thénariens

`atrofia`

### Test de Phalen positif

`phalen`

### Perte de discrimination de deux points (\> 6 mm)

`dpp`

### Signe de Tinel positif au niveau du canal carpien

`tinel`

## Édition de la méthode

CTS-6/Graham 2006 : 6 critères pondérés de canal carpien ; examen clinique

## Formule documentée

Additionnez : engourdissement médian 3,5 ; nocturne 4 ; atrophie/faiblesse thénar 5 ; Phalen positif 5 ; perte de discrimination de deux points 4,5 ; Tinel positif 4. Total 0–26.

## Limites et population

La méthode de Graham 2006 a utilisé un consensus d’experts et des histoires de cas combinant des critères cliniques ; la validation décrite dans le résumé a comparé les probabilités du modèle aux jugements d’un autre panel. Ce plan d’étude n’établit pas, à lui seul, la performance par rapport à un examen électrophysiologique dans chaque population clinique. La cotation à six items, son seuil et la tranche d’âge doivent être vérifiés dans la méthode intégrale.

## Références

- [Graham B et al. Development and validation of diagnostic criteria for carpal tunnel syndrome. J Hand Surg Am, 2006.](https://doi.org/10.1016/j.jhsa.2006.03.005)

- [Graham B. The value added by electrodiagnostic testing in the diagnosis of carpal tunnel syndrome. J Bone Joint Surg Am, 2008.](https://doi.org/10.2106/JBJS.G.01362)

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

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Faible probabilité de syndrome du canal carpien (inférieure à environ 25%)

Envisager des diagnostics alternatifs (radiculopathie cervicale, polyneuropathie).


### 2

Probabilité intermédiaire (entre environ 25% et 80%)

L’électroneuromyographie est plus utile dans cette plage.


### 3

Probabilité intermédiaire (entre environ 25% et 80%)

L’électroneuromyographie est plus utile dans cette plage.


### 4

Forte probabilité de syndrome du canal carpien (environ 80% ou plus)

Dans cette plage, l’électroneuromyographie modifie rarement le diagnostic clinique.

