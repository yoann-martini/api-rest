# api-rest

API signifie Application Programming Interface.
REST signifie “Representational State Transfer”.

Les API REST imitent la façon dont le web lui-même marche dans les échanges entre un client et un serveur. Une API REST est :

- Sans état

- Cacheable (avec cache = mémoire)

- Orienté client-serveur

- Avec une interface uniforme

- Avec un système de couche

- Un code à la demande (optionnel)

Le principe du client-serveur définit les deux entités qui interagissent dans une API REST : un client et un serveur, les mêmes entités qui communiquent sur le web. Un client envoie une requête, et le serveur renvoie une réponse. Ce dernier doit avoir le plus d’informations possible sur le client, car il est important qu’ils soient capables de travailler indépendamment l’un de l’autre.

La relation typique client-serveur sur le web.
Le fait d’être “sans état” signifie que le serveur n’a aucune idée de l’état du client entre deux requêtes. Du point de vue du serveur, chaque requête est une entité distincte des autres. Ensuite, le cache, pour les API REST,  met en jeu le même principe que pour le reste d’Internet : un client doit être capable de garder en mémoire des informations sans avoir constamment besoin de demander tout au serveur. Ce sont les concepts de base à comprendre sur REST.

Les réponses du serveur pour les API REST peuvent être délivrées dans de multiples formats. JSON (JavaScript Object Notation) est souvent utilisé, mais XML, CSV, ou même RSS sont aussi valables.
