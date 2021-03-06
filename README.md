<p align="center"><strong>Work in progress!</strong></p>

# Awesome Laravel ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

> A curated list of awesome bookmarks, packages, tutorials, videos and other cool resources from the Laravel ecosystem.

This repository contains a curated list of selected Laravel packages I, personally, use on a daily basis and I'm always coming back using them for a new project. Almost all of them come from my [extensive list](https://github.com/derheyne?tab=stars) of starred Github projects.

Yes, I know that there's already [a repository](https://github.com/chiraggude/awesome-laravel) for this type of awesome list, but (1) I don't want to scroll through thousands of packages I will probably never use to find the one I actually want to use (2) the list is horribly outdated, poorly maintained, and essential packages are missing, and (3) I don't like how it only links the packages. I know what I want, I just don't fancy clicking the link and scroll to find and then copy the composer command. Sometimes the composer command isn't even mentioned in the readme, so you'd have to go to their docs to find that.

So, how to use this list? Easy! The packages are split into their respective categories, like on every other [Awesome](https://github.com/sindresorhus/awesome) list. Every packages' name links to its Github repository. Click on "w" to open the packages' website. Click on "d" to open the packages' documentation. What follows is a short description of the package. Last but not least, I provide a command you can triple-click to copy it straight into your console to install the package.

## Table of Contents

* [Developer & Debugging Tools](#developer--debugging-tools)
  * Laravel Debugbar
  * Laravel IDE Helper
  * Tinkerwell
  * Ray
  * Clockwork
  * Laravel Telescope
  * Laravel Tail
* [Code Quality Tools](#code-quality-tools)
  * Larastan
  * PHP Insights
  * Enlightn
  * PHP Coding Standards Fixer
* [Database](#database)
  * Laravel MongoDB
  * Lighthouse
  * Eager Load Pivot Relations
* [Integration with JavaScript](#integration-with-javascript)
  * Alpine.js
  * Livewire
  * Inertia.js
* [Media Manipulation & Management](#media-manipulation--management)
  * Laravel Media Library
  * Intervention Image
* [Testing](#testing)
  * Pest
* [PhpStorm Plugins](#phpstorm-plugins)
  * Laravel IDEA
  * Alpine.js Support
  * Php Inspections (EA Extended)

## Developer & Debugging Tools

* **[Laravel Debugbar](https://github.com/barryvdh/laravel-debugbar)** *(12.8k stars, [d](https://github.com/barryvdh/laravel-debugbar#usage))* integrates and displays a debugbar at the bottom of your page with displays Laravel specific information about the current request.  

  ```
  composer require --dev barryvdh/laravel-debugbar
  ```
* **[Laravel IDE Helper](https://github.com/barryvdh/laravel-ide-helper)** *(11.4k stars, [d](https://github.com/barryvdh/laravel-ide-helper#usage))* generates accurate helper files that enables your IDE to provide accurate autocompletion, based on the files in your project.  

  ```
  composer require --dev barryvdh/laravel-ide-helper
  ```
* **[Tinkerwell](https://tinkerwell.app)** *(29.99 ???, [d](https://beyondco.de/docs/tinkerwell/getting-started/about))* is a simple yet powerful desktop application that allows you to run PHP code and quickly try out new ideas ??? all within the context of your application.
* **[Ray](https://github.com/spatie/ray)** *(~300 stars, [w](https://myray.app), [d](https://spatie.be/docs/ray))* helps you debugging to fix problems in Laravel apps faster.
  * 
  ```
  composer require spatie/laravel-ray
  ```
* **[Clockwork](https://github.com/itsgoingd/clockwork)** *(3.6k stars, [w](https://underground.works/clockwork/), [d](https://underground.works/clockwork/#documentation))* Clockwork gives you an insight into your application runtime - including request data, performance metrics, log entries, database queries, cache queries, redis commands, dispatched events, queued jobs, rendered views and more - for HTTP requests, commands, queue jobs and tests. Right in your browser.
  
  ```
  composer require itsgoingd/clockwork
  ```
* **[Laravel Telescope](https://github.com/laravel/telescope)** *(4k stars, [d](https://laravel.com/docs/8.x/telescope))* Telescope provides insight into the requests coming into your application, exceptions, log entries, database queries, queued jobs, mail, notifications, cache operations, scheduled tasks, variable dumps, and more.

  ```
  composer require laravel/telescope
  ```
* **[Laravel Tail](https://github.com/spatie/laravel-tail)** *(~600 stars, [d](https://github.com/spatie/laravel-tail#usage))* adds an artisan command to tail the application log. It supports daily and single logs on your local machine.

  ```
  composer require spatie/laravel-tail
  ```

## Code Quality Tools
* **[Larastan](https://github.com/nunomaduro/larastan)** *(2.6k stars)* focuses on finding errors in your code without actually running it. It catches whole classes of bugs even before you write tests for the code.  

  ```
  composer require --dev nunomaduro/larastan
  ```
* **[PHP Insights](https://github.com/nunomaduro/phpinsights)** *(4.1k stars, [w](https://phpinsights.com))* was carefully crafted to simplify the analysis of your code directly from your terminal, and is the perfect starting point to analyse the code quality of your PHP projects.  

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
* **[Eager Load Pivot Relations](https://github.com/ajcastro/eager-load-pivot-relations)** *(140 stars)* offers a simple method to eager load Laravel's pivot relations for a belongs to many relation.

  ```
  composer require ajcastro/eager-load-pivot-relations
  ```

## Integration with JavaScript

* **[Alpine.js](https://github.com/alpinejs/alpine)** *(17k stars, [w](https://alpinejs.dev), [d](https://alpinejs.dev/alpine-101))* is a rugged, minimal tool for composing behavior directly in your markup. Think of it like jQuery for the modern web. Plop in a script tag and get going.

  ```
  npm install alpinejs
  ```
* **[Livewire](https://github.com/livewire/livewire)** *(11.7k stars, [w](https://laravel-livewire.com), [d](https://laravel-livewire.com/docs))* is a full-stack framework for Laravel that takes the pain out of building dynamic UIs.

  ```
  composer require livewire/livewire
  ```

* **[Inertia.js](https://github.com/inertiajs/inertia)** (3.1k stars, [w](https://inertiajs.com), [d](https://inertiajs.com/server-side-setup)) lets you quickly build modern single-page React, Vue and Svelte apps using classic server-side routing and controllers.

  ```
  composer require inertiajs/inertia-laravel
  ```

## Media Manipulation & Management

* **[Laravel Media Library](https://github.com/spatie/laravel-medialibrary)** *(4.5k stars, [d](https://spatie.be/docs/laravel-medialibrary))* associates all sorts of files with Eloquent models. It provides a simple API to work with.

  ```
  composer require "spatie/laravel-medialibrary:^9.0.0"
  ```
* **[Intervention Image](https://github.com/Intervention/image)** *(11.9k stars, [d](http://image.intervention.io))* provides an easier and expressive way to create, edit, and compose images and supports currently the two most common image processing libraries GD Library and Imagick.

  ```
  composer require intervention/image
  ```

## Testing

* **[Pest](https://github.com/pestphp/pest)** *(2.6k stars, [w](https://pestphp.com), [d](https://pestphp.com/docs))* Pest is a Testing Framework with a focus on simplicity. It was carefully crafted to bring the joy of testing to PHP.

  ```
  composer require pestphp/pest-plugin-laravel --dev
  ```

## PhpStorm Plugins

* **[Laravel IDEA](https://laravel-idea.com)** *($3.9/m, [w](https://laravel-idea.com), [d](https://laravel-idea.com/docs))* provides advanced code generations and powerful autocompletions for almost anything that comes in native Laravel (and Livewire, Inertia and Nova) that's not being autocompleted by your IDE. If you don't have it, *pick it up*!
* **[Alpine.js Support](https://plugins.jetbrains.com/plugin/15251-alpine-js-support)** adds support for Alpine.js directives autocompletion.
* **[Php Inspections (EA Extended)](https://plugins.jetbrains.com/plugin/7622-php-inspections-ea-extended-/)** (1.2k stars, free & paid, [w](https://github.com/kalessil/phpinspectionsea), [d](https://github.com/kalessil/phpinspectionsea/blob/master/docs/getting-started.md)) is a static code analyser that works right in your IDE.
