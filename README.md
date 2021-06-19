<p align="center"><strong>Work in progress!</strong></p>

# Awesome Laravel ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

> A curated list of awesome bookmarks, packages, tutorials, videos and other cool resources from the Laravel ecosystem.

This repository contains a curated list of selected Laravel packages I, personally, use on a daily basis and I'm always coming back using them for a new project. Almost all of them come from my [extensive list](https://github.com/derheyne?tab=stars) of starred Github projects.

Yes, I know that there's already [a repository](https://github.com/chiraggude/awesome-laravel) for this type of awesome list, but (1) I don't want to scroll through thousands of packages I will probably never use to find the one I actually want to use (2) the list is horribly outdated, poorly maintained, and essential packages are missing and (3) I don't like how it only links the packages. I know what I want, I just don't fancy clicking the link and scrolling to find and then copy the composer command.

So, how to use this list? Easy! The packages are split into their respective categories, like on every other [Awesome](https://github.com/sindresorhus/awesome) list. Every packages' name links to its Github repository. Click on "w" to open the packages' website. Click on "d" to open the packages' documentation. What follows is a short description of the package. Last but not least, I provide a command you can triple-click to copy it straight into your console to require the package.

## Table of Contents

* [Developer & Debugging Tools](#developer--debugging-tools)
  * Laravel Debugbar
  * Laravel IDE Helper
* [Code Quality Tools](#code-quality-tools)
  * Larastan
  * PHP Insights
  * Enlightn
  * PHP Coding Standards Fixer
* [Database](#database)
  * Laravel MongoDB
  * Lighthouse
* [PhpStorm Plugins](#phpstorm-plugins)
  * Laravel IDEA

## Developer & Debugging Tools

* **[Laravel Debugbar](https://github.com/barryvdh/laravel-debugbar)** *(12.8k stars, [d](https://github.com/barryvdh/laravel-debugbar#usage))* integrates and displays a debugbar at the bottom of your page with displays Laravel specific information about the current request.  

  ```
  composer require --dev barryvdh/laravel-debugbar
  ```
* **[Laravel IDE Helper](https://github.com/barryvdh/laravel-ide-helper)** *(11.4k stars, [d](https://github.com/barryvdh/laravel-ide-helper#usage))* generates accurate helper files that enables your IDE to provide accurate autocompletion, based on the files in your project.  

  ```
  composer require --dev barryvdh/laravel-ide-helper
  ```

## Code Quality Tools
* **[Larastan](https://github.com/nunomaduro/larastan)** *(2.6k stars)* focuses on finding errors in your code without actually running it. It catches whole classes of bugs even before you write tests for the code.  

  ```
  composer require --dev nunomaduro/larastan
  ```
* **[PHP Insights](https://github.com/nunomaduro/phpinsights)** *(4.1k stars, [w](https://phpinsights.com))* was carefully crafted to simplify the analysis of your code directly from your terminal, and is the perfect starting point to analyze the code quality of your PHP projects.  

   ```
   composer require --dev nunomaduro/phpinsights
   ```
* **[Enlightn](https://github.com/enlightn/enlightn)** *(~500 stars, freemium, [w](https://www.laravel-enlightn.com), [d](https://www.laravel-enlightn.com/docs/))* will "review" your code and server configurations, and give you actionable recommendations on improving performance, security and reliability.  

  ```
  composer require enlightn/enlightn
  ```
* **[PHP Coding Standards Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)** *(10.2k stars, [w](https://cs.symfony.com), [d](https://cs.symfony.com/doc/usage.html))* tool fixes your code to follow standards; whether you want to follow PHP coding standards as defined in the PSR-1, PSR-2, etc., or other community driven ones like the Symfony one. You can also define your (team's) style through configuration.  
  ```
  composer require --dev friendsofphp/php-cs-fixer
  ```

## Database

* **[Laravel MongoDB](https://github.com/jenssegers/laravel-mongodb)** *(5.6k stars, [d](https://github.com/jenssegers/laravel-mongodb#configuration))* adds functionalities to the Eloquent model and Query builder for MongoDB, using the original Laravel API.

  ```
  composer require jenssegers/mongodb
  ```
* **[Lighthouse](https://github.com/nuwave/lighthouse)** *(2.4k stars, [w](https://lighthouse-php.com), [d](https://lighthouse-php.com/master/getting-started/installation.html))* is a GraphQL framework that integrates with your Laravel application. It takes the best ideas of both and combines them to solve common tasks with ease and offer flexibility when you need it.

  ```
  composer require nuwave/lighthouse
  ```

## PhpStorm Plugins

* **[Laravel IDEA](https://laravel-idea.com)** *($3.9/m, [w](https://laravel-idea.com), [d](https://laravel-idea.com/docs))* provides advanced code generations and powerful autocompletions for almost anything that comes in native Laravel (and Livewire, Inertia and Nova) that's not being autocompleted by your IDE. If you don't have it, *pick it up*!
