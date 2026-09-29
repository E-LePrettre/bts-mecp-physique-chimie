---
author: Elisabeth Le Prettre (LePrettre)
title: 21 📖 Trace écrite
---

# S21 – Interpréter une mesure de conductivité (CQ)

---

## 1️⃣ Qu'est-ce que la conductivité ?

### Définition

La **conductivité** (notée **σ**, lettre grecque « sigma ») mesure la **capacité d'une solution à conduire le courant électrique**.

**Principe :** Le courant circule grâce aux **ions** (porteurs de charge) qui se déplacent sous l'effet d'une tension électrique.

**Unité SI :** siemens par mètre (S/m)

**Unité usuelle en cosmétique :** microsiemens par centimètre (µS/cm)

**Conversion :** 1 S/m = 10 000 µS/cm

**Pièges d’unités et de mesure :**
- 1 mS/cm = 1000 µS/cm
- **σ dépend de la température** : comparer uniquement des mesures réalisées à **température identique**.

**Conductance, conductivité et constante de cellule :**
- La **conductance** (notée **G**, en **S**) dépend de la cellule de mesure : **G = 1/R**.
- La **conductivité** (σ) est une propriété de la solution : **σ = K × G**.
- **K** est la **constante de cellule** (géométrie des électrodes) : **K = ℓ/A** (en m⁻¹ ou cm⁻¹).
- La **résistivité** (ρ) est l’inverse de la conductivité : **ρ = 1/σ** (en Ω·m).
- Selon les documents, la conductivité peut aussi être notée **κ**.
 
---

### Principe de mesure

On plonge deux **électrodes** dans la solution et on applique une **tension électrique** :
- Les **cations** (+) migrent vers l'électrode négative
- Les **anions** (–) migrent vers l'électrode positive
- Ce déplacement d'ions crée un **courant électrique**
- Plus le courant circule facilement, plus σ est élevée

```
    Conductimètre
    ┌─────────┐
    │  σ = ?  │
    │ µS/cm   │
    └──┬──┬───┘
       │  │     ← électrodes
    ┌──┼──┼───┐
    │  │  │   │
    │ ⊕→ ←⊖ │  ← ions en mouvement
    │ ⊖→ ←⊕ │
    │  │  │   │
    └─────────┘
      Solution
```

---

### Solutions conductrices et non conductrices

| Type de solution | Exemples | σ | Explication |
|-----------------|----------|:-:|-------------|
| **Eau pure** | Eau ultrapure | ≈ 0,05 µS/cm | Pas d'ions |
| **Solutions ioniques** | NaCl, HCl, NaOH dans l'eau | Élevée | Ions dissous : Na⁺, Cl⁻, H₃O⁺, HO⁻… |
| **Solutions moléculaires** | Glycérol, éthanol dans l'eau | Très faible | Molécules non chargées |
| **Huiles** | Jojoba, silicones | ≈ 0 | Pas d'ions, solvant apolaire |

---

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   📌 À RETENIR – CONDUCTIVITÉ :                            │
│                                                             │
│   • σ mesure la capacité à conduire le courant              │
│   • Seules les solutions contenant des IONS conduisent      │
│   • L'eau pure et les huiles sont ISOLANTES                 │
│   • Unité : S/m (ou µS/cm en cosmétique)                    │
│                                                             │
│   Rappel S11 : NaCl → Na⁺ + Cl⁻ (dissociation ionique)      │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 2️⃣ Facteurs influençant la conductivité

Quatre facteurs principaux modifient la valeur de σ :

| Facteur | Effet | Explication | Exemple cosmétique |
|---------|-------|-------------|-------------------|
| **Concentration en ions** | σ ↑ quand C ↑ | Plus d'ions = plus de porteurs de charge | Sérum physiologique (9 g/L NaCl) → σ très élevée |
| **Nature des ions** | Petits ions mobiles → σ ↑ | H₃O⁺ et HO⁻ sont les ions les plus conducteurs | Lotion acide (riche en H₃O⁺) → σ élevée |
| **Température** | σ ↑ quand T ↑ | Ions plus agités → migrent plus vite | Toujours noter T lors d'une mesure CQ |
| **Solvant** | Solvant polaire → σ ↑ | Seul un solvant polaire dissocie les ions | Phase aqueuse : σ élevée ; phase huileuse : σ ≈ 0 |

---

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   📌 À RETENIR – RÈGLE D'OR DU CQ :                        │
│                                                             │
│   Toute mesure de conductivité doit être réalisée           │
│   à TEMPÉRATURE CONTRÔLÉE (généralement 25°C)               │
│   pour être comparable au cahier des charges.               │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 3️⃣ Application n°1 : type d'émulsion (H/E vs E/H)

### Principe

| Type d'émulsion | Phase continue | Phase dispersée | σ |
|----------------|---------------|-----------------|:-:|
| **H/E** (huile dans eau) | **Eau** (contient des ions) | Gouttelettes d'huile | **Élevée** (> 50 µS/cm) |
| **E/H** (eau dans huile) | **Huile** (pas d'ions) | Gouttelettes d'eau | **Faible** (< 10 µS/cm) |

<p style="text-align:center;">
  <img src="/21_conductivite/images/emulsion.png" alt="Emulsion H/E et Emulsion E/H" style="width:75%;">
  <br>
  <em>Emulsion H/E et Emulsion E/H</em><br>
  <em>Phase continue = EAU Vs Phase continue = HUILE</em>
</p>




### Pourquoi ça fonctionne ?

Le courant circule dans la **phase continue** (celle qui relie les deux électrodes) :
- Phase continue = **eau** → ions migrent → σ **élevée**
- Phase continue = **huile** → pas d'ions → σ **très faible**

---

### Exemples cosmétiques

| Produit | Type | σ typique | Justification |
|---------|:----:|:---------:|---------------|
| Crème de jour légère | H/E | 800–1 200 µS/cm | Phase aqueuse continue, toucher frais |
| Lait démaquillant | H/E | 900–1 500 µS/cm | Facile à rincer, texture fluide |
| Baume à lèvres | E/H | 2–8 µS/cm | Film occlusif, protection barrière |
| Cold cream | E/H | 1–5 µS/cm | Texture riche, effet protecteur |

---

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   📌 À RETENIR – TYPE D'ÉMULSION :                         │
│                                                             │
│   • σ > 50 µS/cm → émulsion H/E                             │
│   • σ < 10 µS/cm → émulsion E/H                             │
│   • Entre 10 et 50 µS/cm → zone ambiguë                     │
│     (test complémentaire nécessaire)                        │
│   • Test RAPIDE et NON DESTRUCTIF                           │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 4️⃣ Application n°2 : suivi de stabilité

### Principe

En mesurant σ **au cours du temps**, on suit la **stabilité** d'une émulsion :

| Observation | Interprétation |
|-------------|---------------|
| σ **constante** dans le temps | Émulsion **stable** |
| σ **diminue lentement** | Légère modification (sédimentation, crémage) |
| σ **chute brutalement** | **Inversion de phase** probable (H/E → E/H) |
| σ **augmente brutalement** | Inversion inverse (E/H → H/E) ou dissolution d'ions |

---

### Inversion de phase

L'**inversion de phase** est un phénomène de déstabilisation où l'émulsion change de type :
- Une émulsion **H/E** (σ élevée) devient **E/H** (σ faible)
- Causes possibles : température extrême, mauvais tensioactif, cisaillement mécanique

---

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   📌 À RETENIR – STABILITÉ :                               │
│                                                             │
│   Un CHANGEMENT BRUTAL de σ au cours du temps               │
│   signale une DÉSTABILISATION de l'émulsion.                │
│   → Signal d'alerte CQ : quarantainer le lot !              │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 5️⃣ Application n°3 : CMC d'un tensioactif

### Qu'est-ce que la CMC ?

La **Concentration Micellaire Critique (CMC)** est la concentration en tensioactif à partir de laquelle les molécules s'organisent en **micelles**.

| Avant la CMC | Après la CMC |
|-------------|-------------|
| Tensioactifs libres (monomères) | Tensioactifs organisés en **micelles** |
| Pas de solubilisation des corps gras | **Solubilisation** des corps gras dans le cœur des micelles |
| σ augmente **proportionnellement** à C | σ augmente **plus lentement** |

---

### Détermination par conductimétrie

Pour un tensioactif **ionique**  :

<p style="text-align:center;">
  <img src="/21_conductivite/images/graphique_cmc.png" alt="Courbe de conductivité en fonction de la concentration" style="width:75%;">
  <br>
  <em>Courbe de conductivité en fonction de la concentration</em>
</p>




**Méthode :**
1. Tracer σ = f(C)
2. Identifier la **rupture de pente**
3. Tracer les **deux droites moyennes**
4. L'intersection donne la **CMC**

---

### Explication de la rupture de pente

| Phase | Ce qui se passe | Effet sur σ |
|-------|----------------|-------------|
| **Avant CMC** | Chaque tensioactif ionique ajouté libère des ions | σ ↑ **fortement** (∝ C) |
| **À la CMC** | Les monomères s'agrègent en micelles | **Rupture de pente** |
| **Après CMC** | Le tensioactif ajouté forme des micelles (pas de nouveaux ions) | σ ↑ **faiblement** |

---

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   📌 À RETENIR – CMC :                                     │
│                                                             │
│   • CMC = rupture de pente sur σ = f(C)                     │
│   • Avant CMC : monomères libres (pas de micelles)          │
│   • Après CMC : micelles formées (solubilisation possible)  │
│   • En cosmétique : OPTIMISER la concentration              │
│     (pas trop = irritation, pas trop peu = inefficace)      │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 6️⃣ Conductivité et contrôle qualité : synthèse

| Application CQ | Ce qu'on mesure | Ce qu'on en déduit | Exemple de décision |
|----------------|-----------------|---------------------|---------------------|
| **Type d'émulsion** | σ d'un produit | H/E (σ > 50) ou E/H (σ < 10) | Vérifier le type attendu |
| **Stabilité** | σ au cours du temps | Stable (σ ≈ cste) ou instable | Quarantainer si σ chute |
| **CMC** | σ = f(C) | Rupture de pente → CMC | Optimiser la formulation |
| **Conformité** | σ vs cahier des charges | Conforme ou non conforme | Libérer ou rejeter le lot |

---

## 7️⃣ Tableau récapitulatif complet

| Notion | Définition / Formule | Unité | Application cosmétique |
|--------|---------------------|:-----:|----------------------|
| **Conductivité σ** | Capacité à conduire le courant | S/m ou µS/cm | CQ, type d'émulsion |
| **Porteur de charge** | Ion en solution (cation / anion) | — | σ ↑ quand plus d'ions |
| **Émulsion H/E** | Phase continue = eau | σ **élevée** (ordre de grandeur > 50 µS/cm) | Crèmes légères, laits |
| **Émulsion E/H** | Phase continue = huile | σ **faible** (ordre de grandeur < 10 µS/cm) | Baumes, cold cream |
| **Inversion de phase** | Changement H/E ↔ E/H | Chute ou hausse brutale de σ | Instabilité, déstabilisation |
| **CMC** | Concentration micellaire critique | mmol/L | Rupture de pente sur σ = f(C) |
| **Micelle** | Agrégat de tensioactifs | — | Solubilisation des corps gras |

---

## 📌 À retenir pour l'E2

### Définitions essentielles

| Terme | Définition |
|-------|------------|
| **Conductivité (σ)** | Capacité d'une solution à conduire le courant électrique grâce aux ions |
| **Porteur de charge** | Espèce chargée mobile (ions en solution) |
| **Phase continue** | Phase qui entoure les gouttelettes dans une émulsion |
| **CMC** | Concentration à partir de laquelle un tensioactif forme des micelles |
| **Rupture de pente** | Changement brusque de pente sur σ = f(C), signalant la CMC |
| **Conformité** | Respect des spécifications du cahier des charges (valeur ± tolérance) |

### Règles pratiques

| Règle | Application |
|-------|-------------|
| Plus d'ions → σ plus élevée | Interpréter une mesure de σ |
| σ élevée (ordre de grandeur > 50 µS/cm) → émulsion H/E | Identifier le type d'émulsion (à T constante, selon formulation) |
| σ faible (ordre de grandeur < 10 µS/cm) → émulsion E/H | Identifier le type d'émulsion (à T constante, selon formulation) |
| Toujours relier σ à la phase continue | σ élevée ↔ phase aqueuse continue ; σ faible ↔ phase huileuse continue |
| Chute brutale de σ → inversion de phase | Suivre la stabilité |
| Rupture de pente → CMC | Déterminer la CMC par conductimétrie |
| Toujours noter la température | Comparer des mesures CQ |

### Vocabulaire à maîtriser

- **Conductivité, conductimètre, porteur de charge, ion**
- **Émulsion H/E, émulsion E/H, phase continue, phase dispersée**
- **Inversion de phase, stabilité, vieillissement accéléré**
- **CMC, micelle, tensioactif ionique, rupture de pente**
- **Cahier des charges, conformité, tolérance, écart relatif**

---



## 🔧 Fiche méthode associée

➡️ [**Fiche méthode 01 – Justifier une réponse scientifique (O.A.C.J.)**](../Methodologie/01_fiche_methode/)

➡️ [**Fiche méthode 05 – Lire une représentation microscopique (E2)**](../Methodologie/05_fiche_methode/)
