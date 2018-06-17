Awesome Laravel
===============

> A curated list of awesome bookmarks, packages, tutorials, videos and other cool resources from the Laravel ecosystem currated by me.

## Table of Contents

- [Essentials](#essentials)
- [Packages](#packages)
- [Popular Packages](#popular-packages)
- [Development Setup](#development-setup)
- [Articles, Tutorials, Blogs, etc.](#articles-tutorials-blogs-etc)
- [Codebases for Reference](#codebases-for-reference)
- [Newsletters](#newsletters)
- [Hosted Development Tools](#hosted-development-tools)
- [Miscellaneous](#miscellaneous)
- [Topic Specific Tutorials](#topic-specific-tutorials)

## Essentials

* [Laravel](https://laravel.com)
* [Laravel Documentation](https://laravel.com/docs)
* [Laravel API Reference](https://laravel.com/api/master/)
* [Lumen](https://lumen.laravel.com)
* [Lumen Documentation](https://lumen.laravel.com/docs)
* [Laracasts](https://laracasts.com)
* [Laravel News](https://laravel-news.com)

## Packages

* [Packagist](https://packagist.org/)
* [Laragist](https://laragist.org)
* [Laravel Collective](https://laravelcollective.com/)
* [Packalyst](http://packalyst.com/)
* [Cartalyst](https://cartalyst.com/)
* [Spatie](https://spatie.be/en/opensource/laravel)

## Popular Packages

> This is a list of well-documented, tested packages that are frequently used in Laravel projects. If you're looking for an exhaustive list of PHP packages, then check out the Package Repositories mentioned above.

##### Developer Tools

* [Scaffold Interface](https://github.com/amranidev/scaffold-interface) - A Smart CRUD Generator For Laravel
* [IDE Helper](https://github.com/barryvdh/laravel-ide-helper) - Generates a helper file for IDE auto-completion
* [Laravel 5 Extended Generators](https://github.com/laracasts/Laravel-5-Generators-Extended) - Extends built-in file generators
* [Laravel API/Scaffold/CRUD Generator](http://labs.infyom.com/laravelgenerator/) - Generator for APIs, CRUD scaffolds etc.
* [Laravel TestTools](https://chrome.google.com/webstore/detail/laravel-testtools/ddieaepnbjhgcbddafciempnibnfnakl) - Chrome extension to generate Laravel integration tests while using your app.
* [Laravel API Documentation Generator](https://github.com/mpociot/laravel-apidoc-generator) - Automatically generate your API documentation from your existing Laravel routes.
* [Laravel Packager](https://github.com/Jeroen-G/Laravel-Packager) - A CLI tool for creating Laravel packages

##### Debugging & Profiling
* [Clockwork](https://github.com/itsgoingd/clockwork) - Integrates Clockwork Chrome extension for debugging and profiling apps
* [Debug Bar](https://github.com/barryvdh/laravel-debugbar) - Integrates PHP Debug Bar with Laravel
* [Laravel 5 Log Viewer](https://github.com/rap2hpoutre/laravel-log-viewer) - Log viewer
* [LogViewer](https://github.com/ARCANEDEV/LogViewer) - Provides a log viewer for Laravel 5
* [LERN](https://github.com/tylercd100/lern#lern-laravel-exception-recorder-and-notifier) - LERN is a Laravel 5 package that will record exceptions into a database and will send you a notification
* [Mail Preview](https://github.com/themsaid/laravel-mail-preview) - Preview sent mail in a web browser or mail client
* [Laravel Tracy](https://github.com/recca0120/laravel-tracy) - A Laravel Package to integrate Nette Tracy Debugger
* [Laravel API Tester](https://github.com/asvae/laravel-api-tester) - Postman-like tool with Laravel routes

##### Authentication & Authorisation

* [Bouncer](https://github.com/JosephSilber/bouncer) - Roles & Permissions
* [Entrust](https://github.com/Zizaco/entrust) - Role-based Permissions
* [JWT Auth](https://github.com/tymondesigns/jwt-auth) - JSON Web Token authentication for APIs
* [Laravel Permission](https://github.com/spatie/laravel-permission) - Associate users with roles and permissions
* [Defender](https://github.com/artesaos/defender) - Roles & Permissions
* [OAuth2 Server Laravel](https://github.com/lucadegasperi/oauth2-server-laravel) - OAuth 2.0 authorization server and resource server
* [Laravel Roles](https://github.com/romanbican/roles) - Roles And Permissions
* [Sentinel](https://github.com/cartalyst/sentinel) - Framework agnostic authentication & authorization system
* [Socialite](https://github.com/laravel/socialite) - OAuth authentication with Facebook, Google, Twitter etc.
* [Socialite Providers 2.0](http://socialiteproviders.github.io/) - 100+ social authentication providers for Socialite with Lumen support
* [Google2FA](https://github.com/antonioribeiro/google2fa) - Google Two-Factor Authentication Module
* [Laravel User Verification](https://github.com/jrean/laravel-user-verification) - Handle the user verification flow and validate email

##### Utilities

* [Artisan View](https://github.com/svenluijten/artisan-view) - Manage the views in Laravel projects via artisan.
* [Bootstrapper](https://github.com/patricktalmadge/bootstrapper/) - Set of classes to create Bootstrap 3 markup
* [Captcha](https://github.com/mewebstudio/captcha) - Captcha for Laravel 5 - An anti-bot image captcha system.
* [Datatable](https://github.com/Chumper/Datatable) - Server-side and client-side integration for jQuery Datatables plugin
* [Eloquent Sluggable](https://github.com/cviebrock/eloquent-sluggable) - Create slugs for Eloquent models
* [Eloquent Sortable](https://github.com/spatie/eloquent-sortable) - Sortable behaviour for Eloquent models
* [HTML](https://github.com/LaravelCollective/html) - Official HTML and Form Builders for Laravel
* [Hyn/multi-tenant](https://github.com/hyn/multi-tenant) - Flexible multi tenancy with secure separation of a.o. routes, assets and databases
* [Laravel 5 form builder](https://github.com/kristijanhusak/laravel-form-builder) - Form builder for Laravel 5 inspired by Symfony's form builder.
* [Intervention Image](https://github.com/Intervention/image) - Image handling library for creating, editing and composing images
* [Laravel Activitylog](https://github.com/spatie/laravel-activitylog) - Log activity inside your Laravel app
* [Laravel Blade Javascript](https://github.com/spatie/laravel-blade-javascript) - A Blade directive to export variables to JavaScript
* [Laravel Breadcrumbs](https://github.com/davejamesmiller/laravel-breadcrumbs) - Create and manage breadcrumbs
* [Laravel Collection Macros](https://github.com/spatie/laravel-collection-macros) - A set of handy collection macros
* [Laravel Cookie Consent](https://github.com/spatie/laravel-cookie-consent) - Make your Laravel app comply with the crazy EU cookie law
* [Laravel Datatables](https://github.com/yajra/laravel-datatables) - jQuery DataTables API for Laravel 4|5
* [Laravel Dot Env Generator](https://github.com/mathiasgrimm/laravel-dot-env-gen) - Generate .env.gen file based on the project source code
* [Laravel Excel](https://github.com/Maatwebsite/Laravel-Excel) - Import and export Excel and CSV files
* [Laravel Failed Job Monitor](https://github.com/spatie/laravel-failed-job-monitor) - Get notified when a queued job fails
* [Laravel GeoIP](https://github.com/Torann/laravel-geoip) - Determine the geographical location of website visitors based on their IP addresses
* [Laravel Glide](https://github.com/spatie/laravel-glide) - Easily convert images with Glide
* [Laravel Hashids](https://github.com/vinkla/laravel-hashids) - Generate unique, non-sequential ids using [Hashids](http://hashids.org/php/)
* [Laravel Markdown](https://github.com/GrahamCampbell/Laravel-Markdown) - CommonMark markdown parser
* [Laravel MediaLibrary](https://github.com/spatie/laravel-medialibrary) - Associate files with Eloquent models
* [Laravel Menu](https://github.com/spatie/laravel-menu) - Html menu generator for Laravel
* [Laravel Messenger](https://github.com/cmgmyr/laravel-messenger) - User messaging system
* [Laravel Moderation](https://github.com/hootlex/laravel-moderation) - A simple Moderation System for Laravel 5.* that allows you to Approve or Reject resources like posts, comments, users, etc.
* [Laravel Paginateroute](https://github.com/spatie/laravel-paginateroute) - Laravel router extension to easily use Laravel's paginator without the query string
* [Laravel Pjax](https://github.com/spatie/laravel-pjax) - A pjax middleware for Laravel 5
* [Laravel Responsecache](https://github.com/spatie/laravel-responsecache) - Speed up a Laravel app by caching the entire response
* [Laravel Snappy](https://github.com/barryvdh/laravel-snappy) - HTML to PDF generator using wkhtmltopdf
* [Laravel Stapler](https://github.com/CodeSleeve/laravel-stapler) - ORM-based file upload manager
* [Laravel url signer](https://github.com/spatie/laravel-url-signer) - Create and validate signed URLs with a limited lifetime
* [Laravel Tail](https://github.com/spatie/laravel-tail) - The missing tail command
* [Laravel Stats Tracker](https://github.com/antonioribeiro/tracker) - Gather information from requests to identify and store
* [Listify](https://github.com/lookitsatravis/listify) - Add sorting/ordering capabilities to any Eloquent model
* [noCAPTCHA](https://github.com/ARCANEDEV/noCAPTCHA) - Helper for Google's new noCAPTCHA (reCAPTCHA)
* [Purifier](https://github.com/mewebstudio/purifier) - HTMLPurifier for Laravel 5 - HTML filter
* [Revisionable](https://github.com/VentureCraft/revisionable) - Create a revision history for Eloquent models
* [SEOTools](https://github.com/artesaos/seotools) - Helpers for some common SEO techniques
* [Laravel Setting](https://github.com/anlutro/laravel-settings) - Persistent configuration settings that are stored in JSON files
* [Friendship](https://github.com/hootlex/laravel-friendships) - Friendship management system - send, receive, accept, deny friend requests
* [Teamwork](https://github.com/mpociot/teamwork) - User to team associations with an invite system
* [Validating](https://github.com/dwightwatson/validating) - Trait for validating Eloquent models
* [VAT Calculator](https://github.com/mpociot/vat-calculator) - Handle all the hard stuff related to EU MOSS vat regulations
* [Laravel Uuid](https://github.com/webpatser/laravel-uuid) - Laravel package to generate a UUID according to the RFC 4122 standard
* [Laravel Installer](https://github.com/RachidLaasri/LaravelInstaller) - Laravel package to allow users to install your application just by following the setup wizard, like WordPress
* [Laravel Test Factory Generator](https://github.com/mpociot/laravel-test-factory-helper) - Generate Laravel test factories from your existing models
* [Laravel-modules](https://github.com/nWidart/laravel-modules) - Easy Module Management In Laravel
* [Blade SVG](https://github.com/adamwathan/blade-svg) - Easily use SVG icons in your Blade templates
* [Google Places API Wrapper](https://github.com/SachinAgarwal1337/google-places-api) - Google Places API Wrapper for Laravel
* [QuickSand](https://github.com/tightenco/quicksand) - Easily schedule regular cleanup of old soft-deleted Eloquent data

##### Working with Javascript

* [Laroute](https://github.com/aaronlord/laroute) - Generate Laravel route URLs from JavaScript
* [PHP Vars to JavaScript Transformer](https://github.com/laracasts/PHP-Vars-To-Js-Transformer) - Pass server-side string/array/collection/whatever to JavaScript
* [Javascript Validation](https://github.com/proengsoft/laravel-jsvalidation) - Use validation rules, messages, FormRequest and validators to validate forms in client side without need to write any Javascript code

##### Databases, ORMs, Migrations & Seeding

* [Backup Manager](https://github.com/backup-manager/laravel) - Backup and restore databases from S3, Dropbox, SFTP etc.
* [Baum](https://github.com/etrepat/baum) - Nested Sets pattern implementation
* [ClosureTable](https://github.com/franzose/ClosureTable) - Closure table pattern implementation
* [Eloquence](https://github.com/kirkbushell/eloquence) - Extra features for Eloquent models
* [iSeed](https://github.com/orangehill/iseed) - Generate a new seed file from an existing database table
* [Laravel OCI8](https://github.com/yajra/laravel-oci8) - Oracle DB driver for Laravel 4|5 via OCI8
* [Laravel Backup](https://github.com/spatie/laravel-backup) - Backup your app
* [Laravel Doctrine](https://github.com/laravel-doctrine/orm) - Doctrine 2 ORM implementation
* [Laravel MongoDB](https://github.com/jenssegers/laravel-mongodb) - Eloquent model and query builder with support for MongoDB
* [Migrations Generator](https://github.com/Xethron/migrations-generator) - Generate migrations from an existing database
* [Sofa/Eloquence](https://github.com/jarektkaczyk/eloquence) - Extensions for the Eloquent ORM
* [Tenanti](https://github.com/orchestral/tenanti) - Multi-tenant database schema manager

##### Search

* [Algolia Search](https://github.com/algolia/algoliasearch-laravel) - Integrates the Algolia Search API to the Laravel Eloquent ORM
* [Elasticquent](https://github.com/elasticquent/Elasticquent) - Elasticsearch for Eloquent models
* [Plastic](https://github.com/sleimanx2/plastic) - Fluently mapping and searching Elasticsearch
* [Laravel Search](https://github.com/mmanos/laravel-search) - Unified API for Elasticsearch, Algolia, and ZendSearch
* [SearchIndex](https://github.com/spatie/searchindex) - Store and retrieve objects from Algolia or Elasticsearch
* [Searchable](https://github.com/nicolaslopezj/searchable) - Trait that adds a simple search function to Eloquent models
* [TNTSearch](https://github.com/teamtnt/tntsearch) - A fully featured full text search engine written in PHP
* [Scout MySQL Driver](https://github.com/damiantw/laravel-scout-mysql-driver) - A laravel scout mysql driver

##### APIs

* [ApiGuard](https://github.com/chrisbjr/api-guard) - Allow API authentication with API keys
* [Dingo API](https://github.com/dingo/api) - Multi-purpose toolkit for developing RESTful APIs
* [Laravel CORS](https://github.com/barryvdh/laravel-cors) - Add CORS (Cross-Origin Resource Sharing) headers support
* [Laravel Fractal](https://github.com/spatie/laravel-fractal) - Output complex, flexible, AJAX/RESTful data structures with Fractal in Laravel and Lumen

##### Tasks, Commands and Scheduling

* [Dispatcher](https://github.com/indatus/dispatcher) - Scheduler for Artisan commands
* [Elixir](https://github.com/laravel/elixir) - Node(NPM) package to run Gulp tasks that watch files, run tests, minify CSS, concatenate scripts etc.
* [Envoy](https://github.com/laravel/envoy) - SSH Task Runner

##### Payments

* [Cashier](https://github.com/laravel/cashier) - Subscription billing with Stripe
* [Omnipay for Laravel](https://github.com/ignited/laravel-omnipay) - Integrate the [Omnipay](https://github.com/thephpleague/omnipay) PHP library

##### Optimization

* [Intervention Image Cache](https://github.com/Intervention/imagecache) - Caching extension for the Intervention Image Class
* [Laravel HTMLMin](https://github.com/GrahamCampbell/Laravel-HTMLMin) - Blade/HTML/CSS/javascript minifier
* [Optimizing the performance of a Laravel application](https://blog.pusher.com/optimizing-performance-laravel/)

##### Localization

* [Language Files](https://github.com/caouecs/Laravel-lang) - Validation, Pagination and Reminders language lines in 37 languages
* [Laravel Localization](https://github.com/mcamara/laravel-localization) - Add i18n support via routes
* [Laravel Translatable](https://github.com/spatie/laravel-translatable) - Making Eloquent models translatable by storing translations as JSON.
* [Laravel Translatable](https://github.com/dimsav/laravel-translatable) - Retrieve and store translatable Eloquent model instances
* [Laravel Translator](https://github.com/vinkla/laravel-translator) - Translate Eloquent models into multiple languages
* [Laravel Date](https://github.com/jenssegers/date) - A library to help you work with dates in multiple languages, based on Carbon
* [Laravel Langman](https://github.com/themsaid/laravel-langman) - Manage language files from Artisan Console
* [Laravel Translation](https://github.com/waavi/translation) - Allow live edit/caching of translation entries, and localization of urls and Eloquent Model attributes.
* [Laravel Translations Loader](https://github.com/spatie/laravel-translation-loader) - Store Laravel Localizations in Database


## Development Setup

* [Homestead](https://laravel.com/docs/5.3/homestead) - Official Vagrant box for Laravel
  * [Getting Started with Laravel Homestead](https://scotch.io/tutorials/getting-started-with-laravel-homestead)
  * [Installation on macOS and Linux](https://laracasts.com/series/laravel-5-from-scratch/episodes/3)
  * [Installation on  Windows](http://blog.teamtreehouse.com/laravel-homestead-on-windows)
* [Valet](https://laravel.com/docs/5.3/valet/) - development environment for Mac minimalists
* [LaraDock](https://github.com/LaraDock/laradock) - Run Laravel on Docker (Like Homstead but for Docker instead of Vagrant).


## Articles, Tutorials, Blogs etc.

* [SitePoint](https://www.sitepoint.com/php/page/0/?filter[4047]=on)
* [Christopher Pitt](https://medium.com/laravel-4)
* [Culttt](http://culttt.com/tag/cribbb/)
* [Scotch](https://scotch.io/tag/laravel)
* [Fideloper](http://fideloper.com/tag/laravel)
* [Maxoffsky](https://maxoffsky.com/tag/laravel/)
* [KodeInfo](http://kodeinfo.com/main_category/laravel)
* [Taylor Otwell](http://taylorotwell.com/)
* [Digital Ocean](https://www.digitalocean.com/community/search?q=laravel&type=tutorials)
* [Matt Stauffer](https://mattstauffer.co/tags/laravel)
* [Creative Punch](http://creative-punch.net/articles/php-articles/laravel-tutorials/)
* [Ryan Tablada](http://ryantablada.com/tag/Laravel)
* [Mohammad Gufran](http://www.gufran.me/tag/Laravel/)
* [Adam Engebretson](http://blog.enge.me/4)
* [CodeHeaps](http://www.codeheaps.com/)
* [Laravel India](http://blog.laravel.in/)
* [Vegi Bit](http://vegibit.com/tag/laravel/)
* [WSnippets](http://wsnippets.com/category/laravel/)
* [Kirk Bushell](http://kirkbushell.me/)
* [Andrews Ang](http://blog.kongnir.com/category/laravel-2/)
* [DeveloPHP](http://www.develophp.org/category/web/laravel/)
* [Jason Lewis](http://jasonlewis.me/category/laravel)
* [Eric Barnes](https://ericlbarnes.com/tag/laravel/)
* [Jens Segers](https://jenssegers.com/)
* [Neon Tsunami](https://www.neontsunami.com/tags/laravel)
* [Stidges](http://blog.stidges.com/)
* [Scott Wilcox](https://dor.ky/tag/laravel/)
* [Clivern](http://clivern.com/tag/laravel/)
* [Code Gains](http://codegains.com/tag/laravel-2/)
* [Stillat](http://www.stillat.com/blog/category/programming/laravel/)
* [Easy Laravel Book Blog](http://www.easylaravelbook.com/blog/)
* [Bosnadev](https://bosnadev.com/tag/laravel-2/)
* [Vedovelli (PT-BR)](http://www.vedovelli.com.br/tag/laravel/)
* [CodeTutorial](https://www.codetutorial.io/tag/laravel/)
* [Ryan Chenkie](http://ryanchenkie.com/tag/laravel/)
* [Laravel Tips](https://laraveltips.wordpress.com/)
* [Codingo Tuts](https://tuts.codingo.me/category/web-development/laravel)
* [Antonio Carlos Ribeiro](https://antoniocarlosribeiro.com/technology)
* [Laravel Coding](http://laravelcoding.com/blog)
* [Styde](https://styde.net/cursos/) (ES)
* [Laravel Daily](http://laraveldaily.com/)
* [Freek Van der Herten](https://murze.be/tag/laravel/)
* [Tutsnare](http://tutsnare.com/category/tutorials/laravel/)
* [ForLaravel](https://forlaravel.com/)
* [Good Heads](http://goodheads.io/category/laravel/)
* [Ryan Stelmat](http://ryanstelmat.com/tag/laravel/)

## Codebases for Reference

* [92Five](https://github.com/chintanbanugaria/92five) - Project management application
* [Cachet](https://github.com/cachethq/Cachet) - Status page system for websites and APIs
* [Deployer](https://github.com/REBELinBLUE/deployer) - Application deployment system
* [Invoice Ninja](https://github.com/invoiceninja/invoiceninja) - Invoicing, expenses, & time-tracking application
* [Koel](https://github.com/phanan/koel) - Personal music streaming server
* [Laravel Tricks](https://github.com/CodepadME/laravel-tricks) - Source for the Laravel Tricks website
* [Laravel.io](https://github.com/laravelio/laravel.io) - Source for the Laravel.io Community Portal
* [Paperwork](https://github.com/twostairs/paperwork) - Note-taking & archiving application
* [PHPHub](https://github.com/summerblue/phphub) - Forum and source for the PHP & Laravel China community
* [Flarum](https://github.com/flarum/flarum) - Delightfully simple forum
* [Laramap](https://github.com/laramap/laramap.com) - Source of Laramap.com
* [Attendize](https://github.com/Attendize/Attendize) - Ticket selling and event management platform
* [Katana](https://github.com/themsaid/katana) - Static site/blog generator with markdown support
* [Antvel](https://github.com/ant-vel/antVel) - Ecommerce platform
* [Jigsaw](http://jigsaw.tighten.co) - Static site generator
* [Canvas](https://github.com/austintoddj/Canvas) - Minimal Blogging Application For Developers.
* [Vuedo](https://github.com/Vuedo/vuedo) - Vuedo is blog platform, built with Laravel and Vue.js
* [Screeenly](https://github.com/stefanzweifel/screeenly) - Create website screenshots through an API

## Newsletters

* [Laravel News](https://laravel-news.com/) ([archive](https://laravel-news.com/archive/))
* [Laravel Weekly](http://laravelweekly.com/)

## Hosted Development Tools

* [Laravel Shift](https://laravelshift.com/) - Automated upgrade tool for Laravel projects
* [Laravel Versions {x.y.z}](https://laraver.xyz/) - Monitor Laravel for updates
* [Laragen](http://makzumi.com/laragen/) - View generator
* [Laravel Schema Designer](http://laravelsd.com/) - Create, export and share database schemas
* [Laravel Database Designer](http://biodesignrealworld.github.io/LaravelDatabaseDesigner/) - Graphical tool to create database schemas
* [Laravel Model Generator Online](http://andressantibanez.com/laravel-model-generator/) - Make a laravel model online with migration code also generated
* [StyleCI](https://styleci.io) - PHP Coding Style Service


## Topic Specific Tutorials

* [Creating Custom Blade Directives](https://mattstauffer.co/blog/custom-conditionals-with-laravels-blade-directives)
* [Adding Tagging System in Your App](https://laravel-news.com/2015/10/how-to-add-tagging-to-your-laravel-app/)
* [Adding Email Verification](http://www.lubus.in/blog/adding-email-verification-in-laravel-5-3-app-149) 
* [Automatically generate a sitemap in Laravel](https://murze.be/2016/08/automatically-generate-a-sitemap-in-laravel/)
* [Masking IDs in URLs using hashids in Laravel](https://sampo.co.uk/blog/masking-ids-in-urls-using-hash-ids-in-laravel)
* [Advanced Laravel Eloquent usage](https://blog.pusher.com/advanced-laravel-eloquent-usage/)

