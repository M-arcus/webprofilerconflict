## Setup 

`composer install`

`docker compose up -d`

`symfony console system:install --basic-setup`

`symfony server:start -d`

Then set `APP_ENV=dev` in the `.env`

Then try `symfony console cache:clear`
