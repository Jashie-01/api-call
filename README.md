Jasmine L. Santos

api-call project (applying Postman)

A project that uses or applies Postman to practice sending HTTP requests to an API. Trying the five methods, GET to fetch data, POST to add new data, PUT to fully update it based from IDs, PATCH to partially modify it, and DELETE to remove the data.

Requirements
 
- [Laravel Herd](https://herd.laravel.com/) (Windows)
- [Composer](https://getcomposer.org/)
- [Postman](https://www.postman.com/) or the Postman VS Code extension
 
Setup
 
1. Clone the repository
   ```bash
   git clone https://github.com/your-username/api-call.git
   ```
 
2. Move the project into your Herd sites folder
   ```
   C:\Users\<YourName>\Herd\api-call
   ```
 
3. Install dependencies
   ```bash
   cd api-call
   composer install
   ```
 
4. Set up your environment file
   ```bash
   copy .env.example .env
   php artisan key:generate
   ```
 
5. Run migrations
   ```bash
   php artisan migrate
   ```
 
6. Make sure Laravel Herd is running, then open your browser and go to:
   ```
   http://api-call.test/api/students
   ```

Access the Postman demo here 
Link:  https://drive.google.com/file/d/17MYpjNL_JO8FkjP4yYh9cmHRBhqPkNOO/view?usp=drive_link