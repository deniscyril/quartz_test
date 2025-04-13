---
created: 2023-07-22T17:42
updated: 2023-10-14T14:05
---

# TP de Terminale spécialité
## TP de Physique
test
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE updated, Phys_ou_Chim, Classe
FROM "TP" 
WHERE Classe = "Terminale" AND Phys_ou_Chim = "Physique"
```
%%

| File                                                               | updated                      | Phys_ou_Chim | Classe    |
| ------------------------------------------------------------------ | ---------------------------- | ------------ | --------- |
| [[Chute libre parabolique\|Chute libre parabolique]] | \-                           | Physique     | Terminale |
| [[Diffraction\|Diffraction]]                         | 2:22 PM - January 15, 2025   | Physique     | Terminale |
| [[Energie mécanique\|Energie mécanique]]             | 1:34 PM - January 14, 2024   | Physique     | Terminale |
| [[Interférences\|Interférences]]                     | 1:33 PM - January 16, 2025   | Physique     | Terminale |
| [[Lunette astronomique\|Lunette astronomique]]       | 9:33 AM - March 22, 2024     | Physique     | Terminale |
| [[Pointage video\|Pointage video]]                   | 11:02 AM - December 15, 2024 | Physique     | Terminale |
| [[Nucléaire\|Nucléaire]]                             | 6:51 PM - March 17, 2024     | Physique     | Terminale |
| [[RC Microbit\|RC Microbit]]                         | 8:57 AM - March 04, 2025     | Physique     | Terminale |
| [[RC\|RC]]                                           | 2:15 PM - January 31, 2025   | Physique     | Terminale |
| [[Thermodynamique\|Thermodynamique]]                 | 6:04 PM - April 04, 2024     | Physique     | Terminale |
| [[Ultrasons Terminale\|Ultrasons Terminale]]         | 1:52 PM - October 14, 2023   | Physique     | Terminale |

%% DATAVIEW_PUBLISHER: end %%

```dataview
TABLE updated, Phys_ou_Chim, Classe
FROM "content/TP" 
WHERE Classe = "Terminale" AND Phys_ou_Chim = "Physique"
```



## TP de Chimie

```dataview
TABLE creation_date, Phys_ou_Chim, Classe
FROM "content/TP" 
WHERE Classe = "Terminale" AND Phys_ou_Chim = "Chimie"

```

# TP de Seconde
## TP de Physique

```dataview
TABLE creation_date, Phys_ou_Chim, Classe
FROM "SPC/TP" 
WHERE Classe = "Seconde" AND Phys_ou_Chim = "Physique"

```

## TP de Chimie

```dataview
TABLE creation_date, Phys_ou_Chim, Classe
FROM "SPC/TP" 
WHERE Classe = "Seconde" AND Phys_ou_Chim = "Chimie"

```
