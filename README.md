# php-artisan-failed
Fix the error "Failed to listen on 127.0.0.1:8000"

Use `php -S localhost:8000 -t public` instead of `php artisan serve`.
> I don't know why, but it works :smile:

![Fix artisan serve](recording.gif)