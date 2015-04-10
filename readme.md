# Laravel Elixir

## Introduction

Laravel Elixir provides a clean, fluent API for defining basic Gulp tasks for your Laravel application. Elixir supports several common CSS and JavaScript pre-processors, and even testing tools.

If you've ever been confused about how to get started with Gulp and asset compliation, you will love Laravel Elixir!


## Official Documentation

Documentation for Elixir can be found on the [Laravel website](http://laravel.com/docs/elixir).

## Using Elixir Outside Laravel

Elixir is not only for using with Laravel. Since, Elixir is a wrapper around gulp, you can use it any
where you need to run gulp tasks. Elixir makes the process whole lot easier.

But since, Elixir is optimized for Laravel, you should change all the default configuration paths, so that
Elixir will know where your files are located. You can do this by creating a `elixir.json` file in your 
project's root directory where your `gulpfile.js` is located. Elixir is smart enough to read those 
configuration values from your `elixir.json` file. 

### License

Laravel Elixir is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
