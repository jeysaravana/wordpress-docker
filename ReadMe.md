# Setup WordPress on Local

- Copy `wp-config-sample.php` to `wordpress` as `/wp-config.php`
- Setup port number and username in `.env`
- Run `docker-compose up`
- Visit http://localhost:7000 (7000 is a default port setup in .env) to see the site in action
- Visit http://localhost:7001 to access phpmyadmin. (username and password set in .env uname: wpuser pass: wppass )