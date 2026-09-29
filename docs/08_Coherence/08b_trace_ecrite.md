---
author: Elisabeth Le Prettre (LePrettre)
title: 08 📖 Trace écrite
---

# S08 – Cohérence des résultats


---



## 1️⃣ Vérification par les unités

### Principe

L'**analyse dimensionnelle** permet de vérifier qu'un calcul est correct en vérifiant que les unités du résultat correspondent à celles attendues.

### Méthode

1. Écrire la formule utilisée
2. Remplacer chaque grandeur par son unité
3. Simplifier les unités
4. Vérifier que l'unité obtenue est celle attendue

### Exemple

| Calcul correct | Calcul incorrect |
|----------------|------------------|
| Cm = m / V | Cm = m × V |
| Cm = g / L = **g/L** ✓ | Cm = g × L = **g·L** ✗ |

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   📌 RÈGLE : Si les unités ne correspondent pas,            │
│              le calcul est FAUX                             │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 2️⃣ Ordres de grandeur

### Définition

Un **ordre de grandeur** est une estimation approximative d'une valeur, souvent exprimée comme une puissance de 10.

### Valeurs typiques en cosmétique

| Grandeur | Valeur typique | Valeur suspecte |
|----------|:--------------:|:---------------:|
| Concentration d'actif | 1 à 200 g/L | > 500 g/L |
| pH cutané | 4 à 8 | < 2 ou > 12 |
| Densité d'une huile | 0,85 à 0,96 | < 0,5 ou > 1,5 |
| Densité d'une crème | 0,95 à 1,05 | < 0,7 ou > 1,3 |
| Masse volumique de l'eau | ≈ 1,00 g/mL | ≠ 1,00 |

### Erreurs courantes

| Erreur | Exemple | Cause probable |
|--------|---------|----------------|
| Facteur 10 | pH = 85 au lieu de 8,5 | Oubli de virgule |
| Facteur 100 | d = 0,0092 au lieu de 0,92 | Erreur de virgule |
| Facteur 1000 | ρ = 1000 g/mL au lieu de 1,00 g/mL | Confusion d'unité |

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   📌 RÉFLEXE : Un résultat très différent de l'attendu     │
│               doit alerter → vérifier le calcul             │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 3️⃣ Moyenne d'une série de mesures

### Définition

La **moyenne** (notée x̄) est la valeur centrale d'une série de mesures.

$$\boxed{\bar{x} = \frac{x_1 + x_2 + ... + x_n}{n} = \frac{\sum x_i}{n}}$$

### Exemple

Mesures de pH : 5,8 ; 5,9 ; 5,7 ; 5,8

$$\bar{x} = \frac{5,8 + 5,9 + 5,7 + 5,8}{4} = \frac{23,2}{4} = 5,80$$

### Utilité

- Obtenir une **valeur représentative** de la série
- **Réduire l'effet** des erreurs aléatoires
- **Comparer** au cahier des charges

---

## 4️⃣ Dispersion simple : min, max, étendue (outil “CQ”)

> Objectif : décrire si les mesures sont **regroupées** ou **dispersées** avec des outils simples.

### 4.1 Valeurs extrêmes : min / max

- **x_min** : plus petite valeur mesurée  
- **x_max** : plus grande valeur mesurée

### 4.2 Étendue (E)

L’**étendue** mesure l’écart global entre la plus grande et la plus petite valeur.

$$\boxed{E = x_{max} - x_{min}}$$

### Interprétation

| Étendue | Signification | Qualité des mesures |
|--------:|---------------|---------------------|
| **Faible** | Valeurs proches | Bonne répétabilité |
| **Élevée** | Valeurs dispersées | Mesures à vérifier |

### Avec une tolérance interne

En laboratoire, on compare souvent l’étendue à une **tolérance** (procédure interne) :

- Si **E ≤ tolérance** → série acceptable (répétable)
- Si **E > tolérance** → vérifier manipulation / refaire une partie des mesures

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   📌 ASTUCE CQ : Toujours donner la moyenne + min/max      │
│      (ou la moyenne + l’étendue) pour résumer une série     │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 5️⃣ Écart à une valeur de référence (contrôle)

On compare parfois une mesure à une valeur de référence (eau, valeur cible, consigne…).

### Écart absolu (Δ)

$$\boxed{\Delta = |x - x_{ref}|}$$

### Écart relatif (en %)

$$\boxed{\varepsilon_r = \frac{|x - x_{ref}|}{x_{ref}} \times 100}$$

**Utilité :**
- quantifier “de combien je suis loin”
- décider si c’est acceptable (selon le cahier des charges / une tolérance)

---

## 6️⃣ Valeur aberrante

### Définition

Une **valeur aberrante** est une mesure qui s'écarte significativement des autres valeurs de la série.

### Comment la détecter ?

| Méthode | Critère |
|---------|---------|
| **Visuelle** | Valeur très différente des autres |
| **Statistique** | Valeur à plus de 2-3σ de la moyenne |
| **Ordre de grandeur** | Valeur incohérente avec le contexte |

### Exemple

Mesures de pH : 5,8 ; 5,9 ; **12,4** ; 5,7 ; 5,8

→ La valeur **12,4** est aberrante (très éloignée des autres)

### Que faire d'une valeur aberrante ?

| Option | Quand l'utiliser |
|--------|------------------|
| **Écarter** | Si l'erreur est identifiée (manip, lecture) |
| **Refaire la mesure** | Si un doute subsiste |
| **Conserver** | Si elle reflète une vraie anomalie du produit |

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   📌 IMPORTANT : Toujours JUSTIFIER la décision            │
│                 d'écarter ou de conserver                   │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 7️⃣ Arbre de décision

### Procédure de validation d'un résultat

```
                    RÉSULTAT OBTENU
                          │
            ┌─────────────┴─────────────┐
            │                           │
     Unités correctes ?            Unités fausses
            │                           │
           OUI                      REFAIRE LE
            │                        CALCUL
            ▼
     Ordre de grandeur              
        cohérent ?                  
            │                       
      ┌─────┴─────┐                
     OUI         NON               
      │           │                
      ▼           ▼                
   Cohérent    VÉRIFIER LA         
   avec les    MANIPULATION        
   autres      OU REFAIRE          
   mesures ?                       
      │                            
  ┌───┴───┐                       
 OUI     NON                      
  │       │                       
  ▼       ▼                       
VALIDER  ÉCARTER OU               
         REFAIRE                  
```

---

## 8️⃣ Rédiger une recommandation professionnelle

### Structure attendue (E2)

| Étape | Contenu | Mots clés |
|-------|---------|-----------|
| **1. Constat** | Présenter les données et identifier le problème | "On observe que...", "La valeur X est..." |
| **2. Analyse** | Expliquer pourquoi c'est un problème | "Cette valeur s'écarte de...", "Cet écart suggère..." |
| **3. Décision** | Indiquer ce qu'on fait de la valeur | "Je recommande d'écarter...", "Il convient de refaire..." |
| **4. Conclusion** | Statuer sur la conformité | "Le lot est conforme/non conforme car..." |

### Exemple de rédaction

> *Le lot B présente une valeur de 180 g/L, nettement supérieure aux trois autres mesures (115, 117, 116 g/L). Cette valeur aberrante est probablement due à une erreur de manipulation. Je recommande de l'écarter et de refaire cette mesure pour confirmation. En excluant cette valeur, la moyenne corrigée (116 g/L) est conforme au cahier des charges [110-130 g/L]. Sous réserve de confirmation, le lot peut être validé.*

---

## 📌 À retenir pour l'E2

### Les 3 vérifications essentielles

| Vérification | Question à se poser |
|--------------|---------------------|
| **Unités** | Mon résultat a-t-il la bonne unité ? |
| **Ordre de grandeur** | Ma valeur est-elle réaliste ? |
| **Cohérence** | Ma valeur est-elle cohérente avec les autres mesures ? |

### Formules à connaître

| Formule | Utilisation |
|---------|-------------|
| x̄ = Σxᵢ / n | Calculer la moyenne |
| E = x_max − x_min | Mesurer la dispersion (étendue) |
| Δ = \|x − x_ref\| | Écart absolu |
| ε_r = ( \|x − x_ref\| / x_ref ) × 100 | Écart relatif (%) |

### Vocabulaire à maîtriser

- **Valeur aberrante** : mesure qui s'écarte significativement
- **Répétabilité** : résultats proches lors de répétitions dans les mêmes conditions
- **Dispersion** : étalement des valeurs dans une série
- **Min/Max/Étendue** : outils simples pour décrire la dispersion
- **Tolérance** : critère interne pour accepter une série

---

## 🔗 Lien avec la suite de la progression

| Séance | Réinvestissement |
|--------|------------------|
| **S09** | pH (vérification de cohérence sur les mesures de pH) |
| **S10 (TP2)** | pH-métrie (analyse d'une série de mesures) |
| **S11** | Évaluation n°2 (questions sur la cohérence des résultats) |
| **S16** | Variabilité de la mesure (approfondissement statistique) |

---

## 🔧 Fiche méthode associée

➡️ [**Fiche méthode 01 – Justifier une réponse scientifique (O.A.C.J.)**](https://bts-mecp-physique-chimie-688080.forge.apps.education.fr/Methodologie/01_fiche_methode/)
