# Laravel Vue SPA with Hot Reloading

This is a boilerplate for single page application using Vue.js and Laravel.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

You need Composer https://getcomposer.org/download/, 
PHP https://www.php.net/downloads.php, 
and Vue.js ```npm install --global vue-cli```

### Installing

1. Clone this repository
```
git clone https://github.com/Pogorzelska/LaravelVueHotReloading.git
```

2. Install libriaries from composer.lock
```
composer install
```

3. Edit your .env file and set up your database connections. 
```
DB_DATABASE=database-name
DB_USERNAME=your-username (default: root)
DB_PASSWORD=your password (there is no default password set)
```

4. Set your hosts. 
5. Install libraries from package-lock.json
```
npm install
```
6. Run migrations
```
php artisan migrate
```

### Usage
Your application with hot reloading shoud be working on your local domail set in hosts file if you run this command:

```
npm run hot
```



