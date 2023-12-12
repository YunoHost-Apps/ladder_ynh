Cette application télécharge un binaire depuis le dépot GitHub de Ladder et l'exécute sous la forme d'un service systemd. Il est rendu accessible grâce à un proxy inverse nginx.

Le binaire est téélchargé dans le dossier `__INSTALL_DIR__`

L'application utilise le "ruleset" par défaut : https://github.com/everywall/ladder-rules/blob/main/ruleset.yaml

Pour le changer, réinstaller l'application et changez l'URL lorsque c'est proposé.