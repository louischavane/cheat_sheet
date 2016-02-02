# Liste des commandes principales pour sqlite3


## Pour lancer sqlite3

```bash
sqlite3 db/development.sqlite3
```

## Principales commandes de Sqlite3

|  commande  |   action |
|:-----------|:----------|
| .tables   | affiche toutes les tables |
| .schema   | affiche le schéma de toutes les tables |
| .schema *$tablename* | affiche le schéma d'une table


## Pour améliorer l'affichage de sqlite3
```bash
.headers on
.mode column
```
## Pour regarder ce qu'il y a dans une table
Faire des requêtes SQL
```sql
SELECT * FROM tablename;
```

## debug

