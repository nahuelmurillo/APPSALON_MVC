Proyecto realizo en PHP 8, MVC, JS, SASS, GULP, MySQL

Pasos a seguir:
1-Instalando dependencias: 
En terminal: 
a- "npm install".
b- "npx gulp" o "npm run gulp" (para cambios en imagenes, archivos, js, css)

2-Instalar composer: 
En terminal: "composer init"

(Package name (<vendor>/<name>) [nahuel/app-salon_php_mvc_js_sass]: enter
Description []: PROYECTO PHP 8, MVC, JS, SASS, GULP, SQL,
Author [n to skip]: NAHUEL MURILLO
Minimum Stability []: 
Package Type (e.g. library, project, metapackage, composer-plugin) []: project
License []: 
Would you like to define your dependencies (require) interactively [yes]? no
Would you like to define your dev dependencies (require-dev) interactively [yes]? no
Add PSR-4 autoload mapping? Maps namespace "Nahuel\AppSalonPhpMvcJsSass" to the entered relative path. [src/, n to skip]: enter)

3-En composer.json: 

a-  "autoload": {
        "psr-4": {
            "MVC\\": "./",
            "Controllers\\": "./controllers",
            "Model\\": "./models"
        }

b-  En terminal: composer update

4- Arrancar el proyecto:
  Situarse en public
  En terminal : a- "cd public"
                b- "php -S localhost:3000"
                c- Seguir el vinculo (Alt+Click)

5-instalar phpMailer
en Terminal: composer require phpmailer/phpmailer
Luego: composer update

6- Si se arranca proyecto en servidor local PHP descomentar 
linea 22 y comentar linea 12 del archivo Router.php

