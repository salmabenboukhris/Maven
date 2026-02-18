



###  Test 1.1 – Initialisation du projet

Cette capture montre l’exécution initiale de l’application.  
<img width="1919" height="1015" alt="test1" src="https://github.com/user-attachments/assets/56fcb818-0aa4-4002-942f-5c1bfa8154b6" />


###  Test 1.2 – Lecture des données

Cette capture présente le résultat de la requête JPQL permettant de récupérer tous les produits enregistrés.  
On observe l’affichage de la liste complète des produits insérés dans la base.
<img width="1919" height="1019" alt="test1 2" src="https://github.com/user-attachments/assets/f7a05fd6-0822-4c6e-9471-6a94148165ea" />

###  Test 1.3 – Recherche d’un produit par identifiant

Cette capture illustre la recherche d’un produit spécifique.  
Le produit correspondant à l’ID recherché est affiché dans la console.
<img width="1919" height="1015" alt="test1 3" src="https://github.com/user-attachments/assets/3e7d7bc3-174c-435a-9f4d-ce2a0da2795f" />

### Test Update – Modification du prix d’un produit

Cette capture montre l’exécution de la méthode de mise à jour.  
Hibernate génère automatiquement la requête SQL `UPDATE` et le nouveau prix du produit est enregistré avec succès.
<img width="1917" height="988" alt="prix modifier" src="https://github.com/user-attachments/assets/d4f98c22-8330-4479-81c9-8e7856e6b35b" />


###  Test Delete – Suppression d’un produit

Cette capture représente l’exécution de la méthode de suppression.  
Le produit sélectionné est supprimé de la base de données et Hibernate exécute la requête `DELETE` correspondante.
<img width="1918" height="972" alt="produit modifier" src="https://github.com/user-attachments/assets/eb90684d-0ace-4b81-b6ef-b6a929f5796c" />

###  Test Recherche par plage de prix

Cette capture montre l’utilisation d’une requête JPQL avec paramètres (`BETWEEN :min AND :max`) afin de récupérer les produits dont le prix se situe dans une plage donnée.  
Seuls les produits correspondant aux critères sont affichés.
<img width="1221" height="975" alt="rechercheparprix" src="https://github.com/user-attachments/assets/af6e61b4-4c46-4f13-975f-22ebbe8e1a26" />


