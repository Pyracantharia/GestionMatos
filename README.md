# GestionMatos:
Le logiciel
GestionMatos désire se doter d’un logiciel lui permettant de gérer son activité d’interventions, et ce par la gestion 
•    Du matériel
•    De ses clients
•    Des interventions prévues et réalisées
Ce logiciel, qui a un accès sécurisé par un mot de passe, doit permettre 
•    La programmation d’interventions
•    Leur validation une fois le travail terminé
•    La levée d’alertes pour chaque matériel dont le MTBF depuis la dernière intervention va être atteint 
•    La consultation des interventions prévues et réalisées, filtrées par 
1.    Client
2.    Matériel 
3.    Type de matériel
4.    Site 
•    La consultation de l’ensemble du matériel
1.    Par type 
2.    Client
3.    Matériel 
4.    Site 
5.    Date de dernière intervention
6.    Durée restante avant fin du MTBF

Spécifications

Une intervention a:
•    Un numéro unique d'intervention
•    Une date planifiée
•    Un champ commentaire
•    Un matériel révisé

Un matériel a
•    Un numéro de série unique
•    Un client
•    Un MTBF
•    Une éventuelle date d’intervention
•    Un nom
•    Une description
•    Un type
•    Un site 

Ce logiciel sera réalisé en C# / Windows Form/ SQL Server
