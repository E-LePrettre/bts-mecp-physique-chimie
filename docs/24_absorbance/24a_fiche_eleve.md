---
author: Elisabeth Le Prettre (LePrettre)
title: 24 📝 Fiche élève
---

# S24 – Lampe UV / UV-Visible : spectres et absorbance 📝

**Ondes EM – Spectre UV-visible – Absorbance – Loi de Beer-Lambert – Applications cosmétiques**

---

## 🎯 Objectifs

À l'issue de la séance, vous serez capables de :

- **situer** les domaines UV et visible dans le spectre électromagnétique
- **définir** l'absorbance A et la transmittance T
- **énoncer** et **utiliser** la loi de Beer-Lambert : A = ε × l × C
- **lire** un spectre d'absorption UV-visible ($λ_{max}$, allure)
- **relier** absorbance et concentration pour un dosage spectrophotométrique
- **interpréter** des résultats de mesure pour conclure sur la conformité

---

## 🧴 Pourquoi c'est important pour votre métier ?

La spectrophotométrie UV-visible est l'outil de référence en contrôle qualité cosmétique pour :

- **Doser** les actifs (panthenol, acide salicylique, vitamine C...)
- **Vérifier** la concentration des filtres UV (protection solaire SPF)
- **Contrôler** la couleur des produits (rouges à lèvres, fards, vernis)
- **Valider** les claims d'efficacité (preuves instrumentales)

> 💡 *Si l'absorbance est trop faible → pas assez d'actif → produit non conforme. Si elle est trop forte → surdosage → risque d'irritation. La spectrophotométrie permet de doser avec précision.*

---

## 🧴 Accroche professionnelle

**Situation :** Vous travaillez au laboratoire CQ d'une marque cosmétique. On vous demande de **vérifier** que le lot de crème solaire SPF 50 contient la bonne concentration de **filtre UVA** (avobenzone).

**Problème :** On ne peut pas « voir » la concentration d'un filtre UV à l'œil nu. Il faut une mesure physique : la **spectrophotométrie UV-visible**. En mesurant combien de lumière UV est absorbée par l'échantillon, on peut calculer la concentration exacte du filtre.

**Question :** Comment fonctionne un spectrophotomètre ? Qu'est-ce que l'absorbance ? Comment utiliser la loi de Beer-Lambert pour doser un actif ?

---

## 📄 Documents

### Document 1 – Le spectre électromagnétique

Les **ondes électromagnétiques** (EM) se propagent dans le vide à la vitesse de la lumière : c = 3 × 10⁸ m/s.

Elles sont classées par longueur d'onde λ (ou fréquence f) :

<p style="text-align:center;">
  <img src="/24_absorbance/images/onde_EM.png" alt="spectre électromagnétique" style="width:95%;">
  <br>
  <em>Spectre électromagnétique</em>
</p>


#### Les domaines UV et visible en détail

| Domaine | Longueur d'onde | Caractéristiques | Usage cosmétique |
|---------|:--------------:|------------------|------------------|
| **UVC** | 100 – 280 nm | Très énergétiques, arrêtés par l'ozone | Stérilisation (lampes germicides) |
| **UVB** | 280 – 320 nm | Responsables des coups de soleil | Protection SPF |
| **UVA** | 320 – 400 nm | Responsables du vieillissement cutané | Protection PA / UVA |
| **Violet** | 400 – 450 nm | Lumière visible | LED bleue (anti-acné) |
| **Bleu** | 450 – 495 nm | Lumière visible | — |
| **Vert** | 495 – 570 nm | Lumière visible | — |
| **Jaune** | 570 – 590 nm | Lumière visible | — |
| **Orange** | 590 – 620 nm | Lumière visible | — |
| **Rouge** | 620 – 800 nm | Lumière visible | LED rouge (anti-âge, cicatrisation) |
| **IR** | 800 nm – 1 mm | Chaleur | Lampes IR institut |

> 📌 **Rappel S23 :** c = λ × f. Ici c = 3 × 10⁸ m/s (vitesse de la lumière dans le vide).

> ⚠️ **Différence UV / ultrasons :** Les UV sont des ondes **électromagnétiques** (pas besoin de milieu). Les ultrasons sont des ondes **mécaniques** (besoin d'un gel de contact). Ne pas confondre !

---

### Document 2 – Le spectrophotomètre UV-visible

#### Principe

Un spectrophotomètre mesure la quantité de lumière **absorbée** par un échantillon.

<p style="text-align:center;">
  <img src="/24_absorbance/images/Spectrophotometer.png" alt="Spectrophotomètre" style="width:95%;">
  <br>
  <em>Principe d'un spectrophotomètre</em>
</p>


1. La **lampe** émet un faisceau de lumière (UV ou visible)
2. Le **monochromateur** sélectionne une seule longueur d'onde λ
3. Le faisceau traverse la **cuve** contenant l'échantillon en solution
4. Le **détecteur** mesure l'intensité transmise I
5. L'appareil calcule et affiche l'**absorbance A**

#### Définitions

| Grandeur | Symbole | Formule | Unité |
|----------|:-------:|:-------:|:-----:|
| **Transmittance** | T | T = I / I₀ | Sans unité (ou %) |
| **Absorbance** | A | A = −$log_{10}$(T) = $log_{10}$(I₀/I) | Sans unité |

- I₀ = intensité incidente (lumière envoyée)
- I = intensité transmise (lumière qui ressort)
- ⚠️ Si **T** est exprimée en **%**, convertir : **T = T(%) / 100** avant d'utiliser **$log_{10}$**.
- Si l'échantillon absorbe beaucoup : I petit → T petit → **A grand**
- Si l'échantillon n'absorbe pas : I ≈ I₀ → T ≈ 1 → **A ≈ 0**

---

### Document 3 – Spectres d'absorption UV-visible

#### Spectre 1 : Avobenzone (filtre UVA)

<p style="text-align:center;">
  <img src="/24_absorbance/images/avobenzone.png" alt="Avobenzone" style="width:75%;">
  <br>
  <em>Spectre de l'Avobenzone</em>
</p>

👉 $λ_{max}$ ≈ 360 nm (domaine UVA)


**Interprétation :** L'avobenzone absorbe fortement les UVA (pic à 360 nm) → c'est un **filtre UVA** efficace.

#### Spectre 2 : β-carotène (colorant orange)

<p style="text-align:center;">
  <img src="/24_absorbance/images/carotene.png" alt="Carotène" style="width:75%;">
  <br>
  <em>Spectre du β-carotène</em>
</p>

👉 $λ_{max}$ ≈ 450 nm (domaine visible : bleu-violet)


**Interprétation :** Le β-carotène absorbe le bleu-violet (450 nm) → il apparaît de la couleur complémentaire = **orange**. Utilisé comme colorant alimentaire et cosmétique.

#### Comment lire un spectre ?

| Ce qu'on cherche | Comment le trouver |
|------------------|-------------------|
| **$λ_{max}$** | Sommet du pic (valeur de λ au maximum d'absorption) |
| **Domaine** | UV (< 400 nm) ou visible (400-800 nm) |
| **Usage** | UV → filtre solaire ; visible → colorant |

---

### Document 4 – La loi de Beer-Lambert

#### Énoncé

L'absorbance A d'une solution est **proportionnelle** à la concentration C de l'espèce absorbante :

```
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│               A = ε × l × C                                  │
│                                                              │
│   A : absorbance (sans unité)                                │
│   ε : coefficient d'absorption molaire (L·mol⁻¹·cm⁻¹)        │
│   l : longueur de la cuve (cm) – en général l = 1 cm         │
│   C : concentration molaire (mol·L⁻¹)                        │
│                                                              │
│   Relations dérivées :                                       │
│   C = A / (ε × l)        ε = A / (l × C)                     │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

#### Triangle mnémotechnique

```
        ┌─────┐
        │  A  │
        ├─────┤
        │ε×l×C│
        └─────┘
        
  Pour trouver A : A = ε × l × C (on multiplie le bas)
  Pour trouver C : C = A / (ε × l) (on divise A par le reste)
  Pour trouver ε : ε = A / (l × C)
```

#### Signification physique

| Situation | Absorbance | Concentration |
|-----------|:----------:|:-------------:|
| Solution très diluée | A ≈ 0 (transparente) | C très faible |
| Solution concentrée | A élevée (foncée) | C élevée |
| Si C double | A double | — |

> 📌 **Analogie du thé :** Plus vous mettez de sachets de thé dans la tasse, plus la couleur est foncée → l'absorbance augmente proportionnellement à la concentration.

#### Conditions de validité

La loi de Beer-Lambert est valable si :
- La solution est **diluée** (A < 2)
- La lumière est **monochromatique** (une seule λ)
- La solution est **homogène**
- Il n'y a pas de **réaction chimique** pendant la mesure

---

### Document 5 – Dosage par courbe d'étalonnage

#### Principe

Pour doser un actif dans un produit cosmétique, on utilise une **courbe d'étalonnage** :

1. On prépare des **solutions étalons** de concentration connue
2. On mesure l'**absorbance** de chaque étalon à $λ_{max}$
3. On trace la courbe **A = f(C)** → droite passant par l'origine
4. On mesure l'absorbance de l'**échantillon inconnu**
5. On lit la concentration par **lecture graphique**

#### Exemple : dosage de l'acide salicylique

**Contexte :** On dose l'acide salicylique dans un exfoliant. $λ_{max}$ = 303 nm.

**Solutions étalons :**

| C (mg/L) | 0 | 5 | 10 | 15 | 20 | 25 |
|----------|:-:|:-:|:--:|:--:|:--:|:--:|
| A (à 303 nm) | 0 | 0,18 | 0,36 | 0,54 | 0,72 | 0,90 |

**Courbe d'étalonnage :**

<p style="text-align:center;">
  <img src="/24_absorbance/images/courbe_etalonnage.png" alt="Corbe d'étalonnage" style="width:85%;">
  <br>
  <em>Courbe d'étalonnage</em>
</p>

👉 $C_{éch}$ ≈ 13,9 mg/L


**Cahier des charges :** Acide salicylique : 12 à 16 mg/L

**Conclusion :** $C_{éch}$ ≈ 13,9 mg/L. Cette valeur est comprise dans l'intervalle [12 ; 16] mg/L → le produit est **conforme** au cahier des charges.

---

### Document 6 – Rappel : conversions et formules

| Grandeur | Formule | Unités |
|----------|---------|--------|
| Beer-Lambert | A = ε × l × C | A (s.u.), ε (L·mol⁻¹·cm⁻¹), l (cm), C (mol·L⁻¹) |
| Célérité EM | c = λ × f | c (m/s), λ (m), f (Hz) |
| Concentration massique | Cm = m / V | Cm (g/L), m (g), V (L) |
| Concentration molaire | C = n / V = Cm / M | C (mol/L), M (g/mol) |

---

## 🧪 Travail 1 – Le spectre EM et les UV (10 min)

> 🎯 **Compétence E2 : Mobiliser**

À partir du **Document 1** :

### 1.1 – Compléter le tableau

| Domaine | Bornes de λ | Onde EM ou mécanique ? | Exemple d'usage cosmétique |
|---------|:-----------:|:----------------------:|---------------------------|
| **UV** | _____ à _____ nm | ___________ | ________________________ |
| **Visible** | _____ à _____ nm | ___________ | ________________________ |
| **IR** | _____ nm à _____ mm | ___________ | ________________________ |

### 1.2 – Sous-domaines UV

Complétez :

| Sous-domaine | Bornes de λ | Effet principal sur la peau |
|:------------:|:-----------:|---------------------------|
| **UVC** | _____ à _____ nm | ________________________ |
| **UVB** | _____ à _____ nm | ________________________ |
| **UVA** | _____ à _____ nm | ________________________ |

### 1.3 – Comparaison S23 / S24

Complétez le tableau comparatif :

| Critère | Ultrasons (S23) | UV / Lumière (S24) |
|---------|:---------------:|:------------------:|
| Type d'onde | ______________ | ______________ |
| Besoin d'un milieu ? | ______________ | ______________ |
| Célérité dans le vide | ______________ | ______________ |
| Gel de contact nécessaire ? | ______________ | ______________ |

---

## 🔍 Travail 2 – Le spectrophotomètre et les spectres (15 min)

> 🎯 **Compétence E2 : Mobiliser, Analyser**

### 2.1 – Légender le schéma

À partir du **Document 2**, légendez les 5 éléments du spectrophotomètre :

```
┌─────①──────┐   ┌──────②───────┐   ┌───③────┐   ┌────④────┐   ┌───⑤───┐
│            │ → │              │ → │        │ → │         │ → │       │
└────────────┘   └──────────────┘   └────────┘   └─────────┘   └───────┘
```

① __________________ ② __________________ ③ __________________

④ __________________ ⑤ __________________

### 2.2 – Lire un spectre d'absorption

À partir du **Document 3** :

a) **Spectre de l'avobenzone :** Déterminez $λ_{max}$ et le domaine d'absorption (UV ou visible).

$λ_{max}$ = _________ nm → domaine : __________

b) **Spectre du β-carotène :** Déterminez $λ_{max}$ et la couleur de la molécule.

$λ_{max}$ = _________ nm → domaine : __________

Couleur absorbée : __________ → Couleur observée : __________

c) Pourquoi l'avobenzone est-elle utilisée comme filtre solaire ? (2-3 lignes)

<br><br><br>

---

## 📐 Travail 3 – La loi de Beer-Lambert (15 min)

> 🎯 **Compétence E2 : Mobiliser, Analyser, Interpréter**

À partir du **Document 4** :

### 3.1 – Énoncer la loi

Complétez :

L'absorbance A d'une solution est _________________ à la concentration C de l'espèce absorbante.

Formule : A = _________ × _________ × _________

### 3.2 – Calcul direct

On mesure l'absorbance d'une solution de panthenol à $λ_{max}$ = 210 nm dans une cuve de l = 1 cm.

**Données :** A = 0,85 ; ε = 170 L·mol⁻¹·cm⁻¹ ; l = 1 cm.

Calculez la concentration molaire C du panthenol (méthode D.U.C.I.) :

<br><br><br><br>

### 3.3 – Calcul inverse

On veut préparer une solution de vitamine C (acide ascorbique) telle que A = 1,00 à λ = 265 nm.

**Données :** ε = 7 500 L·mol⁻¹·cm⁻¹ ; l = 1 cm.

Calculez la concentration molaire C nécessaire (méthode D.U.C.I.) :

<br><br><br><br>

### 3.4 – Interpréter

On prépare deux solutions de panthenol : la solution A à C = 0,002 mol/L et la solution B à C = 0,004 mol/L.

Sans calcul, que vaut l'absorbance de B par rapport à celle de A ? Justifiez.

<br><br>

---

## 📊 Travail 4 – Dosage par courbe d'étalonnage (15 min)

> 🎯 **Compétence E2 : Analyser, Interpréter, Argumenter**

À partir du **Document 5** :

### 4.1 – Lecture graphique

L'absorbance mesurée pour l'échantillon d'exfoliant est A_éch = 0,50 (à λ = 303 nm).

a) Déterminez la concentration en acide salicylique par lecture graphique sur la courbe du Document 5.

$C_{éch}$ = _________ mg/L

b) Décrivez la méthode de lecture graphique en 2-3 lignes :

<br><br><br>

### 4.2 – Vérification de conformité

Le cahier des charges de l'exfoliant indique : **acide salicylique : 12 à 16 mg/L**.

a) Rappelez l'intervalle de conformité : [________ ; ________] mg/L

b) Le produit est-il conforme ? Justifiez avec **2 arguments** :

Argument 1 : .....................................................................

.....................................................................

Argument 2 : .....................................................................

.....................................................................

Conclusion : .....................................................................

### 4.3 – Réflexion

Pourquoi mesure-t-on toujours l'absorbance à **$λ_{max}$** et pas à une autre longueur d'onde ? (2-3 lignes)

<br><br><br>

---

## ✅ Synthèse personnelle

Rédigez une synthèse de **8 à 12 lignes** qui explique le principe de la spectrophotométrie UV-visible, la loi de Beer-Lambert, et son utilisation pour doser un actif cosmétique.

**Mots obligatoires à utiliser** : spectre électromagnétique, UV, absorbance, Beer-Lambert, concentration, courbe d'étalonnage, $λ_{max}$, conformité.

<br><br><br><br><br><br><br><br>

---

## 🎯 Entraînement filé

**Situation :** Une collègue stagiaire au laboratoire CQ vous demande :

> *« Pourquoi faut-il mesurer à $λ_{max}$ et pas à n'importe quelle longueur d'onde ? »*

**Rédigez une réponse professionnelle (4 à 6 lignes).**

<br><br><br><br>

---

## 🗺️ Auto-évaluation

| Je sais… | Pas du tout | Un peu | Plutôt bien | Très bien |
|----------|:-----------:|:------:|:-----------:|:---------:|
| Situer UV et visible dans le spectre EM | ☐ | ☐ | ☐ | ☐ |
| Distinguer UVA, UVB, UVC | ☐ | ☐ | ☐ | ☐ |
| Définir l'absorbance A | ☐ | ☐ | ☐ | ☐ |
| Énoncer la loi de Beer-Lambert | ☐ | ☐ | ☐ | ☐ |
| Utiliser A = ε × l × C pour un calcul | ☐ | ☐ | ☐ | ☐ |
| Lire un spectre UV-vis (trouver $λ_{max}$) | ☐ | ☐ | ☐ | ☐ |
| Utiliser une courbe d'étalonnage | ☐ | ☐ | ☐ | ☐ |
| Conclure sur la conformité d'un dosage | ☐ | ☐ | ☐ | ☐ |

### Si vous avez coché "Pas du tout" ou "Un peu" :

| Notion à retravailler | Action |
|-----------------------|--------|
| Spectre EM | Revoir Document 1, mémoriser les bornes UV/visible |
| Loi de Beer-Lambert | Revoir Document 4, utiliser le triangle mnémotechnique |
| Courbe d'étalonnage | Revoir Document 5, s'entraîner à la lecture graphique |

---

## 🔧 Outils méthodologiques

➡️ [**Fiche méthode 02 – Calculer et interpréter (D.U.C.I.)**](https://bts-mecp-physique-chimie-688080.forge.apps.education.fr/Methodologie/02_fiche_methode/)

➡️ [**Fiche méthode 01 – Justifier une réponse scientifique (O.A.C.J.)**](https://bts-mecp-physique-chimie-688080.forge.apps.education.fr/Methodologie/01_fiche_methode/)

---

## 🔗 Lien avec la suite

⬅️ Séance précédente : [S23 – Appareils à ondes : ultrasons](../23_spectroscopie/)

➡️ Séance suivante : [S25 – Choisir et sécuriser un appareil](../25_securite/)