---
author: Elisabeth Le Prettre (LePrettre)
title: 08 📝 Fiche élève
---

# S08 – Cohérence des résultats : valider ou écarter une donnée ? 📝

**Unités – Ordres de grandeur – Comparaison de séries – Esprit critique**

> En BTS MECP, on attend des réponses **rédigées**, **justifiées** et utilisant un **vocabulaire scientifique précis**.
> Un bon technicien sait **critiquer** ses résultats avant de conclure.

---

## 🎯 Objectifs de la séance

À l'issue de cette séance, vous serez capables de :

- **vérifier** la cohérence d'un résultat par analyse des unités
- **estimer** un ordre de grandeur pour détecter une erreur grossière
- **comparer** des séries de mesures pour identifier une valeur aberrante
- **décider** de valider, rejeter ou refaire une mesure
- **argumenter** une décision de contrôle qualité

---

## 🧴 Pourquoi c'est important pour votre métier ?

En institut ou en laboratoire cosmétique, vous serez amené(e) à :

- **Détecter une erreur de manipulation** avant de valider un résultat
- **Identifier une valeur aberrante** dans une série de mesures
- **Décider si un lot est conforme** malgré une mesure douteuse
- **Justifier le rejet d'un résultat** auprès de votre responsable
- **Éviter des erreurs coûteuses** (lot détruit ou produit non conforme commercialisé)

> 💡 *En contrôle qualité, une seule mesure ne suffit jamais. On répète les mesures et on analyse leur cohérence. Un résultat incohérent peut révéler une erreur humaine, un problème d'appareil ou une vraie anomalie du produit.*

👉 **Cette séance vous permettra** de développer votre esprit critique face aux résultats expérimentaux, une compétence essentielle pour l'épreuve E2.

---

## 🧴 Situation professionnelle

Vous travaillez au **service contrôle qualité** d'un laboratoire cosmétique.

Votre collègue a effectué plusieurs mesures sur un lot de crème hydratante, mais certains résultats semblent **incohérents**. Avant de valider le rapport d'analyse, vous devez vérifier la **cohérence des données** et décider quelles mesures sont fiables.

> *« Ces résultats sont-ils cohérents ? Peut-on valider ce lot ou faut-il refaire certaines mesures ? »*

---

## 📄 Documents fournis

### Document 1 – Vérification par les unités (analyse dimensionnelle)

Une méthode simple pour vérifier un calcul : **l'analyse des unités**.

Le résultat d'un calcul doit avoir l'unité attendue. Si ce n'est pas le cas, il y a une erreur.

**Exemple :**

| Calcul | Résultat | Unité obtenue | Unité attendue | Cohérent ? |
|--------|----------|:-------------:|:--------------:|:----------:|
| Cm = m / V | 50 g / 0,5 L | g/L | g/L | ✓ Oui |
| Cm = m × V | 50 g × 0,5 L | g·L | g/L | ✗ Non |

**Règle :** Si les unités ne correspondent pas, le calcul est **faux**.

---

### Document 2 – Ordres de grandeur en cosmétique

Les grandeurs mesurées en cosmétique ont des **valeurs typiques**. Un résultat très différent doit alerter.

| Grandeur | Ordre de grandeur typique | Valeur suspecte |
|----------|:-------------------------:|:---------------:|
| Concentration d'actif | 0,1 à 20% (1 à 200 g/L) | > 500 g/L |
| pH d'un produit cutané | 4 à 8 | < 2 ou > 12 |
| Densité d'une huile | 0,85 à 0,96 | < 0,5 ou > 1,5 |
| Densité d'une crème H/E | 0,95 à 1,05 | < 0,7 ou > 1,3 |
| Masse volumique de l'eau | ≈ 1,00 g/mL | ≠ 1,00 |

---

### Document 3 – Résultats d'analyse du lot n°2025-103

Un technicien a mesuré le **pH** d'une crème hydratante à 5 reprises :

| Mesure | pH |
|:------:|:--:|
| 1 | 5,8 |
| 2 | 5,9 |
| 3 | 12,4 |
| 4 | 5,7 |
| 5 | 5,8 |

**Cahier des charges :** pH = 5,5 à 6,5

---

### Document 4 – Moyenne et dispersion simple

#### Moyenne (x̄)

La **moyenne** est la valeur centrale d'une série de mesures.

$$\bar{x} = \frac{x_1 + x_2 + ... + x_n}{n} = \frac{\sum x_i}{n}$$

#### Valeurs extrêmes : min / max

- **x_min** : plus petite valeur mesurée  
- **x_max** : plus grande valeur mesurée

#### Étendue (E) : outil simple de dispersion

L’**étendue** mesure “l’écart global” entre la plus grande et la plus petite valeur.

$$E = x_{max} - x_{min}$$

**Interprétation :**

- **Étendue faible** → mesures **regroupées** (bonne répétabilité)
- **Étendue élevée** → mesures **dispersées** (problème possible)

#### Écart à une valeur de référence

- **Écart absolu** : $$\Delta = |x - x_{ref}|$$
- **Écart relatif** (en %) : $$\varepsilon_r = \frac{|x - x_{ref}|}{x_{ref}} \times 100$$

**En contrôle qualité**, on compare souvent :

- à un **cahier des charges** (intervalle de conformité)
- ou à une **tolérance interne** (ex : “l’étendue doit être ≤ 0,005” sur une densité)

---

### Document 5 – Arbre de décision

```
                    RÉSULTAT OBTENU
                          │
                          ▼
              ┌─────────────────────┐
              │ Les unités sont-    │
              │ elles correctes ?   │
              └─────────────────────┘
                    │         │
                   OUI       NON
                    │         │
                    ▼         ▼
              ┌─────────┐  REFAIRE
              │ L'ordre │  LE CALCUL
              │ de gran-│
              │ deur est│
              │ -il     │
              │ correct?│
              └─────────┘
                │     │
               OUI   NON
                │     │
                ▼     ▼
          ┌─────────┐  VÉRIFIER
          │ Cohérent│  LA MANIP
          │ avec les│  OU REFAIRE
          │ autres  │
          │ mesures?│
          └─────────┘
              │     │
             OUI   NON
              │     │
              ▼     ▼
          VALIDER  ÉCARTER OU
                   REFAIRE
```

---

## 🔬 Travail 1 – Vérification par les unités

### 1.1 – Identifier les erreurs

Un élève a effectué les calculs suivants. Identifiez les erreurs en vérifiant les unités :

| Calcul | Formule utilisée | Résultat | Unité obtenue | Correct ? |
|--------|------------------|----------|:-------------:|:---------:|
| Concentration | Cm = m × V = 5 × 0,1 | 0,5 | g·L | ☐ Oui ☐ Non |
| Masse volumique | ρ = V / m = 50 / 45 | 1,11 | mL/g | ☐ Oui ☐ Non |
| Facteur de dilution | F = Vi / Vf = 10 / 100 | 0,1 | sans unité | ☐ Oui ☐ Non |
| Volume à prélever | Vi = Cf × Vf / Ci = 20 × 100 / 80 | 25 | mL | ☐ Oui ☐ Non |

### 1.2 – Corriger les erreurs

Pour chaque calcul incorrect, écrivez la bonne formule et recalculez :

**Calcul 1 (si incorrect) :**

<br><br>

**Calcul 2 (si incorrect) :**

<br><br>

**Calcul 3 (si incorrect) :**

<br><br>

---

## 📊 Travail 2 – Ordres de grandeur

### 2.1 – Identifier les valeurs suspectes

Un stagiaire vous présente ses résultats. Identifiez ceux qui semblent **incohérents** :

| Mesure | Résultat | Valeur typique | Cohérent ? | Si non, erreur probable |
|--------|----------|:--------------:|:----------:|------------------------|
| pH d'un savon liquide | 85 | 8 à 10 | ☐ Oui ☐ Non | |
| Concentration en vitamine C | 150 g/L | 50 à 200 g/L | ☐ Oui ☐ Non | |
| Densité d'une huile | 0,0092 | 0,85 à 0,96 | ☐ Oui ☐ Non | |
| Masse volumique de l'eau | 1000 g/mL | 1,00 g/mL | ☐ Oui ☐ Non | |
| Volume prélevé | 2500 mL | 25 mL attendu | ☐ Oui ☐ Non | |

### 2.2 – Expliquer les erreurs probables

Pour chaque valeur incohérente, proposez une explication (erreur de virgule, erreur d'unité, erreur de manipulation...) :

<br><br><br><br>

---

## 🧮 Travail 3 – Analyser une série de mesures

> 🎯 **Compétence E2 : Interpréter** – Analyser la cohérence d'un jeu de données.

### Application au Document 3

Le technicien a mesuré le pH de la crème 5 fois : 5,8 ; 5,9 ; 12,4 ; 5,7 ; 5,8

### 3.1 – Calcul de la moyenne avec toutes les valeurs

$$\bar{x} = \frac{5,8 + 5,9 + 12,4 + 5,7 + 5,8}{5} = \frac{.........}{5} = .........$$

### 3.2 – Observation

1\. Cette moyenne est-elle dans l'intervalle du cahier des charges [5,5 ; 6,5] ?

☐ Oui ☐ Non

2\. La valeur **12,4** vous semble-t-elle cohérente avec les autres mesures ?

☐ Oui ☐ Non

3\. Justifiez avec **2 arguments** (comparaison aux autres mesures + ordre de grandeur du pH cutané) :


<br><br><br><br>

### 3.3 – Calcul de la moyenne SANS la valeur aberrante

$$\bar{x}_{corrigée} = \frac{5,8 + 5,9 + 5,7 + 5,8}{4} = \frac{.........}{4} = .........$$

### 3.4 – Décision

1\. La moyenne corrigée est-elle dans l'intervalle [5,5 ; 6,5] ?

☐ Oui ☐ Non

2\. Quelle décision prenez-vous concernant la valeur 12,4 ?

☐ La conserver dans le calcul

☐ L'écarter comme valeur aberrante

☐ Refaire cette mesure

3\. Justifiez votre décision en **3–4 lignes** (cause possible + action recommandée) :

<br><br><br><br><br>

---

## 📌 Travail 4 – Dispersion simple : min, max, étendue (sans écart-type)

> 🎯 **Compétence E2 : Interpréter** – Évaluer la répétabilité avec des outils simples de laboratoire.

### Situation

Un laboratoire mesure la densité d'une huile à 6 reprises :

| Mesure | 1 | 2 | 3 | 4 | 5 | 6 |
|--------|:-:|:-:|:-:|:-:|:-:|:-:|
| Densité | 0,912 | 0,915 | 0,910 | 0,914 | 0,911 | 0,913 |

**Tolérance interne (procédure labo) :** la série est jugée répétable si **l’étendue E ≤ 0,005**.

### 4.1 – Calcul de la moyenne

$$\bar{d} = \frac{0,912 + 0,915 + 0,910 + 0,914 + 0,911 + 0,913}{6} = .........$$

### 4.2 – Rechercher les extrêmes

- $d_{min}$ = .........  
- $d_{max}$ = .........

### 4.3 – Calculer l’étendue

$$E = d_{max} - d_{min} = .........$$

### 4.4 – Interprétation contrôle qualité

1. La série est-elle **répétable** selon la tolérance (E ≤ 0,005) ?

☐ Oui ☐ Non

2. Rédigez une conclusion courte (2–3 lignes) :
- répétabilité : oui/non
- décision : valider / refaire une ou plusieurs mesures
- justification (tolérance + cohérence des valeurs)

<br><br><br>

### 4.5 – Bonus “présentation de résultat” (niveau pro)

Proposez une manière de **présenter** le résultat au responsable qualité, en donnant :
- la moyenne $\bar{d}$
- et une indication simple de dispersion (par exemple : **min – max** ou **moyenne ± (E/2)**)

**Proposition :**  

<br><br>
<br><br>

---

## 🔄 Travail 5 – Exercice de synthèse (niveau E2)

> 🎯 **Compétence E2 : Argumenter** – Justifier une décision de contrôle qualité.

### Situation professionnelle

Le laboratoire a analysé trois lots de sérum à la vitamine C. Voici les résultats de concentration (en g/L) :

| Lot | Mesure 1 | Mesure 2 | Mesure 3 | Mesure 4 |
|:---:|:--------:|:--------:|:--------:|:--------:|
| A | 118 | 122 | 119 | 121 |
| B | 115 | 180 | 117 | 116 |
| C | 125 | 128 | 126 | 124 |

**Cahier des charges :** Concentration = 110 à 130 g/L

### Questions

**5.1** Pour chaque lot, calculez la moyenne des 4 mesures :

- Lot A : x̄ = 

- Lot B : x̄ = 

- Lot C : x̄ = 

**5.2** Identifiez si un lot présente une **valeur aberrante** :

<br><br>

**5.3** Pour le lot concerné, recalculez la moyenne **sans** la valeur aberrante :

<br><br>

**5.4** Complétez le tableau de synthèse :

| Lot | Moyenne | Valeur aberrante ? | Moyenne corrigée | Conforme ? |
|:---:|:-------:|:------------------:|:----------------:|:----------:|
| A | | ☐ Oui ☐ Non | — | ☐ Oui ☐ Non |
| B | | ☐ Oui ☐ Non | | ☐ Oui ☐ Non |
| C | | ☐ Oui ☐ Non | — | ☐ Oui ☐ Non |

**5.5** Rédigez une **recommandation professionnelle** pour le lot B (4-5 lignes) :

- Constat sur la valeur aberrante
- Décision (valider ou rejeter cette mesure)
- Conclusion sur la conformité du lot
- Action recommandée(contrôle appareil, refaire dilution, vérifier protocole…)


<br><br><br><br><br><br>

---

## 🚀 Travail 6 – Approfondissement (pour aller plus loin)

> ⚡ Ce travail est **facultatif**.

### Représentation graphique : l'histogramme

Un histogramme permet de visualiser la **distribution** des mesures.

**Exemple :** Mesures de pH sur 20 échantillons

```
Nombre de mesures
     │
   8 │       ████
   6 │    ████████
   4 │ ████████████
   2 │ ████████████████
   0 └─┴──┴──┴──┴──┴──┴──► pH
     5,0 5,5 6,0 6,5 7,0 7,5
```

**Interprétation :**

- La majorité des mesures sont autour de 6,0
- La distribution est **symétrique** (forme de cloche)
- Pas de valeur isolée → pas de valeur aberrante évidente

### Question

Pourquoi un histogramme est-il utile pour détecter des valeurs aberrantes ?

<br><br><br>

---

## ✍️ Synthèse personnelle (entraînement E2 – 5 à 7 lignes)

> 🎯 **Compétence E2 : Communiquer**

Rédigez un **court paragraphe** expliquant comment vérifier la cohérence d'un résultat expérimental avant de le valider.

**Votre synthèse doit contenir :**

- La vérification par les unités
- La comparaison aux ordres de grandeur
- L'analyse d'une série de mesures (moyenne, écart-type)
- La décision finale (valider, rejeter, refaire)

**Mots obligatoires à placer :**

*unité – ordre de grandeur – moyenne – écart-type – aberrant – cohérent – valider*

<br><br><br><br><br><br><br>

---

## 🏆 Mes réussites aujourd'hui

Avant de passer à l'auto-évaluation, prenez un moment pour reconnaître vos progrès !

**Cochez ce que vous avez réussi à faire :**

| Réussite | ✓ |
|----------|---|
| J'ai su vérifier la cohérence d'un calcul par les unités | ☐ |
| J'ai su identifier une valeur suspecte par son ordre de grandeur | ☐ |
| J'ai su calculer une moyenne | ☐ |
| J'ai su identifier une valeur aberrante dans une série | ☐ |
| J'ai su justifier la décision de valider ou rejeter une mesure | ☐ |
| J'ai su rédiger une recommandation professionnelle | ☐ |

💡 **Chaque case cochée est une victoire !** L'esprit critique est une compétence qui se développe avec la pratique.

---

## ✅ Auto-évaluation

Avant de rendre votre travail, vérifiez :

| Critère | ✓ |
|---------|---|
| Je sais vérifier un calcul par l'analyse des unités | ☐ |
| Je connais les ordres de grandeur typiques en cosmétique | ☐ |
| Je sais calculer une moyenne | ☐ |
| Je sais identifier et traiter une valeur aberrante | ☐ |
| J'ai justifié mes décisions avec des arguments | ☐ |
| J'ai rédigé ma synthèse avec les mots obligatoires | ☐ |

---

## 🔗 Pour la suite de la progression

Dans les **séances suivantes**, vous découvrirez :

- **S09** : Le pH (paramètre de contrôle qualité fondamental)
- **S10 (TP2)** : pH-métrie – mesure et exploitation de résultats
- **S11** : Évaluation n°2 (S01-S10)

---

## 🔧 Outils méthodologiques associés

➡️ [**Fiche méthode 01 – Justifier une réponse scientifique (O.A.C.J.)**](https://bts-mecp-physique-chimie-688080.forge.apps.education.fr/Methodologie/01_fiche_methode/)

➡️ [**Fiche méthode 02 – Calculer et interpréter (D.U.C.I.)**](https://bts-mecp-physique-chimie-688080.forge.apps.education.fr/Methodologie/02_fiche_methode/)


