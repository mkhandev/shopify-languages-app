## Install this Languages, Please follow the next steps

#. update .env file

add database connection
- DB_DATABASE=
- DB_USERNAME=
- DB_PASSWORD=

update shopify credentials
- SHOPIFY_APP_URL
- SHOPIFY_API_KEY
- SHOPIFY_API_SECRET

## composer install then add migration

- ** composer install
- ** php artisan migrate

## from shopify app settup

- ** add App URL. Example: https://salmon-present-newly.ngrok-free.app
- ** Allowed redirection URL. Example: https://salmon-present-newly.ngrok-free.app/authenticate

## From terminal go to directory cd app_extension

- ** npm install
- ** npm run dev