# Création et supression de la BDD
`php app/console doctrine:database:drop --force`

`php app/console doctrine:database:create`

# Update des tables de la BDD ( à faire après chaque modification d'une entité)
`php app/console doctrine:schema:update --force`

# Chargement des fixtures dans la base (attention cela efface toutes les données de la BDD)
`php app/console doctrine:fixtures:load`

# Promotion de l'user user en admin
`php app/console fos:user:promote user ROLE_ADMIN`

# Installer les ressources (images)
`php app/console assets:install --symlink`

# Vider le cache en dev
`php app/console cache:clear`
