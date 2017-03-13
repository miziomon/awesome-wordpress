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
		- [Images and Media Gallery] (#images-and-media-gallery)
		- [Performance] (#performance)
		- [E-commerce] (#e-commerce)
		- [Security and Management] (#security-and-management)
		- [Forms and modules] (#forms-and-modules)
		- [Widget] (#widget)		
		- [Move and Backup] (#move-and-backup)
		- [Marketing] (#marketing)
		- [Facebook Ads] (#facebook-ads)
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
* [WordPlate](https://wordplate.github.io/) - WordPlate tries to simplify the fuzziness around WordPress development.
* [Sprig](http://sprigwp.com/) - Build WordPress themes quickly with Twig
* [WP MVC](http://wpmvc.org/) - WP MVC is an MVC framework that makes WordPress development faster, easier, and more elegant. It is a full-fledged framework with conventions that are similar to those of Ruby on Rails and CakePHP
* [CherryFramework](https://github.com/CherryFramework/CherryFramework) - Fully responsive design, easy install, steady updates, great number of shortcodes and widgets, integration of Bootstrap functions. All brought to you by Cherry Framework for straightforward experience in website design
* [Gantry Framework](https://github.com/gantry/gantry5) - Next Generation Theme Framework. Gantry was born when the RocketTheme development team wanted to consolidate our extensive set of custom Joomla and WordPress template functionality into a simple, easy to use framework
* [Runway Framework](https://github.com/parallelus/Runway-Framework) - A better way to create WordPress themes. Runway was built for creating WordPress themes and it encompasses both of the classic meanings of "theme framework" as defined by the WordPress developers. But Runway is much more than just a theme framework, Runway is a Theme Development Environment.
* [Kirki](http://kirki.org/) - Kirki is not a framework. It's a Toolkit allowing WordPress developers to use the Customizer and take advantage of its advanced features and flexibility by abstracting the code and making it easier for everyone to create beautiful and meaningful user experiences.
* [HTML5 Blank](http://html5blank.com/) - The HTML5 WordPress boilerplate theme.
* [Odin WP](http://wpod.in/) - Base-theme developed by WordPress Brasil Group, to help on agile development of themes for WordPress.
* [Landing Pages](https://wordpress.org/support/plugin/landing-pages/) - Framework for building single page presentations with split testing capabilities.	

## Plugins

### Featured Plugins
*Plugins that have a chance to make it into WordPress core*

* [Shortcake](https://wordpress.org/plugins/shortcode-ui/) - Used alongside add_shortcode, Shortcake supplies a user-friendly interface for adding a shortcode to a post, and viewing and editing it from within the content editor.
* [Responsive Images](https://wordpress.org/plugins/ricg-responsive-images/) - This plugin works by including all available image sizes for each image upload. Whenever WordPress outputs the image through the media uploader, or whenever a featured image is generated, those sizes will be included in the image tag via the srcset attribute.

#### SEO

* [Redirection](https://wordpress.org/plugins/redirection/) - Redirection is a WordPress plugin to manage 301 redirections and keep track of 404 errors without requiring knowledge of Apache .htaccess files. 
* [Yoast SEO](https://wordpress.org/plugins/wordpress-seo/) - Improve your WordPress SEO: Write better content and have a fully optimized WordPress site using Yoast SEO plugin. 
* [Broken Link Checker](https://wordpress.org/plugins/broken-link-checker/) - This plugin will monitor your blog looking for broken links and let you know if any are found.

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
* [Members](https://wordpress.org/plugins/members/) - Members is a plugin that extends your control over your blog. It's a user, role, and content management plugin that was created to make WordPress a more powerful CMS. The foundation of the plugin is its extensive role and capability management system. This is the backbone of all the current features and planned future features.
* [GitHub Updater](https://github.com/afragen/github-updater) - A simple plugin to enable automatic updates to your GitHub, Bitbucket, or GitLab hosted WordPress plugins and themes. It also allows for the remote installation of plugins or themes.
* [Rewrite Rules Inspector](https://wordpress.org/plugins/rewrite-rules-inspector/) - A straightforward WordPress admin tool for inspecting your rewrite rules. View a listing of all your rewrite rules, see which rewrite rules match a given URL (and the priorites they match in), or filter by different sources of rewrite rules. Perform a soft flush of your rewrite rules to regenerate them.
* [CMB2](https://wordpress.org/plugins/cmb2/) - CMB2 is a metabox, custom fields, and forms library for WordPress that will blow your mind. 
* [Ship](http://ship.getherbert.com/) - Tag a release on GitHub and have it automatically shipped to the official WordPress.org plugin SVN
* [Simply Show Hooks](https://wordpress.org/plugins/simply-show-hooks/) - Simply Show Hooks helps theme and plugin developers to quickly see where all the action and filter hooks are on any WordPress page.
* [Timber](https://github.com/timber/timber) - Add [Twig](http://twig.sensiolabs.org/doc/templates.html) templating capabilities to your theme and keep your template code separate from your PHP.
* [Child Theme Check](https://wordpress.org/plugins/child-theme-check/) - Warns you about outdated template files in your child theme and shows a diff view of the changes between parent and child theme template. 
* [One-Click Child Theme](https://it.wordpress.org/plugins/one-click-child-theme/) - Adds a Theme option to any active theme allowing you to make a child theme. 
	
#### Installer and Generators

* [WP Quick Install](http://wp-quick-install.com/) - WordPress installation could be long: downloading, decompressing, uploading, plugins and themes installation. WP Quick Install will take care all of this things. Simply upload this tiny script where you want to install WordPress
* [GenerateWP](http://generatewp.com/) - The easiest and the fastest way to create custom and high quality code for your WordPress project using the latest WordPress coding standards and API's.
* [FakerPress](https://wordpress.org/plugins/fakerpress/) - FakerPress is a clean way to generate fake and dummy content to your WordPress, great for developers who need testing 
* [wppm](https://github.com/lucasbhjf/wppm) - Wordpress Plugin Manager - a new and easy way to install plugins using nodejs

#### Images and Media Gallery
*All about media items management*

* [Enhanced Media Library](https://wordpress.org/plugins/enhanced-media-library/) - A better management for WordPress Media Library 
* [Imsanity](https://wordpress.org/plugins/imsanity/) - Imsanity automatically resizes huge image uploads. Are contributors uploading huge photos? Tired of manually scaling? Imsanity to the rescue! 
* [Resize Image After Upload](https://wordpress.org/plugins/resize-image-after-upload/) - Behind-the-scenes plugin to automatically resize images when uploaded, restricting size to within specified maximum h/w. Uses standard WP functions. 
* [Regenerate Thumbnails](https://wordpress.org/plugins/regenerate-thumbnails/) - Regenerate Thumbnails allows you to regenerate the thumbnails for your image attachments. This is very handy if you've changed any of your thumbnail dimensions (via Settings -> Media) after previously uploading images or have changed to a theme with different featured post image dimensions.
* [Enable Media Replace](https://wordpress.org/plugins/enable-media-replace/) - Enables replacing attachment files by simply uploading a new file in the media library edit view.
* [Multiple Post Thumbnails](https://wordpress.org/plugins/multiple-post-thumbnails/) - Adds multiple post thumbnails to a post type. If you've ever wanted more than one Featured Image on a post, this plugin is for you. 
* [Media from FTP](https://it.wordpress.org/plugins/media-from-ftp/) - Register to media library from files that have been uploaded by FTP. 

#### Performance

* [WP-Optimize](https://it.wordpress.org/plugins/wp-optimize/) - Simple but effective plugin allows you to extensively clean up your WordPress database and optimize it without doing manual queries. 
* [P3](https://it.wordpress.org/plugins/p3-profiler/) - This plugin creates a profile of your WordPress site's plugins' performance by measuring their impact on your site's load time.  Often times, WordPress sites load slowly because of poorly configured plugins or because there are so many of them. By using the P3 plugin, you can narrow down anything causing slowness on your site.

#### E-commerce

* [Easy Digital Downloads](https://wordpress.org/plugins/easy-digital-downloads/) - Easy Digital Downloads is a complete e-commerce solution for selling digital products in a light, performant, and easy to use plugin. Rather that attempting to provide every feature under the sun, Easy Digital Downloads makes selling digital simple and complete by providing just the features you need.
* [WooCommerce](https://wordpress.org/plugins/woocommerce/) - Transform your WordPress website into a thoroughbred eCommerce store. Delivering enterprise-level quality and features, backed by a name you can trust. Say "hello" to the WooCommerce eCommerce plugin.

#### Security and Management
*Antispam, prevent brute force, ecc*

* [GoodBye Captcha](https://wordpress.org/plugins/goodbye-captcha/) - An extremely powerful anti-spam plugin that blocks Spam-bots without annoying captcha images. 
* [Lockdown WP Admin](https://wordpress.org/plugins/lockdown-wp-admin/) - Lockdown WP Admin conceals the administration and login screen from intruders. It can hide WordPress Admin (/wp-admin/) and and login (/wp-login.php)
* [MainWP](https://mainwp.com/) - Self-hosted open source manager for maintaining your WordPress sites from one location.
* [Captcha on Login](https://wordpress.org/plugins/captcha-on-login) - Protect your blog from login brute force attacks adding a captcha on login page of your site 
* [Stealth Login Page](https://www.wordpress.org/plugins/stealth-login-page/) - Protect your dashboard without editing the .htaccess file -- the FIRST one that completely blocks remote bot login requests. 
* [Antispam Bee](https://wordpress.org/plugins/antispam-bee/) - Say Goodbye to comment spam on your WorddPress blog or website. Antispam Bee blocks spam comments and trackbacks effectively and without captchas. It is free of charge, ad-free and compliant with European data privacy standards.
* [Stream](https://wordpress.org/plugins/stream/) - Stream is the easiest and safest way to track content changes happening to your WordPress site and then view them in beautifully organized detail. 
* [Simple Login Log](https://wordpress.org/plugins/simple-login-log/) - This plugin keeps a log of WordPress user logins. Offers user and date filtering, and export features.
* [iThemes Security](https://wordpress.org/plugins/better-wp-security/) - Take the guesswork out of WordPress security. iThemes Security offers 30+ ways to lock down WordPress in an easy-to-use WordPress security plugin.
* [Easy Updates Manager](https://wordpress.org/plugins/stops-core-theme-and-plugin-updates/) - Easy Updates Manager is a light yet powerful plugin which enables you to manage all types of updates on your single site install or in WordPress Multisite. With loads of settings making endless possibilities for configuration, Easy Updates Manager is an obvious choice for anyone wanting to take control of their websites updates.

#### Forms and modules

* [Caldera Forms](https://it.wordpress.org/plugins/caldera-forms/) - A diffrent kind of WordPress form builder. With an intuitive drag and drop interface -– based on a responsive grid -- and a wide range of add-ons, it’s never been easier to create forms for your WordPress site that look great on any device, thanks to Caldera Forms. 
* [Ninja Forms](https://it.wordpress.org/plugins/ninja-forms/) - Ninja Forms is the easiest way to build any form you need for your WordPress website. No longer mess with code or worry about made-up limitations. Create the form you want, when you want with a simple drag and drop interface provided by the very powerful Ninja Forms framework.

#### Widget

* [Widget Options](https://it.wordpress.org/plugins/widget-options/) - Get Better Control over your Widgets. Easily show or hide WordPress widgets on specified pages & devices and/or assign custom alignment. 
* [Widget Logic](https://it.wordpress.org/plugins/widget-logic/) - This plugin gives every widget an extra control field called "Widget logic" that lets you control the pages that the widget will appear on. The text field lets you use WP's Conditional Tags, or any general PHP code.
* [Widget Output Cache](https://it.wordpress.org/plugins/widget-output-cache/) - Use PHP output buffering to extract widget output and store it into WordPress transients for faster retrieval. It also adds a checkbox to widget controls to exclude it from being cached.


#### Move and backup
*If you need to move your installation*

* [All-in-One WP Migration](https://wordpress.org/plugins/all-in-one-wp-migration/) - The plugin allows you to export your database, media files, plugins, and themes. You can apply unlimited find/replace operations on your database and the plugin will also fix any serialization problems that occur during find/replace operations.
* [Duplicator](https://wordpress.org/plugins/duplicator/) - Duplicate, clone, backup, move and transfer an entire site from one location to another. 
* [UpdraftPlus Backup and Restoration](https://wordpress.org/plugins/updraftplus/) - UpdraftPlus simplifies backups (and restoration). Backup into the cloud (Amazon S3 (or compatible), Dropbox, Google Drive, Rackspace Cloud, DreamObjects, FTP, Openstack Swift, UpdraftPlus Vault and email) and restore with a single click. Backups of files and database can have separate schedules. 
* [BackWPup](https://wordpress.org/plugins/backwpup/) - The backup plugin BackWPup Free can be used to save your complete installation including /wp-content/ and push them to an external Backup Service, like Dropbox, S3, FTP and many more, see list below. With a single backup .zip file you are able to easily restore an installation.
* [MultiSite Clone Duplicator](https://it.wordpress.org/plugins/multisite-clone-duplicator/) - MultiSite Clone Duplicator adds a "Duplicate Site" functionality to your network installation. It allows you to clone any site of your network into a new one : all data, files, users and roles can be copied.
* [WP-CFM](https://wordpress.org/plugins/wp-cfm/) - WP-CFM lets you copy database configuration to / from the filesystem. Easily deploy configuration changes without needing to copy the entire database. WP-CFM is similar to Drupal's Features module.


#### Marketing
* [Leads] (https://wordpress.org/support/plugin/leads/) - Provides in-depth visitor tracking and list collection + segmentation tools.
* [Calls to Action] (https://wordpress.org/support/plugin/cta/) - Provides template powered ad placement system for calls to action, sponsored adverts, and data collection efforts. 


#### Facebook Ads
* [Pixel Caffeine] (https://wordpress.org/support/plugin/pixel-caffeine/) - The simplest and easiest way to manage your Facebook Pixel needs and create laser focused custom audiences on WordPress.

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

* [Stackexchange](http://wordpress.stackexchange.com/) - WordPress Development Stack Exchange is a question and answer site for WordPress developers and administrators. It's 100% free, no registration required.
* [Tom McFarlin](https://tommcfarlin.com/about/) - A Perspective on Professional WordPress Development
* [Mark on WordPress](https://markjaquith.wordpress.com/) - WordPress puts food on my table.
* [Otto on WordPress](http://ottopress.com/) - You have to use an Ottopress to get fresh squeezed Otto
* [Nacin](http://nacin.com/) - WordPress Lead Developer
* [Konstantin Kovshenin](http://kovshenin.com/) - WordPress, Automattic and Open Source
* [Automattic](http://automattic.com/) - We are the people behind WordPress.com, which serves more than 15.8 billion pages a month, as well as a host of other popular services, such as Akismet, Jetpack, and VaultPress.  We are strong believers in Open Source, and the vast majority of our work is available under licenses like the GPL.
* [WPChat](http://www.wpchat.com) - Popular Forum for WordPress discussion.

#### Resources List

* [Awesome WordPress by dropndot](https://github.com/dropndot/awesome-wordpress) - A curated list of Awesome WordPress Theme, Plugins and Framework development Resources and WordPress Communities. 
* [wpmudev.org](http://premium.wpmudev.org/blog/35-resources-for-kick-ass-wordpress-developers/) -35+ Resources to Become a Kick Ass WordPress Developer
* [Toolbox of the Smart WordPress Developer](http://code.tutsplus.com/tutorials/toolbox-of-the-smart-wordpress-developer-series-introduction--cms-23663) - Is the core of WordPress enough for you? No, probably not. Almost all the time, we install WordPress plugins and themes to help build our websites. And that's all right, because WordPress isn't meant to be a one-size-fits-all solution. We do need extra functionality and design elements, and we meet our needs with plugins and themes... and more.
* [Awesome WordPress Developer Tips](https://github.com/Mte90/awesome-wordpress-developer-tips) - Curated list that contain very awesome and ready code, snippets or examples without libraries or external packages made it for developers.
* [Powered By WordPress](https://github.com/minthemiddle/powered-by-wordpress) - Curated list of TOP 1M Alexa ranking websites using WordPress, sorted by category and ranking.

## Books

* [Digging Into WordPress](https://digwp.com/book/) - There is much to learn about the World’s most popular publishing platform. From your first steps of learning about WordPress all the way through securing, customizing, and maintaining your site into the future, this book is packed with truly practical information.
* [The Story of WordPress](https://github.com/WordPress/book) - The history and development of WordPress. The book is currently in version 1, having been written by Siobhan McKeown, edited by Krista Stevens, and with helpful pull requests from members of the community. 

## Contributing

We welcome any contributions to the this awesome list! Please send us a pull request.

* For contribution, [fork the project](https://github.com/miziomon/awesome-wordpress/fork)
* To report a broken link or want to remove one, [use issues](https://github.com/miziomon/awesome-wordpress/issues)
