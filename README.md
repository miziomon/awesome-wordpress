# Awesome WordPress
A curated list of amazingly awesome WordPress resources, themes, plugins and shiny things. 

Inspired by [awesome](https://github.com/sindresorhus/awesome) and [awesome-php](https://github.com/ziadoz/awesome-php).

- [Awesome WordPress](#awesome-wordpress)
	- [Core](#core)
	- [Themes and Framework](#themes-and-framework)
	- [Plugins](#plugins)
		- [Featured Plugins] (#featured-plugins)
		- [SEO] (#seo)
		- [Dev] (#dev-plugins)
		- [Installer and Generators] (#installer-and-generators)
		- [Media Gallery] (#media-gallery)
		- [Performance] (#performance)
		- [E-commerce] (#e-commerce)
		- [Security and Managment] (#security-and-management)
		- [Move and Backup] (#move-and-backup)
	- [Commandline] (#commandline)
	- [Resources](#resources)
		- [Classes](#classes)
		- [Theme Customizer](#theme-customizer)
		- [Websites](#websites)
		- [Books](#books)
	- [Contributing](#contributing)

## Core

* [WordPress on GitHub](https://github.com/WordPress/WordPress) - WordPress, Git-ified. Synced via SVN every 15 minutes, including branches and tags!
* [WordPress Coding Standards](https://make.wordpress.org/core/handbook/coding-standards/) - The purpose of the WordPress Coding Standards is to create a baseline for collaboration and review within various aspects of the WordPress open source project and community, from core code to themes to plugins.
* [The Customizer API](https://developer.wordpress.org/themes/advanced-topics/customizer-api/) - The Customizer is a framework for live-previewing any change to WordPress. It provides a simple and consistent interface for users to customize various aspects of their theme and their site, from colors and layouts to widgets, menus, and more. Themes and plugins alike can add custom options to the Customizer. The Customizer is the canonical way to add options to your theme.
* [Automated Testing](https://make.wordpress.org/core/handbook/automated-testing/) - This is an overview of running and writing tests for WordPress. Automated testing is running test cases where manual intervention is not required to run each one. This is usually in the form of writing test suites which have multiple test cases and a library and command line tool that runs the test suite or suites. The test suite execution is usually manual, from the developer choosing which suites on the command line to run, but this isn’t required. The process could be automated and looked over from time to time to ensure that when the code changed, no problems were introduced.

	
## Themes and Framework

* [_S](https://github.com/automattic/_s) - Hi. I'm a starter theme called _s, or underscores, if you like. I'm a theme meant for hacking so don't use me as a Parent Theme. Instead try turning me into the next, most awesome, WordPress theme out there. That's what I'm here for.
* [Bones](http://themble.com/bones/) - An HTML5, Mobile-First starter theme for rapid WordPress development.
* [Sage](https://roots.io/sage/) - Sage is a WordPress starter theme based on HTML5 Boilerplate, gulp, Bower, and Bootstrap, that will help you make better themes.
* [WordPlate](https://github.com/wordplate/wordplate) - A WordPress boilerplate. This project is trying to simplify the way we're setting up a new WordPress project. Don't repeat yourself.
* [Sprig](http://sprigwp.com/) - Build WordPress themes quickly with Twig
* [WP MVC](http://wpmvc.org/) - WP MVC is an MVC framework that makes WordPress development faster, easier, and more elegant. It is a full-fledged framework with conventions that are similar to those of Ruby on Rails and CakePHP
* [CherryFramework](https://github.com/CherryFramework/CherryFramework) - Fully responsive design, easy install, steady updates, great number of shortcodes and widgets, integration of Bootstrap functions. All brought to you by Cherry Framework for straightforward experience in website design
* [Gantry Framework](https://github.com/gantry/gantry5) - Next Generation Theme Framework. Gantry was born when the RocketTheme development team wanted to consolidate our extensive set of custom Joomla and WordPress template functionality into a simple, easy to use framework
* [Runway Framework](https://github.com/parallelus/Runway-Framework) - A better way to create WordPress themes. Runway was built for creating WordPress themes and it encompasses both of the classic meanings of "theme framework" as defined by the WordPress developers. But Runway is much more than just a theme framework, Runway is a Theme Development Environment.
* [Kirki](http://kirki.org/) - Kirki is not a framework. It's a Toolkit allowing WordPress developers to use the Customizer and take advantage of its advanced features and flexibility by abstracting the code and making it easier for everyone to create beautiful and meaningful user experiences.
* [HTML5 Blank](http://html5blank.com/) - The HTML5 WordPress boilerplate theme.
	
## Plugins

### Featured Plugins
*Plugins that have a chance to make it into WordPress core*

* [Shortcake](https://wordpress.org/plugins/shortcode-ui/) - Used alongside add_shortcode, Shortcake supplies a user-friendly interface for adding a shortcode to a post, and viewing and editing it from within the content editor.
* [Responsive Images](https://wordpress.org/plugins/ricg-responsive-images/) - This plugin works by including all available image sizes for each image upload. Whenever WordPress outputs the image through the media uploader, or whenever a featured image is generated, those sizes will be included in the image tag via the srcset attribute.

#### SEO

* [Redirection](https://wordpress.org/plugins/redirection/) - Redirection is a WordPress plugin to manage 301 redirections and keep track of 404 errors without requiring knowledge of Apache .htaccess files. 
* [Yoast SEO](https://wordpress.org/plugins/wordpress-seo/) - Improve your WordPress SEO: Write better content and have a fully optimized WordPress site using Yoast SEO plugin. 

#### Dev Plugins
*Plugins can help in your workflow*

* [Theme Check](https://wordpress.org/plugins/theme-check/) - he theme check plugin is an easy way to test your theme and make sure it's up to spec with the latest theme review standards. With it, you can run all the same automated testing tools on your theme that WordPress.org uses for theme submissions.
* [Posts 2 Posts](https://wordpress.org/plugins/posts-to-posts/) - Efficient many-to-many connections between posts, pages, custom post types, users. 
* [TGM Plugin Activation](tgmpluginactivation.com/) - TGM Plugin Activation is a PHP library that allows you to easily require or recommend plugins for your WordPress themes (and plugins). It allows your users to install and even automatically activate plugins in singular or bulk fashion using native WordPress classes, functions and interfaces. You can reference pre-packaged plugins, plugins from the WordPress Plugin Repository or even plugins hosted elsewhere on the internet. 
* [Revisr](https://wordpress.org/plugins/revisr/) - Revisr allows you to manage your WordPress website with a Git repository. A must have plugin for deploying and managing WordPress using Git repositories.
* [Debug Bar](http://wordpress.org/plugins/debug-bar/) - Adds a debug menu to the admin bar that shows query, cache, and other helpful debugging information.
* [Debug Bar Extender](http://wordpress.org/plugins/debug-bar-extender/) - Extends the debug-bar plugin with additional tabs to measure runtimes between checkpoints and lookup variable content. 
* [Custom Post Type Permalinks](https://wordpress.org/plugins/custom-post-type-permalinks/) - Custom Post Type Permalinks lets you edit the permalink structure of custom post type
* [WP Rollback](https://wordpress.org/plugins/wp-rollback/screenshots/) - Rollback (or forward) any WordPress.org plugin or theme like a boss. 
* [Members](https://wordpress.org/plugins/members/) - Members is a plugin that extends your control over your blog. It's a user, role, and content management plugin that was created to make WordPress a more powerful CMS.
The foundation of the plugin is its extensive role and capability management system. This is the backbone of all the current features and planned future features.
* [GitHub Updater](https://github.com/afragen/github-updater) - A simple plugin to enable automatic updates to your GitHub, Bitbucket, or GitLab hosted WordPress plugins and themes. It also allows for the remote installation of plugins or themes.
* [Rewrite Rules Inspector](https://wordpress.org/plugins/rewrite-rules-inspector/) - A straightforward WordPress admin tool for inspecting your rewrite rules. View a listing of all your rewrite rules, see which rewrite rules match a given URL (and the priorites they match in), or filter by different sources of rewrite rules. Perform a soft flush of your rewrite rules to regenerate them.
* [CMB2](https://wordpress.org/plugins/cmb2/) - CMB2 is a metabox, custom fields, and forms library for WordPress that will blow your mind. 
* [Ship](http://ship.getherbert.com/) - Tag a release on GitHub and have it automatically shipped to the official WordPress.org plugin SVN
	
#### Installer and Generators

* [WP Quick Install](http://wp-quick-install.com/) - WordPress installation could be long: downloading, decompressing, uploading, plugins and themes installation. WP Quick Install will take care all of this things. Simply upload this tiny script where you want to install WordPress
* [GenerateWP](http://generatewp.com/) - The easiest and the fastest way to create custom and high quality code for your WordPress project using the latest WordPress coding standards and API's.
* [FakerPress](https://wordpress.org/plugins/fakerpress/) - FakerPress is a clean way to generate fake and dummy content to your WordPress, great for developers who need testing 

#### Media Gallery
*Images e media *

* [Enhanced Media Library](https://wordpress.org/plugins/enhanced-media-library/) - A better management for WordPress Media Library 
* [Imsanity](https://wordpress.org/plugins/imsanity/) - Imsanity automatically resizes huge image uploads. Are contributors uploading huge photos? Tired of manually scaling? Imsanity to the rescue! 
* [Resize Image After Upload](https://wordpress.org/plugins/resize-image-after-upload/) - Behind-the-scenes plugin to automatically resize images when uploaded, restricting size to within specified maximum h/w. Uses standard WP functions. 
* [Regenerate Thumbnails](https://wordpress.org/plugins/regenerate-thumbnails/) - Regenerate Thumbnails allows you to regenerate the thumbnails for your image attachments. This is very handy if you've changed any of your thumbnail dimensions (via Settings -> Media) after previously uploading images or have changed to a theme with different featured post image dimensions.
* [Enable Media Replace](https://wordpress.org/plugins/enable-media-replace/) - Enables replacing attachment files by simply uploading a new file in the media library edit view.

#### Performance

* [RICG Responsive Images](https://wordpress.org/plugins/ricg-responsive-images/) - Bringing automatic default responsive images to WordPress.

#### E-commerce

* [Easy Digital Downloads](https://wordpress.org/plugins/easy-digital-downloads/) - Easy Digital Downloads is a complete e-commerce solution for selling digital products in a light, performant, and easy to use plugin. Rather that attempting to provide every feature under the sun, Easy Digital Downloads makes selling digital simple and complete by providing just the features you need.
* [WooCommerce](https://wordpress.org/plugins/woocommerce/) - Transform your WordPress website into a thoroughbred eCommerce store. Delivering enterprise-level quality and features, backed by a name you can trust. Say "hello" to the WooCommerce eCommerce plugin.

#### Security and Management
*Antispam, prevent brute force, ecc*

* [GoodBye Captcha](https://wordpress.org/plugins/goodbye-captcha/) - An extremely powerful anti-spam plugin that blocks Spam-bots without annoying captcha images. 
* [Lockdown WP Admin](https://wordpress.org/plugins/lockdown-wp-admin/) - Lockdown WP Admin conceals the administration and login screen from intruders. It can hide WordPress Admin (/wp-admin/) and and login (/wp-login.php) * [MainWP](https://mainwp.com/) - Self-hosted open source manager for maintaining your WordPress sites from one location.

#### Move e backup
*If you need to move your installation*

* [All-in-One WP Migration](https://wordpress.org/plugins/all-in-one-wp-migration/) - The plugin allows you to export your database, media files, plugins, and themes. You can apply unlimited find/replace operations on your database and the plugin will also fix any serialization problems that occur during find/replace operations.
* [Duplicator](https://wordpress.org/plugins/duplicator/) - Duplicate, clone, backup, move and transfer an entire site from one location to another. 
* [BackWPup](https://wordpress.org/plugins/backwpup/) - The backup plugin BackWPup Free can be used to save your complete installation including /wp-content/ and push them to an external Backup Service, like Dropbox, S3, FTP and many more, see list below. With a single backup .zip file you are able to easily restore an installation.

## Commandline

* [WP-CLI](http://wp-cli.org/) - WP-CLI is a set of command-line tools for managing WordPress installations. You can update plugins, set up multisite installs and much more, without using a web browse.
* [WPScan](http://wpscan.org/) - WPScan is a black box WordPress vulnerability scanner.

## Resources

#### Theme Customizer
* [Multi Image Control] (https://github.com/lucatume/multi-image-control) - A Theme customizer control allowing selection and sorting of multiple images.

#### Classes
* [wp-custom-post-type-class](https://github.com/jjgrainger/wp-custom-post-type-class) - A PHP Class for creating Wordpress Custom Post Types easily 
* [wp-bootstrap-navwalker](https://github.com/twittem/wp-bootstrap-navwalker) -  A custom WordPress nav walker class to fully implement the Twitter Bootstrap 3.0+ navigation style in a custom theme using the WordPress built in menu manager.

#### Knowhow
* [10up Engineering Best Practices](http://10up.github.io/Engineering-Best-Practices/) - As a company, we strive to provide websites and components that yield a top-notch user experience. In order to improve efficiency, we need to standardize what we use and how we use it. Standardizing our tools, frameworks, libraries, style, version control, and even languages will allow us to understand better the inner workings of someone else’s project and produce better solutions ourselves.

## Websites

* [Stackexchang](http://wordpress.stackexchange.com/) - WordPress Development Stack Exchange is a question and answer site for WordPress developers and administrators. It's 100% free, no registration required.
* [Tom McFarlin](https://tommcfarlin.com/about/) - A Perspective on Professional WordPress Development
* [Mark on WordPress](https://markjaquith.wordpress.com/) - WordPress puts food on my table.
* [Otto on WordPress](http://ottopress.com/) - You have to use an Ottopress to get fresh squeezed Otto
* [Nacin](http://nacin.com/) - WordPress Lead Developer
* [Konstantin Kovshenin](http://kovshenin.com/) - WordPress, Automattic and Open Source
* [Automattic](http://automattic.com/) - We are the people behind WordPress.com, which serves more than 15.8 billion pages a month, as well as a host of other popular services, such as Akismet, Jetpack, and VaultPress.  We are strong believers in Open Source, and the vast majority of our work is available under licenses like the GPL.

#### Resources List

* [Awesome WordPress by dropndot](https://github.com/dropndot/awesome-wordpress) - A curated list of Awesome WordPress Theme, Plugins and Framework development Resources and WordPress Communities. 
* [wpmudev.org](http://premium.wpmudev.org/blog/35-resources-for-kick-ass-wordpress-developers/) -35+ Resources to Become a Kick Ass WordPress Developer
* [Toolbox of the Smart WordPress Developer](http://code.tutsplus.com/tutorials/toolbox-of-the-smart-wordpress-developer-series-introduction--cms-23663) - Is the core of WordPress enough for you? No, probably not. Almost all the time, we install WordPress plugins and themes to help build our websites. And that's all right, because WordPress isn't meant to be a one-size-fits-all solution. We do need extra functionality and design elements, and we meet our needs with plugins and themes... and more.

## Books

* [Digging Into WordPress](https://digwp.com/book/) - There is much to learn about the World’s most popular publishing platform. From your first steps of learning about WordPress all the way through securing, customizing, and maintaining your site into the future, this book is packed with truly practical information.
* [The Story of WordPress](https://github.com/WordPress/book) - The history and development of WordPress. The book is currently in version 1, having been written by Siobhan McKeown, edited by Krista Stevens, and with helpful pull requests from members of the community. 

## Contributing

We welcome any contributions to the this awesome list! Please send us a pull request.

* For contribution, [fork the project](https://github.com/miziomon/awesome-wordpress/fork)
* To report a broken link or want to remove one, [use issues](https://github.com/miziomon/awesome-wordpress/issues)
