## P1908332 Daniel Ruan Project API
A Product CRUD Application API. It's included with JWT authentication and Swagger API format.

----

### Language:
1. PHP-8
1. Laravel-9

### API List:
##### Authentication Module
1. Register User API with Token
1. Login API with Token
1. Authenticated User Profile
1. Refresh Data
1. Logout

##### Product Module
1. Product List
1. Product List [Public]
1. Create Product
1. Edit Product
1. View Product
1. Delete Product

### How to Run:
1. Clone Project - 

```bash
git clone 
```
1. Go to the project drectory by `cd Laravel-Basic-CRUD-API` & Run the
2. Create `.env` file & Copy `.env.example` file to `.env` file
3. Create a database called - `laravel_basic_crud`.
4. Install composer packages - `composer install`.
5. Now migrate and seed database to complete whole project setup by running this-
``` bash
php artisan migrate:refresh --seed
```
6. Generate Swagger API
``` bash
php artisan l5-swagger:generate
```
7. Run the server -
``` bash
php artisan serve
```
8. Open Browser -
http://127.0.0.1:8000 & go to API Documentation -
http://127.0.0.1:8000/api/documentation
9. You'll see a Swagger Panel.


### Procedure
1. First Login with the given credential or any other user credential
1. Set bearer token to Swagger Header or Post Header as Authentication
1. Hit Any API, You can also hit any API, before authorization header data set to see the effects.


### Demo

### Test
1. Test with Postman - https://www.getpostman.com/collections/5642915d135f376b84af [Click to open with post man]
1. Test with Swagger.
1. Swagger Limitation: Image can not be uploaded throw Swagger, it can be uploaded throw Postman.
