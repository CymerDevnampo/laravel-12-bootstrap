# 1

## 2

### 3

#### 4

##### 5

###### 6

## How did I Install that

Make sure you have the latest version of laravel 12

To check the version run this command

laravel --version

## Update Laravel Version

composer global require laravel/installer

## Run

laravel new Cymer-laravel-12-bootstrap

choose "NONE" for staterkit

choose your own database

choose your testing tool

if npm install and migration were asked typed "NO"

## Installation

composer require Laravel/ui

chp artisan ui bootstrap –auth

If controller shows that is exist, type "YES"

npm install

php artisan migrate

## Running the application

run "COMPOSER RUN DEV" instead of "PHP ARTISAN SERVE" to compile both "NPM RUN DEV" and "PHP ARTISAN SERVE"

Visit

- [http://127.0.0.1:8000/](http://127.0.0.1:8000/).

you will see the design is not okay

## Debugging

goto "WELCOME.BLADE.PHP"

Comment out the ifelse and endif just leave the style

it should look like this.

{{-- @if (file_exists(public_path('build/manifest.json')) || file_exists(public_path('hot')))
            @vite(['resources/css/app.css', 'resources/js/app.js'])
@else --}}
<style>
</style>
{{-- @endif --}}

Then your good togo.

for questions kindly contact me on this 
- [Cymer Denampo](https://www.facebook.com/Lord.Cymer).
