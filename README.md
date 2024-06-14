#Projet : Base de Données des Corps Célestes avec PostgreSQL
Règles pour la base de données des corps célestes
Voici les lignes directrices à suivre pour ce projet afin de créer des tables acceptables.

Exigences à remplir lors de la création des tables :
La base de données doit contenir au moins 5 tables.
Il doit y avoir une table pour les galaxies (≥ 6 lignes), les étoiles (≥ 6 lignes), les planètes (≥ 12 lignes) et les lunes (≥ 20 lignes).
Chaque table doit avoir au moins 3 lignes et 3 colonnes.
Les tables des galaxies, étoiles, planètes et lunes doivent chacune avoir au moins 5 colonnes.
Une clé primaire doit être incluse dans chaque table. La norme de dénomination pour les colonnes de clé primaire doit être nom_table_id. Par exemple, la table des lunes doit inclure une colonne de clé primaire appelée lune_id.
Chaque table doit avoir une colonne nom.
Le type de données INT doit être utilisé dans au moins deux colonnes qui ne sont pas des clés primaires ou étrangères.
Le type de données NUMERIC doit être utilisé au moins une fois.
Le type de données TEXT doit être utilisé au moins une fois.
Le type de données BOOLEAN doit être utilisé dans au moins deux colonnes.
Au moins 2 colonnes par table ne doivent pas accepter de valeurs NULL.
Au moins une colonne de chaque table doit être unique.
Chaque étoile doit avoir une clé étrangère qui référence une des lignes de la table des galaxies.
Chaque planète doit avoir une clé étrangère qui référence une des lignes de la table des étoiles.
Chaque lune doit avoir une clé étrangère qui référence une des lignes de la table des planètes.
Chaque colonne de clé étrangère doit avoir le même nom que la colonne à laquelle elle fait référence.
