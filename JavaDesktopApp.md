Stack technique :
- SqLite pour la base de données, plus léger et plus simple à prendre en main que H2
- Ebean ORM, plus léger qu'hibernate et support natif de SqLite (compatible également Kotlin et H2)
- Plugins -> SPI (Service Provider Interface) Java
- Thèmes / Front -> CSS + JavaFX (pour la personnalisation)
- Mises à jour -> pas de module spécialiser, une simple fonction qui compare le dernier tag github (requte http) et la version locale stockée dans une constante. Si un tag plus récent existe, il télécharge le fichier .jar et remplace celui déjà présent sur la machine avant de proposer un redémarrage de l'appli. Check automatique au lancement de l'appli et mettre un bouton pour check si un maj existe.
