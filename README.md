# Laravel RESTful API for Posts

## Description
This project is a RESTful API built using Laravel that provides CRUD operations for managing posts. Each post consists of an image, title, and content. The API is designed to be used with frontend applications such as React, Vue, or any other framework that consumes RESTful APIs.

## Features
- Create, read, update, and delete posts
- Image upload and storage
- Pagination for listing posts
- Standardized API responses using API resources
- Validation for input data

## Technologies Used
- Laravel
- MySQL
- Laravel API Resources
- Postman (for testing API)

## Installation
### Prerequisites
- PHP >= 8.0
- Composer
- MySQL
- Laravel installed globally
- Storage link setup for serving images (`php artisan storage:link`)

### Steps to Install
1. Clone the repository:
   ```sh
   git clone https://github.com/[YourGitHub]/[YourRepository].git
   ```
2. Navigate to the project directory:
   ```sh
   cd [YourRepository]
   ```
3. Install dependencies:
   ```sh
   composer install
   ```
4. Copy the example environment file:
   ```sh
   cp .env.example .env
   ```
5. Configure your `.env` file with database credentials.
6. Generate the application key:
   ```sh
   php artisan key:generate
   ```
7. Run database migrations:
   ```sh
   php artisan migrate
   ```
8. Start the Laravel development server:
   ```sh
   php artisan serve
   ```

## API Endpoints
| Method | Endpoint        | Description               |
|--------|----------------|---------------------------|
| GET    | `/api/posts`   | Retrieve all posts       |
| GET    | `/api/posts/{id}` | Retrieve a single post |
| POST   | `/api/posts`   | Create a new post        |
| PUT    | `/api/posts/{id}` | Update an existing post |
| DELETE | `/api/posts/{id}` | Delete a post          |

## Project Source
This project was developed with the help of materials and guidance from SANTRIKODING. Many thanks to SANTRIKODING for the excellent materials and guidance. This project would not have been possible without the knowledge and resources provided.

https://santrikoding.com/tutorial-set/tutorial-restful-api-laravel-11
