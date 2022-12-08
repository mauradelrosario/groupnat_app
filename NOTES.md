# Notes

### SETUP
- composer require --dev symfony/maker-bundle
- composer require --dev symfony/profiler-pack
- composer require orm

### Introduction SECURITY: users, permissions, custom voters, ways to authenticate
Authentication & Authorization : users, login form remember me cookies, password, api keys
Authenticate => Login forms, API token authentication, social authentication with OAuth, SSO's, LDAP

- composer require security 
- composer require symfony/security-bundle
- composer require form validator 

    ### Generating User class 
    - php bin/console make:user
    - php bin/console make:migration
    - php bin/console doctrine:migrations:migrate


    ### Setup database
    - php bin/console doctrine:database:create
    - php bin/console make:migration 
    - php bin/console doctrine:migrations:migrate

    ### Create Controller
    - php bin/console make:controller
     
    ### Data fixtures: pré remplir la bdd
    - composer require --dev orm-fixtures

    ### Registration
    - php bin/console make:registration-form