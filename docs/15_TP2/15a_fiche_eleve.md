---
author: Elisabeth Le Prettre (LePrettre)
title: 15 🧪 TP2 Fiche élève 
---

# S15 – Titrage acido-basique et solutions tampons 📝

**Principe du titrage – Équivalence – Relation à l'équivalence – Solutions tampons**

> Cette fiche couvre la **1re heure** de la séance. Elle installe les concepts nécessaires **avant** de passer à la manipulation (TP2). Après cette heure, vous aurez tous les outils pour réaliser et exploiter un titrage pH-métrique.

---

## 🎯 Objectifs

À l'issue de cette heure, vous serez capables de :

- **expliquer** le principe d'un titrage acido-basique
- **identifier** le point d'équivalence sur une courbe pH = f(V)
- **écrire** et **utiliser** la relation à l'équivalence pour calculer une quantité de matière
- **définir** une solution tampon et expliquer son rôle en cosmétique

---

## 🧴 Pourquoi c'est important pour votre métier ?

Le titrage est **l'outil de contrôle qualité** le plus courant en laboratoire cosmétique :

- Vérifier la **concentration d'un actif** (acide glycolique dans un peeling, allantoïne dans une crème)
- Contrôler la **conformité** d'un lot avant commercialisation
- Valider qu'un produit respecte le **cahier des charges**

> 💡 *À l'épreuve E2, vous ne réalisez jamais le titrage : les résultats sont fournis. Mais vous devez savoir les EXPLOITER. C'est ce qu'on apprend ici.*

---

## 📄 Documents

### Document I – Principe du titrage pH-métrique

Un **titrage** (ou dosage) est une méthode qui permet de déterminer la **concentration** ou la **quantité de matière** d'une espèce en solution.

#### Principe

On ajoute progressivement une **solution titrante** (de concentration **connue**) dans une **solution titrée** (de concentration **inconnue**), et on mesure le **pH** après chaque ajout.

```
         BURETTE
         ┌───┐
         │   │ ← Solution titrante (NaOH, concentration connue)
         │   │    On verse mL par mL
         └─┬─┘
           │
           ▼
     ┌───────────┐
     │           │ ← Solution titrée (acide cosmétique, concentration inconnue)
     │  BÉCHER   │ ← Sonde pH-mètre (mesure le pH en continu)
     │           │ ← Agitateur magnétique (mélange)
     └───────────┘
```

On obtient une courbe **pH = f(V_versé)**.

---

### Document II – La courbe pH = f(V) et ses 3 zones



![Titrage pH-métrique](pH_1014.png)

| Zone | pH | Signification chimique |
|:----:|:--:|----------------------|
| **Zone 1** (avant le saut) zone de A à B | Varie lentement | L'acide est encore en excès → il reste de l'acide non titré |
| **Zone 2** (saut) | Varie **brutalement** zone de B à C| On approche puis dépasse l'**équivalence** |
| **Zone 3** (après le saut) zone de C à D| Varie lentement | La base ajoutée est en excès |

> 💡 *Le saut de pH est le signal : on vient de consommer TOUT l'acide. C'est le point d'équivalence.*

---

### Document III – La relation à l'équivalence

#### Définition de l'équivalence

À l'**équivalence**, les réactifs ont été mélangés en **proportions stœchiométriques** : tout l'acide a réagi avec toute la base ajoutée.

#### La relation clé

Pour un titrage d'un acide AH par une base forte (NaOH → HO⁻) :

$$AH + HO^- \rightarrow A^- + H_2O$$

À l'équivalence :

$$\boxed{n(acide) = n(base) = C_{titrante} \times V_E}$$

| Symbole | Grandeur | Unité |
|:-------:|----------|:-----:|
| n(acide) | Quantité de matière d'acide dans le bécher | mol |
| C_titrante | Concentration de la solution titrante (connue) | mol/L |
| $V_E$ | Volume à l'équivalence (lu sur la courbe) | **L** (attention : convertir les mL !) |

#### Pour trouver la masse

$$\boxed{m = n \times M}$$

---

### Document IV – Les solutions tampons

#### Définition

Une **solution tampon** est une solution dont le **pH varie peu** lors de l'ajout modéré d'un acide, d'une base ou lors d'une dilution.

#### Composition

Un tampon est constitué d'un **acide faible** et de sa **base conjuguée** (même couple AH/A⁻).

$$\text{Tampon} = AH + A^- \quad \text{(même couple, mélangés)}$$

#### Zone de fonctionnement

Un tampon est efficace au **voisinage du pKa** :

$$\boxed{pH_{tampon} \approx pK_a \pm 1}$$

> 💡 *Lien avec S14 : autour du pKa, les deux formes (AH et A⁻) coexistent. Elles peuvent absorber les variations de pH → effet tampon.*

#### Exemples en cosmétique

| Tampon | Composition | pH ≈ | Usage |
|--------|:-----------:|:----:|-------|
| Citrate | Acide citrique + citrate de Na | 3–6 | Stabilisation pH des crèmes |
| Lactate | Acide lactique + lactate de Na | 3–5 | Soins hydratants |
| Phosphate | H₂PO₄⁻ + HPO₄²⁻ | 6–8 | Tampons biologiques (sang) |

#### Rôle en cosmétique

| Fonction | Explication |
|----------|-------------|
| **Stabiliser le pH** | Le pH ne dérive pas pendant le stockage (DLC) |
| **Résister aux variations** | Contact avec la peau (pH ≈ 5,5) ne modifie pas le pH du produit |
| **Garantir l'efficacité** | Un actif pH-dépendant reste sous sa forme active (lien pKa) |

---

## 🧪 Travail A – Comprendre la courbe (5 min)

> 🎯 **Compétence E2 : Analyser**

À partir du **Document II** :

**A1.** Décrivez l'allure générale de la courbe pH = f(V) en 2 à 3 phrases :

<br><br><br>

**A2.** À quoi correspond chimiquement la zone de variation rapide du pH ?

<br><br>

**A3.** Le pH initial est-il acide ou basique ? Est-ce cohérent avec le fait qu'on titre un acide ? Justifiez.

<br><br>

---

## 🧮 Travail B – Exploiter la relation à l'équivalence (5 min)

> 🎯 **Compétence E2 : Appliquer, Calculer**

Un laboratoire titre l'allantoïne (acide, noté HA) par une solution de NaOH.

**Données :**
- C(NaOH) = 0,50 mol/L
- $V_E$ = 12,0 mL (déterminé sur la courbe)
- M(allantoïne) = 158 g/mol

**B1.** Convertissez $V_E$ en litres :

> $V_E$ = _______ mL = _______ L

**B2.** Écrivez la relation à l'équivalence :

<br>

**B3.** Calculez n(allantoïne) :

<br><br>

**B4.** Calculez m(allantoïne) :

<br><br>

---

## 🧪 Travail C – Reconnaître un tampon (3 min)

> 🎯 **Compétence E2 : Mobiliser**

Pour chaque mélange, indiquez s'il constitue un tampon et justifiez :

| Mélange | Tampon ? (oui/non) | Justification |
|---------|:------------------:|---------------|
| Acide lactique + lactate de sodium | _______ | _______ |
| HCl + NaCl | _______ | _______ |
| Acide citrique + citrate de sodium | _______ | _______ |
| NaOH + eau | _______ | _______ |

---

## ✅ Auto-vérification avant le TP

Avant de passer à la manipulation, vérifiez :

| Je sais… | ✓ |
|----------|---|
| Décrire le principe d'un titrage | ☐ |
| Identifier les 3 zones sur une courbe pH = f(V) | ☐ |
| Écrire la relation à l'équivalence | ☐ |
| Convertir $V_E$ de mL en L | ☐ |
| Calculer n puis m à partir de $V_E$| ☐ |
| Définir une solution tampon | ☐ |

> 💡 Si vous avez coché toutes les cases, vous êtes prêt(e) pour le TP !

---

## 🔧 Outils méthodologiques

➡️ [**Fiche méthode 02 – Calculer et interpréter une concentration (D.U.C.I.)**](https://bts-mecp-physique-chimie-688080.forge.apps.education.fr/Methodologie/02_fiche_methode/)

➡️ [**Fiche méthode 07 – Exploiter un titrage acido-basique**](https://bts-mecp-physique-chimie-688080.forge.apps.education.fr/Methodologie/07_fiche_methode/)
