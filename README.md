## installation

- `git clone git@github.com/mouadh-dev/apijson.git`
- `cd apijson`
- change `.env.example` to `.env`
- Edit `.env` and set your database connection details
    - database connection details 
    - app url (include ports in dev) 
- `composer install`
- `php artisan key:generate`
-   `php artisan migrate`     

## notes 💡

### usage

#### URI

- GET `api/users` //index
- POST `api/users` //store
- GET|HEAD `api/users/{user}` //show
- PUT|PATCH `api/users/{user}` //update
- DELETE `api/users/{user}` //destroy
