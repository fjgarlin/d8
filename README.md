# Drupal 8 playground

Start docker containers and get into the cli one:
`docker-compose up -d`
`docker-compose exec cli composer install`
`docker-compose exec cli bash`

If you want to install as new site:
`drush site-install`

If you want to use existing config:
`drush si --existing-config`

If you want to update core:
`composer update drupal/core drupal/core-recommended --with-dependencies`
