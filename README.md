WordPress FTP Full Backup
=========================

WordPress FTP Full Backup takes browser based FTP backup of WordPress plus other folders. Basically it uses PHP ZipArchive class ZipArchive(); which can not be used without shell access directly. The first script checks and shows up your WordPress Installation root. Depending upon the size of your FTP content, it can taken few minutes to few hours to complete the process and will create a zip file on the root where the script is made to run. On the next screen, you will get the option to download it to your computer as well.

== Installation ==

This is a stable backup script, I have not added WordPress Plugin integration yet, its simple but powerful for work with :


1. Upload to the WordPress Installation root or any directory
2. There is nothing to activate. Point towards your-domain.com/run.php
3. Simply follow the on screen instruction, it absolutely looks like default WordPress files. 

== Frequently Asked Questions ==

= No WordPress Installation ? =

This is the first version of the Plugin. Definitely there will be lot of features like premium plugins.

= I heard that these Backup Plugins are mostly paid software ? =

Yes they are. But as you can see, this is a fully free plugin, aditionally many features will be added like uploading to Rackspace Cloud Files with cURL, Amazon S3, auto upload to almost all Free Cloud Storages.

= What is the major difference between this WordPress FTP Full Backup Plugin and Others ? =

This Plugin uses the PHP memory from outside WordPress. This is important for servers with low config. In future, there will be API based integration with WordPress Admin panel, but unlike other plugins it will never put stress on the working WordPress installation.

= What is the recomanded settings for .htaccess ? =

Set your PHP memory limit beyond 512 MB for smooth function. Simply add this line at the begining of your .htaccess file of the root :

php_value memory_limit 1024M

Ask your web host, the limit on PHP. If you can set PHP memory to higher yourself, doing alone will suffice.

== Changelog ==

= 1.0 =

* First version released.

== Other Notes ==

Your Feedback is valuable. This plugin will work even if you have lost access to login to WordPress or it is unsafe to login (in case your site is under attack). 

At any issues, please check the plugin's official support page at : 
http://thecustomizewindows.com/2012/07/wordpress-ftp-full-backup-backup-ftp-to-zip-file/ ; support is free as well.