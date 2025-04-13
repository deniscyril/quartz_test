---
created: 2023-07-22T17:42
updated: 2023-10-14T14:05
---
# TEST 13AVril
# TP de Terminale spécialité
## TP de Physique

%% DATAVIEW_PUBLISHER: start
```dataview
TABLE updated, Phys_ou_Chim, Classe
FROM "TP" 
WHERE Classe = "Terminale" AND Phys_ou_Chim = "Physique"
```
%%

| File | updated | Phys_ou_Chim | Classe |
| ---- | ------- | ------------ | ------ |

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
