# Gestion BDD

## Création table


```sql
-- Etudiants definition

CREATE TABLE Etudiants (
	id INTEGER NOT NULL,
	nom TEXT(50),
	prenom TEXT,
	naissance TEXT(10),
	email TEXT(100), age INTEGER, ville VARCHAR(50),
	CONSTRAINT Etudiants_PK PRIMARY KEY (id)
);
```
## Ajout de ligne

```sql
-- Insertion d'une ligne dans la table
INSERT INTO Etudiants (id,nom,prenom,naissance,email)
VALUES (25, 'Jonathan', 'Daval', '2000-01-16', 'jonathan.daval@ki.fr');
```

## Mise à jour de ligne
```sql
