<p align="center"><strong>Work in progress!</strong></p>

# Awesome Laravel ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

> A curated list of awesome bookmarks, packages, tutorials, videos and other cool resources from the Laravel ecosystem.

This repository contains all the Laravel packages I, personally, use on a daily basis and I'm always coming back using them for a new project.

Yes, I know that there's already [a repository](https://github.com/chiraggude/awesome-laravel) for this type of awesome list but I don't want to scroll through thousands of packages I will probably never use to find the one I want to use.

## Table of Contents

* [Developer & Debugging Tools](#developer--debugging-tools)
  * Laravel Debugbar
  * Laravel IDE Helper
* [Code Quality Tools](#code-quality-tools)
  * Larastan
  * PHP Insights
  * Enlightn
  * PHP Coding Standards Fixer
* [PhpStorm Plugins](#phpstorm-plugins)
  * Laravel IDEA

## Developer & Debugging Tools

* **[Laravel Debugbar](https://github.com/barryvdh/laravel-debugbar)** *(12.8k stars)* integrates and displays a debugbar at the bottom of your page with displays Laravel specific information about the current request.  

  ```
  composer require --dev barryvdh/laravel-debugbar
  ```
* **[Laravel IDE Helper](https://github.com/barryvdh/laravel-ide-helper)** *(11.4k stars)* generates accurate helper files that enables your IDE to provide accurate autocompletion, based on the files in your project.  

  ```
  composer require --dev barryvdh/laravel-ide-helper
  ```

## Code Quality Tools
* **[Larastan](https://github.com/nunomaduro/larastan)** *(2.6k stars)* focuses on finding errors in your code without actually running it. It catches whole classes of bugs even before you write tests for the code.  

  ```
  composer require --dev nunomaduro/larastan
  ```
* **[PHP Insights](https://github.com/nunomaduro/phpinsights)** *(4.1k stars)* was carefully crafted to simplify the analysis of your code directly from your terminal, and is the perfect starting point to analyze the code quality of your PHP projects.  

   ```
   composer require --dev nunomaduro/phpinsights
   ```
* **[Enlightn](https://github.com/enlightn/enlightn)** *(~500 stars, freemium)* will "review" your code and server configurations, and give you actionable recommendations on improving performance, security and reliability.  

  ```
  composer require enlightn/enlightn
  ```
* **[PHP Coding Standards Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)** *(10.2k stars)* tool fixes your code to follow standards; whether you want to follow PHP coding standards as defined in the PSR-1, PSR-2, etc., or other community driven ones like the Symfony one. You can also define your (team's) style through configuration.  
  ```
  composer require --dev friendsofphp/php-cs-fixer
  ```

## PhpStorm Plugins

* **[Laravel IDEA](https://laravel-idea.com)** *($3.9/m)* provides advanced code generations and powerful autocompletions for almost anything that comes in native Laravel (and Livewire, Inertia and Nova) that's not being autocompleted by your IDE. If you don't have it, *pick it up*!
