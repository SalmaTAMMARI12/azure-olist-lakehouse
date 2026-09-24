# Journal du projet

## 24/09 — Setup Azure
- Storage account ADLS Gen2 créé (LRS, tier Hot) 
- Hierarchical Namespace est activé (ADLS Gen2) : transforme le Blob Storage classique en véritable Data Lake(vrais dossiers imbriqués, performance optimisée pour l'analytique), condition nécessaire pour construire l'architecture medallion.
- LRS: données activement manipulées pendant la phase de développementdu projet. Réévaluation possible plus tard vers Cool si certaines données deviennent peu consultées
- Hiérarchie RAW : domaine/source/dataset/type de chargement/date
  → évite le "data swamp" : on sait toujours d'où vient une donnée et quand 
  elle est arrivée
- Dataset choisi : Olist (e-commerce brésilien) — données réelles, 
 sujet business (retards de livraison, satisfaction client)

## [prochaine session] — ...
