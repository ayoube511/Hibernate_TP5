# TP5 – Gestion des Réservations Avancée (JPA/Hibernate)

Implémentation de fonctionnalités avancées pour la recherche et la gestion des salles :
- Vérification de la disponibilité par créneau horaire
- Recherche multi-critères (nom, capacité, bâtiment, étage, équipement)
- Pagination des résultats avec navigation

## Objectifs du TP atteints

- Requête JPQL/Criteria pour trouver les salles disponibles (sans chevauchement de réservation)
- Recherche dynamique multi-critères via Criteria API
- Pagination simple avec comptage total et infos sur les pages
- Séparation propre des couches : Model → Repository → Service → Utilitaire Pagination
- Tests dans `App.java` avec initialisation de données réalistes

## Technologies utilisées

- Java 8+
- Maven
- JPA 2.2 + Hibernate 5.6
- H2 Database (in-memory)
- SLF4J pour les logs
- Criteria API pour les requêtes dynamiques

## Disponibilité par créneau 
<img width="1754" height="758" alt="image" src="https://github.com/user-attachments/assets/0ce786a6-c84e-4897-bca8-29abc86b7cc3" />
<img width="1745" height="683" alt="image" src="https://github.com/user-attachments/assets/8244a307-538b-4f2f-9f05-f9ba471d1c07" />

## Test de recherche multi-critères
<img width="1746" height="482" alt="image" src="https://github.com/user-attachments/assets/3ef5b76b-b734-4c0a-aa48-0a2417f2b36c" />
<img width="1753" height="451" alt="image" src="https://github.com/user-attachments/assets/01f5150d-1e18-47fb-acba-64a096261fd1" />
<img width="1738" height="465" alt="image" src="https://github.com/user-attachments/assets/9b5b81c0-bee1-4fdb-b5e4-909bed39f71a" />

## Test de pagination
<img width="1745" height="644" alt="image" src="https://github.com/user-attachments/assets/fa722aee-1dfd-4506-8104-fac5572cf17e" />
<img width="1729" height="423" alt="image" src="https://github.com/user-attachments/assets/6109a3be-1863-4961-86ad-ddf24f560c15" />
<img width="1706" height="409" alt="image" src="https://github.com/user-attachments/assets/73110976-b3e6-4feb-bb43-115385441869" />
<img width="1733" height="642" alt="image" src="https://github.com/user-attachments/assets/1a1fe375-7447-4a77-82ef-b7830c373236" />
<img width="1713" height="559" alt="image" src="https://github.com/user-attachments/assets/a7ce4c37-219b-4023-90f5-467556337d47" />
