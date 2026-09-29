---
author: Elisabeth Le Prettre (LePrettre)
title: 04 📖 Trace écrite
---

# S04 – Dilution en formulation : méthode et justification 📖

**Dilution – Facteur de dilution – Conservation de la matière**

---

## 1️⃣ Qu'est-ce qu'une dilution ?

### 🔹 Définition

La **dilution** est une opération qui consiste à **diminuer la concentration** d'une solution en **ajoutant du solvant**.

### 🔹 Ce qui change et ce qui ne change pas

| Grandeur | Après dilution |
|----------|----------------|
| Volume de solution | **Augmente** (on ajoute du solvant) |
| Concentration | **Diminue** |
| Quantité de soluté (masse) | **Reste constante** |

📌 **Important** : On n'ajoute **jamais de soluté** lors d'une dilution, seulement du solvant.

---

## 2️⃣ Vocabulaire de la dilution

| Terme | Définition | Notation |
|-------|------------|:--------:|
| **Solution mère** | Solution initiale, concentrée | Cm, Vm |
| **Solution fille** | Solution obtenue après dilution, moins concentrée | Cf, Vf |
| **Facteur de dilution** | Nombre par lequel la concentration est divisée | F |

### 🔹 Schéma

```
SOLUTION MÈRE                              SOLUTION FILLE
(concentrée)                               (diluée)
                                           
   Cm, Vm          + solvant                  Cf, Vf
     ●━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━►○
                                           
Concentration      Ajouter du solvant      Concentration
   élevée          (eau, généralement)        faible
```

---

## 3️⃣ La relation de conservation

### 🔹 Principe fondamental

Lors d'une dilution, la **quantité de soluté est conservée** :

- Masse de soluté avant = Masse de soluté après
- mi = mf

### 🔹 Démonstration

On sait que m = C × V, donc :

$$m_i = C_m \times V_m \quad \text{et} \quad m_f = C_f \times V_f$$

Comme mi = mf :

$$\boxed{C_m \times V_m = C_f \times V_f}$$

### 🔹 Signification des grandeurs

| Grandeur | Signification | Unité |
|----------|---------------|:-----:|
| **Cm** | Concentration de la solution mère | g/L |
| **Vm** | Volume prélevé de solution mère | L ou mL |
| **Cf** | Concentration de la solution fille | g/L |
| **Vf** | Volume final de solution fille | L ou mL |

📌 **Attention** : Vm et Vf doivent être dans la **même unité** (tous les deux en mL ou tous les deux en L).

---

## 4️⃣ Le facteur de dilution

### 🔹 Définition

Le **facteur de dilution (F)** indique combien de fois la concentration est **divisée** :

$$\boxed{F = \frac{C_m}{C_f} = \frac{V_f}{V_m}}$$

### 🔹 Exemples

| Expression | Facteur F | Signification |
|------------|:---------:|---------------|
| Dilution au 1/2 | 2 | Cf = Cm / 2 |
| Dilution au 1/5 | 5 | Cf = Cm / 5 |
| Dilution au 1/10 | 10 | Cf = Cm / 10 |
| Dilution au 1/100 | 100 | Cf = Cm / 100 |

### 🔹 Utilité

Le facteur de dilution permet de :
- **Vérifier** un calcul (deux façons de calculer F)
- **Exprimer simplement** une dilution ("dilution 10 fois")
- **Planifier** des dilutions successives

---

## 5️⃣ Calculer le volume à prélever

### 🔹 Formule à utiliser

Pour trouver **Vm** (volume de solution mère à prélever) :

$$\boxed{V_m = \frac{C_f \times V_f}{C_m}}$$

### 🔹 Exemple

**Énoncé** : Préparer 100 mL de solution à 20 g/L à partir d'une solution mère à 80 g/L.

**Données** :
- Cm = 80 g/L
- Cf = 20 g/L
- Vf = 100 mL
- Vm = ?

**Calcul** :

$$V_m = \frac{C_f \times V_f}{C_m} = \frac{20 \times 100}{80} = 25 \text{ mL}$$

**Vérification** :
- F = Cm / Cf = 80 / 20 = 4
- F = Vf / Vm = 100 / 25 = 4 ✓

**Interprétation** : Il faut prélever 25 mL de solution mère et compléter jusqu'à 100 mL avec du solvant.

---

## 6️⃣ Protocole de dilution

### 🔹 Étapes

```
PROTOCOLE DE DILUTION

1. CALCULER le volume Vm à prélever

2. PRÉLEVER Vm de solution mère avec une pipette jaugée adaptée

3. VERSER dans une fiole jaugée de volume Vf

4. AJOUTER du solvant jusqu'aux 2/3 environ

5. HOMOGÉNÉISER (agiter doucement)

6. COMPLÉTER avec du solvant jusqu'au trait de jauge
   (ménisque tangent au trait)

7. BOUCHER et HOMOGÉNÉISER (retourner plusieurs fois)

8. ÉTIQUETER (nom, concentration, date)
```

### 🔹 Schéma du protocole

```
   Solution mère         Pipette jaugée        Fiole jaugée
       (Cm)                  (Vm)                 (Vf)
        │                     │                    │
        │    Prélever Vm      │                    │
        └────────────────────►│                    │
                              │    Verser          │
                              └───────────────────►│
                                                   │
                              Solvant              │
                                 │    Compléter    │
                                 └────────────────►│
                                                   │
                                            Homogénéiser
                                                   │
                                                   ▼
                                            Solution fille
                                                (Cf)
```

---

## 7️⃣ Dilutions successives (en cascade)

### 🔹 Quand les utiliser ?

Quand le facteur de dilution est **très grand** (F > 100), il est plus précis de faire **plusieurs dilutions successives**.

### 🔹 Principe

Au lieu d'une seule dilution de facteur F, on fait plusieurs dilutions de facteurs plus petits :

$$F_{total} = F_1 \times F_2 \times F_3 \times ...$$

### 🔹 Exemple

Préparer une solution à 0,1 g/L à partir d'une solution à 100 g/L.

**Facteur total** : F = 100 / 0,1 = 1000

**En une seule étape** : Vm = 0,1 mL pour 100 mL → **Trop imprécis !**

**En 3 étapes** (dilutions au 1/10) :

```
100 g/L  ──(F=10)──►  10 g/L  ──(F=10)──►  1 g/L  ──(F=10)──►  0,1 g/L
```

F = 10 × 10 × 10 = 1000 ✓

À chaque étape, Vm = 10 mL pour 100 mL → **Plus précis !**

---

## 8️⃣ Conseils pratiques

### 🔹 Choix de la verrerie

| Volume à prélever | Verrerie recommandée |
|-------------------|---------------------|
| < 1 mL | Micropipette |
| 1 – 25 mL | Pipette jaugée |
| > 25 mL | Pipette jaugée ou éprouvette graduée |

### 🔹 Règles de précision

- Éviter de prélever des volumes **< 5 mL** (imprécis)
- Éviter des facteurs de dilution **> 100** en une seule étape
- Toujours **vérifier** le calcul avec le facteur de dilution

---

## 9️⃣ À retenir pour l'épreuve E2

### ✅ Formules essentielles

| Formule | Utilisation |
|---------|-------------|
| Cm × Vm = Cf × Vf | Relation de conservation |
| Vm = (Cf × Vf) / Cm | Calculer le volume à prélever |
| F = Cm / Cf = Vf / Vm | Facteur de dilution |

### ✅ Points clés

- Diluer = ajouter du **solvant** (pas du soluté)
- La **quantité de soluté est conservée**
- Toujours **vérifier** avec le facteur de dilution
- Rédiger un **protocole complet** si demandé

### ✅ Erreurs à éviter

| ❌ Erreur | ✅ Correction |
|----------|--------------|
| Inverser Cm et Cf | Cm = mère (concentrée), Cf = fille (diluée) |
| Confondre Vm et Vf | Vm = prélevé, Vf = volume final |
| Oublier de compléter au trait | Le volume final doit être exact |

---

## 🔗 Lien avec la suite de la progression

Dans la **séance suivante (S05 – TP1)**, vous mettrez en pratique :
- La **dissolution** (préparer une solution mère)
- La **dilution** (préparer des solutions filles)
- L'**échelle de teinte** (exploiter visuellement les concentrations)

---

## 🔧 Outils méthodologiques associés

➡️ [**Fiche méthode 02 – Calculer et interpréter une concentration**](https://bts-mecp-physique-chimie-688080.forge.apps.education.fr/Methodologie/02_fiche_methode/)

➡️ [**Fiche méthode 04 – Choisir et justifier une dilution**](https://bts-mecp-physique-chimie-688080.forge.apps.education.fr/Methodologie/04_fiche_methode/)
