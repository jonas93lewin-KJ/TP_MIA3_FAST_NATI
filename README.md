GESTION D'UN PERSONNEL UNIVERSITAIRE

1. Présentation du projet

Ce projet consiste à développer une application en C++ permettant de gérer différentes catégories de personnel universitaire à l'aide de la programmation orientée objet (POO).

2. Catégories du personnel

Le système comprend trois catégories :

- Enseignant
- Agent administratif
- Technicien

3. Classe mère

La classe "Employe" est la classe mère abstraite.

Elle contient les attributs communs :

- Matricule
- Nom
- Prénom
- Salaire de base

4. Classes dérivées

Les classes suivantes héritent de "Employe" :

- "Enseignant"
- "AgentAdministratif"
- "Technicien"

Chaque catégorie possède une prime ou une indemnité spécifique.

5. Fonctionnalités

- Identifier et gérer les différentes catégories d'employés.
- Calculer le salaire total de chaque employé.
- Afficher les informations des employés.
- Stocker plusieurs catégories d'employés dans une collection.
- Utiliser le polymorphisme pour le calcul des salaires.

6. Technologies utilisées

- Langage : C++
- Programmation orientée objet
- Diagramme UML

7. Notions étudiées

- Héritage
- Polymorphisme
- Classes abstraites
- Méthodes virtuelles
- Redéfinition des méthodes
- Liaison dynamique

8. Compilation et exécution

Avec g++ :

g++ main.cpp -o personnel
./personnel

9. Conclusion

Ce projet permet de mettre en pratique les principaux concepts de la programmation orientée objet en C++, notamment l'héritage et le polymorphisme, dans un contexte de gestion du personnel universitaire.# TP_MIA3_FAST_NATI
