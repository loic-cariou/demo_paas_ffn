release: composer dump-autoload --no-dev --classmap-authoritative && php bin/console doctrine:migrations:migrate -n
web: heroku-php-nginx -C nginx_app.conf public/