# sail
alias sail='[ -f sail ] && sh sail || sh vendor/bin/sail'
# laravel breeze
composer require laravel/breeze --dev
sail artisan breeze:install api
sail artisan migrate:fresh --seed

https://www.youtube.com/watch?v=NY9yoqoN72w
