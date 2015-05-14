# Awesome WordPress
A curated list of amazingly awesome WordPress resources, themes, plugins and shiny things. Inspired by awesome-php. 

- [Awesome WordPress](#awesome-wordpress)
	- [Core](#core)
	- [Themes](#themes)
		- [Framework] (#framework)
	- [Plugins](#plugins)
		- [Dev] (#dev-plugins)
		- [Media Gallery] (#media-gallery)
		- [Security] (#security)
		- [Move e Backup] (#move)
	- [Command Line] (#commandline)
	- [Resources](#resources)
		- [Websites](#websites)
		- [Books](#books)

## Core
* [WordPress on GitHub](https://github.com/WordPress/WordPress) - WordPress, Git-ified. Synced via SVN every 15 minutes, including branches and tags!
* [WordPress Coding Standards](https://make.wordpress.org/core/handbook/coding-standards/) - The purpose of the WordPress Coding Standards is to create a baseline for collaboration and review within various aspects of the WordPress open source project and community, from core code to themes to plugins.
* [The Customizer API](https://developer.wordpress.org/themes/advanced-topics/customizer-api/) - The Customizer is a framework for live-previewing any change to WordPress. It provides a simple and consistent interface for users to customize various aspects of their theme and their site, from colors and layouts to widgets, menus, and more. Themes and plugins alike can add custom options to the Customizer. The Customizer is the canonical way to add options to your theme.
* [Automated Testing](https://make.wordpress.org/core/handbook/automated-testing/) - This is an overview of running and writing tests for WordPress. Automated testing is running test cases where manual intervention is not required to run each one. This is usually in the form of writing test suites which have multiple test cases and a library and command line tool that runs the test suite or suites. The test suite execution is usually manual, from the developer choosing which suites on the command line to run, but this isn’t required. The process could be automated and looked over from time to time to ensure that when the code changed, no problems were introduced.

	
## Themes	

* [_S](https://github.com/automattic/_s) - Hi. I'm a starter theme called _s, or underscores, if you like. I'm a theme meant for hacking so don't use me as a Parent Theme. Instead try turning me into the next, most awesome, WordPress theme out there. That's what I'm here for.
* [Bones](http://themble.com/bones/) - An HTML5, Mobile-First starter theme for rapid WordPress development.
* [Sage](https://roots.io/sage/) - Sage is a WordPress starter theme based on HTML5 Boilerplate, gulp, Bower, and Bootstrap, that will help you make better themes.
* [WordPlate](https://github.com/wordplate/wordplate) - A WordPress boilerplate. This project is trying to simplify the way we're setting up a new WordPress project. Don't repeat yourself.

## Framework

* [WP MVC](http://wpmvc.org/) - WP MVC is an MVC framework that makes WordPress development faster, easier, and more elegant. It is a full-fledged framework with conventions that are similar to those of Ruby on Rails and CakePHP
	
## Plugins
#### Seo

* [Redirection](https://wordpress.org/plugins/redirection/) - Redirection is a WordPress plugin to manage 301 redirections and keep track of 404 errors without requiring knowledge of Apache .htaccess files. 

#### Dev Plugins
*Plugins can help in your workflow*

* [Posts 2 Posts](https://wordpress.org/plugins/posts-to-posts/) - Efficient many-to-many connections between posts, pages, custom post types, users. 
* [TGM Plugin Activation](tgmpluginactivation.com/) - TGM Plugin Activation is a PHP library that allows you to easily require or recommend plugins for your WordPress themes (and plugins). It allows your users to install and even automatically activate plugins in singular or bulk fashion using native WordPress classes, functions and interfaces. You can reference pre-packaged plugins, plugins from the WordPress Plugin Repository or even plugins hosted elsewhere on the internet. 
* [Revisr](https://wordpress.org/plugins/revisr/) - Revisr allows you to manage your WordPress website with a Git repository. A must have plugin for deploying and managing WordPress using Git repositories.
* [Debug Bar](http://wordpress.org/plugins/debug-bar/) - Adds a debug menu to the admin bar that shows query, cache, and other helpful debugging information.
* [Debug Bar Extender](http://wordpress.org/plugins/debug-bar-extender/) - Extends the debug-bar plugin with additional tabs to measure runtimes between checkpoints and lookup variable content. 
* [Custom Post Type Permalinks](https://wordpress.org/plugins/custom-post-type-permalinks/) - Custom Post Type Permalinks lets you edit the permalink structure of custom post type
* [WP Rollback](https://wordpress.org/plugins/wp-rollback/screenshots/) - Rollback (or forward) any WordPress.org plugin or theme like a boss. 
* [Members](https://wordpress.org/plugins/members/) - Members is a plugin that extends your control over your blog. It's a user, role, and content management plugin that was created to make WordPress a more powerful CMS.
The foundation of the plugin is its extensive role and capability management system. This is the backbone of all the current features and planned future features.
	
#### Media Gallery
*Images e media *

* [Enhanced Media Library](https://wordpress.org/plugins/enhanced-media-library/) - A better management for WordPress Media Library 
* [Imsanity](https://wordpress.org/plugins/imsanity/) - Imsanity automatically resizes huge image uploads. Are contributors uploading huge photos? Tired of manually scaling? Imsanity to the rescue! 
* [Resize Image After Upload](https://wordpress.org/plugins/resize-image-after-upload/) - Behind-the-scenes plugin to automatically resize images when uploaded, restricting size to within specified maximum h/w. Uses standard WP functions. 
* [Regenerate Thumbnails](https://wordpress.org/plugins/regenerate-thumbnails/) - Regenerate Thumbnails allows you to regenerate the thumbnails for your image attachments. This is very handy if you've changed any of your thumbnail dimensions (via Settings -> Media) after previously uploading images or have changed to a theme with different featured post image dimensions.

#### Ecommerce
[Easy Digital Downloads](https://wordpress.org/plugins/easy-digital-downloads/) - Easy Digital Downloads is a complete e-commerce solution for selling digital products in a light, performant, and easy to use plugin. Rather that attempting to provide every feature under the sun, Easy Digital Downloads makes selling digital simple and complete by providing just the features you need.
[WooCommerce](https://wordpress.org/plugins/woocommerce/) - Transform your WordPress website into a thoroughbred eCommerce store. Delivering enterprise-level quality and features, backed by a name you can trust. Say "hello" to the WooCommerce eCommerce plugin.

#### Security
*Antispam, prevent brute force, ecc*

* [GoodBye Captcha](https://wordpress.org/plugins/goodbye-captcha/) - An extremely powerful anti-spam plugin that blocks Spam-bots without annoying captcha images. 
* [Lockdown WP Admin](https://wordpress.org/plugins/lockdown-wp-admin/) - Lockdown WP Admin conceals the administration and login screen from intruders. It can hide WordPress Admin (/wp-admin/) and and login (/wp-login.php) 

#### Move e backup
*If you need to move your installation*

* [All-in-One WP Migration](https://wordpress.org/plugins/all-in-one-wp-migration/) - The plugin allows you to export your database, media files, plugins, and themes. You can apply unlimited find/replace operations on your database and the plugin will also fix any serialization problems that occur during find/replace operations.
* [Duplicator](https://wordpress.org/plugins/duplicator/) - Duplicate, clone, backup, move and transfer an entire site from one location to another. 
* [BackWPup](https://wordpress.org/plugins/backwpup/) - The backup plugin BackWPup Free can be used to save your complete installation including /wp-content/ and push them to an external Backup Service, like Dropbox, S3, FTP and many more, see list below. With a single backup .zip file you are able to easily restore an installation.

## Command line

* [WP-CLI](http://wp-cli.org/) - WP-CLI is a set of command-line tools for managing WordPress installations. You can update plugins, set up multisite installs and much more, without using a web browse.
* [WPScan](http://wpscan.org/) - WPScan is a black box WordPress vulnerability scanner.

## Resources

#### Classes
* [wp-custom-post-type-class](https://github.com/jjgrainger/wp-custom-post-type-class) - A PHP Class for creating Wordpress Custom Post Types easily 
* [wp-bootstrap-navwalker](https://github.com/twittem/wp-bootstrap-navwalker) -  A custom WordPress nav walker class to fully implement the Twitter Bootstrap 3.0+ navigation style in a custom theme using the WordPress built in menu manager.

#### Knowhow
* [10up Engineering Best Practices](http://10up.github.io/Engineering-Best-Practices/) - As a company, we strive to provide websites and components that yield a top-notch user experience. In order to improve efficiency, we need to standardize what we use and how we use it. Standardizing our tools, frameworks, libraries, style, version control, and even languages will allow us to understand better the inner workings of someone else’s project and produce better solutions ourselves.

## Websites

* [http://wordpress.stackexchange.com/](http://wordpress.stackexchange.com/) - WordPress Development Stack Exchange is a question and answer site for WordPress developers and administrators. It's 100% free, no registration required. 

* [Tom McFarlin](https://tommcfarlin.com/about/) - A Perspective on Professional WordPress Development
* [Mark on WordPress](https://markjaquith.wordpress.com/) - WordPress puts food on my table.
* [Otto on WordPress](http://ottopress.com/) - You have to use an Ottopress to get fresh squeezed Otto
* [Nacin](http://nacin.com/) - WordPress Lead Developer
* [Konstantin Kovshenin](http://kovshenin.com/) - WordPress, Automattic and Open Source


#### Resources List

* [Awesome WordPress by dropndot](https://github.com/dropndot/awesome-wordpress) - A curated list of Awesome WordPress Theme, Plugins and Framework development Resources and WordPress Communities. 
* [wpmudev.org](http://premium.wpmudev.org/blog/35-resources-for-kick-ass-wordpress-developers/) -35+ Resources to Become a Kick Ass WordPress Developer

## Books
