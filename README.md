# projet-lts

- symfony new my_project_directory --version="6.2.\*" --webapp
- removing webpack => composer remove webpack
- Creating DB & Entities:
    - php bin/console doctrine:database:create
    - php bin/console make:entity || symfony console make:user
- php bin/console make:migration
- php bin/console doctrine:migrations:migrate
- 
