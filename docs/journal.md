# Journal du projet

## 24/09 — Setup Azure
- Storage account ADLS Gen2 créé (LRS, tier Hot) — LRS car projet perso, 
  pas besoin de payer plus cher pour de la résilience multi-région
- Hierarchical Namespace : activé (ADLS Gen2)
- Hiérarchie RAW : domaine/source/dataset/type de chargement/date
  → évite le "data swamp" : on sait toujours d'où vient une donnée et quand 
  elle est arrivée
- Dataset choisi : Olist (e-commerce brésilien) — données réelles, 
 sujet business (retards de livraison, satisfaction client)

## [prochaine session] — ...