# Awesome WordPress
A curated list of amazingly awesome WordPress resources, themes, plugins and shiny things.

Inspired by [awesome](https://github.com/sindresorhus/awesome) and [awesome-php](https://github.com/ziadoz/awesome-php).

- [Awesome WordPress](#awesome-wordpress)
	- [Core](#core)
	- [Themes and Framework](#themes-and-framework)
	- [Gutenberg](#gutenberg)
	- [Plugins](#plugins)
		- [Featured Plugins](#featured-plugins)
		- [SEO](#seo)
		- [Dev](#dev-plugins)
		- [Custom Post Type](#custom-post-type)
		- [Installer and Generators](#installer-and-generators)
		- [Images and Media Gallery](#images-and-media-gallery)
		- [Performance](#performance)
		- [E-commerce](#e-commerce)
		- [Security and Management](#security-and-management)
		- [Forms and modules](#forms-and-modules)
		- [Widget](#widget)		
		- [Move and Backup](#move-and-backup)
		- [Marketing](#marketing)
		- [Google Analytics](#google-analytics)
	- [Commandline](#commandline)
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
* [WP MVC](http://wpmvc.org/) - WP MVC is an MVC framework that makes WordPress development faster, easier, and more elegant. It is a full-fledged framework with conventions that are similar to those of Ruby on Rails and CakePHP
* [CherryFramework](https://github.com/CherryFramework/CherryFramework) - Fully responsive design, easy install, steady updates, great number of shortcodes and widgets, integration of Bootstrap functions. All brought to you by Cherry Framework for straightforward experience in website design
* [Gantry Framework](https://github.com/gantry/gantry5) - Next Generation Theme Framework. Gantry was born when the RocketTheme development team wanted to consolidate our extensive set of custom Joomla and WordPress template functionality into a simple, easy to use framework
* [Runway Framework](https://github.com/parallelus/Runway-Framework) - A better way to create WordPress themes. Runway was built for creating WordPress themes and it encompasses both of the classic meanings of "theme framework" as defined by the WordPress developers. But Runway is much more than just a theme framework, Runway is a Theme Development Environment.
* [Kirki](http://kirki.org/) - Kirki is not a framework. It's a Toolkit allowing WordPress developers to use the Customizer and take advantage of its advanced features and flexibility by abstracting the code and making it easier for everyone to create beautiful and meaningful user experiences.
* [Wp Developer Theme](https://github.com/heitorspedroso/wp-developer-theme) - This Theme was developed to be a fast tool in the developer's hands, through it the developer can already create the theme without worrying about the file structure that is already ready and with pre-defined loops without influence in html / css
* [HTML5 Blank](http://html5blank.com/) - The HTML5 WordPress boilerplate theme.
* [Odin WP](http://wpod.in/) - Base-theme developed by WordPress Brasil Group, to help on agile development of themes for WordPress.
* [Landing Pages](https://wordpress.org/support/plugin/landing-pages/) - Framework for building single page presentations with split testing capabilities.
* [Titan Framework](https://github.com/gambitph/Titan-Framework) - The easiest to use WordPress options framework. Titan Framework allows theme and plugin developers to create admin pages, options, meta boxes, and theme customizer options with just a few simple lines of code.
* [create-wp-react-app](https://github.com/matzeeable/wp-reactjs-starter) - WordPress CLI to generate your next modern plugin with the power of REST API, webpack, babel, MobX and MobX State Tree

## Gutenberg
* [Create Guten Block](https://github.com/ahmadawais/create-guten-block) - A zero configuration toolkit for building Gutenberg block plugins.
* [Gutenberg Custom Fields](https://github.com/youknowriad/gcf) - Plugin to create Custom Fields in Gutenberg.
* [Gutenberg Examples](https://github.com/WordPress/gutenberg-examples) - Official WordPress examples of blocks. 
* [Gutenberg Handbook](https://wordpress.org/gutenberg/handbook/) - The official overview of Gutenberg, the new editor for WordPress. 
* [Gutenberg Migration Guide](https://github.com/danielbachhuber/gutenberg-migration-guide) - A guide for WP developers to migrate their themes and plugins to Gutenberg by showing the Gutenberg equivalents. 

* [Gutenblock](https://github.com/crossfield/gutenblock) - An alternative toolkit for creating block plugins. 
* 

## Plugins

### Featured Plugins
*Plugins that have a chance to make it into WordPress core*

* [Shortcake](https://wordpress.org/plugins/shortcode-ui/) - Used alongside add_shortcode, Shortcake supplies a user-friendly interface for adding a shortcode to a post, and viewing and editing it from within the content editor.
* [Gutenberg](https://wordpress.org/plugins/gutenberg/) - The new post and page building experience will make writing rich posts effortless, making it easy to do what today might take shortcodes, custom HTML, or “mystery meat” embed discovery.

#### SEO

* [Redirection](https://wordpress.org/plugins/redirection/) - Redirection is a WordPress plugin to manage 301 redirections and keep track of 404 errors without requiring knowledge of Apache .htaccess files.
* [Yoast SEO](https://wordpress.org/plugins/wordpress-seo/) - Improve your WordPress SEO: Write better content and have a fully optimized WordPress site using Yoast SEO plugin.
* [Broken Link Checker](https://wordpress.org/plugins/broken-link-checker/) - This plugin will monitor your blog looking for broken links and let you know if any are found.

#### Dev Plugins
*Plugins can help in your workflow*

* [Theme Check](https://wordpress.org/plugins/theme-check/) - The theme check plugin is an easy way to test your theme and make sure it's up to spec with the latest theme review standards. With it, you can run all the same automated testing tools on your theme that WordPress.org uses for theme submissions.
* [Query Monitor](https://wordpress.org/plugins/query-monitor/) - Query Monitor is the developer tools panel for WordPress. It enables debugging of database queries, PHP errors, hooks and actions, block editor blocks, enqueued scripts and stylesheets, HTTP API calls, and more.
* [Posts 2 Posts](https://wordpress.org/plugins/posts-to-posts/) - Efficient many-to-many connections between posts, pages, custom post types, users.
* [TGM Plugin Activation](tgmpluginactivation.com/) - TGM Plugin Activation is a PHP library that allows you to easily require or recommend plugins for your WordPress themes (and plugins). It allows your users to install and even automatically activate plugins in singular or bulk fashion using native WordPress classes, functions and interfaces. You can reference pre-packaged plugins, plugins from the WordPress Plugin Repository or even plugins hosted elsewhere on the internet.
* [Revisr](https://wordpress.org/plugins/revisr/) - Revisr allows you to manage your WordPress website with a Git repository. A must have plugin for deploying and managing WordPress using Git repositories.
* [Debug Bar](http://wordpress.org/plugins/debug-bar/) - Adds a debug menu to the admin bar that shows query, cache, and other helpful debugging information.
* [Debug Bar Extender](http://wordpress.org/plugins/debug-bar-extender/) - Extends the debug-bar plugin with additional tabs to measure runtimes between checkpoints and lookup variable content.
* [WP Rollback](https://wordpress.org/plugins/wp-rollback/screenshots/) - Rollback (or forward) any WordPress.org plugin or theme like a boss.
* [Members](https://wordpress.org/plugins/members/) - Members is a plugin that extends your control over your blog. It's a user, role, and content management plugin that was created to make WordPress a more powerful CMS. The foundation of the plugin is its extensive role and capability management system. This is the backbone of all the current features and planned future features.
* [GitHub Updater](https://github.com/afragen/github-updater) - A simple plugin to enable automatic updates to your GitHub, Bitbucket, or GitLab hosted WordPress plugins and themes. It also allows for the remote installation of plugins or themes.
* [Rewrite Rules Inspector](https://wordpress.org/plugins/rewrite-rules-inspector/) - A straightforward WordPress admin tool for inspecting your rewrite rules. View a listing of all your rewrite rules, see which rewrite rules match a given URL (and the priorities they match in), or filter by different sources of rewrite rules. Perform a soft flush of your rewrite rules to regenerate them.
* [CMB2](https://wordpress.org/plugins/cmb2/) - CMB2 is a metabox, custom fields, and forms library for WordPress that will blow your mind.
* [Ship](http://ship.getherbert.com/) - Tag a release on GitHub and have it automatically shipped to the official WordPress.org plugin SVN
* [Simply Show Hooks](https://wordpress.org/plugins/simply-show-hooks/) - Simply Show Hooks helps theme and plugin developers to quickly see where all the action and filter hooks are on any WordPress page.
* [WP Inspect](https://wordpress.org/plugins/wp-inspect/) - The WP Inspect plugin visually annotates pages with the actions & filters (hooks) invoked during the request life cycle.
* [Timber](https://github.com/timber/timber) - Add [Twig](http://twig.sensiolabs.org/doc/templates.html) templating capabilities to your theme and keep your template code separate from your PHP.
* [Child Theme Check](https://wordpress.org/plugins/child-theme-check/) - Warns you about outdated template files in your child theme and shows a diff view of the changes between parent and child theme template.
* [One-Click Child Theme](https://wordpress.org/plugins/one-click-child-theme/) - Adds a Theme option to any active theme allowing you to make a child theme.


### Custom Post Type

* [Custom Post Type UI](https://wordpress.org/plugins/custom-post-type-ui/) - Custom Post Type UI provides an easy to use interface for registering and managing custom post types and taxonomies for your website.
* [Toolset Types](https://wordpress.org/plugins/types//) - Toolset Types let’s you add custom post types, custom fields and custom taxonomies to the WordPress admin. A convenient dashboard lets you control everything from one place.
* [Pods](https://wordpress.org/plugins/pods/) - Manage all your custom content needs in ONE location with the Pods Framework. You can create and edit custom post types, taxonomy, fields and extend existing WordPress objects like users, media, posts and pages or extend other plugins’ custom post types — all from Pods.
* [WordPress Creation Kit](https://wordpress.org/plugins/wck-custom-fields-and-custom-post-types-creator/) - WordPress Creation Kit consists of three tools that can help you create and maintain custom post types, custom taxonomies and most importantly, custom fields and metaboxes for your posts, pages or CPT’s.
* [MB Custom Post Type](https://wordpress.org/plugins/mb-custom-post-type/) - MB Custom Post Type helps you to create and manage custom post types and custom taxonomies easily in WordPress by providing an easy-to-use interface in the admin area.
* [Custom Post Type Permalinks](https://wordpress.org/plugins/custom-post-type-permalinks/) - Custom Post Type Permalinks lets you edit the permalink structure of custom post type


#### Installer and Generators

* [WP Quick Install](http://wp-quick-install.com/) - WordPress installation could be long: downloading, decompressing, uploading, plugins and themes installation. WP Quick Install will take care all of this things. Simply upload this tiny script where you want to install WordPress
* [GenerateWP](http://generatewp.com/) - The easiest and the fastest way to create custom and high quality code for your WordPress project using the latest WordPress coding standards and API's.
* [FakerPress](https://wordpress.org/plugins/fakerpress/) - FakerPress is a clean way to generate fake and dummy content to your WordPress, great for developers who need testing

#### Images and Media Gallery
*All about media items management*

* [Enhanced Media Library](https://wordpress.org/plugins/enhanced-media-library/) - A better management for WordPress Media Library
* [Imsanity](https://wordpress.org/plugins/imsanity/) - Imsanity automatically resizes huge image uploads. Are contributors uploading huge photos? Tired of manually scaling? Imsanity to the rescue!
* [Resize Image After Upload](https://wordpress.org/plugins/resize-image-after-upload/) - Behind-the-scenes plugin to automatically resize images when uploaded, restricting size to within specified maximum h/w. Uses standard WP functions.
* [Regenerate Thumbnails](https://wordpress.org/plugins/regenerate-thumbnails/) - Regenerate Thumbnails allows you to regenerate the thumbnails for your image attachments. This is very handy if you've changed any of your thumbnail dimensions (via Settings -> Media) after previously uploading images or have changed to a theme with different featured post image dimensions.
* [Enable Media Replace](https://wordpress.org/plugins/enable-media-replace/) - Enables replacing attachment files by simply uploading a new file in the media library edit view.
* [Multiple Post Thumbnails](https://wordpress.org/plugins/multiple-post-thumbnails/) - Adds multiple post thumbnails to a post type. If you've ever wanted more than one Featured Image on a post, this plugin is for you.
* [Media from FTP](https://wordpress.org/plugins/media-from-ftp/) - Register to media library from files that have been uploaded by FTP.
* [WP Tiles](https://wordpress.org/plugins/wp-tiles/) - Add beautiful, fully customizable post tiles or tiled galleries anywhere on your WordPress site easily with WP Tiles.
* [Wanna Isotope](https://wordpress.org/plugins/wanna-isotope/) - A plugin to easily build Isotope/Masonry layouts with any content (posts, pages or custom post types). Responsive grids, filterable content.
* [Polaroid Gallery](https://wordpress.org/plugins/polaroid-gallery/) - Polaroid Gallery is a CSS3 & jQuery Image Gallery plugin for WordPress Media Library. It is used to overlay images as polaroid pictures on the current page or post and uses WordPress Media Library. Using Polaroid Gallery you add unique view for your blog posts. Polaroid Gallery adds feeling of old good times.
* [Fly Dynamic Image Resizer](https://wordpress.org/plugins/fly-dynamic-image-resizer/) - Reduce disk space and upload time by having your images generated in custom sizes dynamically, on-the-fly.
* [Sirv Image CDN](https://wordpress.org/plugins/sirv/) - Optimize and resize images on-the-fly with Sirv's Image CDN. Manipulate images by simply changing the URL. 

#### Performance

* [WP-Optimize](https://wordpress.org/plugins/wp-optimize/) - Simple but effective plugin allows you to extensively clean up your WordPress database and optimize it without doing manual queries.
* [P3](https://wordpress.org/plugins/p3-profiler/) - This plugin creates a profile of your WordPress site's plugins' performance by measuring their impact on your site's load time.  Often times, WordPress sites load slowly because of poorly configured plugins or because there are so many of them. By using the P3 plugin, you can narrow down anything causing slowness on your site.
* [Plugin Load Filter](https://wordpress.org/plugins/plugin-load-filter/) - Although have installed a lot of plugins, if you do not want to activate for all of the pages, you will be able to deactivate unnecessary plugins of each individual page. Through the filter activation of plugins, you can speed up the display response.
* [Autoptimize](https://wordpress.org/plugins/autoptimize/) - Autoptimize is an effective performance tool that speeds up a website by optimizing JS, CSS, images (incl. lazy-load), HTML and Google Fonts, asyncing JS, removing emoji cruft and more.

#### E-commerce

* [Hubaga](https://github.com/picocodes/hubaga/) - Hubaga is a lightweight eCommerce plugin for developers. It was has a lot of optimisation that increase your conversion rates such as a single-field checkout and instacheck.
* [Easy Digital Downloads](https://wordpress.org/plugins/easy-digital-downloads/) - Easy Digital Downloads is a complete e-commerce solution for selling digital products in a light, performant, and easy to use plugin. Rather that attempting to provide every feature under the sun, Easy Digital Downloads makes selling digital simple and complete by providing just the features you need.
* [WooCommerce](https://wordpress.org/plugins/woocommerce/) - Transform your WordPress website into a thoroughbred eCommerce store. Delivering enterprise-level quality and features, backed by a name you can trust. Say "hello" to the WooCommerce eCommerce plugin.

#### Security and Management
*Antispam, prevent brute force, ecc*

* [GoodBye Captcha](https://wordpress.org/plugins/goodbye-captcha/) - An extremely powerful anti-spam plugin that blocks Spam-bots without annoying captcha images.
* [Lockdown WP Admin](https://wordpress.org/plugins/lockdown-wp-admin/) - Lockdown WP Admin conceals the administration and login screen from intruders. It can hide WordPress Admin (/wp-admin/) and and login (/wp-login.php)
* [MainWP](https://mainwp.com/) - Self-hosted open source manager for maintaining your WordPress sites from one location.
* [Stealth Login Page](https://www.wordpress.org/plugins/stealth-login-page/) - Protect your dashboard without editing the .htaccess file -- the FIRST one that completely blocks remote bot login requests.
* [Antispam Bee](https://wordpress.org/plugins/antispam-bee/) - Say Goodbye to comment spam on your WorddPress blog or website. Antispam Bee blocks spam comments and trackbacks effectively and without captchas. It is free of charge, ad-free and compliant with European data privacy standards.
* [Stream](https://wordpress.org/plugins/stream/) - Stream is the easiest and safest way to track content changes happening to your WordPress site and then view them in beautifully organized detail.
* [Simple Login Log](https://wordpress.org/plugins/simple-login-log/) - This plugin keeps a log of WordPress user logins. Offers user and date filtering, and export features.
* [iThemes Security](https://wordpress.org/plugins/better-wp-security/) - Take the guesswork out of WordPress security. iThemes Security offers 30+ ways to lock down WordPress in an easy-to-use WordPress security plugin.
* [Sucuri Security – Auditing, Malware Scanner and Security Hardening](https://wordpress.org/plugins/sucuri-scanner/) - It combines features:Remote Malware Scanning,File Integrity Monitoring, Security Activity Auditing, Blacklist Monitoring etc..
* [Easy Updates Manager](https://wordpress.org/plugins/stops-core-theme-and-plugin-updates/) - Easy Updates Manager is a light yet powerful plugin which enables you to manage all types of updates on your single site install or in WordPress Multisite. With loads of settings making endless possibilities for configuration, Easy Updates Manager is an obvious choice for anyone wanting to take control of their websites updates.
* [Wordfence Security – Firewall & Malware Scan](https://wordpress.org/plugins/wordfence/) - Wordfence includes an endpoint firewall and malware scanner that were built from the ground up to protect WordPress. Web Application Firewall identifies and blocks malicious traffic. Built and maintained by a large team focused 100% on WordPress security. Malware scanner checks core files, themes and plugins for malware, bad URLs, backdoors, SEO spam, malicious redirects and code injections.
* [CloudFlare WAF and CDN](https://www.cloudflare.com/integrations/wordpress/) = CloudFlare offers managed WAF (Web Application Firewall) rules for WordPress, CDN, and DDOS mitigation for WordPress sites

#### Dashboard

* [Frontend Dashboard](https://wordpress.org/plugins/frontend-dashboard/) - Frontend Dashboard is bundled with the huge list of custom features which can easily customise the User profile, Posts, Login, Register, Custom roles on the custom front page.


#### Forms and modules

* [Caldera Forms](https://wordpress.org/plugins/caldera-forms/) - A different kind of WordPress form builder. With an intuitive drag and drop interface -– based on a responsive grid -- and a wide range of add-ons, it’s never been easier to create forms for your WordPress site that look great on any device, thanks to Caldera Forms.
* [Ninja Forms](https://wordpress.org/plugins/ninja-forms/) - Ninja Forms is the easiest way to build any form you need for your WordPress website. No longer mess with code or worry about made-up limitations. Create the form you want, when you want with a simple drag and drop interface provided by the very powerful Ninja Forms framework.

#### Widget

* [Widget Options](https://wordpress.org/plugins/widget-options/) - Get Better Control over your Widgets. Easily show or hide WordPress widgets on specified pages & devices and/or assign custom alignment.
* [Widget Logic](https://wordpress.org/plugins/widget-logic/) - This plugin gives every widget an extra control field called "Widget logic" that lets you control the pages that the widget will appear on. The text field lets you use WP's Conditional Tags, or any general PHP code.
* [Widget Output Cache](https://wordpress.org/plugins/widget-output-cache/) - Use PHP output buffering to extract widget output and store it into WordPress transients for faster retrieval. It also adds a checkbox to widget controls to exclude it from being cached.


#### Move and backup
*If you need to move your installation*

* [All-in-One WP Migration](https://wordpress.org/plugins/all-in-one-wp-migration/) - The plugin allows you to export your database, media files, plugins, and themes. You can apply unlimited find/replace operations on your database and the plugin will also fix any serialization problems that occur during find/replace operations.
* [Duplicator](https://wordpress.org/plugins/duplicator/) - Duplicate, clone, backup, move and transfer an entire site from one location to another.
* [UpdraftPlus Backup and Restoration](https://wordpress.org/plugins/updraftplus/) - UpdraftPlus simplifies backups (and restoration). Backup into the cloud (Amazon S3 (or compatible), Dropbox, Google Drive, Rackspace Cloud, DreamObjects, FTP, Openstack Swift, UpdraftPlus Vault and email) and restore with a single click. Backups of files and database can have separate schedules.
* [BackWPup](https://wordpress.org/plugins/backwpup/) - The backup plugin BackWPup Free can be used to save your complete installation including /wp-content/ and push them to an external Backup Service, like Dropbox, S3, FTP and many more, see list below. With a single backup .zip file you are able to easily restore an installation.
* [MultiSite Clone Duplicator](https://wordpress.org/plugins/multisite-clone-duplicator/) - MultiSite Clone Duplicator adds a "Duplicate Site" functionality to your network installation. It allows you to clone any site of your network into a new one : all data, files, users and roles can be copied.
* [WP-CFM](https://wordpress.org/plugins/wp-cfm/) - WP-CFM lets you copy database configuration to / from the filesystem. Easily deploy configuration changes without needing to copy the entire database. WP-CFM is similar to Drupal's Features module.


#### Marketing
* [Leads](https://wordpress.org/support/plugin/leads/) - Provides in-depth visitor tracking and list collection + segmentation tools.
* [Calls to Action](https://wordpress.org/support/plugin/cta/) - Provides template powered ad placement system for calls to action, sponsored adverts, and data collection efforts.

#### Google Analytics
* [Analytify](https://wordpress.org/plugins/wp-analytify/) - Google Analytics Dashboard for WordPress – by Analytify makes simple and complete Google Analytics for everywhere in WordPress (posts, pages and custom post types)
* [MonsterInsights](https://wordpress.org/plugins/google-analytics-for-wordpress/) - MonsterInsights, a complete Google Analytics for WordPress plugin that’s EASY and POWERFUL.

## Commandline

* [WP-CLI](http://wp-cli.org/) - WP-CLI is a set of command-line tools for managing WordPress installations. You can update plugins, set up multisite installs and much more, without using a web browse.
* [WPScan](http://wpscan.org/) - WPScan is a black box WordPress vulnerability scanner.

## Resources

#### Theme Customizer
* [Multi Image Control](https://github.com/lucatume/multi-image-control) - A Theme customizer control allowing selection and sorting of multiple images.

#### Classes
* [wp-custom-post-type-class](https://github.com/jjgrainger/wp-custom-post-type-class) - A PHP Class for creating Wordpress Custom Post Types easily
* [wp-bootstrap-navwalker](https://github.com/twittem/wp-bootstrap-navwalker) -  A custom WordPress nav walker class to fully implement the Twitter Bootstrap 3.0+ navigation style in a custom theme using the WordPress built in menu manager.

#### Knowhow
* [10up Engineering Best Practices](http://10up.github.io/Engineering-Best-Practices/) - As a company, we strive to provide websites and components that yield a top-notch user experience. In order to improve efficiency, we need to standardize what we use and how we use it. Standardizing our tools, frameworks, libraries, style, version control, and even languages will allow us to understand better the inner workings of someone else’s project and produce better solutions ourselves.

#### Websites

* [Stackexchange](http://wordpress.stackexchange.com/) - WordPress Development Stack Exchange is a question and answer site for WordPress developers and administrators. It's 100% free, no registration required.
* [Tom McFarlin](https://tommcfarlin.com/about/) - A Perspective on Professional WordPress Development
* [Mark on WordPress](https://markjaquith.wordpress.com/) - WordPress puts food on my table.
* [Otto on WordPress](http://ottopress.com/) - You have to use an Ottopress to get fresh squeezed Otto
* [Nacin](http://nacin.com/) - WordPress Lead Developer
* [Konstantin Kovshenin](http://kovshenin.com/) - WordPress, Automattic and Open Source
* [Automattic](http://automattic.com/) - We are the people behind WordPress.com, which serves more than 15.8 billion pages a month, as well as a host of other popular services, such as Akismet, Jetpack, and VaultPress.  We are strong believers in Open Source, and the vast majority of our work is available under licenses like the GPL.
* [WPChat](http://www.wpchat.com) - Popular Forum for WordPress discussion.
* [WordPress Tavern](https://wptavern.com/) - WPTavern has news and a weekly podcast on Wordpress and its ecosystem.
* [Quora](https://www.quora.com/topic/WordPress) - Q&A in Quora for Wordpress users and developers.
* [Wordpress subreddit](https://www.reddit.com/r/Wordpress/) - Subreddit for news, articles and discussion regarding WordPress. For advanced users try the [ProWordpress subreddit](https://www.reddit.com/r/ProWordPress/)
#### Resources List

* [Awesome WordPress by dropndot](https://github.com/dropndot/awesome-wordpress) - A curated list of Awesome WordPress Theme, Plugins and Framework development Resources and WordPress Communities.
* [Programming Community Curated Resources For Learning WordPress](https://hackr.io/tutorials/learn-wordpress)
* [wpmudev.org](http://premium.wpmudev.org/blog/35-resources-for-kick-ass-wordpress-developers/) -35+ Resources to Become a Kick Ass WordPress Developer
* [Toolbox of the Smart WordPress Developer](http://code.tutsplus.com/tutorials/toolbox-of-the-smart-wordpress-developer-series-introduction--cms-23663) - Is the core of WordPress enough for you? No, probably not. Almost all the time, we install WordPress plugins and themes to help build our websites. And that's all right, because WordPress isn't meant to be a one-size-fits-all solution. We do need extra functionality and design elements, and we meet our needs with plugins and themes... and more.
* [Awesome WordPress Developer Tips](https://github.com/Mte90/awesome-wordpress-developer-tips) - Curated list that contain very awesome and ready code, snippets or examples without libraries or external packages made it for developers.
* [Powered By WordPress](https://github.com/minthemiddle/powered-by-wordpress) - Curated list of TOP 1M Alexa ranking websites using WordPress, sorted by category and ranking.
* [Best WordPress Hosting Providers Compared](https://thishosting.rocks/best-wordpress-hosting/) - Detailed article/comparison of the best WordPress hosting providers.


## Books

* [Digging Into WordPress](https://digwp.com/book/) - There is much to learn about the World’s most popular publishing platform. From your first steps of learning about WordPress all the way through securing, customizing, and maintaining your site into the future, this book is packed with truly practical information.
* [The Story of WordPress](https://github.com/WordPress/book) - The history and development of WordPress. The book is currently in version 1, having been written by Siobhan McKeown, edited by Krista Stevens, and with helpful pull requests from members of the community.

## Contributing

We welcome any contributions to the this awesome list! Please send us a pull request.

* For contribution, [fork the project](https://github.com/miziomon/awesome-wordpress/fork)
* To report a broken link or want to remove one, [use issues](https://github.com/miziomon/awesome-wordpress/issues)
