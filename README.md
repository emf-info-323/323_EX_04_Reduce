<h1><code>Module 323</code> - Programmer de manière fonctionnelle</h1>

# 😅 Exercice 04 - Comprendre reduce()

## Objectifs

- Découvrir et bien comprendre cette incontournable méthode de programmation `filter()`.

## Données

Les trois fichiers de données ci-dessous sont déjà chargés par le fichier HTML. Ces fichiers fournissent beaucoup d'informations sur :

- [ex04-data-motos.js](/src/ex04-data-motos.js) ➜ des marques de motos et des modèles de moto
- [ex04-data-villes.js](/src/ex04-data-villes.js) ➜ des villes, leur canton et nombre d'habitants
- [ex04-data-evaluations.js](/src/ex04-data-evaluations.js) ➜ des résultats d'évaluation de branches matu pour les apprentis de l'EMF

Ces informations sont directement utilisables via ces 3 constantes (`dataMotos`, `dataVilles` et `dataEvaluations`).

## Rapports à produire

Les rapports à produire :

- [R1 - La moyenne de toutes les évaluations effectuées](#r1---la-moyenne-de-toutes-les-évaluations-effectuées)
- [R2 - Pour chaque marque de moto, la plus puissante](#r2---pour-chaque-marque-de-moto-la-plus-puissante)
- [R3 - Le total de tous les habitants](#r3---le-total-de-tous-les-habitants)
- [R4 - Le total des habitants de chaque canton et de la Suisse](#r4---le-total-des-habitants-de-chaque-canton-et-de-la-suisse)
- [R5 - La liste des cantons, sans doublons](#r5---la-liste-des-cantons-sans-doublons)

## R1 - La moyenne de toutes les évaluations effectuées

À partir des données disponibles (`dataEvaluations`), vous devez obtenir ceci en utilisant la fonction `reduce()`:

```json
{
   "somme": 2881.799999999998,
   "nbre": 666,
   "moyenne": 4.3270270270270235
}
```

Ensuite, adaptez votre requête afin qu'elle retourne directement ceci :

```json
4.3270270270270235
```

## R2 - Pour chaque marque de moto, la plus puissante

À partir des données disponibles (`dataMotos`), vous devez obtenir ceci :

```json
{
   "Honda": {
      "nom": "CBR1000RR Fireblade",
      "annee": 2024,
      "prix": 23000,
      "puissance": 218,
      "couple": 113
   },
   "Yamaha": {
      "nom": "YZF-R1",
      "annee": 2024,
      "prix": 21000,
      "puissance": 200,
      "couple": 113
   },
   "Ducati": {
      "nom": "Panigale V4",
      "annee": 2024,
      "prix": 26000,
      "puissance": 215,
      "couple": 124
   },
   "BMW": {
      "nom": "S1000RR",
      "annee": 2024,
      "prix": 21000,
      "puissance": 210,
      "couple": 113
   },
   "Harley-Davidson": {
      "nom": "Fat Boy 114",
      "annee": 2024,
      "prix": 25000,
      "puissance": 95,
      "couple": 155
   }
}
```

## R3 - Le total de tous les habitants

À partir des données  disponibles (`dataVilles`), vous devez obtenir ceci :

```json
649170
```

## R4 - Le total des habitants de chaque canton et de la Suisse

À partir des données  disponibles (`dataVilles`), vous devez obtenir ceci :

```json
{
   "CH": 649170,
   "FR": 79900,
   "VD": 206120,
   "SO": 53800,
   "VS": 74400,
   "BE": 234600,
   "GE": 350
}
```

## R5 - La liste des cantons, sans doublons

À partir des données disponibles (`dataVilles`), vous devez obtenir ceci :

```json
[
   "FR",
   "VD",
   "SO",
   "VS",
   "BE",
   "GE"
]
```

---

<img src="res/EMF_logo_RVB_Info_long.png" width="25%" style="margin-left:-20px;">
