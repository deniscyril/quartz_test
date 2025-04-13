---
created: 2023-07-22T17:42
updated: 2023-10-14T14:05
---

# TP de Terminale spécialité
## TP de Physique

```dataview
TABLE updated, Phys_ou_Chim, Classe
FROM "SPC/TP" 
WHERE Classe = "Terminale" AND Phys_ou_Chim = "Physique"

```

## TP de Chimie

```dataview
TABLE creation_date, Phys_ou_Chim, Classe
FROM "SPC/TP" 
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
