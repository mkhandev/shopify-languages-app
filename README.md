## Install shopify Languages App, Please follow the next steps

### Update .env file

### add database connection
- DB_DATABASE=
- DB_USERNAME=
- DB_PASSWORD=

### Update shopify credentials
- SHOPIFY_APP_URL
- SHOPIFY_API_KEY
- SHOPIFY_API_SECRET

### Run composer install then add migration command from terminal

- **composer install**
- **php artisan migrate**

## From admin shopify app settup

- add App URL. Example: https://salmon-present-newly.ngrok-free.app
- Allowed redirection URL. Example: https://salmon-present-newly.ngrok-free.app/authenticate

## From terminal go to directory cd app_extension

- npm install
- npm run dev

### After successfully install app, You must need to enable Languages app from theme app embeds settings
Then you can see laguages app from store front bottom right corner