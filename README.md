## Reproduction repo

Steps to deploy:

- `git clone https://github.com/kamilst96/filament-issue-repo.git`
- `cd filament-issue-repo`
- `cp .env.example .env`
- `composer install`
- `php artisan key:generate`
- Add database credentials to .env
- `php artisan migrate:fresh --seed`
- `php artisan serve`
- View `http://localhost:{port}/admin` in the browser

**User:** admin@localhost

**Password:** password
