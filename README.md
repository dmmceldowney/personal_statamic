This is the personal website for David McEldowney, but built on Statamic instead of raw HTML/CSS *or* Winter CMS.

I chose Statamic because it's the most Laravel-like CMS and it's extremely easy to use.

---

## Requirements
- Docker desktop
- PHP & Composer

## Setup for local dev

- Run `composer install` to get all your PHP packages installed
- Run `npm i` to install node packages
- Now that you have Laravel installed via `composer`, you can run Laravel sail
    - `sail up --build`
- To create a user that can modify content in the CMS, you'll need to run the Statamic command
    - `php please make:user` to run it on your local PHP installation, OR
    - `docker exec -it dmmcel-stat-laravel-1 php please make:user` if you want to run it in Docker

---

MIT license. 👍
