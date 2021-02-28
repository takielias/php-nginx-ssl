# A Boilerplate for PHP, nginx with Let’s Encrypt on docker-compose 

## Installation
1. [Install docker-compose](https://docs.docker.com/compose/install/#install-compose).

2. Clone this repository: `git clone https://github.com/takielias/php-nginx-ssl.git .`

3. Modify configuration:
- Add domains and email addresses to init-letsencrypt.sh
- Replace all occurrences of chilro.com with primary domain (the first one you added to init-letsencrypt.sh) in data/nginx/app.conf

4. Run the init script:

        ./init-letsencrypt.sh

5. Run the server:

        docker-compose up


### Thanks