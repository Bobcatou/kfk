# Patricia Changelog

## 1.2.8 - 19 Sept 2017
* Changed update URL domain to https://9seeds.com
* Changed cache name to make updates from previous versions run more smoothly
* Disabled SSL for cURL, for servers which can't cURL from SSL sites
* Changed URL domain in "Update Downloads and Instructions" to https://9seeds.com
* change widget constructor
### Files Modified
* /style.css
* /lib/functions/update.php
* /lib/widgets/call-to-action.php
* /lib/widgets/widget-social.php
---


## 1.2.7 - 11 Aug 2017
* Changed update URL to HTTPS
* Changed cache name to make updates from previous versions run more smoothly
* Disabled SSL for cURL, for servers which can't cURL from SSL site
* Changed URL in Update Downloads and Instructions to HTTP       

### Files Modified
* /style.css
* /lib/functions/update.php

---

## 1.2.6 - 10 Nov 2016 and 08 Dec 2016
* Fix form button position          

### Files Modified
* /style.css  
* /style-rtl.css   

---

## 1.2.5 - 05 Mar 2016
* Fix bug in Soliloquy caption heading      
* Fix for compatibility with new WordPress comment form  
* Change Genesis Simple Sidebar related logic to be compatible with Genesis 2.2.7        

### Files Modified
* /style.css  
* /style-rtl.css   
* /lib/structure/sidebar.php  

---

## 1.2.4 - 07 Sep 2015
* Fix bug in Call to Action widget    
* Fix bug in Social Widget
* Add full Genesis 2.2+ accessibility support  
* Switch to built-in Genesis mobile responsive meta tag     
* Various minor bug fixes      

### Files Modified
* /style.css  
* /style-rtl.css   
* /functions.php  
* /wpml-config-xml (new file added)  
* /languages/*  
* /lib/init.php    
* /lib/widgets/call-to-action.php  
* /lib/widgets/widget-social.php  

---

## 1.2.3 - 21 Aug 2015
* Now fully compatible with the WPML plugin    
* Fix for widget compatibility with WordPress 4.3
* Updated Soliloquy install script  
* Added missing strings to text domain  
* Improved Internet Explorer compatibility  
* Improved compatibility with SSL secure sites    
* Various minor bug fixes      

### Files Modified
* /style.css  
* /style-rtl.css   
* /functions.php  
* /wpml-config-xml (new file added)  
* /languages/*  
* /lib/init.php   
* /lib/plugins/class-tgm-plugin-activation.php  
* /lib/plugins/plugins.php  
* /lib/widgets/call-to-action.php  
* /lib/widgets/widget-social.php  
* /lib/widgets/wsm-featured-page.php  
* /lib/widgets/wsm-featured-post.php  

---

## 1.2.2 - 30 Apr 2015
* Bug fix for Soliloquy plugin CSS change    
* Update Soliloquy install script  
* Convert to new Gravity Forms built-in placeholder functionality  
* Changed comment form for placeholders without script  
* Enable shortcodes in footer settings  
* Add missing strings to text domain    
* Remove REM units from style sheet for simplicity  
* Remove unused files  
* Misc. bug fixes     

### Files Modified
* /style.css  
* /style-rtl.css   
* /functions.php  
* /languages/*  
* /lib/init.php  
* /lib/admin/patricia-theme-settings.php  
* /lib/functions/gforms-placeholder.php (file removed)  
* /js/jquery.cycle.all.min.js (file removed)  
* /js/modernizer.min.js  (file removed)  
* /lib/plugins/class-tgm-plugin-activation.php  
* /lib/plugins/plugins.php  
* /lib/structure/comment-form.php  
* /lib/structure/footer.php  
* /lib/widgets/widget-social.php  
* /lib/widgets/wsm-featured-page.php  
* /lib/widgets/wsm-featured-post.php  

---

## 1.2.1 - 13 Nov 2014
* Bug fix for imported fonts  

### Files Modified
* /style.css  
* /style-rtl.css   

---

## 1.2.0 - 12 Nov 2014
* Added internationalization (i18n) support by wrapping all front-end facing text strings in a translation function  
* Added text domain in style.css and loaded text domain in functions.php  
* Added .pot file as basis for translations  
* Add .rtl stylesheet to be conditionally enqueued (instead of style.css) when WordPress language is set to an RTL script  

### Files Modified
* /style.css  
* /style-rtl.css (new file added)  
* /functions.php  
* /languages/*.pot (new directory and file added)  

---

## 1.1.4 - 29 Sept 2014
* Improved CSS for Genesis Column Classes
* Update plugin activation code to use remote location for Soliloquy install
* Removed depreciated function in theme update notification

### Files Modified
* /style.css
* /lib/functions/update.php
* /lib/plugins/plugins.php
* /lib/plugins/class-tgm-plugin-activation.php
* /lib/plugins/packaged/ (dirctory removed)
* /lib/plugins/packaged/soliloquy.zip  (file removed)

---

## 1.1.3 - 05 Sept 2014
* Fix Gravity Forms placeholder script to deconflict with Soliloquy in WordPress 4.0
* Improved cache handling of theme updates
* Update Soliloquy to 2.3.5

### Files Modified
* /style.css (version number only)
* /lib/init.php
* /lib/functions/gforms-placeholder.php
* /lib/plugins/packaged/soliloquy.zip

---

## 1.1.2 - 14 Jul 2014
* Fix bug in Call to Action widget

### Files Modified
* /style.css (version number only)
* /lib/widgets/call-to-action.php

---

## 1.1.1 - 11 Jul 2014
* Fix Genesis Simple Sidebar compatibility bug
* Fix bug in Call to Action widget
* Fix embeded content mobile displays
* Fix bug in theme update instctuctions display
* CSS tweak for donate button background fallback
* Updated Soliloquy license key functionality
* Removed anonymous data tracking system
* Updated Soliloquy to 2.3.3

### Files Modified
* /style.css
* /lib/init.php
* /lib/admin/patricia-theme-settings.php
* /lib/functions/theme-optin.php (file removed)
* /lib/functions/update.php
* /lib/structure/sidebar.php
* /lib/widgets/call-to-action.php
* /lib/plugins/packaged/soliloquy.zip

---

## 1.1.0 - 16 Dec 2013
* New method for Gravity Forms field placeholders
* Added dashboard notification system for new theme updates
* Added anonymous data tracking system
* Updated screenshot with larger image
* Updated Soliloquy to 1.5.7

### Files Modified
* /style.css (version number only)
* /functions.php
* /screenshot.jpg (file removed)
* /screenshot.png (new file added)
* /README.txt (file removed)
* /README.md (new file added)
* /lib/init.php
* /lib/admin/patricia-theme-settings.php
* /lib/functions/gforms-placeholder.php (new file added)
* /lib/functions/theme-optin.php (new file added)
* /lib/functions/update.php (new file added)
* /lib/js/clear_form_fields.js (file removed)
* /lib/js/modernizr.min.js (new file added)
* /lib/structure/comment-form.php (new file added)
* /lib/plugins/packaged/soliloquy.zip

---

## 1.0.1 - 27 Nov 2013
* Fix CSS bug in home page slider
* Fix CSS bug in footer navigation
* Remove unused redundant code
* Fixed some whitespace issues in code
* Update Soliloquy package to version 1.5.6.3

### Files Modified
* /style.css
* /functions.php
* /lib/plugins/packaged/soliloquy.zip

---

## 1.0.0 - 12 Nov 2013
* Initial theme release
