# TP1 : JDBC
# Lab1 : 
  Cours : Java Avancé – Bases de Données, Réseau, Concurrency et Interfaces
  # Objectifs :
  
Se connecter à MySQL via JDBC.
Créer et manipuler une table SQL depuis Java.
Utiliser Statement et PreparedStatement.
Produire des statistiques avec GROUP BY, MAX, SUM, ORDER BY.

# ✅ Résultat attendu
Un programme Java qui :
crée la table DevData
insère des données de test
affiche 4 statistiques SQL

# <img width="841" height="611" alt="image" src="https://github.com/user-attachments/assets/c34ef593-5f1e-4187-a19a-a9650a0124b4" />
# <img width="1864" height="717" alt="image" src="https://github.com/user-attachments/assets/cb965793-0c3f-4592-a4bd-e911cafc6bfa" />
# <img width="1888" height="742" alt="image" src="https://github.com/user-attachments/assets/670130d0-b778-4489-b699-1aa00f2463d2" />

# Lab2:
# Gestion des Machines et Employés : JDBC en Couches
# Objectifs
Comprendre l’architecture en couches : DAO ↔ Service ↔ Présentation
Mettre en œuvre une connexion JDBC thread-safe (via Singleton)
Manipuler les entités Java Employe et Machine avec relation objet
Implémenter un DAO générique CRUD
Utiliser PreparedStatement + try-with-resources (sécurité & fermeture automatique)
Écrire des services prenant des objets en paramètre (logique métier)
Tester via main() en créant les objets via constructeurs

# ✅ Résultat final attendu
Un mini-projet Java structuré en :
util      → connexion (ex: DataSourceSingleton)  
entities  → classes métier (Employe, Machine)  
dao       → accès données (DAO générique + impl. spécifiques)  
service   → logique métier  
app       → tests (main)

# <img width="1572" height="672" alt="image" src="https://github.com/user-attachments/assets/d05fda55-2590-45dc-97a7-122ee23c1817" />
# <img width="1662" height="599" alt="image" src="https://github.com/user-attachments/assets/d4128fed-db6a-4574-95b0-c802749876e4" />
# <img width="1109" height="773" alt="image" src="https://github.com/user-attachments/assets/2b887ee7-5336-42c4-a325-06b474e1f358" />
# <img width="1104" height="674" alt="image" src="https://github.com/user-attachments/assets/8f2378d8-a866-45fd-847a-52e91f07ac79" />









