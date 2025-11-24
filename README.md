1) Discovery Service : annuaire de tous les services 
Role: Permet aux services de se découvrir dynamiquement sans connaître leurs adresses IP à l’avance
Exemple: Eureka (Netflix)
2)Config server : configuration centralisée de tous les services
Role: evite la duplication, facilite la mise à jour des configurations
Exemple: Spring Cloud Config Server
3) Api Gateway : le seul point d'entrée pour toute l'application microservices.
Role: Routage des requêtes, filtrage, authentification, load balancing, sécurité...
Exemple : Spring Cloud Gateway

test for PR