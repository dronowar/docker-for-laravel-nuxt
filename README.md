# Docker for laravel + nuxt + postgres

# Instructions dev:
<ul>
<li>npx create-nuxt-app client</li>
<li>replace client/package.json > "dev": "export NODE_OPTIONS=--openssl-legacy-provider && nuxt",</li>
<li>mkdir docker/postgres/data</li>
<li>docker-compose up -d --build</li>
<li>docker-compose exec php-fpm bash</li>
<li>composer create-project laravel/laravel example-app</li>
<li>cd example-app</li>
<li>mv * ../ (+ .files)</li>
<li>rm -rf example-app</li>
</ul>
