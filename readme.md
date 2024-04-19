## First
Clone the repository. Do the following steps to get it up and running:
1. Set your db configuration in .env and key generate
2. `composer install`
3. `npm install`
4. `php artisan migrate`
5. `npm run watch` *(To start React frontend)
6. `php artisan serve` *(To start Laravel backend api)

You can access the application at http://127.0.0.1:8000/

***For react production build** - execute `npm run prod`

## API  

 | Routes | Method | Description | 
 |:----------|:-------------:|:------| 
 | api/login | POST | Login route. | 
 | api/logout | GET | User Logout. | 
 | api/register | POST | User registeration. | 
 | api/check-auth | GET | Authenticate user. | 
 | api/profile | GET | Get user profile. | 
 | api/profile/update | POST | Update user profile. | 
 | api/posts?page= | GET | List all posts. (Returns 10 items per page with pagination data )| 
 | api/posts/:id | GET | Get post by id. | 
 | api/posts | POST | Create new post. | 
 | api/posts/likes | POST | Like post by id. | 
 | api/posts/:id | PUT | Edit post by id. | 
 | *api/posts/:id | DELETE | Delete post by id. |

login : admin@admin.com
password:password
