# api
Create Ecommerce Restful API course

- Clone this repository
- Open and save `.env.eample as .env`
- Run `php artisan key:generate`
- Run `php artisan migrate`
- Run `composer update`
- Run `npm install`
- Run `php artisan passport:install`
- Run `php artisan db:seed`
- Run `php artisan serve`
- Go to your browser at `http://localhost:8000`

===================

# Techs
This repository uses:
- API routes
- API resources
- Eloquent relationship
- Resource transformers
- Collection paginationLinks
- Passport security (token based authentication)

====================

# UIRs
- List all products: `http://localhost:8000/api/products`;
- List product id = 4: `http://localhost:8000/api/products/4`;
- List product review for id = 4: `http://localhost:8000/api/products/4/reviews`;
